# Plano de Estudos SRE — Trilhas de Aprendizado por Nível

Guia prático de estudos para profissionais de **Site Reliability Engineering (SRE)**, organizado por nível de senioridade e com foco em **conteúdos gratuitos, online e preferencialmente em português**.

Este material foi estruturado para ajudar na evolução técnica em confiabilidade, automação, observabilidade, resposta a incidentes e engenharia de plataforma, cobrindo desde os fundamentos até temas mais avançados de arquitetura e estratégia.

---

## Visão geral

O objetivo deste repositório é reunir uma trilha clara de aprendizado para quem quer evoluir na carreira de SRE, passando pelos níveis:

- **SRE Júnior**
- **SRE Pleno**
- **SRE Sênior**
- **SRE Especialista / Arquiteto**

As trilhas foram organizadas em quatro grandes pilares:

- **Fundamentos de SRE**
- **Tecnologias Essenciais**
- **Observabilidade**
- **Pipelines e CI/CD**

Além dos temas clássicos de SRE, o plano também aborda ferramentas amplamente usadas no mercado, como:

- Linux
- Docker
- Kubernetes
- AWS
- Terraform
- Ansible
- Prometheus
- OpenTelemetry
- New Relic
- Jenkins

Também é totalmente válido complementar a jornada com tecnologias como **ArgoCD**, **GitHub Actions**, **Karpenter**, entre outras.

---

## Para quem é este material

Este repositório foi pensado para:

- profissionais iniciando em SRE, DevOps, Cloud ou Infraestrutura
- analistas e engenheiros que querem estruturar melhor sua evolução técnica
- times que desejam usar uma trilha base para desenvolvimento interno
- pessoas que preferem estudar com uma direção clara, sem depender de conteúdo solto e aleatório da internet

Sem mapa, o estudo vira caça ao tesouro com bússola quebrada. A ideia aqui é justamente reduzir esse caos.

---

## Como usar esta trilha

A recomendação é simples:

1. siga a trilha correspondente ao seu nível atual
2. consulte também o nível seguinte para orientar sua evolução
3. trate os blocos técnicos como **cumulativos**

Ou seja:

- quem está no nível **Pleno** deve dominar a base do **Júnior**
- quem está no nível **Sênior** deve carregar os fundamentos dos níveis anteriores
- quem atua como **Especialista/Arquiteto** precisa consolidar técnica, visão sistêmica e influência organizacional

---

## Estrutura da trilha

Cada nível foi organizado com foco em quatro áreas:

### 1. Fundamentos de SRE
Conceitos como:

- confiabilidade
- disponibilidade
- observabilidade
- SLA, SLI e SLO
- error budget
- toil
- incident management
- postmortem
- capacity planning
- cultura blameless

### 2. Tecnologias Essenciais
Foco em base operacional e automação:

- Linux
- Docker
- Kubernetes
- AWS
- Terraform
- Ansible

### 3. Observabilidade
Ferramentas e práticas para entender sistemas distribuídos:

- Prometheus
- Grafana
- Alertmanager
- OpenTelemetry
- tracing distribuído
- logs e telemetria
- APM com New Relic

### 4. Pipelines e CI/CD
Automação de build, teste e entrega:

- Jenkins
- Jenkinsfile
- pipelines como código
- GitHub Actions
- GitLab CI
- ArgoCD
- práticas modernas de entrega contínua

---

## Resumo por nível

## SRE Júnior — Fundamentos e Primeiros Passos

Neste nível, o foco está em construir base sólida.

### O que se espera

- entender os conceitos fundamentais de SRE
- aprender os princípios de confiabilidade e observabilidade
- trabalhar com escopo bem definido e apoio de profissionais mais experientes
- ganhar familiaridade com Linux, containers, cloud e automação
- começar a entender métricas, alertas, logs e tracing
- aprender a operar pipelines simples de CI/CD

### Foco principal

- fundamentos de SRE
- Linux básico
- Docker
- Kubernetes básico
- AWS introdutório
- Terraform básico
- Ansible básico
- Prometheus e Grafana
- OpenTelemetry introdutório
- New Relic introdutório
- Jenkins básico

### Resultado esperado

Ao final dessa etapa, a pessoa deve conseguir atuar com boa autonomia em tarefas operacionais mais bem definidas, entender o vocabulário central de SRE e começar a automatizar rotinas simples.

---

## SRE Pleno — Consolidação e Profundidade

Aqui o profissional deixa de apenas executar e começa a **projetar melhorias reais** para confiabilidade e eficiência.

### O que se espera

- domínio prático de SLI, SLO e error budget
- participação mais ativa em incidentes e postmortems
- capacidade de desenhar soluções com escopo bem definido
- aprofundamento em operação de sistemas distribuídos
- atuação mais consistente com infraestrutura como código e observabilidade
- capacidade de automatizar processos de ponta a ponta
- início de mentoria para perfis mais juniores

### Foco principal

- workbook de SRE e práticas aplicadas
- Linux avançado e troubleshooting
- Docker avançado
- Kubernetes com visão operacional
- AWS com foco em arquitetura confiável
- Terraform modular e colaboração em equipe
- Ansible intermediário
- Prometheus em escala
- OpenTelemetry com instrumentação prática
- New Relic com dashboards e alertas mais avançados
- Jenkins com pipelines como código e uso de agentes
- noções de GitHub Actions, GitLab CI e ArgoCD

### Resultado esperado

Ao final dessa etapa, o profissional deve conseguir implementar melhorias estruturais, reduzir toil, desenhar automações mais maduras e colaborar com mais peso em decisões técnicas.

---

## SRE Sênior — Referência Técnica e Liderança

Neste nível, a atuação passa a ser mais ampla, estratégica e transversal.

### O que se espera

- liderança técnica em problemas complexos e ambíguos
- definição de padrões de confiabilidade
- atuação forte em incidentes críticos
- mentoria de pessoas e influência sobre múltiplos times
- visão aprofundada de arquitetura, performance, resiliência e custos
- capacidade de priorizar iniciativas com impacto organizacional

### Foco principal

- gestão avançada de incidentes
- redução estruturada de toil
- capacity planning
- chaos engineering
- Linux profundo, performance e eBPF
- Kubernetes como plataforma
- segurança e arquitetura em ambientes distribuídos
- AWS em nível arquitetural avançado
- Terraform em larga escala
- Ansible em ambientes complexos
- observabilidade holística
- Prometheus com Thanos/Cortex
- OpenTelemetry com padrões organizacionais
- New Relic com visão enterprise
- Jenkins em escala, DevSecOps, GitOps e pipelines corporativos

### Resultado esperado

Ao final dessa etapa, o profissional deve atuar como referência técnica clara, liderando iniciativas críticas de confiabilidade, observabilidade e automação com impacto direto no negócio.

---

## SRE Especialista / Arquiteto — Estratégia, Escala e Influência

Esse é o nível de quem enxerga o sistema, os times e a empresa como um organismo inteiro. Uma criatura caótica, distribuída e cheia de surpresas, como toda arquitetura real.

### O que se espera

- definição da estratégia técnica de confiabilidade da organização
- influência transversal sem depender de autoridade formal
- criação de padrões globais de engenharia
- alinhamento entre confiabilidade, arquitetura e objetivos de negócio
- antecipação de riscos futuros de escala
- liderança na adoção de tecnologias e práticas emergentes
- formação de novos líderes técnicos

### Foco principal

- estratégia organizacional de SRE
- governança de SLOs e padrões globais
- resiliência de negócio e disaster recovery
- AI Ops e automação inteligente
- chaos engineering avançado
- observabilidade como capacidade organizacional
- decisões de plataforma e arquitetura enterprise
- ROI de observabilidade
- CI/CD em escala organizacional
- GitOps, DevSecOps e modernização da esteira
- mentoria, coaching técnico e multiplicação de conhecimento

### Resultado esperado

Ao final dessa etapa, o profissional deve ser capaz de orientar áreas inteiras, definir direção técnica de longo prazo e transformar confiabilidade em vantagem competitiva.

---

## Conteúdos e temas abordados

A trilha reúne e referencia conteúdos como:

- livros e materiais inspirados nas práticas de SRE do Google
- cursos e guias de Linux
- conteúdos de Docker e Kubernetes
- trilhas da AWS
- materiais de Terraform e Ansible
- cursos e guias de Prometheus, Grafana e observabilidade
- conteúdos introdutórios e avançados de OpenTelemetry
- documentação e prática com New Relic
- cursos e tutoriais de Jenkins
- conteúdos complementares de GitHub Actions, GitLab CI, ArgoCD e GitOps

---

## Sugestão de progressão

Uma forma simples de estudar:

- **Júnior:** construir base
- **Pleno:** consolidar prática e profundidade
- **Sênior:** liderar decisões técnicas e confiabilidade em escala
- **Especialista/Arquiteto:** definir estratégia, padrões e direção de engenharia

---

## Arquivo original em PDF

O material completo em PDF pode ser acessado aqui:

[Baixar plano em PDF](./docs/plano-estudos-sre.pdf)

---

## Trilhas em Markdown por nível

Além do PDF, o conteúdo também foi segmentado em arquivos por nível:

- [SRE Júnior](./docs/junior.md)
- [SRE Pleno](./docs/pleno.md)
- [SRE Sênior](./docs/senior.md)
- [SRE Especialista / Arquiteto](./docs/especialista.md)

---

## Como este repositório pode evoluir

Algumas melhorias futuras para este material:

- separar a trilha por arquivos individuais por nível
- adicionar links diretos para cada conteúdo recomendado
- incluir checklists de progresso
- incluir roadmap visual
- adicionar trilhas complementares por especialidade  
  - observabilidade
  - plataforma
  - cloud
  - automação
  - incident response
- incluir labs práticos e projetos de portfólio

---

## Contribuição

Sugestões de melhoria são bem-vindas.

A ideia deste material é servir como base prática para quem quer estudar SRE com mais direção, menos ruído e menos dependência de “aprender no susto em produção”, que é um professor bem eficiente, mas meio sociopata.

---

## Autor

**Tharlesson**

Se este material te ajudou, deixe uma estrela no repositório e compartilhe com outras pessoas da comunidade.


