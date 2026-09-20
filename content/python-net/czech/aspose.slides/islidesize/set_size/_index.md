---
title: set_size method
second_title: Aspose.Slides pro Python prostřednictvím .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/islidesize/set_size/
weight: 10
---
## set_size(self, type, scale_type) {#slidesizetype-slidesizescaletype}
Nastaví velikost snímku podle typu a škáluje existující obsah.


```python
def set_size(self, type, scale_type):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| type | [`SlideSizeType`](/slides/python-net/cs/aspose.slides/slidesizetype) | Předdefinovaná velikost snímku, která se použije. |
| scale_type | [`SlideSizeScaleType`](/slides/python-net/cs/aspose.slides/slidesizescaletype) | Režim škálování obsahu, který se použije. |

### Poznámky

Přiřazením jakékoli hodnoty jinak než [`SlideSizeType.CUSTOM`](/slides/python-net/cs/aspose.slides/slidesizetype/CUSTOM) se upraví [`ISlideSize.size`](/slides/python-net/cs/aspose.slides/islidesize/size) podle vybraného typu, přičemž se zachová [`ISlideSize.orientation`](/slides/python-net/cs/aspose.slides/islidesize/orientation).


## set_size(self, width, height, scale_type) {#float-float-slidesizescaletype}
Nastaví rozměry snímku explicitně a škáluje existující obsah.


```python
def set_size(self, width, height, scale_type):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| width | **float** | Nová šířka snímku v bodech. |
| height | **float** | Nová výška snímku v bodech. |
| scale_type | [`SlideSizeScaleType`](/slides/python-net/cs/aspose.slides/slidesizescaletype) | Režim škálování obsahu, který se použije. |

### Poznámky

Tím se resetuje vlastnost [`ISlideSize.type`](/slides/python-net/cs/aspose.slides/islidesize/type) na [`SlideSizeType.CUSTOM`](/slides/python-net/cs/aspose.slides/slidesizetype/CUSTOM) a nastaví se [`ISlideSize.orientation`](/slides/python-net/cs/aspose.slides/islidesize/orientation).



### Viz také
* třída [`ISlideSize`](/slides/python-net/cs/aspose.slides/islidesize)
* enumerace [`SlideSizeScaleType`](/slides/python-net/cs/aspose.slides/slidesizescaletype)
* enumerace [`SlideSizeType`](/slides/python-net/cs/aspose.slides/slidesizetype)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)