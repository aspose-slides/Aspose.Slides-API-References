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

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Presentation template is not provided. |
| **RuntimeError(Proxy error(ArgumentException))** | AI chat instruction can't be None or empty. |



### See Also
* class [`IPresentation`](/slides/python-net/aspose.slides/ipresentation)
* enumeration [`PresentationContentAmountType`](/slides/python-net/aspose.slides.ai/presentationcontentamounttype)
* class [`SlidesAIAgent`](/slides/python-net/aspose.slides.ai/slidesaiagent)
* module [`aspose.slides.ai`](/slides/python-net/aspose.slides.ai)
* library [`Aspose.Slides`](/slides/python-net)

