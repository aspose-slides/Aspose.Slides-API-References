---
title: show_leader_lines property
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides.charts/datalabelformat/show_leader_lines/
weight: 160
---
## show_leader_lines 屬性
表示指定圖表的資料標籤領線顯示行為。 
            True 會顯示領線。False 會隱藏。 
            讀/寫 **bool**.

### 備註
如果此 DataLabelFormat 物件的父項是 DataLabelCollection 資料標籤的集合，則此
            屬性會取得或設定 ShowLeaderLines 屬性的預設值，用於新的資料
            標籤於 DataLabelCollection 集合中。 
            設定此屬性時，同時會將此值設定為 ShowLeaderLines 屬性 
            用於 DataLabelCollection 集合中所有資料標籤 
            (例如 "DataLabels.DefaultDataLabelFormat.ShowLeaderLines = val;" 會導致 
            所有 DataLabels[i].ShowLeaderLines 等於 val)。

### 定義：
```python
@property
def show_leader_lines(self):
    ...

@show_leader_lines.setter
def show_leader_lines(self, value):
    ...
```

### 另請參閱
* 類別 [`DataLabelFormat`](/slides/python-net/zh-hant/aspose.slides.charts/datalabelformat)
* 模組 [`aspose.slides.charts`](/slides/python-net/zh-hant/aspose.slides.charts)
* 函式庫 [`Aspose.Slides`](/slides/python-net)