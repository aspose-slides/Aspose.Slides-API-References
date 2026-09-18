---
title: set_size method
second_title: Aspose.Slides dla Pythona – odniesienie API .NET
description: 
type: docs
url: /pl/aspose.slides/islidesize/set_size/
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
| type | [`SlideSizeType`](/slides/python-net/pl/aspose.slides/slidesizetype) | Wstępnie określony rozmiar slajdu do zastosowania. |
| scale_type | [`SlideSizeScaleType`](/slides/python-net/pl/aspose.slides/slidesizescaletype) | Tryb skalowania zawartości do użycia. |

### Uwagi

Przypisanie dowolnej wartości oprócz [`SlideSizeType.CUSTOM`](/slides/python-net/pl/aspose.slides/slidesizetype/CUSTOM) dostosowuje [`ISlideSize.size`](/slides/python-net/pl/aspose.slides/islidesize/size)
            w zależności od wybranego typu, zachowując [`ISlideSize.orientation`](/slides/python-net/pl/aspose.slides/islidesize/orientation).

## set_size(self, width, height, scale_type) {#float-float-slidesizescaletype}
Ustawia wymiary slajdu jawnie i skaluje istniejącą zawartość.

```python
def set_size(self, width, height, scale_type):
    ...
```

| Parametr | Typ | Opis |
| :- | :- | :- |
| width | **float** | Nowa szerokość slajdu, w punktach. |
| height | **float** | Nowa wysokość slajdu, w punktach. |
| scale_type | [`SlideSizeScaleType`](/slides/python-net/pl/aspose.slides/slidesizescaletype) | Tryb skalowania zawartości do użycia. |

### Uwagi

To resetuje właściwość [`ISlideSize.type`](/slides/python-net/pl/aspose.slides/islidesize/type) do [`SlideSizeType.CUSTOM`](/slides/python-net/pl/aspose.slides/slidesizetype/CUSTOM)
            i ustawia [`ISlideSize.orientation`](/slides/python-net/pl/aspose.slides/islidesize/orientation).

### Zobacz także
* class [`ISlideSize`](/slides/python-net/pl/aspose.slides/islidesize)
* enumeration [`SlideSizeScaleType`](/slides/python-net/pl/aspose.slides/slidesizescaletype)
* enumeration [`SlideSizeType`](/slides/python-net/pl/aspose.slides/slidesizetype)
* module [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)