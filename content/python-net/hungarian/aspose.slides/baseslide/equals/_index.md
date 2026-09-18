---
title: equals method
second_title: Aspose.Slides a Pythonhoz .NET API hivatkozás
description: 
type: docs
url: /hu/aspose.slides/baseslide/equals/
weight: 20
---
## equals(self, slide) {#ibaseslide}
Meghatározza, hogy a két IBaseSlide példány egyenlő-e.
A visszatérő érték a diák szerkezete és statikus tartalma alapján kerül kiszámításra.
Két dia akkor egyenlő, ha az összes alakzat, stílus, szöveg, animáció és egyéb beállítások stb. egyenlőek. Az összehasonlítás nem veszi figyelembe az egyedi azonosító értékeket, például a SlideId-t, valamint a dinamikus tartalmat, például a Dátum helyőrzőben a jelenlegi dátum értékét.

### Visszatérési érték

**true**  ha a megadott IBaseSlide egyenlő a jelenlegi IBaseSlide-del; egyébként **false** .

```python
def equals(self, slide):
    ...
```

| Paraméter | Típus | Leírás |
| :- | :- | :- |
| slide | [`IBaseSlide`](/slides/python-net/hu/aspose.slides/ibaseslide) | Az IBaseSlide, amelyet a jelenlegi IBaseSlide-hez hasonlít. |

### Lásd még
* osztály [`BaseSlide`](/slides/python-net/hu/aspose.slides/baseslide)
* osztály [`IBaseSlide`](/slides/python-net/hu/aspose.slides/ibaseslide)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)