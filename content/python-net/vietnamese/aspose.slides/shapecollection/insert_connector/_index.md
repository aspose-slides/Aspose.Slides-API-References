---
title: insert_connector method
second_title: Tham chiếu API Aspose.Slides cho Python thông qua .NET
description: 
type: docs
url: /vi/aspose.slides/shapecollection/insert_connector/
weight: 260
---
## insert_connector(self, index, shape_type, x, y, width, height) {#int-shapetype-float-float-float-float}
Tạo một hình connector mới và chèn nó vào bộ sưu tập hình tại chỉ mục được chỉ định,
            áp dụng kiểu mẫu mặc định.

### Trả về

[`IConnector`](/slides/python-net/vi/aspose.slides/iconnector).



```python
def insert_connector(self, index, shape_type, x, y, width, height):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| index | **int** | Chỉ mục bắt đầu từ 0 tại vị trí cần chèn hình connector. |
| shape_type | [`ShapeType`](/slides/python-net/vi/aspose.slides/shapetype) | [`ShapeType`](/slides/python-net/vi/aspose.slides/shapetype) của hình connector cần chèn. |
| x | **float** | Tọa độ x của khung connector, tính bằng điểm. |
| y | **float** | Tọa độ y của khung connector, tính bằng điểm. |
| width | **float** | Chiều rộng của khung connector, tính bằng điểm. |
| height | **float** | Chiều cao của khung connector, tính bằng điểm. |


## insert_connector(self, index, shape_type, x, y, width, height, create_from_template) {#int-shapetype-float-float-float-float-bool}
Tạo một hình connector mới và chèn nó vào bộ sưu tập hình tại chỉ mục được chỉ định,
            tùy chọn áp dụng kiểu mẫu mặc định.

### Trả về

[`IConnector`](/slides/python-net/vi/aspose.slides/iconnector).



```python
def insert_connector(self, index, shape_type, x, y, width, height, create_from_template):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| index | **int** | Chỉ mục bắt đầu từ 0 tại vị trí cần chèn hình connector. |
| shape_type | [`ShapeType`](/slides/python-net/vi/aspose.slides/shapetype) | [`ShapeType`](/slides/python-net/vi/aspose.slides/shapetype) của hình connector cần chèn. |
| x | **float** | Tọa độ x của khung connector, tính bằng điểm. |
| y | **float** | Tọa độ y của khung connector, tính bằng điểm. |
| width | **float** | Chiều rộng của khung connector, tính bằng điểm. |
| height | **float** | Chiều cao của khung connector, tính bằng điểm. |
| create_from_template | **bool** | True để áp dụng kiểu mẫu mặc định (tên không rỗng, kiểu đơn giản);<br/><br/>            false để tạo connector với các giá trị thuộc tính mặc định. |



### Xem thêm
* lớp [`IConnector`](/slides/python-net/vi/aspose.slides/iconnector)
* lớp [`ShapeCollection`](/slides/python-net/vi/aspose.slides/shapecollection)
* liệt kê [`ShapeType`](/slides/python-net/vi/aspose.slides/shapetype)
* mô-đun [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)