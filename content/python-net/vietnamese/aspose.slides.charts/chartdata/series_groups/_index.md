---
title: series_groups property
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides.charts/chartdata/series_groups/
weight: 140
---
## series_groups thuộc tính
Lấy các nhóm của series.
Chỉ đọc [`IChartSeriesGroupCollection`](/slides/python-net/vi/aspose.slides.charts/ichartseriesgroupcollection).

### Ghi chú

1) Mỗi nhóm series chứa các series có kiểu có thể kết hợp. Các nhóm kiểu series có thể kết hợp được định nghĩa và mô tả bằng enum CombinableSeriesTypesGroup. Ngoài ra, mỗi nhóm series chứa các series được vẽ trên trục chính hoặc trên trục phụ (không cả hai trường hợp trong một nhóm). Vì vậy, nguyên tắc nhóm series là nhóm theo các nhóm kiểu đã đề cập ở trên và theo kiểu vẽ trục chính/phụ.

2) Nhóm series chứa một số thuộc tính series mà chung cho mỗi series trong nhóm ("series group properties"). "Series group properties" trong lớp ChartSeriesGroup là đọc/ghi. Mỗi "Series group properties" có thể có một phép chiếu chỉ đọc trong lớp ChartSeries.

### Định nghĩa:
```python
@property
def series_groups(self):
    ...
```

### Xem thêm
* lớp [`ChartData`](/slides/python-net/vi/aspose.slides.charts/chartdata)
* lớp [`IChartSeriesGroupCollection`](/slides/python-net/vi/aspose.slides.charts/ichartseriesgroupcollection)
* mô-đun [`aspose.slides.charts`](/slides/python-net/vi/aspose.slides.charts)
* thư viện [`Aspose.Slides`](/slides/python-net)