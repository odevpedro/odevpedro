# Pedro Schmidt

**Desenvolvedor Back-End especializado em Java, Spring Boot, sistemas distribuídos e arquitetura cloud.**

Atuo no desenvolvimento e evolução de aplicações corporativas, com foco em manutenibilidade, integração, consistência, observabilidade e tratamento de falhas.

Minha experiência está concentrada em sistemas financeiros e empresariais, envolvendo monólitos modulares, microsserviços, mensageria, bancos relacionais, integrações com sistemas legados e ambientes cloud.

---

## Projetos em destaque

### [Digital Onboarding](https://github.com/odevpedro/digital-onboarding)

Monólito modular que simula um processo completo de abertura de conta digital para pessoas físicas e jurídicas.

Principais aspectos explorados:

* Máquina de estados explícita para o fluxo de onboarding
* Outbox Pattern transacional
* Operações idempotentes
* Mensageria com RabbitMQ
* PostgreSQL e Flyway
* Armazenamento de documentos com MinIO
* Métricas com Prometheus e Grafana
* Testes de integração com Testcontainers
* Integração com bibliotecas bancárias reutilizáveis

---

### [Banking Foundation](https://github.com/odevpedro/banking-foundation)

Spring Boot Starter multi-módulo criado para centralizar preocupações transversais comuns em aplicações corporativas.

O projeto fornece:

* Propagação de Correlation ID
* Tratamento padronizado de erros
* Autenticação JWT e RBAC
* Suporte a auditoria
* Idempotência
* Abstrações para Outbox Pattern
* Métricas e observabilidade
* Auto-configuração condicional do Spring Boot
* Suporte de testes para aplicações consumidoras

---

### [Núcleo de Validação](https://github.com/odevpedro/nucleo-validacao)

Gateway genérico para execução de grupos de validações bancárias implementadas por meio de procedures Oracle PL/SQL.

O projeto aborda:

* Integração entre Java e PL/SQL
* Execução dinâmica de procedures com `CallableStatement`
* Configuração declarativa de validações em YAML
* Auditoria independente com `REQUIRES_NEW`
* Separação entre falha técnica e reprovação de negócio
* Permissões e grants no Oracle
* Testes com Oracle Database Free e Testcontainers

---

### CertiFlow — em desenvolvimento

Plataforma SaaS multi-tenant para gestão de fornecedores, documentos obrigatórios, conformidade e vencimentos.

A arquitetura está sendo desenvolvida localmente com LocalStack e inclui:

* AWS Lambda
* API Gateway
* DynamoDB
* S3
* EventBridge
* SQS e DLQs
* Step Functions
* Cognito
* Terraform
* Workflows orientados a eventos
* Isolamento multi-tenant
* Consumidores idempotentes
* Auditoria e observabilidade

---

## Áreas de interesse

Tenho interesse especial em:

* Monólitos modulares e sistemas distribuídos
* Modelagem de domínio e workflows explícitos
* Arquitetura orientada a eventos
* Consistência transacional
* Idempotência e deduplicação de mensagens
* Retries, timeouts e recuperação de falhas
* Observabilidade e diagnóstico em produção
* Performance de banco de dados
* Modernização de sistemas legados
* Bibliotecas internas e engenharia de plataforma
* AWS e infraestrutura como código

---

## Como penso sobre arquitetura

Procuro evitar decisões baseadas apenas em tendências ou popularidade de tecnologias.

Meus projetos são guiados por perguntas como:

* Qual problema este padrão realmente resolve?
* O que acontece quando uma dependência fica indisponível?
* Como mensagens duplicadas são tratadas?
* Uma operação pode ser repetida com segurança?
* Como o sistema será observado e diagnosticado?
* Qual é o custo operacional desta decisão?
* Quando um monólito modular é mais adequado que microsserviços?
* Como evoluir o sistema sem quebrar seus consumidores?

---

## Stack principal

### Back-End

`Java` · `Spring Boot` · `Quarkus` · `JPA` · `Hibernate` · `PL/SQL`

### Mensageria e sistemas distribuídos

`Kafka` · `RabbitMQ` · `SQS` · `EventBridge`

### Bancos de dados

`PostgreSQL` · `Oracle` · `MySQL` · `MongoDB` · `Redis` · `DynamoDB`

### Cloud e infraestrutura

`AWS` · `Azure` · `Docker` · `Terraform` · `LocalStack` · `GitHub Actions`

### Testes e observabilidade

`JUnit` · `Mockito` · `Testcontainers` · `RestAssured` · `Prometheus` · `Grafana` · `OpenTelemetry`

---

## Escrita técnica

Escrevo sobre decisões, erros, investigações e trade-offs encontrados durante a construção de sistemas back-end.

Principais temas:

* Arquitetura sem hype
* Java e Spring Boot
* Sistemas distribuídos
* Bancos de dados e transações
* AWS e LocalStack
* Observabilidade
* Integração com sistemas legados
* Aprendizados obtidos em projetos pessoais

---

## Contato

* GitHub: [@odevpedro](https://github.com/odevpedro)
* E-mail: [pedrosschmidt2@gmail.com](mailto:pedrosschmidt2@gmail.com)
