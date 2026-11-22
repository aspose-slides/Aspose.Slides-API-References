---
title: refresh_data method
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides.charts/chartdata/refresh_data/
weight: 30
---
## refresh_data(self) {#}
Làm mới dữ liệu biểu đồ bằng cách tải lại từ sách tính nguồn.

```python
def refresh_data(self):
    ...
```

### Ghi chú

Nếu biểu đồ sử dụng một sách tính bên ngoài, sách tính phải có thể truy cập được vào thời điểm gọi.

### Ngoại lệ

| Ngoại lệ | Mô tả |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Bị ném khi định dạng sách tính không được hỗ trợ, hoặc khi [`ChartData.data_source_type`](/slides/python-net/vi/aspose.slides.charts/chartdata/data_source_type) là<br/>            [`ChartDataSourceType.EXTERNAL_WORKBOOK`](/slides/python-net/vi/aspose.slides.charts/chartdatasourcetype/EXTERNAL_WORKBOOK) và sách tính bên ngoài không thể truy cập hoặc tải lên. |

### Xem thêm
* lớp [`ChartData`](/slides/python-net/vi/aspose.slides.charts/chartdata)
* mô-đun [`aspose.slides.charts`](/slides/python-net/vi/aspose.slides.charts)
* thư viện [`Aspose.Slides`](/slides/python-net)