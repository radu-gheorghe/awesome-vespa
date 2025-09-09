# awesome-vespa
Unofficial, but curated list of Vespa.ai resources

## Table of Contents
- [Tutorials and guides](#tutorials-and-guides)
  - [Develop](#develop)
  - [Deploy/operate](#deployoperate)
  - [Watch](#watch)
- [Use-cases and studies](#use-cases-and-studies)
- [Non-English](#non-english)
  - [Japanese](#japanese)
- [Benchmarks](#benchmarks)
- [Tools and integrations](#tools-and-integrations)
  - [Write](#write)
  - [Read](#read)
  - [Monitor](#monitor)
  - [Deploy](#deploy)
- [Official resources](#official-resources)
  - [Tutorials and guides](#tutorials-and-guides-1)
  - [Learning tensors](#learning-tensors)
  - [Benchmarks](#benchmarks)
  - [Clients and integrations](#clients-and-integrations)
  - [Deploy](#deploy-1)
  - [Watch](#watch-1)
- [Consulting and training](#consulting-and-training)
- [Community](#community)
- [General Search/Information Retrieval resources](#general-search--information-retrieval-resources)

# Tutorials and guides

## Develop
* [Vespa Neural Search Tutorial](https://sease.io/2023/02/vespa-neural-search-tutorial.html)
* [How to quickly implement a text search system using pyvespa](https://blog.marvik.ai/2022/11/17/how-to-quickly-implement-a-text-search-system-using-pyvespa/)
* [Build Scalable Search Applications With Vespa](https://astconsulting.in/vespa/build-scalable-search-applications-vespa-2)
* [Efficient open-domain question-answering on Vespa.ai](https://towardsdatascience.com/efficient-open-domain-question-answering-on-vespa-ai-72562121dcd8/)

## Deploy/operate
* Deploying in Kubernetes: [part 1](https://medium.com/@kumargaurav.pandey/vespa-ai-a-devops-focussed-guide-part-1-2424c6056bd7) and [part 2](https://medium.com/@kumargaurav.pandey/vespa-ai-a-devops-focussed-guide-part-2-63873c4c75d6)

## Watch
* [Atita Arora – Understanding Vespa with a Lucene mindset](https://www.youtube.com/watch?v=_ML-QB0Zxvg)
* [Harrison Pim, Fred O'Loughlin – Building a knowledge graph for climate policy](https://www.youtube.com/watch?v=H6BhF6zSvp4&list=PLq-odUc2x7i8dTff006Wg2r0fsseSGrpJ)
* [Vespa-related presentations playlist](https://www.youtube.com/watch?v=pg_oPbYXTPU&list=PL74-V_Ao6U-HDEKIR3jM8O2GM5mCRNbiC)
* [Vespa-related podcasts playlist](https://www.youtube.com/watch?v=mI2DD6pnG80&list=PL74-V_Ao6U-FhwHvOXetIGuHSIsypr7RA)

# Use-cases and studies
* [Vinted's journey from Elasticsearch to Vespa](https://vinted.engineering/2024/09/05/goodbye-elasticsearch-hello-vespa)
* [Vinted's journey to data modernisation podcast](https://em360tech.com/podcasts/vinted-journey-data-modernisation-vespa)
* [Onyx: Open Source Gen-AI + Enterprise Search using Vespa for retrieval](https://github.com/onyx-dot-app/onyx). The Vespa-specific part is [here](https://github.com/onyx-dot-app/onyx/tree/main/backend/onyx/document_index/vespa)
* [AllenAI Ai2 ScholarQA](https://allenai.org/blog/ai2-scholarqa) - system for answering scientific queries and generating literature reviews

# Non-English

## Japanese
* [Yahoo! using Vespa! Flea market vector search - Product search with similar images](https://techblog.lycorp.co.jp/ja/20250908c)
* [Vespa Linguistics with Kuromoji Tokenizer](https://github.com/yahoojapan/vespa-kuromoji-linguistics)

# Benchmarks
* [Vespa on ANN Benchmarks](https://ann-benchmarks.com/index.html#hnsw(vespa))

# Tools and integrations

## Write
* [Kafka Connect Vespa](https://github.com/vinted/kafka-connect-vespa)

## Read
* [LangChain](https://python.langchain.com/docs/integrations/vectorstores/vespa/)
* [YQL parser](https://www.yql-parser.com/)

## Monitor
* [Vispana (by Spotify)](https://github.com/spotify/vispana)
* [Datadog Vespa integration](https://docs.datadoghq.com/integrations/vespa/)
* [Grafana dashboard](https://grafana.com/grafana/dashboards/11018-vespa-metrics-oss/)

## Deploy
* Helm charts [here](https://github.com/walmartlabs/vespa-helm) and [here](https://github.com/unoplat/vespa-helm-charts/tree/main)

# Official resources
* [Vespa website](https://vespa.ai/)
* [Vespa case studies](https://vespa.ai/case-studies) - who uses Vespa?

## Tutorials and guides
* [Sample applications](https://github.com/vespa-engine/sample-apps)
* [Vespa Guide for Solr Users](https://blog.vespa.ai/solr-vs-vespa/)
* [Pyvespa notebooks](https://vespa-engine.github.io/pyvespa/examples/Matryoshka_embeddings_in_Vespa-cloud.html) - lot of great examples of how to feed, query, infer models and evaluate results
* [Vespa documentation](https://docs.vespa.ai/) - our documentation is also a RAG app which lets you ask questions!
* [Visual RAG over PDFs with ColPali](https://huggingface.co/spaces/vespa-engine/colpali-vespa-visual-retrieval) - see how you can search any printable visually without ever converting to text!
* Lots more on the [Official Vespa blog](https://blog.vespa.ai/)

## Learning tensors
* [Tensor Playground](https://docs.vespa.ai/playground/) - check out examples and build your own
* [24 Tensor Playground Challenges (Advent)](https://blog.vespa.ai/advent-of-tensors-2023/)

## Benchmarks
* [Elasticsearch vs Vespa performance comparison](https://blog.vespa.ai/elasticsearch-vs-vespa-performance-comparison/). A comprehensive, reproducible report that goes in depth on Vespa performance characteristics

## Clients and integrations
* [PyVespa](https://vespa-engine.github.io/pyvespa/)
* [Vespa CLI](https://docs.vespa.ai/en/vespa-cli.html)
* [Java Feed Client](https://docs.vespa.ai/en/vespa-feed-client.html)
* [IDE Support](https://docs.vespa.ai/en/ide-support.html)
* [Logstash input and output plugins](https://github.com/vespa-engine/vespa/tree/master/integration/logstash-plugins). Tutorial blog post [here](https://blog.vespa.ai/logstash-vespa-tutorials/) and using Logstash to detect schema [here](https://blog.vespa.ai/logstash-quick-start/)
* LangGraph. Sample apps [here](https://github.com/vespa-engine/sample-apps/tree/master/examples/agentic-streamlit-chatbot) and blog post [here](https://blog.vespa.ai/retail-ai-assistant/)
* Llamaindex integration: [demo](https://docs.llamaindex.ai/en/stable/examples/vector_stores/VespaIndexDemo/) and [blog post](https://blog.vespa.ai/scaling-personal-ai-assistants-with-streaming-mode/)

## Deploy
* [Vespa Cloud](https://cloud.vespa.ai/)
* [Official Docker images](https://hub.docker.com/r/vespaengine/vespa/)
* [AWS Marketplace](https://aws.amazon.com/marketplace/seller-profile?id=seller-p6kptsjie2mzk)

## Watch
* [Getting Started with Vespa AI Search](https://www.youtube.com/watch?v=kaFDpIwY9F0)
* [Personalized Search: Advanced Ranking & Tensor framework](https://www.youtube.com/watch?v=362U7alsfuI)
* [The RAG Blueprint Overview](https://www.youtube.com/watch?v=su81gUdW1w8)
* [Official Vespa Youtube channel](https://www.youtube.com/channel/UCVXw_f6UHff8-V9FA1LMIiw)

# Consulting and training
* [SearchPlex](https://www.searchplex.net/vespa-ai-consulting)
* Sease [consulting](https://sease.io/consulting/vespa-consulting) and [training](https://sease.io/training/vespa-training-list)
* [Vespa AI Search Engine and Vector Database with Python](https://www.udemy.com/course/vespa-ai-search-engine-and-vector-database-with-python/)

# Community
* [Public Slack](https://slack.vespa.ai/)
* [Twitter](https://twitter.com/vespaengine)
* [Vespa Github org](https://github.com/vespa-engine)

# General Search / Information Retrieval Resources
* [awesome-information-retrieval](https://github.com/harpribot/awesome-information-retrieval)
* [awesome-search](https://github.com/frutik/awesome-search)
* [AI-Powered Search book](https://aipoweredsearch.com/)
