---
title: AsposeAIWebClient class
second_title: Aspose.Slides para Python a través de la API .NET
description: 
type: docs
url: /es/aspose.slides.ai/asposeaiwebclient/
---
## AsposeAIWebClient clase

Una implementación incorporada [`IAIWebClient`](/slides/python-net/es/aspose.slides.ai/iaiwebclient) que se conecta al propio LLM de Aspose.
            Este es el cliente predeterminado usado por el constructor sin parámetros **SlidesAIAgent.#ctor**.

El tipo AsposeAIWebClient expone los siguientes miembros:

## Constructores

| Constructor | Descripción |
| :- | :- |
| [`__init__(self)`](/slides/python-net/es/aspose.slides.ai/asposeaiwebclient/__init__/#) | Crea una instancia del cliente web Aspose AI que se conecta al punto final predeterminado de Aspose LLM.<br/>            Este es el cliente usado por el constructor sin parámetros **SlidesAIAgent.#ctor**, por lo que crear<br/>            lo explícitamente solo es necesario cuando se pasa el cliente al constructor **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A**<br/>            directamente. |
| [`__init__(self, url)`](/slides/python-net/es/aspose.slides.ai/asposeaiwebclient/__init__/#str) | Crea una instancia del cliente web Aspose AI que se conecta a una URL de punto final personalizada. Use esta<br/>            sobrecarga cuando tenga una URL proporcionada por el equipo de Aspose.Slides; de lo contrario, use la<br/>            sobrecarga **AsposeAIWebClient.#ctor** con la URL predeterminada. |

## Métodos

| Método | Descripción |
| :- | :- |
| [`create_conversation(self)`](/slides/python-net/es/aspose.slides.ai/asposeaiwebclient/create_conversation/#) | Crea una instancia de conversación. A diferencia de las llamadas de IA regulares, las conversaciones conservan todo el contexto. |

### Ver también
* clase [`IAIWebClient`](/slides/python-net/es/aspose.slides.ai/iaiwebclient)
* módulo [`aspose.slides.ai`](/slides/python-net/es/aspose.slides.ai)
* biblioteca [`Aspose.Slides`](/slides/python-net)