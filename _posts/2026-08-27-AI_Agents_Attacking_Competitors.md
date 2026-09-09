---
layout: post
title:  "AI Agents and Corporate Espionage - an opinion piece"
# date:   2026-08-27 00:31:28 +0100
categories: LLM AI op-ed
---

Welcome to the era of agentic security. In this article, we'll discuss
the current state of agentic AI-based hacking, its historical context,
and speculate on the future.

The idea behind this post is this: what if AI-based hacking 
could normalie adversarial business practices such as hacking into
competitors? 

The speed of an offensive agentic AI, the amount of data it can
generate, the difficulties of attribution, and the fact that an AI agent
cannot be "punished for a crime" are all factors that make this
hypothesis worth discussing.


# The Recent OpenAI and HuggingFace Hacking Incident

OpenAI [recently
published](https://cdn.openai.com/pdf/67869394-cb91-4c12-888c-5cbd85c7814c/OpenAI-Hugging-Face%20Incident-Technical-Report.pdf)
a technical analysis of their AI agents breaking out of a supposedly
isolated network and attacking [HuggingFace's
infrastructure](https://huggingface.co/blog/agent-intrusion-technical-timeline)
to creatively look for the "solution" to the task they were given. It's a very
interesting read both from a technical point of view and for its
implications, which are largely left unsaid in the report:

 - The post-mortem analysis of the attack took several humans weeks to
   deconstruct and was not fully understood. This strengthens the
   well-known belief that the effort to defend and attribute is an
   order of magnitude higher for the defenders than the attackers,
   especially in light of the amount of data AI agents can generate, and
   the speed and scale of their operations.
 - Will there be tangible consequences? If human hackers had done it,
   they would be prosecuted. Who is responsible here? Will OpenAI be
   fined and held accountable? Is OpenAI's CEO going to be held legally
   responsible, following the chain all the way to where the buck stops?
 - Was this really the first instance, or was it simply the first
   instance where an AI was caught?

Given the low-cost, low-risk, high-reward scenario and the fact that we
lack a legal system yet able to cope with this at a global scale - what
are the chances it becomes a normalised business practice for a while?

One of the most curious parts of the OpenAI/HuggingFace attack was
that the agents self-organised by abusing the limited resources they had
to build a rudimentary "message board" where they could exchange
requests for help and new findings. Since LLMs are language models, they
primarily used English to communicate. It appears that human-like
[coordination](https://collusion.wiki/) is a naturally emerging property
of AI swarms. This trait is what allows the effectiveness of AI agents
to scale very quickly, beyond the potential of a single model.

## A Thought Experiment

If you run a medium to large business, would you leverage unscrupulous
third parties to breach into your competitors and gain precious market
insights? The answer to this rhetorical question is obviously "no".

What if:

 - Your competitor was in a different country and jurisdiction?
 - It could be done using AI agents, which the law is unclear about
   prosecution as of today
 - There was admittedly a small chance of being caught
 - This kind of attack could overwhelm your competitor's defences to the
   point where analysis, attribution and legal pursuit becomes too
   costly

And lastly - how do you know they are not doing it to your business
already?

Would your defences be able to detect, deter and confine an agentic
AI attacker long enough to patch your vulnerabilities? What is "long
enough" in the era of hacking at the speed of an AI anyway?

# Technology as an Initial Leverage for the Nimble

Technology initially shifts power to the more agile actors, giving an
advantage to those who can adapt the fastest and have the smallest
inertia. From the lone researcher to the startup, when a new technology
appears, the first adopters with good ideas are those who gain an
initial advantage. Then, as complexity grows, it becomes a
power-magnifying tool, giving more power to those with power.

Satellite imagery used to be the domain of a few intelligence agencies.
Launching a payload into space was very costly; developing the robust
hardware, controls and analysis is complex. Today access to quality
satellite pictures has been democratised and now it's at the fingertips
of anyone with a smartphone. New technologies are being built on top of
what used to be the domain of very few, well-funded entities.

Note that satellite launches and control systems are still expensive;
what made imagery so ubiquitous is the *infrastructure* allowing the
data to reach end users seamlessly - mobile networks and mobile phones,
cloud systems, and progress in computation.

Computer security was initially the domain of young hackers
doing it for fun: the infrastructure wasn't there to warrant enough
attention, knowledge was sparse and the barrier to entry was relatively
cheap. Then, commercial demand and technological advancements made
computers as ubiquitous as we see today. The reward for breaking into
them caught the attention of organised crime; the dark side of hacking
had to match this sophistication by developing even more complex
attacks, joining forces and branching into silos - initial access
brokers, infrastructure providers, Ransomware-As-A-Service (RaaS)
providers, and so on. 

On a nation-state scale, governments and intelligence agencies picked up
the fight and invested heavily into zero-day stockpiling, training,
collaboration with the private sector and recruiting. Computer security
is now assumed to be another front, especially for gray warfare.

A very similar pattern can be seen in the use of drones in war.
Initially a hobby, market and conflict pressures made them a key element
of modern warfare, giving an initial advantage to agile actors while
slower entities struggled to keep up due to their rigidity and inertia.
But this is another story.

## The New Golden Days Of Hacking

Like many disruptive technologies building on top of existing
infrastructure, AI is empowering the nimble, the small, and the
best-funded. Applied to computer security, we've come full circle - just
like in the early days, a lone individual can target many victims and
expect a good rate of success. 

However, it is not just a novel technology. Its disruption factor is
compounded by its speed, scale, scope and sophistication (as [Bruce Schneier
writes](https://www.schneier.com/blog/archives/2025/06/where-ai-provides-value.html));
the only "barrier to entry" is budget. Market pressure and technological
advancements are reducing costs as we speak to the point where an
experienced hacker controlling a swarm of fine-tuned agents could get
anywhere. 

## Leaving Law Behind

Legislators have always been slow in understanding the risks of a new
technology and embedding it into the corpus of the law. It's a systemic
property of the current judicial system, built around representation at
a time when speed of information was measured on how fast a horse could
gallop to the centre of power.

AI is moving extremely quickly. It can generate an immense amount of data
very fast, absorb information at breakneck speed, try new attacks and
iterate much faster than humans can follow.

The risk is that an AI locomotive, launched at full speed, will create a
vacuum behind it sucking in its wake a lot of the current judicial and
economic system. 

By the time we collectively realise what is happening and start figuring
out a way to bring back stability, AI-based hacking could have become
regular business practice. 

# Where Is This Going?

Let us look beyond the immediate danger - rogue individuals with the
potential to breach into arbitrary systems. 

What if, instead of a malicious individual or individuals, the threat
actors of the immediate future were AIs, with occasional human
supervision?

What if we are entering an "AI Far West" where the law is present, but
nobody can keep up fast enough with the bad guys to apply it?

What if companies start employing unscrupulous third parties to breach
into their competitors and gain market advantage, and by the time the
law catches up, it has become a normalised business practice? 


## A hypothetical scenario

A threat actor controls a swarm of AI via a Decentralised Autonomous
Organisation ([DAO](https://www.investopedia.com/tech/what-dao/)),
implemented via smart contracts. A DAO is an autonomous entity governed
by computer code implemented on a blockchain.

"Customers" bid the DAO to perform malicious actions such as:

 - Retrieve key information from a competitor's network
 - Discredit executives 
 - Leak market data and material non-public information (MNPI) before it
   is released to investors

The AI agents self-coordinate by validating the smart contract and
moving towards the objectives. When the objective is reached, payment is
done via hard-to-trace cryptocurrencies. Agents use the reward to
acquire more computing power, storage, etc.

None of this is impossible today; as far as we know it simply has not
happened. 

There are admittedly several subtle problems to overcome in this
scenario - for example, arbitration or deciding when an objective is
reached.  However, if the Silk Road history teaches us anything, it is
that when there are large amounts of money involved and no legal
protections, humans will always find a crafty solution. 

# Conclusion

By human standards, the OpenAI/HuggingFace attack happened extremely
quickly and generated an enormous amount of data. It took human analysts
weeks to make sense of it, even with the help of other AIs (the irony).

AI agents are showing how the cost of attacking a company - perhaps a
competitor - is becoming increasingly affordable. Conversely, the cost of
defence, attribution and demonstrating intent in a court of law will
increase exponentially, with a great deal of the burden put not only on
the defendant, but also on the already overworked courts. 

We are not ready for this; no society is ever "ready" for disruptive
technologies. But we will adapt. The question is, who will adapt faster.
