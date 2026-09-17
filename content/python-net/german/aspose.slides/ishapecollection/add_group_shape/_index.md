---
title: add_group_shape method
second_title: Aspose.Slides für Python über .NET API-Referenz
description: 
type: docs
url: /de/aspose.slides/ishapecollection/add_group_shape/
weight: 80
---
## add_group_shape(self) {#}
Erstellt ein neues leeres Gruppenshape und fügt es am Ende der Shape-Sammlung hinzu. Der Rahmen der Gruppe passt sich automatisch an, um alle hinzugefügten Shapes aufzunehmen.

### Rückgabewert

Die neu erstellte [`IGroupShape`](/slides/python-net/de/aspose.slides/igroupshape).



```python
def add_group_shape(self):
    ...
```



## add_group_shape(self, svg_image, x, y, width, height) {#isvgimage-float-float-float-float}
Erstellt ein neues Gruppenshape, konvertiert das angegebene SVG-Bild in einzelne Shapes und fügt die resultierende Gruppe am Ende der Shape-Sammlung hinzu.

### Rückgabewert

Die neu erstellte [`IGroupShape`](/slides/python-net/de/aspose.slides/igroupshape).



```python
def add_group_shape(self, svg_image, x, y, width, height):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| svg_image | [`ISvgImage`](/slides/python-net/de/aspose.slides/isvgimage) | Das [`ISvgImage`](/slides/python-net/de/aspose.slides/isvgimage) enthält Vektorinhalt, der in Shapes konvertiert wird. |
| x | **float** | Die x-Koordinate des Gruppenrahmens in Punkten. |
| y | **float** | Die y-Koordinate des Gruppenrahmens in Punkten. |
| width | **float** | Die Breite des Gruppenrahmens in Punkten. |
| height | **float** | Die Höhe des Gruppenrahmens in Punkten. |

### Siehe auch
* Klasse [`IGroupShape`](/slides/python-net/de/aspose.slides/igroupshape)
* Klasse [`IShapeCollection`](/slides/python-net/de/aspose.slides/ishapecollection)
* Klasse [`ISvgImage`](/slides/python-net/de/aspose.slides/isvgimage)
* Modul [`aspose.slides`](/slides/python-net/de/aspose.slides)
* Bibliothek [`Aspose.Slides`](/slides/python-net)