---
title: remove method
second_title: Aspose.Slides dla Pythona – odwołanie do interfejsu .NET API
description: 
type: docs
url: /pl/aspose.slides/layoutslidecollection/remove/
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
| value | [`ILayoutSlide`](/slides/python-net/pl/aspose.slides/ilayoutslide) | Układ slajdu do usunięcia z kolekcji. |

### Uwagi

1) Aby uniknąć rzucania PptxEditException, sprawdź właściwość HasDependingSlides układu wcześniej.  
2) Możesz także użyć metody [`ILayoutSlide.remove`](/slides/python-net/pl/aspose.slides/ilayoutslide/remove), aby uprościć kod.

### Wyjątki

| Wyjątek | Opis |
| :- | :- |
| [`PptxEditException`](/slides/python-net/pl/aspose.slides/pptxeditexception) | Rzucany, jeśli układ jest używany w prezentacji (jego właściwość HasDependingSlides ma wartość true). |

### Zobacz także
* klasa [`ILayoutSlide`](/slides/python-net/pl/aspose.slides/ilayoutslide)
* klasa [`LayoutSlideCollection`](/slides/python-net/pl/aspose.slides/layoutslidecollection)
* klasa [`PptxEditException`](/slides/python-net/pl/aspose.slides/pptxeditexception)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)