# MotoAI Assist — diagnóstico de motocicletas com IA

Protótipo de uma aplicação web que organiza sintomas e dados da motocicleta para apoiar uma avaliação inicial com IA generativa.

## Problema

Quem enfrenta uma falha mecânica costuma encontrar informações dispersas e difíceis de relacionar ao modelo da própria moto. A proposta do MotoAI Assist é transformar uma descrição livre em hipóteses e próximos passos claros.

## Experiência do produto

- **Diagnóstico guiado:** informa marca, modelo e sintomas; a IA devolve causas prováveis, nível de probabilidade, etapas de verificação e ferramentas sugeridas.
- **Assistente conversacional:** permite fazer perguntas complementares sobre motocicletas em uma interface de chat.
- **Busca de apoio local:** o projeto também contém um fluxo para localizar oficinas próximas usando coordenadas fornecidas pelo usuário.

## Arquitetura e tecnologias

- Next.js 15, React e TypeScript
- Genkit com Gemini 2.0 Flash
- Esquemas Zod para estruturar entradas e respostas
- Integração com ferramenta de busca para apoiar o assistente
- Interface com componentes React e Radix UI

## O que este projeto demonstra

- Integração de modelos generativos a fluxos de produto
- Respostas estruturadas para apoiar uma experiência conversacional
- Organização de uma interface de diagnóstico em etapas
- Uso de ferramentas externas e contexto de localização

## Estado e limites

Este repositório público é um **estudo de caso**. O código-fonte do protótipo continua privado e está em revisão antes de qualquer publicação; não há demonstração online vinculada neste momento.

As respostas da IA são orientativas e podem estar incorretas. Elas não substituem inspeção, diagnóstico ou reparo feito por profissional qualificado. O uso de dados de localização e de qualquer informação pessoal exige controles de privacidade antes de uma demonstração pública.

## Próximos passos

- Validar a qualidade das orientações com profissionais de mecânica.
- Revisar autenticação, limites de uso e proteção de dados nos fluxos de IA.
- Preparar uma demonstração pública segura e documentar os resultados de validação.

---

Desenvolvido como experimento de aplicações com IA generativa para manutenção de motocicletas.
