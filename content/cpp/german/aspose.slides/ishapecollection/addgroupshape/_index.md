---
title: AddGroupShape()
second_title: Aspose.Slides für C++ API Referenz
description: Erstellt eine neue leere Gruppenform und fügt sie am Ende der Formensammlung hinzu. Der Rahmen der Gruppe wird automatisch angepasst, um alle hinzugefügten Formen zu umfassen.
type: docs
weight: 352
url: /de/aspose.slides/ishapecollection/addgroupshape/
---
## IShapeCollection::AddGroupShape() Methode


Erstellt eine neue leere Gruppenform und fügt sie am Ende der Formensammlung hinzu. Der Rahmen der Gruppe wird automatisch an die hinzugefügten Formen angepasst.

```cpp
virtual System::SharedPtr<IGroupShape> Aspose::Slides::IShapeCollection::AddGroupShape()=0
```


### Rückgabewert

The newly created [IGroupShape](../../igroupshape/).

## IShapeCollection::AddGroupShape(System::SharedPtr\<ISvgImage\>, float, float, float, float) Methode


Erstellt eine neue Gruppenform, konvertiert das angegebene SVG-Bild in einzelne Formen und fügt die resultierende Gruppe am Ende der Formensammlung hinzu.

```cpp
virtual System::SharedPtr<IGroupShape> Aspose::Slides::IShapeCollection::AddGroupShape(System::SharedPtr<ISvgImage> svgImage, float x, float y, float width, float height)=0
```


### Argumente

| Parameter | Type | Description |
| --- | --- | --- |
| svgImage | [System::SharedPtr](../../../system/sharedptr/)\<[ISvgImage](../../isvgimage/)\> | Der [ISvgImage](../../isvgimage/) enthält Vektorinhalt, der in Formen konvertiert wird. |
| x | **float** | Die x-Koordinate des Rahmens der Gruppe, in Punkten. |
| y | **float** | Die y-Koordinate des Rahmens der Gruppe, in Punkten. |
| width | **float** | Die Breite des Rahmens der Gruppe, in Punkten. |
| height | **float** | Die Höhe des Rahmens der Gruppe, in Punkten. |

### Rückgabewert

The newly created [IGroupShape](../../igroupshape/).

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IGroupShape](../../igroupshape/)
* Klasse [IShapeCollection](../)
* Klasse [ISvgImage](../../isvgimage/)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)