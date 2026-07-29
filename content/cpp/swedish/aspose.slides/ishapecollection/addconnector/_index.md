---
title: AddConnector()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en ny anslutningsform med standardmallstil och lägger till den i slutet av formsamlingen.
type: docs
weight: 378
url: /sv/aspose.slides/ishapecollection/addconnector/
---
## IShapeCollection::AddConnector(ShapeType, float, float, float, float) metod

Skapar en ny anslutningsform med standardmallstil och lägger till den i slutet av formsamlingen.

```cpp
virtual System::SharedPtr<IConnector> Aspose::Slides::IShapeCollection::AddConnector(ShapeType shapeType, float x, float y, float width, float height)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | Den [ShapeType](../../shapetype/) för den anslutningsform som ska läggas till. |
| x | **float** | x-koordinaten för anslutningens ram, i punkter. |
| y | **float** | y-koordinaten för anslutningens ram, i punkter. |
| width | **float** | Bredden på anslutningens ram, i punkter. |
| height | **float** | Höjden på anslutningens ram, i punkter. |

### Returvärde

Den nyss skapade [IConnector](../../iconnector/).

## IShapeCollection::AddConnector(ShapeType, float, float, float, float, bool) metod

Skapar en ny anslutningsform och lägger till den i slutet av formsamlingen, med möjlighet att tillämpa standardmallstil.

```cpp
virtual System::SharedPtr<IConnector> Aspose::Slides::IShapeCollection::AddConnector(ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | Den [ShapeType](../../shapetype/) för den anslutningsform som ska skapas. |
| x | **float** | x-koordinaten för anslutningens ram, i punkter. |
| y | **float** | y-koordinaten för anslutningens ram, i punkter. |
| width | **float** | Bredden på anslutningens ram, i punkter. |
| height | **float** | Höjden på anslutningens ram, i punkter. |
| createFromTemplate | **bool** | Sant för att tillämpa standardmallstil (icke-tomt namn, enkel stil); falskt för att skapa anslutningen med standardegenskapsvärden. |

### Returvärde

Den nyss skapade [IConnector](../../iconnector/).

## Se även

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IConnector](../../iconnector/)
* Klass [IShapeCollection](../)
* Namnområde [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)