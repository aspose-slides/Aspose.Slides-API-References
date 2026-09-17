---
title: OpenAICompatibleWebClient constructor
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.ai/openaicompatiblewebclient/__init__/
weight: 10
---
## __init__(self, model, api_key, base_url) {#str-str-str}
Erstellt eine Instanz des OpenAI-kompatiblen Web-Clients.


```python
def __init__(self, model, api_key, base_url):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| model | **str** | Modellname, der vom LLM-Anbieter unterstützt wird. |
| api_key | **str** | API-Schlüssel (Token). |
| base_url | **str** | Basis-URL des OpenAI-kompatiblen LLM. |

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | API-Schlüsselwert darf nicht None oder leer sein. |
| **RuntimeError(Proxy error(ArgumentException))** | Textmodellwert darf nicht None oder leer sein. |
| **RuntimeError(Proxy error(ArgumentException))** | Basis-URL-Wert darf nicht None oder leer sein. |



### Siehe auch
* Klasse [`OpenAICompatibleWebClient`](/slides/python-net/de/aspose.slides.ai/openaicompatiblewebclient)
* Modul [`aspose.slides.ai`](/slides/python-net/de/aspose.slides.ai)
* Bibliothek [`Aspose.Slides`](/slides/python-net)