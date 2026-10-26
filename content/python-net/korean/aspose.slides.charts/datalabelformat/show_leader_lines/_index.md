---
title: show_leader_lines property
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides.charts/datalabelformat/show_leader_lines/
weight: 160
---
## show_leader_lines 속성
지정된 차트의 데이터 레이블 리더 라인 표시 동작을 나타냅니다.
True는 리더 라인을 표시합니다. False는 숨깁니다.
읽기/쓰기 **bool**.

### 비고

만약 이 DataLabelFormat 객체의 부모가 데이터 레이블의 DataLabelCollection 컬렉션이면, 이 속성은 DataLabelCollection 컬렉션의 새 데이터 레이블에 대한 ShowLeaderLines 속성의 기본값을 가져오거나 설정합니다.
값으로 이 속성을 설정하면 DataLabelCollection 컬렉션의 모든 데이터 레이블에 대한 ShowLeaderLines 속성에도 동일한 값이 설정됩니다.
(예: "DataLabels.DefaultDataLabelFormat.ShowLeaderLines = val;"은 모든 DataLabels[i].ShowLeaderLines가 val과 같아지게 합니다).

### 정의:
```python
@property
def show_leader_lines(self):
    ...

@show_leader_lines.setter
def show_leader_lines(self, value):
    ...
```

### 참고
* 클래스 [`DataLabelFormat`](/slides/python-net/ko/aspose.slides.charts/datalabelformat)
* 모듈 [`aspose.slides.charts`](/slides/python-net/ko/aspose.slides.charts)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)