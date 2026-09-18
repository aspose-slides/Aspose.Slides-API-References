---
title: equals method
second_title: Aspose.Slides a Pythonhoz .NET-en keresztül API-referencia
description: 
type: docs
url: /hu/aspose.slides/notesslide/equals/
weight: 20
---
## equals(self, slide) {#ibaseslide}
Megállapítja, hogy a két IBaseSlide példány egyenlő-e.
            A visszatérő érték a diapozitív szerkezete és a statikus tartalom alapján kerül kiszámításra.
            Két diapozitív egyenlő, ha az összes alakzat, stílus, szöveg, animáció és egyéb beállítás, stb. egyenlő. Az összehasonlítás nem veszi figyelembe az egyedi azonosító értékeket, például a SlideId-t, illetve a dinamikus tartalmat, például a Dátumhelyőrző aktuális dátumértékét.

### Returns

**true**  ha a megadott IBaseSlide egyenlő a jelenlegi IBaseSlide-el; 
            egyébként **false** .

```python
def equals(self, slide):
    ...
```

| Paraméter | Típus | Leírás |
| :- | :- | :- |
| slide | [`IBaseSlide`](/slides/python-net/hu/aspose.slides/ibaseslide) | Az a IBaseSlide, amelyet a jelenlegi IBaseSlide-hez hasonlítunk. |

### Lásd még
* class [`IBaseSlide`](/slides/python-net/hu/aspose.slides/ibaseslide)
* class [`NotesSlide`](/slides/python-net/hu/aspose.slides/notesslide)
* module [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)