---
title: insert_picture_frame method
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides/ishapecollection/insert_picture_frame/
weight: 290
---
## insert_picture_frame(self, index, shape_type, x, y, width, height, image) {#int-shapetype-float-float-float-float-ippimage}
Tạo một khung hình mới chứa hình ảnh được chỉ định và chèn nó vào bộ sưu tập hình dạng tại chỉ mục được chỉ định.

### Trả về

Đối tượng mới được tạo [`IPictureFrame`](/slides/python-net/vi/aspose.slides/ipictureframe).

```python
def insert_picture_frame(self, index, shape_type, x, y, width, height, image):
    ...
```

| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| index | **int** | Chỉ mục bắt đầu từ 0 mà tại đó sẽ chèn khung hình. |
| shape_type | [`ShapeType`](/slides/python-net/vi/aspose.slides/shapetype) | Xác định loại hình dạng chứa trong [`ShapeType`](/slides/python-net/vi/aspose.slides/shapetype),<br/><br/>            ngoại trừ mọi loại đường:<br/><br/><br/><br/><br/><br/>    ShapeType.Line,<br/><br/><br/><br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector5. |
| x | **float** | Tọa độ x của khung hình, tính bằng điểm. |
| y | **float** | Tọa độ y của khung hình, tính bằng điểm. |
| width | **float** | Chiều rộng của khung hình, tính bằng điểm. |
| height | **float** | Chiều cao của khung hình, tính bằng điểm. |
| image | [`IPPImage`](/slides/python-net/vi/aspose.slides/ippimage) | Đối tượng [`IPPImage`](/slides/python-net/vi/aspose.slides/ippimage) để hiển thị trong khung hình. |

### Xem thêm
* lớp [`IPictureFrame`](/slides/python-net/vi/aspose.slides/ipictureframe)
* lớp [`IPPImage`](/slides/python-net/vi/aspose.slides/ippimage)
* lớp [`IShapeCollection`](/slides/python-net/vi/aspose.slides/ishapecollection)
* liệt kê [`ShapeType`](/slides/python-net/vi/aspose.slides/shapetype)
* module [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)