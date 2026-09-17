---
title: add_clone method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/igloballayoutslidecollection/add_clone/
weight: 20
---
## add_clone(self, source_layout) {#ilayoutslide}
Fügt eine Kopie einer angegebenen Layout-Folie zur Präsentation hinzu.

### Rückgabe
Hinzugefügte Folie.

```python
def add_clone(self, source_layout):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source_layout | [`ILayoutSlide`](/slides/python-net/de/aspose.slides/ilayoutslide) | Zu klonende Folie. |

### Hinweise
Beim Klonen eines Layouts zwischen verschiedenen Präsentationen kann der Master des Layouts ebenfalls geklont werden, um die Quellformatierung beizubehalten.
            Das interne Register wird verwendet, um automatisch geklonte Master zu verfolgen und die Erstellung mehrerer Klone derselben Master-Folien zu verhindern.
            Das manuelle Klonen von Master-Folien wird weder verhindert noch registriert.

## add_clone(self, source_layout, dest_master) {#ilayoutslide-imasterslide}
Fügt eine Kopie einer angegebenen Layout-Folie zur Präsentation hinzu.

### Rückgabe
Hinzugefügte Folie.

```python
def add_clone(self, source_layout, dest_master):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source_layout | [`ILayoutSlide`](/slides/python-net/de/aspose.slides/ilayoutslide) | Zu klonende Folie. |
| dest_master | [`IMasterSlide`](/slides/python-net/de/aspose.slides/imasterslide) | Master-Folie für ein neues Layout. |

### Hinweise
Das neue Layout wird mit dem definierten Master in der Zielpräsentation verknüpft.
            Das entspricht dem Kopieren/Einfügen mit der Option "Use Destination Theme" in PowerPoint.

### Siehe auch
* Klasse [`IGlobalLayoutSlideCollection`](/slides/python-net/de/aspose.slides/igloballayoutslidecollection)
* Klasse [`ILayoutSlide`](/slides/python-net/de/aspose.slides/ilayoutslide)
* Klasse [`IMasterSlide`](/slides/python-net/de/aspose.slides/imasterslide)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)