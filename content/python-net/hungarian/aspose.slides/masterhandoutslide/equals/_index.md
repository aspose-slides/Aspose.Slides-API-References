---
title: equals method
second_title: Aspose.Slides a Pythonhoz .NET API-n keresztül
description: 
type: docs
url: /hu/aspose.slides/masterhandoutslide/equals/
weight: 20
---
## equals(self, slide) {#ibaseslide}
Megállapítja, hogy a két IBaseSlide példány egyenlő-e.
A visszatérési érték a dia szerkezete és statikus tartalma alapján kerül kiszámításra.
Két dia akkor egyenlő, ha minden alakzat, stílus, szöveg, animáció és egyéb beállítás (stb.) egyenlő. Az összehasonlítás nem veszi figyelembe az egyedi azonosító értékeket, például a SlideId-t, valamint a dinamikus tartalmakat, például a Date Placeholder-ben lévő aktuális dátumot.

### Visszatérési érték

**true**  ha a megadott IBaseSlide egyenlő a jelenlegi IBaseSlide-del; 
különben **false** .

```python
def equals(self, slide):
    ...
```

| Paraméter | Típus | Leírás |
| :- | :- | :- |
| slide | [`IBaseSlide`](/slides/python-net/hu/aspose.slides/ibaseslide) | Az IBaseSlide, amelyet a jelenlegi IBaseSlide-kel kell összehasonlítani. |

### Lásd még
* class [`IBaseSlide`](/slides/python-net/hu/aspose.slides/ibaseslide)
* class [`MasterHandoutSlide`](/slides/python-net/hu/aspose.slides/masterhandoutslide)
* module [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)