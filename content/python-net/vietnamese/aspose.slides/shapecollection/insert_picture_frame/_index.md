---
title: insert_picture_frame method
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides/shapecollection/insert_picture_frame/
weight: 290
---
## insert_picture_frame(self, index, shape_type, x, y, width, height, image) {#int-shapetype-float-float-float-float-ippimage}
Tạo một khung ảnh mới chứa hình ảnh được chỉ định và chèn nó vào bộ sưu tập hình dạng ở vị trí chỉ mục đã cho.

### Trả về

Đối tượng [`IPictureFrame`](/slides/python-net/vi/aspose.slides/ipictureframe) mới được tạo.

```python
def insert_picture_frame(self, index, shape_type, x, y, width, height, image):
    ...
```

| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| index | **int** | Chỉ mục bắt đầu từ 0, vị trí để chèn khung ảnh. |
| shape_type | [`ShapeType`](/slides/python-net/vi/aspose.slides/shapetype) | Xác định loại hình dạng chứa trong [`ShapeType`](/slides/python-net/vi/aspose.slides/shapetype),<br/><br/>            ngoại trừ tất cả các loại đường:<br/><br/><br/><br/><br/><br/>    ShapeType.Line,<br/><br/><br/><br/><br/><br/>    ShapeType.StraightConnector1,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector2,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector3,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector4,<br/><br/><br/><br/><br/><br/>    ShapeType.BentConnector5,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector2,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector3,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector4,<br/><br/><br/><br/><br/><br/>    ShapeType.CurvedConnector5. |
| x | **float** | Tọa độ x của khung ảnh, tính bằng điểm. |
| y | **float** | Tọa độ y của khung ảnh, tính bằng điểm. |
| width | **float** | Chiều rộng của khung ảnh, tính bằng điểm. |
| height | **float** | Chiều cao của khung ảnh, tính bằng điểm. |
| image | [`IPPImage`](/slides/python-net/vi/aspose.slides/ippimage) | Đối tượng [`IPPImage`](/slides/python-net/vi/aspose.slides/ippimage) để hiển thị trong khung ảnh. |

### Xem thêm
* lớp [`IPictureFrame`](/slides/python-net/vi/aspose.slides/ipictureframe)
* lớp [`IPPImage`](/slides/python-net/vi/aspose.slides/ippimage)
* lớp [`ShapeCollection`](/slides/python-net/vi/aspose.slides/shapecollection)
* enumeration [`ShapeType`](/slides/python-net/vi/aspose.slides/shapetype)
* mô-đun [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)