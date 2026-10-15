# Creator Content Reviewer

An AI agent that gives a first-pass review of creator content against a brand's guidelines and campaign brief, so a marketing team spends its time on creative judgment instead of catching typos and naming slips.

This is the project that got my work featured in an [Anthropic customer story](https://claude.com/customers/miro-qa). I rebuilt the concept here as an interactive prototype of the workflow.

## The problem

Running a creator program at scale means reviewing a high volume of scripts and captions on tight timelines. Most of the catches are small (wrong product casing, an off-brief claim, a missing disclosure), but multiplied across dozens of creators in a compressed window, they eat an enormous amount of time that does not require creative judgment.

## How it works

The marketer gives the agent everything it needs once:

1. **Brand guidelines** — tone, voice, do's and don'ts, naming conventions
2. **Campaign brief** — objectives, key messages, product references, and what's off-limits before launch
3. **Any additional information** — anything specific to this creator or post
4. **Campaign name** — flows into the agent's editable instructions

The agent's instruction (editable): *"Review creator content as part of the [campaign] campaign, and provide feedback based on the brand guidelines, brief, and other details I've shared. Tell me what's working, what needs to be improved, and suggestions for how to revise."*

Then the marketer drops a link to the creator's Google Doc and clicks **Review**. The agent reads the document and returns structured feedback: what's working, what needs improvement, and specific suggested revisions.

The human stays in the loop for the judgment the agent can't make: whether the content feels authentic to the creator's voice and whether the story lands.

## Results (at Miro)

The production version, built on Claude Cowork, cut review time roughly in half and took post-event content live within 48 hours from **64% to 99%** across three global events and around 90 creators.

## About this prototype

This is a self-contained front-end prototype that demonstrates the flow and a representative output. The live version runs on Claude and reviews the actual linked document. Sample content here is illustrative and contains no proprietary data.

## Built with

AI tooling, iterated by hand. Single self-contained HTML file.
