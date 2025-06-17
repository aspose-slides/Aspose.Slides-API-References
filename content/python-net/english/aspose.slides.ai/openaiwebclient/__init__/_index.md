---
title: OpenAIWebClient constructor
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.ai/openaiwebclient/__init__/
weight: 10
---


## __init__ {#str-str-str}
Creates instance of OpenAI Web client.


```python
def __init__(self, model, api_key, organization_id):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| model | **str** | OpenAI language model. Possible values:<br/><br/>              - gpt-4o<br/><br/>              - gpt-4o-mini<br/><br/>              - o1<br/><br/>              - o1-mini<br/><br/>              - o3<br/><br/>              - o3-mini |
| api_key | **str** | OpenAI API key |
| organization_id | **str** | Organization ID (optional) |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | API key value can't be None or empty |
| **RuntimeError(Proxy error(ArgumentException))** | Text model value can't be None or empty |



### See Also
* class [`OpenAIWebClient`](/slides/python-net/aspose.slides.ai/openaiwebclient)
* module [`aspose.slides.ai`](/slides/python-net/aspose.slides.ai)
* library [`Aspose.Slides`](/slides/python-net)

