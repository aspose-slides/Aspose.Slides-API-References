---
title: add_group_shape method
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides/ishapecollection/add_group_shape/
weight: 80
---
## add_group_shape(self) {#}
Tạo một shape nhóm mới trống và thêm nó vào cuối bộ sưu tập shape.  
Khung của nhóm sẽ tự động điều chỉnh để phù hợp với bất kỳ shape nào được thêm vào.

### Trả về

Đối tượng [`IGroupShape`](/slides/python-net/vi/aspose.slides/igroupshape) mới được tạo.

```python
def add_group_shape(self):
    ...
```

## add_group_shape(self, svg_image, x, y, width, height) {#isvgimage-float-float-float-float}
Tạo một shape nhóm mới, chuyển đổi hình ảnh SVG chỉ định thành các shape riêng lẻ,  
và thêm nhóm đã tạo vào cuối bộ sưu tập shape.

### Trả về

Đối tượng [`IGroupShape`](/slides/python-net/vi/aspose.slides/igroupshape) mới được tạo.

```python
def add_group_shape(self, svg_image, x, y, width, height):
    ...
```

| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| svg_image | [`ISvgImage`](/slides/python-net/vi/aspose.slides/isvgimage) | Đối tượng [`ISvgImage`](/slides/python-net/vi/aspose.slides/isvgimage) chứa nội dung vector để chuyển thành các shape. |
| x | **float** | Tọa độ x của khung nhóm, tính bằng điểm. |
| y | **float** | Tọa độ y của khung nhóm, tính bằng điểm. |
| width | **float** | Chiều rộng của khung nhóm, tính bằng điểm. |
| height | **float** | Chiều cao của khung nhóm, tính bằng điểm. |

### Xem Thêm
* lớp [`IGroupShape`](/slides/python-net/vi/aspose.slides/igroupshape)
* lớp [`IShapeCollection`](/slides/python-net/vi/aspose.slides/ishapecollection)
* lớp [`ISvgImage`](/slides/python-net/vi/aspose.slides/isvgimage)
* mô-đun [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)