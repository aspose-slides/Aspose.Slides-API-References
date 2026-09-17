---
title: number_format property
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.charts/datalabelformat/number_format/
weight: 80
---
## number_format プロパティ
DataLabels オブジェクトの書式文字列を表します。
            読み書き **str**.


### 備考

この DataLabelFormat オブジェクトの親が DataLabelCollection のデータラベル コレクションである場合、このプロパティは DataLabelCollection に新しく作成されるデータラベルの NumberFormat プロパティの既定値を取得または設定します。
            このプロパティに値を設定すると、その値は DataLabelCollection のすべてのデータラベルの NumberFormat プロパティにも設定されます
            (例: "DataLabels.DefaultDataLabelFormat.NumberFormat = val;" はすべての DataLabels[i].NumberFormat を val に等しくします)。

### 定義:
```python
@property
def number_format(self):
    ...

@number_format.setter
def number_format(self, value):
    ...
```


### 参照
* クラス [`DataLabelFormat`](/slides/python-net/ja/aspose.slides.charts/datalabelformat)
* モジュール [`aspose.slides.charts`](/slides/python-net/ja/aspose.slides.charts)
* ライブラリ [`Aspose.Slides`](/slides/python-net)