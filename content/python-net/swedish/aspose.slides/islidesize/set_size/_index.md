---
title: set_size method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/islidesize/set_size/
weight: 10
---
## set_size(self, type, scale_type) {#slidesizetype-slidesizescaletype}
Ställer in bildstorleken efter typ och skalar befintligt innehåll.

```python
def set_size(self, type, scale_type):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| type | [`SlideSizeType`](/slides/python-net/sv/aspose.slides/slidesizetype) | Den fördefinierade bildstorleken att använda. |
| scale_type | [`SlideSizeScaleType`](/slides/python-net/sv/aspose.slides/slidesizescaletype) | Innehållsskaleringsläget att använda. |

### Anmärkningar

Att tilldela något värde annat än [`SlideSizeType.CUSTOM`](/slides/python-net/sv/aspose.slides/slidesizetype/CUSTOM) justerar [`ISlideSize.size`](/slides/python-net/sv/aspose.slides/islidesize/size) baserat på den valda typen, samtidigt som [`ISlideSize.orientation`](/slides/python-net/sv/aspose.slides/islidesize/orientation) bevaras.

## set_size(self, width, height, scale_type) {#float-float-slidesizescaletype}
Ställer in bildens mått explicit och skalar befintligt innehåll.

```python
def set_size(self, width, height, scale_type):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| width | **float** | Den nya bildbredden, i punkter. |
| height | **float** | Den nya bildhöjden, i punkter. |
| scale_type | [`SlideSizeScaleType`](/slides/python-net/sv/aspose.slides/slidesizescaletype) | Innehållsskaleringsläget att använda. |

### Anmärkningar

Det här återställer [`ISlideSize.type`](/slides/python-net/sv/aspose.slides/islidesize/type) egenskapen till [`SlideSizeType.CUSTOM`](/slides/python-net/sv/aspose.slides/slidesizetype/CUSTOM) och sätter [`ISlideSize.orientation`](/slides/python-net/sv/aspose.slides/islidesize/orientation).

### Se även
* klass [`ISlideSize`](/slides/python-net/sv/aspose.slides/islidesize)
* enumeration [`SlideSizeScaleType`](/slides/python-net/sv/aspose.slides/slidesizescaletype)
* enumeration [`SlideSizeType`](/slides/python-net/sv/aspose.slides/slidesizetype)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)