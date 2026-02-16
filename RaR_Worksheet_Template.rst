Reasoning About Reasoning (RaR) Worksheet
==================


Reasoning Identification
------------------------

**I.1** Does the task your system is supposed to do involve some form of reasoning as per your interpretation? Describe the task and then explain why the task be interpreted specifically as reasoning.

**I.2** Does the expected LLM response (at inference) involve reasoning as per your interpretation? Describe the LLM response and then explain why the response be interpreted specifically as reasoning.

**I.3** Does your system consist of an explicitly trained reasoning language model? Describe what characteristics or behaviors of the model lead you to that view and then explain why those aspects indicate whether it is a reasoning model or not.

Reasoning Framing
-----------------

**F.1** Is the reasoning process structured in an orderly step-by-step manner? Justify why this is necessary.

**F.2** Is the reasoning process structured in stages or phases (where each stage may have its own sub-task) with a degree of order between them? Justify why this framing is necessary for your task.

**F.3** How are individual steps or stages or phases organized and interacted with one another? Do the steps branch and/or merge? Justify why your desired mode of organization is necessary for your task.

**F.4** Does a step or stage or phase include multiple reasoning-related sub-tasks? If so, explain why they are necessary for your task and how they are related to LLM reasoning.

**F.5** List down all possible interpretations that a reasoning step or stage or phase can refer to in your application. Explain why you interpret them that way and how they connect to your system's behavior and goals.

**F.6** Can the terminal state of your reasoning task that the LLM(s) is(are) performing have one or more than one possible conclusions? Explain why this multiplicity arises or why it may be necessary.

**F.7** Can each of the possible conclusion of your reasoning task be objectively understood or are they open to subjective interpretations? Describe what makes your preferred interpretation reasonable and why that matters.

**F.8** Is your interpreted reasoning behavior at inference expected to follow some structure or form? Justify why a structure is (or is not) required and explain the level of explicitness in the structure, if applicable.

**F.9** Can the reasoning behavior at inference be structured in ways other than by separating it into multiple parts or sub-tasks? If so, explain why this might be preferred in your case.

Reasoning Execution
-------------------

Inference Scaling
~~~~~~~~~~~~~~~~~

**E.1** Does your task rely solely on prompting techniques? If so, what strengths and capabilities of LLMs convince you that this is sufficient?

**E.2** Did you include any domain knowledge in your prompt(s)? If not, justify why this is not required or explain how you interpret LLMs can incorporate the necessary knowledge.

**E.3** How did you choose in-context examples or demonstrations for your task? Justify why these samples will help LLMs to respond better.

**E.4** Were your final prompt(s) evolved over several iterations? Explain what changes were necessary and why they were important.

**E.5** Do you explicitly introduce the reasoning frame, required for your task, in the prompt? Justify your stance.

**E.6** If you considered some form for finetuning LLMs but did not implement it, explain what made you not implement and why this is acceptable.

Reasoning Finetuning
~~~~~~~~~~~~~~~~~~~~

**E.7** To what extent do the contents of the finetuning datasets reflect the kinds of responses your system is expected to produce at inference? Explain why this alignment is necessary.

**E.8** If the finetuning datasets are not specifically developed for your task, justify why task-specific datasets are not used.

**E.9** Are the ways reasoning is structured (steps, stages, or phases) and organized (in chains, trees, or graphs) in finetuning datasets similar to how your system is expected to respond at inference? Explain why the similarities and differences are acceptable.

**E.10** Does your finetuning datasets contain flawed reasoning patterns (as per your task)? If so, explain how this is (or is not) a problem; if not, justify your stance.

**E.11** Does your system's performance on tasks other than (or somewhat related to) yours change due to the finetuning? If this aspect is insignificant, explain why.

Reasoning Evaluation
--------------------

**V.1** Do you conduct a preliminary evaluation of LLMs' reasoning abilities prior to applying them for your task? If not, explain why this is not necessary.

**V.2** Justify why LLM reasoning is necessary or beneficial to your target user?

**V.3** How do you ensure and assess whether your users consider LLMs' reasoning behavior (towards a desired terminal state) when determining your system's utility? Explain why your method works.

**V.4** If your evaluation of LLM reasoning is predominantly qualitative, justify why this is necessary and/or sufficient? If your evaluation involves quantitative methods, are they against ground truth values or user feedback? Justify why you chose one over the other, if applicable.

**V.5** Do you refer to LLMs' benchmark performance to interpret their reasoning ability? If so, justify why these established results are sufficient for your task.

**V.6** How aligned are the modes of reasoning in these benchmarks with respect to your task? Describe the level of alignment necessary for your task and explain why this is (in)sufficient.

**V.7** Do your benchmarks contain intermediate reasoning steps? Justify why this does (not) affect your interpretation of LLM reasoning required for your task.

**V.8** How do you justify that the LLMs you use did not memorize the benchmark test datasets?
