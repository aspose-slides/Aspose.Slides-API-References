---
title: InsertPictureFrame()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Tworzy nową ramkę obrazu zawierającą określony obraz i wstawia ją do kolekcji kształtów podanym indeksem.
type: docs
weight: 456
url: /pl/aspose.slides/shapecollection/insertpictureframe/
---
## ShapeCollection::InsertPictureFrame(int32_t, ShapeType, float, float, float, float, System::SharedPtr\<IPPImage\>) metoda

Tworzy nową ramkę obrazu zawierającą określony obraz i wstawia ją do kolekcji kształtów podanym indeksie.

```cpp
System::SharedPtr<IPictureFrame> Aspose::Slides::ShapeCollection::InsertPictureFrame(int32_t index, ShapeType shapeType, float x, float y, float width, float height, System::SharedPtr<IPPImage> image) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| index | **int32_t** | Indeks zerowy, pod którym ma zostać wstawiona ramka obrazu. |
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