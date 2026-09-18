---
title: equals method
second_title: Aspose.Slides Pythonhoz .NET API hivatkozás
description: 
type: docs
url: /hu/aspose.slides/slide/equals/
weight: 20
---
## equals(self, slide) {#ibaseslide}
Megállapítja, hogy a két IBaseSlide példány egyenlő-e.
A visszatérési érték a dia szerkezete és a statikus tartalom alapján kerül kiszámításra.
Két dia akkor egyenlő, ha minden alakzat, stílus, szöveg, animáció és egyéb beállítás stb. egyenlő. Az összehasonlítás nem veszi figyelembe az egyedi azonosító értékeket, például a SlideId-t, illetve a dinamikus tartalmat, például a Dátumhelyőrzőben lévő aktuális dátumértéket.

### Visszatérési érték

**true**, ha a megadott IBaseSlide egyenlő a jelenlegi IBaseSlide-del; egyébként **false** .

```python
def equals(self, slide):
    ...
```

| Paraméter | Típus | Leírás |
| :- | :- | :- |
| slide | [`IBaseSlide`](/slides/python-net/hu/aspose.slides/ibaseslide) | Az IBaseSlide, amelyet a jelenlegi IBaseSlide-del hasonlítunk össze. |

### Lásd még
* osztály [`IBaseSlide`](/slides/python-net/hu/aspose.slides/ibaseslide)
* osztály [`Slide`](/slides/python-net/hu/aspose.slides/slide)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)