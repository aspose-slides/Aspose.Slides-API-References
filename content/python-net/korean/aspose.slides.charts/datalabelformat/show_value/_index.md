---
title: show_value property
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides.charts/datalabelformat/show_value/
weight: 200
---
## show_value 속성
지정된 차트의 데이터 레이블 백분율 값 표시 동작을 나타냅니다. 
            True는 백분율 값을 표시합니다. False는 숨깁니다.
            읽기/쓰기 **bool**.


### 비고

만약 이 DataLabelFormat 객체의 부모가 데이터 레이블의 DataLabelCollection 컬렉션인 경우, 이 속성은 DataLabelCollection 컬렉션에 있는 새 데이터 레이블에 대한 ShowValue 속성의 기본값을 가져오거나 설정합니다.
            값과 함께 이 속성을 설정하면 DataLabelCollection 컬렉션에 있는 모든 데이터 레이블의 ShowValue 속성에도 이 값이 설정됩니다 (i.e. "DataLabels.DefaultDataLabelFormat.ShowValue = val;" cause to 
            all DataLabels[i].ShowValue is equal to val).

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
* 클래스 [`DataLabelFormat`](/slides/python-net/ko/aspose.slides.charts/datalabelformat)
* 모듈 [`aspose.slides.charts`](/slides/python-net/ko/aspose.slides.charts)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)