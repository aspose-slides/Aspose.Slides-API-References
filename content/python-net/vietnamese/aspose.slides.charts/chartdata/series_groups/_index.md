---
title: series_groups property
second_title: Aspose.Slides cho Python qua .NET API Reference
description: 
type: docs
url: /vi/aspose.slides.charts/chartdata/series_groups/
weight: 150
---
## series_groups thuộc tính
Lấy các nhóm của chuỗi.
Chỉ đọc [`IChartSeriesGroupCollection`](/slides/python-net/vi/aspose.slides.charts/ichartseriesgroupcollection).

### Ghi chú

1) Mỗi nhóm chuỗi chứa các chuỗi có các kiểu có thể kết hợp. Các nhóm 
            kiểu chuỗi có thể kết hợp được định nghĩa và mô tả bằng enum CombinableSeriesTypesGroup.
            Ngoài ra, mỗi nhóm chuỗi chứa các chuỗi được vẽ trên trục chính hoặc trục phụ (không cả hai trong cùng một nhóm).
            Vì vậy, nguyên tắc nhóm chuỗi là nhóm theo các nhóm kiểu đã đề cập ở trên và theo kiểu vẽ trên trục chính/phụ.

2) Nhóm chuỗi chứa một số thuộc tính chuỗi mà chung cho 
            mỗi chuỗi trong nhóm ("series group properties").
            "Series group properties" trong lớp ChartSeriesGroup là đọc/ghi.
            Mỗi "series group properties" có thể có một phiên bản chỉ đọc trong lớp ChartSeries.

### Định nghĩa:
```python
@property
def series_groups(self):
    ...
```

### Xem thêm
* lớp [`ChartData`](/slides/python-net/vi/aspose.slides.charts/chartdata)
* lớp [`IChartSeriesGroupCollection`](/slides/python-net/vi/aspose.slides.charts/ichartseriesgroupcollection)
* module [`aspose.slides.charts`](/slides/python-net/vi/aspose.slides.charts)
* thư viện [`Aspose.Slides`](/slides/python-net)