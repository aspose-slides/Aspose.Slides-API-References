---
title: AddConnector()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt eine neue Connector-Form mit Standardvorlagenstil und fügt sie am Ende der Formensammlung hinzu.
type: docs
weight: 378
url: /de/aspose.slides/ishapecollection/addconnector/
---
## IShapeCollection::AddConnector(ShapeType, float, float, float, float) Methode

Erstellt eine neue Connector-Form mit den Standardvorlagen-Stilen und fügt sie am Ende der Formensammlung hinzu.

```cpp
virtual System::SharedPtr<IConnector> Aspose::Slides::IShapeCollection::AddConnector(ShapeType shapeType, float x, float y, float width, float height)=0
```

### Parameter

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | Der [ShapeType](../../shapetype/) der hinzuzufügenden Connector-Form. |
| x | **float** | Die x-Koordinate des Rahmens der Connector-Form, in Punkten. |
| y | **float** | Die y-Koordinate des Rahmens der Connector-Form, in Punkten. |
| width | **float** | Die Breite des Rahmens der Connector-Form, in Punkten. |
| height | **float** | Die Höhe des Rahmens der Connector-Form, in Punkten. |

### Rückgabewert

Die neu erstellte [IConnector](../../iconnector/).

## IShapeCollection::AddConnector(ShapeType, float, float, float, float, bool) Methode

Erstellt eine neue Connector-Form und fügt sie am Ende der Formensammlung hinzu, wobei optional die Standardvorlagen-Stile angewendet werden.

```cpp
virtual System::SharedPtr<IConnector> Aspose::Slides::IShapeCollection::AddConnector(ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate)=0
```

### Parameter

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | Der [ShapeType](../../shapetype/) der zu erstellenden Connector-Form. |
| x | **float** | Die x-Koordinate des Rahmens der Connector-Form, in Punkten. |
| y | **float** | Die y-Koordinate des Rahmens der Connector-Form, in Punkten. |
| width | **float** | Die Breite des Rahmens der Connector-Form, in Punkten. |
| height | **float** | Die Höhe des Rahmens der Connector-Form, in Punkten. |
| createFromTemplate | **bool** | True, um die Standardvorlagen-Stile anzuwenden (nicht leerer Name, einfacher Stil); false, um den Connector mit Standardwerten der Eigenschaften zu erstellen. |

### Rückgabewert

Die neu erstellte [IConnector](../../iconnector/).

## Siehe auch

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IConnector](../../iconnector/)
* Class [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)