---
title: show_leader_lines property
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides.charts/idatalabelformat/show_leader_lines/
weight: 160
---
## show_leader_lines 屬性
表示指定圖表的資料標籤領引線顯示行為。 True 會顯示領引線， False 則隱藏。 讀寫 **bool**。

### 備註
如果此 DataLabelFormat 物件的父項是 DataLabelCollection（資料標籤集合），則此屬性會取得或設定在 DataLabelCollection 中新資料標籤的 ShowLeaderLines 屬性的預設值。將此屬性設為某個值，同時也會將該值設定給 DataLabelCollection 中所有資料標籤的 ShowLeaderLines 屬性（例如「DataLabels.DefaultDataLabelFormat.ShowLeaderLines = val;」會導致所有 DataLabels[i].ShowLeaderLines 等於 val）。

### 定義：
```python
@property
def show_leader_lines(self):
    ...

@show_leader_lines.setter
def show_leader_lines(self, value):
    ...
```

### 另見
* 類別 [`IDataLabelFormat`](/slides/python-net/zh-hant/aspose.slides.charts/idatalabelformat)
* 模組 [`aspose.slides.charts`](/slides/python-net/zh-hant/aspose.slides.charts)
* 函式庫 [`Aspose.Slides`](/slides/python-net)