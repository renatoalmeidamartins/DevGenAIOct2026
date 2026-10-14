# DevGenAIOct2026

## Labs, courseware, survey, completion certificate
- [Labs and courseware](https://us-east-1.student.classrooms.aws.training/class/ilt%2313aefewrszxPMxB2jsC3mG)
- [MyClass](https://myclass.skillbuilder.aws), here you can get the certificate and fill the survey when attendance is marked complete. The class moves to the "past classes" section, and you will see the "Evaluation survey" button.

## Cloud quests
There are multiple cloud quests available. This is a gamified way to learn, similar to our labs, but more focused (smaller individual tasks). You navigate a whole island, and explore it. There are 2 free ones (Cloud practitioner and AI practitioner) and several that require a skill builder subscription. 
- [Landing page](https://cloudquest.skillbuilder.aws). 
- [Direct link to the AI practitioner one](https://skillbuilder.aws/learn/5YB3FCEE1H/aws-cloud-quest-generative-ai-practitioner/26A81MG83V)

## Class links
- Foundations
    - [Neural network zoo](https://www.asimovinstitute.org/neural-network-zoo/)
    - [Built-in algorithms and pretrained models in Amazon SageMaker](https://docs.aws.amazon.com/sagemaker/latest/dg/algos.html)
    - [What is deep learning?](https://aws.amazon.com/what-is/deep-learning/)
    - [What is Machine Learning?](https://aws.amazon.com/what-is/machine-learning/)
    - [What is Generative AI?](https://aws.amazon.com/what-is/generative-ai/)
    - [Attention is all you need paper](https://arxiv.org/pdf/1706.03762)
    - [What is a transformer in AI?](https://aws.amazon.com/what-is/transformers-in-artificial-intelligence/)
    - [What are Embeddings in Machine Learning?](https://aws.amazon.com/what-is/embeddings-in-machine-learning/)
    - [Embeddings playground](https://projector.tensorflow.org/)
- Bedrock main APIs, both support a streamed version, reducing the TTFT (time-to-first-token)
    - [InvokeModel](https://docs.aws.amazon.com/bedrock/latest/APIReference/API_runtime_InvokeModel.html)
    - [Converse](https://docs.aws.amazon.com/bedrock/latest/APIReference/API_runtime_Converse.html), trying to be model-independent
- [Explore AWS Capabilities by region](https://builder.aws.com/build/capabilities/explore)
- Prompt engineering and optimizations
    - [Bedrock doc on prompt design](https://docs.aws.amazon.com/bedrock/latest/userguide/design-a-prompt.html)
    - [What is Prompt Engineering?](https://aws.amazon.com/what-is/prompt-engineering/)
    - [Bedrock's documentation on prompt engineering concepts](https://docs.aws.amazon.com/bedrock/latest/userguide/prompt-engineering-guidelines.html). Pay attention to the links to provider-specific ones.
    - [Implementing advanced prompt engineering with Amazon Bedrock](https://aws.amazon.com/blogs/machine-learning/implementing-advanced-prompt-engineering-with-amazon-bedrock/)
    - [Construct and store reusable prompts with Prompt management in Amazon Bedrock](https://docs.aws.amazon.com/bedrock/latest/userguide/prompt-management.html)
    - [Amazon Bedrock introduces new advanced prompt optimization and migration tool](https://aws.amazon.com/blogs/aws/amazon-bedrock-introduces-new-advanced-prompt-optimization-and-migration-tool/)
    - [Prompt caching for faster model inference](https://docs.aws.amazon.com/bedrock/latest/userguide/prompt-caching.html)
- Knowledge bases and RAG patterns
    - [Vector database options](https://docs.aws.amazon.com/prescriptive-guidance/latest/choosing-an-aws-vector-database-for-rag-use-cases/vector-db-options.html), coming from AWS's prescriptive guidance on vector DB choices for RAG use cases. 
    - [Amazon DynamoDB now supports real-time vector search at any scale](https://aws.amazon.com/blogs/aws/amazon-dynamodb-now-supports-real-time-vector-search-at-any-scale/)
    - [Amazon Bedrock Knowledge Bases now supports hybrid search](https://aws.amazon.com/blogs/machine-learning/amazon-bedrock-knowledge-bases-now-supports-hybrid-search/)
    - [Improve the relevance of query responses with a reranker model in Amazon Bedrock](https://docs.aws.amazon.com/bedrock/latest/userguide/rerank.html)
    - [Introducing Amazon Bedrock Managed Knowledge Base for faster, more accurate enterprise AI applications](https://aws.amazon.com/blogs/aws/introducing-amazon-bedrock-managed-knowledge-base-for-faster-more-accurate-enterprise-ai-applications/)
    - [What is RAG (Retrieval-Augmented Generation)?](https://aws.amazon.com/what-is/retrieval-augmented-generation/)

- [REACT: SYNERGIZING REASONING AND ACTING IN LANGUAGE MODELS](https://arxiv.org/pdf/2210.03629)
- [Try the new console experience in Amazon Bedrock, optimized for Anthropic- and OpenAI-compatible APIs ](https://aws.amazon.com/blogs/aws/try-the-new-console-experience-in-amazon-bedrock-optimized-for-anthropic-and-openai-compatible-apis/)
- [Increase model invocation capacity with Provisioned Throughput in Amazon Bedrock](https://docs.aws.amazon.com/bedrock/latest/userguide/prov-throughput.html)
- [Set up a model invocation resource using inference profiles](https://docs.aws.amazon.com/bedrock/latest/userguide/inference-profiles.html), notice there are the cross-region (AWS-created) and the application ones, which allow you to "track costs and model usage" (quoted from the page)
- [Effective context engineering for AI agents](https://www.anthropic.com/engineering/effective-context-engineering-for-ai-agents)
- [Durable functions or Step Functions](https://docs.aws.amazon.com/lambda/latest/dg/durable-step-functions.html)
- [Conceptual discussion about memory in Langchain docs](https://docs.langchain.com/oss/python/concepts/memory)
- Langchain
    - [Messages abstractions](https://docs.langchain.com/oss/python/langchain/messages)
    - [prompts](https://reference.langchain.com/python/langchain-core/prompts)
    - [chains](https://reference.langchain.com/python/langchain-classic/chains/base/Chain)
    - [runnables](https://reference.langchain.com/python/langchain-core/runnables)
    - [RunnableWithMessageHistory](https://reference.langchain.com/python/langchain-core/runnables/history/RunnableWithMessageHistory), one example of a runnable
    - [DynamoDBChatMessageHistory](https://reference.langchain.com/python/langchain-community/chat_message_histories/dynamodb/DynamoDBChatMessageHistory)
- [Built-in metric evaluator prompts for model-as-a-judge evaluation jobs](https://docs.aws.amazon.com/bedrock/latest/userguide/model-evaluation-type-judge-prompt.html)
- [Use prompt datasets for model evaluation in Amazon Bedrock](https://docs.aws.amazon.com/bedrock/latest/userguide/model-evaluation-prompt-datasets.html)
- [RAGAS built-in metrics](https://docs.ragas.io/en/stable/concepts/metrics/available_metrics/)
- [Binary Model Insights](https://docs.aws.amazon.com/machine-learning/latest/dg/binary-model-insights.html), this is documentation from a long-gone service (Amazon Machine learning), but it is a nice summary of precision, accuracy, and others.
- [Evaluate models or RAG systems using Amazon Bedrock Evaluations – Now generally available](https://aws.amazon.com/blogs/machine-learning/evaluate-models-or-rag-systems-using-amazon-bedrock-evaluations-now-generally-available/)
- [Understanding intelligent prompt routing in Amazon Bedrock](https://docs.aws.amazon.com/bedrock/latest/userguide/prompt-routing.html)
- [Use Amazon Bedrock Intelligent Prompt Routing for cost and latency benefits](https://aws.amazon.com/blogs/machine-learning/use-amazon-bedrock-intelligent-prompt-routing-for-cost-and-latency-benefits/)
- [Optimize model inference for latency](https://docs.aws.amazon.com/bedrock/latest/userguide/latency-optimized-inference.html)
- [Responsible AI](https://aws.amazon.com/ai/responsible-ai/)
- [FuzzyAI Fuzzer](https://github.com/cyberark/fuzzyai): The FuzzyAI Fuzzer is a powerful tool for automated LLM fuzzing. It is designed to help developers and security researchers identify jailbreaks and mitigate potential security vulnerabilities in their LLM APIs.
- [AWS re:Invent 2024 - Mitigating the OWASP Top 10 for LLMs: Build secure gen AI applications (AIM283)](https://www.youtube.com/watch?v=ewxCqXYoz4A)
- [Minimize AI hallucinations and deliver up to 99% verification accuracy with Automated Reasoning checks: Now available](https://aws.amazon.com/blogs/aws/minimize-ai-hallucinations-and-deliver-up-to-99-verification-accuracy-with-automated-reasoning-checks-now-available/)
- [Get started with Nova Act](https://docs.aws.amazon.com/nova-act/latest/userguide/getting-started.html)
- [CrewAI Quickstart](https://docs.crewai.com/v1.15.28/en/quickstart)
- [Langchain Agents](https://docs.langchain.com/oss/python/langchain/agents)
- [Building a LangGraph Agent from Scratch](https://towardsdatascience.com/building-a-langgraph-agent-from-scratch/)
- [Model Context Protocol - MCP](https://modelcontextprotocol.io/docs/2026-07-28/getting-started/intro)
- [A2A repo](https://github.com/a2aproject/a2a)
- [Announcing the Agent2Agent Protocol (A2A)](https://developers.googleblog.com/en/a2a-a-new-era-of-agent-interoperability/)
- [Introducing Strands Agents, an Open Source AI Agents SDK](https://aws.amazon.com/blogs/opensource/introducing-strands-agents-an-open-source-ai-agents-sdk/)
- [Bedrock Flows samples](https://github.com/aws-samples/amazon-bedrock-flows-samples)
- [Open source MCP servers for AWS](https://github.com/awslabs/mcp)
- Agentcore
    - [Amazon Bedrock AgentCore payments is now generally available: Enabling agents to transact safely and autonomously at scale](https://aws.amazon.com/blogs/machine-learning/amazon-bedrock-agentcore-payments-is-now-generally-available-enabling-agents-to-transact-safely-and-autonomously-at-scale/)
    - [The future of managing agents at scale: AWS Agent Registry now in preview](https://aws.amazon.com/blogs/machine-learning/the-future-of-managing-agents-at-scale-aws-agent-registry-now-in-preview/)
    - [Agentcore SDK](https://github.com/aws/bedrock-agentcore-sdk-python)
    - [Deployment strategies](https://docs.aws.amazon.com/bedrock-agentcore/latest/devguide/runtime-get-started-code-deploy.html), notice that zip deployment is the preferred way
    - [Identity provider setup and configuration](https://docs.aws.amazon.com/bedrock-agentcore/latest/devguide/identity-idps.html), for both inbound and outbound auth
    - [Search for tools in your AgentCore gateway with a natural language query](https://docs.aws.amazon.com/bedrock-agentcore/latest/devguide/gateway-using-mcp-semantic-search.html)
    - [Long-temr memory extraction prompts in Agentcore](https://docs.aws.amazon.com/bedrock-agentcore/latest/devguide/built-in-strategies.html)
    - [Policy in Amazon Bedrock AgentCore: Control Agent Interactions](https://docs.aws.amazon.com/bedrock-agentcore/latest/devguide/policy.html)
    - [https://github.com/aws/agentcore-cli](Agentcore CLI)
    - [Get to your first working agent in minutes: Announcing new features in Amazon Bedrock AgentCore](https://aws.amazon.com/blogs/machine-learning/get-to-your-first-working-agent-in-minutes-announcing-new-features-in-amazon-bedrock-agentcore/)