---
title: OpenAIWebClient constructor
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.ai/openaiwebclient/__init__/
weight: 10
---
## __init__(self, model, api_key, organization_id) {#str-str-str}
Skapar en instans av OpenAI-webbklienten.


```python
def __init__(self, model, api_key, organization_id):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| model | **str** | OpenAI-språkmodell. Möjliga värden:<br/><br/>              - gpt-4o<br/><br/>              - gpt-4o-mini<br/><br/>              - o1<br/><br/>              - o1-mini<br/><br/>              - o3<br/><br/>              - o3-mini |
| api_key | **str** | OpenAI API-nyckel. |
| organization_id | **str** | Organisations-ID (valfritt). |

### Undantag

| Undantag | Beskrivning |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | API-nyckelvärdet får inte vara None eller tomt. |
| **RuntimeError(Proxy error(ArgumentException))** | Textmodellvärdet får inte vara None eller tomt. |

### Se också
* klass [`OpenAIWebClient`](/slides/python-net/sv/aspose.slides.ai/openaiwebclient)
* modul [`aspose.slides.ai`](/slides/python-net/sv/aspose.slides.ai)
* bibliotek [`Aspose.Slides`](/slides/python-net)