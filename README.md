<img src="assets/vital-logo-black.png" alt="Vital AI Logo" width="200">

# vital-agent-ecosystem

The Vital Agent Ecosystem provides a collection of software components, knowledge models, and interfaces that together provide an A.I. Agent deployment and management platform.

Commercial support of the Vital AI Agent Ecosystem is provided by Vital AI: [https://www.vital.ai](https://www.vital.ai)

This repository provides documentation and resources for the Agent Ecosystem as a whole.

Documentation is managed here: [https://docs.vital.ai/agent-ecosystem](https://docs.vital.ai/agent-ecosystem).

# Agent Ecosystem Architecture

The following diagram shows the Ecosystem components in a deployment. Components are horizontally scalable.

A Kafka Cluster, shown in the center of the diagram, is used for messaging across the deployment.

The Processor is used to manage Agent Containers.

<img src="assets/agent-ecosystem-arch.png" alt="Vital Agent Ecosystem Architecture">

The Agent Ecosystem is comprised of the individual components in the table below, which are maintained in separate repositories.

| Name                         | Link                                                             | Description                                                    |
|------------------------------|------------------------------------------------------------------|----------------------------------------------------------------|
| vitalhome-aimp               | [Link](https://github.com/vital-ai/vitalhome-aimp)               | Knowledge Model for Artificial Intelligence Messaging Protocol |
| vital-vitalsigns-python      | [Link](https://github.com/vital-ai/vital-vitalsigns-python)      | Knowledge Model Runtime and Tools (Python)                     |
| vitalhome-haley              | [Link](https://github.com/vital-ai/vitalhome-haley)              | Knowledge Model (Haley-KG) for core Knowledge Graph concepts   |
| kgraphservice                | [Link](https://github.com/vital-ai/kgraphservice)                | Knowledge Graph Service in Python                              |
| kgraphnexus                  | [Link](https://www.kgraphnexus.com/)                             | Knowledge Graph Visualization Desktop App                      |
| kgraphservice                | [Link](https://github.com/vital-ai/kgraphservice)                | Knowledge Graph Service (Python Library)                       |
| kgraphmemory                 | [Link](https://github.com/vital-ai/kgraphmemory)                 | Knowledge Graph Memory (Python Library)                        |
| kgraphgen                    | [Link](https://github.com/vital-ai/kgraphgen)                    | Knowledge Graph Generation (Python Library)                    |
| vital-extract-service        | [Link](https://github.com/vital-ai/vital-extract-service-python) | Knowledge Graph Extraction (Python Service)                    |
| kgraphagent                  | [Link](https://github.com/vital-ai/kgraphagent)                  | Agent interface to Knowledge Graphs (Python Library)           |
| vital-agent-kg-utils         | [Link](https://github.com/vital-ai/vital-agent-kg-utils)         | Agent Utils for Vital AI Agent Ecosystem (Python Library)      |
| vital-agent-resource-rest    | [Link](https://github.com/vital-ai/vital-agent-resource-rest)    | Vital Agent Resource REST                                      |
| vital-client-python          | [Link](https://github.com/vital-ai/vital-client-python)          | Python Client to access Agent Ecosystem                        |
| vital-client-js              | [Link](https://github.com/vital-ai/vital-client-js)              | JavaScript Client to access Agent Ecosystem                    |
| vital-client-groovy          | [Link](https://github.com/vital-ai/vital-client-groovy)          | Groovy (JVM) Client to access Agent Ecosystem                  |
| vital-client-java            | [Link](https://github.com/vital-ai/vital-client-java)            | Java (JVM) Client to access Agent Ecosystem                    |
| vital-vitalsigns             | [Link](https://github.com/vital-ai/vital-vitalsigns)             | Knowledge Model Runtime and Tools (JVM)                        |
| vital-saas-admin             | [Link](https://github.com/vital-ai/vital-saas-admin)             | Agent Ecosystem Admin WebApp                                   |
| vital-saas-service-endpoint  | [Link](https://github.com/vital-ai/vital-saas-service-endpoint)  | Agent Service Endpoint Implementation based on NGINX           |
| vital-saas-email-endpoint    | [Link](https://github.com/vital-ai/vital-saas-email-endpoint)    | Agent Ecosystem Endpoint for Email                             |
| vital-saas-payment-endpoint  | [Link](https://github.com/vital-ai/vital-saas-payment-endpoint)  | Agent Ecosystem Endpoint for Payment Processing                |
| vital-saas-slack-endpoint    | [Link](https://github.com/vital-ai/vital-saas-slack-endpoint)    | Agent Ecosystem Endpoint for Slack Integeration                |
| vital-saas-service           | [Link](https://github.com/vital-ai/vital-saas-service)           | Agent Ecosystem Service Infrastructure                         |
| vital-vitalservice           | [Link](https://github.com/vital-ai/vital-vitalservice)           | VitalService Interfaces for Databases                          |
| vital-vitalservice-sql       | [Link](https://github.com/vital-ai/vital-vitalservice-sql)       | VitalService Implementation via SQL                            |
| vital-vitalservice-graph     | [Link](https://github.com/vital-ai/vital-vitalservice-graph)     | VitalService Implementation via Graph Database (SPARQL)        |
| vital-vitalservice-vector    | [Link](https://github.com/vital-ai/vital-vitalservice-vector)    | VitalService Implementation for Vector Databases               |
| vital-vitalservice-impl      | [Link](https://github.com/vital-ai/vital-vitalservice-impl)      | VitalService Implementation Internals                          |
| vital-prime                  | [Link](https://github.com/vital-ai/vital-prime)                  | Agent Ecosysem base infrastructure server using Vert.x         |
| vital-actor                  | [Link](https://github.com/vital-ai/vital-actor)                  | Agent Ecosystem Worker/Workflow Implementation                 |
| vital-processor              | [Link](https://github.com/vital-ai/vital-processor)              | Agent Ecosystem Processor Implementation                       |
| vital-processor-agent        | [Link](https://github.com/vital-ai/vital-processor-agent)        | Agent Ecosystem Processor Agent Implementation                 |
| vital-agent-container        | [Link](https://github.com/vital-ai/vital-agent-container)        | Agent Container Specification                                  |
| vital-agent-container-python | [Link](https://github.com/vital-ai/vital-agent-container-python) | Agent Container SDK for Python                                 |
| vital-agent-opengpt          | [Link](https://github.com/vital-ai/vital-agent-opengpt)          | Agent Implementation based on OpenGPT                          |
| vital-agent-template-python  | [Link](https://github.com/vital-ai/vital-agent-template-python)  | Agent Template for Python Implementation                       |
| vital-agent-sample-python    | [Link](https://github.com/vital-ai/vital-agent-sample-python)    | Agent Sample Implementation in Python                          |

