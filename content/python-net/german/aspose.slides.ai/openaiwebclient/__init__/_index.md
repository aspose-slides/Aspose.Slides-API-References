---
title: OpenAIWebClient constructor
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.ai/openaiwebclient/__init__/
weight: 10
---
## __init__(self, model, api_key, organization_id) {#str-str-str}
Erstellt eine Instanz des OpenAI-Webclients.


```python
def __init__(self, model, api_key, organization_id):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| model | **str** | OpenAI-Sprachmodell. Mögliche Werte:<br/><br/>              - gpt-4o<br/><br/>              - gpt-4o-mini<br/><br/>              - o1<br/><br/>              - o1-mini<br/><br/>              - o3<br/><br/>              - o3-mini |
| api_key | **str** | OpenAI API-Schlüssel. |
| organization_id | **str** | Organisations-ID (optional). |

### Ausnahmen

| Ausnahme | Beschreibung |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | API-Schlüsselwert darf nicht None oder leer sein. |
| **RuntimeError(Proxy error(ArgumentException))** | Textmodellwert darf nicht None oder leer sein. |



### Siehe auch
* Klasse [`OpenAIWebClient`](/slides/python-net/de/aspose.slides.ai/openaiwebclient)
* Modul [`aspose.slides.ai`](/slides/python-net/de/aspose.slides.ai)
* Bibliothek [`Aspose.Slides`](/slides/python-net)