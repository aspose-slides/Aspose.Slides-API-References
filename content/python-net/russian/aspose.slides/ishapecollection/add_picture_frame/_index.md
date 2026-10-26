---
title: add_picture_frame method
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides/ishapecollection/add_picture_frame/
weight: 110
---
## add_picture_frame(self, shape_type, x, y, width, height, image) {#shapetype-float-float-float-float-ippimage}
Создаёт новый фрейм изображения, содержащий указанное изображение, и добавляет его в конец коллекции фигур.

### Возвращаемое значение

Новосозданный [`IPictureFrame`](/slides/python-net/ru/aspose.slides/ipictureframe).



```python
def add_picture_frame(self, shape_type, x, y, width, height, image):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/ru/aspose.slides/shapetype) | Указывает тип фигуры, содержащийся в [`ShapeType`](/slides/python-net/ru/aspose.slides/shapetype), за исключением всех видов линий:<br/><br/>            ShapeType.Line,<br/><br/>            ShapeType.StraightConnector1,<br/><br/>            ShapeType.BentConnector2,<br/><br/>            ShapeType.BentConnector3,<br/><br/>            ShapeType.BentConnector4,<br/><br/>            ShapeType.BentConnector5,<br/><br/>            ShapeType.CurvedConnector2,<br/><br/>            ShapeType.CurvedConnector3,<br/><br/>            ShapeType.CurvedConnector4,<br/><br/>            ShapeType.CurvedConnector5. |
| x | **float** | Координата X фрейма изображения, в пунктах. |
| y | **float** | Координата Y фрейма изображения, в пунктах. |
| width | **float** | Ширина фрейма изображения, в пунктах. |
| height | **float** | Высота фрейма изображения, в пунктах. |
| image | [`IPPImage`](/slides/python-net/ru/aspose.slides/ippimage) | [`IPPImage`](/slides/python-net/ru/aspose.slides/ippimage) для отображения во фрейме изображения. |



### См. также
* класс [`IPictureFrame`](/slides/python-net/ru/aspose.slides/ipictureframe)
* класс [`IPPImage`](/slides/python-net/ru/aspose.slides/ippimage)
* класс [`IShapeCollection`](/slides/python-net/ru/aspose.slides/ishapecollection)
* перечисление [`ShapeType`](/slides/python-net/ru/aspose.slides/shapetype)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)