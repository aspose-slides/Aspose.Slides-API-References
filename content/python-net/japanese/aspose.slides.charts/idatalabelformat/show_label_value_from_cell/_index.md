---
title: show_label_value_from_cell property
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.charts/idatalabelformat/show_label_value_from_cell/
weight: 150
---
## show_label_value_from_cell プロパティ
指定されたチャートのデータ ラベル セル値の表示動作を表します。
True はセル値を表示します。False は非表示にします。
読み書き **bool**.


### 備考

この DataLabelFormat オブジェクトの親がデータ ラベルの DataLabelCollection コレクションである場合、このプロパティは DataLabelCollection コレクション内の新しいデータ ラベルに対する ShowLabelValueFromCell プロパティのデフォルト値を取得または設定します。
このプロパティに値を設定すると、DataLabelCollection コレクション内のすべてのデータ ラベルの ShowLabelValueFromCell プロパティにも同じ値が設定されます。
(例: "DataLabels.DefaultDataLabelFormat.ShowLabelValueFromCell = val;" はすべての DataLabels[i].ShowLabelValueFromCell が val と等しくなることを引き起こします)。

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
* クラス [`IDataLabelFormat`](/slides/python-net/ja/aspose.slides.charts/idatalabelformat)
* モジュール [`aspose.slides.charts`](/slides/python-net/ja/aspose.slides.charts)
* ライブラリ [`Aspose.Slides`](/slides/python-net)