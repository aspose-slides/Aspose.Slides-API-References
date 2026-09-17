---
title: show_leader_lines property
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.charts/datalabelformat/show_leader_lines/
weight: 160
---
## show_leader_lines プロパティ
指定されたチャートのデータラベルリーダーラインの表示動作を表します。 
True はリーダーラインを表示します。False は非表示にします。
読み書き可能 **bool**。


### 備考

この DataLabelFormat オブジェクトの親がデータラベルの DataLabelCollection コレクションである場合、このプロパティは DataLabelCollection コレクション内の新しいデータラベルに対する ShowLeaderLines プロパティの既定値を取得または設定します。
このプロパティに値を設定すると、DataLabelCollection コレクション内のすべてのデータラベルの ShowLeaderLines プロパティにも同じ値が設定されます。
(例: "DataLabels.DefaultDataLabelFormat.ShowLeaderLines = val;" は、すべての DataLabels[i].ShowLeaderLines が val と等しくなる原因となります。)

### 定義:
```python
@property
def show_leader_lines(self):
    ...

@show_leader_lines.setter
def show_leader_lines(self, value):
    ...
```


### 関連項目
* クラス [`DataLabelFormat`](/slides/python-net/ja/aspose.slides.charts/datalabelformat)
* モジュール [`aspose.slides.charts`](/slides/python-net/ja/aspose.slides.charts)
* ライブラリ [`Aspose.Slides`](/slides/python-net)