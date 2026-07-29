---
title: AddAutoShape()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en ny autoshape med standardformatering och lägger till den i slutet av shape-samlingen.
type: docs
weight: 352
url: /sv/aspose.slides/shapecollection/addautoshape/
---
## ShapeCollection::AddAutoShape(ShapeType, float, float, float, float) method

Skapar en ny autoshape med standardformatering och lägger till den i slutet av shape-samlingen.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::ShapeCollection::AddAutoShape(ShapeType shapeType, float x, float y, float width, float height) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | Den [ShapeType](../../shapetype/) för den autoshape som ska läggas till. |
| x | **float** | x-koordinaten för shape\\u2019s ram, i punkter. |
| y | **float** | y-koordinaten för shape\\u2019s ram, i punkter. |
| width | **float** | bredden på shape\\u2019s ram, i punkter. |
| height | **float** | höjden på shape\\u2019s ram, i punkter. |

### Returvärde

Den nyss skapade [IAutoShape](../../iautoshape/).

## ShapeCollection::AddAutoShape(ShapeType, float, float, float, float, bool) method

Skapar en ny autoshape och lägger till den i slutet av shape-samlingen, med möjlighet att initiera den med standardmall-formatering.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::ShapeCollection::AddAutoShape(ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | Den [ShapeType](../../shapetype/) för den autoshape som ska läggas till. |
| x | **float** | x-koordinaten för shape\\u2019s ram, i punkter. |
| y | **float** | y-koordinaten för shape\\u2019s ram, i punkter. |
| width | **float** | bredden på shape\\u2019s ram, i punkter. |
| height | **float** | höjden på shape\\u2019s ram, i punkter. |
| createFromTemplate | **bool** | Sant för att tillämpa standardmall-formatering (enkel stil, centrerad text och icke-tomt namn) på den nya shape; falskt för att skapa shape med alla egenskaper satta till sina standardvärden. |

### Returvärde

Den nyss skapade [IAutoShape](../../iautoshape/).

## Se även

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IAutoShape](../../iautoshape/)
* Klass [ShapeCollection](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)