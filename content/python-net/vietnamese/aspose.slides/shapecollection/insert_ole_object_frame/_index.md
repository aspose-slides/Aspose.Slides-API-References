---
title: insert_ole_object_frame method
second_title: Tham chiếu API Aspose.Slides cho Python thông qua .NET
description: 
type: docs
url: /vi/aspose.slides/shapecollection/insert_ole_object_frame/
weight: 280
---
## insert_ole_object_frame(self, index, x, y, width, height, data_info) {#int-float-float-float-float-ioleembeddeddatainfo}
Tạo một khung đối tượng OLE mới và chèn nó vào bộ sưu tập shape tại chỉ mục được chỉ định.

### Trả về

Đối tượng [`IOleObjectFrame`](/slides/python-net/vi/aspose.slides/ioleobjectframe) mới được tạo.



```python
def insert_ole_object_frame(self, index, x, y, width, height, data_info):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| index | **int** | Chỉ mục bắt đầu từ 0, nơi sẽ chèn khung đối tượng OLE. |
| x | **float** | Tọa độ x của khung OLE mới, tính bằng điểm. |
| y | **float** | Tọa độ y của khung OLE mới, tính bằng điểm. |
| width | **float** | Chiều rộng của khung OLE mới, tính bằng điểm. |
| height | **float** | Chiều cao của khung OLE mới, tính bằng điểm. |
| data_info | [`IOleEmbeddedDataInfo`](/slides/python-net/vi/aspose.slides/ioleembeddeddatainfo) | Thông tin dữ liệu OLE nhúng ([`IOleEmbeddedDataInfo`](/slides/python-net/vi/aspose.slides/ioleembeddeddatainfo)). |


## insert_ole_object_frame(self, index, x, y, width, height, class_name, path) {#int-float-float-float-float-str-str}
Tạo một khung đối tượng OLE mới và chèn nó vào bộ sưu tập shape tại chỉ mục được chỉ định.

### Trả về

Khung đối tượng OLE mới được tạo.



```python
def insert_ole_object_frame(self, index, x, y, width, height, class_name, path):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| index | **int** | Chỉ mục bắt đầu từ 0, nơi sẽ chèn khung đối tượng OLE. |
| x | **float** | Tọa độ x của khung OLE mới, tính bằng điểm. |
| y | **float** | Tọa độ y của khung OLE mới, tính bằng điểm. |
| width | **float** | Chiều rộng của khung OLE mới, tính bằng điểm. |
| height | **float** | Chiều cao của khung OLE mới, tính bằng điểm. |
| class_name | **str** | Tên lớp của đối tượng OLE. |
| path | **str** | Đường dẫn tới tệp được liên kết.<br/><br/>Đường dẫn này được lưu nguyên trong bài thuyết trình.<br/><br/>Nếu đường dẫn tương đối được chỉ định, tệp sẽ không thể truy cập khi mở<br/><br/>bài thuyết trình từ một thư mục khác. |



### Xem thêm
* lớp [`IOleEmbeddedDataInfo`](/slides/python-net/vi/aspose.slides/ioleembeddeddatainfo)
* lớp [`IOleObjectFrame`](/slides/python-net/vi/aspose.slides/ioleobjectframe)
* lớp [`ShapeCollection`](/slides/python-net/vi/aspose.slides/shapecollection)
* mô-đun [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)