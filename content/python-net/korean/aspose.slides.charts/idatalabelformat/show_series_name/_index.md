---
title: show_series_name property
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.charts/idatalabelformat/show_series_name/
weight: 190
---
## show_series_name 속성
차트의 데이터 레이블에 대한 시리즈 이름 표시 동작을 나타내는 Boolean 값을 반환하거나 설정합니다.
            True를 사용하면 시리즈 이름을 표시합니다. False를 사용하면 숨깁니다.
            읽기/쓰기 **bool**.

### 참고

이 DataLabelFormat 객체의 부모가 데이터 레이블의 DataLabelCollection 컬렉션인 경우
            속성은 새 데이터 레이블에 대한 ShowSeriesName 속성의 기본값을 가져오거나 설정합니다
            DataLabelCollection 컬렉션의 레이블에 대해.
            이 속성을 값으로 설정하면 ShowSeriesName 속성에도 해당 값이 설정됩니다
            DataLabelCollection 컬렉션의 모든 데이터 레이블에 대해
            (예: "DataLabels.DefaultDataLabelFormat.ShowSeriesName = val;" 은
            모든 DataLabels[i].ShowSeriesName이 val과 동일해집니다).

### 정의:
```python
@property
def show_series_name(self):
    ...

@show_series_name.setter
def show_series_name(self, value):
    ...
```

### 참고
* 클래스 [`IDataLabelFormat`](/slides/python-net/ko/aspose.slides.charts/idatalabelformat)
* 모듈 [`aspose.slides.charts`](/slides/python-net/ko/aspose.slides.charts)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)