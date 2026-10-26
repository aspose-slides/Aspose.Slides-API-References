---
title: OpenAICompatibleWebClient constructor
second_title: Aspose.Slides pro Python přes .NET referenční příručka API
description: 
type: docs
url: /cs/aspose.slides.ai/openaicompatiblewebclient/__init__/
weight: 10
---
## __init__(self, model, api_key, base_url) {#str-str-str}
Vytvoří instanci webového klienta kompatibilního s OpenAI.


```python
def __init__(self, model, api_key, base_url):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| model | **str** | Název modelu podporovaný poskytovatelem LLM. |
| api_key | **str** | API klíč (token). |
| base_url | **str** | Základní URL OpenAI-kompatibilního LLM. |

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Hodnota API klíče nesmí být None nebo prázdná. |
| **RuntimeError(Proxy error(ArgumentException))** | Hodnota textového modelu nesmí být None nebo prázdná. |
| **RuntimeError(Proxy error(ArgumentException))** | Hodnota základního URL nesmí být None nebo prázdná. |



### Viz také
* třída [`OpenAICompatibleWebClient`](/slides/python-net/cs/aspose.slides.ai/openaicompatiblewebclient)
* modul [`aspose.slides.ai`](/slides/python-net/cs/aspose.slides.ai)
* knihovna [`Aspose.Slides`](/slides/python-net)