---
title: categories property
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides.charts/chartdata/categories/
weight: 70
---
## categories thuộc tính
Trả về các danh mục chính (hoặc cả danh mục chính và phụ nếu [`ChartData.use_secondary_categories`](/slides/python-net/vi/aspose.slides.charts/chartdata/use_secondary_categories) thuộc tính là false).
Chỉ đọc [`IChartCategoryCollection`](/slides/python-net/vi/aspose.slides.charts/ichartcategorycollection).

### Ghi chú

Nếu [`ChartData.use_secondary_categories`](/slides/python-net/vi/aspose.slides.charts/chartdata/use_secondary_categories) thuộc tính là false thì [`ChartData.secondary_categories`](/slides/python-net/vi/aspose.slides.charts/chartdata/secondary_categories) thuộc tính trả về None và dữ liệu trong [`ChartData.categories`](/slides/python-net/vi/aspose.slides.charts/chartdata/categories) thuộc tính này được sử dụng cho cả chuỗi chính và phụ. Nếu [`ChartData.use_secondary_categories`](/slides/python-net/vi/aspose.slides.charts/chartdata/use_secondary_categories) thuộc tính là true thì dữ liệu trong [`ChartData.secondary_categories`](/slides/python-net/vi/aspose.slides.charts/chartdata/secondary_categories) thuộc tính được sử dụng cho chuỗi phụ và dữ liệu trong [`ChartData.categories`](/slides/python-net/vi/aspose.slides.charts/chartdata/categories) thuộc tính này được sử dụng cho chuỗi chính.

### Định nghĩa:
```python
@property
def categories(self):
    ...
```

### Xem thêm
* lớp [`ChartData`](/slides/python-net/vi/aspose.slides.charts/chartdata)
* lớp [`IChartCategoryCollection`](/slides/python-net/vi/aspose.slides.charts/ichartcategorycollection)
* module [`aspose.slides.charts`](/slides/python-net/vi/aspose.slides.charts)
* thư viện [`Aspose.Slides`](/slides/python-net)