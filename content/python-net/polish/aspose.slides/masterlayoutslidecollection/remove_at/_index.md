---
title: remove_at method
second_title: Aspose.Slides dla Pythona za pośrednictwem .NET API
description: 
type: docs
url: /pl/aspose.slides/masterlayoutslidecollection/remove_at/
weight: 70
---
## remove_at(self, index) {#int}
Usuwa element o określonym indeksie w kolekcji.

```python
def remove_at(self, index):
    ...
```

| Parametr | Typ | Opis |
| :- | :- | :- |
| index | **int** | Indeks zerowy elementu, który ma zostać usunięty. |

### Uwagi

1) Aby uniknąć wyrzucenia PptxEditException, najpierw sprawdź właściwość HasDependingSlides układu.
2) Możesz również użyć metody [`ILayoutSlide.remove`](/slides/python-net/pl/aspose.slides/ilayoutslide/remove), aby uprościć kod.

### Wyjątki

| Wyjątek | Opis |
| :- | :- |
| [`PptxEditException`](/slides/python-net/pl/aspose.slides/pptxeditexception) | Rzucany, gdy układ jest używany w prezentacji (jego właściwość HasDependingSlides jest true). |

### Zobacz także
* klasa [`MasterLayoutSlideCollection`](/slides/python-net/pl/aspose.slides/masterlayoutslidecollection)
* klasa [`PptxEditException`](/slides/python-net/pl/aspose.slides/pptxeditexception)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)