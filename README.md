### Ryan Burch
<sub>STAFF AI/ML ENGINEER &nbsp;·&nbsp; FORWARD DEPLOYED &nbsp;·&nbsp; 12+ YEARS</sub>


<img src="https://quickchart.io/graphviz?format=svg&graph=digraph%20G%20%7B%0Arankdir%3DLR%3B%20bgcolor%3D%22transparent%22%3B%20nodesep%3D0.35%3B%20ranksep%3D0.45%3B%0Anode%20%5Bshape%3Dbox%20style%3D%22rounded%2Cfilled%22%20fontname%3D%22Helvetica%22%20fontsize%3D13%20color%3D%22%230e7490%22%20fillcolor%3D%22%23ecfeff%22%20fontcolor%3D%22%230f172a%22%20penwidth%3D1.4%20margin%3D%220.18%2C0.1%22%5D%3B%0Aedge%20%5Bcolor%3D%22%2364748b%22%20arrowsize%3D0.7%20penwidth%3D1.2%5D%3B%0Ae%20%5Blabel%3D%22Events%5CnKinesis%20%C2%B7%20Flink%22%5D%3B%0Ar%20%5Blabel%3D%22Retrieval%5Cnhybrid%20search%20%C2%B7%20rerank%22%5D%3B%0Aa%20%5Blabel%3D%22Agents%5CnLangGraph%20%C2%B7%20Bedrock%22%5D%3B%0Ag%20%5Blabel%3D%22Guardrails%5Cngrounding%20checks%22%5D%3B%0Ao%20%5Blabel%3D%22Answer%5Cnwith%20citations%22%20fillcolor%3D%22%230e7490%22%20fontcolor%3D%22white%22%5D%3B%0At%20%5Blabel%3D%22Audit%20trail%5Cnevery%20call%20traced%22%20shape%3Dcylinder%20style%3Dfilled%20fillcolor%3D%22%23f1f5f9%22%20color%3D%22%2394a3b8%22%5D%3B%0Ae%20-%3E%20a%3B%20r%20-%3E%20a%3B%20a%20-%3E%20g%3B%20g%20-%3E%20o%3B%0Aa%20-%3E%20t%20%5Bstyle%3Ddashed%5D%3B%20g%20-%3E%20t%20%5Bstyle%3Ddashed%5D%3B%0A%7D" width="100%" alt="How my AI systems fit together: events and retrieval feed agents, guardrails check them, and every call is traced" />


> [!NOTE]
> I architect generative AI systems that hold up in production, working close to the teams who will use them and taking each one from whiteboard to production. My path runs from early machine learning in digital health through payments infrastructure to enterprise life sciences.


#### Things I've shipped


1. **Streamsense** scores operational events as they arrive and calls a model only when a signal crosses a threshold.<br><kbd>Kinesis</kbd> <kbd>Flink</kbd> <kbd>Lambda</kbd> <kbd>Bedrock</kbd>
2. **Dossier** answers questions over regulatory submissions and SOPs, citing the exact passage and version.<br><kbd>OpenSearch</kbd> <kbd>LangChain</kbd> <kbd>Glue</kbd> <kbd>FastAPI</kbd>
3. **Auditrail** records tamper-evident lineage for every LLM request, from prompt template to final response.<br><kbd>OpenTelemetry</kbd> <kbd>Firehose</kbd> <kbd>S3 Object Lock</kbd> <kbd>Athena</kbd>
4. **Supply Swarm** runs LangGraph agents for demand, inventory and suppliers, pausing for a planner on high-impact changes.<br><kbd>LangGraph</kbd> <kbd>Bedrock</kbd> <kbd>Aurora</kbd> <kbd>Step Functions</kbd>
5. **Rerankr** is a shared retrieval service that fuses keyword and vector search and re-embeds without downtime.<br><kbd>BM25</kbd> <kbd>FAISS</kbd> <kbd>Cross-encoders</kbd> <kbd>Kubernetes</kbd>
6. **Bumper** screens model inputs and outputs and blocks answers the evidence doesn't support.<br><kbd>Bedrock Guardrails</kbd> <kbd>Presidio</kbd> <kbd>LangSmith</kbd>


#### Rules I design by


> [!TIP]
> **Grounded by default.** Answers carry citations back to source documents.


> [!IMPORTANT]
> **Observable.** Every prompt, retrieval and tool call is traceable end to end.


> [!WARNING]
> **Compliance-ready.** Access, retention and audit are designed in, not bolted on, to stand up to GDPR and SOX review.

