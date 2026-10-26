---
title: insert_connector method
second_title: Tham khảo API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides/ishapecollection/insert_connector/
weight: 260
---
## insert_connector(self, index, shape_type, x, y, width, height) {#int-shapetype-float-float-float-float}
Tạo một hình kết nối mới và chèn nó vào bộ sưu tập hình tại chỉ mục được chỉ định,
            áp dụng kiểu mẫu mặc định.

### Trả về

Đối tượng [`IConnector`](/slides/python-net/vi/aspose.slides/iconnector) mới tạo.



```python
def insert_connector(self, index, shape_type, x, y, width, height):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| index | **int** | Chỉ mục bắt đầu từ 0 tại vị trí sẽ chèn hình kết nối. |
| shape_type | [`ShapeType`](/slides/python-net/vi/aspose.slides/shapetype) | [`ShapeType`](/slides/python-net/vi/aspose.slides/shapetype) của hình kết nối sẽ chèn. |
| x | **float** | Tọa độ x của khung hình kết nối, tính bằng điểm. |
| y | **float** | Tọa độ y của khung hình kết nối, tính bằng điểm. |
| width | **float** | Chiều rộng của khung hình kết nối, tính bằng điểm. |
| height | **float** | Chiều cao của khung hình kết nối, tính bằng điểm. |


## insert_connector(self, index, shape_type, x, y, width, height, create_from_template) {#int-shapetype-float-float-float-float-bool}
Tạo một hình kết nối mới và chèn nó vào bộ sưu tập hình tại chỉ mục được chỉ định,
            tùy chọn áp dụng kiểu mẫu mặc định.

### Trả về

Đối tượng [`IConnector`](/slides/python-net/vi/aspose.slides/iconnector) mới tạo.



```python
def insert_connector(self, index, shape_type, x, y, width, height, create_from_template):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| index | **int** | Chỉ mục bắt đầu từ 0 tại vị trí sẽ chèn hình kết nối. |
| shape_type | [`ShapeType`](/slides/python-net/vi/aspose.slides/shapetype) | [`ShapeType`](/slides/python-net/vi/aspose.slides/shapetype) của hình kết nối sẽ chèn. |
| x | **float** | Tọa độ x của khung hình kết nối, tính bằng điểm. |
| y | **float** | Tọa độ y của khung hình kết nối, tính bằng điểm. |
| width | **float** | Chiều rộng của khung hình kết nối, tính bằng điểm. |
| height | **float** | Chiều cao của khung hình kết nối, tính bằng điểm. |
| create_from_template | **bool** | True để áp dụng kiểu mẫu mặc định (tên không rỗng, kiểu đơn giản);<br/><br/>            false để tạo kết nối với các giá trị thuộc tính mặc định. |



### Xem thêm
* lớp [`IConnector`](/slides/python-net/vi/aspose.slides/iconnector)
* lớp [`IShapeCollection`](/slides/python-net/vi/aspose.slides/ishapecollection)
* enumeration [`ShapeType`](/slides/python-net/vi/aspose.slides/shapetype)
* module [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)