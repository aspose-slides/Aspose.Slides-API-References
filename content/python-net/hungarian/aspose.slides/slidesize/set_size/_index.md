---
title: set_size method
second_title: Aspose.Slides Pythonhoz .NET API hivatkozás
description: 
type: docs
url: /hu/aspose.slides/slidesize/set_size/
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
| scale_type | [`SlideSizeScaleType`](/slides/python-net/hu/aspose.slides/slidesizescaletype) | A használandó tartalomméretezési mód. |

### Megjegyzés

Az [`SlideSizeType.CUSTOM`](/slides/python-net/hu/aspose.slides/slidesizetype/CUSTOM)-tól eltérő érték hozzárendelése a kiválasztott típus alapján módosítja a [`SlideSize.size`](/slides/python-net/hu/aspose.slides/slidesize/size)-t, miközben megőrzi a [`SlideSize.orientation`](/slides/python-net/hu/aspose.slides/slidesize/orientation)-t.

## set_size(self, width, height, scale_type) {#float-float-slidesizescaletype}
Explicit módon beállítja a diavetítés méreteit és átméretezi a meglévő tartalmat.

```python
def set_size(self, width, height, scale_type):
    ...
```

| Paraméter | Típus | Leírás |
| :- | :- | :- |
| width | **float** | Az új diavetítés szélessége pontban. |
| height | **float** | Az új diavetítés magassága pontban. |
| scale_type | [`SlideSizeScaleType`](/slides/python-net/hu/aspose.slides/slidesizescaletype) | A használandó tartalomméretezési mód. |

### Megjegyzés

Ez visszaállítja a [`SlideSize.type`](/slides/python-net/hu/aspose.slides/slidesize/type) tulajdonságot [`SlideSizeType.CUSTOM`](/slides/python-net/hu/aspose.slides/slidesizetype/CUSTOM) értékre, és beállítja a [`SlideSize.orientation`](/slides/python-net/hu/aspose.slides/slidesize/orientation)-t.

### Lásd még
* osztály [`SlideSize`](/slides/python-net/hu/aspose.slides/slidesize)
* enumeráció [`SlideSizeScaleType`](/slides/python-net/hu/aspose.slides/slidesizescaletype)
* enumeráció [`SlideSizeType`](/slides/python-net/hu/aspose.slides/slidesizetype)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)