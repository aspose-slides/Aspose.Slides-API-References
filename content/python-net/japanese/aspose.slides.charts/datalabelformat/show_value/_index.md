---
title: show_value property
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.charts/datalabelformat/show_value/
weight: 200
---
## show_value プロパティ
指定されたチャートのデータラベルのパーセンテージ値の表示動作を表します。 
            True はパーセンテージ値を表示し、False は非表示にします。
            読み書き **bool**。


### 備考

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this
            property gets or sets the default value of the ShowValue Property for the new data 
            labels in the DataLabelCollection collection.
            Set this property with value also sets this value to the ShowValue property 
            for all data labels in the DataLabelCollection collection
            (i.e. "DataLabels.DefaultDataLabelFormat.ShowValue = val;" cause to 
            all DataLabels[i].ShowValue is equal to val).


### 定義：
```python
@property
def show_value(self):
    ...

@show_value.setter
def show_value(self, value):
    ...
```


### 参照
* クラス [`DataLabelFormat`](/slides/python-net/ja/aspose.slides.charts/datalabelformat)
* モジュール [`aspose.slides.charts`](/slides/python-net/ja/aspose.slides.charts)
* ライブラリ [`Aspose.Slides`](/slides/python-net)