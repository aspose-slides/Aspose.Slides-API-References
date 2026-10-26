---
title: show_bubble_size property
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.charts/datalabelformat/show_bubble_size/
weight: 120
---
## show_bubble_size プロパティ
指定されたチャートのデータ ラベルのバブル サイズ値の表示動作を表します。  
True はバブル サイズ値を表示し、False は非表示にします。  
読み書き可能 **bool**。


### Remarks

この DataLabelFormat オブジェクトの親が DataLabelCollection のデータ ラベル コレクションである場合、このプロパティは DataLabelCollection コレクション内の新しいデータ ラベルに対する ShowBubbleSize プロパティのデフォルト値を取得または設定します。  
このプロパティに値を設定すると、DataLabelCollection コレクション内のすべてのデータ ラベルの ShowBubbleSize プロパティにも同じ値が設定されます。  
（例: "DataLabels.DefaultDataLabelFormat.ShowBubbleSize = val;" はすべての DataLabels[i].ShowBubbleSize が val と等しくなることを引き起こします。）


### Definition:
```python
@property
def show_bubble_size(self):
    ...

@show_bubble_size.setter
def show_bubble_size(self, value):
    ...
```


### 参照
* クラス [`DataLabelFormat`](/slides/python-net/ja/aspose.slides.charts/datalabelformat)
* モジュール [`aspose.slides.charts`](/slides/python-net/ja/aspose.slides.charts)
* ライブラリ [`Aspose.Slides`](/slides/python-net)