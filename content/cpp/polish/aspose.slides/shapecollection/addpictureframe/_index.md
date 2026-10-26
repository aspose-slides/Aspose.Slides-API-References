---
title: AddPictureFrame()
second_title: Aspose.Slides dla C++ - Dokumentacja API
description: Tworzy nową ramkę obrazu zawierającą określony obraz i dodaje ją na koniec kolekcji kształtów.
type: docs
weight: 443
url: /pl/aspose.slides/shapecollection/addpictureframe/
---
## ShapeCollection::AddPictureFrame(ShapeType, float, float, float, float, System::SharedPtr\<IPPImage\>) metoda

Tworzy nową ramkę obrazu zawierającą określony obraz i dodaje ją na koniec kolekcji kształtów.

```cpp
System::SharedPtr<IPictureFrame> Aspose::Slides::ShapeCollection::AddPictureFrame(ShapeType shapeType, float x, float y, float width, float height, System::SharedPtr<IPPImage> image) override
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | Określa typ kształtu zawarty w [ShapeType](../../shapetype/), z wyjątkiem wszystkich rodzajów linii:

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
| x | **float** | Współrzędna x ramki obrazu, w punktach. |
| y | **float** | Współrzędna y ramki obrazu, w punktach. |
| width | **float** | Szerokość ramki obrazu, w punktach. |
| height | **float** | Wysokość ramki obrazu, w punktach. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | [IPPImage](../../ippimage/) do wyświetlenia w ramce obrazu. |

### Wartość zwracana

Nowo utworzony [IPictureFrame](../../ipictureframe/).

## Zobacz także

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPictureFrame](../../ipictureframe/)
* Class [IPPImage](../../ippimage/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)