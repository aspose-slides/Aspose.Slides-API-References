---
title: InsertPictureFrame()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Tworzy nową ramkę obrazu zawierającą określony obraz i wstawia ją do kolekcji kształtów pod określonym indeksem.
type: docs
weight: 417
url: /pl/aspose.slides/ishapecollection/insertpictureframe/
---
## IShapeCollection::InsertPictureFrame(int32_t, ShapeType, float, float, float, float, System::SharedPtr\<IPPImage\>) metoda


Tworzy nową ramkę obrazu zawierającą określony obraz i wstawia ją do kolekcji kształtów pod określonym indeksem.

```cpp
virtual System::SharedPtr<IPictureFrame> Aspose::Slides::IShapeCollection::InsertPictureFrame(int32_t index, ShapeType shapeType, float x, float y, float width, float height, System::SharedPtr<IPPImage> image)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| index | **int32_t** | Indeks zerowy, pod którym należy wstawić ramkę obrazu. |
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
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | Obiekt [IPPImage](../../ippimage/) wyświetlany w ramce obrazu. |

### Wartość zwracana

Nowo utworzony [IPictureFrame](../../ipictureframe/).

## Zobacz także

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPictureFrame](../../ipictureframe/)
* Class [IPPImage](../../ippimage/)
* Class [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)