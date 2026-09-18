---
title: set_size method
second_title: Aspose.Slides Pythonhoz .NET-en keresztül API-referencia
description: 
type: docs
url: /hu/aspose.slides/islidesize/set_size/
weight: 10
---
## set_size(self, type, scale_type) {#slidesizetype-slidesizescaletype}
Beállítja a diavetítés méretét típus szerint, és átméretezi a meglévő tartalmat.

```python
def set_size(self, type, scale_type):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| type | [`SlideSizeType`](/slides/python-net/hu/aspose.slides/slidesizetype) | A alkalmazandó előre definiált diavetítés mérete. |
| scale_type | [`SlideSizeScaleType`](/slides/python-net/hu/aspose.slides/slidesizescaletype) | A használandó tartalom méretezési mód. |

### Megjegyzés

A [`SlideSizeType.CUSTOM`](/slides/python-net/hu/aspose.slides/slidesizetype/CUSTOM)-tól eltérő érték megadása a [`ISlideSize.size`](/slides/python-net/hu/aspose.slides/islidesize/size)-t a kiválasztott típus szerint módosítja, miközben megőrzi a [`ISlideSize.orientation`](/slides/python-net/hu/aspose.slides/islidesize/orientation)-t.

## set_size(self, width, height, scale_type) {#float-float-slidesizescaletype}
Kifejezetten beállítja a dia méreteit, és átméretezi a meglévő tartalmat.

```python
def set_size(self, width, height, scale_type):
    ...
```

| Paraméter | Típus | Leírás |
| :- | :- | :- |
| width | **float** | Az új dia szélessége pontban. |
| height | **float** | Az új dia magassága pontban. |
| scale_type | [`SlideSizeScaleType`](/slides/python-net/hu/aspose.slides/slidesizescaletype) | A használandó tartalom méretezési mód. |

### Megjegyzés

Ez visszaállítja a [`ISlideSize.type`](/slides/python-net/hu/aspose.slides/islidesize/type) tulajdonságot [`SlideSizeType.CUSTOM`](/slides/python-net/hu/aspose.slides/slidesizetype/CUSTOM) értékre, és beállítja a [`ISlideSize.orientation`](/slides/python-net/hu/aspose.slides/islidesize/orientation)-t.

### Lásd még
* osztály [`ISlideSize`](/slides/python-net/hu/aspose.slides/islidesize)
* enumeráció [`SlideSizeScaleType`](/slides/python-net/hu/aspose.slides/slidesizescaletype)
* enumeráció [`SlideSizeType`](/slides/python-net/hu/aspose.slides/slidesizetype)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)