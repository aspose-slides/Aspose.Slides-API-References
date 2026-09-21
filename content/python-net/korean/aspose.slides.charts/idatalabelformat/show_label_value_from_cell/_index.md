---
title: show_label_value_from_cell property
second_title: Aspose.Slides Python용 via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides.charts/idatalabelformat/show_label_value_from_cell/
weight: 150
---
## show_label_value_from_cell 속성
지정된 차트의 데이터 레이블 셀 값 표시 동작을 나타냅니다. 
True는 셀 값을 표시합니다. False는 숨깁니다.
읽기/쓰기 **bool**.

### 비고

이 DataLabelFormat 객체의 부모가 데이터 레이블의 DataLabelCollection 컬렉션인 경우, 이 속성은 DataLabelCollection 컬렉션의 새 데이터 레이블에 대해 ShowLabelValueFromCell 속성의 기본값을 가져오거나 설정합니다.
값으로 이 속성을 설정하면 DataLabelCollection 컬렉션의 모든 데이터 레이블에 대한 ShowLabelValueFromCell 속성에도 이 값을 설정합니다.
(예: "DataLabels.DefaultDataLabelFormat.ShowLabelValueFromCell = val;" 은 모든 DataLabels[i].ShowLabelValueFromCell이 val과 동일하게 됩니다.)

### 정의:
```python
@property
def show_label_value_from_cell(self):
    ...

@show_label_value_from_cell.setter
def show_label_value_from_cell(self, value):
    ...
```

### 참조
* 클래스 [`IDataLabelFormat`](/slides/python-net/ko/aspose.slides.charts/idatalabelformat)
* 모듈 [`aspose.slides.charts`](/slides/python-net/ko/aspose.slides.charts)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)