---
title: remove method
second_title: Aspose.Slides dla Pythona poprzez .NET API Reference
description: 
type: docs
url: /pl/aspose.slides/globallayoutslidecollection/remove/
weight: 40
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

1) Aby uniknąć rzucenia PptxEditException, sprawdź wcześniej właściwość HasDependingSlides układu.  
2) Możesz również użyć metody [`ILayoutSlide.remove`](/slides/python-net/pl/aspose.slides/ilayoutslide/remove), aby uprościć kod.

### Wyjątki

| Wyjątek | Opis |
| :- | :- |
| [`PptxEditException`](/slides/python-net/pl/aspose.slides/pptxeditexception) | Rzucany, jeśli układ jest używany w prezentacji (jego właściwość HasDependingSlides jest prawdziwa). |

### Zobacz także
* klasa [`GlobalLayoutSlideCollection`](/slides/python-net/pl/aspose.slides/globallayoutslidecollection)
* klasa [`ILayoutSlide`](/slides/python-net/pl/aspose.slides/ilayoutslide)
* klasa [`PptxEditException`](/slides/python-net/pl/aspose.slides/pptxeditexception)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)