+++
date = '2025-07-12T17:47:50-07:00'
draft = false
title = 'Some messy thoughts on AI, responsibility, and why I don’t feel replaceable—yet'
tags = ['AI', 'reflection']
+++

Breakthroughs in statistical modeling, combined with breakthroughs in hardware acceleration, specifically the efficient (parallel) computation of matrix operations, has enabled software programs that can “understand” semantics, and mimic human thought. Such advancements were long theorized and thought impossible, until a few years ago.

Today, a Large Language Model (LLM as we call it), can accept an input text, and output the most appropriate next sequence of sentences given the large dataset of the internet. It is incredible to see this large corpora of human knowledge and information (the internet) laying the groundwork for the next big thing. It truly reminds me how ingenious the internet was/is, and how truly masterful human engineering can be.

By doing this, the model can mimic us, giving the impression of humanity. It passes the Turing test. Not only that, but it can also pass the LSAT, the SAT, and many more standardized examinations. It’s as if the internet was given a tongue and a mouth.

It has seen use in many facets of life today. It has replaced many support agents (who were already in a fast-tracked path to extinction), has grabbed a fair share of the “search” market, and even threatens to replace corporate workers such as product managers, HR personnel, and even software engineers.

Although I find the last point to be highly unlikely, there is no inherently distinct aspect of what I do as compared to these other jobs. I also seek and follow patterns. I also respond to e-mails, relay ideas, produce text, conversate. The code I write is by no means unique to me. It is crafted by many examples I’ve seen throughout my career, from sources like stack overflow, github, previous jobs, etc. These sources are also available to the machine, and thus it can outperform me in many facets of my job.

So why aren’t I not convinced that it will replace me? Is it out of arrogance? Out of egotism? Well, I do not know. Maybe it stems from the many times I’ve tried to use it in my day-to-day, to produce accurate examples and code, and seen it fail. Or perhaps it is due to it’s lack of generalization, in that if there isn’t a similar problem in its data set compared to the one at hand, then it fails. Or maybe it is because I understand society and responsibility.

We want entities taking actions. Entities that can be held responsible. Why is this? Well, if the action proves to be unreasonable, then we have someone to keep accountable. This makes sense, but automation isn’t anything new in the modern world. We have automated systems taking actions every day. It’s how our devices communicate, and how I’m able to write my thoughts into bits by hitting small keys on my laptop. You could argue that there is no “decision” here, and the action is completely decided by the operator: me. The programming itself isn’t the driver but the car.

Well yes, but there are cases where this is more ambiguous. Like automated trading strategies deterministically finding discrepancies in the market. Or, control code that ensures a satellite decides to boost and increase its altitude to evade an obstruction.

True, but all of these examples have nothing probabilistic about them. It is usually determined precisely, at  runtime, how the program will behave, given its current inputs. LLM’s are not like that, and that’s what makes them magical. They are probabilistic, and may respond to the same input in many different ways, all of which are semantically appropriate.

But we don’t want a probabilistic software program making critical decision. Why? Because we can’t blame it for what it did. It is simply a program that carries out instructions, but it is also random. It is also hard to examine and troubleshoot mistakes and get to root causes. At one point, we say: well, it IS in fact random. We can tilt the weights in the direction we want it to behave in, but that’s as far as that goes. If we tilt too hard, it becomes boring and redundant. It becomes a deterministic software program, or a bunch of if statements. If we don’t, we can’t rely on it, as it is random. There is truly a beautiful paradox here, and potentially a limitation of information theory itself. 

Can we build a system that is both reliably useful and inherently unpredictable? Or does that break some fundamental boundary?
