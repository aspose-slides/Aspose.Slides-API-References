---
title: insert_auto_shape method
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides/ishapecollection/insert_auto_shape/
weight: 230
---
## insert_auto_shape(self, index, shape_type, x, y, width, height) {#int-shapetype-float-float-float-float}
Tạo một hình tự động mới và chèn nó vào bộ sưu tập hình tại chỉ mục được chỉ định, áp dụng định dạng mẫu mặc định.

### Giá trị trả về

Đối tượng [`IAutoShape`](/slides/python-net/vi/aspose.slides/iautoshape) mới được tạo.

```python
def insert_auto_shape(self, index, shape_type, x, y, width, height):
    ...
```

| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| index | **int** | Chỉ mục không bắt đầu từ 0 để chèn hình tự động mới. |
| shape_type | [`ShapeType`](/slides/python-net/vi/aspose.slides/shapetype) | [`ShapeType`](/slides/python-net/vi/aspose.slides/shapetype) của hình tự động cần chèn. |
| x | **float** | Tọa độ x của khung hình, tính bằng điểm. |
| y | **float** | Tọa độ y của khung hình, tính bằng điểm. |
| width | **float** | Độ rộng của khung hình, tính bằng điểm. |
| height | **float** | Độ cao của khung hình, tính bằng điểm. |


## insert_auto_shape(self, index, shape_type, x, y, width, height, create_from_template) {#int-shapetype-float-float-float-float-bool}
Tạo một hình tự động mới và chèn nó vào bộ sưu tập hình tại chỉ mục được chỉ định, tùy chọn khởi tạo nó với kiểu mẫu mặc định.

### Giá trị trả về

Đối tượng [`IAutoShape`](/slides/python-net/vi/aspose.slides/iautoshape) mới được tạo.

```python
def insert_auto_shape(self, index, shape_type, x, y, width, height, create_from_template):
    ...
```

| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| index | **int** | Chỉ mục không bắt đầu từ 0 để chèn hình tự động. |
| shape_type | [`ShapeType`](/slides/python-net/vi/aspose.slides/shapetype) | [`ShapeType`](/slides/python-net/vi/aspose.slides/shapetype) của hình tự động cần chèn. |
| x | **float** | Tọa độ x của khung hình, tính bằng điểm. |
| y | **float** | Tọa độ y của khung hình, tính bằng điểm. |
| width | **float** | Độ rộng của khung hình, tính bằng điểm. |
| height | **float** | Độ cao của khung hình, tính bằng điểm. |
| create_from_template | **bool** | True để áp dụng kiểu mẫu mặc định (bao gồm tên không rỗng, kiểu đơn giản và văn bản căn giữa); <br/><br/>false để tạo hình với tất cả các thuộc tính được đặt về mặc định. |



### Xem thêm
* lớp [`IAutoShape`](/slides/python-net/vi/aspose.slides/iautoshape)
* lớp [`IShapeCollection`](/slides/python-net/vi/aspose.slides/ishapecollection)
* liệt kê [`ShapeType`](/slides/python-net/vi/aspose.slides/shapetype)
* mô-đun [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)