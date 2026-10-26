---
title: insert_clone method
second_title: Aspose.Slides dla Pythona przez .NET – dokumentacja API
description: 
type: docs
url: /pl/aspose.slides/imasterlayoutslidecollection/insert_clone/
weight: 50
---
## insert_clone(self, index, source_layout) {#int-ilayoutslide}
Wstawia kopię określonego slajdu układu w określone miejsce w kolekcji.

### Zwraca

Wstawiony slajd.

```python
def insert_clone(self, index, source_layout):
    ...
```

| Parametr | Typ | Opis |
| :- | :- | :- |
| index | **int** | Indeks nowego slajdu. |
| source_layout | [`ILayoutSlide`](/slides/python-net/pl/aspose.slides/ilayoutslide) | Slajd do sklonowania. |

### Uwagi

Nowy układ zostanie powiązany z nadrzędnym slajdem master dla tej kolekcji slajdów układu.  
            Jest to analogiczne do kopiuj/wklej z opcją "Use Destination Theme" w PowerPoint.

### Zobacz także
* klasa [`ILayoutSlide`](/slides/python-net/pl/aspose.slides/ilayoutslide)
* klasa [`IMasterLayoutSlideCollection`](/slides/python-net/pl/aspose.slides/imasterlayoutslidecollection)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)