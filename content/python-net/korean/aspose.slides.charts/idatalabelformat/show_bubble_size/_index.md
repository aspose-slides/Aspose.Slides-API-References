---
title: show_bubble_size property
second_title: Aspose.Slides Python용 .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.charts/idatalabelformat/show_bubble_size/
weight: 120
---
## show_bubble_size 속성
지정된 차트의 데이터 레이블 버블 크기 값 표시 동작을 나타냅니다.  
True는 버블 크기 값을 표시합니다. False는 숨깁니다.  
읽기/쓰기 **bool**.

### 비고

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this  
            속성 gets or sets the default value of the ShowBubbleSize 속성 for the new data  
            labels in the DataLabelCollection collection.  
Set this 속성 with value also sets this value to the ShowBubbleSize 속성  
for all data labels in the DataLabelCollection collection  
(i.e. "DataLabels.DefaultDataLabelFormat.ShowBubbleSize = val;" cause to  
all DataLabels[i].ShowBubbleSize is equal to val).

### 정의:
```python
@property
def show_bubble_size(self):
    ...

@show_bubble_size.setter
def show_bubble_size(self, value):
    ...
```

### 참조
* 클래스 [`IDataLabelFormat`](/slides/python-net/ko/aspose.slides.charts/idatalabelformat)
* 모듈 [`aspose.slides.charts`](/slides/python-net/ko/aspose.slides.charts)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)