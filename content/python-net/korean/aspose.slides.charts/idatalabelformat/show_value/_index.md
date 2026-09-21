---
title: show_value property
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.charts/idatalabelformat/show_value/
weight: 200
---
## show_value 속성
특정 차트의 데이터 레이블 백분율 값 표시 동작을 나타냅니다. 
            True는 백분율 값을 표시합니다. False는 숨깁니다.
            읽기/쓰기 **bool**.

### 비고

이 DataLabelFormat 객체의 상위가 DataLabelCollection 데이터 레이블 컬렉션인 경우, 이
            속성은 DataLabelCollection 컬렉션에 있는 새 데이터 레이블에 대한 ShowValue 속성의 기본값을 가져오거나 설정합니다.
            값을 사용하여 이 속성을 설정하면 해당 값이 ShowValue 속성에도 설정됩니다.
            DataLabelCollection 컬렉션의 모든 데이터 레이블에 대해 (예: "DataLabels.DefaultDataLabelFormat.ShowValue = val;" 로 인해 모든 DataLabels[i].ShowValue가 val와 동일하게 됩니다).

### 정의:
```python
@property
def show_value(self):
    ...

@show_value.setter
def show_value(self, value):
    ...
```


### 참조
* 클래스 [`IDataLabelFormat`](/slides/python-net/ko/aspose.slides.charts/idatalabelformat)
* 모듈 [`aspose.slides.charts`](/slides/python-net/ko/aspose.slides.charts)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)