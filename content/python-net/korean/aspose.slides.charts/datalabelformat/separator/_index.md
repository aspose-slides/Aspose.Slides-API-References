---
title: separator property
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides.charts/datalabelformat/separator/
weight: 110
---
## 구분자 속성
차트의 데이터 레이블에 사용되는 구분자를 나타내는 Variant를 설정하거나 반환합니다.
            읽기/쓰기 **str**.


### 비고

이 DataLabelFormat 개체의 상위가 DataLabelCollection 컬렉션인 경우, 이
            속성은 DataLabelCollection 컬렉션의 새 데이터 레이블에 대한 Separator 속성의 기본값을 가져오거나 설정합니다.
            이 속성을 값으로 설정하면 DataLabelCollection 컬렉션의 모든 데이터 레이블에 대해 Separator 속성도 해당 값으로 설정됩니다
            (예: "DataLabels.DefaultDataLabelFormat.Separator = val;"는 모든 DataLabels[i].Separator가 val와 같게 됩니다).

### 정의:
```python
@property
def separator(self):
    ...

@separator.setter
def separator(self, value):
    ...
```


### 참고
* 클래스 [`DataLabelFormat`](/slides/python-net/ko/aspose.slides.charts/datalabelformat)
* 모듈 [`aspose.slides.charts`](/slides/python-net/ko/aspose.slides.charts)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)