---
title: translate method
second_title: Referencia de API de Aspose.Slides para Python mediante .NET
description: 
type: docs
url: /es/aspose.slides.ai/slidesaiagent/translate/
weight: 30
---
## translate(self, presentation, language) {#ipresentation-str}
Traduce una presentación al idioma especificado mediante IA (versión sincrónica).


```python
def translate(self, presentation, language):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| presentation | [`IPresentation`](/slides/python-net/es/aspose.slides/ipresentation) | Presentación de destino |
| language | **str** | Idioma de destino |

### Observaciones

El ejemplo a continuación utiliza el [`AsposeAIWebClient`](/slides/python-net/es/aspose.slides.ai/asposeaiwebclient) predeterminado, que es creado por el constructor sin parámetros **SlidesAIAgent.#ctor** y se conecta al LLM propio de Aspose.
Para usar un proveedor de IA diferente, suministre su propio LLM, o personalice la conexión
(por ejemplo, proporcionando su propio `HttpClient`), pase una implementación [`IAIWebClient`](/slides/python-net/es/aspose.slides.ai/iaiwebclient)
al constructor **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A**. Las implementaciones disponibles son:
             
* [`AsposeAIWebClient`](/slides/python-net/es/aspose.slides.ai/asposeaiwebclient)
* [`OpenAIWebClient`](/slides/python-net/es/aspose.slides.ai/openaiwebclient)
* [`OpenAICompatibleWebClient`](/slides/python-net/es/aspose.slides.ai/openaicompatiblewebclient)

### Excepciones

| Excepción | Descripción |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | No se proporciona la instancia de presentación |
| **RuntimeError(Proxy error(ArgumentException))** | El valor de idioma no puede ser None o estar vacío |



### Véase también
* clase [`AsposeAIWebClient`](/slides/python-net/es/aspose.slides.ai/asposeaiwebclient)
* clase [`IAIWebClient`](/slides/python-net/es/aspose.slides.ai/iaiwebclient)
* clase [`IPresentation`](/slides/python-net/es/aspose.slides/ipresentation)
* clase [`OpenAICompatibleWebClient`](/slides/python-net/es/aspose.slides.ai/openaicompatiblewebclient)
* clase [`OpenAIWebClient`](/slides/python-net/es/aspose.slides.ai/openaiwebclient)
* clase [`SlidesAIAgent`](/slides/python-net/es/aspose.slides.ai/slidesaiagent)
* módulo [`aspose.slides.ai`](/slides/python-net/es/aspose.slides.ai)
* biblioteca [`Aspose.Slides`](/slides/python-net)