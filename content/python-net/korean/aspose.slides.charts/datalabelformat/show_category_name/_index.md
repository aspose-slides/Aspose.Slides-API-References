---
title: show_category_name property
second_title: Aspose.Slides for Python를 통한 .NET API 참조
description: 
type: docs
url: /ko/aspose.slides.charts/datalabelformat/show_category_name/
weight: 130
---
## show_category_name 속성
지정된 차트의 데이터 레이블 범주 이름 표시 동작을 나타냅니다.
            True to display the category name for the data labels on a chart. False to hide.
            읽기/쓰기 **bool**.


### 비고

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this
            property gets or sets the default value of the ShowCategoryName property for the new data 
            labels in the DataLabelCollection collection.
            Set this property with value also sets this value to the ShowCategoryName property 
            for all data labels in the DataLabelCollection collection
            (예: "DataLabels.DefaultDataLabelFormat.ShowCategoryName = val;" cause to 
            all DataLabels[i].ShowCategoryName is equal to val).

### 정의:
```python
@property
def show_category_name(self):
    ...

@show_category_name.setter
def show_category_name(self, value):
    ...
```


### 참고
* 클래스 [`DataLabelFormat`](/slides/python-net/ko/aspose.slides.charts/datalabelformat)
* 모듈 [`aspose.slides.charts`](/slides/python-net/ko/aspose.slides.charts)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)