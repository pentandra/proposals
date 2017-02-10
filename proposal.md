---
title: A proposal for scholarlycommons.org
created_at: 2017-02-04
amount_usd: TBD
---

# What is needed for a Scholarly Commons?

Decision trees are a good start, but they are not enough to create a viable
alternative to the current system. We need a viable alternative that is
distinct and comprehensive enough to be considered an alternative system of
scholarly communication. We also need this alternative system to be so much
better than the alternative, so that there is motivation to adopt new
practices. The Scholarly Commons is a culture, but we're missing critical
infrastructure to tie everything together and allow the culture of the
Scholarly Commons to thrive. 

Also, it is not enough for disciplines to 'spin up their own variety of
commoning' ([Bruce Caron]). In order to tie everything together and avoid
perpetuating disciplinary silos, we need 'technical duct tape' (also Bruce)
harnessing the power of the Web to provide the machine interoperability needed
to tie together disciplines, cultures, languages, questions, answers, inputs,
outputs, data, sources of data, evidences, standards, principles, practices,
tools, projects, organizations, funders, individuals, interfaces, and
expectations in a unified way.

The work is composed of three interrelated subprojects:

; [Open-research curation system](#open-research-curation-system)
: Exposes and preserves the researcher's process

; [Research guides](#research-guides)
: Machine-processable decision trees that guide research

; [Branding and visualization](#branding-and-visualization)
: An integrative approach to the design and functionality of scholarlycommons.org

Value: $125k ($100 per hour base rate × 50 hours per week × 22 weeks)

Cost: TBD (see [caveat])

# Open-research curation system

_See [Defining the Commons Platform][DtheCP] and [my 400 word response][400] for
some background thoughts, though this is still a moving target._

The most fundamental purpose of this subproject is to provide a place to
explore and eventually answer the question, _'What is the Scholarly Commons?'_.
It will build upon all the work that we have done in the past as a steering
committee and working group, as well as the outputs from the workshops in
Madrid, Portland, and San Diego. Going forward, it will provide an open and
even playing field for anyone to contribute to the definition of the Scholarly
Commons.

The output of this subproject will be a modern, reusable, archetypical research
system, aligned with the culture of the Scholarly Commons, that could be used
for accomplishing Concept II (focused on the research process) of [Doable
pathways to the Scholarly Commons][Pathways], discussed during the San Diego
workshop. The Scholarly Commons should be a jumping-off point to new ways of
working together, taking the best ideas of how to do scholarship in a modern
setting, setting aside as many of the undesirable social and cultural
limitations as possible. According to Diffusion of Innovations we need a viable
alternative that can be trialed, and I'm not convinced that we have an existing
viable alternative, hypothetical or otherwise.

One of my greatest takeaways from the main track of the San Diego workshop was
that because the research processes were made explicit and studied this way, it
allowed the workshop attendees to reason about, find patterns, and learn from
them. With this end in mind, a central feature of this system will be exposing
the researcher's path explicitly. From the researcher's perspective, the entire
research process could be viewed as a sequence of decisions. These decisions
and the process of how they came about should form the basis of research
publication and collaboration.

If we don't make that process explicit, how will we be able to share,
reproduce, or assess the differences? If we keep the process implicit, or even
leave it to post facto analysis to attempt to reveal it all alone, we are
missing the whole point, and we end up not very far from where we are now:
publishing _about_ the research, instead of publishing research, and our
ability to effectively common will be impeded. As Jeffrey Schnapp says in his
presentation on [Knowledge Design]: the process _is_ the product. 

The general approach will build on the early work of on Issue-Based Information
Systems ([IBIS]), Knowledge Media Institute's [Scholonto] later ideas, other
thoughts from the brightest minds on the future of scholarly communication, and
our own research on how to fit this all together that we have conducted over
the past several years. It will implement the best thinking on evidence and
argumentation in a collaborative research context, bringing in bits of
knowledge from around the Web, including existing declarations (building on
WP1), and mapping that knowledge together (building on WP2), all within a
beautiful, simple, and intuitive experience.

Wherever possible, this system will integrate with and connect current tools,
standards, and implementations instead of replacing existing functionality.

## Tentative high-level components

* Persistent identifiers for:
  * Researchers and other individuals (authentication via [ORCiD] and the
    IndieAuth protocol (or another Web-centric equivalent))
  * Organizations and groups (via [Grid])
  * Concepts
  * Decisions
  * Questions
  * Everything else uniquely identifiable :-)
* Design an ontology that describes the process of decision-making in research
  based upon ideas from [DecisionML], [IBIS], and [Scholonto], and relate it to
  the recent [Design Intent Ontology][dio]
* Develop a user experience around the flow of research on the Scholarly
  Commons, including questions, peer-to-peer interactions, and versioning, that
  will form the basis of discourse as well as inform the development of the
  above ontology
* Create integrations with common tools, starting with the tools that we used
  during the course of this program, such as Google Docs, hypothes.is, Slack,
  and Trello
* stuff would happen via Hydra

## Basic research flow

The basic premise is that our current outputs, approaches, and implementations,
such as papers and working groups, are inherently closed, and not compliant
with the principles of the Scholarly Commons. We need a way to open the process
so that people can get involved and can collaborate without the barrier of time
or place.

# Research guides

_See [Infrastructure Map Proposal][IMP] for some background thoughts, though
those ideas have evolved into something much more simple and distributed,
thanks to the discussion on decision trees that came out of the San Diego
workshop._

* the process trees would be a scholarly output of their own (WP3)
* each workflow would be exposed as a community best practice for a specific situation
* and also as the actual 'what happened' for a researcher
* these two would form a processual backbone of the Scholarly Commons
* and would make research reproducible

We've started by selecting the entities of data and software tools, but
tracking decisions could be useful during other parts of the research process.

myExperiment and Taverna

Explicate the development of every type of research output

Research guides. At any point, you should be able to see what the plan was (or
that there was no plan), and how plan that differed from what actually happened.

Semi-automating

Reuseable workflows

## Macro guides

## Micro guides

# Branding and visualization

_See [Branding the Scholarly Commons][BtheSC] for some background thoughts,
though those thoughts have evolved since then somewhat. This is the only part
of this system that is not reusable._

Logo

## Visualization

Connects things that have previously been unconnected.

The visualization helps people see how the commons works—how the resources of
the commons interact.

Viz accessible to machines.

# Other functionalities

* Web pages
* Blog

# Governance

I am envisioning this project to be more of an ongoing partnership, rather than
a one-time outsourcing to a contractor or vendor. I know that we are all coming
at this from different places, and are not yet in agreement even as to what we
would like the Scholarly Commons to be. We (Pentandra) could do this on our
own, but I don't see any real advantage to doing it that way, at least not when
there is the possibility of doing it together. :-)

Pentandra will manage the development process, reporting weekly during the
steering group calls, and 

Not advisory board, but invitations to collaborate directly.

I'm open to options here. 

# Maintenance

# Accessibility

# A tentative development schedule for scholarlycommons.org

The work will be organized into 11 two-week sprints. All three subprojects will
be developed incrementally and simultaneously, as they will inform each other
during the development process.

* Sprint 1: Feb 13–24
* Sprint 2: Feb 27–Mar 10
* Sprint 3: Mar 6–Mar 17
* Sprint 4: Mar 20–Mar 31

(Spring Break: Apr 3–Apr 7)

* Sprint 5: Apr 10–Apr 21 (Everything desired for the CC Summit must be
  completed by the end of this sprint)
* Sprint 6: Apr 24–May 5
* Sprint 7: May 8—May 19
* Sprint 8: May 22–Jun 2
* Sprint 9: Jun 5—Jun 16

(Summer Vacation at Yellowstone: Jul 3—Jul 7)

* Sprint 10: Jun 19–Jun 30
* Sprint 11: Jul 10–Jul 21

# Future directions

* As more decision trees are curated and research done, use machine learning to
  find patterns of commoning and then generate decision trees based on these
  patterns, with the goal of assisting future research or decision tree design
* Use A/B testing to compare processes, ideas, and user interactions to find
  what works best

[dio]: <https://w3id.org/dio>
[IBIS]: <> "Issue-based Information Systems"
[DecisionML]: <https://www.w3.org/2005/Incubator/decision/wiki/Draft_Final_Report>
[Scholonto]: <http://projects.kmi.open.ac.uk/scholonto/>
[Hydra]: <https://hydra-cg.com>
[Knowledge Design]: <https://via.hypothes.is/http://jeffreyschnapp.com/wp-content/uploads/2011/06/HH_lectures_Schnapp_01.pdf>
[Verborgh]: <https://ruben.verborgh.org/phd/>
[DtheCP]: <https://docs.google.com/document/d/1iZplXo3meTR5164fbkk40-CrauZk89PgxvsZ_jDPTCQ/edit> "Defining the Commons Platform Proposal"
[IMP]: <https://docs.google.com/document/d/1ciLAzl65ppmJ_GOPrpkA-s8XXLBmqocME1KkQ5adgUc/edit> "Infrastructure Map Proposal"
[BtheSC]: <https://docs.google.com/document/d/1YIxxMpcOni7alThkdVvvrnc_edKay2Ow4kiRwBDTQrs/edit> "Branding the Scholarly Commons"
[Bruce Caron]: <https://cybersocialstructure.org/2016/10/18/think-of-science-like-an-incurable-intellectual-disease-part-3/>
[caveat]: <https://groups.google.com/a/force11.org/d/msg/steering-scwg/tE8yA-zEGrU/F2yMIEuFCAAJ>
[Pathways]: <> "Doable pathways to the Scholarly Commons"
