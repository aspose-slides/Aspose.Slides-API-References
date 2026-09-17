---
title: show_label_as_data_callout property
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.charts/datalabelformat/show_label_as_data_callout/
weight: 140
---
## show_label_as_data_callout プロパティ
指定されたチャートのデータ ラベルがデータ コールアウトとして表示されるか、データ ラベルとして表示されるかを決定します。

            If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this
            property gets or sets the default value of the ShowLabelAsDataCallout property for the new data 
            labels in the DataLabelCollection collection.
            Set this property with value also sets this value to the ShowLabelAsDataCallout property 
            for all data labels in the DataLabelCollection collection
            (i.e. "DataLabels.DefaultDataLabelFormat.ShowLabelAsDataCallout = val;" cause to 
            all DataLabels[i].ShowLabelAsDataCallout is equal to val).

### 定義:
```python
@property
def show_label_as_data_callout(self):
    ...

@show_label_as_data_callout.setter
def show_label_as_data_callout(self, value):
    ...
```

### 参照
* class [`DataLabelFormat`](/slides/python-net/ja/aspose.slides.charts/datalabelformat)
* module [`aspose.slides.charts`](/slides/python-net/ja/aspose.slides.charts)
* library [`Aspose.Slides`](/slides/python-net)