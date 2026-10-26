---
title: insert_picture_frame method
second_title: Aspose.Slides для Python через .NET – справочник API
description: 
type: docs
url: /ru/aspose.slides/shapecollection/insert_picture_frame/
weight: 290
---
## insert_picture_frame(self, index, shape_type, x, y, width, height, image) {#int-shapetype-float-float-float-float-ippimage}
Создает новую рамку изображения, содержащую указанный образ, и вставляет её в коллекцию фигур по указанному индексу.

### Возвращаемое значение

Созданный [`IPictureFrame`](/slides/python-net/ru/aspose.slides/ipictureframe).

```python
def insert_picture_frame(self, index, shape_type, x, y, width, height, image):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| index | **int** | Нулевой индекс, по которому вставляется рамка изображения. |
| shape_type | [`ShapeType`](/slides/python-net/ru/aspose.slides/shapetype) | Указывает тип фигуры, содержащийся в [`ShapeType`](/slides/python-net/ru/aspose.slides/shapetype),<br/><br/>            за исключением всех видов линий:<br/><br/><br/><br/><br/><br/>    ShapeType.Line,<br/><br/><br/><br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector5. |
| x | **float** | Координата x рамки изображения в пунктах. |
| y | **float** | Координата y рамки изображения в пунктах. |
| width | **float** | Ширина рамки изображения в пунктах. |
| height | **float** | Высота рамки изображения в пунктах. |
| image | [`IPPImage`](/slides/python-net/ru/aspose.slides/ippimage) | [`IPPImage`](/slides/python-net/ru/aspose.slides/ippimage) для отображения в рамке изображения. |

### См. также
* класс [`IPictureFrame`](/slides/python-net/ru/aspose.slides/ipictureframe)
* класс [`IPPImage`](/slides/python-net/ru/aspose.slides/ippimage)
* класс [`ShapeCollection`](/slides/python-net/ru/aspose.slides/shapecollection)
* перечисление [`ShapeType`](/slides/python-net/ru/aspose.slides/shapetype)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)