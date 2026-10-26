---
title: show_leader_lines property
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.charts/idatalabelformat/show_leader_lines/
weight: 160
---
## show_leader_lines プロパティ
指定されたチャートのデータラベルリーダーラインの表示動作を表します。True はリーダーラインを表示し、False は非表示にします。読み書き **bool**。

### 備考

この DataLabelFormat オブジェクトの親がデータラベルの DataLabelCollection コレクションである場合、このプロパティは DataLabelCollection コレクション内の新しいデータラベルに対する ShowLeaderLines プロパティのデフォルト値を取得または設定します。値を設定すると、この値が DataLabelCollection コレクション内のすべてのデータラベルの ShowLeaderLines プロパティにも設定されます (例: "DataLabels.DefaultDataLabelFormat.ShowLeaderLines = val;" はすべての DataLabels[i].ShowLeaderLines が val と等しくなることを引き起こします)。

### 定義:
```python
@property
def show_leader_lines(self):
    ...

@show_leader_lines.setter
def show_leader_lines(self, value):
    ...
```

### 参照
* クラス [`IDataLabelFormat`](/slides/python-net/ja/aspose.slides.charts/idatalabelformat)
* モジュール [`aspose.slides.charts`](/slides/python-net/ja/aspose.slides.charts)
* ライブラリ [`Aspose.Slides`](/slides/python-net)