---
title: OpenAICompatibleWebClient constructor
second_title: Aspose.Slides dla Pythona – referencja API .NET
description: 
type: docs
url: /pl/aspose.slides.ai/openaicompatiblewebclient/__init__/
weight: 10
---
## __init__(self, model, api_key, base_url) {#str-str-str}
Tworzy instancję klienta sieciowego zgodnego z OpenAI.

```python
def __init__(self, model, api_key, base_url):
    ...
```

| Parametr | Typ | Opis |
| :- | :- | :- |
| model | **str** | Nazwa modelu obsługiwana przez dostawcę LLM. |
| api_key | **str** | Klucz API (token). |
| base_url | **str** | Podstawowy adres URL LLM zgodnego z OpenAI. |

### Wyjątki

| Wyjątek | Opis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Wartość klucza API nie może być None ani pusta. |
| **RuntimeError(Proxy error(ArgumentException))** | Wartość modelu tekstowego nie może być None ani pusta. |
| **RuntimeError(Proxy error(ArgumentException))** | Wartość Base URL nie może być None ani pusta. |

### Zobacz także
* klasa [`OpenAICompatibleWebClient`](/slides/python-net/pl/aspose.slides.ai/openaicompatiblewebclient)
* moduł [`aspose.slides.ai`](/slides/python-net/pl/aspose.slides.ai)
* biblioteka [`Aspose.Slides`](/slides/python-net)