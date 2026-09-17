---
title: show_legend_key property
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.charts/datalabelformat/show_legend_key/
weight: 170
---
## show_legend_key プロパティ
指定されたチャートのデータラベルの凡例キーの表示動作を表します。  
凡例キーが表示されている場合は True。  
読み取り/書き込み **bool**。


### 備考

この DataLabelFormat オブジェクトの親が DataLabelCollection のデータラベル コレクションである場合、この プロパティは DataLabelCollection 内の新しいデータラベルに対する ShowLegendKey プロパティの既定値を取得または設定します。  
この プロパティに値を設定すると、DataLabelCollection 内のすべてのデータラベルの ShowLegendKey プロパティにも同じ値が設定されます  
(例: "DataLabels.DefaultDataLabelFormat.ShowLegendKey = val;" とすると、すべての DataLabels[i].ShowLegendKey が val と等しくなります)。

### 定義:
```python
@property
def show_legend_key(self):
    ...

@show_legend_key.setter
def show_legend_key(self, value):
    ...
```


### 関連項目
* クラス [`DataLabelFormat`](/slides/python-net/ja/aspose.slides.charts/datalabelformat)
* モジュール [`aspose.slides.charts`](/slides/python-net/ja/aspose.slides.charts)
* ライブラリ [`Aspose.Slides`](/slides/python-net)