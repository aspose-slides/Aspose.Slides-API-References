---
title: InsertConnector()
second_title: Aspose.Slides C++ API Referencia
description: Létrehoz egy új csatlakozó alakzatot, és a megadott indexnél beilleszti az alakzatgyűjteménybe, az alapértelmezett sablonstílus alkalmazásával.
type: docs
weight: 430
url: /hu/aspose.slides/shapecollection/insertconnector/
---
## ShapeCollection::InsertConnector(int32_t, ShapeType, float, float, float, float) metódus

Létrehoz egy új csatlakozó alakzatot, és a megadott indexnél beilleszti az alakzatgyűjteménybe, az alapértelmezett sablonstílus alkalmazásával.

```cpp
System::SharedPtr<IConnector> Aspose::Slides::ShapeCollection::InsertConnector(int32_t index, ShapeType shapeType, float x, float y, float width, float height) override
```

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | A nulla alapú index, amelynél a csatlakozó alakzatot beilleszti. |
| shapeType | [ShapeType](../../shapetype/) | A [ShapeType](../../shapetype/) a beillesztendő csatlakozó alakzat. |
| x | **float** | A csatlakozó keretének x-koordinátája pontban. |
| y | **float** | A csatlakozó keretének y-koordinátája pontban. |
| width | **float** | A csatlakozó keretének szélessége pontban. |
| height | **float** | A csatlakozó keretének magassága pontban. |

### Visszatérési érték

Az újonnan létrehozott [IConnector](../../iconnector/).

## ShapeCollection::InsertConnector(int32_t, ShapeType, float, float, float, float, bool) metódus

Létrehoz egy új csatlakozó alakzatot, és a megadott indexnél beilleszti az alakzatgyűjteménybe, opcionálisan az alapértelmezett sablonstílus alkalmazásával.

```cpp
System::SharedPtr<IConnector> Aspose::Slides::ShapeCollection::InsertConnector(int32_t index, ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate) override
```

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | A nulla alapú index, amelynél a csatlakozó alakzatot beilleszti. |
| shapeType | [ShapeType](../../shapetype/) | A [ShapeType](../../shapetype/) a beillesztendő csatlakozó alakzat. |
| x | **float** | A csatlakozó keretének x-koordinátája pontban. |
| y | **float** | A csatlakozó keretének y-koordinátája pontban. |
| width | **float** | A csatlakozó keretének szélessége pontban. |
| height | **float** | A csatlakozó keretének magassága pontban. |
| createFromTemplate | **bool** | Igaz, ha az alapértelmezett sablonstílust alkalmazza (nem üres név, egyszerű stílus); hamis, ha a csatlakozót alapértelmezett tulajdonságértékekkel hozza létre. |

### Visszatérési érték

Az újonnan létrehozott [IConnector](../../iconnector/).

## Lásd még

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IConnector](../../iconnector/)
* Osztály [ShapeCollection](../)
* Névtér [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)