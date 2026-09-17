---
title: insert_clone method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/imasterlayoutslidecollection/insert_clone/
weight: 50
---
## insert_clone(self, index, source_layout) {#int-ilayoutslide}
Fügt eine Kopie einer angegebenen Layout-Folien in die angegebene Position der Sammlung ein.

### Rückgabe

Eingefügte Folie.

```python
def insert_clone(self, index, source_layout):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| index | **int** | Index der neuen Folie. |
| source_layout | [`ILayoutSlide`](/slides/python-net/de/aspose.slides/ilayoutslide) | Folie zum Klonen. |

### Hinweise

Das neue Layout wird mit der übergeordneten Masterfolie für diese Layout-Folien-Sammlung verknüpft.
            Dies entspricht dem Kopieren/Einfügen mit der Option "Use Destination Theme" in PowerPoint.

### Siehe auch
* Klasse [`ILayoutSlide`](/slides/python-net/de/aspose.slides/ilayoutslide)
* Klasse [`IMasterLayoutSlideCollection`](/slides/python-net/de/aspose.slides/imasterlayoutslidecollection)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)