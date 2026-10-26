---
title: set_size method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/slidesize/set_size/
weight: 10
---
## set_size(self, type, scale_type) {#slidesizetype-slidesizescaletype}
Ställer in bildstorleken efter typ och skalar befintligt innehåll.

```python
def set_size(self, type, scale_type):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| type | [`SlideSizeType`](/slides/python-net/sv/aspose.slides/slidesizetype) | Den fördefinierade bildstorleken som ska tillämpas. |
| scale_type | [`SlideSizeScaleType`](/slides/python-net/sv/aspose.slides/slidesizescaletype) | Det innehållsskalningsläge som ska användas. |

### Anmärkningar

Att tilldela något annat värde än [`SlideSizeType.CUSTOM`](/slides/python-net/sv/aspose.slides/slidesizetype/CUSTOM) justerar [`SlideSize.size`](/slides/python-net/sv/aspose.slides/slidesize/size) baserat på den valda typen, samtidigt som [`SlideSize.orientation`](/slides/python-net/sv/aspose.slides/slidesize/orientation) bevaras.

## set_size(self, width, height, scale_type) {#float-float-slidesizescaletype}
Ställer in bildens dimensioner explicit och skalar befintligt innehåll.

```python
def set_size(self, width, height, scale_type):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| width | **float** | Den nya bildbredden i punkter. |
| height | **float** | Den nya bildhöjden i punkter. |
| scale_type | [`SlideSizeScaleType`](/slides/python-net/sv/aspose.slides/slidesizescaletype) | Det innehållsskalningsläge som ska användas. |

### Anmärkningar

Detta återställer egenskapen [`SlideSize.type`](/slides/python-net/sv/aspose.slides/slidesize/type) till [`SlideSizeType.CUSTOM`](/slides/python-net/sv/aspose.slides/slidesizetype/CUSTOM) och sätter [`SlideSize.orientation`](/slides/python-net/sv/aspose.slides/slidesize/orientation).

### Se även
* klass [`SlideSize`](/slides/python-net/sv/aspose.slides/slidesize)
* enumeration [`SlideSizeScaleType`](/slides/python-net/sv/aspose.slides/slidesizescaletype)
* enumeration [`SlideSizeType`](/slides/python-net/sv/aspose.slides/slidesizetype)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)