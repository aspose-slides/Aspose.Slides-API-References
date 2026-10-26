---
title: insert_auto_shape method
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides/shapecollection/insert_auto_shape/
weight: 230
---
## insert_auto_shape(self, index, shape_type, x, y, width, height) {#int-shapetype-float-float-float-float}
Tạo một auto shape mới và chèn nó vào bộ sưu tập shape tại chỉ số được chỉ định, áp dụng định dạng mẫu mặc định.

### Trả về

Đối tượng [`IAutoShape`](/slides/python-net/vi/aspose.slides/iautoshape) mới được tạo.

```python
def insert_auto_shape(self, index, shape_type, x, y, width, height):
    ...
```

| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| index | **int** | Chỉ số bắt đầu từ 0 để chèn auto shape mới. |
| shape_type | [`ShapeType`](/slides/python-net/vi/aspose.slides/shapetype) | [`ShapeType`](/slides/python-net/vi/aspose.slides/shapetype) của auto shape cần chèn. |
| x | **float** | Tọa độ x của khung shape, tính bằng điểm. |
| y | **float** | Tọa độ y của khung shape, tính bằng điểm. |
| width | **float** | Độ rộng của khung shape, tính bằng điểm. |
| height | **float** | Độ cao của khung shape, tính bằng điểm. |

## insert_auto_shape(self, index, shape_type, x, y, width, height, create_from_template) {#int-shapetype-float-float-float-float-bool}
Tạo một auto shape mới và chèn nó vào bộ sưu tập shape tại chỉ số được chỉ định, tùy chọn khởi tạo nó với định dạng mẫu mặc định.

### Trả về

Đối tượng [`IAutoShape`](/slides/python-net/vi/aspose.slides/iautoshape) mới được tạo.

```python
def insert_auto_shape(self, index, shape_type, x, y, width, height, create_from_template):
    ...
```

| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| index | **int** | Chỉ số bắt đầu từ 0 để chèn auto shape. |
| shape_type | [`ShapeType`](/slides/python-net/vi/aspose.slides/shapetype) | [`ShapeType`](/slides/python-net/vi/aspose.slides/shapetype) của auto shape cần chèn. |
| x | **float** | Tọa độ x của khung shape, tính bằng điểm. |
| y | **float** | Tọa độ y của khung shape, tính bằng điểm. |
| width | **float** | Độ rộng của khung shape, tính bằng điểm. |
| height | **float** | Độ cao của khung shape, tính bằng điểm. |
| create_from_template | **bool** | True để áp dụng định dạng mẫu mặc định (bao gồm tên không rỗng, kiểu đơn giản và văn bản căn giữa); <br/><br/> false để tạo shape với tất cả các thuộc tính được đặt về mặc định. |

### Xem thêm
* lớp [`IAutoShape`](/slides/python-net/vi/aspose.slides/iautoshape)
* lớp [`ShapeCollection`](/slides/python-net/vi/aspose.slides/shapecollection)
* liệt kê [`ShapeType`](/slides/python-net/vi/aspose.slides/shapetype)
* mô-đun [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)