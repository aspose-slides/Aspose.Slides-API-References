---
title: aspose.slides.ai
second_title: Aspose.Slides para Python a través de la API .NET
description: 
type: docs
url: /es/aspose.slides.ai/
---
Contiene clases que proporcionan funciones basadas en IA para analizar y procesar presentaciones de PowerPoint.
## Clases

| Clase | Descripción |
| :- | :- |
| [`AsposeAIWebClient`](/slides/python-net/es/aspose.slides.ai/asposeaiwebclient/) | Una implementación integrada de [`IAIWebClient`](/slides/python-net/es/aspose.slides.ai/iaiwebclient) que se conecta al LLM propio de Aspose.<br/>            Este es el cliente predeterminado usado por el constructor sin parámetros **SlidesAIAgent.#ctor**. |
| [`IAIConversation`](/slides/python-net/es/aspose.slides.ai/iaiconversation/) | Representa una instancia de conversación. A diferencia de las llamadas de IA regulares, las conversaciones conservan todo el contexto. |
| [`IAIWebClient`](/slides/python-net/es/aspose.slides.ai/iaiwebclient/) | Interfaz de cliente web de IA. Esta interfaz permite sustituir diferentes modelos de lenguaje de IA.<br/>            Se supone que las clases que implementan esta interfaz se usan junto con `SlidesAIAgent`. |
| [`OpenAICompatibleWebClient`](/slides/python-net/es/aspose.slides.ai/openaicompatiblewebclient/) | Una implementación integrada de [`IAIWebClient`](/slides/python-net/es/aspose.slides.ai/iaiwebclient) que se conecta a un proveedor de LLM compatible con OpenAI<br/>            en una URL base especificada. |
| [`OpenAIWebClient`](/slides/python-net/es/aspose.slides.ai/openaiwebclient/) | Una implementación integrada de [`IAIWebClient`](/slides/python-net/es/aspose.slides.ai/iaiwebclient) que se conecta a la API de OpenAI. |
| [`SlidesAIAgent`](/slides/python-net/es/aspose.slides.ai/slidesaiagent/) | Proporciona funciones impulsadas por IA para procesar presentaciones. |
| [`SlidesAIAgentException`](/slides/python-net/es/aspose.slides.ai/slidesaiagentexception/) | Representa excepciones relacionadas con Slides AI Agent. |

## Enumeraciones

| Enumeración | Descripción |
| :- | :- |
| [`PresentationContentAmountType`](/slides/python-net/es/aspose.slides.ai/presentationcontentamounttype/) | Especifica la cantidad de contenido incluido en la presentación generada, influyendo tanto en el número de diapositivas como en el nivel de detalle por diapositiva. |