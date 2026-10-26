---
title: insert_clone method
second_title: Aspose.Slides pro Python prostřednictvím .NET referenční příručky API
description: 
type: docs
url: /cs/aspose.slides/masterlayoutslidecollection/insert_clone/
weight: 50
---
## insert_clone(self, index, source_layout) {#int-ilayoutslide}
Vloží kopii zadaného rozložení snímku na určenou pozici ve sbírce.

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
Nové rozložení bude propojeno s nadřazeným hlavním snímkem pro tuto sbírku snímků rozložení. Jedná se tedy o ekvivalent kopírování/vkládání s volbou „Use Destination Theme“ v PowerPointu.

### Viz také
* třída [`ILayoutSlide`](/slides/python-net/cs/aspose.slides/ilayoutslide)
* třída [`MasterLayoutSlideCollection`](/slides/python-net/cs/aspose.slides/masterlayoutslidecollection)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)