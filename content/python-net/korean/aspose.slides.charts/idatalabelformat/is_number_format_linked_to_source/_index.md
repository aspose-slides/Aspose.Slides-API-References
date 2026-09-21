---
title: is_number_format_linked_to_source property
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.charts/idatalabelformat/is_number_format_linked_to_source/
weight: 70
---
## is_number_format_linked_to_source 속성
읽기/쓰기 **bool**.


### 비고

이 DataLabelFormat 객체의 부모가 데이터 레이블의 DataLabelCollection 컬렉션인 경우, 이 속성은 DataLabelCollection 컬렉션에 있는 새 데이터 레이블에 대해 IsNumberFormatLinkedToSource 속성의 기본값을 가져오거나 설정합니다. 이 속성에 값을 설정하면 DataLabelCollection 컬렉션에 있는 모든 데이터 레이블에 대해 IsNumberFormatLinkedToSource 속성에도 동일한 값이 설정됩니다. (예: "DataLabels.DefaultDataLabelFormat.IsNumberFormatLinkedToSource = val;" 은 모든 DataLabels[i].IsNumberFormatLinkedToSource 가 val 와 동일하게 됩니다.)

### 정의:
```python
@property
def is_number_format_linked_to_source(self):
    ...

@is_number_format_linked_to_source.setter
def is_number_format_linked_to_source(self, value):
    ...
```


### 참고
* 클래스 [`IDataLabelFormat`](/slides/python-net/ko/aspose.slides.charts/idatalabelformat)
* 모듈 [`aspose.slides.charts`](/slides/python-net/ko/aspose.slides.charts)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)