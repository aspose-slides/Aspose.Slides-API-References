---
title: remove_at method
second_title: Aspose.Slides pro Python prostřednictvím .NET API
description: 
type: docs
url: /cs/aspose.slides/masterslidecollection/remove_at/
weight: 40
---
## remove_at(self, index) {#int}
Odstraní prvek na určeném indexu kolekce.

```python
def remove_at(self, index):
    ...
```

| Parametr | Typ | Popis |
| :- | :- | :- |
| index | **int** | Index prvku k odstranění, počítáno od nuly. |

### Poznámky

Aby se předešlo vyhození výjimky PptxEditException, předtím zkontrolujte vlastnost HasDependingSlides mistra.

### Výjimky

| Výjimka | Popis |
| :- | :- |
| [`PptxEditException`](/slides/python-net/cs/aspose.slides/pptxeditexception) | Vyvolána, pokud je odstraněný mistr použit v prezentaci (jeho vlastnost HasDependingSlides je true). |

### Viz také
* třída [`MasterSlideCollection`](/slides/python-net/cs/aspose.slides/masterslidecollection)
* třída [`PptxEditException`](/slides/python-net/cs/aspose.slides/pptxeditexception)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)