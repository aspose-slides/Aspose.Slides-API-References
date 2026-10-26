---
title: show_leader_lines property
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.charts/idatalabelformat/show_leader_lines/
weight: 160
---
## show_leader_lines property
지정된 차트의 데이터 레이블 리더 라인 표시 동작을 나타냅니다. 
            True는 리더 라인을 표시합니다. False는 숨깁니다.
            읽기/쓰기 **bool**.

### 비고

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this
            property gets or sets the default value of the ShowLeaderLines property for the new data 
            labels in the DataLabelCollection collection.
            Set this property with value also sets this value to the ShowLeaderLines property 
            for all data labels in the DataLabelCollection collection
            (예: "DataLabels.DefaultDataLabelFormat.ShowLeaderLines = val;"은 모든 DataLabels[i].ShowLeaderLines가 val와 동일하게 됩니다).

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
* 클래스 [`IDataLabelFormat`](/slides/python-net/ko/aspose.slides.charts/idatalabelformat)
* 모듈 [`aspose.slides.charts`](/slides/python-net/ko/aspose.slides.charts)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)