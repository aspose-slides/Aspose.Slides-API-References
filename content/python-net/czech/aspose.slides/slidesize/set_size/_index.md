---
title: set_size method
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/slidesize/set_size/
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

Při přiřazení jakékoli hodnoty jinou než [`SlideSizeType.CUSTOM`](/slides/python-net/cs/aspose.slides/slidesizetype/CUSTOM) se upraví [`SlideSize.size`](/slides/python-net/cs/aspose.slides/slidesize/size)
            podle zvoleného typu, přičemž se zachová [`SlideSize.orientation`](/slides/python-net/cs/aspose.slides/slidesize/orientation).


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

Tím se resetuje vlastnost [`SlideSize.type`](/slides/python-net/cs/aspose.slides/slidesize/type) na [`SlideSizeType.CUSTOM`](/slides/python-net/cs/aspose.slides/slidesizetype/CUSTOM)
            a nastaví se [`SlideSize.orientation`](/slides/python-net/cs/aspose.slides/slidesize/orientation).



### Viz také
* třída [`SlideSize`](/slides/python-net/cs/aspose.slides/slidesize)
* enumerace [`SlideSizeScaleType`](/slides/python-net/cs/aspose.slides/slidesizescaletype)
* enumerace [`SlideSizeType`](/slides/python-net/cs/aspose.slides/slidesizetype)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)