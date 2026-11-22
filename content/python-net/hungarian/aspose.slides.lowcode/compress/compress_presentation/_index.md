---
title: compress_presentation method
second_title: Aspose.Slides Pythonhoz .NET API referencia
description: 
type: docs
url: /hu/aspose.slides.lowcode/compress/compress_presentation/
weight: 30
---
## compress_presentation(presentation) {#presentation}
Csökkenti egy prezentáció méretét, az összes elérhető tömörítési lépés alkalmazásával:
            
* Eltávolítja a nem használt mester diákot **Aspose.Slides.LowCode.Compress.RemoveUnusedMasterSlides(Aspose.Slide**.
* Eltávolítja a nem használt elrendezési diákot **Aspose.Slides.LowCode.Compress.RemoveUnusedLayoutSlides(Aspose.Slide**.
* Csak a beágyazott betűtípusokban ténylegesen használt glifeket tartja meg **Aspose.Slides.LowCode.Compress.CompressEmbeddedFonts(Aspose.Slide**.
* Csökkenti a képek felbontását 150 DPI-re, és eltávolítja a képek levágott részeit **Aspose.Slides.LowCode.Compress.CompressImages(Aspose.Slides.IPresentation,Aspose.Slides.Expor**.


```python
@staticmethod
def compress_presentation(presentation):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| presentation | [`Presentation`](/slides/python-net/hu/aspose.slides/presentation) | A tömörítendő prezentáció. |

### Megjegyzés

A tömörítés testreszabásához, például különböző képfelbontás használatához vagy egy lépés kihagyásához,
            hívja meg a fent felsorolt metódusokat egyenként ennek helyett.
            A képek levágott részei véglegesen eltávolításra kerülnek, és a PowerPointban nem állíthatók helyre.

### Kivétel

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `presentation` is `None`. |



### Lásd még
* osztály [`Compress`](/slides/python-net/hu/aspose.slides.lowcode/compress)
* osztály [`Presentation`](/slides/python-net/hu/aspose.slides/presentation)
* modul [`aspose.slides.lowcode`](/slides/python-net/hu/aspose.slides.lowcode)
* könyvtár [`Aspose.Slides`](/slides/python-net)