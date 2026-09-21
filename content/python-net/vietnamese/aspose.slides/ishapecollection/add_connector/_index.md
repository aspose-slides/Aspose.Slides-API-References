---
title: add_connector method
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides/ishapecollection/add_connector/
weight: 70
---
## add_connector(self, shape_type, x, y, width, height) {#shapetype-float-float-float-float}
Tạo một hình connector mới với kiểu mẫu mặc định và thêm nó vào cuối bộ sưu tập hình dạng.

### Trả về

Đối tượng [`IConnector`](/slides/python-net/vi/aspose.slides/iconnector) mới được tạo.

```python
def add_connector(self, shape_type, x, y, width, height):
    ...
```

| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/vi/aspose.slides/shapetype) | [`ShapeType`](/slides/python-net/vi/aspose.slides/shapetype) của hình connector để thêm. |
| x | **float** | Tọa độ x của khung connector, tính bằng điểm. |
| y | **float** | Tọa độ y của khung connector, tính bằng điểm. |
| width | **float** | Độ rộng của khung connector, tính bằng điểm. |
| height | **float** | Độ cao của khung connector, tính bằng điểm. |

## add_connector(self, shape_type, x, y, width, height, create_from_template) {#shapetype-float-float-float-float-bool}
Tạo một hình connector mới và thêm nó vào cuối bộ sưu tập hình dạng, tùy chọn áp dụng kiểu mẫu mặc định.

### Trả về

Đối tượng [`IConnector`](/slides/python-net/vi/aspose.slides/iconnector) mới được tạo.

```python
def add_connector(self, shape_type, x, y, width, height, create_from_template):
    ...
```

| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| shape_type | [`ShapeType`](/slides/python-net/vi/aspose.slides/shapetype) | [`ShapeType`](/slides/python-net/vi/aspose.slides/shapetype) của hình connector để tạo. |
| x | **float** | Tọa độ x của khung connector, tính bằng điểm. |
| y | **float** | Tọa độ y của khung connector, tính bằng điểm. |
| width | **float** | Độ rộng của khung connector, tính bằng điểm. |
| height | **float** | Độ cao của khung connector, tính bằng điểm. |
| create_from_template | **bool** | True để áp dụng kiểu mẫu mặc định (tên không rỗng, kiểu đơn giản); <br/><br/>false để tạo connector với các giá trị thuộc tính mặc định. |

### Xem thêm
* lớp [`IConnector`](/slides/python-net/vi/aspose.slides/iconnector)
* lớp [`IShapeCollection`](/slides/python-net/vi/aspose.slides/ishapecollection)
* liệt kê [`ShapeType`](/slides/python-net/vi/aspose.slides/shapetype)
* mô-đun [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)