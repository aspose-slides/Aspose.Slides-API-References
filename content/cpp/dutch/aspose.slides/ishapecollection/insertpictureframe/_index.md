---
title: InsertPictureFrame()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt een nieuw afbeeldingsframe dat de opgegeven afbeelding bevat en voegt het toe aan de shape collection op de opgegeven index.
type: docs
weight: 417
url: /nl/aspose.slides/ishapecollection/insertpictureframe/
---
## IShapeCollection::InsertPictureFrame(int32_t, ShapeType, float, float, float, float, System::SharedPtr\<IPPImage\>) methode


Maakt een nieuw afbeeldingsframe dat de opgegeven afbeelding bevat en voegt het toe aan de shape collection op de opgegeven index.

```cpp
virtual System::SharedPtr<IPictureFrame> Aspose::Slides::IShapeCollection::InsertPictureFrame(int32_t index, ShapeType shapeType, float x, float y, float width, float height, System::SharedPtr<IPPImage> image)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | **int32_t** | De nulgebaseerde index waarop het afbeeldingsframe moet worden ingevoegd. |
| shapeType | [ShapeType](../../shapetype/) | Specificeert het shape type dat zit in [ShapeType](../../shapetype/), behalve voor alle soorten lijnen:

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
| x | **float** | De x-coördinaat van het afbeeldingsframe, in points. |
| y | **float** | De y-coördinaat van het afbeeldingsframe, in points. |
| width | **float** | De breedte van het afbeeldingsframe, in points. |
| height | **float** | De hoogte van het afbeeldingsframe, in points. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | De [IPPImage](../../ippimage/) om weer te geven in het afbeeldingsframe. |

### Retourwaarde

De nieuw aangemaakte [IPictureFrame](../../ipictureframe/).

## Zie ook

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IPictureFrame](../../ipictureframe/)
* Klasse [IPPImage](../../ippimage/)
* Klasse [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)