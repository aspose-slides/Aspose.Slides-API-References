---
title: OpenAIWebClient constructor
second_title: Aspose.Slides pro Python prostřednictvím .NET API Reference
description: 
type: docs
url: /cs/aspose.slides.ai/openaiwebclient/__init__/
weight: 10
---
## __init__(self, model, api_key, organization_id) {#str-str-str}
Vytvoří instanci webového klienta OpenAI.


```python
def __init__(self, model, api_key, organization_id):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| model | **str** | Jazykový model OpenAI. Možné hodnoty:<br/><br/>              - gpt-4o<br/><br/>              - gpt-4o-mini<br/><br/>              - o1<br/><br/>              - o1-mini<br/><br/>              - o3<br/><br/>              - o3-mini |
| api_key | **str** | Klíč API OpenAI. |
| organization_id | **str** | ID organizace (volitelné). |

### Výjimky

| Výjimka | Popis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Hodnota klíče API nesmí být None nebo prázdná. |
| **RuntimeError(Proxy error(ArgumentException))** | Hodnota textového modelu nesmí být None nebo prázdná. |



### Viz také
* třída [`OpenAIWebClient`](/slides/python-net/cs/aspose.slides.ai/openaiwebclient)
* modul [`aspose.slides.ai`](/slides/python-net/cs/aspose.slides.ai)
* knihovna [`Aspose.Slides`](/slides/python-net)