---
aliases:
  - Shard.md
tags:
  - overview
---
# Shard.md
-> Shard.md is a set of tools that provides structured access to Markdown notes and offers rules and integrations for the organized creation and maintenance of knowledge bases
- works with [GitHub-flavored Markdown](https://github.github.com/gfm/) and  [Obsidian-flavored Markdown](https://help.obsidian.md/Editing+and+formatting/Obsidian+Flavored+Markdown)

**_Why should I/we use this?_ - Well, Shard.md helps you to:**
- write [[Notes|notes]] that follow a consistent style using configurable structures/rules
	- this allows knowledge bases to grow sustainably, even on larger scales
- create a single, unified source of truth within projects you want to document
- maintain written documentation and keeping it in sync with what's actually implemented in the project via live synchronization/suggestions (and/or as a quality gate on commit)

**Central Features:**
- rule validations and suggestions for Markdown notes
	- feedback either via API or directly through Obsidian integration
- bi-directional live-synchronization of code documentation and Markdown documentation
	- provided by extensions that offer a direct integration into various programming languages
	- allows linking of abstract concept descriptions, software architecture documentation, and concrete implementations
- intuitive and integrated linking to remote Markdown notes
	- allows the connection of multiple knowledge/documentation bases with each other
- versatile API that allows for easy extensibility

## General Concepts
- [[Notes]]
- [[Note Patterns]]
- [[Note Pattern Elements|Pattern Elements]]
	- [[Basic Note Pattern Elements]]
	- [[Constrained Note Pattern Elements]]
	- [[Compound Note Pattern Elements]]
- [[Content Rules]]
	- [[Occurrence Rules]]
	- [[Text Rules]]
	- [[Provided and Linked Values]]
## Architecture
- [[Shard.md Software Artifacts]]