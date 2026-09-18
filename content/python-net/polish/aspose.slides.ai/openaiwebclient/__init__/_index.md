---
title: OpenAIWebClient constructor
second_title: Aspose.Slides dla Pythona przez .NET – dokumentacja API
description: 
type: docs
url: /pl/aspose.slides.ai/openaiwebclient/__init__/
weight: 10
---
## __init__(self, model, api_key, organization_id) {#str-str-str}
Tworzy instancję klienta sieciowego OpenAI.


```python
def __init__(self, model, api_key, organization_id):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| model | **str** | OpenAI language model. Możliwe wartości:<br/><br/>              - gpt-4o<br/><br/>              - gpt-4o-mini<br/><br/>              - o1<br/><br/>              - o1-mini<br/><br/>              - o3<br/><br/>              - o3-mini |
| api_key | **str** | OpenAI API key. |
| organization_id | **str** | ID organizacji (opcjonalne). |

### Wyjątki

| Wyjątek | Opis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Wartość klucza API nie może być None ani pustą. |
| **RuntimeError(Proxy error(ArgumentException))** | Wartość modelu tekstowego nie może być None ani pustą. |



### Zobacz także
* klasa [`OpenAIWebClient`](/slides/python-net/pl/aspose.slides.ai/openaiwebclient)
* moduł [`aspose.slides.ai`](/slides/python-net/pl/aspose.slides.ai)
* biblioteka [`Aspose.Slides`](/slides/python-net)