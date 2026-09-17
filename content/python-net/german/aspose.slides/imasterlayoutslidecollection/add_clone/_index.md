---
title: add_clone method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/imasterlayoutslidecollection/add_clone/
weight: 20
---
## add_clone(self, source_layout) {#ilayoutslide}
Fügt eine Kopie einer angegebenen Layout-Folien am Ende der Sammlung hinzu.

### Rückgabe

Hinzugefügte Folie.

```python
def add_clone(self, source_layout):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source_layout | [`ILayoutSlide`](/slides/python-net/de/aspose.slides/ilayoutslide) | Folie zum Klonen. |

### Hinweise

1) Das neue Layout wird mit dem übergeordneten Master-Slide für diese Layout-Slides-Sammlung verknüpft.  
   Dies entspricht also Kopieren/Einfügen mit der Option „Use Destination Theme“ in PowerPoint.  
2) Analoge zu dieser Methode ist die Methode **Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slides.ILayoutSlide,Aspose.Slide** zugegriffen über die [`IPresentation.layout_slides`](/slides/python-net/de/aspose.slides/ipresentation/layout_slides)-Eigenschaft.

### Siehe auch
* Klasse [`ILayoutSlide`](/slides/python-net/de/aspose.slides/ilayoutslide)
* Klasse [`IMasterLayoutSlideCollection`](/slides/python-net/de/aspose.slides/imasterlayoutslidecollection)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)