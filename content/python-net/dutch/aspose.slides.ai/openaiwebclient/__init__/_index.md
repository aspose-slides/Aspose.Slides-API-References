---
title: OpenAIWebClient constructor
second_title: Aspose.Slides voor Python via .NET API Referentie
description: 
type: docs
url: /nl/aspose.slides.ai/openaiwebclient/__init__/
weight: 10
---
## __init__(self, model, api_key, organization_id) {#str-str-str}
Maakt een instantie van de OpenAI webclient aan.


```python
def __init__(self, model, api_key, organization_id):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| model | **str** | OpenAI-taalmodel. Mogelijke waarden:<br/><br/>              - gpt-4o<br/><br/>              - gpt-4o-mini<br/><br/>              - o1<br/><br/>              - o1-mini<br/><br/>              - o3<br/><br/>              - o3-mini |
| api_key | **str** | OpenAI API-sleutel. |
| organization_id | **str** | Organisatie-ID (optioneel). |

### Exceptions

| Exception | Beschrijving |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | API-sleutelwaarde mag niet None of leeg zijn. |
| **RuntimeError(Proxy error(ArgumentException))** | Tekstmodelwaarde mag niet None of leeg zijn. |



### See Also
* class [`OpenAIWebClient`](/slides/python-net/nl/aspose.slides.ai/openaiwebclient)
* module [`aspose.slides.ai`](/slides/python-net/nl/aspose.slides.ai)
* library [`Aspose.Slides`](/slides/python-net)