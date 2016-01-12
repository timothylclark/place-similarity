# Place similarity for determining infectious disease vector risks

## Overview
Humans tend to think in analogs. For example, I did something during situation A...should I do that same thing during situation B? This depends on how similar the situations might be, either perceptually or in actuality. So goes the theory of analogies and, computationally, [case based reasoning](https://en.wikipedia.org/wiki/Case-based_reasoning).

Wouldn't it be great if we could apply this to evaluations of how similar two or more places are? For example, from the perspective of a user, how similar are Washington DC and Dallas? It depends on what attributes a user cares about...maybe it's the restaurant scene, or how big the hair is, or how susceptible to infectious disease a particular area is?

That's what I'd like this project to be.

#### Goals/Needs

- Develop disease likelihood use cases
- Integrate existing ontologies ([VectorBase](https://www.vectorbase.org/), [EnvO](https://github.com/EnvironmentOntology/envo), etc.)
- Investigate suitable backend (Neo4j, OrientDB, etc)
- Google Knowledge Graph search results?
- Find data (DBPedia, GKG, etc.)
- Scientific justification - similarity metrics related to geospatial coverage, attributes, links to other things...
 - topic modeling using [gensim](https://pypi.python.org/pypi/gensim) or similar
- write prototype in Python

### Stay tuned
