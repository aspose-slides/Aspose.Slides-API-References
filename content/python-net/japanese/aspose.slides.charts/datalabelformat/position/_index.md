---
title: position property
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.charts/datalabelformat/position/
weight: 90
---
## position プロパティ
データ ラベルの position を表します。
            読み取り/書き込み [`LegendDataLabelPosition`](/slides/python-net/ja/aspose.slides.charts/legenddatalabelposition).

### 備考

この DataLabelFormat オブジェクトの親がデータ ラベルの DataLabelCollection コレクションである場合、これ
            プロパティは新しいデータの Position プロパティの既定値を取得または設定します
            DataLabelCollection コレクション内のラベルです。
            DataLabel オブジェクトの位置を表します。
            このプロパティに値を設定すると、その値は Position プロパティにも設定されます
            DataLabelCollection コレクション内のすべてのデータ ラベルに対して
            （例："DataLabels.DefaultDataLabelFormat.Position = val;" は
            すべての DataLabels[i].Position が val に等しくなる）.

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
* クラス [`DataLabelFormat`](/slides/python-net/ja/aspose.slides.charts/datalabelformat)
* 列挙型 [`LegendDataLabelPosition`](/slides/python-net/ja/aspose.slides.charts/legenddatalabelposition)
* モジュール [`aspose.slides.charts`](/slides/python-net/ja/aspose.slides.charts)
* ライブラリ [`Aspose.Slides`](/slides/python-net)