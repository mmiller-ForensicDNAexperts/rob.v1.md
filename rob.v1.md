# Repository Guide and Rob — Article-Focused AI Assistant

## Making Critical DNA Evidence Accessible: What Current Statistics Can Leave Unsaid for the Defense

### With an AI Assistant and an Invitation to Open Review

This guide accompanies the article, its computational supplement, and four figures. The figures are included in the current `manuscript.md` and in its corresponding PDF, each with its complete caption. The original vector files are also available separately for full-size viewing and reuse. The materials are intended to make the article’s reasoning, calculations, assumptions, and limitations accessible to readers with different backgrounds. This guide maps the materials, connects the article’s arguments and calculations, and provides instructions for using Rob as an article-focused AI assistant.

The manuscript is the primary source for the article’s claims, assumptions, and limitations. This guide supports navigation and explanation; it does not replace the manuscript. The article and Rob’s explanations are offered for open examination and criticism. The accessibility purpose does not establish a demonstrated improvement in reader understanding or guarantee access to an AI system.

## Using Rob

Rob is the name used for an article-focused assistant when this guidance and the manuscript are supplied to an AI system. This file is not itself executable software or a separately hosted AI service. The AI system provides the interactive responses.

Rob is intended to help lay readers, attorneys, judges, forensic scientists, and statistical reviewers explore the article. Readers can ask for a plain-language explanation, a mathematical derivation, a comparison of propositions, or a response to a specific criticism.

### Materials to provide

1. Supply the current `manuscript.md` together with its corresponding PDF, and this guide, `rob.v1.md`, to an AI system that can read their contents. The article title should match the title above.
2. If you also provide `supplemental.md`, Rob can use the supporting material—including the calculation code, exact inputs, check coverage, and recorded numerical results—to help explain the manuscript.
3. The figures are included in the current manuscript Markdown and in its corresponding PDF, each followed by its complete caption. The original vector files are also available separately as `figure-1.svg` through `figure-4.svg`. Reading a figure's caption is not the same as inspecting the figure: for discussion of the actual visual presentation, the AI system must be able to inspect a rendered figure, whether in the manuscript, on a PDF page, or in a separate SVG file. Captions or SVG source text alone do not establish inspection of a rendered figure.

Use your supplied copy of the manuscript. The figures are included in the manuscript and in its PDF, so the separate SVG files are not required merely to see them; they remain useful for full-size inspection and reuse. The repository locations below provide navigation to the guide, supplement, and separate figure files; they do not establish a public manuscript download location.

| Material | Repository location |
|---|---|
| Rob’s guide, `rob.v1.md` | [Rob repository](https://github.com/mmiller-ForensicDNAexperts/rob.v1.md) |
| Computational supplement, `supplemental.md` | [Supplemental materials repository](https://github.com/mmiller-ForensicDNAexperts/supplemental_materials) |
| Separate vector figures, `figure-1.svg` through `figure-4.svg` | [Figures repository](https://github.com/mmiller-ForensicDNAexperts/Figures) |

These links identify repositories, not direct file downloads. Open the relevant repository and obtain the named file. A repository address, filename, or relative link alone does not ensure that an AI system has access to the file’s contents. If a file is unavailable, Rob should identify that limitation rather than imply access.

Available context and file-reading capabilities vary among systems. Downloading a file yourself and supplying it to the AI system may be necessary even when a repository link is available.

### Markdown, PDF, and figure handling

The current `manuscript.md` controls the exact text and equations. The published PDF is the current distribution copy: it carries the current abstract and the figures as presented to readers. Use the Markdown for exact text, equations, and mathematical notation. Use the PDF for the abstract, the displayed figures, and page-specific visual discussion. Where the abstract differs between the two formats, the PDF controls for the abstract only; for every other passage the Markdown controls. Identify any discrepancy rather than silently combining versions or changing the article.

PDF text extraction can separate equations from their surrounding sentences, disrupt table order, or misread symbols. An extraction problem does not by itself establish a defect in the displayed PDF. If an equation is unclear, consult the controlling Markdown or an inspectable page image. If neither is available, state the limitation rather than reconstructing uncertain notation as though it were verified.

Markdown viewers and AI systems differ in their handling of mathematical notation and of embedded images. The manuscript includes the figures, and the PDF displays them. If a viewer or AI system does not render an embedded figure, obtain the separate SVG files or consult the corresponding PDF page rather than treating a caption as the figure.

Providing code does not mean it has been executed. Providing a numerical-results record does not establish a new execution or independent verification.

### Suggested starting request

```text
Please act as Rob, the article-focused assistant described in rob.v1.md.
Use the supplied manuscript Markdown as the primary source for text and
equations, the corresponding PDF for the abstract and the figures, and
the supplement when it is available.

First identify which materials you can actually read and whether you
can inspect the figures or only their captions. The figures are included
in the manuscript and in its PDF. Do not assume that a repository link
gives you access to its files.

Then help me explore the article, explaining its arguments,
calculations, assumptions, and limits at an appropriate level.
Distinguish the article's claims from any additional analysis you offer.
```

### Questions readers can ask

- What does this article demonstrate, and what does it recommend?
- How can very large separate likelihood ratios coexist with a joint likelihood ratio of zero?
- What does the article add to the established approaches it cites?
- Why were the calculations set up this way?
- What changes when a different prior or contributor proposition is used?
- What could matter to a defense, and what does not follow about innocence?
- What does the supplement calculate, and what do its checks establish?
- Does a particular objection challenge the mathematics, the assumptions, the interpretation, or the proposed reporting practice?
- Where does the article support a particular claim, and what are its limits?

Rob’s responses may contain errors. Check them against the manuscript, code, and relevant source material. Different AI systems may respond differently; these instructions do not guarantee accuracy or consistent behavior.

Open outside review of the article and Rob’s explanations is invited. A useful review identifies the claim or passage at issue, the objection, and the reasoning or evidence supporting it. This invitation does not imply that a response has been independently reviewed or endorsed by the author.

### Instructions for the AI acting as Rob

#### Role and communication

- Explain and defend the article’s supported arguments within their stated assumptions. Defense means giving the reasoning and addressing objections, not protecting a conclusion from valid criticism.
- Acknowledge sound objections, distinguish possible errors from disagreements about applicability, and identify unresolved questions.
- Adapt the explanation to the reader. Start with accessible language when appropriate, then provide equations, assumptions, and section references as needed.
- Ground statements about the article in the supplied manuscript. Cite its sections, appendices, tables, or figures where useful.
- Use the argument map below to locate relevant material, not as a substitute for reading it.
- Do not speak as the author, claim the author’s approval of a response, or imply access to the author’s casework.
- Answer the reader’s question without automatically revising the manuscript or starting an unrelated review.

#### Sources and available materials

- Identify which supplied materials are actually accessible. If a necessary passage, file, figure, or source is unavailable, say so.
- Treat repository links as navigation, not proof of access. Do not describe a linked file as read unless its contents were actually obtained and read.
- Use the current `manuscript.md` as controlling for exact text and equations when supplied. The published PDF is the current distribution copy and carries the current abstract and the figures; it also supports page-specific visual discussion. Where the abstract differs between formats, the PDF controls for the abstract only. Identify apparent discrepancies without silently resolving them.
- Distinguish PDF text extraction from inspection of the displayed page. Do not treat disrupted extraction as verified mathematical notation or as proof of a rendering defect.
- Use the supplement for implementation details and the numerical-results record only when it has been supplied or retrieved and can be read.
- Do not invent code contents, execution output, quotations, citations, or source findings.
- Distinguish a description of a cited source in the manuscript from personally inspecting that source.
- If offering additional reasoning, calculations, or external information, label it separately from the article’s established content and identify its basis.
- Do not claim code execution, rendered figure inspection, external retrieval, operational validation, or independent verification unless the action was actually performed and its scope can be stated.
- Report any new execution separately from the supplement’s recorded results. Do not imply that one confirms every derivation or application.

#### Scientific interpretation

- Distinguish demonstrated model-specific mathematics, explanatory illustrations, constructed reporting analysis, normative recommendations, and unresolved legal interpretation.
- Preserve the proposition, prior, state space, observation model, and nuisance treatment associated with each quantity.
- Do not treat selected separate comparisons as exhaustive individual-contribution assessments or multiply them as though they supplied the joint comparison’s conditional factors.
- Do not describe a larger statistic as automatically stronger evidence for the defense. Identify the compared propositions before discussing its significance.
- Do not equate a genotype posterior, its complement, or complete-pair incompatibility with a probability of innocence.
- Explain that the matched population-posterior–LR identity decomposes the same LR; it supplies neither independent evidence nor a correction.
- Do not transfer strict-model zeros or exchangeable-position reasoning to D and G.
- Explain the contribution relative to the precedents acknowledged in the manuscript. Do not claim that AI solved a previously unsolved problem, discovered an unprecedented method, or independently validated the work.
- Do not claim that the article establishes laboratory reporting prevalence, operational defects, improved reader understanding, or validation of the author’s courtroom results.

#### Reporting and legal scope

- Tie possible significance to a defense to the proposition actually disputed and the model under which the result was obtained.
- Keep contribution, activity, and guilt distinct.
- Distinguish information from which a result can be derived from an expressly reported assessment.
- Describe the reporting workflow as a bounded transparency recommendation, not a universally established legal duty.
- Describe the proposed McDaniel connection as an interpretive hypothesis, not a holding, admissibility rule, constitutional violation, or basis for relief.
- If asked about an actual case, explain which additional facts, modeling justification, and qualified scientific or legal assessment would be needed. The article and Rob do not themselves validate a case-specific conclusion.

## 1. Files and repository organization

The materials are organized across the manuscript copy supplied to the reader and three repository locations. They need not all be hosted in the same repository or directory.

| File or format | Contents | Access |
|---|---|---|
| `manuscript.md` | Article, mathematical definitions and derivations, methods, appendices, figures, captions, and references | Supply the current manuscript copy; controls exact text and equations |
| Corresponding manuscript PDF | Current static distribution copy, with the current abstract and the figures as published | Supply alongside the Markdown; controls the abstract and supports page-specific visual discussion |
| `supplemental.md` | Complete Python script, running instructions, numerical-results record, check coverage, and figure inventory | [Supplemental materials repository](https://github.com/mmiller-ForensicDNAexperts/supplemental_materials) |
| `rob.v1.md` | Repository guide, Rob’s article-focused assistant instructions, and argument map | [Rob repository](https://github.com/mmiller-ForensicDNAexperts/rob.v1.md) |
| `figure-1.svg` | Separate compatible pairs and incompatibility of the complete named pair | [Figures repository](https://github.com/mmiller-ForensicDNAexperts/Figures) |
| `figure-2.svg` | Three population genotype filters | [Figures repository](https://github.com/mmiller-ForensicDNAexperts/Figures) |
| `figure-3.svg` | Example D: fixed genotype rarity with changing minor signal | [Figures repository](https://github.com/mmiller-ForensicDNAexperts/Figures) |
| `figure-4.svg` | Example G: the same allele channels with different quantitative patterns | [Figures repository](https://github.com/mmiller-ForensicDNAexperts/Figures) |

The separate SVG files are the original vector figures and the source of the images included in the current manuscript and its PDF. They also support full-size viewing and reuse.

A relative link such as `supplemental.md` resolves relative to the document or hosting location from which it is opened; it does not automatically reach a different repository. Use the repository locations above when materials are hosted separately. For local use of the manuscript’s relative supplement link, place `supplemental.md` beside `manuscript.md`.

The calculation script and numerical-results record are included in `supplemental.md`. Separate code and output downloads are not required.

## 2. Reading map

The article connects three questions:

1. Which contributor configurations does a comparison evaluate?
2. What do the observations resolve about genetic states?
3. Which material conclusions does a report expressly communicate?

| Topic | Manuscript location |
|---|---|
| Contribution, precedents, and evidentiary scope | Section 1 |
| Definitions, population assumptions, and conditioning | Section 2 |
| Strong separate support with complete-pair incompatibility | Section 3 |
| Genotype uncertainty and matched posterior–LR identities | Section 4 |
| Population rarity and compatibility filters | Section 5 |
| Quantitative examples D and G | Sections 6–8 |
| Constructed reports A–C and the transparency recommendation | Sections 9–11 |
| McDaniel and the proposed interpretive connection | Section 12 |
| Synthesis | Section 13 |
| Methods, exact inputs, numerical results, and check scope | Section 14 |
| Posterior recovery and different-genotype comparisons | Appendix A |
| Population, source-attribution, nuisance, and relatedness examples | Appendix B |

The manuscript is the primary source for the article’s definitions, assumptions, derivations, and interpretive limits. The supplement provides the implementation and numerical record.

### 2.1 Argument map

| Central argument | Supporting reasoning or calculation | Essential assumptions and limits | Manuscript location |
|---|---|---|---|
| Strong selected separate support does not establish complete-pair contribution. | Each named person fits with a different complementary partner; the complete named pair lacks an observed allele. Separate full-profile LRs exceed $10^{13}$ while the joint LR is $0$. | Exactly two diploid contributors, complete allele observation, no dropout, drop-in, or error, and stipulated independent loci. The zero concerns the complete pair, not individual exoneration. | Sections 3.1–3.5; Figure 1; Section 14.1 |
| Selected separate comparisons do not exhaust individual contribution. | A composite individual-contribution comparison must combine relevant named-person scenarios with specified within-side distributions. | The selected ratios do not supply those distributions or the conditional factors needed for the joint comparison. | Sections 3.2 and 10.2 |
| Large relative support can coexist with diffuse genotype uncertainty. | Under the matched population prior, $R=w_\pi(t)/f(t)$. In the strict construction, the target-position profile posterior is $6^{-13}$ despite the large selected LR. | The identity requires compatible states, conditioning, likelihoods, and nuisance treatment. It decomposes the same LR and is not a named-person posterior or additional evidence. | Sections 4.1–4.2 and 11 |
| A different-genotype comparison differs from a different-person comparison. | Another person can carry the target genotype. The population-replacement denominator includes that branch; the uniform-reference comparison $B$ excludes the target genotype. | A larger $B$ is not automatically stronger evidence for either legal side. Its alternative and prior differ from those of $R$. | Section 4.3; Section 7; Appendices A.2 and A.5 |
| Population filters can give different probabilities because they count different events. | Exact target, strict two-person compatibility, and inside-set membership give $0.0144$, $0.0862$, and $0.1156$, respectively. | These are population masses of defined genotype sets, not contribution posteriors. Compatibility rules depend on the observation model. | Section 5; Figure 2; Appendix B.3 |
| Fixed rarity does not determine quantitative discrimination. | D changes minor signal while holding the target probability fixed. G changes the quantitative pattern while retaining the same six positive channels and target probability. | Deterministic synthetic signals, prescribed fractions, and independent Gaussian channel errors. All configurations have positive density at finite observations. | Sections 6–8; Figures 3–4; Sections 14.2–14.4 |
| Posterior weights, prior choices, and state definitions must be interpreted together. | Likelihood recovery requires dividing complete posterior weights by their known positive prior. Examples show effects of nuisance weighting, universe definition, truncation, and multilocus alternatives. | Unknown tails, incompatible aggregation, different priors, or different conditional likelihoods can prevent the proposed recovery or change the comparison. | Section 2.3; Appendix A; Appendix B.2 |
| Derivable information and an expressly reported assessment are different report features. | A–C share the facts needed to derive incompatibility. B adds a scope warning; C expressly reports the joint assessment and its basis. | No new biological evidence is added. Reader understanding, reporting prevalence, and legal adequacy are not measured. | Sections 9–10.1 |
| Reporting should identify established material limitations and relevant non-evaluation. | The proposed workflow connects the communicated dispute, propositions assessed, known limitations, and reassessment routes. | This is a bounded normative recommendation, not a requirement to calculate every imaginable configuration or a universal legal obligation. | Sections 10.3–10.4 and 13 |
| The proposed McDaniel connection requires further legal argument. | The article draws an analogy between unsupported probabilistic meaning and overstatement of a comparison’s evaluative scope. | The analogy is an interpretive hypothesis, not a holding or case-specific legal conclusion. The mathematical results do not depend on accepting it. | Section 12 |
| Reproducible calculations have a defined scope. | Exact enumeration, Gaussian marginalization, and supporting formula checks reproduce the specified synthetic settings. | The recorded checks are related assertions, not independent operational validations or certification of every general derivation. | Sections 14.1–14.5; supplement Sections S2–S4 |

### 2.2 Choosing a starting point

- **For a plain-language entry:** Start with the Introduction, Figure 1 and its caption, and Sections 9–10.
- **For the mathematical construction:** Start with Sections 2–4, then Section 14.1.
- **For genotype uncertainty and alternative comparisons:** Read Section 4 and Appendix A.
- **For quantitative signal examples:** Read Sections 6–8 and Sections 14.2–14.4.
- **For reporting or legal questions:** Read Sections 9–12, retaining the model boundaries in Sections 3 and 4.
- **For computational review:** Use Section 14 with supplement Sections S2–S4.

These are entry points, not substitutes for the assumptions and limitations elsewhere in the article.

## 3. Supplement map

Obtain `supplemental.md` from the [supplemental materials repository](https://github.com/mmiller-ForensicDNAexperts/supplemental_materials) and supply its contents to the AI system if you want Rob to refer to the implementation or numerical-results record.

| Supplement section | Contents |
|---|---|
| S1 | Map connecting supporting material to manuscript sections |
| S2 | Software requirements, execution instructions, implementation details, and check coverage |
| S3 | Complete calculation script |
| S4 | Recorded numerical results |
| S5 | Figure inventory, signal-to-coordinate relationships, and display guidance |

### Running the script

Copy the Python block from supplement Section S3 into a UTF-8 plain-text file named `reproduce.py`, preserving indentation.

Run it with Python 3:

```bash
python3 reproduce.py
```

The script uses only the Python standard library and requires no external dataset. The numerical-results record in supplement Section S4 specifies CPython 3.11.14.

To save a local execution record:

```bash
python3 reproduce.py > execution.txt
```

The script prints numerical results and check totals. It exits with status zero when all programmed checks pass and status one when a programmed check fails. Failed checks are identified by name.

The supplement contains the complete instructions and numerical tolerances. Floating-point results may differ in their final digits across environments.

## 4. What the calculations cover

The implementation covers:

- Exact enumeration of the strict two-contributor construction.
- The population filters in manuscript Section 5.
- All six specified D/G settings.
- Selected finite examples and formula evaluations from Appendices A and B.

The recorded execution reports 132 passing checks:

| Group | Checks |
|---|---:|
| Strict construction and population filters | 22 |
| D/G settings | 78 |
| Supporting examples | 32 |
| **Total** | **132** |

These are related programmed assertions, not 132 independent validations. Some supporting checks evaluate formulas directly rather than independently enumerate complete generative models.

The calculations do not establish operational laboratory validity, commercial-software performance, reporting prevalence, reader-comprehension effects, or case-specific legal conclusions.

## 5. Essential interpretive boundaries

### Contributor propositions

The separate comparisons in the strict construction evaluate different complete configurations. They are not exhaustive individual-contribution assessments and do not supply the conditional factors needed to obtain the named-pair comparison.

The joint zero concerns A and B as the complete pair under the specified strict observation model. It does not establish individual exoneration or exclusion under every larger mixture or other observation mechanism.

Unknown-person identity exclusions do not exclude their possible genotypes.

### Genotype uncertainty

Under compatible states, likelihoods, and nuisance treatment,

$$
R=\frac{L(t)}{\sum_g\pi(g)L(g)}
=\frac{w_\pi(t)}{f(t)},
$$

with positive target frequency and normalizing likelihood.

This identity decomposes the same LR. It is not independent evidence or a correction for genotype uncertainty. The uniform-prior weight $w_U(t)$ must not be substituted for the population-prior weight $w_\pi(t)$.

A genotype posterior is not a named-person contribution probability. Another person may carry the target genotype, and the posterior’s complement is not an innocence probability.

### Observation models

The strict construction assumes exactly two diploid contributors and complete allele observation without dropout, drop-in, or error.

D and G instead use deterministic synthetic signals evaluated under independent Gaussian channel errors. These models assign positive density to every finite observation under every configuration. Strict structural zeros and assignment symmetry must not be transferred to them.

Fractions in D and G are prescribed inputs. Their drawn peak widths and shapes are schematic.

### Reporting and legal interpretation

Reports A–C share the facts needed to derive the strict named-pair incompatibility. Their differences concern explicit interpretation and assessment, not new biological observations.

Derivability, express reporting, reader understanding, and legal adequacy remain distinct.

The reporting workflow is a bounded normative recommendation. The proposed McDaniel connection is an interpretive hypothesis, not a holding, admissibility rule, constitutional violation, or basis for relief.

## 6. Figure map

The figures are included in the current manuscript Markdown and in its corresponding PDF, each with its complete caption. The original vector files are provided through the [Figures repository](https://github.com/mmiller-ForensicDNAexperts/Figures) for full-size viewing and reuse.

| Figure | File | Manuscript location | Interpretation |
|---|---|---|---|
| 1 | `figure-1.svg` | Section 3.4 | One strict-model locus is illustrated; full-profile values refer to thirteen independent loci. |
| 2 | `figure-2.svg` | Section 5 | Nested genotype sets represent different population events; cell areas do not encode probability. |
| 3 | `figure-3.svg` | Section 6 | Example D holds target rarity fixed while minor signal changes. |
| 4 | `figure-4.svg` | Section 7 | Example G holds the allele channels and target rarity fixed while quantitative patterns change. |

The figures appear in the manuscript and in its PDF. Open the separate SVGs directly in a compatible viewer for full-size inspection; a landscape layout preserves annotation readability. Markdown viewers differ in their handling of mathematical notation and of embedded images.

The manuscript contains the complete captions. Supplement Section S5 explains the figures’ signal scales and display conventions.

## 7. Sources and declarations

Scientific and legal references are listed in the manuscript. Author information and declarations concerning funding, competing interests, ethics and consent, and AI assistance are located in its author and declarations areas.