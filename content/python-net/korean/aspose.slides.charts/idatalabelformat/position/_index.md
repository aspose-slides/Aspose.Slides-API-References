---
title: position property
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.charts/idatalabelformat/position/
weight: 90
---
## position 속성
데이터 레이블의 위치를 나타냅니다.
            읽기/쓰기 [`LegendDataLabelPosition`](/slides/python-net/ko/aspose.slides.charts/legenddatalabelposition).

### 비고

이 DataLabelFormat 객체의 부모가 데이터 레이블의 DataLabelCollection 컬렉션인 경우 이
            속성은 새 데이터 레이블에 대한 Position 속성의 기본값을 가져오거나 설정합니다.
            DataLabelCollection 컬렉션에 있습니다.
            DataLabel 객체의 위치를 나타냅니다.
            이 속성을 값으로 설정하면 해당 값이 Position 속성에도 설정됩니다.
            DataLabelCollection 컬렉션에 있는 모든 데이터 레이블에 대해
            (예: "DataLabels.DefaultDataLabelFormat.Position = val;"는
            모든 DataLabels[i].Position이 val과 동일하게 됩니다.)

### 정의:
```python
@property
def position(self):
    ...

@position.setter
def position(self, value):
    ...
```

### 참고
* 클래스 [`IDataLabelFormat`](/slides/python-net/ko/aspose.slides.charts/idatalabelformat)
* 열거형 [`LegendDataLabelPosition`](/slides/python-net/ko/aspose.slides.charts/legenddatalabelposition)
* 모듈 [`aspose.slides.charts`](/slides/python-net/ko/aspose.slides.charts)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)