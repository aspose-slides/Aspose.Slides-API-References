---
title: InsertConnector()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en ny förbindelseform och lägger in den i formsamlingen på det angivna indexet, med standardmallens stil.
type: docs
weight: 430
url: /sv/aspose.slides/shapecollection/insertconnector/
---
## ShapeCollection::InsertConnector(int32_t, ShapeType, float, float, float, float) metod

Skapar en ny förbindelseform och lägger in den i formsamlingen på det angivna indexet, med standardmallens stil.

```cpp
System::SharedPtr<IConnector> Aspose::Slides::ShapeCollection::InsertConnector(int32_t index, ShapeType shapeType, float x, float y, float width, float height) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | **int32_t** | Det nollbaserade indexet vid vilket förbindelseformen ska infogas. |
| shapeType | [ShapeType](../../shapetype/) | Den [ShapeType](../../shapetype/) för den anslutningsformen som ska infogas. |
| x | **float** | x-koordinaten för anslutningsformens ram, i punkter. |
| y | **float** | y-koordinaten för anslutningsformens ram, i punkter. |
| width | **float** | Bredden på anslutningsformens ram, i punkter. |
| height | **float** | Höjden på anslutningsformens ram, i punkter. |

### Returvärde

Den nyss skapade [IConnector](../../iconnector/).

## ShapeCollection::InsertConnector(int32_t, ShapeType, float, float, float, float, bool) metod

Skapar en ny förbindelseform och lägger in den i formsamlingen på det angivna indexet, med möjlighet att applicera standardmallens stil.

```cpp
System::SharedPtr<IConnector> Aspose::Slides::ShapeCollection::InsertConnector(int32_t index, ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | **int32_t** | Det nollbaserade indexet vid vilket förbindelseformen ska infogas. |
| shapeType | [ShapeType](../../shapetype/) | Den [ShapeType](../../shapetype/) för den anslutningsformen som ska infogas. |
| x | **float** | x-koordinaten för anslutningsformens ram, i punkter. |
| y | **float** | y-koordinaten för anslutningsformens ram, i punkter. |
| width | **float** | Bredden på anslutningsformens ram, i punkter. |
| height | **float** | Höjden på anslutningsformens ram, i punkter. |
| createFromTemplate | **bool** | True för att applicera standardmallens stil (icke-tomt namn, enkel stil); false för att skapa anslutningsformen med standardegenskapsvärden. |

### Returvärde

Den nyss skapade [IConnector](../../iconnector/).

## See Also

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IConnector](../../iconnector/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)