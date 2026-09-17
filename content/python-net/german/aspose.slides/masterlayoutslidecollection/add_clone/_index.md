---
title: add_clone method
second_title: Aspose.Slides für Python via .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/masterlayoutslidecollection/add_clone/
weight: 20
---
## add_clone(self, source_layout) {#ilayoutslide}
Fügt eine Kopie einer angegebenen Layoutfolie am Ende der Sammlung hinzu.

### Rückgabewert
Hinzugefügte Folie.

```python
def add_clone(self, source_layout):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source_layout | [`ILayoutSlide`](/slides/python-net/de/aspose.slides/ilayoutslide) | Zu klonende Folie. |

### Bemerkungen
1) Das neue Layout wird mit der übergeordneten Masterfolie für diese Layout-Foliensammlung verknüpft. Dies entspricht dem Kopieren/Einfügen mit der Option „Use Destination Theme“ in PowerPoint.  
2) Das Gegenstück zu dieser Methode ist die Methode **Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slides.ILayoutSlide,Aspose.Slide** zugegriffen über die [`IPresentation.layout_slides`](/slides/python-net/de/aspose.slides/ipresentation/layout_slides)-Eigenschaft.

### Siehe auch
* Klasse [`ILayoutSlide`](/slides/python-net/de/aspose.slides/ilayoutslide)
* Klasse [`MasterLayoutSlideCollection`](/slides/python-net/de/aspose.slides/masterlayoutslidecollection)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)