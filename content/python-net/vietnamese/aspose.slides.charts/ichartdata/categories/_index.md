---
title: categories property
second_title: Tham chiếu API Aspose.Slides cho Python qua .NET
description: 
type: docs
url: /vi/aspose.slides.charts/ichartdata/categories/
weight: 70
---
## categories thuộc tính
Lấy các danh mục chính (hoặc cả danh mục chính và danh mục phụ nếu [`IChartData.use_secondary_categories`](/slides/python-net/vi/aspose.slides.charts/ichartdata/use_secondary_categories) thuộc tính là false). Chỉ đọc [`IChartCategoryCollection`](/slides/python-net/vi/aspose.slides.charts/ichartcategorycollection).

### Ghi chú

Nếu [`IChartData.use_secondary_categories`](/slides/python-net/vi/aspose.slides.charts/ichartdata/use_secondary_categories) thuộc tính là false thì [`IChartData.secondary_categories`](/slides/python-net/vi/aspose.slides.charts/ichartdata/secondary_categories) thuộc tính trả về None và dữ liệu trong [`IChartData.categories`](/slides/python-net/vi/aspose.slides.charts/ichartdata/categories) thuộc tính được sử dụng cho cả chuỗi chính và chuỗi phụ. Nếu [`IChartData.use_secondary_categories`](/slides/python-net/vi/aspose.slides.charts/ichartdata/use_secondary_categories) thuộc tính là true thì dữ liệu trong [`IChartData.secondary_categories`](/slides/python-net/vi/aspose.slides.charts/ichartdata/secondary_categories) thuộc tính được sử dụng cho chuỗi phụ và dữ liệu trong [`IChartData.categories`](/slides/python-net/vi/aspose.slides.charts/ichartdata/categories) thuộc tính được sử dụng cho chuỗi chính.

### Định nghĩa:
```python
@property
def categories(self):
    ...
```

### Xem thêm
* lớp [`IChartCategoryCollection`](/slides/python-net/vi/aspose.slides.charts/ichartcategorycollection)
* lớp [`IChartData`](/slides/python-net/vi/aspose.slides.charts/ichartdata)
* mô-đun [`aspose.slides.charts`](/slides/python-net/vi/aspose.slides.charts)
* thư viện [`Aspose.Slides`](/slides/python-net)