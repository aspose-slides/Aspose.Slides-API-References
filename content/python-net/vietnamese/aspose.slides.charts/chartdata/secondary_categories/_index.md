---
title: secondary_categories property
second_title: Tham khảo API Aspose.Slides cho Python thông qua .NET
description: 
type: docs
url: /vi/aspose.slides.charts/chartdata/secondary_categories/
weight: 130
---
## secondary_categories thuộc tính
Lấy các danh mục phụ nếu [`ChartData.use_secondary_categories`](/slides/python-net/vi/aspose.slides.charts/chartdata/use_secondary_categories) thuộc tính là true.
            Chỉ đọc [`IChartCategoryCollection`](/slides/python-net/vi/aspose.slides.charts/ichartcategorycollection).

### Ghi chú

Nếu [`ChartData.use_secondary_categories`](/slides/python-net/vi/aspose.slides.charts/chartdata/use_secondary_categories) thuộc tính là false thì [`ChartData.secondary_categories`](/slides/python-net/vi/aspose.slides.charts/chartdata/secondary_categories) thuộc tính 
            thuộc tính trả về None và dữ liệu trong [`ChartData.categories`](/slides/python-net/vi/aspose.slides.charts/chartdata/categories) thuộc tính được dùng cho cả chuỗi chính 
            và chuỗi phụ.
            Nếu [`ChartData.use_secondary_categories`](/slides/python-net/vi/aspose.slides.charts/chartdata/use_secondary_categories) thuộc tính là true thì dữ liệu trong 
            [`ChartData.secondary_categories`](/slides/python-net/vi/aspose.slides.charts/chartdata/secondary_categories) thuộc tính được dùng cho chuỗi phụ và dữ liệu 
            trong [`ChartData.categories`](/slides/python-net/vi/aspose.slides.charts/chartdata/categories) thuộc tính được dùng cho chuỗi chính.

### Định nghĩa:
```python
@property
def secondary_categories(self):
    ...
```

### Xem thêm
* lớp [`ChartData`](/slides/python-net/vi/aspose.slides.charts/chartdata)
* lớp [`IChartCategoryCollection`](/slides/python-net/vi/aspose.slides.charts/ichartcategorycollection)
* mô-đun [`aspose.slides.charts`](/slides/python-net/vi/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)