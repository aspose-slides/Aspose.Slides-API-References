---
title: series_groups property
second_title: Tham khảo API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides.charts/ichartdata/series_groups/
weight: 140
---
## series_groups thuộc tính
Lấy các nhóm của series.
            Chỉ đọc [`IChartSeriesGroupCollection`](/slides/python-net/vi/aspose.slides.charts/ichartseriesgroupcollection).

### Ghi chú

1) Mỗi nhóm của series chứa các series có các loại có thể kết hợp. Các nhóm của
            các loại series có thể kết hợp được định nghĩa và mô tả bằng enum CombinableSeriesTypesGroup.
            Ngoài ra, mỗi nhóm của series chứa các series được vẽ trên trục chính hoặc trên trục phụ (không cả hai trường hợp trong một nhóm).
            Vì vậy, nguyên tắc nhóm series là nhóm theo các nhóm loại đã nêu ở trên và theo loại vẽ chính/phụ.

2) Nhóm của series chứa một số thuộc tính của series mà chung cho
            mỗi series trong nhóm ("series group properties").
            "Series group properties" trong ChartSeriesGroup lớp là đọc/ghi.
            Mỗi "series group properties" có thể có một phép chiếu chỉ đọc trong ChartSeries lớp.

### Định nghĩa:
```python
@property
def series_groups(self):
    ...
```

### Xem thêm
* lớp [`IChartData`](/slides/python-net/vi/aspose.slides.charts/ichartdata)
* lớp [`IChartSeriesGroupCollection`](/slides/python-net/vi/aspose.slides.charts/ichartseriesgroupcollection)
* mô-đun [`aspose.slides.charts`](/slides/python-net/vi/aspose.slides.charts)
* thư viện [`Aspose.Slides`](/slides/python-net)