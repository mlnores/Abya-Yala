# Revision report

## Material changes

1. **Abstract**
   - Added hierarchical information to the representation problem.
   - Clarified that the algorithmic and curated states remain separately inspectable.
   - Identified OpenAlex specifically as the scholarly-graph source of bounded external context while preserving the separate meaning of the Research Horizon layer.

2. **Introduction: opening and knowledge-representation problem**
   - Introduced publisher catalogues in the opening paragraph as longitudinal knowledge resources combining heterogeneous natural-language descriptions, uneven metadata, evolving thematic structure, long time spans, documentary/editorial provenance, and relations with external scholarly infrastructures.
   - Stated the need to preserve semantic, temporal, hierarchical, and provenance information.

3. **Introduction: architecture, evidence layers, and contributions**
   - Made the analytical sequence explicit: heterogeneous scholarly text, machine-derived semantic units, documented expert curation, structured longitudinal representation, linkage with external scholarly infrastructures, and provenance-preserving cross-source interpretation.
   - Clarified that internal persistence, OpenAlex indexed activity, and Research Horizon retention are different constructs and are not combined into a synthetic global score.
   - Recast the first two contributions around explicit semantic units, hierarchy, longitudinal attributes, document-level provenance, and separately inspectable algorithmic and curated states.

4. **OpenAlex framing**
   - Described OpenAlex as an open scholarly graph and structured knowledge infrastructure containing works, authors, venues, institutions, and topics.
   - Kept the empirical use narrow: topic-country indexed activity for selected thematic units, without graph reasoning or publication-level linkage.

5. **Methods: expert-label provenance**
   - Corrected the label-review wording from plural "experts" to "the expert" to match the stated single-expert limitation.

6. **Discussion: hybrid interpretation and broader methodological relevance**
   - Identified the preserved algorithmic and curated states, including the bounded 389-record intervention, as hybrid machine/expert semantic interpretation with explicit provenance and inspectability.
   - Clarified that inspectability concerns recorded transformations, curation operations, and evidence, not the internal mechanics of the models.
   - Added a cautious general implication for knowledge-enhanced web intelligence, digital libraries, scientific data platforms, and open knowledge systems: heterogeneous text and structured external evidence can be integrated while each evidence layer retains its original semantics and scale.

## Deliberate terminology choices

- **Ontology:** not used to characterize the framework because no ontology is constructed and no ontology reasoning is performed. The Introduction explicitly distinguishes the architecture from an ontology.
- **Knowledge graph:** used only for OpenAlex, accurately described as an open scholarly graph. The paper's internal representation remains a semantic or structured thematic representation.
- **Explainable AI:** not used. The supportable claim concerns inspectable provenance, transformations, curation operations, and evidence layers rather than model-internal explanation.
- **Natural-language interface:** not claimed because the study provides neither a conversational interface nor question answering. The Discussion explicitly states that such an interface is not implemented.

## Remaining thematic-fit limitation

The paper fits the Special Issue through semantic knowledge representation, heterogeneous evidence integration, provenance, inspectable hybrid machine/expert interpretation, and use of an open scholarly graph as external context. Its empirical validation nevertheless remains a single-publisher proof-of-concept with one expert and bounded external comparisons. It does not implement an ontology, internal knowledge graph, formal graph reasoning, natural-language interface, or accessibility evaluation. Those gaps require new methods, systems, or validation data and cannot be resolved through wording alone.
