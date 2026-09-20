---
title: remove method
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/globallayoutslidecollection/remove/
weight: 40
---
## remove(self, value) {#ilayoutslide}
Odstraní rozložení ze sbírky.

```python
def remove(self, value):
    ...
```

| Parametr | Typ | Popis |
| :- | :- | :- |
| value | [`ILayoutSlide`](/slides/python-net/cs/aspose.slides/ilayoutslide) | Rozložení snímku, které se má odebrat ze sbírky. |

### Poznámky

1) Aby se předešlo vyhození výjimky PptxEditException, zkontrolujte předem vlastnost HasDependingSlides rozvržení.  
2) Můžete také použít metodu [`ILayoutSlide.remove`](/slides/python-net/cs/aspose.slides/ilayoutslide/remove) pro zjednodušení kódu.

### Výjimky

| Výjimka | Popis |
| :- | :- |
| [`PptxEditException`](/slides/python-net/cs/aspose.slides/pptxeditexception) | Vyvolána, pokud je rozvržení použito v prezentaci (jeho vlastnost HasDependingSlides je true). |

### Viz také
* třída [`GlobalLayoutSlideCollection`](/slides/python-net/cs/aspose.slides/globallayoutslidecollection)
* třída [`ILayoutSlide`](/slides/python-net/cs/aspose.slides/ilayoutslide)
* třída [`PptxEditException`](/slides/python-net/cs/aspose.slides/pptxeditexception)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)