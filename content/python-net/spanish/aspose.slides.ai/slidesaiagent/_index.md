---
title: SlidesAIAgent class
second_title: Referencia de API de Aspose.Slides para Python a través de .NET
description: 
type: docs
url: /es/aspose.slides.ai/slidesaiagent/
---
## SlidesAIAgent clase

Proporciona funciones impulsadas por IA para procesar presentaciones.

El tipo SlidesAIAgent expone los siguientes miembros:

## Constructores

| Constructor | Descripción |
| :- | :- |
| [`__init__(self, ai_client)`](/slides/python-net/es/aspose.slides.ai/slidesaiagent/__init__/#iaiwebclient) | Inicializa una nueva instancia de [`SlidesAIAgent`](/slides/python-net/es/aspose.slides.ai/slidesaiagent) con un cliente de IA personalizado.<br/>            Use esta sobrecarga para especificar el proveedor de IA, proporcionar su propio LLM o personalizar la<br/>            conexión (por ejemplo, proporcionando su propio `HttpClient`).<br/>            Cualquier implementación de [`IAIWebClient`](/slides/python-net/es/aspose.slides.ai/iaiwebclient) puede usarse, incluyendo:<br/>            <br/>* [`AsposeAIWebClient`](/slides/python-net/es/aspose.slides.ai/asposeaiwebclient)<br/>* [`OpenAIWebClient`](/slides/python-net/es/aspose.slides.ai/openaiwebclient)<br/>* [`OpenAICompatibleWebClient`](/slides/python-net/es/aspose.slides.ai/openaicompatiblewebclient)<br/><br/><br/>            Para usar el [`AsposeAIWebClient`](/slides/python-net/es/aspose.slides.ai/asposeaiwebclient) incorporado con su configuración predeterminada,<br/>            use la sobrecarga **SlidesAIAgent.#ctor** en su lugar. |
| [`__init__(self)`](/slides/python-net/es/aspose.slides.ai/slidesaiagent/__init__/#) | Inicializa una nueva instancia de [`SlidesAIAgent`](/slides/python-net/es/aspose.slides.ai/slidesaiagent) usando el [`AsposeAIWebClient`](/slides/python-net/es/aspose.slides.ai/asposeaiwebclient) incorporado<br/>            con su configuración predeterminada. El cliente se conecta al<br/>            LLM propio de Aspose y no requiere configuración adicional.<br/>            Para usar un cliente de IA diferente, use la sobrecarga **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A** en su lugar. |

## Métodos

| Método | Descripción |
| :- | :- |
| [`generate_presentation(self, description, presentation_content_amount)`](/slides/python-net/es/aspose.slides.ai/slidesaiagent/generate_presentation/#str-presentationcontentamounttype) | Genera una instancia de presentación a partir de una descripción de texto. Proporcione un tema, ideas, citas o fragmentos de texto en el idioma requerido. |
| [`generate_presentation(self, description, presentation_content_amount, presentation_template)`](/slides/python-net/es/aspose.slides.ai/slidesaiagent/generate_presentation/#str-presentationcontentamounttype-ipresentation) | Genera una instancia de presentación a partir de una descripción de texto. Proporcione un tema, ideas, citas o fragmentos de texto en el idioma requerido. |
| [`translate(self, presentation, language)`](/slides/python-net/es/aspose.slides.ai/slidesaiagent/translate/#ipresentation-str) | Traduce una presentación al idioma especificado usando IA (versión síncrona). |

### Ver también
* clase [`AsposeAIWebClient`](/slides/python-net/es/aspose.slides.ai/asposeaiwebclient)
* clase [`IAIWebClient`](/slides/python-net/es/aspose.slides.ai/iaiwebclient)
* clase [`OpenAICompatibleWebClient`](/slides/python-net/es/aspose.slides.ai/openaicompatiblewebclient)
* clase [`OpenAIWebClient`](/slides/python-net/es/aspose.slides.ai/openaiwebclient)
* clase [`SlidesAIAgent`](/slides/python-net/es/aspose.slides.ai/slidesaiagent)
* módulo [`aspose.slides.ai`](/slides/python-net/es/aspose.slides.ai)
* biblioteca [`Aspose.Slides`](/slides/python-net)