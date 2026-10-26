---
title: position property
second_title: Aspose.Slides 適用於 Python 的 .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides.charts/datalabelformat/position/
weight: 90
---
## position 屬性
Represents the position of the data label.
可讀寫 [`LegendDataLabelPosition`](/slides/python-net/zh-hant/aspose.slides.charts/legenddatalabelposition).

### 備註

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this
            property gets or sets the default value of the Position property for the new data 
            labels in the DataLabelCollection collection.
            Represents the position for the DataLabel objects.
            Set this property with value also sets this value to the Position property 
            for all data labels in the DataLabelCollection collection
            (i.e. "DataLabels.DefaultDataLabelFormat.Position = val;" cause to 
            all DataLabels[i].Position is equal to val).

### 定義：
```python
@property
def position(self):
    ...

@position.setter
def position(self, value):
    ...
```

### 另見
* 類別 [`DataLabelFormat`](/slides/python-net/zh-hant/aspose.slides.charts/datalabelformat)
* 列舉 [`LegendDataLabelPosition`](/slides/python-net/zh-hant/aspose.slides.charts/legenddatalabelposition)
* 模組 [`aspose.slides.charts`](/slides/python-net/zh-hant/aspose.slides.charts)
* 函式庫 [`Aspose.Slides`](/slides/python-net)