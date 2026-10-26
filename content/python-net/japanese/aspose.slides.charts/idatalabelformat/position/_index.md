---
title: position property
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.charts/idatalabelformat/position/
weight: 90
---
## 位置プロパティ
データラベルの位置を表します。  
読み取り/書き込み [`LegendDataLabelPosition`](/slides/python-net/ja/aspose.slides.charts/legenddatalabelposition)。

### 備考

この DataLabelFormat オブジェクトの親が DataLabelCollection（データラベルのコレクション）である場合、このプロパティは DataLabelCollection の新しいデータラベルに対する Position プロパティの既定値を取得または設定します。  
DataLabel オブジェクトの位置を表します。  
このプロパティに値を設定すると、DataLabelCollection のすべてのデータラベルの Position プロパティにも同じ値が設定されます（例: "DataLabels.DefaultDataLabelFormat.Position = val;" により、すべての DataLabels[i].Position が val と等しくなります）。

### 定義:
```python
@property
def position(self):
    ...

@position.setter
def position(self, value):
    ...
```

### 参照
* クラス [`IDataLabelFormat`](/slides/python-net/ja/aspose.slides.charts/idatalabelformat)
* 列挙体 [`LegendDataLabelPosition`](/slides/python-net/ja/aspose.slides.charts/legenddatalabelposition)
* モジュール [`aspose.slides.charts`](/slides/python-net/ja/aspose.slides.charts)
* ライブラリ [`Aspose.Slides`](/slides/python-net)