---
title: add_group_shape method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/shapecollection/add_group_shape/
weight: 80
---
## add_group_shape(self) {#}
Erstellt eine neue leere Gruppenform und fügt sie am Ende der Formsammlung hinzu.
Der Rahmen der Gruppe passt sich automatisch an, um alle hinzugefügten Formen aufzunehmen.

### Rückgabewert

Die neu erstellte [`IGroupShape`](/slides/python-net/de/aspose.slides/igroupshape).

```python
def add_group_shape(self):
    ...
```

## add_group_shape(self, svg_image, x, y, width, height) {#isvgimage-float-float-float-float}
Erstellt eine neue Gruppenform, konvertiert das angegebene SVG-Bild in einzelne Formen und fügt die resultierende Gruppe am Ende der Formsammlung hinzu.

### Rückgabewert

Die neu erstellte [`IGroupShape`](/slides/python-net/de/aspose.slides/igroupshape).

```python
def add_group_shape(self, svg_image, x, y, width, height):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| svg_image | [`ISvgImage`](/slides/python-net/de/aspose.slides/isvgimage) | Das [`ISvgImage`](/slides/python-net/de/aspose.slides/isvgimage) mit Vektorinhalt, das in Formen konvertiert werden soll. |
| x | **float** | Die x-Koordinate des Gruppenrahmens in Punkten. |
| y | **float** | Die y-Koordinate des Gruppenrahmens in Punkten. |
| width | **float** | Die Breite des Gruppenrahmens in Punkten. |
| height | **float** | Die Höhe des Gruppenrahmens in Punkten. |

### Siehe Auch
* class [`IGroupShape`](/slides/python-net/de/aspose.slides/igroupshape)
* class [`ISvgImage`](/slides/python-net/de/aspose.slides/isvgimage)
* class [`ShapeCollection`](/slides/python-net/de/aspose.slides/shapecollection)
* module [`aspose.slides`](/slides/python-net/de/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)