---
title: find_and_replace_text method
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.util/slideutil/find_and_replace_text/
weight: 20
---


## find_and_replace_text {#ipresentation-bool-str-str-portionformat}
Finds and replaces text in presentation with given format


```python
@staticmethod
def find_and_replace_text(presentation, with_masters, find, replace, format):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| presentation | [`IPresentation`](/slides/python-net/aspose.slides/ipresentation) | Scanned presentation. |
| with_masters | **bool** | Determines whether master slides should be scanned. |
| find | **str** | String value to find. |
| replace | **str** | String value to replace. |
| format | [`PortionFormat`](/slides/python-net/aspose.slides/portionformat) | Format for replacing text portion. If null then will be used format of the first <br/><br/>            character of the found string |



### See Also
* class [`IPresentation`](/slides/python-net/aspose.slides/ipresentation)
* class [`PortionFormat`](/slides/python-net/aspose.slides/portionformat)
* class [`SlideUtil`](/slides/python-net/aspose.slides.util/slideutil)
* module [`aspose.slides.util`](/slides/python-net/aspose.slides.util)
* library [`Aspose.Slides`](/slides/python-net)

