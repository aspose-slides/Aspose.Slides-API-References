---
title: insert_ole_object_frame method
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides/ishapecollection/insert_ole_object_frame/
weight: 280
---
## insert_ole_object_frame(self, index, x, y, width, height, data_info) {#int-float-float-float-float-ioleembeddeddatainfo}
Tạo một khung đối tượng OLE mới và chèn nó vào bộ sưu tập hình tại chỉ số đã chỉ định.

### Trả về

Đối tượng mới tạo [`IOleObjectFrame`](/slides/python-net/vi/aspose.slides/ioleobjectframe).



```python
def insert_ole_object_frame(self, index, x, y, width, height, data_info):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| index | **int** | Chỉ số bắt đầu từ 0 nơi chèn khung đối tượng OLE. |
| x | **float** | Tọa độ x của khung OLE mới, tính bằng điểm. |
| y | **float** | Tọa độ y của khung OLE mới, tính bằng điểm. |
| width | **float** | Chiều rộng của khung OLE mới, tính bằng điểm. |
| height | **float** | Chiều cao của khung OLE mới, tính bằng điểm. |
| data_info | [`IOleEmbeddedDataInfo`](/slides/python-net/vi/aspose.slides/ioleembeddeddatainfo) | Thông tin dữ liệu OLE được nhúng ([`IOleEmbeddedDataInfo`](/slides/python-net/vi/aspose.slides/ioleembeddeddatainfo)). |


## insert_ole_object_frame(self, index, x, y, width, height, class_name, path) {#int-float-float-float-float-str-str}
Tạo một khung đối tượng OLE mới và chèn nó vào bộ sưu tập hình tại chỉ số đã chỉ định.

### Trả về

Đối tượng mới tạo [`IOleObjectFrame`](/slides/python-net/vi/aspose.slides/ioleobjectframe).



```python
def insert_ole_object_frame(self, index, x, y, width, height, class_name, path):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| index | **int** | Chỉ số bắt đầu từ 0 nơi chèn khung đối tượng OLE. |
| x | **float** | Tọa độ x của khung OLE mới, tính bằng điểm. |
| y | **float** | Tọa độ y của khung OLE mới, tính bằng điểm. |
| width | **float** | Chiều rộng của khung OLE mới, tính bằng điểm. |
| height | **float** | Chiều cao của khung OLE mới, tính bằng điểm. |
| class_name | **str** | Tên lớp của đối tượng OLE. |
| path | **str** | Đường dẫn tới tập tin được liên kết. <br/><br/>Đường dẫn này được lưu nguyên trong bản trình chiếu.<br/><br/>Nếu chỉ định đường dẫn tương đối, tập tin sẽ không thể truy cập được khi mở bản trình chiếu từ thư mục khác. |



### Xem Thêm
* lớp [`IOleEmbeddedDataInfo`](/slides/python-net/vi/aspose.slides/ioleembeddeddatainfo)
* lớp [`IOleObjectFrame`](/slides/python-net/vi/aspose.slides/ioleobjectframe)
* lớp [`IShapeCollection`](/slides/python-net/vi/aspose.slides/ishapecollection)
* mô-đun [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)