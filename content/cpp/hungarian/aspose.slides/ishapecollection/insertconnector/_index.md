---
title: InsertConnector()
second_title: Aspose.Slides C++ API referenciája
description: Új csatlakozó alakzatot hoz létre, és a megadott indexen beilleszti az alakzatgyűjteménybe, az alapértelmezett sablonstílus alkalmazásával.
type: docs
weight: 391
url: /hu/aspose.slides/ishapecollection/insertconnector/
---
## IShapeCollection::InsertConnector(int32_t, ShapeType, float, float, float, float) metódus

Új csatlakozó alakzatot hoz létre, és a megadott indexen illeszti be az alakzatgyűjteménybe, az alapértelmezett sablonstílus alkalmazásával.

```cpp
virtual System::SharedPtr<IConnector> Aspose::Slides::IShapeCollection::InsertConnector(int32_t index, ShapeType shapeType, float x, float y, float width, float height)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | **int32_t** | A nulláralapú index, amelynél be kell illeszteni a csatlakozó alakzatot. |
| shapeType | [ShapeType](../../shapetype/) | A beszúrni kívánt csatlakozó alakzat [ShapeType](../../shapetype/)-ja. |
| x | **float** | A csatlakozó keretének x koordinátája pontban. |
| y | **float** | A csatlakozó keretének y koordinátája pontban. |
| width | **float** | A csatlakozó keretének szélessége pontban. |
| height | **float** | A csatlakozó keretének magassága pontban. |

### Visszatérési érték

Az újonnan létrehozott [IConnector](../../iconnector/).

## IShapeCollection::InsertConnector(int32_t, ShapeType, float, float, float, float, bool) metódus

Új csatlakozó alakzatot hoz létre, és a megadott indexen illeszti be az alakzatgyűjteménybe, opcionálisan az alapértelmezett sablonstílus alkalmazásával.

```cpp
virtual System::SharedPtr<IConnector> Aspose::Slides::IShapeCollection::InsertConnector(int32_t index, ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | **int32_t** | A nulláralapú index, amelynél be kell illeszteni a csatlakozó alakzatot. |
| shapeType | [ShapeType](../../shapetype/) | A beszúrni kívánt csatlakozó alakzat [ShapeType](../../shapetype/)-ja. |
| x | **float** | A csatlakozó keretének x koordinátája pontban. |
| y | **float** | A csatlakozó keretének y koordinátája pontban. |
| width | **float** | A csatlakozó keretének szélessége pontban. |
| height | **float** | A csatlakozó keretének magassága pontban. |
| createFromTemplate | **bool** | Igaz, ha az alapértelmezett sablonstílust (nem üres név, egyszerű stílus) alkalmazni szeretnénk; hamis, ha a csatlakozót az alapértelmezett tulajdonságértékekkel hozunk létre. |

### Visszatérési érték

Az újonnan létrehozott [IConnector](../../iconnector/).

## Lásd még

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IConnector](../../iconnector/)
* Class [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)