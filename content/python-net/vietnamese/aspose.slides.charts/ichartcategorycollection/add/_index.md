---
title: add method
second_title: Aspose.Slides cho Python thông qua .NET API Reference
description: 
type: docs
url: /vi/aspose.slides.charts/ichartcategorycollection/add/
weight: 10
---
## add(self, chart_data_cell) {#ichartdatacell}
Nếu danh mục đã tồn tại trong bộ sưu tập, trả về nó. Nếu không, tạo danh mục biểu đồ mới từ [`IChartDataCell`](/slides/python-net/vi/aspose.slides.charts/ichartdatacell) và thêm nó vào bộ sưu tập.

### Trả về

Danh mục đã thêm hoặc đã tồn tại.



```python
def add(self, chart_data_cell):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| chart_data_cell | [`IChartDataCell`](/slides/python-net/vi/aspose.slides.charts/ichartdatacell) | Ô được sử dụng để tạo danh mục biểu đồ. |


## add(self, value) {#any}
Tạo [`IChartCategory`](/slides/python-net/vi/aspose.slides.charts/ichartcategory) mới từ giá trị và thêm nó vào bộ sưu tập.

### Trả về

Đã thêm [`IChartCategory`](/slides/python-net/vi/aspose.slides.charts/ichartcategory).



```python
def add(self, value):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| value | **any** | Giá trị. |

### Ghi chú

Phương pháp này thêm bảng tính với tên AUTO_DATA và thêm tất cả các giá trị vào đó. Nếu bạn sử dụng [`IChartDataWorkbook`](/slides/python-net/vi/aspose.slides.charts/ichartdataworkbook) để thêm hoặc chỉnh sửa giá trị ô, hãy chắc chắn rằng bạn không sử dụng bảng tính này
Số lượng tối đa các giá trị được thêm bằng phương pháp này không được vượt quá 16711680

### Ngoại lệ

| Ngoại lệ | Mô tả |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | nếu vượt quá giới hạn |



### Xem thêm
* lớp [`IChartCategory`](/slides/python-net/vi/aspose.slides.charts/ichartcategory)
* lớp [`IChartCategoryCollection`](/slides/python-net/vi/aspose.slides.charts/ichartcategorycollection)
* lớp [`IChartDataCell`](/slides/python-net/vi/aspose.slides.charts/ichartdatacell)
* lớp [`IChartDataWorkbook`](/slides/python-net/vi/aspose.slides.charts/ichartdataworkbook)
* module [`aspose.slides.charts`](/slides/python-net/vi/aspose.slides.charts)
* thư viện [`Aspose.Slides`](/slides/python-net)