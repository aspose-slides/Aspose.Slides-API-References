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

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Presentation instance is not provided |
| **RuntimeError(Proxy error(ArgumentException))** | Language value can't be None or empty |



### See Also
* class [`IPresentation`](/slides/python-net/aspose.slides/ipresentation)
* class [`SlidesAIAgent`](/slides/python-net/aspose.slides.ai/slidesaiagent)
* module [`aspose.slides.ai`](/slides/python-net/aspose.slides.ai)
* library [`Aspose.Slides`](/slides/python-net)

