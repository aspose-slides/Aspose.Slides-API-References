---
title: insert_summary_zoom_frame method
second_title: Tham chiếu API Aspose.Slides cho Python thông qua .NET
description: 
type: docs
url: /vi/aspose.slides/shapecollection/insert_summary_zoom_frame/
weight: 310
---
## insert_summary_zoom_frame(self, index, x, y, width, height) {#int-float-float-float-float}
Tạo một khung Summary Zoom mới và chèn nó vào bộ sưu tập hình dạng tại vị trí chỉ định.

### Trả về

[`ISummaryZoomFrame`](/slides/python-net/vi/aspose.slides/isummaryzoomframe) mới được tạo.



```python
def insert_summary_zoom_frame(self, index, x, y, width, height):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| index | **int** | Chỉ số bắt đầu từ 0 tại đó sẽ chèn khung Summary Zoom. |
| x | **float** | Tọa độ x của khung Summary Zoom mới, tính bằng điểm. |
| y | **float** | Tọa độ y của khung Summary Zoom mới, tính bằng điểm. |
| width | **float** | Chiều rộng của khung Summary Zoom mới, tính bằng điểm. |
| height | **float** | Chiều cao của khung Summary Zoom mới, tính bằng điểm. |

### Ghi chú

Phương thức này tạo một khung Summary Zoom tổng hợp các liên kết tóm tắt cho mọi phần trong bài thuyết trình.

### Ngoại lệ

| Ngoại lệ | Mô tả |
| :- | :- |
| [`PptxEditException`](/slides/python-net/vi/aspose.slides/pptxeditexception) | Bị ném nếu bài thuyết trình không chứa phần nào, hoặc nếu slide đích không thuộc bất kỳ phần nào. |



### Xem thêm
* lớp [`ISummaryZoomFrame`](/slides/python-net/vi/aspose.slides/isummaryzoomframe)
* lớp [`PptxEditException`](/slides/python-net/vi/aspose.slides/pptxeditexception)
* lớp [`ShapeCollection`](/slides/python-net/vi/aspose.slides/shapecollection)
* module [`aspose.slides`](/slides/python-net/vi/aspose.slides)
* thư viện [`Aspose.Slides`](/slides/python-net)