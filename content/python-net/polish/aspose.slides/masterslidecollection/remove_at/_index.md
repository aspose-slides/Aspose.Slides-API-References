---
title: remove_at method
second_title: Aspose.Slides dla Pythona via .NET – odniesienie API
description: 
type: docs
url: /pl/aspose.slides/masterslidecollection/remove_at/
weight: 40
---
## remove_at(self, index) {#int}
Usuwa element znajdujący się pod określonym indeksem w kolekcji.

```python
def remove_at(self, index):
    ...
```

| Parametr | Typ | Opis |
| :- | :- | :- |
| index | **int** | Indeks zerowy elementu do usunięcia. |

### Uwagi

Aby uniknąć wyrzucenia PptxEditException, przedtem sprawdź własność HasDependingSlides mastera.

### Wyjątki

| Wyjątek | Opis |
| :- | :- |
| [`PptxEditException`](/slides/python-net/pl/aspose.slides/pptxeditexception) | Rzucane, jeśli master do usunięcia jest używany w prezentacji (jego własność HasDependingSlides jest prawdziwa). |

### Zobacz także
* klasa [`MasterSlideCollection`](/slides/python-net/pl/aspose.slides/masterslidecollection)
* klasa [`PptxEditException`](/slides/python-net/pl/aspose.slides/pptxeditexception)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)