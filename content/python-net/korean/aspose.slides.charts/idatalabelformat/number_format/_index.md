---
title: number_format property
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides.charts/idatalabelformat/number_format/
weight: 80
---
## number_format 속성
DataLabels 개체에 대한 형식 문자열을 나타냅니다.
            읽기/쓰기 **str**.


### 비고

이 DataLabelFormat 객체의 상위가 데이터 레이블의 DataLabelCollection 컬렉션인 경우, 이 속성은 DataLabelCollection 컬렉션에 있는 새 데이터 레이블에 대한 NumberFormat 속성의 기본값을 가져오거나 설정합니다.
            이 속성을 값으로 설정하면 해당 값이 DataLabelCollection 컬렉션에 있는 모든 데이터 레이블의 NumberFormat 속성에도 설정됩니다 (예: "DataLabels.DefaultDataLabelFormat.NumberFormat = val;"은 모든 DataLabels[i].NumberFormat이 val과 동일하도록 합니다).

### 정의:
```python
@property
def number_format(self):
    ...

@number_format.setter
def number_format(self, value):
    ...
```


### 참조
* 클래스 [`IDataLabelFormat`](/slides/python-net/ko/aspose.slides.charts/idatalabelformat)
* 모듈 [`aspose.slides.charts`](/slides/python-net/ko/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)