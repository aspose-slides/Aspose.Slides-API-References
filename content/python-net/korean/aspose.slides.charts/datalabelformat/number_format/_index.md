---
title: number_format property
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides.charts/datalabelformat/number_format/
weight: 80
---
## number_format 속성
DataLabels 개체에 대한 형식 문자열을 나타냅니다.
            읽기/쓰기 **str**.

### 비고

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels, then this
            속성은 DataLabelCollection 컬렉션의 새 데이터 레이블에 대한 NumberFormat 속성의 기본값을 가져오거나 설정합니다.
            이 속성이 값으로 설정되면, 해당 값은 DataLabelCollection 컬렉션의 모든 데이터 레이블에 대한 NumberFormat 속성에도 설정됩니다.
            (i.e. "DataLabels.DefaultDataLabelFormat.NumberFormat = val;" 은 모든 DataLabels[i].NumberFormat이 val과 같게 됩니다.)

### 정의:
```python
@property
def number_format(self):
    ...

@number_format.setter
def number_format(self, value):
    ...
```

### 참고
* 클래스 [`DataLabelFormat`](/slides/python-net/ko/aspose.slides.charts/datalabelformat)
* 모듈 [`aspose.slides.charts`](/slides/python-net/ko/aspose.slides.charts)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)