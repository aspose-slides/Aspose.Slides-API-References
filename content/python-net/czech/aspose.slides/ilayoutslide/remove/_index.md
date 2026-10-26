---
title: remove method
second_title: Aspose.Slides pro Python přes .NET API Referenci
description: 
type: docs
url: /cs/aspose.slides/ilayoutslide/remove/
weight: 60
---
## remove(self) {#}
Odstraní rozložení z prezentace.

```python
def remove(self):
    ...
```

### Poznámky

Aby nedošlo k vyhození výjimky PptxEditException, zkontrolujte předem vlastnost HasDependingSlides rozložení.

### Výjimky

| Výjimka | Popis |
| :- | :- |
| [`PptxEditException`](/slides/python-net/cs/aspose.slides/pptxeditexception) | Vyvolána, pokud je rozložení již odstraněno z prezentace nebo pokud je rozložení použito v prezentaci (její vlastnost HasDependingSlides je true). |

### Viz také
* třída [`ILayoutSlide`](/slides/python-net/cs/aspose.slides/ilayoutslide)
* třída [`PptxEditException`](/slides/python-net/cs/aspose.slides/pptxeditexception)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)