---
title: AsposeAIWebClient constructor
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.ai/asposeaiwebclient/__init__/
weight: 10
---


## __init__ {#}
Creates an instance of the Aspose AI web client that connects to the default Aspose LLM endpoint.
            This is the client used by the parameterless **SlidesAIAgent.#ctor** constructor, so creating
            it explicitly is only required when passing the client to the **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A**
            constructor directly.


```python
def __init__(self):
    ...
```



## __init__ {#str}
Creates an instance of the Aspose AI web client that connects to a custom endpoint URL. Use this
            overload when you have a URL provided by the Aspose.Slides team; otherwise, use the
            **AsposeAIWebClient.#ctor** overload with the default URL.


```python
def __init__(self, url):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| url | **str** | Endpoint URL of the Aspose LLM, provided by the Aspose.Slides team. |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | URL can't be None or empty. |



### See Also
* class [`AsposeAIWebClient`](/slides/python-net/aspose.slides.ai/asposeaiwebclient)
* module [`aspose.slides.ai`](/slides/python-net/aspose.slides.ai)
* library [`Aspose.Slides`](/slides/python-net)

