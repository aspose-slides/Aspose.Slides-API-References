---
title: series_groups property
second_title: Aspose.Slides cho Python thông qua .NET Tham chiếu API
description: 
type: docs
url: /vi/aspose.slides.charts/ichartdata/series_groups/
weight: 150
---
## Thuộc tính series_groups
Lấy các nhóm của series.
            Chỉ đọc [`IChartSeriesGroupCollection`](/slides/python-net/vi/aspose.slides.charts/ichartseriesgroupcollection).

### Ghi chú

1) Mỗi nhóm của series chứa các series có các kiểu có thể kết hợp được. Các nhóm của 
            kiểu series có thể kết hợp được được định nghĩa và mô tả bằng enum CombinableSeriesTypesGroup 
            .
            Ngoài ra mỗi nhóm của series chứa series được vẽ trên trục chính hoặc trên trục phụ (không cả hai trong cùng một nhóm).
            Vì vậy, nguyên tắc nhóm series là nhóm theo các nhóm kiểu đã nêu ở trên và theo kiểu vẽ trên trục chính/phụ.
            
            2) Nhóm của series chứa một số thuộc tính series mà chung cho 
            mỗi series trong nhóm ("thuộc tính nhóm series").
            "Thuộc tính nhóm series" trong lớp ChartSeriesGroup là đọc/ghi.
            Mỗi "thuộc tính nhóm series" có thể có một chiếu chỉ đọc trong lớp ChartSeries.

### Định nghĩa:
```python
@property
def series_groups(self):
    ...
```

### Xem thêm
* lớp [`IChartData`](/slides/python-net/vi/aspose.slides.charts/ichartdata)
* lớp [`IChartSeriesGroupCollection`](/slides/python-net/vi/aspose.slides.charts/ichartseriesgroupcollection)
* module [`aspose.slides.charts`](/slides/python-net/vi/aspose.slides.charts)
* thư viện [`Aspose.Slides`](/slides/python-net)