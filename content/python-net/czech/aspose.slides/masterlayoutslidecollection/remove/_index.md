---
title: remove method
second_title: Aspose.Slides pro Python pomocí .NET referenční příručky
description: 
type: docs
url: /cs/aspose.slides/masterlayoutslidecollection/remove/
weight: 60
---
## remove(self, value) {#ilayoutslide}
Odstraní rozložení ze sbírky.


```python
def remove(self, value):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| value | [`ILayoutSlide`](/slides/python-net/cs/aspose.slides/ilayoutslide) | Rozvržení snímku, které se má odstranit ze sbírky. |

### Poznámky

1) Aby se předešlo vyhození výjimky PptxEditException, zkontrolujte předtím vlastnost HasDependingSlides rozložení.  
2) Můžete také použít metodu [`ILayoutSlide.remove`](/slides/python-net/cs/aspose.slides/ilayoutslide/remove) pro zjednodušení kódu.

### Výjimky

| Výjimka | Popis |
| :- | :- |
| [`PptxEditException`](/slides/python-net/cs/aspose.slides/pptxeditexception) | Vyvolána, pokud je rozložení použito v prezentaci (její vlastnost HasDependingSlides je true). |



### Viz také
* třída [`ILayoutSlide`](/slides/python-net/cs/aspose.slides/ilayoutslide)
* třída [`MasterLayoutSlideCollection`](/slides/python-net/cs/aspose.slides/masterlayoutslidecollection)
* třída [`PptxEditException`](/slides/python-net/cs/aspose.slides/pptxeditexception)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)