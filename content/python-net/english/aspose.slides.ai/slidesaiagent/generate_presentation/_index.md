---
title: generate_presentation method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.ai/slidesaiagent/generate_presentation/
weight: 20
---


## generate_presentation {#str-presentationcontentamounttype}
Generates a presentation instance from a text description. Provide a topic, ideas, quotes, or text snippets in the required language.


```python
def generate_presentation(self, description, presentation_content_amount):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| description | **str** | The topic, ideas, quotes, or text snippets. |
| presentation_content_amount | [`PresentationContentAmountType`](/slides/python-net/aspose.slides.ai/presentationcontentamounttype) | The amount of content in the resulting presentation. |

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
| **RuntimeError(Proxy error(ArgumentException))** | AI chat instruction can't be None or empty. |


## generate_presentation {#str-presentationcontentamounttype-ipresentation}
Generates a presentation instance from a text description. Provide a topic, ideas, quotes, or text snippets in the required language.


```python
def generate_presentation(self, description, presentation_content_amount, presentation_template):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| description | **str** | The topic, ideas, quotes, or text snippets. |
| presentation_content_amount | [`PresentationContentAmountType`](/slides/python-net/aspose.slides.ai/presentationcontentamounttype) | The amount of content in the resulting presentation. |
| presentation_template | [`IPresentation`](/slides/python-net/aspose.slides/ipresentation) | A presentation to use as a template for layout and design, replacing the default template. |

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
| **RuntimeError(Proxy error(ArgumentNullException))** | Presentation template is not provided. |
| **RuntimeError(Proxy error(ArgumentException))** | AI chat instruction can't be None or empty. |



### See Also
* class [`AsposeAIWebClient`](/slides/python-net/aspose.slides.ai/asposeaiwebclient)
* class [`IAIWebClient`](/slides/python-net/aspose.slides.ai/iaiwebclient)
* class [`IPresentation`](/slides/python-net/aspose.slides/ipresentation)
* class [`OpenAICompatibleWebClient`](/slides/python-net/aspose.slides.ai/openaicompatiblewebclient)
* class [`OpenAIWebClient`](/slides/python-net/aspose.slides.ai/openaiwebclient)
* enumeration [`PresentationContentAmountType`](/slides/python-net/aspose.slides.ai/presentationcontentamounttype)
* class [`SlidesAIAgent`](/slides/python-net/aspose.slides.ai/slidesaiagent)
* module [`aspose.slides.ai`](/slides/python-net/aspose.slides.ai)
* library [`Aspose.Slides`](/slides/python-net)

