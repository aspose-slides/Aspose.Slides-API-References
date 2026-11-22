---
title: refresh_data method
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides.charts/ichartdata/refresh_data/
weight: 30
---
## refresh_data(self) {#}
Làm mới dữ liệu biểu đồ bằng cách tải lại từ workbook nguồn.

```python
def refresh_data(self):
    ...
```

### Ghi chú

Nếu biểu đồ sử dụng một workbook bên ngoài, workbook phải khả dụng tại thời điểm gọi.

### Ngoại lệ

| Ngoại lệ | Mô tả |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Bị ném khi định dạng workbook không được hỗ trợ, hoặc khi [`IChartData.data_source_type`](/slides/python-net/vi/aspose.slides.charts/ichartdata/data_source_type) là<br/>            [`ChartDataSourceType.EXTERNAL_WORKBOOK`](/slides/python-net/vi/aspose.slides.charts/chartdatasourcetype/EXTERNAL_WORKBOOK) và workbook bên ngoài không thể truy cập hoặc tải. |

### Xem thêm
* lớp [`IChartData`](/slides/python-net/vi/aspose.slides.charts/ichartdata)
* mô-đun [`aspose.slides.charts`](/slides/python-net/vi/aspose.slides.charts)
* thư viện [`Aspose.Slides`](/slides/python-net)