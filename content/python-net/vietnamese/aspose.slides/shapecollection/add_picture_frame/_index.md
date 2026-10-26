---
title: add_picture_frame method
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides/shapecollection/add_picture_frame/
weight: 110
---
## add_picture_frame(self, shape_type, x, y, width, height, image) {#shapetype-float-float-float-float-ippimage}
Tạo một khung ảnh mới chứa hình ảnh được chỉ định và thêm nó vào cuối bộ sưu tập hình dạng.

### Trả về
Đối tượng [`IPictureFrame`](/slides/python-net/vi/aspose.slides/ipictureframe) mới được tạo.

```python
def add_picture_frame(self, shape_type, x, y, width, height, image):
    ...
```

| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/vi/aspose.slides/shapetype) | Xác định kiểu hình dạng chứa trong [`ShapeType`](/slides/python-net/vi/aspose.slides/shapetype),<br/><br/>            ngoại trừ mọi loại đường:<br/><br/><br/><br/><br/><br/>    ShapeType.Line,<br/><br/><br/><br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector5. |
| x | **float** | Tọa độ x của khung ảnh, tính bằng điểm. |
| y | **float** | Tọa độ y của khung ảnh, tính bằng điểm. |
| width | **float** | Chiều rộng của khung ảnh, tính bằng điểm. |
| height | **float** | Chiều cao của khung ảnh, tính bằng điểm. |
| image | [`IPPImage`](/slides/python-net/vi/aspose.slides/ippimage) | [`IPPImage`](/slides/python-net/vi/aspose.slides/ippimage) để hiển thị trong khung ảnh. |

### Xem thêm
* lớp [`IPictureFrame`](/slides/python-net/vi/aspose.slides/ipictureframe)
* lớp [`IPPImage`](/slides/python-net/vi/aspose.slides/ippimage)
* lớp [`ShapeCollection`](/slides/python-net/vi/aspose.slides/shapecollection)
* enumeration [`ShapeType`](/slides/python-net/vi/aspose.slides/shapetype)
* mô-đun [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)