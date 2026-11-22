---
title: categories property
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.charts/ichartdata/categories/
weight: 80
---
## 카테고리 속성
Gets the primary categories (or both primary and secondary categories 
            if [`IChartData.use_secondary_categories`](/slides/python-net/ko/aspose.slides.charts/ichartdata/use_secondary_categories) property is false).
            읽기 전용 [`IChartCategoryCollection`](/slides/python-net/ko/aspose.slides.charts/ichartcategorycollection).

### 비고

If [`IChartData.use_secondary_categories`](/slides/python-net/ko/aspose.slides.charts/ichartdata/use_secondary_categories) property is false then [`IChartData.secondary_categories`](/slides/python-net/ko/aspose.slides.charts/ichartdata/secondary_categories) 
            property return None and data in this [`IChartData.categories`](/slides/python-net/ko/aspose.slides.charts/ichartdata/categories) property is used both for primary 
            and secondary series.
            If [`IChartData.use_secondary_categories`](/slides/python-net/ko/aspose.slides.charts/ichartdata/use_secondary_categories) property is true then data in [`IChartData.secondary_categories`](/slides/python-net/ko/aspose.slides.charts/ichartdata/secondary_categories) 
            property is used for secondary series and data in this [`IChartData.categories`](/slides/python-net/ko/aspose.slides.charts/ichartdata/categories) property is used 
            for primary series.

### 정의:
```python
@property
def categories(self):
    ...
```

### 또 보기
* 클래스 [`IChartCategoryCollection`](/slides/python-net/ko/aspose.slides.charts/ichartcategorycollection)
* 클래스 [`IChartData`](/slides/python-net/ko/aspose.slides.charts/ichartdata)
* 모듈 [`aspose.slides.charts`](/slides/python-net/ko/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)