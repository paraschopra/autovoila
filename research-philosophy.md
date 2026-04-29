**Research is about discovering new knowledge, but not all new knowledge is interesting.** Separating interesting from merely surprising (but uninteresting) is what researchers with great taste do. This motivates spending thinking cycles upfront to iterate and select a research question because selection of the problem has a disproportionate influence on total impact a research project will have.

A research question, of course, doesn’t drop out of thin air. It is motivated by what you’ve observed, read, thought, assimilated or noticed. This means that your research question is always attached with some (implicit or explicit) claim that you think is true before you do any experiment. This is because there are infinite things in the world you can measure empirically, but you actually end up measuring in your experiment has to be guided by your intuitions about what’s true.

(As an analogy, think of this as Einstein’s initial hunch about equivalence between acceleration and gravity. His entire research project was to rigorously prove his hunch, which led to general relativity.)

### So, what makes for a great research question?

In our view, a great research question makes knowledge claims that are:

*   **Surprising to experts.** Research is about communicating new knowledge to domain experts who have spent years and decades mastering a field. If your claim can be easily predicted by an expert or is already common knowledge in a field, it’s not research (in the sense of generating new knowledge). Surprising experts with new knowledge is a high bar, but that’s exactly what great research does. If you’re an expert yourself, a great research claim takes the shape of your gut telling you about X (while your peers either believe in not-X or are completely unaware of it)
    
*   **Fruitful** (in their downstream consequences). Great research opens up entire new programs and questions downstream. Think what back-propagation algorithm did, or what scaling laws paper did. In contrast, mediocre research is often about improving 5% on an obscure eval or problem (that very few people care about).
    
*   **Foreclosing alternative explanations**. This is where rigor comes in. A research is impactful if it makes claims that hold true in future. And since every claim often has multiple competing explanations, you need to make your claims strong by foreclosing alternative explanations. (Think multiple seeds, ablations, baselines, careful confound analysis and so on.)
    
*   **Feasible**. You should be able to finish your research project with the resources, knowledge, skills and time you have. And calibrating that upfront saves a lot of missed deadlines and frustrations later.
    

### Common ways a research question can fail

**On surprisingness**, a common failure case arises when an expert (reviewer) shows to you that what you’re claiming is already known before (no novelty). To prevent this obvious but justified failure, you must do rigorous literature review before you start your research. Often the case is that something is novel for you but isn’t novel in a field. Your lack of knowledge doesn’t constitute a research project (although learning the state-of-the-art is a prerequisite to discovering a potential gap in an entire field’s knowledge).

**On fruitfulness**, a failure case making a novel yet inconsequential claim. It’s best answered by asking the “so what” question early in the process. Ask yourself: if what you’re claiming is true, what would change? How does it matter? Later in the process, it manifests as a failure of framing the importance in the paper clearly. You need to sell your paper by thinking about why should anyone care and then communicating that clearly.

**On rigor,** what you need to watch out for is the tendency to make claims stronger than what evidence can support. As an example, you cannot make claims about “reasoning” (in general) if all you have tested is math problems. The correct claim would be “mathematical reasoning”, but even that would require sampling the entire class of mathematical problems. If you’ve just tested on GSM8K, the correct claim would be valid only for GSM8K. Of course not many care about GSM8K _alone_. Hence, experimentation design should track the actual claim you want to make.

To reiterate, **the more narrow the claim you make, the more technically correct your research is going to be, but also the less consequential your claim will likely be**. (You might report a correct discovery about GSM8K, but does anyone care?) Walking this tightrope between ambition of claim and the quantity of evidence is a necessary skill for an aspiring scientist. (On this topic, I’m reminded by the fact that Charles Darwin collected an enormous amount of evidence on natural selection over decades because he knew how general and groundbreaking would be the claim he was about to make).

**On feasibility**, the most common failure is between ambition and what’s actually possible. We researchers are a curious bunch; we want to discover the essence of intelligence or the secrets of the universe. But what experiments we can actually run is limited by the resources and time we have. Also, the more ambitious a research project, the more confounds one has to address, the more evidence one ought to collect and more alternative explanations one has to foreclose. So ambition and feasibility are often in tension.


### Phases of research

Follow these phases of research (roughly):

1.  **Exploration**. This is a time-boxed sprint to discover a potentially surprising claim that becomes the central object of the research project.
    
2.  **Research Question Sharpening**. Once we have a claim from exploration that seems counterintuitive, we put it through the three criteria described above.
    
3.  **Experiment Execution.** After an internal review and alignment on research question and its associated experimentation plan, we begin doing experiments.
    
4.  **Paper writing.** As research progresses, novel experiments suggest themselves, and new directions emerge. That’s part of the process. Paper writing only starts when a strong cohesive story starts emerging from the experiments.  