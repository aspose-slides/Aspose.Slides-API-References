---
title: OpenAICompatibleWebClient constructor
second_title: Aspose.Slides Pythonhoz .NET-en keresztül API-referencia
description: 
type: docs
url: /hu/aspose.slides.ai/openaicompatiblewebclient/__init__/
weight: 10
---
## __init__(self, model, api_key, base_url) {#str-str-str}
Létrehoz egy példányt az OpenAI-kompatibilis webkliensből.

```python
def __init__(self, model, api_key, base_url):
    ...
```

| Paraméter | Típus | Leírás |
| :- | :- | :- |
| model | **str** | Az LLM szolgáltató által támogatott modell neve. |
| api_key | **str** | API kulcs (token). |
| base_url | **str** | Az OpenAI-kompatibilis LLM alap URL-je. |

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Az API kulcs értéke nem lehet None vagy üres. |
| **RuntimeError(Proxy error(ArgumentException))** | A szövegmodell értéke nem lehet None vagy üres. |
| **RuntimeError(Proxy error(ArgumentException))** | Az alap URL értéke nem lehet None vagy üres. |

### Lásd még
* osztály [`OpenAICompatibleWebClient`](/slides/python-net/hu/aspose.slides.ai/openaicompatiblewebclient)
* modul [`aspose.slides.ai`](/slides/python-net/hu/aspose.slides.ai)
* könyvtár [`Aspose.Slides`](/slides/python-net)