---
title: AddPictureFrame()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt een nieuw afbeeldingsframe aan dat de opgegeven afbeelding bevat en voegt het toe aan het einde van de vormverzameling.
type: docs
weight: 443
url: /nl/aspose.slides/shapecollection/addpictureframe/
---
## ShapeCollection::AddPictureFrame(ShapeType, float, float, float, float, System::SharedPtr\<IPPImage\>) methode

Maakt een nieuw afbeeldingsframe aan dat de opgegeven afbeelding bevat en voegt het toe aan het einde van de vormverzameling.

```cpp
System::SharedPtr<IPictureFrame> Aspose::Slides::ShapeCollection::AddPictureFrame(ShapeType shapeType, float x, float y, float width, float height, System::SharedPtr<IPPImage> image) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | Specificeert het vormtype dat zich in [ShapeType](../../shapetype/) bevindt, behalve voor alle soorten lijnen:

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
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | De [IPPImage](../../ippimage/) om weer te geven in het afbeeldingsframe. |

### Returnwaarde

De nieuw aangemaakte [IPictureFrame](../../ipictureframe/).

## Zie ook

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPictureFrame](../../ipictureframe/)
* Class [IPPImage](../../ippimage/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)