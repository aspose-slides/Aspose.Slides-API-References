---
title: AddConnector()
second_title: Aspose.Slides C++ API Referenciája
description: Létrehoz egy új csatlakozó alakzatot az alapértelmezett sablon stílussal, és a alakzatsorozat végéhez adja hozzá.
type: docs
weight: 378
url: /hu/aspose.slides/ishapecollection/addconnector/
---
## IShapeCollection::AddConnector(ShapeType, float, float, float, float) metódus

Creates a new connector shape with default template styling and adds it to the end of the shape collection.

```cpp
virtual System::SharedPtr<IConnector> Aspose::Slides::IShapeCollection::AddConnector(ShapeType shapeType, float x, float y, float width, float height)=0
```

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | A hozzáadandó csatlakozó alakzat [ShapeType](../../shapetype/)-ja. |
| x | **float** | A csatlakozó keretének x-koordinátája, pontban. |
| y | **float** | A csatlakozó keretének y-koordinátája, pontban. |
| width | **float** | A csatlakozó keretének szélessége, pontban. |
| height | **float** | A csatlakozó keretének magassága, pontban. |

### Visszatérési érték

Az újonnan létrehozott [IConnector](../../iconnector/).

## IShapeCollection::AddConnector(ShapeType, float, float, float, float, bool) metódus

Létrehoz egy új csatlakozó alakzatot, és a alakzatsorozat végére helyezi, opcionálisan alkalmazva az alapértelmezett sablon stílusát.

```cpp
virtual System::SharedPtr<IConnector> Aspose::Slides::IShapeCollection::AddConnector(ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate)=0
```

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | A létrehozandó csatlakozó alakzat [ShapeType](../../shapetype/)-ja. |
| x | **float** | A csatlakozó keretének x-koordinátája, pontban. |
| y | **float** | A csatlakozó keretének y-koordinátája, pontban. |
| width | **float** | A csatlakozó keretének szélessége, pontban. |
| height | **float** | A csatlakozó keretének magassága, pontban. |
| createFromTemplate | **bool** | Igaz, ha az alapértelmezett sablon stílust akarja alkalmazni (nem üres név, egyszerű stílus); hamis, ha a csatlakozót az alapértelmezett tulajdonságértékekkel hozza létre. |

### Visszatérési érték

Az újonnan létrehozott [IConnector](../../iconnector/).

## Lásd még

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IConnector](../../iconnector/)
* Osztály [IShapeCollection](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)