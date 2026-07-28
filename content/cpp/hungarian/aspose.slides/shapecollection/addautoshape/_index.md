---
title: AddAutoShape()
second_title: Aspose.Slides C++ API Referencia
description: Új automata alakzatot hoz létre alapértelmezett formázással, és a alakzatgyűjtemény végéhez adja hozzá.
type: docs
weight: 352
url: /hu/aspose.slides/shapecollection/addautoshape/
---
## ShapeCollection::AddAutoShape(ShapeType, float, float, float, float) metódus

Új automata alakzatot hoz létre alapértelmezett formázással, és a alakzatgyűjtemény végéhez adja hozzá.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::ShapeCollection::AddAutoShape(ShapeType shapeType, float x, float y, float width, float height) override
```

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | A hozzáadandó automata alakzat [ShapeType](../../shapetype/)-ja. |
| x | **float** | Az alakzat keretének x-koordinátája pontokban. |
| y | **float** | Az alakzat keretének y-koordinátája pontokban. |
| width | **float** | Az alakzat keretének szélessége pontokban. |
| height | **float** | Az alakzat keretének magassága pontokban. |

### Visszatérési érték

Az újonnan létrehozott [IAutoShape](../../iautoshape/).

## ShapeCollection::AddAutoShape(ShapeType, float, float, float, float, bool) metódus

Új automata alakzatot hoz létre, és a alakzatgyűjtemény végéhez adja hozzá, opcionálisan alapértelmezett sablonformázással inicializálva.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::ShapeCollection::AddAutoShape(ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate) override
```

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | A hozzáadandó automata alakzat [ShapeType](../../shapetype/)-ja. |
| x | **float** | Az alakzat keretének x-koordinátája pontokban. |
| y | **float** | Az alakzat keretének y-koordinátája pontokban. |
| width | **float** | Az alakzat keretének szélessége pontokban. |
| height | **float** | Az alakzat keretének magassága pontokban. |
| createFromTemplate | **bool** | True, ha az alapértelmezett sablonstílust (egyszerű stílus, középre igazított szöveg, és nem üres név) alkalmazza az új alakzatra; false, ha a alakzat minden tulajdonságát az alapértelmezett értékekre állítja. |

### Visszatérési érték

Az újonnan létrehozott [IAutoShape](../../iautoshape/).

## Lásd még

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IAutoShape](../../iautoshape/)
* Osztály [ShapeCollection](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)