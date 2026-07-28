---
title: InsertAutoShape()
second_title: Aspose.Slides C++ API referencia
description: Létrehoz egy új automatikus alakzatot, és a megadott indexnél beilleszti a alakzatgyűjteménybe, alkalmazva az alapértelmezett sablonformázást.
type: docs
weight: 378
url: /hu/aspose.slides/shapecollection/insertautoshape/
---
## ShapeCollection::InsertAutoShape(int32_t, ShapeType, float, float, float, float) metódus

Létrehoz egy új automatikus alakzatot, és beilleszti azt a alakzatgyűjteménybe a megadott indexnél, alkalmazva az alapértelmezett sablonformázást.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::ShapeCollection::InsertAutoShape(int32_t index, ShapeType shapeType, float x, float y, float width, float height) override
```

### Arguments

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | **int32_t** | A null-alapú index, ahol az új automatikus alakzatot be kell illeszteni. |
| shapeType | [ShapeType](../../shapetype/) | A beillesztendő automatikus alakzat [ShapeType](../../shapetype/). |
| x | **float** | Az alakzat keretének x-koordinátája pontban. |
| y | **float** | Az alakzat keretének y-koordinátája pontban. |
| width | **float** | Az alakzat keretének szélessége pontban. |
| height | **float** | Az alakzat keretének magassága pontban. |

### Return Value

Az újonnan létrehozott [IAutoShape](../../iautoshape/).

## ShapeCollection::InsertAutoShape(int32_t, ShapeType, float, float, float, float, bool) metódus

Létrehoz egy új automatikus alakzatot, és beilleszti azt a alakzatgyűjteménybe a megadott indexnél, opcionálisan alapértelmezett sablonstílussal inicializálva.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::ShapeCollection::InsertAutoShape(int32_t index, ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate) override
```

### Arguments

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | **int32_t** | A null-alapú index, ahol az automatikus alakzatot be kell illeszteni. |
| shapeType | [ShapeType](../../shapetype/) | A beillesztendő automatikus alakzat [ShapeType](../../shapetype/). |
| x | **float** | Az alakzat keretének x-koordinátája pontban. |
| y | **float** | Az alakzat keretének y-koordinátája pontban. |
| width | **float** | Az alakzat keretének szélessége pontban. |
| height | **float** | Az alakzat keretének magassága pontban. |
| createFromTemplate | **bool** | Igaz, ha az alapértelmezett sablonstílus alkalmazandó (beleértve egy nem üres nevet, egyszerű stílust és középre igazított szöveget); hamis, ha az alakzat minden tulajdonsága az alapértelmezett értékekkel jön létre. |

### Return Value

Az újonnan létrehozott [IAutoShape](../../iautoshape/).

## Lásd még

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IAutoShape](../../iautoshape/)
* Osztály [ShapeCollection](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)