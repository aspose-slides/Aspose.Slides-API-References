---
title: add method
second_title: Aspose.Slides cho Python qua .NET Tham chiếu API
description: 
type: docs
url: /vi/aspose.slides.charts/ichartcellcollection/add/
weight: 10
---
## add(self, chart_data_cell) {#ichartdatacell}
Thêm ô mới vào bộ sưu tập.


```python
def add(self, chart_data_cell):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| chart_data_cell | [`IChartDataCell`](/slides/python-net/vi/aspose.slides.charts/ichartdatacell) | Ô mới để thêm. |


## add(self, value) {#any}
Tạo [`IChartDataCell`](/slides/python-net/vi/aspose.slides.charts/ichartdatacell) từ giá trị được chỉ định và thêm nó vào bộ sưu tập.


```python
def add(self, value):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| value | **any** | Giá trị. |

### Ghi chú

Phương thức này thêm bảng tính với tên AUTO_DATA và thêm tất cả các giá trị vào đó. Nếu bạn sử dụng [`IChartDataWorkbook`](/slides/python-net/vi/aspose.slides.charts/ichartdataworkbook) để thêm hoặc chỉnh sửa giá trị Cell, hãy chắc chắn rằng bạn không sử dụng bảng tính này
Maximum số lượng các giá trị được thêm bằng phương pháp này không được vượt quá 16711680

### Ngoại lệ

| Ngoại lệ | Mô tả |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | nếu vượt quá giới hạn |



### Xem thêm
* lớp [`IChartCellCollection`](/slides/python-net/vi/aspose.slides.charts/ichartcellcollection)
* lớp [`IChartDataCell`](/slides/python-net/vi/aspose.slides.charts/ichartdatacell)
* lớp [`IChartDataWorkbook`](/slides/python-net/vi/aspose.slides.charts/ichartdataworkbook)
* module [`aspose.slides.charts`](/slides/python-net/vi/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)