---
title: remove_at method
second_title: Aspose.Slides pro Python prostřednictvím .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/masterlayoutslidecollection/remove_at/
weight: 70
---
## remove_at(self, index) {#int}
Odstraní prvek na zadaném indexu kolekce.

```python
def remove_at(self, index):
    ...
```

| Parametr | Typ | Popis |
| :- | :- | :- |
| index | **int** | Nulový index prvku, který se má odstranit. |

### Poznámky

1) Aby se předešlo vyhození výjimky PptxEditException, zkontrolujte předtím vlastnost HasDependingSlides rozvržení.
2) Pro usnadnění kódu můžete také použít metodu [`ILayoutSlide.remove`](/slides/python-net/cs/aspose.slides/ilayoutslide/remove).

### Výjimky

| Výjimka | Popis |
| :- | :- |
| [`PptxEditException`](/slides/python-net/cs/aspose.slides/pptxeditexception) | Vyvolána, pokud je rozvržení použito v prezentaci (jeho vlastnost HasDependingSlides je true). |

### Viz také
* třída [`MasterLayoutSlideCollection`](/slides/python-net/cs/aspose.slides/masterlayoutslidecollection)
* třída [`PptxEditException`](/slides/python-net/cs/aspose.slides/pptxeditexception)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)