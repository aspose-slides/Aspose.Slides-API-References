---
title: InsertPictureFrame()
second_title: Справочник API Aspose.Slides для C++
description: Создает новую рамку изображения, содержащую указанное изображение, и вставляет её в коллекцию фигур по указанному индексу.
type: docs
weight: 456
url: /ru/aspose.slides/shapecollection/insertpictureframe/
---
## ShapeCollection::InsertPictureFrame(int32_t, ShapeType, float, float, float, float, System::SharedPtr\<IPPImage\>) метод

Создает новую рамку изображения, содержащую указанное изображение, и вставляет её в коллекцию фигур по указанному индексу.

```cpp
System::SharedPtr<IPictureFrame> Aspose::Slides::ShapeCollection::InsertPictureFrame(int32_t index, ShapeType shapeType, float x, float y, float width, float height, System::SharedPtr<IPPImage> image) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | **int32_t** | Нулевой индекс, в котором следует вставить рамку изображения. |
| shapeType | [ShapeType](../../shapetype/) | Указывает тип фигуры, содержащийся в [ShapeType](../../shapetype/), за исключением всех видов линий:

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
| x | **float** | Координата x рамки изображения, в пунктах. |
| y | **float** | Координата y рамки изображения, в пунктах. |
| width | **float** | Ширина рамки изображения, в пунктах. |
| height | **float** | Высота рамки изображения, в пунктах. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | [IPPImage](../../ippimage/) для отображения в рамке изображения. |

### Возвращаемое значение

Новое созданное [IPictureFrame](../../ipictureframe/).

## См. также

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPictureFrame](../../ipictureframe/)
* Class [IPPImage](../../ippimage/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)