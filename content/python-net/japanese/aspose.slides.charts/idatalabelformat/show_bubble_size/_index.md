---
title: show_bubble_size property
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.charts/idatalabelformat/show_bubble_size/
weight: 120
---
## show_bubble_size プロパティ
指定されたチャートのデータラベルバブルサイズ値の表示動作を表します。  
True はバブルサイズの値を表示し、False は非表示にします。  
読み取り/書き込み **bool**。


### 備考

もしこの DataLabelFormat オブジェクトの親がデータラベルの DataLabelCollection コレクションである場合、このプロパティは DataLabelCollection コレクション内の新しいデータラベルに対する ShowBubbleSize プロパティのデフォルト値を取得または設定します。  
このプロパティに値を設定すると、DataLabelCollection コレクション内のすべてのデータラベルの ShowBubbleSize プロパティにも同じ値が設定されます。  
(例: "DataLabels.DefaultDataLabelFormat.ShowBubbleSize = val;" により、すべての DataLabels[i].ShowBubbleSize が val と等しくなります。)


### 定義:
```python
@property
def show_bubble_size(self):
    ...

@show_bubble_size.setter
def show_bubble_size(self, value):
    ...
```


### 参照
* クラス [`IDataLabelFormat`](/slides/python-net/ja/aspose.slides.charts/idatalabelformat)
* モジュール [`aspose.slides.charts`](/slides/python-net/ja/aspose.slides.charts)
* ライブラリ [`Aspose.Slides`](/slides/python-net)