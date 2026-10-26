---
title: remove method
second_title: Aspose.Slides pro Python pomocí .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/layoutslidecollection/remove/
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
| value | [`ILayoutSlide`](/slides/python-net/cs/aspose.slides/ilayoutslide) | Rozložení snímku, které se má odstranit ze sbírky. |

### Poznámky

1) Aby se zabránilo vyhození výjimky PptxEditException, předtím zkontrolujte vlastnost HasDependingSlides rozvržení.  
2) Můžete také použít metodu [`ILayoutSlide.remove`](/slides/python-net/cs/aspose.slides/ilayoutslide/remove) pro zjednodušení kódu.

### Výjimky

| Výjimka | Popis |
| :- | :- |
| [`PptxEditException`](/slides/python-net/cs/aspose.slides/pptxeditexception) | Vyvolána, pokud je rozvržení použito v prezentaci (jeho vlastnost HasDependingSlides je true). |



### Viz také
* třída [`ILayoutSlide`](/slides/python-net/cs/aspose.slides/ilayoutslide)
* třída [`LayoutSlideCollection`](/slides/python-net/cs/aspose.slides/layoutslidecollection)
* třída [`PptxEditException`](/slides/python-net/cs/aspose.slides/pptxeditexception)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)