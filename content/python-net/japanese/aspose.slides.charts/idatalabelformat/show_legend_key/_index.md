---
title: show_legend_key property
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.charts/idatalabelformat/show_legend_key/
weight: 170
---
## show_legend_key プロパティ
指定されたチャートのデータ ラベルの凡例キーの表示動作を表します。 
True if the data label legend key is visible.
読み取り/書き込み **bool**.


### 備考

この DataLabelFormat オブジェクトの親がデータ ラベルの DataLabelCollection コレクションである場合、このプロパティは DataLabelCollection コレクション内の新しいデータ ラベルに対する ShowLegendKey プロパティの既定値を取得または設定します。 
このプロパティに値を設定すると、DataLabelCollection コレクション内のすべてのデータ ラベルの ShowLegendKey プロパティにも同じ値が設定されます。 
（例: "DataLabels.DefaultDataLabelFormat.ShowLegendKey = val;" はすべての DataLabels[i].ShowLegendKey が val と等しくなることを引き起こします）。

### 定義:
```python
@property
def show_legend_key(self):
    ...

@show_legend_key.setter
def show_legend_key(self, value):
    ...
```


### 参照
* クラス [`IDataLabelFormat`](/slides/python-net/ja/aspose.slides.charts/idatalabelformat)
* モジュール [`aspose.slides.charts`](/slides/python-net/ja/aspose.slides.charts)
* ライブラリ [`Aspose.Slides`](/slides/python-net)