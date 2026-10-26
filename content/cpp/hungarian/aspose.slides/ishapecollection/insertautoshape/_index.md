---
title: InsertAutoShape()
second_title: Aspose.Slides C++ API-referencia
description: Új automatikus alakzatot hoz létre, és a megadott indexnél beilleszti a alakzatgyűjteménybe, alapértelmezett sablonformázást alkalmazva.
type: docs
weight: 339
url: /hu/aspose.slides/ishapecollection/insertautoshape/
---
## IShapeCollection::InsertAutoShape(int32_t, ShapeType, float, float, float, float) metódus

Új automatikus alakzatot hoz létre, és a megadott indexnél beilleszti a alakzatgyűjteménybe, alapértelmezett sablonformázást alkalmazva.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::IShapeCollection::InsertAutoShape(int32_t index, ShapeType shapeType, float x, float y, float width, float height)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | **int32_t** | A nullától kezdődő index, amelyen az új automatikus alakzatot beillesztik. |
| shapeType | [ShapeType](../../shapetype/) | A beillesztendő automatikus alakzat [ShapeType](../../shapetype/). |
| x | **float** | Az alakzat keretének x-koordinátája pontban. |
| y | **float** | Az alakzat keretének y-koordinátája pontban. |
| width | **float** | Az alakzat keretének szélessége pontban. |
| height | **float** | Az alakzat keretének magassága pontban. |

### Visszatérési érték

Az újonnan létrehozott [IAutoShape](../../iautoshape/).

## IShapeCollection::InsertAutoShape(int32_t, ShapeType, float, float, float, float, bool) metódus

Új automatikus alakzatot hoz létre, és a megadott indexnél beilleszti a alakzatgyűjteménybe, opcionálisan alapértelmezett sablonstílusokkal inicializálva.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::IShapeCollection::InsertAutoShape(int32_t index, ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | **int32_t** | A nullától kezdődő index, amelyen az automatikus alakzatot beillesztik. |
| shapeType | [ShapeType](../../shapetype/) | A beillesztendő automatikus alakzat [ShapeType](../../shapetype/). |
| x | **float** | Az alakzat keretének x-koordinátája pontban. |
| y | **float** | Az alakzat keretének y-koordinátája pontban. |
| width | **float** | Az alakzat keretének szélessége pontban. |
| height | **float** | Az alakzat keretének magassága pontban. |
| createFromTemplate | **bool** | Igaz, ha alapértelmezett sablonstílust alkalmaz (beleértve a nem üres nevet, egyszerű stílust és középre igazított szöveget); hamis, ha az alakzatot minden tulajdonság alapértelmezett értékével hozza létre. |

### Visszatérési érték

Az újonnan létrehozott [IAutoShape](../../iautoshape/).

## Lásd még

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAutoShape](../../iautoshape/)
* Class [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)