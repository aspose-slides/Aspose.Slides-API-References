---
title: insert_clone method
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/imasterlayoutslidecollection/insert_clone/
weight: 50
---
## insert_clone(self, index, source_layout) {#int-ilayoutslide}
Vloží kopii určeného rozvržení snímku na zadanou pozici v kolekci.

### Návratová hodnota
Vložený snímek.

```python
def insert_clone(self, index, source_layout):
    ...
```

| Parametr | Typ | Popis |
| :- | :- | :- |
| index | **int** | Index nového snímku. |
| source_layout | [`ILayoutSlide`](/slides/python-net/cs/aspose.slides/ilayoutslide) | Snímek ke klonování. |

### Poznámky
Nové rozvržení bude propojeno s nadřízeným hlavním snímkem pro tuto kolekci snímků rozvržení. Takže se jedná o ekvivalent kopírování/vkládání s možností „Use Destination Theme“ v PowerPointu.

### Viz také
* třída [`ILayoutSlide`](/slides/python-net/cs/aspose.slides/ilayoutslide)
* třída [`IMasterLayoutSlideCollection`](/slides/python-net/cs/aspose.slides/imasterlayoutslidecollection)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)