---
layout: default
title: "CS294/194-280 <br> Advanced Large Language Model Agents"
permalink: /sp25
redirect_from:
 - /
---

### Prospective Students

- ***Students interested in the course should first try enrolling in the course in CalCentral. The class number for CS194-280 is 33840. The class number for CS294-280 is 33841. Please join the waitlist if the class is full.***
- ***We plan to expand the class size to allow more students to join. Please fill in the <a href="https://forms.gle/sfWW8M2w1LDTnQWm9">petition form</a> if you are on the waitlist or can't get added to the waitlist. You will receive an email notification around the beginning of the spring semester if you are allowed in.***
- ***<span style="color:red">Do not email course staff or TAs. Please use [Edstem](https://edstem.org/us/join/QMmJkA) for any questions. For private matters, post a private question on Edstem and make sure it is visable to all teaching staff.</span>***

## Course Staff

<table>
<tbody>
<tr>
<td>Instructor</td>
<td>(Guest) Co-instructor</td>
<td>(Guest) Co-instructor</td>
</tr>
<tr>
<td><img src="assets/dawn-berkeley.jpg" height=200/></td>
<td><img src="assets/XinyunChen.jpg" height=200/></td>
<td><img src="assets/KaiyuYang.jpg" height=200/></td>
</tr>
<tr>
<td><a href="https://people.eecs.berkeley.edu/~dawnsong/">Dawn Song</a></td>
<td>Xinyun Chen</td>
<td>Kaiyu Yang</td>
<tr>
<td>Professor, UC Berkeley</td>
<td>Research Scientist, <br> Google DeepMind</td>
<td>Research Scientist, <br> Meta FAIR</td>
</tr>
</tr>
</tbody>
</table>

Teaching Staff: Alex Pan, Tara Pande, Ashwin Dara, Jason Yan

## Class Time and Location

Lecture: 4-6pm PT Monday at Anthro/Art Building 160

## Course Description

Large language model (LLM) agents have been an important frontier in AI, however, they still fall short critical skills, such as complex reasoning and planning, for solving hard problems and enabling end-to-end applications in real-world scenarios. Building on our [previous course](https://llmagents-learning.org/f24), this course dives deeper into advanced topics in LLM agents, focusing on reasoning, AI for mathematics, code generation, and program verification. We begin by introducing advanced inference and post-training techniques for building LLM agents that can search and plan. Then, we focus on two application domains: mathematics and programming. We study how LLMs can be used to prove mathematical theorems, as well as generate and reason about computer programs. Specifically, we will cover the following topics:
- Inference-time techniques for reasoning
- Post-training methods for reasoning
- Search and planning
- Agentic workflow, tool use, and functional calling
- LLMs for code generation and verification
- LLMs for mathematics: data curation, continual pretraining, and finetuning
- LLM agents for theorem proving and autoformalization

## Syllabus
*‡Livestream Only*

| Date   | Guest Lecture <br> (4:00PM-6:00PM PT) | Supplemental Readings | 
|--------|-------|-------|
| Jan 27th | **Inference-Time Techniques for LLM Reasoning** <br> Xinyun Chen, Google DeepMind <br> <a href="https://rdi.berkeley.edu/adv-llm-agents/slides/llm-agents-berkeley-intro-sp25.pdf">Intro</a> <a href="https://rdi.berkeley.edu/adv-llm-agents/slides/inference_time_techniques_lecture_sp25.pdf">Slides</a> | - [Large Language Models as Optimizers](https://arxiv.org/abs/2309.03409) <br> - [Large Language Models Cannot Self-Correct Reasoning Yet](https://arxiv.org/abs/2310.01798) <br> - [Teaching Large Language Models to Self-Debug](https://arxiv.org/abs/2304.05128) <br> *All readings are optional this week.* |   
| Feb 3rd‡ | **Learning to reason with LLMs** <br> Jason Weston, Meta <br> <a href="https://rdi.berkeley.edu/adv-llm-agents/slides/Jason-Weston-Reasoning-Alignment-Berkeley-Talk.pdf">Slides</a> | - [Direct Preference Optimization: Your Language Model is Secretly a Reward Model](https://arxiv.org/abs/2305.18290) <br> - [Iterative Reasoning Preference Optimization](https://arxiv.org/abs/2404.19733) <br> - [Chain-of-Verification Reduces Hallucination in Large Language Models](https://arxiv.org/abs/2309.11495) |   
| Feb 10th‡ | **On Reasoning, Memory, and Planning of Language Agents** <br> Yu Su, Ohio State University <br> <a href="https://rdi.berkeley.edu/adv-llm-agents/slides/language_agents_YuSu_Berkeley.pdf">Slides</a>  |  - [Grokked Transformers are Implicit Reasoners: A Mechanistic Journey to the Edge of Generalization](https://arxiv.org/abs/2405.15071) <br> - [HippoRAG: Neurobiologically Inspired Long-Term Memory for Large Language Models](https://arxiv.org/abs/2405.14831) <br> - [Is Your LLM Secretly a World Model of the Internet? Model-Based Planning for Web Agents](https://arxiv.org/abs/2411.06559) |   
| Feb 17th | *No Class - Presidents' Day*  | |   
| Feb 24th‡ | **Open Training Recipes for Reasoning in Language Models** <br> Hanna Hajishirzi, University of Washington <br> <a href="https://rdi.berkeley.edu/adv-llm-agents/slides/OLMo-Tulu-Reasoning-Hanna.pdf">Slides</a> | - [Tulu 3: Pushing Frontiers in Open Language Model Post-Training](https://arxiv.org/abs/2411.15124) <br> - [Unpacking DPO and PPO: Disentangling Best Practices for Learning from Preference Feedback](https://arxiv.org/abs/2406.09279) <br> - [OpenScholar: Synthesizing Scientific Literature with Retrieval-augmented LMs](https://arxiv.org/abs/2411.14199) |   
| Mar 3rd | **Coding Agents and AI for Vulnerability Detection** <br> Charles Sutton, Google DeepMind <br> <a href="https://rdi.berkeley.edu/adv-llm-agents/slides/Code Agents and AI for Vulnerability Detection.pdf">Slides</a> | - [Interactive Tools Substantially Assist LM Agents in Finding Security Vulnerabilities](https://arxiv.org/abs/2409.16165) <br> - [From Naptime to Big Sleep: Using Large Language Models To Catch Vulnerabilities In Real-World Code](https://googleprojectzero.blogspot.com/2024/10/from-naptime-to-big-sleep.html) |   
| Mar 10th‡ | **Multimodal Autonomous AI Agents** <br> Ruslan Salakhutdinov, CMU/Meta <br> <a href="https://rdi.berkeley.edu/adv-llm-agents/slides/ruslan-multimodal.pdf">Slides</a> | - [Mind2Web: Towards a Generalist Agent for the Web](https://arxiv.org/abs/2306.06070) <br> - [WebArena: A Realistic Web Environment for Building Autonomous Agents](https://arxiv.org/abs/2307.13854) <br> - [VisualWebArena: Evaluating Multimodal Agents on Realistic Visual Web Tasks](https://jykoh.com/vwa) <br> - [Tree Search for Language Model Agents](https://jykoh.com/search-agents) |  
| Mar 17th | **Multimodal Agents – From Perception to Action** <br> Caiming Xiong, Salesforce AI Research <br> <a href="https://rdi.berkeley.edu/adv-llm-agents/slides/Multimodal_Agent_caiming.pdf">Slides</a> | - [OSWORLD: Benchmarking Multimodal Agents for Open-Ended Tasks in Real Computer Environments](https://arxiv.org/pdf/2404.07972) <br> - [AGUVIS: Unified Pure Vision Agents For Autonomous GUI Interaction](https://arxiv.org/pdf/2412.04454) |   
| Mar 24th | *No Class - Spring Recess*  | |   
| Mar 31st‡ | **AlphaProof: when reinforcement learning meets formal mathematics** <br> Thomas Hubert, Google DeepMind <br> <span style="color:red">10am-noon PT</span> <br> <a href="https://rdi.berkeley.edu/adv-llm-agents/slides/alphaproof.pdf">Slides</a> | - [AI achieves silver-medal standard solving International Mathematical Olympiad problems](https://deepmind.google/discover/blog/ai-solves-imo-problems-at-silver-medal-level/) <br> - [Mastering Chess and Shogi by Self-Play with a General Reinforcement Learning Algorithm](https://arxiv.org/pdf/1712.01815) <br> - [The Future of Mathematics?](https://www.youtube.com/watch?v=Dp-mQ3HxgDE) <br> - [Building the Mathematical Library of the Future](https://www.quantamagazine.org/building-the-mathematical-library-of-the-future-20201001/) |   
| Apr 7th | **Language models for autoformalization and theorem proving** <br> Kaiyu Yang, Meta FAIR <br> <a href="https://rdi.berkeley.edu/adv-llm-agents/slides/mathverification.pdf">Slides</a> | - [LeanDojo: Theorem Proving with Retrieval-Augmented Language Models](https://arxiv.org/abs/2306.15626) <br> - [Autoformalization with Large Language Models](https://arxiv.org/abs/2205.12615) <br> - [Autoformalizing Euclidean Geometry](https://arxiv.org/abs/2405.17216) |   
| Apr 14th‡ | **Advanced topics in theorem proving** <br> Sean Welleck, CMU <br> <a href="https://rdi.berkeley.edu/adv-llm-agents/slides/welleck2025_berkeley_bridging.pdf">Slides</a> | - [Draft, Sketch, and Prove: Guiding Formal Theorem Provers with Informal Proofs](https://arxiv.org/abs/2210.12283) <br> - [miniCTX: Neural Theorem Proving with Long-Contexts](https://www.arxiv.org/pdf/2408.03350) <br> - [Lean-STaR: Learning to Interleave Thinking and Proving](https://arxiv.org/abs/2407.10040) <br> - [ImProver: Agent-Based Automated Proof Optimization](https://arxiv.org/abs/2410.04753) |   
| Apr 21st‡ | **Program verification & generating verified code** <br> Swarat Chaudhuri, UT Austin <br> <span style="color:red">10am-noon PT</span> | - [An In-Context Learning Agent for Formal Theorem-Proving](https://arxiv.org/abs/2310.04353) <br> - [Symbolic Regression with a Learned Concept Library](https://arxiv.org/abs/2409.09359) |   
| Apr 28th‡ | **Agent safety & security** <br> Dawn Song, UC Berkeley | |   

## Enrollment and Grading

***Prerequisites:*** **Students are strongly encouraged to have had experience and basic understanding of Machine Learning and Deep Learning before taking this class, e.g., have taken courses such as CS182, CS188, and CS189.**

***Please fill out the <a href="https://forms.gle/sfWW8M2w1LDTnQWm9">petition form</a> if you are on the waitlist or can't get added to the waitlist.***

This is a variable-unit course. All enrolled students are expected to participate in lectures in person and complete weekly reading summaries related to the course content. Students enrolling in one unit are expected to submit an article that summarizes one of the lectures. Students enrolling in more than one unit are expected to submit a lab assignment and a project instead of the article.
For students enrolling in 2 units, the project should have a written report, which can be a survey in a certain area related to LLMs. For students enrolling in 3 or 4 units, projects will follow either an applications track or a research track:
 - **Applications Track:** Projects in this track focus on applied use cases of LLMs and do not necessarily need to contribute novel research. Students in this track will work in groups of 3-4. The project for 3-unit students should include an implementation (coding) component that programmatically interacts with LLMs, while 4-unit students must complete a more substantial implementation with the potential for real-world impact.
 - **Research Track:** Students in this track will conduct novel research under the supervision of postdocs and graduate students, with the goal of publishing in a workshop or conference. Research track projects must be completed in groups of 2-3, and students must apply to participate via a forthcoming Google form. The expectations for implementation and intellectual contributions will align with the project requirements for 3- and 4-unit students.
    
The grade breakdowns for students enrolled in different units are the following:

|                              | 1 unit | 2 units | 3/4 units |
|------------------------------|--------|---------|-----------|
| Participation                | 40%    | 16%     | 8%        |
| Reading Summaries            | 10%    | 4%      | 2%        |
| Quizzes                      | 10%    | 4%      | 2%        |
| Article                      | 40%    |         |           |
| Lab                          |        | 16%     | 8%        |
| Project                      |        |         |           |
| &nbsp;&nbsp;*Proposal*       |        | 10%     | 10%       |
| &nbsp;&nbsp;*Milestone*      |        | 10%     | 10%       |
| &nbsp;&nbsp;*Poster Presentation*   |        | 10%     | 10%       |
| &nbsp;&nbsp;*Presentation Recording*   |        | 10%     | 5%       |
| &nbsp;&nbsp;*Report*         |        | 20%     | 20%       |
| &nbsp;&nbsp;*Implementation* |        |         | 25%       |

## Lab and Project Timeline

|                         | Released | Due    |
|-------------------------|----------|--------|
| Project group formation | 1/27      | 2/24    |
| Project proposal        |  2/3     | 2/24    |
| Project milestone       |  2/24     |  3/31   |
| Lab                     |  3/31     |  4/28   |
| Project final poster presentation    |  4/28     | 5/5    |
| Project final presentation recording    |  4/28     | 5/16    |
| Project final report    |  4/28     | 5/16    |

## Office Hours
- Alex: 6-7pm on Mondays on [Zoom](https://berkeley.zoom.us/j/2012565201)
