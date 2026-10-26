---
title: show_percentage property
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.charts/datalabelformat/show_percentage/
weight: 180
---
## show_percentage 속성
지정된 차트의 데이터 레이블 백분율 값 표시 동작을 나타냅니다. 
            True는 백분율 값을 표시합니다. False는 숨깁니다. 
            읽기/쓰기 **bool**.

### 비고

이 DataLabelFormat 객체의 상위가 데이터 레이블의 DataLabelCollection 컬렉션인 경우, 이 속성은 DataLabelCollection 컬렉션의 새로운 데이터 레이블에 대한 ShowPercentage 속성의 기본값을 가져오거나 설정합니다. 
            이 속성을 값으로 설정하면 DataLabelCollection 컬렉션의 모든 데이터 레이블에 대한 ShowPercentage 속성에도 동일한 값이 설정됩니다 (예: "DataLabels.DefaultDataLabelFormat.ShowPercentage = val;"는 모든 DataLabels[i].ShowPercentage가 val와 동일하게 됩니다).

### 정의:
```python
@property
def show_percentage(self):
    ...

@show_percentage.setter
def show_percentage(self, value):
    ...
```

### 참조
* 클래스 [`DataLabelFormat`](/slides/python-net/ko/aspose.slides.charts/datalabelformat)
* 모듈 [`aspose.slides.charts`](/slides/python-net/ko/aspose.slides.charts)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)