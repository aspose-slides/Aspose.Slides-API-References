---
title: add_clone method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/globallayoutslidecollection/add_clone/
weight: 20
---
## add_clone(self, source_layout) {#ilayoutslide}
Fügt der Präsentation eine Kopie einer angegebenen Layout-Folie hinzu.

### Rückgabewert

Hinzugefügte Folie.



```python
def add_clone(self, source_layout):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source_layout | [`ILayoutSlide`](/slides/python-net/de/aspose.slides/ilayoutslide) | Folie zum Klonen. |

### Hinweise

Wenn ein Layout zwischen verschiedenen Präsentationen geklont wird, kann der Master des Layouts ebenfalls geklont werden,
            um die Quellformatierung beizubehalten.
            Ein internes Verzeichnis wird verwendet, um automatisch geklonte Master zu verfolgen, um die Erstellung von 
            mehreren Klonen derselben Masterfolie zu verhindern.
            Das manuelle Klonen von Masterfolien wird weder verhindert noch registriert.


## add_clone(self, source_layout, dest_master) {#ilayoutslide-imasterslide}
Fügt der Präsentation eine Kopie einer angegebenen Layout-Folie hinzu.

### Rückgabewert

Hinzugefügte Folie.



```python
def add_clone(self, source_layout, dest_master):
    ...
```


| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source_layout | [`ILayoutSlide`](/slides/python-net/de/aspose.slides/ilayoutslide) | Folie zum Klonen. |
| dest_master | [`IMasterSlide`](/slides/python-net/de/aspose.slides/imasterslide) | Masterfolie für ein neues Layout. |

### Hinweise

1) Das neue Layout wird mit dem definierten Master in der Zielpräsentation verknüpft.
            Das ist also das Gegenstück zu Kopieren/Einfügen mit der Option „Use Destination Theme“ in PowerPoint.
            2) Das Gegenstück zu dieser Methode ist die Methode **Aspose.Slides.IMasterLayoutSlideCollection.AddClone(Aspose.Slide**
            zugegriffen über die Eigenschaft [`IMasterSlide.layout_slides`](/slides/python-net/de/aspose.slides/imasterslide/layout_slides).



### Siehe auch
* Klasse [`GlobalLayoutSlideCollection`](/slides/python-net/de/aspose.slides/globallayoutslidecollection)
* Klasse [`ILayoutSlide`](/slides/python-net/de/aspose.slides/ilayoutslide)
* Klasse [`IMasterSlide`](/slides/python-net/de/aspose.slides/imasterslide)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)