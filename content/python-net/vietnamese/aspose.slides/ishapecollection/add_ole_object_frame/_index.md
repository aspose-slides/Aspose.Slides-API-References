---
title: add_ole_object_frame method
second_title: Tham chiếu API Aspose.Slides cho Python thông qua .NET
description: 
type: docs
url: /vi/aspose.slides/ishapecollection/add_ole_object_frame/
weight: 100
---
## add_ole_object_frame(self, x, y, width, height, data_info) {#float-float-float-float-ioleembeddeddatainfo}
Tạo một khung đối tượng OLE mới và thêm nó vào cuối bộ sưu tập hình dạng.

### Returns

Đối tượng mới tạo [`IOleObjectFrame`](/slides/python-net/vi/aspose.slides/ioleobjectframe).



```python
def add_ole_object_frame(self, x, y, width, height, data_info):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| x | **float** | Tọa độ x của khung OLE mới, tính bằng điểm. |
| y | **float** | Tọa độ y của khung OLE mới, tính bằng điểm. |
| width | **float** | Chiều rộng của khung OLE mới, tính bằng điểm. |
| height | **float** | Chiều cao của khung OLE mới, tính bằng điểm. |
| data_info | [`IOleEmbeddedDataInfo`](/slides/python-net/vi/aspose.slides/ioleembeddeddatainfo) | Thông tin dữ liệu OLE được nhúng ([`IOleEmbeddedDataInfo`](/slides/python-net/vi/aspose.slides/ioleembeddeddatainfo)). |


## add_ole_object_frame(self, x, y, width, height, class_name, path) {#float-float-float-float-str-str}
Tạo một khung đối tượng OLE mới và thêm nó vào cuối bộ sưu tập hình dạng.

### Returns

Đối tượng mới tạo [`IOleObjectFrame`](/slides/python-net/vi/aspose.slides/ioleobjectframe).



```python
def add_ole_object_frame(self, x, y, width, height, class_name, path):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| x | **float** | Tọa độ x của khung OLE mới, tính bằng điểm. |
| y | **float** | Tọa độ y của khung OLE mới, tính bằng điểm. |
| width | **float** | Chiều rộng của khung OLE mới, tính bằng điểm. |
| height | **float** | Chiều cao của khung OLE mới, tính bằng điểm. |
| class_name | **str** | Tên lớp của đối tượng OLE. |
| path | **str** | Đường dẫn tới tệp được liên kết. <br/><br/>Đường dẫn này được lưu nguyên như trong bản trình chiếu.<br/><br/>Nếu đường dẫn tương đối được chỉ định, tệp sẽ không thể truy cập được khi mở<br/><br/>bản trình chiếu từ một thư mục khác. |



### See Also
* lớp [`IOleEmbeddedDataInfo`](/slides/python-net/vi/aspose.slides/ioleembeddeddatainfo)
* lớp [`IOleObjectFrame`](/slides/python-net/vi/aspose.slides/ioleobjectframe)
* lớp [`IShapeCollection`](/slides/python-net/vi/aspose.slides/ishapecollection)
* mô-đun [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)