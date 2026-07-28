---
title: AddAutoShape()
second_title: Aspose.Slides for C++ API Referenciája
description: Új automatikus alakzatot hoz létre alapértelmezett formázással, és hozzáadja az alakzatgyűjtemény végéhez.
type: docs
weight: 313
url: /hu/aspose.slides/ishapecollection/addautoshape/
---
## IShapeCollection::AddAutoShape(ShapeType, float, float, float, float) metódus

Új automatikus alakzatot hoz létre alapértelmezett formázással, és hozzáadja az alakzatgyűjtemény végéhez.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::IShapeCollection::AddAutoShape(ShapeType shapeType, float x, float y, float width, float height)=0
```

### Arguments

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | A hozzáadandó automatikus alakzat [ShapeType](../../shapetype/). |
| x | **float** | Az alakzat keretének x-koordinátája pontban. |
| y | **float** | Az alakzat keretének y-koordinátája pontban. |
| width | **float** | Az alakzat keretének szélessége pontban. |
| height | **float** | Az alakzat keretének magassága pontban. |

### Return Value

Az újonnan létrehozott [IAutoShape](../../iautoshape/).

## IShapeCollection::AddAutoShape(ShapeType, float, float, float, float, bool) metódus

Új automatikus alakzatot hoz létre, és hozzáadja az alakzatgyűjtemény végéhez, opcionálisan alapértelmezett sablonformázással inicializálva.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::IShapeCollection::AddAutoShape(ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate)=0
```

### Arguments

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | A hozzáadandó automatikus alakzat [ShapeType](../../shapetype/). |
| x | **float** | Az alakzat keretének x-koordinátája pontban. |
| y | **float** | Az alakzat keretének y-koordinátája pontban. |
| width | **float** | Az alakzat keretének szélessége pontban. |
| height | **float** | Az alakzat keretének magassága pontban. |
| createFromTemplate | **bool** | True, ha alapértelmezett sablonstílust (egyszerű stílus, középre igazított szöveg és nem üres név) alkalmaz a új alakzatra; false, ha az alakzatot minden tulajdonság alapértelmezett értékével hozza létre. |

### Return Value

Az újonnan létrehozott [IAutoShape](../../iautoshape/).

## Lásd még

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IAutoShape](../../iautoshape/)
* Osztály [IShapeCollection](../)
* Névtere [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)