---
title: show_legend_key property
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides.charts/datalabelformat/show_legend_key/
weight: 170
---
## show_legend_key 屬性
表示特定圖表的資料標籤圖例鍵顯示行為。  
True if the data label legend key is visible.  
如果資料標籤圖例鍵可見，則為 True。  
Read/write **bool**.  
可讀寫 **bool**。

### 備註
如果此 DataLabelFormat 物件的父項是資料標籤的 DataLabelCollection 集合，則此  
屬性會取得或設定新資料標籤的 ShowLegendKey 屬性的預設值，於 DataLabelCollection 集合中的標籤。  
設定此屬性的值也會將此值設定為所有資料標籤的 ShowLegendKey 屬性  
於 DataLabelCollection 集合中  
（即 "DataLabels.DefaultDataLabelFormat.ShowLegendKey = val;" 會導致  
所有 DataLabels[i].ShowLegendKey 等於 val）。

### 定義：
```python
@property
def show_legend_key(self):
    ...

@show_legend_key.setter
def show_legend_key(self, value):
    ...
```

### 另見
* 類別 [`DataLabelFormat`](/slides/python-net/zh-hant/aspose.slides.charts/datalabelformat)
* 模組 [`aspose.slides.charts`](/slides/python-net/zh-hant/aspose.slides.charts)
* 函式庫 [`Aspose.Slides`](/slides/python-net)