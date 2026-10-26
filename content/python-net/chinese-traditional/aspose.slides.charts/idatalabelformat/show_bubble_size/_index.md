---
title: show_bubble_size property
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides.charts/idatalabelformat/show_bubble_size/
weight: 120
---
## show_bubble_size 屬性
表示指定圖表的資料標籤氣泡大小值的顯示行為。 
True 會顯示氣泡大小值。False 會隱藏。
讀寫 **bool**。


### 備註

如果此 DataLabelFormat 物件的父層是 DataLabelCollection（資料標籤集合），則此屬性會取得或設定 DataLabelCollection 中新資料標籤的 ShowBubbleSize 屬性的預設值。設定此屬性時，同時也會把此值設定給 DataLabelCollection 中所有資料標籤的 ShowBubbleSize 屬性（例如「DataLabels.DefaultDataLabelFormat.ShowBubbleSize = val;」會導致所有 DataLabels[i].ShowBubbleSize 等於 val）。


### 定義：
```python
@property
def show_bubble_size(self):
    ...

@show_bubble_size.setter
def show_bubble_size(self, value):
    ...
```


### 另請參閱
* 類別 [`IDataLabelFormat`](/slides/python-net/zh-hant/aspose.slides.charts/idatalabelformat)
* 模組 [`aspose.slides.charts`](/slides/python-net/zh-hant/aspose.slides.charts)
* 函式庫 [`Aspose.Slides`](/slides/python-net)