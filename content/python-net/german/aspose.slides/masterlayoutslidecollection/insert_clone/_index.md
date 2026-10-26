---
title: insert_clone method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/masterlayoutslidecollection/insert_clone/
weight: 50
---
## insert_clone(self, index, source_layout) {#int-ilayoutslide}
Fügt eine Kopie einer angegebenen Layoutfolie an der angegebenen Position der Sammlung ein.

### Rückgabewert

Eingefügte Folie.



```python
def insert_clone(self, index, source_layout):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| index | **int** | Index der neuen Folie. |
| source_layout | [`ILayoutSlide`](/slides/python-net/de/aspose.slides/ilayoutslide) | Folien zum Klonen. |

### Bemerkungen

Neues Layout wird mit der übergeordneten Masterfolie für diese Layout-Folien-Sammlung verknüpft.
            Das ist das Gegenstück zum Kopieren/Einfügen mit der Option "Use Destination Theme" in PowerPoint.



### Siehe auch
* Klasse [`ILayoutSlide`](/slides/python-net/de/aspose.slides/ilayoutslide)
* Klasse [`MasterLayoutSlideCollection`](/slides/python-net/de/aspose.slides/masterlayoutslidecollection)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)