---
title: SlidesAIAgent constructor
second_title: Referencia de API de Aspose.Slides para Python vía .NET
description: 
type: docs
url: /es/aspose.slides.ai/slidesaiagent/__init__/
weight: 10
---
## __init__(self) {#}
Inicializa una nueva instancia de [`SlidesAIAgent`](/slides/python-net/es/aspose.slides.ai/slidesaiagent) usando el [`AsposeAIWebClient`](/slides/python-net/es/aspose.slides.ai/asposeaiwebclient) incorporado con su configuración predeterminada. El cliente se conecta al LLM propio de Aspose y no requiere configuración adicional. Para usar un cliente de IA diferente, use la sobrecarga **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A** en su lugar.

```python
def __init__(self):
    ...
```

## __init__(self, ai_client) {#iaiwebclient}
Inicializa una nueva instancia de [`SlidesAIAgent`](/slides/python-net/es/aspose.slides.ai/slidesaiagent) con un cliente de IA personalizado. Use esta sobrecarga para especificar el proveedor de IA, suministrar su propio LLM o personalizar la conexión (por ejemplo, proporcionando su propio `HttpClient`). Se puede utilizar cualquier implementación de [`IAIWebClient`](/slides/python-net/es/aspose.slides.ai/iaiwebclient), incluyendo:

* [`AsposeAIWebClient`](/slides/python-net/es/aspose.slides.ai/asposeaiwebclient)
* [`OpenAIWebClient`](/slides/python-net/es/aspose.slides.ai/openaiwebclient)
* [`OpenAICompatibleWebClient`](/slides/python-net/es/aspose.slides.ai/openaicompatiblewebclient)

Para usar el [`AsposeAIWebClient`](/slides/python-net/es/aspose.slides.ai/asposeaiwebclient) incorporado con su configuración predeterminada, use la sobrecarga **SlidesAIAgent.#ctor** en su lugar.

```python
def __init__(self, ai_client):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| ai_client | [`IAIWebClient`](/slides/python-net/es/aspose.slides.ai/iaiwebclient) | Instancia del cliente de IA. Se puede usar cualquier implementación de [`IAIWebClient`](/slides/python-net/es/aspose.slides.ai/iaiwebclient). |

### Excepciones

| Excepción | Descripción |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | No se proporciona la instancia del cliente de IA. |

### Ver también
* clase [`AsposeAIWebClient`](/slides/python-net/es/aspose.slides.ai/asposeaiwebclient)
* clase [`IAIWebClient`](/slides/python-net/es/aspose.slides.ai/iaiwebclient)
* clase [`OpenAICompatibleWebClient`](/slides/python-net/es/aspose.slides.ai/openaicompatiblewebclient)
* clase [`OpenAIWebClient`](/slides/python-net/es/aspose.slides.ai/openaiwebclient)
* clase [`SlidesAIAgent`](/slides/python-net/es/aspose.slides.ai/slidesaiagent)
* módulo [`aspose.slides.ai`](/slides/python-net/es/aspose.slides.ai)
* biblioteca [`Aspose.Slides`](/slides/python-net)