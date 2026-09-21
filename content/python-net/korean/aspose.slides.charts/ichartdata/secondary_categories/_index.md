---
title: secondary_categories property
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.charts/ichartdata/secondary_categories/
weight: 120
---
## secondary_categories 속성
[`IChartData.use_secondary_categories`](/slides/python-net/ko/aspose.slides.charts/ichartdata/use_secondary_categories) 속성이 true인 경우 보조 카테고리를 가져옵니다.
            읽기 전용 [`IChartCategoryCollection`](/slides/python-net/ko/aspose.slides.charts/ichartcategorycollection).


### 비고

만약 [`IChartData.use_secondary_categories`](/slides/python-net/ko/aspose.slides.charts/ichartdata/use_secondary_categories) 속성이 false인 경우 이 [`IChartData.secondary_categories`](/slides/python-net/ko/aspose.slides.charts/ichartdata/secondary_categories) 
            속성은 None을 반환하고 [`IChartData.categories`](/slides/python-net/ko/aspose.slides.charts/ichartdata/categories) 속성의 데이터는 주 및 보조 시리즈 모두에 사용됩니다.
            만약 [`IChartData.use_secondary_categories`](/slides/python-net/ko/aspose.slides.charts/ichartdata/use_secondary_categories) 속성이 true인 경우 데이터는 
            이 [`IChartData.secondary_categories`](/slides/python-net/ko/aspose.slides.charts/ichartdata/secondary_categories) 속성은 보조 시리즈에 사용되고 [`IChartData.categories`](/slides/python-net/ko/aspose.slides.charts/ichartdata/categories) 속성의 데이터는 주 시리즈에 사용됩니다.

### 정의:
```python
@property
def secondary_categories(self):
    ...
```


### 참조
* 클래스 [`IChartCategoryCollection`](/slides/python-net/ko/aspose.slides.charts/ichartcategorycollection)
* 클래스 [`IChartData`](/slides/python-net/ko/aspose.slides.charts/ichartdata)
* 모듈 [`aspose.slides.charts`](/slides/python-net/ko/aspose.slides.charts)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)