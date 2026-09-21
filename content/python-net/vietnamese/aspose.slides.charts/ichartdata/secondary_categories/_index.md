---
title: secondary_categories property
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides.charts/ichartdata/secondary_categories/
weight: 120
---
## secondary_categories thuộc tính
Gets the secondary categories if [`IChartData.use_secondary_categories`](/slides/python-net/vi/aspose.slides.charts/ichartdata/use_secondary_categories) thuộc tính is true.
            Read-only [`IChartCategoryCollection`](/slides/python-net/vi/aspose.slides.charts/ichartcategorycollection).

### Ghi chú

If [`IChartData.use_secondary_categories`](/slides/python-net/vi/aspose.slides.charts/ichartdata/use_secondary_categories) thuộc tính is false then this [`IChartData.secondary_categories`](/slides/python-net/vi/aspose.slides.charts/ichartdata/secondary_categories) 
            thuộc tính return None and data in [`IChartData.categories`](/slides/python-net/vi/aspose.slides.charts/ichartdata/categories) thuộc tính is used both for primary 
            and secondary series.
            If [`IChartData.use_secondary_categories`](/slides/python-net/vi/aspose.slides.charts/ichartdata/use_secondary_categories) thuộc tính is true then data in 
            this [`IChartData.secondary_categories`](/slides/python-net/vi/aspose.slides.charts/ichartdata/secondary_categories) thuộc tính is used for secondary series and data 
            in [`IChartData.categories`](/slides/python-net/vi/aspose.slides.charts/ichartdata/categories) thuộc tính is used for primary series.

### Định nghĩa:
```python
@property
def secondary_categories(self):
    ...
```

### Xem thêm
* lớp [`IChartCategoryCollection`](/slides/python-net/vi/aspose.slides.charts/ichartcategorycollection)
* lớp [`IChartData`](/slides/python-net/vi/aspose.slides.charts/ichartdata)
* module [`aspose.slides.charts`](/slides/python-net/vi/aspose.slides.charts)
* thư viện [`Aspose.Slides`](/slides/python-net)