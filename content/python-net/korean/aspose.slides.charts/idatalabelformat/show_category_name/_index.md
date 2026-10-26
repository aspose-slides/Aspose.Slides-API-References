---
title: show_category_name property
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides.charts/idatalabelformat/show_category_name/
weight: 130
---
## show_category_name 속성
지정된 차트의 데이터 라벨 카테고리 이름 표시 동작을 나타냅니다.
True를 사용하면 차트의 데이터 라벨에 대한 카테고리 이름을 표시합니다. False를 사용하면 숨깁니다.
읽기/쓰기 **bool**.

### 비고

이 DataLabelFormat 객체의 상위가 데이터 라벨의 DataLabelCollection 컬렉션인 경우, 이 속성은 DataLabelCollection 컬렉션의 새 데이터 라벨에 대한 ShowCategoryName 속성의 기본값을 가져오거나 설정합니다.
이 속성을 값으로 설정하면 DataLabelCollection 컬렉션의 모든 데이터 라벨에 대한 ShowCategoryName 속성에도 해당 값이 설정됩니다.
(예: "DataLabels.DefaultDataLabelFormat.ShowCategoryName = val;" 은 모든 DataLabels[i].ShowCategoryName이 val과 동일하게 됩니다.)

### 정의:
```python
@property
def show_category_name(self):
    ...

@show_category_name.setter
def show_category_name(self, value):
    ...
```

### 참조
* 클래스 [`IDataLabelFormat`](/slides/python-net/ko/aspose.slides.charts/idatalabelformat)
* 모듈 [`aspose.slides.charts`](/slides/python-net/ko/aspose.slides.charts)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)