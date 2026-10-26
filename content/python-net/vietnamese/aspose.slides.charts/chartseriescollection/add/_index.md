---
title: add method
second_title: Aspose.Slides cho Python qua .NET Tham chiếu API
description: 
type: docs
url: /vi/aspose.slides.charts/chartseriescollection/add/
weight: 10
---
## add(self, type) {#charttype}
Tạo chuỗi biểu đồ mới và thêm nó vào bộ sưu tập.

### Trả về

Chuỗi biểu đồ mới.



```python
def add(self, type):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/vi/aspose.slides.charts/charttype) | Loại chuỗi |


## add(self, cell_with_series_name, type) {#ichartdatacell-charttype}
Tạo chuỗi biểu đồ mới từ [`ChartDataCell`](/slides/python-net/vi/aspose.slides.charts/chartdatacell) và thêm nó vào bộ sưu tập.

### Trả về

Chuỗi biểu đồ đã thêm hoặc chuỗi đã có trong bộ sưu tập.



```python
def add(self, cell_with_series_name, type):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| cell_with_series_name | [`IChartDataCell`](/slides/python-net/vi/aspose.slides.charts/ichartdatacell) | Ô chứa tên chuỗi. |
| type | [`ChartType`](/slides/python-net/vi/aspose.slides.charts/charttype) | Loại được đặt cho chuỗi |

### Ghi chú

Nếu chuỗi biểu đồ được tạo từ cùng một ô đã có trong bộ sưu tập thì phương thức không thêm gì và trả về chỉ số của nó.


## add(self, cells_with_series_name, type) {#ichartcellcollection-charttype}
Tạo chuỗi biểu đồ mới từ [`ChartCellCollection`](/slides/python-net/vi/aspose.slides.charts/chartcellcollection) và thêm nó vào bộ sưu tập.

### Trả về

Chuỗi biểu đồ đã thêm hoặc chuỗi đã có trong bộ sưu tập.



```python
def add(self, cells_with_series_name, type):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| cells_with_series_name | [`IChartCellCollection`](/slides/python-net/vi/aspose.slides.charts/ichartcellcollection) | Các ô chứa tên chuỗi. |
| type | [`ChartType`](/slides/python-net/vi/aspose.slides.charts/charttype) | Loại được đặt cho chuỗi |

### Ghi chú

Nếu chuỗi biểu đồ được tạo từ cùng một ô đã có trong bộ sưu tập thì phương thức không thêm gì và trả về chỉ số của nó.


## add(self, name, type) {#str-charttype}
Tạo chuỗi biểu đồ mới từ giá trị và thêm nó vào bộ sưu tập.

### Trả về

Chuỗi biểu đồ đã thêm.



```python
def add(self, name, type):
    ...
```


| Tham số | Kiểu | Mô tả |
| :- | :- | :- |
| name | **str** | Tên chuỗi. |
| type | [`ChartType`](/slides/python-net/vi/aspose.slides.charts/charttype) | Loại được đặt cho chuỗi |



### Xem thêm
* lớp [`ChartCellCollection`](/slides/python-net/vi/aspose.slides.charts/chartcellcollection)
* lớp [`ChartDataCell`](/slides/python-net/vi/aspose.slides.charts/chartdatacell)
* lớp [`ChartSeriesCollection`](/slides/python-net/vi/aspose.slides.charts/chartseriescollection)
* liệt kê [`ChartType`](/slides/python-net/vi/aspose.slides.charts/charttype)
* lớp [`IChartCellCollection`](/slides/python-net/vi/aspose.slides.charts/ichartcellcollection)
* lớp [`IChartDataCell`](/slides/python-net/vi/aspose.slides.charts/ichartdatacell)
* lớp [`IChartSeries`](/slides/python-net/vi/aspose.slides.charts/ichartseries)
* mô-đun [`aspose.slides.charts`](/slides/python-net/vi/aspose.slides.charts)
* thư viện [`Aspose.Slides`](/slides/python-net)