---
title: show_percentage property
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides.charts/idatalabelformat/show_percentage/
weight: 180
---
## show_percentage 屬性
表示指定圖表的資料標籤百分比值顯示行為。 
True 會顯示百分比值。False 會隱藏。 
可讀寫 **bool**.


### Remarks

如果此 DataLabelFormat 物件的父項是 DataLabelCollection（資料標籤集合），則此屬性會取得或設定 DataLabelCollection 中新資料標籤的 ShowPercentage 屬性之預設值。 
以值設定此屬性時，也會將此值設定給 DataLabelCollection 中所有資料標籤的 ShowPercentage 屬性。 
（例如 "DataLabels.DefaultDataLabelFormat.ShowPercentage = val;" 會導致所有 DataLabels[i].ShowPercentage 等於 val）。

### 定義：
```python
@property
def show_percentage(self):
    ...

@show_percentage.setter
def show_percentage(self, value):
    ...
```


### 另請參閱
* class [`IDataLabelFormat`](/slides/python-net/zh-hant/aspose.slides.charts/idatalabelformat)
* module [`aspose.slides.charts`](/slides/python-net/zh-hant/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)