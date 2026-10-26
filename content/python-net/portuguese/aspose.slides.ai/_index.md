---
title: aspose.slides.ai
second_title: Aspose.Slides para Python via .NET Referência de API
description: 
type: docs
url: /pt/aspose.slides.ai/
---
Contém classes que fornecem recursos baseados em IA para analisar e processar apresentações do PowerPoint.

## Classes

| Classe | Descrição |
| :- | :- |
| [`AsposeAIWebClient`](/slides/python-net/pt/aspose.slides.ai/asposeaiwebclient/) | Uma implementação incorporada [`IAIWebClient`](/slides/python-net/pt/aspose.slides.ai/iaiwebclient) que se conecta ao LLM próprio da Aspose.<br/>Este é o cliente padrão usado pelo construtor **SlidesAIAgent.#ctor** sem parâmetros. |
| [`IAIConversation`](/slides/python-net/pt/aspose.slides.ai/iaiconversation/) | Representa uma instância de conversa. Ao contrário das chamadas regulares de IA, as conversas mantêm todo o contexto. |
| [`IAIWebClient`](/slides/python-net/pt/aspose.slides.ai/iaiwebclient/) | Interface de cliente web de IA. Esta interface permite substituir diferentes modelos de linguagem de IA.<br/>As classes que implementam esta interface devem ser usadas junto com `SlidesAIAgent`. |
| [`OpenAICompatibleWebClient`](/slides/python-net/pt/aspose.slides.ai/openaicompatiblewebclient/) | Uma implementação incorporada [`IAIWebClient`](/slides/python-net/pt/aspose.slides.ai/iaiwebclient) que se conecta a um provedor de LLM compatível com OpenAI<br/>em uma URL base especificada. |
| [`OpenAIWebClient`](/slides/python-net/pt/aspose.slides.ai/openaiwebclient/) | Uma implementação incorporada [`IAIWebClient`](/slides/python-net/pt/aspose.slides.ai/iaiwebclient) que se conecta à API OpenAI. |
| [`SlidesAIAgent`](/slides/python-net/pt/aspose.slides.ai/slidesaiagent/) | Fornece recursos alimentados por IA para processar apresentações. |
| [`SlidesAIAgentException`](/slides/python-net/pt/aspose.slides.ai/slidesaiagentexception/) | Representa exceções relacionadas ao Slides AI Agent. |

## Enumerações

| Enumeração | Descrição |
| :- | :- |
| [`PresentationContentAmountType`](/slides/python-net/pt/aspose.slides.ai/presentationcontentamounttype/) | Especifica a quantidade de conteúdo incluído na apresentação gerada, influenciando tanto o número de slides quanto o nível de detalhe por slide. |