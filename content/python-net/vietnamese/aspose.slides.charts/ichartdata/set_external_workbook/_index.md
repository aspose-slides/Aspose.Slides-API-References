---
title: set_external_workbook method
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides.charts/ichartdata/set_external_workbook/
weight: 40
---
## set_external_workbook(self, workbook_path) {#str}
Đặt sổ làm việc bên ngoài làm nguồn dữ liệu cho biểu đồ. Dữ liệu biểu đồ sẽ được cập nhật từ sổ làm việc đích.


```python
def set_external_workbook(self, workbook_path):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| workbook_path | **str** | Đường dẫn tới sổ làm việc đích |

### Ngoại lệ

| Ngoại lệ | Mô tả |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | External workbook is not available or can't be loaded. |


## set_external_workbook(self, workbook_path, update_chart_data) {#str-bool}
Đặt sổ làm việc bên ngoài làm nguồn dữ liệu cho biểu đồ.


```python
def set_external_workbook(self, workbook_path, update_chart_data):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| workbook_path | **str** | Đường dẫn tới sổ làm việc đích |
| update_chart_data | **bool** | Nếu giá trị là false, chỉ đường dẫn sổ làm việc sẽ được cập nhật. <br/><br/> Dữ liệu biểu đồ sẽ không được tải và cập nhật từ sổ làm việc đích. Có thể được sử dụng khi sổ làm việc đích không tồn tại hoặc không khả dụng.<br/><br/> Nếu giá trị là true, dữ liệu biểu đồ sẽ được cập nhật từ sổ làm việc đích. |

### Ngoại lệ

| Ngoại lệ | Mô tả |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | External workbook is not available or can't be loaded. |



### Xem thêm
* lớp [`IChartData`](/slides/python-net/vi/aspose.slides.charts/ichartdata)
* mô-đun [`aspose.slides.charts`](/slides/python-net/vi/aspose.slides.charts)
* thư viện [`Aspose.Slides`](/slides/python-net)