---
title: show_bubble_size property
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.charts/datalabelformat/show_bubble_size/
weight: 120
---
## show_bubble_size 속성
지정된 차트의 데이터 레이블 버블 크기 값 표시 동작을 나타냅니다.
True는 버블 크기 값을 표시합니다. False는 숨깁니다.
읽기/쓰기 **bool**.

### 비고

이 DataLabelFormat 개체의 상위가 데이터 레이블의 DataLabelCollection 컬렉션인 경우, 이 속성은 DataLabelCollection 컬렉션의 새로운 데이터 레이블에 대한 ShowBubbleSize 속성의 기본 값을 가져오거나 설정합니다.
이 속성을 값으로 설정하면 DataLabelCollection 컬렉션의 모든 데이터 레이블에 대한 ShowBubbleSize 속성에도 이 값이 설정됩니다.
(예: "DataLabels.DefaultDataLabelFormat.ShowBubbleSize = val;" 은 모든 DataLabels[i].ShowBubbleSize가 val과 같게 됩니다.)

### 정의:
```python
@property
def show_bubble_size(self):
    ...

@show_bubble_size.setter
def show_bubble_size(self, value):
    ...
```

### 참고
* 클래스 [`DataLabelFormat`](/slides/python-net/ko/aspose.slides.charts/datalabelformat)
* 모듈 [`aspose.slides.charts`](/slides/python-net/ko/aspose.slides.charts)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)