---
title: OpenAIWebClient constructor
second_title: Aspose.Slides para Python vía .NET Referencia de API
description: 
type: docs
url: /es/aspose.slides.ai/openaiwebclient/__init__/
weight: 10
---
## __init__(self, model, api_key, organization_id) {#str-str-str}
Crea una instancia del cliente web de OpenAI.


```python
def __init__(self, model, api_key, organization_id):
    ...
```


| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| model | **str** | Modelo de lenguaje de OpenAI. Valores posibles:<br/><br/>              - gpt-4o<br/><br/>              - gpt-4o-mini<br/><br/>              - o1<br/><br/>              - o1-mini<br/><br/>              - o3<br/><br/>              - o3-mini |
| api_key | **str** | Clave API de OpenAI. |
| organization_id | **str** | ID de la organización (opcional). |

### Excepciones

| Excepción | Descripción |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | El valor de la clave API no puede ser None o vacío. |
| **RuntimeError(Proxy error(ArgumentException))** | El valor del modelo de texto no puede ser None o vacío. |



### Ver también
* clase [`OpenAIWebClient`](/slides/python-net/es/aspose.slides.ai/openaiwebclient)
* módulo [`aspose.slides.ai`](/slides/python-net/es/aspose.slides.ai)
* biblioteca [`Aspose.Slides`](/slides/python-net)