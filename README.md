# Escola de Lutas Potyra

## Sistema de gestão administrativa | Projeto Azetec

**Projeto da Azetec, desenvolvido por mim, Rebeka Lemos, para a cliente Escola de Lutas Potyra.**

Este repositório apresenta o projeto como estudo de caso de portfólio. O código-fonte da aplicação permanece privado.

> **Situação: em homologação.** Os fluxos e as regras de negócio seguem em validação com a cliente. Esta apresentação não representa uma liberação para uso definitivo.

## O desafio

Organizar a rotina administrativa de uma escola de lutas, reunindo informações de alunos, famílias, planos, matrículas e acompanhamento financeiro, com regras claras e preservação do histórico.

## Meu trabalho no projeto

- Levantamento e organização dos requisitos com a cliente.
- Tradução das necessidades operacionais em regras de negócio.
- Desenvolvimento dos fluxos administrativos e ajustes de interface.
- Testes automatizados e documentação das decisões e pendências.
- Preparação da infraestrutura e acompanhamento da homologação.

## Funcionalidades implementadas no código

| Área | Recursos |
| --- | --- |
| Alunos e famílias | Cadastros e organização dos responsáveis |
| Planos | Preços por vigência e exibição de valores futuros agendados |
| Matrículas | Vencimento mensal separado da data de cobrança inicial |
| Financeiro | Cobranças e registro manual de recebimentos |
| Documentação | Estrutura para anexos e modelos documentais |
| Rastreabilidade | Histórico de alterações e preservação de registros anteriores |

## Tecnologias

**Ruby on Rails 8 · PostgreSQL · Hotwire/Turbo · Stimulus · Active Storage · Solid Queue · Git/GitHub · Railway**

A aplicação utiliza uma estrutura monolítica Rails, com PostgreSQL, armazenamento de anexos e tarefas em segundo plano. A infraestrutura de homologação está organizada em serviço web, worker e banco de dados.

## Decisões de implementação

- Separar o vencimento mensal da cobrança inicial para evitar calendários ambíguos.
- Exibir preços futuros como agendados, sem antecipar sua vigência.
- Preservar cobranças e matrículas históricas ao introduzir novas regras.
- Registrar como pendentes as decisões ainda não aprovadas pela cliente.

## Verificação de qualidade

Na última execução local registrada em **21/10/2026**:

- **183 testes aprovados**, com **1.868 verificações**.
- Nenhuma falha, erro ou teste ignorado nessa execução.
- RuboCop: **159 arquivos verificados, sem infrações**.

Esses resultados documentam a verificação local; não substituem o aceite da cliente ou a validação completa em ambiente publicado.

## Limites e próximos passos

A conclusão da homologação, os documentos finais e algumas regras comerciais dependem de definições e aprovações. Integrações de envio real não estão ativadas. Não são anunciadas como concluídas assinatura validada, conciliação bancária automática ou conformidade jurídica certificada.

## Privacidade e acesso

Este repositório contém somente a apresentação pública. Não inclui código privado, dados de alunos, informações de saúde, documentos internos, credenciais ou endereço de acesso administrativo.

As capturas de tela serão adicionadas após revisão para garantir que apresentem apenas dados fictícios e conteúdo autorizado. Não há uma demonstração pública interativa disponível neste repositório.

## Autoria e contato

- **Desenvolvimento:** Rebeka Lemos
- **Projeto:** Azetec
- **Cliente:** Escola de Lutas Potyra
- [Perfil no GitHub](https://github.com/rebekalemooss-24)

O conteúdo serve à apresentação profissional do trabalho. O repositório não concede acesso ao código-fonte nem autorização de uso da marca da cliente por terceiros.
