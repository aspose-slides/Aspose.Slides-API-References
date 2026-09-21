---
title: set_size method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/slidesize/set_size/
weight: 10
---
## set_size(self, type, scale_type) {#slidesizetype-slidesizescaletype}
Stelt de dia-grootte in op basis van type en schaalt de bestaande inhoud.

```python
def set_size(self, type, scale_type):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| type | [`SlideSizeType`](/slides/python-net/nl/aspose.slides/slidesizetype) | De vooraf gedefinieerde dia-grootte die moet worden toegepast. |
| scale_type | [`SlideSizeScaleType`](/slides/python-net/nl/aspose.slides/slidesizescaletype) | De inhoudsschaalmodus die moet worden gebruikt. |

### Opmerkingen
Het toewijzen van een andere waarde dan [`SlideSizeType.CUSTOM`](/slides/python-net/nl/aspose.slides/slidesizetype/CUSTOM) pas de [`SlideSize.size`](/slides/python-net/nl/aspose.slides/slidesize/size)
            aan op basis van het geselecteerde type, terwijl [`SlideSize.orientation`](/slides/python-net/nl/aspose.slides/slidesize/orientation) behouden blijft.

## set_size(self, width, height, scale_type) {#float-float-slidesizescaletype}
Stelt de afmetingen van de dia expliciet in en schaalt bestaande inhoud.

```python
def set_size(self, width, height, scale_type):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| width | **float** | De nieuwe dia-breedte, in punten. |
| height | **float** | De nieuwe dia-hoogte, in punten. |
| scale_type | [`SlideSizeScaleType`](/slides/python-net/nl/aspose.slides/slidesizescaletype) | De inhoudsschaalmodus die moet worden gebruikt. |

### Opmerkingen
Dit reset de [`SlideSize.type`](/slides/python-net/nl/aspose.slides/slidesize/type) eigenschap naar [`SlideSizeType.CUSTOM`](/slides/python-net/nl/aspose.slides/slidesizetype/CUSTOM)
            en stelt de [`SlideSize.orientation`](/slides/python-net/nl/aspose.slides/slidesize/orientation) in.

### Zie ook
* klasse [`SlideSize`](/slides/python-net/nl/aspose.slides/slidesize)
* enumeratie [`SlideSizeScaleType`](/slides/python-net/nl/aspose.slides/slidesizescaletype)
* enumeratie [`SlideSizeType`](/slides/python-net/nl/aspose.slides/slidesizetype)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* bibliotheek [`Aspose.Slides`](/slides/python-net)