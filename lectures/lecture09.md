# Lecture 9

## Housekeeping
- Week in World of AI
    * [$500M+ AI Agent -- Terminal of Truth](https://youtu.be/EKspo1FLj-4?si=V84g5YbiOTM9BFfu)
    * [Anthropic Agents](https://youtu.be/xr0FCUNoy_0?si=NUFjV0FJQ87CnVYB) [& Control](https://youtu.be/idipaHSpQes?si=05Gax-A6t_TbaZFN)
    * [o1 vs. 4o](https://youtu.be/rVjANY9UC9s?si=3DXay1ovZXzcRum8)
    * [New Mac AI Coding tool](https://www.youtube.com/live/ikn7JSUflTI?si=cut1HjdZ7SWP50eU)
    * ["Open Source" Nvidia Nemotron](https://youtu.be/QXVSIR2z1q4?si=v7a-oB2eZMlbmhFW)
    * [World Coin Update](https://youtu.be/fJszPAk-WHk?si=vHyGPkfJvrKo2ZI0)
- Delayed quiz due to assignment catch up.
- Check Canvas for grading; DM me if you think it is not up to date; You must DM both of my users & accept friend requests!
- Quiz reminder: will be 20 minutes with 20 questions.
- Remember to `git pull upstream master && git push`
- Did not assign you an Open AI key if CSV is not updated and do not see PRs; I review the [#continuous integration channel on Discord](https://discord.com/channels/1204850325748457543/1204856923149697045)
- Check postings on CSV file for accuracy; will not receive grades unless all tasks are completed
- Make sure your CI notifications are proper
- Review Grades/CSV
- Docking now at 10% per week

## Where Everyone Should Be Revisited:
- Discord Notifications with Webhook (DM me if you need the hook; Look in Discord help channel for Webhooks)
- Upstream forked and Setup on Personal Github accounts; Know Git/hub:
    * `ssh-keygen` & `ssh-add {-l}`
    * `git set upstream <branch>`
    * `git pull upstream master`
    * `git merge`
    * `git push {origin}`
    * `git checkout {-b} <branch>`
    * `ssh -vT git@github.com # check ssh key setup`
    * understand `.gitignore` and `.*` hidden files in project
    * understand `git log` and how to reset out sync repos with the `upstream`
    * if on Mac: `ssh-add --apple-use-keychain  ... && ssh-add --apple-load-keychain` otherwise:
    * `ssh-add -K ~/.ssh/.ssh`
- Pull Requests on Github, forks, and origin/upstreams synchronized.
- Basics of AI coding with V0 and setting up code on local repo; Understand how to use Aider and LLM
- Knowledge of TypeScript ecosystem with `npx`, `npm`, and NodeJS (ask AI if uncertain)
- AI Tooling: V0, Replit, Chat.dev, Copilot, Cursor, & Concepts:
    * Large Language Models (LLMs)
    * Feed forward networks (& ANNs)
    * Context Windows
    * Retrieval Augmented Generation (RAG)
    * Chain & Tree of Thought (CoT/ToT)
    * Self Taught Reasoning (STaR)
    * Tokenization and Transformer Architectures as well as Next Token Prediction
    * Mixture of Experts (MoE)
    * Agentic Approaches
    * Benchmarking, Weigths/Biases (Parameters) & Open Source Relevance (open weights, data, and models)
- API Keys setup & sample `.aider.conf.yml` in proper subdirectory
- Have me (jeffrey-l-turner) as reviewer/collaborator on Pull Requests (note Canvas will be graded once assignment complete)
- Make Sure you're information is accurate on CSV posted in Discord
- Signup for [Pythathagora](https://www.pythagora.ai) - no luck getting access so far; Recommendation: use Cursor with Pythagora
- Understand basics of complexity theory and non-deterministic algos
- Up to date on CSV file. Will place whether Open AI key assigned
- Know how to use Github to create PRs, add me as reviewer and not close until graded

## Planning Software Architecture with Chain of Thought

<div align="center">
  <img src="./../docs/drawings/Centering_context.png" width="500" height="355" />
</div>

## Aider Coding Exercise
- Reminder on Techniques:
    * Triple quotes - """
    * LLMs as really good pattern matchers
    * Importance of repetion and context
    * Reinforcement prompting for defects and setting steps
    * Difference with o1 and 4o (STaR vs traditional MoE)
    * Using AI to plan out your code
    * Using "Judgement" -- AI cannot assess versioning for example (e.g. Rust, DenoJS vs NodeJS, Python 2/3, ...)
- Parsing
- Revision Control Use
- [Prompting Care](https://cursor.directory/)

## Resources:
- Channels I Follow for this Class: [Wes Roth](https://www.youtube.com/@WesRoth), [Matthew Berman](https://www.youtube.com/@matthew_berman), [David Shapiro](https://www.youtube.com/@DaveShap/videos), [Indy Dev Dan](https://www.youtube.com/@indydevdan), [Greg Isenberg](https://www.youtube.com/@GregIsenberg), [3 Blue 1 Brown](https://www.youtube.com/@3blue1brown), [AI Explained](https://www.youtube.com/@3blue1brown)
- Tools: [Aider](https://aider.chat/), [LLM](https://github.com/simonw/llm), & [uv](https://github.com/astral-sh/uv) [Data Centric](https://youtube.com/@data-centric?si=SjrEhrokPgsDoeYF) [Internet of Bugs](https://youtube.com/@internetofbugs?si=hahhYKaGX59agFjH) [The AI Grid](https://youtube.com/@theaigrid?si=ZhJcF-WMTwlFZwuP)
- [Open AI Key Management](https://platform.openai.com/)
- [Repo Prompt](https://repoprompt.com/)
