---
title: show_percentage property
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.charts/idatalabelformat/show_percentage/
weight: 180
---
## show_percentage プロパティ
指定されたチャートのデータラベルのパーセンテージ値の表示動作を表します。 
True はパーセンテージ値を表示します。False は非表示にします。 
読み書き **bool**。


### 備考

この DataLabelFormat オブジェクトの親が DataLabelCollection（データラベルのコレクション）である場合、この
プロパティは DataLabelCollection 内の新しいデータラベルの ShowPercentage プロパティの既定値を取得または設定します。
このプロパティに値を設定すると、この値は DataLabelCollection 内のすべてのデータラベルの ShowPercentage プロパティにも設定されます
（例: `DataLabels.DefaultDataLabelFormat.ShowPercentage = val;` により、すべての DataLabels[i].ShowPercentage が val と等しくなります）。


### 定義:
```python
@property
def show_percentage(self):
    ...

@show_percentage.setter
def show_percentage(self, value):
    ...
```


### 参照
* クラス [`IDataLabelFormat`](/slides/python-net/ja/aspose.slides.charts/idatalabelformat)
* モジュール [`aspose.slides.charts`](/slides/python-net/ja/aspose.slides.charts)
* ライブラリ [`Aspose.Slides`](/slides/python-net)