Natural Language Processing Parent
==================================

Description:

It a set of tools to build NLP. It's composed of:

    - chunker
    - stemmer
    - language detector
    - BTree / delaf / patricia tree / AGLX aggregation
    - data storage (memory operations, buffer, disk operations)
    - file storage (java primitives)
    - NER
    - glossaries
    - dictionaries
    - post tagging
    - stop words
    - vocabulary
    - tokenizer
    - clustering
    - commons (tools for tools)
    - big data (system for opening and handling big data files)
    - tagger
    - text normalization
    - splitter
    - grammer

Technology mappings:

    - chunker: Stanford chunker, apache NLP libraries, weka, freeling

    - stemmer: custom stemmer (dictionary based), heuristic stemmer, lovin stemmer, porter stemmer (stemization algorithms)

    - language detector: java custom language detection based in Markov trigrams

    - BTree / delaf / patricia tree / AGLX aggregation: custom made

    - data storage (memory operations, buffer, disk operations): java native, jni (java native interface) wrapper

    - file storage (java primitives): java native, tokyo cabinet, fm tokyo

    - NER: wiki repo for information retrieval. Freeling and Stanford.

    - glossaries: disk hash persistence (CRC access)

    - dictionaries: open data. Metadata is stored in the own dictionary.

    - post tagging: set of tools for semantic retrieval categorization

    - stop words: set of words without scientific weight (vary in function of language and universe). Algorithm: semantix data (80%)

    - vocabulary: skos (simple knowledge organization system: a common data model for sharing and linking knowledge). Openrdf, elmo, sesamo.

    - tokenizer: Stanford, Apache NLP, Freeling

    - clustering: weka

    - commons (tools for tools):

    - big data (system for opening and handling big data files): async string buffer

    - tagger: set of tools for word categorization. Stanford, Apache NLP, Freeling

    - text normalization: java native

    - splitter: java native, divides phrases in grammatical units

    - grammer: grammas (trained data from algorithmic discovery)

------------------

Use cases:

    - Keywords extraction

    - NER extraction

    - Solr injection

    - Feed normalization

    - Content generator

------------------

Dependencies:

    - jni dependencies (freeling binaries, tokyo binaries): work as competing consumers

    - maven clean install

    - deprecated repos (epub lib, freeling.jar, tokyo, openrdf, elmo, sesamo, siegmann)

    - corporate contents (usr/local/share/kyotodata)



