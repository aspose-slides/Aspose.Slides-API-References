---
title: AddPictureFrame()
second_title: Aspose.Slides для C++ справочник API
description: Создает новую рамку изображения, содержащую указанное изображение, и добавляет её в конец коллекции фигур.
type: docs
weight: 443
url: /ru/aspose.slides/shapecollection/addpictureframe/
---
## ShapeCollection::AddPictureFrame(ShapeType, float, float, float, float, System::SharedPtr\<IPPImage\>) метод

Создает новую рамку изображения, содержащую указанное изображение, и добавляет её в конец коллекции фигур.

```cpp
System::SharedPtr<IPictureFrame> Aspose::Slides::ShapeCollection::AddPictureFrame(ShapeType shapeType, float x, float y, float width, float height, System::SharedPtr<IPPImage> image) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | Указывает тип фигуры, содержащейся в [ShapeType](../../shapetype/), за исключением всех видов линий:

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
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | Объект [IPPImage](../../ippimage/), отображаемый в рамке изображения. |

### Возвращаемое значение

Новый созданный [IPictureFrame](../../ipictureframe/).

## См. также

* Перечисление [ShapeType](../../shapetype/)
* Типовое определение [SharedPtr](../../../system/sharedptr/)
* Класс [IPictureFrame](../../ipictureframe/)
* Класс [IPPImage](../../ippimage/)
* Класс [ShapeCollection](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)