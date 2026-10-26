---
title: is_visible property
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.charts/datalabelcollection/is_visible/
weight: 120
---
## is_visible 속성
False는 데이터 레이블이 기본적으로 표시되지 않음을 의미합니다(그리고 DefaultDataLabelFormat 속성의 모든 Show*-flags(ShowValue, ...)가 false입니다). 읽기 전용 **bool**.

### 비고

데이터 레이블이 기본적으로 표시되는 경우 Hide() 메서드를 사용하여 기본적으로 숨길 수 있습니다. 그러나 데이터 레이블이 기본적으로 표시되지 않는 경우(IsVisible가 false) Show*-flags(ShowValue, ...)를 DefaultDataLabelFormat 속성에 true 상태로 설정하여 데이터 레이블을 “기본적으로 표시”하도록 만들 수 있습니다.

### 정의:
```python
@property
def is_visible(self):
    ...
```

### 참고
* 클래스 [`DataLabelCollection`](/slides/python-net/ko/aspose.slides.charts/datalabelcollection)
* 모듈 [`aspose.slides.charts`](/slides/python-net/ko/aspose.slides.charts)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)