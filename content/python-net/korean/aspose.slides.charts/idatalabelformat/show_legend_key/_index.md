---
title: show_legend_key property
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.charts/idatalabelformat/show_legend_key/
weight: 170
---
## show_legend_key 속성
지정된 차트의 데이터 레이블 범례 키 표시 동작을 나타냅니다. 
            데이터 레이블 범례 키가 보이는 경우 True입니다.
            읽기/쓰기 **bool**.

### 비고
If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this
            속성은 DataLabelCollection 컬렉션의 새 데이터 레이블에 대한 ShowLegendKey 속성의 기본값을 가져오거나 설정합니다.
            이 속성을 값으로 설정하면 DataLabelCollection 컬렉션의 모든 데이터 레이블에 대해 ShowLegendKey 속성에도 동일한 값이 설정됩니다.
            (예: "DataLabels.DefaultDataLabelFormat.ShowLegendKey = val;"는 모든 DataLabels[i].ShowLegendKey가 val와 같게 됩니다.)

### 정의:
```python
@property
def show_legend_key(self):
    ...

@show_legend_key.setter
def show_legend_key(self, value):
    ...
```

### 참조
* 클래스 [`IDataLabelFormat`](/slides/python-net/ko/aspose.slides.charts/idatalabelformat)
* 모듈 [`aspose.slides.charts`](/slides/python-net/ko/aspose.slides.charts)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)