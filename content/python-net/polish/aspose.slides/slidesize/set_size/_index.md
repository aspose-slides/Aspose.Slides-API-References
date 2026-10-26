---
title: set_size method
second_title: Aspose.Slides dla Pythona poprzez .NET – odniesienie API
description: 
type: docs
url: /pl/aspose.slides/slidesize/set_size/
weight: 10
---
## set_size(self, type, scale_type) {#slidesizetype-slidesizescaletype}
Ustawia rozmiar slajdu według typu i skaluje istniejącą zawartość.


```python
def set_size(self, type, scale_type):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| type | [`SlideSizeType`](/slides/python-net/pl/aspose.slides/slidesizetype) | The predefined slide size to apply. |
| scale_type | [`SlideSizeScaleType`](/slides/python-net/pl/aspose.slides/slidesizescaletype) | The content scaling mode to use. |

### Uwagi

Przypisanie dowolnej wartości oprócz [`SlideSizeType.CUSTOM`](/slides/python-net/pl/aspose.slides/slidesizetype/CUSTOM) dostosowuje [`SlideSize.size`](/slides/python-net/pl/aspose.slides/slidesize/size) w zależności od wybranego typu, zachowując [`SlideSize.orientation`](/slides/python-net/pl/aspose.slides/slidesize/orientation).


## set_size(self, width, height, scale_type) {#float-float-slidesizescaletype}
Ustawia wymiary slajdu wyraźnie i skaluje istniejącą zawartość.


```python
def set_size(self, width, height, scale_type):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| width | **float** | The new slide width, in points. |
| height | **float** | The new slide height, in points. |
| scale_type | [`SlideSizeScaleType`](/slides/python-net/pl/aspose.slides/slidesizescaletype) | The content scaling mode to use. |

### Uwagi

To resetuje właściwość [`SlideSize.type`](/slides/python-net/pl/aspose.slides/slidesize/type) do [`SlideSizeType.CUSTOM`](/slides/python-net/pl/aspose.slides/slidesizetype/CUSTOM) i ustawia [`SlideSize.orientation`](/slides/python-net/pl/aspose.slides/slidesize/orientation).



### Zobacz także
* klasa [`SlideSize`](/slides/python-net/pl/aspose.slides/slidesize)
* wyliczenie [`SlideSizeScaleType`](/slides/python-net/pl/aspose.slides/slidesizescaletype)
* wyliczenie [`SlideSizeType`](/slides/python-net/pl/aspose.slides/slidesizetype)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)