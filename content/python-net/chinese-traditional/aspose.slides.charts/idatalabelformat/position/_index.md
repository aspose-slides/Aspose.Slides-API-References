---
title: position property
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides.charts/idatalabelformat/position/
weight: 90
---
## position 屬性
表示資料標籤的位置。  
可讀寫 [`LegendDataLabelPosition`](/slides/python-net/zh-hant/aspose.slides.charts/legenddatalabelposition).

### 備註

如果此 DataLabelFormat 物件的父項是 DataLabelCollection（資料標籤集合），則此屬性會取得或設定新資料標籤在 DataLabelCollection 集合中的 Position 屬性的預設值。  
表示 DataLabel 物件的位置。  
設定此屬性的值也會將該值設定為 DataLabelCollection 集合中所有資料標籤的 Position 屬性。  
（即「DataLabels.DefaultDataLabelFormat.Position = val;」導致所有 DataLabels[i].Position 等於 val。）

### 定義:
```python
@property
def position(self):
    ...

@position.setter
def position(self, value):
    ...
```

### 另請參閱
* 類別 [`IDataLabelFormat`](/slides/python-net/zh-hant/aspose.slides.charts/idatalabelformat)
* 列舉 [`LegendDataLabelPosition`](/slides/python-net/zh-hant/aspose.slides.charts/legenddatalabelposition)
* 模組 [`aspose.slides.charts`](/slides/python-net/zh-hant/aspose.slides.charts)
* 函式庫 [`Aspose.Slides`](/slides/python-net)