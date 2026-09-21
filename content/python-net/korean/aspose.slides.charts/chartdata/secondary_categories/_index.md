---
title: secondary_categories property
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.charts/chartdata/secondary_categories/
weight: 120
---
## secondary_categories 속성
Gets the secondary categories if [`ChartData.use_secondary_categories`](/slides/python-net/ko/aspose.slides.charts/chartdata/use_secondary_categories) property is true.
            읽기 전용 [`IChartCategoryCollection`](/slides/python-net/ko/aspose.slides.charts/ichartcategorycollection).


### 비고

If [`ChartData.use_secondary_categories`](/slides/python-net/ko/aspose.slides.charts/chartdata/use_secondary_categories) property is false then this [`ChartData.secondary_categories`](/slides/python-net/ko/aspose.slides.charts/chartdata/secondary_categories) 
            property return None and data in [`ChartData.categories`](/slides/python-net/ko/aspose.slides.charts/chartdata/categories) property is used both for primary 
            and secondary series.
            If [`ChartData.use_secondary_categories`](/slides/python-net/ko/aspose.slides.charts/chartdata/use_secondary_categories) property is true then data in 
            this [`ChartData.secondary_categories`](/slides/python-net/ko/aspose.slides.charts/chartdata/secondary_categories) property is used for secondary series and data 
            in [`ChartData.categories`](/slides/python-net/ko/aspose.slides.charts/chartdata/categories) property is used for primary series.

### 정의:
```python
@property
def secondary_categories(self):
    ...
```


### 또 보기
* 클래스 [`ChartData`](/slides/python-net/ko/aspose.slides.charts/chartdata)
* 클래스 [`IChartCategoryCollection`](/slides/python-net/ko/aspose.slides.charts/ichartcategorycollection)
* 모듈 [`aspose.slides.charts`](/slides/python-net/ko/aspose.slides.charts)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)