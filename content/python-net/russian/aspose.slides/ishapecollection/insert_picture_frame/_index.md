---
title: insert_picture_frame method
second_title: Aspose.Slides для Python через .NET Справочник API
description: 
type: docs
url: /ru/aspose.slides/ishapecollection/insert_picture_frame/
weight: 290
---
## insert_picture_frame(self, index, shape_type, x, y, width, height, image) {#int-shapetype-float-float-float-float-ippimage}
Создает новый фрейм изображения, содержащий указанное изображение, и вставляет его в
            коллекцию фигур по указанному индексу.

### Возвращаемое значение

Созданный [`IPictureFrame`](/slides/python-net/ru/aspose.slides/ipictureframe).



```python
def insert_picture_frame(self, index, shape_type, x, y, width, height, image):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| index | **int** | Нулевой индекс, по которому вставляется фрейм изображения. |
| shape_type | [`ShapeType`](/slides/python-net/ru/aspose.slides/shapetype) | Указывает тип фигуры, содержащейся в [`ShapeType`](/slides/python-net/ru/aspose.slides/shapetype),<br/><br/>            за исключением всех видов линий:<br/><br/><br/><br/><br/><br/>    ShapeType.Line,<br/><br/><br/><br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector5. |
| x | **float** | Координата x фрейма изображения, в пунктах. |
| y | **float** | Координата y фрейма изображения, в пунктах. |
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