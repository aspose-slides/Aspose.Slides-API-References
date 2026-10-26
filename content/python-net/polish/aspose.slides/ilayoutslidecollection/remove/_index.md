---
title: remove method
second_title: Aspose.Slides dla Pythona przez .NET API Reference
description: 
type: docs
url: /pl/aspose.slides/ilayoutslidecollection/remove/
weight: 20
---
## remove(self, value) {#ilayoutslide}
Usuwa układ z kolekcji.

```python
def remove(self, value):
    ...
```

| Parametr | Typ | Opis |
| :- | :- | :- |
| value | [`ILayoutSlide`](/slides/python-net/pl/aspose.slides/ilayoutslide) | Slajd układu do usunięcia z kolekcji. |

### Uwagi

1) Aby uniknąć rzucenia PptxEditException, sprawdź właściwość HasDependingSlides układu wcześniej.
2) Możesz również użyć metody [`ILayoutSlide.remove`](/slides/python-net/pl/aspose.slides/ilayoutslide/remove), aby uprościć kod.

### Wyjątki

| Wyjątek | Opis |
| :- | :- |
| [`PptxEditException`](/slides/python-net/pl/aspose.slides/pptxeditexception) | Rzucany, jeśli układ jest używany w prezentacji (jego właściwość HasDependingSlides jest prawdziwa). |

### Zobacz także
* klasa [`ILayoutSlide`](/slides/python-net/pl/aspose.slides/ilayoutslide)
* klasa [`ILayoutSlideCollection`](/slides/python-net/pl/aspose.slides/ilayoutslidecollection)
* klasa [`PptxEditException`](/slides/python-net/pl/aspose.slides/pptxeditexception)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)