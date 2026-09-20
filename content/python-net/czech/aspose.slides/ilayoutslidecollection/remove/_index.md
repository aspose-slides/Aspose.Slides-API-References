---
title: remove method
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/ilayoutslidecollection/remove/
weight: 20
---
## remove(self, value) {#ilayoutslide}
Odstraní rozložení ze sbírky.


```python
def remove(self, value):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| value | [`ILayoutSlide`](/slides/python-net/cs/aspose.slides/ilayoutslide) | Rozvržení snímku k odstranění ze sbírky. |

### Poznámky

1) Aby se předešlo vyhození výjimky PptxEditException, zkontrolujte předem vlastnost HasDependingSlides rozložení.  
2) Kód můžete také zjednodušit pomocí metody [`ILayoutSlide.remove`](/slides/python-net/cs/aspose.slides/ilayoutslide/remove).

### Výjimky

| Výjimka | Popis |
| :- | :- |
| [`PptxEditException`](/slides/python-net/cs/aspose.slides/pptxeditexception) | Vyhozena, pokud je rozložení použito v prezentaci (jeho vlastnost HasDependingSlides je pravda). |



### Viz také
* třída [`ILayoutSlide`](/slides/python-net/cs/aspose.slides/ilayoutslide)
* třída [`ILayoutSlideCollection`](/slides/python-net/cs/aspose.slides/ilayoutslidecollection)
* třída [`PptxEditException`](/slides/python-net/cs/aspose.slides/pptxeditexception)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)