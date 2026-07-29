---
title: InsertConnector()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en ny connector shape och infogar den i shape-samlingen på det angivna indexet, med standardmallstil.
type: docs
weight: 391
url: /sv/aspose.slides/ishapecollection/insertconnector/
---
## IShapeCollection::InsertConnector(int32_t, ShapeType, float, float, float, float) metod

Skapar en ny connector shape och infogar den i shape-samlingen på det angivna indexet, med standardmallstil.

```cpp
virtual System::SharedPtr<IConnector> Aspose::Slides::IShapeCollection::InsertConnector(int32_t index, ShapeType shapeType, float x, float y, float width, float height)=0
```

### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Det nollbaserade indexet där connector shape ska infogas. |
| shapeType | [ShapeType](../../shapetype/) | Den [ShapeType](../../shapetype/) för den connector shape som ska infogas. |
| x | **float** | x-koordinaten för connector-formens ram, i punkter. |
| y | **float** | y-koordinaten för connector-formens ram, i punkter. |
| width | **float** | Bredden på connector-formens ram, i punkter. |
| height | **float** | Höjden på connector-formens ram, i punkter. |

### Returvärde

Det nyss skapade [IConnector](../../iconnector/).

## IShapeCollection::InsertConnector(int32_t, ShapeType, float, float, float, float, bool) metod

Skapar en ny connector shape och infogar den i shape-samlingen på det angivna indexet, med möjlighet att tillämpa standardmallstil.

```cpp
virtual System::SharedPtr<IConnector> Aspose::Slides::IShapeCollection::InsertConnector(int32_t index, ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate)=0
```

### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Det nollbaserade indexet där connector shape ska infogas. |
| shapeType | [ShapeType](../../shapetype/) | Den [ShapeType](../../shapetype/) för den connector shape som ska infogas. |
| x | **float** | x-koordinaten för connector-formens ram, i punkter. |
| y | **float** | y-koordinaten för connector-formens ram, i punkter. |
| width | **float** | Bredden på connector-formens ram, i punkter. |
| height | **float** | Höjden på connector-formens ram, i punkter. |
| createFromTemplate | **bool** | True för att tillämpa standardmallstil (icke-tomt namn, enkel stil); false för att skapa connector-formen med standardegenskapsvärden. |

### Returvärde

Det nyss skapade [IConnector](../../iconnector/).

## Se även

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IConnector](../../iconnector/)
* Klass [IShapeCollection](../)
* Namnområde [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)