---
title: AddPictureFrame()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt een nieuw afbeeldingsframe dat de opgegeven afbeelding bevat en voegt het toe aan het einde van de vormverzameling.
type: docs
weight: 404
url: /nl/aspose.slides/ishapecollection/addpictureframe/
---
## IShapeCollection::AddPictureFrame(ShapeType, float, float, float, float, System::SharedPtr\<IPPImage\>) methode

Maakt een nieuw afbeeldingsframe dat de opgegeven afbeelding bevat en voegt het toe aan het einde van de vormcollectie.

```cpp
virtual System::SharedPtr<IPictureFrame> Aspose::Slides::IShapeCollection::AddPictureFrame(ShapeType shapeType, float x, float y, float width, float height, System::SharedPtr<IPPImage> image)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | Specificeert het vormtype dat in [ShapeType](../../shapetype/) zit, behalve alle soorten lijnen:

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
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | De [IPPImage](../../ippimage/) die in het afbeeldingsframe moet worden weergegeven. |

### Retourwaarde

Het nieuw gemaakte [IPictureFrame](../../ipictureframe/).

## Zie ook

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IPictureFrame](../../ipictureframe/)
* Klasse [IPPImage](../../ippimage/)
* Klasse [IShapeCollection](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)