---
title: Usability
slug: usability
author: Eriol Fox
---
## What does usability mean to people contributing to, building and designing for Science and Research OSS? What does it mean to designers outside of the science and research field?

Usability, like Accessibility discussed in a different section ([accessibility](/part-2-project-operations/accessibility/)), is not an unknown term in the Science and Research OSS space, yet, like Accessibility, it has many different interpretations, implications and applications depending on the perspective and motivations of the individual approaching the topic of Usability.

Below, a designer who works across many Python related SROSS tools describes where they sense the use of the term Usability is coming from the term being more pervasive in the general vocabulary of software and OSS but that the practical application of Usability falls short in their opinion.

_“Usability is not necessarily an uncommon word, but something I feel like I see a lot is they kind of are picking up vocabulary, whether that's from me, whether that's from it being more present on tech spaces in the internet now, and they're reading blogs… it's very rare that I feel like it's being used as accurately as I would like it”_

From our exploration and conversations we largely found that Usability was described by non-designers in the Science and Research OSS space as, discoverability of features and data (which we explore in some detail in the Onboarding section of this document), terminology and it’s appropriate use, making features and functions ‘easy’ (yet they struggle to describe what easy means contextually), and, connected to accessibility, to ensure that everyone and anyone regardless of background and prior knowledge have the opportunity to ‘access’ and ‘use’ the OSS.

Important to note in this introduction to the topic of Usability in Science and Research OSS, is that the wider infrastructure that supports OSS and Science and Research does not invest in usability in the ways in which we may come to talk about in this section. Github, Gitlab, secure University data storage systems and various other softwares and applications are usability challenged in their own ways. Some of these organizations invest in usability and design more broadly, but many people, in this research study and beyond, describe the difficulties in learning and understanding the ecosystems that the Science and Research OSS tools exist in.

_“Tech tools themselves have not thought about how to make things usable and friendly. Makes it hard for, eg, undergrads who start thinking about problems and get intimidated by Git. Github is scary - buttons, menus and options…too many, I'm an outsider and it isn’t for me.” _

Here, a Data research Scientist at a lab that incubates numerous open science and research tools speaks to the complexity of the software and tool ecosystem.



A challenge we heard from designers is that they can lack the knowledge of both the larger OSS ecosystems that SROSS exists in as well as the scientific and research purposes therein the OSS. With dedicated learning time and collaborative support the designers were able to understand enough about OSS and the Science/Research to design effectively, but this lack of knowledge and understanding goes both ways.

“I don't think that many of the partners that we've worked with knew what usability testing was” a designer who works in a university based lab describes the OSS team’s lack of knowledge about usability testing processes as they began working together. From these insights we can make the reasonable assumption that there are knowledge gaps from the OSS, Design/Usability and Science/Research perspectives all around to better communicate into the future.

## Usability is important to Science and Research OSS when they consider themselves ‘no longer niche’ (single digit users). When there are more diverse users, or when another stakeholder has expressed interest, is when Usability becomes critical. 

At the point where users are using a tool in the double digits is a stage that most designers would describe as a late stage for usability and UX improvements. This isn’t uncommon in resource constrained proprietary and commercial software, to bring in usability concerns post functioning software. But this does contribute to an aspect often raised throughout the research by our participants that design, usability and accessibility is viewed as laborious, time consuming and difficult to implement. Not surprising given the opportunity to perform usability and UX improvements would have been during the pre-build process.

A scientist and researcher building an OSS citizen science platform describes below the lifecycle of SROSS starting out small and niche and that that is fine as long as it stays as OSS that doesn’t need to serve a purpose beyond a limited number of research papers.

_“Usability doesn’t have to be important, and that’s fine: “because I feel like a lot of academic open source software really starts out in such a small niche. And it's for supporting a single research paper or a series of research papers with no expectation of anyone to really grow this into a project. And I just want to like we be clear that I think that's fine. I think it's a different kind of open source.”_

Many OSS tools will remain in the single digit user bases and there are no obvious ways of knowing if any given OSS project will become a highly sought after tool beyond logical assumptions such as if tools are currently scarce for that need and if the tool has good resource investment.

## Science and Research OSS tool teams, like most OSS tools, have an ‘ideal’ user type and level of proficiency. Most OSS build and maintain for these users or people to become these kinds of users. 

A legacy that seems like it’s been passed on from OSS to Scientific and Research OSS is that there is an ‘ideal’ user. A user that is able to understand all appropriate key terms, functions, commands, particular coding languages or know the way to self-serve that knowledge through a combination of reading documentation (if available), searching out related solutions to problems or learning the processes and skills needed to self-troubleshoot. These are the users of OSS that often reflect those that also build, maintain and configure it. The user best described as ‘myself’ by developers of OSS. This perspective is not as much an attitude that the people we spoke to genuinely have about users but more this legacy ‘ideal’ that has cut through OSS culture by way of directing less skilled and proficient users to ‘read the manual’.

These users do exist, as described below by a lead developer working on a Python package for audio data, there are a good number of people that can get most of the way when using SROSS in the same or similar ways that the core developers would.

_“GUI - long story short, there's a bunch of people that can pick up Python and make a thing that gets 50 to 75% of the way there, but it still doesn't really give you that sort of, you know, like usability or accessibility, that would, that would really be like, I think a game changer for the community.” _

This lead developer, while recognizing that these people exist and there is this pervasive sense through OSS to ‘self serve’ until you can use OSS proficiently, that a GUI (graphical interface) would be a benefit to their project in allowing those that cannot, for whatever reason, self-serve the knowledge needed to operate the OSS like that of the core developers.

A community manager for the various OSS projects that a funder supports and maintains describes below the reliance on norms and knowledge in a community and how this really only suffices until a point where someone gets stuck.

_“In a lot of cases, people are reliant on their knowledge of set of norms in a given community, with a community either being something like whatever scientific Python or the Bioconductor community in R or something, and having a standard set of norms that are kind of like missing stairs, where if you don't understand this one weird thing about how the software is interpreting your data or how you need to interact with the software, then you're going to be completely lost, and deciphering what that missing stair is really, really challenging.” _

In our casual conversations in OSS we found that getting lost is fairly common despite your knowledge of norms and processes and skills. OSS and by extension Science and Research OSS is most often built by a single person or small collection of people that cycle through intensity of activity on an OSS project. These are the people that are likely to have the most comprehensive knowledge of operating that OSS and even if they document incredibly well, there will be quirks in that OSS that others will not understand until they ask. This is where Usability can make a difference. In the period of time where the configurer of the OSS are making judgements and assumptions about general use using their own experiences as a benchmark which are often highly knowledgeable benchmarks.

Adjacent to these findings about how those that build and maintain scientific and research OSS  describe an ideal user is a subtle, almost missed discovery about how usability is described by the scientists and researchers versus how it is described by those that work on usability regularly, such as designers.

Usability was often described as ‘how I want people to use the OSS tool’ or ‘how will we present our tool to users’ as well as questions such as ‘Can users see, understand and use our tool?’ and ‘How the user is viewing the system’. These phrases are subtle but suggest that the tool builders are delivering usable software to the users in the ways in which they believe are the most appropriate ways to use a tool. Put another way, there are ‘most correct ways’ of using the OSS tool and improving the tool’s usability means getting as many users as possible to use the tool in that most correct way.

A designer working out of a university based lab across multiple OSS projects describes the sometimes rigid and protective way that OSS projects can suggest users use a tool.

_“An example is when they have this very specific queries as a way of querying the data. And either you don't, you know, or you don't. And it's, it can be simplified quite easily from a design point of view by using filters that are self explanatory, for instance, but they it's just, I don't want people that don't know about the subject to search the way to find out the way it's, yeah, as you say, it's way protective.”_

Designers however, describe Usability as a process of working together with multiple people involved in the building of the OSS software to best understand the ways in which users want to and will use the tool and ensuring that these workflows and multiple ways of a user achieving a purpose with a tool (in SROSS’s case, solving a scientific or research problem where the OSS tool is part of that solution). 

A designer who worked on integrations for a data cleaning and transformation OSS project describes briefly what usability means within SROSS projects which includes not being beholden to commercial and industry ways of performing usability improvements.

_“Usability, I would say, is the job of designers working together with the tech team, so developers, product managers make that as easy as possible for users within the bounds of the project. So I'm also the kind of person who I would never advocate for this kind of old school, Silicon Valley thing like, don't make me think. I don't believe in that.”_

Like similar conversations, these multiple user pathways tend to make SROSS projects nervous about resources, prioritization and scope of usability improvements.

## Usability is mostly understood by Science and Research OSS contributors and builders only when the OSS is actively being used. Very few SROSS contributors and builders think of the usability beyond the act of using the OSS.

This finding was more of a gap in the conversation than an explicit conversation. Raised specifically by one project when discussing what usability is they began to explore strategic decisions made by the members of the project and the difficulty they’ve been having as a project in making clear, informed strategic decisions that reach beyond the maintainer teams own perspectives and understanding.

The lead developer maintainer of a 10 years mature OSS project that focuses on data analysis of machine learning in Python states “People understanding the limits of the scope of the project — and why. And people using libraries correctly (within scientific methodological limits). There is a risk of using the tool incorrectly and then pursuing a line of inquiry that leads them to an improper result.”

This conversation quickly began to describe the parts of the SROSS tool that were ‘outside’ of the functional OSS tool. The decisions before using the tool that the user makes, the ways they prepare their data, the research questions they approach the use of the OSS tool with, the hope and expectations they have of how the OSS tool might process and present data as well as how that output from the OSS tool informs the next use of the tool is all part of the wider user experience of the OSS, the service design of the OSS tool.

As this conversation with the participant concludes, our researcher notes in the progressing conversation that “\[The OSS project] participant seems to be thinking about the user problems that occur 'before' the tool/software is used and is frustrated/concerned/confused on how to tackle those problems if to tackle those problems”. 

This is an understandable concern on the part of the maintainer, how to better understand and build for the parts of the experience that comes before and after the use of the OSS is a complex usability question for someone not familiar with usability approaches.



## Science and Research OSS misses out on the ways that dedicated Usability efforts could improve their tools and services in ways that they themselves express, but don’t yet realize is connected to Usability.

Developers and maintainers of early stages, low user numbers Science and Research OSS often spoke of answering email requests for help from users as a joyful activity. They described the act of directly helping and addressing someone's problem as a positive in terms of solving a specific problem for a person as well as having some clarity on how to improve usability or documentation generally. Developers here are doing customer support informed usability improvements. However, there were projects with significantly more users or different kinds of science and research fields that spoke of the support requests in a way that was time consuming and not efficient uses of their time.

Here a participant that was a computational scientist that now maintains OSS for data science projects running multiple components in Python describes the volume of questions the project receives and the desire to make this easier for those people asking questions:

_“Leads to lots of questions from users that if we, if we could figure out how to do it, then we wouldn't spend as much time kind of answering basic questions over and over again. Right, software would be easier to use for people and that would kind of free up more of our time to actually work on developing and further as opposed to helping users do things that in theory should be simple.” _

They describe a reality where if the software made sense to users then that would free up time for other work and priorities for the OSS.

They go on to describe the complex nature of the OSS tool “What we're doing is kind of complicated, in some ways. And we try to make it as simple as possible, and how we encapsulate or abstract the complexity in a way that people can understand.” and how the efforts on the documentation have helped “we have gotten a lot of people that have been very happy with our documentation. Which is kind of weird, because again, there are people that definitely have problems doing things that we think should be simple”.

This individual is performing usability improvements in the way that makes sense to them that they are trained in, writing and updating documentation and responding to requests for help. The alternative method that is not served here is what they suggest in the first quote which laments around ‘if the software was easier’.

## Conclusion

We can clearly see from our research that there are ways that Usability is being practiced in Science and Research OSS, yet those teams without access to usability and design resources and experts hit a wall at certain points in these projects that they struggle to self-serve and problem solve out of.

The appetite for better usability is best described by a community manager supporting multiple SROSS projects.

_“What I learned from all of that, though, is that there is a huge desire for people to improve the usability of their software, and then acknowledge that there's not a lot of forethought into what the trajectory of the software project will mean in the context of user accessibility later on. Usually, the thought process is how can we incorporate this feature as quickly as possible. But that being said, people do want to make the user experience better. And there's a huge desire to do that. But figuring out how to make that happen is a much bigger and harder question.” _

If we can better communicate the need for usability earlier in the lifecycle of Science and Research OSS and assess their future needs better, support with educational resources that are directly applicable to the kinds of Science and Research OSS that exists and provide that usability support at the moments when the SROSS are ready (and just becoming ready) for support then we can mitigate these points where SROSS projects get stuck and spend resources writing additional documentation and responding to support requests without incorporating those support request changes into the OSS tool.
