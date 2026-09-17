---
title: show_series_name property
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.charts/idatalabelformat/show_series_name/
weight: 190
---
## show_series_name プロパティ
Returns or sets a Boolean to indicate the series name display behavior for the data labels on a chart. 
            True to show the series name. False to hide.
            Read/write **bool**.

### 備考
If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this
            property gets or sets the default value of the ShowSeriesName property for the new data 
            labels in the DataLabelCollection collection.
            Set this property with value also sets this value to the ShowSeriesName property 
            for all data labels in the DataLabelCollection collection
            (i.e. "DataLabels.DefaultDataLabelFormat.ShowSeriesName = val;" cause to 
            all DataLabels[i].ShowSeriesName is equal to val).

### 定義:
```python
@property
def show_series_name(self):
    ...

@show_series_name.setter
def show_series_name(self, value):
    ...
```

### 参照
* クラス [`IDataLabelFormat`](/slides/python-net/ja/aspose.slides.charts/idatalabelformat)
* モジュール [`aspose.slides.charts`](/slides/python-net/ja/aspose.slides.charts)
* ライブラリ [`Aspose.Slides`](/slides/python-net)