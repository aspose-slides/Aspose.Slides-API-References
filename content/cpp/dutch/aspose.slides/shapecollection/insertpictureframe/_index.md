---
title: InsertPictureFrame()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt een nieuw afbeeldingsframe met de opgegeven afbeelding en voegt het in de vormverzameling in op de opgegeven index.
type: docs
weight: 456
url: /nl/aspose.slides/shapecollection/insertpictureframe/
---
## ShapeCollection::InsertPictureFrame(int32_t, ShapeType, float, float, float, float, System::SharedPtr\<IPPImage\>) method


Maakt een nieuw afbeeldingsframe met de opgegeven afbeelding en voegt het in de vormverzameling in op de opgegeven index.

```cpp
System::SharedPtr<IPictureFrame> Aspose::Slides::ShapeCollection::InsertPictureFrame(int32_t index, ShapeType shapeType, float x, float y, float width, float height, System::SharedPtr<IPPImage> image) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | **int32_t** | De index, beginnend bij nul, waarop het afbeeldingsframe moet worden ingevoegd. |
| shapeType | [ShapeType](../../shapetype/) | Specificeert het vormtype dat zich bevindt in [ShapeType](../../shapetype/), behalve alle soorten lijnen:

[ShapeType::Line](../../shapetype/),

[ShapeType::StraightConnector1](../../shapetype/),

[ShapeType::BentConnector2](../../shapetype/),

[ShapeType::BentConnector3](../../shapetype/),

[ShapeType::BentConnector4](../../shapetype/),

[ShapeType::BentConnector5](../../shapetype/),

[ShapeType::CurvedConnector2](../../shapetype/),

[ShapeType::CurvedConnector3](../../shapetype/),

[ShapeType::CurvedConnector4](../../shapetype/),

[ShapeType::CurvedConnector5](../../shapetype/). |
| x | **float** | De x-coördinaat van het afbeeldingsframe, in punten. |
| y | **float** | De y-coördinaat van het afbeeldingsframe, in punten. |
| width | **float** | De breedte van het afbeeldingsframe, in punten. |
| height | **float** | De hoogte van het afbeeldingsframe, in punten. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | De [IPPImage](../../ippimage/) die moet worden weergegeven in het afbeeldingsframe. |

### Retourwaarde

Het nieuw aangemaakte [IPictureFrame](../../ipictureframe/).

## Zie ook

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPictureFrame](../../ipictureframe/)
* Class [IPPImage](../../ippimage/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)