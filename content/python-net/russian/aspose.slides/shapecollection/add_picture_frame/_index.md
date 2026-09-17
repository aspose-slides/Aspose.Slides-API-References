---
title: add_picture_frame method
second_title: Aspose.Slides для Python через .NET API Reference
description: 
type: docs
url: /ru/aspose.slides/shapecollection/add_picture_frame/
weight: 110
---
## add_picture_frame(self, shape_type, x, y, width, height, image) {#shapetype-float-float-float-float-ippimage}
Создает новый кадр изображения, содержащий указанное изображение, и добавляет его в конец
            коллекции фигур.

### Возвращаемое значение

Новосозданный [`IPictureFrame`](/slides/python-net/ru/aspose.slides/ipictureframe).



```python
def add_picture_frame(self, shape_type, x, y, width, height, image):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/ru/aspose.slides/shapetype) | Указывает тип фигуры, содержащийся в [`ShapeType`](/slides/python-net/ru/aspose.slides/shapetype),<br/><br/>            за исключением всех видов линий:<br/><br/><br/><br/><br/><br/>    ShapeType.Line,<br/><br/><br/><br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector5. |
| x | **float** | Координата x кадра изображения, в пунктах. |
| y | **float** | Координата y кадра изображения, в пунктах. |
| width | **float** | Ширина кадра изображения, в пунктах. |
| height | **float** | Высота кадра изображения, в пунктах. |
| image | [`IPPImage`](/slides/python-net/ru/aspose.slides/ippimage) | Объект [`IPPImage`](/slides/python-net/ru/aspose.slides/ippimage), который будет отображаться в кадре изображения. |



### См. также
* класс [`IPictureFrame`](/slides/python-net/ru/aspose.slides/ipictureframe)
* класс [`IPPImage`](/slides/python-net/ru/aspose.slides/ippimage)
* класс [`ShapeCollection`](/slides/python-net/ru/aspose.slides/shapecollection)
* перечисление [`ShapeType`](/slides/python-net/ru/aspose.slides/shapetype)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)