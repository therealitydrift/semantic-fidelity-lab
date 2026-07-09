# Measuring Fidelity Decay: Tracking Meaning Collapse in Generative Systems

*A framework for measuring how meaning erodes in AI systems through drift, decay, noise, and recursive compression.*

**Semantic Fidelity Project**  
**Apr 08, 2024**

Most critiques of large language models still focus on hallucinations and factual errors. Those problems matter, but they do not cover the full range of failure. A system can avoid obvious falsehood while still weakening the meaning it was supposed to preserve.

This framework measures fidelity decay through lexical decay, semantic drift, ground erosion, and semantic noise. Each dimension captures a different way meaning weakens as language moves through generative systems.

## The Four Dimensions of Fidelity Decay

## 1. Lexical Decay

Lexical decay happens when words remain legible but lose contact with concrete use. A term can circulate widely, appear in polished language, and still become less specific over time. The word is still understood at the surface, but its connection to lived reference has weakened.

This can be measured by comparing frequency against specificity. A word that appears constantly across a narrow range of generic contexts may be decaying. Another approach is to test whether the word still points to stable external referents, or whether it has become a flexible placeholder that can be attached to almost anything.

Human judgment still matters here. Some decay is felt before it is easy to formalize. A term can become technically meaningful in a model’s representation while feeling empty to readers because the contexts around it have become too repetitive or too generic.

## 2. Semantic Drift Across Generations

Semantic drift occurs when meaning changes as language passes through repeated transformation. In older usage, semantic drift often referred to how words change over time. In generative systems, the drift can happen faster because language is repeatedly processed, compressed, and regenerated.

Each pass can preserve the surface of the language while weakening its relation to the original intent. The change may not appear as a single clear error. It accumulates across iterations until the final output remains fluent but carries less of what made the original communication work.

A useful measurement approach is to track meaning across generations. A source text can be passed through repeated transformations, then evaluated for whether intent, uncertainty, emphasis, and metaphor remain intact. The measurement works as a decay curve, showing how much fidelity is lost as the system continues to process the text.

## 3. Ground Erosion

Ground erosion happens when the background that gives language weight begins to collapse, weakening the implied, contextual, or deliberately unsaid elements that meaning depends on.

AI systems often make language more explicit. That can be useful, but it can also flatten the relation between foreground and background. A summary that turns every detail into the same kind of information may preserve content while losing hierarchy. The problem is that it failed to preserve what mattered more and what mattered less.

This kind of failure can be measured by testing whether a model preserves context and hierarchy where they matter. Some texts carry meaning through placement, restraint, and emphasis, not just through explicit information. A system that flattens those relationships may still be accurate, but it loses the background structure that made the language intelligible.

## 4. Semantic Noise

Semantic noise appears when fluent generated language saturates an information environment. The issue is whether the surrounding ecosystem becomes harder to search, interpret, or trust because too much language carries too little new substance.

Semantic noise can be measured by looking at redundancy, retrieval quality, and the rate at which generated outputs repeat existing forms without adding useful distinction. As synthetic text expands, the signal-to-noise problem becomes more important. Search results and generated answers may remain readable while offering less contact with source, context, or judgment.

This type of evaluation looks beyond a single output. It examines what happens when many similar outputs accumulate inside a corpus, making the information space harder to navigate even when individual texts appear coherent.

## What Measurement Changes

Measuring fidelity decay changes what AI systems are trained to preserve, how they are tested, and how loss is made visible to users. Training data should be assessed for varied contexts, precise language, and meaningful distinctions. A model trained mostly on high-volume generic language may learn fluency while becoming less sensitive to the conditions that give language weight.

Evaluation also has to become more longitudinal. Fidelity decay is not always visible in a single response, so systems need to be tested across repeated transformations, larger corpora, and changing contexts. The purpose is to see whether loss accumulates over time, rather than only whether one output passes in isolation.

Interfaces can make some of this loss visible. A system can give clearer cues when an answer has been heavily compressed, when important context has been reduced, or when the output should be treated as a thinner version of the source. The goal is to prevent compression from hiding what has been lost.

Fidelity decay cannot stay at the level of intuition. Once meaning loss can be named, it can also be tested. This framework makes that loss visible enough for AI systems to be compared, corrected, and designed with preservation in mind.
