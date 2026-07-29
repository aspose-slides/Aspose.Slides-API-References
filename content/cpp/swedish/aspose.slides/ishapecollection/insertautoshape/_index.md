---
title: InsertAutoShape()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en ny automatisk form och infogar den i formsamlingen på det specificerade indexet, med standardmallens formatering.
type: docs
weight: 339
url: /sv/aspose.slides/ishapecollection/insertautoshape/
---
## IShapeCollection::InsertAutoShape(int32_t, ShapeType, float, float, float, float) metod

Skapar en ny automatisk form och infogar den i formsamlingen på det angivna indexet, med standardmallens formatering.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::IShapeCollection::InsertAutoShape(int32_t index, ShapeType shapeType, float x, float y, float width, float height)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | **int32_t** | Det nollbaserade index där den nya automatiska formen ska infogas. |
| shapeType | [ShapeType](../../shapetype/) | Den [ShapeType](../../shapetype/) för den automatiska formen som ska infogas. |
| x | **float** | X-koordinaten för formens ram, i punkter. |
| y | **float** | Y-koordinaten för formens ram, i punkter. |
| width | **float** | Bredden på formens ram, i punkter. |
| height | **float** | Höjden på formens ram, i punkter. |

### Returvärde

Det nyss skapade [IAutoShape](../../iautoshape/).

## IShapeCollection::InsertAutoShape(int32_t, ShapeType, float, float, float, float, bool) metod

Skapar en ny automatisk form och infogar den i formsamlingen på det angivna indexet, och initierar den eventuellt med standardmallens stil.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::IShapeCollection::InsertAutoShape(int32_t index, ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | **int32_t** | Det nollbaserade index där den automatiska formen ska infogas. |
| shapeType | [ShapeType](../../shapetype/) | Den [ShapeType](../../shapetype/) för den automatiska formen som ska infogas. |
| x | **float** | X-koordinaten för formens ram, i punkter. |
| y | **float** | Y-koordinaten för formens ram, i punkter. |
| width | **float** | Bredden på formens ram, i punkter. |
| height | **float** | Höjden på formens ram, i punkter. |
| createFromTemplate | **bool** | Sant för att tillämpa standardmallens stil (inklusive ett icke-tomt namn, enkel stil och centrerad text); falskt för att skapa formen med alla egenskaper satta till sina standardvärden. |

### Returvärde

Det nyss skapade [IAutoShape](../../iautoshape/).

## Se även

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* klass [IAutoShape](../../iautoshape/)
* klass [IShapeCollection](../)
* namnrymd [Aspose::Slides](../../)
* bibliotek [Aspose.Slides](../../../)