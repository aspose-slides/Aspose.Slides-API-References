---
title: AddPictureFrame()
second_title: Aspose.Slides для C++ справочник API
description: Создаёт новый кадр изображения, содержащий указанное изображение, и добавляет его в конец коллекции фигур.
type: docs
weight: 404
url: /ru/aspose.slides/ishapecollection/addpictureframe/
---
## IShapeCollection::AddPictureFrame(ShapeType, float, float, float, float, System::SharedPtr\<IPPImage\>) метод

Создаёт новый кадр изображения, содержащий указанное изображение, и добавляет его в конец коллекции фигур.

```cpp
virtual System::SharedPtr<IPictureFrame> Aspose::Slides::IShapeCollection::AddPictureFrame(ShapeType shapeType, float x, float y, float width, float height, System::SharedPtr<IPPImage> image)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
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
| x | **float** | Координата x кадра изображения, в пунктах. |
| y | **float** | Координата y кадра изображения, в пунктах. |
| width | **float** | Ширина кадра изображения, в пунктах. |
| height | **float** | Высота кадра изображения, в пунктах. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | [IPPImage](../../ippimage/) для отображения в кадре изображения. |

### Возвращаемое значение

Новый созданный [IPictureFrame](../../ipictureframe/).

## См. также

* Перечисление [ShapeType](../../shapetype/)
* Типовое определение [SharedPtr](../../../system/sharedptr/)
* Класс [IPictureFrame](../../ipictureframe/)
* Класс [IPPImage](../../ippimage/)
* Класс [IShapeCollection](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)