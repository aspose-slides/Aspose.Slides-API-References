---
title: set_size method
second_title: Aspose.Slides voor Python via .NET API-referentie
description: 
type: docs
url: /nl/aspose.slides/islidesize/set_size/
weight: 10
---
## set_size(self, type, scale_type) {#slidesizetype-slidesizescaletype}
Stelt de slidegrootte in op type en schaalt bestaande inhoud.


```python
def set_size(self, type, scale_type):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| type | [`SlideSizeType`](/slides/python-net/nl/aspose.slides/slidesizetype) | De vooraf gedefinieerde slidegrootte die moet worden toegepast. |
| scale_type | [`SlideSizeScaleType`](/slides/python-net/nl/aspose.slides/slidesizescaletype) | De te gebruiken inhoudsschaalmodus. |

### Opmerkingen

Het toewijzen van een andere waarde dan [`SlideSizeType.CUSTOM`](/slides/python-net/nl/aspose.slides/slidesizetype/CUSTOM) past de [`ISlideSize.size`](/slides/python-net/nl/aspose.slides/islidesize/size) aan op basis van het geselecteerde type, terwijl [`ISlideSize.orientation`](/slides/python-net/nl/aspose.slides/islidesize/orientation) behouden blijft.


## set_size(self, width, height, scale_type) {#float-float-slidesizescaletype}
Stelt de slideafmetingen expliciet in en schaalt bestaande inhoud.


```python
def set_size(self, width, height, scale_type):
    ...
```


| Parameter | Type | Beschrijving |
| :- | :- | :- |
| width | **float** | De nieuwe slidebreedte, in punten. |
| height | **float** | De nieuwe slidehoogte, in punten. |
| scale_type | [`SlideSizeScaleType`](/slides/python-net/nl/aspose.slides/slidesizescaletype) | De te gebruiken inhoudsschaalmodus. |

### Opmerkingen

Dit zet de eigenschap [`ISlideSize.type`](/slides/python-net/nl/aspose.slides/islidesize/type) terug naar [`SlideSizeType.CUSTOM`](/slides/python-net/nl/aspose.slides/slidesizetype/CUSTOM) en stelt de [`ISlideSize.orientation`](/slides/python-net/nl/aspose.slides/islidesize/orientation) in.



### Zie ook
* class [`ISlideSize`](/slides/python-net/nl/aspose.slides/islidesize)
* enumeration [`SlideSizeScaleType`](/slides/python-net/nl/aspose.slides/slidesizescaletype)
* enumeration [`SlideSizeType`](/slides/python-net/nl/aspose.slides/slidesizetype)
* module [`aspose.slides`](/slides/python-net/nl/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)