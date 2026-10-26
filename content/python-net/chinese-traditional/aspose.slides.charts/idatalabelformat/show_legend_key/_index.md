---
title: show_legend_key property
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides.charts/idatalabelformat/show_legend_key/
weight: 170
---
## show_legend_key 屬性
表示指定圖表的資料標籤圖例鍵顯示行為。 
            如果資料標籤圖例鍵可見，則為 True。
            讀/寫 **bool**.

### 備註

如果此 DataLabelFormat 物件的父項是 DataLabelCollection（資料標籤集合），則此屬性會取得或設定 DataLabelCollection 中新資料標籤的 ShowLegendKey 屬性的預設值。  
            以該值設定此屬性時，也會將此值設定給 DataLabelCollection 中所有資料標籤的 ShowLegendKey 屬性  
            （例如 "DataLabels.DefaultDataLabelFormat.ShowLegendKey = val;" 會導致所有 DataLabels[i].ShowLegendKey 等於 val）。

### 定義：
```python
@property
def show_legend_key(self):
    ...

@show_legend_key.setter
def show_legend_key(self, value):
    ...
```

### 另請參閱
* 類別 [`IDataLabelFormat`](/slides/python-net/zh-hant/aspose.slides.charts/idatalabelformat)
* 模組 [`aspose.slides.charts`](/slides/python-net/zh-hant/aspose.slides.charts)
* 程式庫 [`Aspose.Slides`](/slides/python-net)