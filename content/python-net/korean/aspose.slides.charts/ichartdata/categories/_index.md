---
title: categories property
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.charts/ichartdata/categories/
weight: 70
---
## 카테고리 속성
주 카테고리를 가져옵니다 (또는 [`IChartData.use_secondary_categories`](/slides/python-net/ko/aspose.slides.charts/ichartdata/use_secondary_categories) 속성이 false인 경우 기본 카테고리와 보조 카테고리를 모두 가져옵니다).  
읽기 전용 [`IChartCategoryCollection`](/slides/python-net/ko/aspose.slides.charts/ichartcategorycollection).

### 비고

[`IChartData.use_secondary_categories`](/slides/python-net/ko/aspose.slides.charts/ichartdata/use_secondary_categories) 속성이 false인 경우 [`IChartData.secondary_categories`](/slides/python-net/ko/aspose.slides.charts/ichartdata/secondary_categories) 속성은 None을 반환하고 이 [`IChartData.categories`](/slides/python-net/ko/aspose.slides.charts/ichartdata/categories) 속성의 데이터가 기본 및 보조 시리즈 모두에 사용됩니다.  
[`IChartData.use_secondary_categories`](/slides/python-net/ko/aspose.slides.charts/ichartdata/use_secondary_categories) 속성이 true인 경우 [`IChartData.secondary_categories`](/slides/python-net/ko/aspose.slides.charts/ichartdata/secondary_categories) 속성의 데이터는 보조 시리즈에 사용되고, 이 [`IChartData.categories`](/slides/python-net/ko/aspose.slides.charts/ichartdata/categories) 속성의 데이터는 기본 시리즈에 사용됩니다.

### 정의:
```python
@property
def categories(self):
    ...
```

### 참고
* 클래스 [`IChartCategoryCollection`](/slides/python-net/ko/aspose.slides.charts/ichartcategorycollection)
* 클래스 [`IChartData`](/slides/python-net/ko/aspose.slides.charts/ichartdata)
* 모듈 [`aspose.slides.charts`](/slides/python-net/ko/aspose.slides.charts)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)