---
title: insert_section_zoom_frame method
second_title: Tham khảo API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides/ishapecollection/insert_section_zoom_frame/
weight: 300
---
## insert_section_zoom_frame(self, index, x, y, width, height, section) {#int-float-float-float-float-isection}
Tạo một khung Section Zoom mới và chèn nó vào bộ sưu tập shape tại
            vị trí chỉ mục đã chỉ định.

### Trả về

Khối [`ISectionZoomFrame`](/slides/python-net/vi/aspose.slides/isectionzoomframe) mới tạo.



```python
def insert_section_zoom_frame(self, index, x, y, width, height, section):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| index | **int** | Chỉ mục bắt đầu từ 0 mà tại đó chèn khung Section Zoom. |
| x | **float** | Tọa độ x của khung Section Zoom mới, tính bằng điểm. |
| y | **float** | Tọa độ y của khung Section Zoom mới, tính bằng điểm. |
| width | **float** | Độ rộng của khung Section Zoom mới, tính bằng điểm. |
| height | **float** | Độ cao của khung Section Zoom mới, tính bằng điểm. |
| section | [`ISection`](/slides/python-net/vi/aspose.slides/isection) | [`ISection`](/slides/python-net/vi/aspose.slides/isection) được tham chiếu bởi khung Section Zoom;<br/><br/>            phải thuộc về bản trình chiếu này và chứa ít nhất một slide. |

### Ngoại lệ

| Ngoại lệ | Mô tả |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Bị ném nếu phần được tham chiếu không thuộc về bản trình chiếu hiện tại hoặc không chứa slide nào. |


## insert_section_zoom_frame(self, index, x, y, width, height, section, image) {#int-float-float-float-float-isection-ippimage}
Tạo một khung Section Zoom mới với hình ảnh được định trước và chèn nó vào bộ sưu tập shape
            tại vị trí chỉ mục đã chỉ định.

### Trả về

Khối [`ISectionZoomFrame`](/slides/python-net/vi/aspose.slides/isectionzoomframe) mới tạo.



```python
def insert_section_zoom_frame(self, index, x, y, width, height, section, image):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| index | **int** | Chỉ mục bắt đầu từ 0 mà tại đó chèn khung Section Zoom. |
| x | **float** | Tọa độ x của khung Section Zoom mới, tính bằng điểm. |
| y | **float** | Tọa độ y của khung Section Zoom mới, tính bằng điểm. |
| width | **float** | Độ rộng của khung Section Zoom mới, tính bằng điểm. |
| height | **float** | Độ cao của khung Section Zoom mới, tính bằng điểm. |
| section | [`ISection`](/slides/python-net/vi/aspose.slides/isection) | [`ISection`](/slides/python-net/vi/aspose.slides/isection) được tham chiếu bởi khung Section Zoom;<br/><br/>            phải thuộc về bản trình chiếu này và chứa ít nhất một slide. |
| image | [`IPPImage`](/slides/python-net/vi/aspose.slides/ippimage) | Hình ảnh hiển thị trong khung Section Zoom. |

### Ngoại lệ

| Ngoại lệ | Mô tả |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Bị ném nếu phần được tham chiếu không thuộc về bản trình chiếu hiện tại hoặc không chứa slide nào. |



### Xem thêm
* lớp [`IPPImage`](/slides/python-net/vi/aspose.slides/ippimage)
* lớp [`ISection`](/slides/python-net/vi/aspose.slides/isection)
* lớp [`ISectionZoomFrame`](/slides/python-net/vi/aspose.slides/isectionzoomframe)
* lớp [`IShapeCollection`](/slides/python-net/vi/aspose.slides/ishapecollection)
* module [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)