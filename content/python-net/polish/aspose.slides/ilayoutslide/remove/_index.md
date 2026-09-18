---
title: remove method
second_title: Aspose.Slides dla Pythona via .NET – Dokumentacja API
description: 
type: docs
url: /pl/aspose.slides/ilayoutslide/remove/
weight: 60
---
## remove(self) {#}
Usuwa układ z prezentacji.


```python
def remove(self):
    ...
```


### Uwagi

Aby uniknąć wyrzucenia PptxEditException, przedtem sprawdź właściwość HasDependingSlides układu.

### Wyjątki

| Wyjątek | Opis |
| :- | :- |
| [`PptxEditException`](/slides/python-net/pl/aspose.slides/pptxeditexception) | Rzucany, jeśli układ został już usunięty z prezentacji lub jeśli układ jest używany w prezentacji (jego <br/>            HasDependingSlides property ma wartość true). |



### Zobacz także
* klasa [`ILayoutSlide`](/slides/python-net/pl/aspose.slides/ilayoutslide)
* klasa [`PptxEditException`](/slides/python-net/pl/aspose.slides/pptxeditexception)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)