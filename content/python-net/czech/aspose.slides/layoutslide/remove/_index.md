---
title: remove method
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/layoutslide/remove/
weight: 60
---
## remove(self) {#}
Odstraní rozvržení z prezentace.

```python
def remove(self):
    ...
```

### Poznámky

Aby nedošlo k vyhození výjimky PptxEditException, předtím zkontrolujte vlastnost HasDependingSlides rozvržení.

### Výjimky

| Výjimka | Popis |
| :- | :- |
| [`PptxEditException`](/slides/python-net/cs/aspose.slides/pptxeditexception) | Vyvolána, pokud je rozvržení již odstraněno z prezentace nebo pokud je rozvržení použito v prezentaci (jeho <br/> HasDependingSlides property je true). |

### Viz také
* třída [`LayoutSlide`](/slides/python-net/cs/aspose.slides/layoutslide)
* třída [`PptxEditException`](/slides/python-net/cs/aspose.slides/pptxeditexception)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)