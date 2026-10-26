---
title: add_auto_shape method
second_title: Aspose.Slides cho Python qua .NET API
description: 
type: docs
url: /vi/aspose.slides/ishapecollection/add_auto_shape/
weight: 40
---
## add_auto_shape(self, shape_type, x, y, width, height) {#shapetype-float-float-float-float}
Tạo một auto shape mới với định dạng mặc định và thêm nó vào cuối bộ sưu tập shape.

### Trả về

Đối tượng [`IAutoShape`](/slides/python-net/vi/aspose.slides/iautoshape) mới tạo.



```python
def add_auto_shape(self, shape_type, x, y, width, height):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/vi/aspose.slides/shapetype) | [`ShapeType`](/slides/python-net/vi/aspose.slides/shapetype) của auto shape cần thêm. |
| x | **float** | Tọa độ x của khung shape, tính bằng điểm. |
| y | **float** | Tọa độ y của khung shape, tính bằng điểm. |
| width | **float** | Chiều rộng của khung shape, tính bằng điểm. |
| height | **float** | Chiều cao của khung shape, tính bằng điểm. |


## add_auto_shape(self, shape_type, x, y, width, height, create_from_template) {#shapetype-float-float-float-float-bool}
Tạo một auto shape mới và thêm nó vào cuối bộ sưu tập shape, tùy chọn khởi tạo nó với định dạng mẫu mặc định.

### Trả về

Đối tượng [`IAutoShape`](/slides/python-net/vi/aspose.slides/iautoshape) mới tạo.



```python
def add_auto_shape(self, shape_type, x, y, width, height, create_from_template):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/vi/aspose.slides/shapetype) | [`ShapeType`](/slides/python-net/vi/aspose.slides/shapetype) của auto shape cần thêm. |
| x | **float** | Tọa độ x của khung shape, tính bằng điểm. |
| y | **float** | Tọa độ y của khung shape, tính bằng điểm. |
| width | **float** | Chiều rộng của khung shape, tính bằng điểm. |
| height | **float** | Chiều cao của khung shape, tính bằng điểm. |
| create_from_template | **bool** | True để áp dụng kiểu mẫu mặc định (kiểu đơn giản, văn bản căn giữa và tên không rỗng) cho shape mới; false để tạo shape với tất cả các thuộc tính được đặt giá trị mặc định.<br/><br/>            |
### Xem Thêm
* lớp [`IAutoShape`](/slides/python-net/vi/aspose.slides/iautoshape)
* lớp [`IShapeCollection`](/slides/python-net/vi/aspose.slides/ishapecollection)
* liệt kê [`ShapeType`](/slides/python-net/vi/aspose.slides/shapetype)
* mô-đun [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)