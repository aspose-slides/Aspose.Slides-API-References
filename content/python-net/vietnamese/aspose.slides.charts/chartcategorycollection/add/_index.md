---
title: add method
second_title: Tham chiếu API Aspose.Slides cho Python thông qua .NET
description: 
type: docs
url: /vi/aspose.slides.charts/chartcategorycollection/add/
weight: 10
---
## add(self, chart_data_cell) {#ichartdatacell}
Nếu danh mục đã tồn tại trong bộ sưu tập, trả về nó. Nếu không, tạo danh mục biểu đồ mới từ [`IChartDataCell`](/slides/python-net/vi/aspose.slides.charts/ichartdatacell) và thêm nó vào bộ sưu tập.

### Giá trị trả về

Danh mục đã thêm hoặc đã tồn tại.

```python
def add(self, chart_data_cell):
    ...
```

| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| chart_data_cell | [`IChartDataCell`](/slides/python-net/vi/aspose.slides.charts/ichartdatacell) | Ô được sử dụng để tạo danh mục biểu đồ. |

## add(self, value) {#any}
Tạo [`ChartCategory`](/slides/python-net/vi/aspose.slides.charts/chartcategory) mới từ giá trị và thêm nó vào bộ sưu tập.

### Giá trị trả về

Đã thêm [`IChartCategory`](/slides/python-net/vi/aspose.slides.charts/ichartcategory).

```python
def add(self, value):
    ...
```

| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| value | **any** | Giá trị. |

### Ghi chú

Phương thức này thêm worksheet có tên AUTO_DATA và đưa tất cả các giá trị vào đó. Nếu bạn sử dụng [`ChartDataWorkbook`](/slides/python-net/vi/aspose.slides.charts/chartdataworkbook) để thêm hoặc chỉnh sửa giá trị ô, hãy chắc chắn rằng bạn không sử dụng worksheet này. Số lượng giá trị tối đa có thể thêm bằng phương thức này không được vượt quá 16711680

### Ngoại lệ

| Ngoại lệ | Mô tả |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | nếu vượt quá giới hạn |

### Xem thêm
* class [`ChartCategory`](/slides/python-net/vi/aspose.slides.charts/chartcategory)
* class [`ChartCategoryCollection`](/slides/python-net/vi/aspose.slides.charts/chartcategorycollection)
* class [`ChartDataWorkbook`](/slides/python-net/vi/aspose.slides.charts/chartdataworkbook)
* class [`IChartCategory`](/slides/python-net/vi/aspose.slides.charts/ichartcategory)
* class [`IChartDataCell`](/slides/python-net/vi/aspose.slides.charts/ichartdatacell)
* module [`aspose.slides.charts`](/slides/python-net/vi/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)