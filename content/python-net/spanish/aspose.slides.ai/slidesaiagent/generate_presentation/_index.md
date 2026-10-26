---
title: generate_presentation method
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides.ai/slidesaiagent/generate_presentation/
weight: 20
---
## generate_presentation(self, description, presentation_content_amount) {#str-presentationcontentamounttype}
Genera una instancia de presentación a partir de una descripción de texto. Proporcione un tema, ideas, citas o fragmentos de texto en el idioma requerido.


```python
def generate_presentation(self, description, presentation_content_amount):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| description | **str** | El tema, ideas, citas o fragmentos de texto. |
| presentation_content_amount | [`PresentationContentAmountType`](/slides/python-net/es/aspose.slides.ai/presentationcontentamounttype) | La cantidad de contenido en la presentación resultante. |

### Observaciones

El ejemplo a continuación utiliza el [`AsposeAIWebClient`](/slides/python-net/es/aspose.slides.ai/asposeaiwebclient) predeterminado, que se crea mediante el constructor sin parámetros **SlidesAIAgent.#ctor** y se conecta al LLM propio de Aspose. Para usar un proveedor de IA diferente, proporcione su propio LLM o personalice la conexión (por ejemplo, proporcionando su propio `HttpClient`), pase una implementación [`IAIWebClient`](/slides/python-net/es/aspose.slides.ai/iaiwebclient) al constructor **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A**. Las implementaciones disponibles incluyen:
             
* [`AsposeAIWebClient`](/slides/python-net/es/aspose.slides.ai/asposeaiwebclient)
* [`OpenAIWebClient`](/slides/python-net/es/aspose.slides.ai/openaiwebclient)
* [`OpenAICompatibleWebClient`](/slides/python-net/es/aspose.slides.ai/openaicompatiblewebclient)

### Excepciones

| Excepción | Descripción |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | La instrucción de chat de IA no puede ser None ni vacía. |


## generate_presentation(self, description, presentation_content_amount, presentation_template) {#str-presentationcontentamounttype-ipresentation}
Genera una instancia de presentación a partir de una descripción de texto. Proporcione un tema, ideas, citas o fragmentos de texto en el idioma requerido.


```python
def generate_presentation(self, description, presentation_content_amount, presentation_template):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| description | **str** | El tema, ideas, citas o fragmentos de texto. |
| presentation_content_amount | [`PresentationContentAmountType`](/slides/python-net/es/aspose.slides.ai/presentationcontentamounttype) | La cantidad de contenido en la presentación resultante. |
| presentation_template | [`IPresentation`](/slides/python-net/es/aspose.slides/ipresentation) | Una presentación para usar como plantilla de diseño y maquetado, reemplazando la plantilla predeterminada. |

### Observaciones

El ejemplo a continuación utiliza el [`AsposeAIWebClient`](/slides/python-net/es/aspose.slides.ai/asposeaiwebclient) predeterminado, que se crea mediante el constructor sin parámetros **SlidesAIAgent.#ctor** y se conecta al LLM propio de Aspose. Para usar un proveedor de IA diferente, proporcione su propio LLM o personalice la conexión (por ejemplo, proporcionando su propio `HttpClient`), pase una implementación [`IAIWebClient`](/slides/python-net/es/aspose.slides.ai/iaiwebclient) al constructor **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A**. Las implementaciones disponibles incluyen:
            
* [`AsposeAIWebClient`](/slides/python-net/es/aspose.slides.ai/asposeaiwebclient)
* [`OpenAIWebClient`](/slides/python-net/es/aspose.slides.ai/openaiwebclient)
* [`OpenAICompatibleWebClient`](/slides/python-net/es/aspose.slides.ai/openaicompatiblewebclient)

### Excepciones

| Excepción | Descripción |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | No se proporcionó la plantilla de presentación. |
| **RuntimeError(Proxy error(ArgumentException))** | La instrucción de chat de IA no puede ser None ni vacía. |



### Ver también
* clase [`AsposeAIWebClient`](/slides/python-net/es/aspose.slides.ai/asposeaiwebclient)
* clase [`IAIWebClient`](/slides/python-net/es/aspose.slides.ai/iaiwebclient)
* clase [`IPresentation`](/slides/python-net/es/aspose.slides/ipresentation)
* clase [`OpenAICompatibleWebClient`](/slides/python-net/es/aspose.slides.ai/openaicompatiblewebclient)
* clase [`OpenAIWebClient`](/slides/python-net/es/aspose.slides.ai/openaiwebclient)
* enumeración [`PresentationContentAmountType`](/slides/python-net/es/aspose.slides.ai/presentationcontentamounttype)
* clase [`SlidesAIAgent`](/slides/python-net/es/aspose.slides.ai/slidesaiagent)
* módulo [`aspose.slides.ai`](/slides/python-net/es/aspose.slides.ai)
* biblioteca [`Aspose.Slides`](/slides/python-net)