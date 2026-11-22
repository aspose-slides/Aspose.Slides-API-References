---
title: secondary_categories property
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.charts/chartdata/secondary_categories/
weight: 130
---
## secondary_categories 속성
Gets the secondary categories if [`ChartData.use_secondary_categories`](/slides/python-net/ko/aspose.slides.charts/chartdata/use_secondary_categories) 속성이 true인 경우 보조 카테고리를 가져옵니다.
            읽기 전용 [`IChartCategoryCollection`](/slides/python-net/ko/aspose.slides.charts/ichartcategorycollection).

### 비고
If [`ChartData.use_secondary_categories`](/slides/python-net/ko/aspose.slides.charts/chartdata/use_secondary_categories) 속성이 false인 경우 이 [`ChartData.secondary_categories`](/slides/python-net/ko/aspose.slides.charts/chartdata/secondary_categories) 
            속성은 None을 반환하고 [`ChartData.categories`](/slides/python-net/ko/aspose.slides.charts/chartdata/categories) 속성의 데이터는 기본 및 보조 시리즈 모두에 사용됩니다.
            If [`ChartData.use_secondary_categories`](/slides/python-net/ko/aspose.slides.charts/chartdata/use_secondary_categories) 속성이 true인 경우 데이터는 
            이 [`ChartData.secondary_categories`](/slides/python-net/ko/aspose.slides.charts/chartdata/secondary_categories) 속성에 사용되어 보조 시리즈에 사용되고 [`ChartData.categories`](/slides/python-net/ko/aspose.slides.charts/chartdata/categories) 속성의 데이터는 기본 시리즈에 사용됩니다.

### 정의:
```python
@property
def secondary_categories(self):
    ...
```

### 참조
* 클래스 [`ChartData`](/slides/python-net/ko/aspose.slides.charts/chartdata)
* 클래스 [`IChartCategoryCollection`](/slides/python-net/ko/aspose.slides.charts/ichartcategorycollection)
* 모듈 [`aspose.slides.charts`](/slides/python-net/ko/aspose.slides.charts)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)