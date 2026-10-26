---
title: remove_at method
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/imasterlayoutslidecollection/remove_at/
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

1) Aby se zabránilo vyhození výjimky PptxEditException, zkontrolujte předtím vlastnost HasDependingSlides rozložení.
2) Můžete také použít metodu [`ILayoutSlide.remove`](/slides/python-net/cs/aspose.slides/ilayoutslide/remove) pro zjednodušení kódu.

### Výjimky

| Výjimka | Popis |
| :- | :- |
| [`PptxEditException`](/slides/python-net/cs/aspose.slides/pptxeditexception) | Vyvolána, pokud je rozložení použito v prezentaci (jeho vlastnost HasDependingSlides je true). |



### Viz také
* třída [`IMasterLayoutSlideCollection`](/slides/python-net/cs/aspose.slides/imasterlayoutslidecollection)
* třída [`PptxEditException`](/slides/python-net/cs/aspose.slides/pptxeditexception)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)