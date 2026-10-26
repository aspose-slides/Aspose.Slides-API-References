---
title: OpenAICompatibleWebClient constructor
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides.ai/openaicompatiblewebclient/__init__/
weight: 10
---
## __init__(self, model, api_key, base_url) {#str-str-str}
Maakt een instantie van de OpenAI-compatibele webclient.


```python
def __init__(self, model, api_key, base_url):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| model | **str** | Modelnaam ondersteund door de LLM-leverancier. |
| api_key | **str** | API-sleutel (token). |
| base_url | **str** | Basis-URL van de OpenAI-compatibele LLM. |

### Uitzonderingen

| Uitzondering | Beschrijving |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | API-sleutelwaarde mag niet None of leeg zijn. |
| **RuntimeError(Proxy error(ArgumentException))** | Waarde van tekstmodel mag niet None of leeg zijn. |
| **RuntimeError(Proxy error(ArgumentException))** | Base-URL-waarde mag niet None of leeg zijn. |



### Zie ook
* klasse [`OpenAICompatibleWebClient`](/slides/python-net/nl/aspose.slides.ai/openaicompatiblewebclient)
* module [`aspose.slides.ai`](/slides/python-net/nl/aspose.slides.ai)
* bibliotheek [`Aspose.Slides`](/slides/python-net)