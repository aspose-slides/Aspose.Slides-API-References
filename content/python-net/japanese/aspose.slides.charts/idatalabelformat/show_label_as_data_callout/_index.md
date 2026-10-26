---
title: show_label_as_data_callout property
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.charts/idatalabelformat/show_label_as_data_callout/
weight: 140
---
## show_label_as_data_callout プロパティ
指定されたチャートのデータラベルがデータコールアウトとして表示されるか、データラベルとして表示されるかを決定します。
            
            この DataLabelFormat オブジェクトの親がデータラベルの DataLabelCollection コレクションである場合、このプロパティは DataLabelCollection コレクション内の新しいデータラベルに対する ShowLabelAsDataCallout プロパティの既定値を取得または設定します。
            このプロパティに値を設定すると、DataLabelCollection コレクション内のすべてのデータラベルの ShowLabelAsDataCallout プロパティにも同じ値が設定されます（例: "DataLabels.DefaultDataLabelFormat.ShowLabelAsDataCallout = val;" はすべての DataLabels[i].ShowLabelAsDataCallout が val と等しくなる原因となります）。

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
* クラス [`IDataLabelFormat`](/slides/python-net/ja/aspose.slides.charts/idatalabelformat)
* モジュール [`aspose.slides.charts`](/slides/python-net/ja/aspose.slides.charts)
* ライブラリ [`Aspose.Slides`](/slides/python-net)