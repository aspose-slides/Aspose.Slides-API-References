---
title: InsertPictureFrame()
second_title: Справка API Aspose.Slides для C++
description: Создаёт новую рамку изображения, содержащую указанное изображение, и вставляет её в коллекцию фигур по указанному индексу.
type: docs
weight: 417
url: /ru/aspose.slides/ishapecollection/insertpictureframe/
---
## IShapeCollection::InsertPictureFrame(int32_t, ShapeType, float, float, float, float, System::SharedPtr\<IPPImage\>) метод

Создаёт новую рамку изображения, содержащую указанное изображение, и вставляет её в коллекцию фигур по указанному индексу.

```cpp
virtual System::SharedPtr<IPictureFrame> Aspose::Slides::IShapeCollection::InsertPictureFrame(int32_t index, ShapeType shapeType, float x, float y, float width, float height, System::SharedPtr<IPPImage> image)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | **int32_t** | Нулевой индекс, по которому вставляется рамка изображения. |
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

Новосозданный [IPictureFrame](../../ipictureframe/).

## См. также

* Перечисление [ShapeType](../../shapetype/)
* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [IPictureFrame](../../ipictureframe/)
* Класс [IPPImage](../../ippimage/)
* Класс [IShapeCollection](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)