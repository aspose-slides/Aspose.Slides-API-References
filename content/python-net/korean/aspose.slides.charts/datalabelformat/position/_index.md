---
title: position property
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.charts/datalabelformat/position/
weight: 90
---
## 위치 속성
데이터 레이블의 position을 나타냅니다.  
읽기/쓰기 [`LegendDataLabelPosition`](/slides/python-net/ko/aspose.slides.charts/legenddatalabelposition).

### 비고
이 DataLabelFormat 개체의 부모가 데이터 레이블의 DataLabelCollection 컬렉션인 경우, 이 속성은 DataLabelCollection 컬렉션의 새 데이터 레이블에 대한 Position 속성의 기본값을 가져오거나 설정합니다.  
DataLabel 개체에 대한 position을 나타냅니다.  
값으로 이 속성을 설정하면 DataLabelCollection 컬렉션의 모든 데이터 레이블에 대한 Position 속성에도 동일한 값이 설정됩니다 (예: "DataLabels.DefaultDataLabelFormat.Position = val;" 은 모든 DataLabels[i].Position이 val과 동일해집니다).

### 정의:
```python
@property
def position(self):
    ...

@position.setter
def position(self, value):
    ...
```

### 참조
* 클래스 [`DataLabelFormat`](/slides/python-net/ko/aspose.slides.charts/datalabelformat)
* 열거형 [`LegendDataLabelPosition`](/slides/python-net/ko/aspose.slides.charts/legenddatalabelposition)
* 모듈 [`aspose.slides.charts`](/slides/python-net/ko/aspose.slides.charts)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)