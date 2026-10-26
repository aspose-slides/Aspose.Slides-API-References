---
title: insert_clone method
second_title: Aspose.Slides dla Pythona poprzez .NET API Reference
description: 
type: docs
url: /pl/aspose.slides/masterlayoutslidecollection/insert_clone/
weight: 50
---
## insert_clone(self, index, source_layout) {#int-ilayoutslide}
Wstawia kopię określonego slajdu układu na określone miejsce w kolekcji.

### Returns
Wstawiony slajd.

```python
def insert_clone(self, index, source_layout):
    ...
```

| Parametr | Typ | Opis |
| :- | :- | :- |
| index | **int** | Indeks nowego slajdu. |
| source_layout | [`ILayoutSlide`](/slides/python-net/pl/aspose.slides/ilayoutslide) | Slajd do sklonowania. |

### Remarks
Nowy układ będzie powiązany z nadrzędnym slajdem master dla tej kolekcji slajdów układu.
            Jest to analogia do kopiuj/wklej z opcją „Use Destination Theme” w PowerPoint.

### See Also
* klasa [`ILayoutSlide`](/slides/python-net/pl/aspose.slides/ilayoutslide)
* klasa [`MasterLayoutSlideCollection`](/slides/python-net/pl/aspose.slides/masterlayoutslidecollection)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)