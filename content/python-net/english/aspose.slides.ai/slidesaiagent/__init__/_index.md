---
title: SlidesAIAgent constructor
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.ai/slidesaiagent/__init__/
weight: 10
---


## __init__ {#}
Initializes a new instance of [`SlidesAIAgent`](/slides/python-net/aspose.slides.ai/slidesaiagent) using the built-in
            [`AsposeAIWebClient`](/slides/python-net/aspose.slides.ai/asposeaiwebclient) with its default configuration. The client connects to
            Aspose's own LLM and requires no additional configuration.
            To use a different AI client, use the **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A** overload instead.


```python
def __init__(self):
    ...
```



## __init__ {#iaiwebclient}
Initializes a new instance of [`SlidesAIAgent`](/slides/python-net/aspose.slides.ai/slidesaiagent) with a custom AI client.
            Use this overload to specify the AI provider, supply your own LLM, or customize the
            connection (for example, by providing your own `HttpClient`).
            Any implementation of [`IAIWebClient`](/slides/python-net/aspose.slides.ai/iaiwebclient) can be used, including:
            
* [`AsposeAIWebClient`](/slides/python-net/aspose.slides.ai/asposeaiwebclient)
* [`OpenAIWebClient`](/slides/python-net/aspose.slides.ai/openaiwebclient)
* [`OpenAICompatibleWebClient`](/slides/python-net/aspose.slides.ai/openaicompatiblewebclient)


            To use the built-in [`AsposeAIWebClient`](/slides/python-net/aspose.slides.ai/asposeaiwebclient) with its default configuration,
            use the **SlidesAIAgent.#ctor** overload instead.


```python
def __init__(self, ai_client):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| ai_client | [`IAIWebClient`](/slides/python-net/aspose.slides.ai/iaiwebclient) | AI client instance. Any implementation of [`IAIWebClient`](/slides/python-net/aspose.slides.ai/iaiwebclient) can be used. |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | AI client instance is not provided. |



### See Also
* class [`AsposeAIWebClient`](/slides/python-net/aspose.slides.ai/asposeaiwebclient)
* class [`IAIWebClient`](/slides/python-net/aspose.slides.ai/iaiwebclient)
* class [`OpenAICompatibleWebClient`](/slides/python-net/aspose.slides.ai/openaicompatiblewebclient)
* class [`OpenAIWebClient`](/slides/python-net/aspose.slides.ai/openaiwebclient)
* class [`SlidesAIAgent`](/slides/python-net/aspose.slides.ai/slidesaiagent)
* module [`aspose.slides.ai`](/slides/python-net/aspose.slides.ai)
* library [`Aspose.Slides`](/slides/python-net)

