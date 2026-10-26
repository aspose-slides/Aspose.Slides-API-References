---
title: InsertAutoShape()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en ny autoform och infogar den i shape-samlingen på det angivna indexet, med standardmallformatering.
type: docs
weight: 378
url: /sv/aspose.slides/shapecollection/insertautoshape/
---
## ShapeCollection::InsertAutoShape(int32_t, ShapeType, float, float, float, float) metod

Skapar en ny autoform och infogar den i shape-samlingen på det angivna indexet, med standardmallformatering.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::ShapeCollection::InsertAutoShape(int32_t index, ShapeType shapeType, float x, float y, float width, float height) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | **int32_t** | Det nollbaserade indexet där den nya autoformen ska infogas. |
| shapeType | [ShapeType](../../shapetype/) | Den [ShapeType](../../shapetype/) för den autoformen som ska infogas. |
| x | **float** | X-koordinaten för formens ram, i punkter. |
| y | **float** | Y-koordinaten för formens ram, i punkter. |
| width | **float** | Bredden på formens ram, i punkter. |
| height | **float** | Höjden på formens ram, i punkter. |

### Returvärde

Den nyss skapade [IAutoShape](../../iautoshape/).

## ShapeCollection::InsertAutoShape(int32_t, ShapeType, float, float, float, float, bool) metod

Skapar en ny autoform och infogar den i shape-samlingen på det angivna indexet, eventuellt med initialisering med standardmallstil.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::ShapeCollection::InsertAutoShape(int32_t index, ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | **int32_t** | Det nollbaserade indexet där autoformen ska infogas. |
| shapeType | [ShapeType](../../shapetype/) | Den [ShapeType](../../shapetype/) för den autoformen som ska infogas. |
| x | **float** | X-koordinaten för formens ram, i punkter. |
| y | **float** | Y-koordinaten för formens ram, i punkter. |
| width | **float** | Bredden på formens ram, i punkter. |
| height | **float** | Höjden på formens ram, i punkter. |
| createFromTemplate | **bool** | Sant för att tillämpa standardmallstil (inklusive ett icke-tomt namn, enkel stil och centrerad text); falskt för att skapa formen med alla egenskaper satta till sina standardvärden. |

### Returvärde

Den nyss skapade [IAutoShape](../../iautoshape/).

## Se även

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IAutoShape](../../iautoshape/)
* Klass [ShapeCollection](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)