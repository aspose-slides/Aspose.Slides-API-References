---
title: show_label_value_from_cell property
second_title: Aspose.Slides for Python via .NET APIリファレンス
description: 
type: docs
url: /ja/aspose.slides.charts/datalabelformat/show_label_value_from_cell/
weight: 150
---
## show_label_value_from_cell プロパティ
指定されたチャートのデータラベルセル値の表示動作を表します。 
            True はセル値を表示し、False は非表示にします。 
            読み取り/書き込み **bool**。


### 備考

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this
            プロパティ は ShowLabelValueFromCell プロパティのデフォルト値を取得または設定します 新しいデータ 
            ラベルは DataLabelCollection コレクション内にあります。
            この プロパティに値を設定すると、ShowLabelValueFromCell プロパティにも同じ値が設定されます 
            DataLabelCollection コレクション内のすべてのデータラベルに対して
            (例: "DataLabels.DefaultDataLabelFormat.ShowLabelValueFromCell = val;" は、 
            すべての DataLabels[i].ShowLabelValueFromCell が val と等しくなる原因となります)。


### 定義:
```python
@property
def show_label_value_from_cell(self):
    ...

@show_label_value_from_cell.setter
def show_label_value_from_cell(self, value):
    ...
```


### 参照
* クラス [`DataLabelFormat`](/slides/python-net/ja/aspose.slides.charts/datalabelformat)
* モジュール [`aspose.slides.charts`](/slides/python-net/ja/aspose.slides.charts)
* ライブラリ [`Aspose.Slides`](/slides/python-net)