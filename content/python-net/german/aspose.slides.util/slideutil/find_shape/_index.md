---
title: find_shape method
second_title: Aspose.Slides für Python via .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides.util/slideutil/find_shape/
weight: 30
---
## find_shape(pres, alt_text) {#ipresentation-str}
Finde shape anhand des alternativen Textes in einer PPTX-Präsentation.

### Rückgabewert

Shape oder None.



```python
@staticmethod
def find_shape(pres, alt_text):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| pres | [`IPresentation`](/slides/python-net/de/aspose.slides/ipresentation) | Gescannte Präsentation. |
| alt_text | **str** | Alternativer Text eines shape. |


## find_shape(slide, alt_text) {#ibaseslide-str}
Finde shape anhand des alternativen Textes auf einer Folie in einer PPTX-Präsentation.

### Rückgabewert

Shape oder None.



```python
@staticmethod
def find_shape(slide, alt_text):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| slide | [`IBaseSlide`](/slides/python-net/de/aspose.slides/ibaseslide) | Gescannte Folie. |
| alt_text | **str** | Alternativer Text eines shape. |



### Siehe auch
* class [`IBaseSlide`](/slides/python-net/de/aspose.slides/ibaseslide)
* class [`IPresentation`](/slides/python-net/de/aspose.slides/ipresentation)
* class [`IShape`](/slides/python-net/de/aspose.slides/ishape)
* class [`SlideUtil`](/slides/python-net/de/aspose.slides.util/slideutil)
* module [`aspose.slides.util`](/slides/python-net/de/aspose.slides.util)
* library [`Aspose.Slides`](/slides/python-net)