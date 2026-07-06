---
title: OpenAICompatibleWebClient constructor
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.ai/openaicompatiblewebclient/__init__/
weight: 10
---


## __init__ {#str-str-str}
Creates an instance of the OpenAI-compatible web client.


```python
def __init__(self, model, api_key, base_url):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| model | **str** | Model name supported by the LLM provider. |
| api_key | **str** | API key (token). |
| base_url | **str** | Base URL of the OpenAI-compatible LLM. |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | API key value can't be None or empty. |
| **RuntimeError(Proxy error(ArgumentException))** | Text model value can't be None or empty. |
| **RuntimeError(Proxy error(ArgumentException))** | Base URL value can't be None or empty. |



### See Also
* class [`OpenAICompatibleWebClient`](/slides/python-net/aspose.slides.ai/openaicompatiblewebclient)
* module [`aspose.slides.ai`](/slides/python-net/aspose.slides.ai)
* library [`Aspose.Slides`](/slides/python-net)

