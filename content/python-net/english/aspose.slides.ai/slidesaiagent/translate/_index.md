---
title: translate method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.ai/slidesaiagent/translate/
weight: 30
---


## translate {#ipresentation-str}
Translates a presentation to the specified language using AI (synchronous version).


```python
def translate(self, presentation, language):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| presentation | [`IPresentation`](/slides/python-net/aspose.slides/ipresentation) | Target presentation |
| language | **str** | Target language |

### Remarks

The example below uses the default [`AsposeAIWebClient`](/slides/python-net/aspose.slides.ai/asposeaiwebclient), which is created by the
             parameterless **SlidesAIAgent.#ctor** constructor and connects to Aspose's own LLM.
             To use a different AI provider, supply your own LLM, or customize the connection
             (for example, by providing your own `HttpClient`), pass an [`IAIWebClient`](/slides/python-net/aspose.slides.ai/iaiwebclient)
             implementation to the **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A** constructor. Available
             implementations include:
             
* [`AsposeAIWebClient`](/slides/python-net/aspose.slides.ai/asposeaiwebclient)
* [`OpenAIWebClient`](/slides/python-net/aspose.slides.ai/openaiwebclient)
* [`OpenAICompatibleWebClient`](/slides/python-net/aspose.slides.ai/openaicompatiblewebclient)

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Presentation instance is not provided |
| **RuntimeError(Proxy error(ArgumentException))** | Language value can't be None or empty |



### See Also
* class [`AsposeAIWebClient`](/slides/python-net/aspose.slides.ai/asposeaiwebclient)
* class [`IAIWebClient`](/slides/python-net/aspose.slides.ai/iaiwebclient)
* class [`IPresentation`](/slides/python-net/aspose.slides/ipresentation)
* class [`OpenAICompatibleWebClient`](/slides/python-net/aspose.slides.ai/openaicompatiblewebclient)
* class [`OpenAIWebClient`](/slides/python-net/aspose.slides.ai/openaiwebclient)
* class [`SlidesAIAgent`](/slides/python-net/aspose.slides.ai/slidesaiagent)
* module [`aspose.slides.ai`](/slides/python-net/aspose.slides.ai)
* library [`Aspose.Slides`](/slides/python-net)

