---
title: separator property
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.charts/idatalabelformat/separator/
weight: 110
---
## separator プロパティ
チャート上のデータ ラベルで使用される separator を表す Variant を設定または取得します。
読み取り/書き込み **str**。

### 備考
この DataLabelFormat オブジェクトの親がデータ ラベルの DataLabelCollection コレクションである場合、このプロパティは DataLabelCollection 内の新しいデータ ラベルに対する Separator プロパティの既定値を取得または設定します。値を設定すると、この値は DataLabelCollection 内のすべてのデータ ラベルの Separator プロパティにも設定されます（例: "DataLabels.DefaultDataLabelFormat.Separator = val;" はすべての DataLabels[i].Separator が val と等しくなることを引き起こします）。

### 定義:
```python
@property
def separator(self):
    ...

@separator.setter
def separator(self, value):
    ...
```

### 参照
* クラス [`IDataLabelFormat`](/slides/python-net/ja/aspose.slides.charts/idatalabelformat)
* モジュール [`aspose.slides.charts`](/slides/python-net/ja/aspose.slides.charts)
* ライブラリ [`Aspose.Slides`](/slides/python-net)