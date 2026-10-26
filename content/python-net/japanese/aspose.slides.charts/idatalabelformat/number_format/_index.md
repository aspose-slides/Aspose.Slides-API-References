---
title: number_format property
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.charts/idatalabelformat/number_format/
weight: 80
---
## number_format プロパティ
DataLabels オブジェクトの書式文字列を表します。
            読み取り/書き込み **str**.


### 備考

この DataLabelFormat オブジェクトの親が DataLabelCollection コレクションである場合、この
            プロパティは DataLabelCollection コレクション内の新しいデータ
            ラベルの NumberFormat プロパティの既定値を取得または設定します。
            このプロパティに値を設定すると、その値は DataLabelCollection コレクション内のすべてのデータ ラベルの NumberFormat プロパティにも設定されます
            (i.e. "DataLabels.DefaultDataLabelFormat.NumberFormat = val;" causes all DataLabels[i].NumberFormat to equal to val).

### 定義:
```python
@property
def number_format(self):
    ...

@number_format.setter
def number_format(self, value):
    ...
```


### 関連項目
* クラス [`IDataLabelFormat`](/slides/python-net/ja/aspose.slides.charts/idatalabelformat)
* モジュール [`aspose.slides.charts`](/slides/python-net/ja/aspose.slides.charts)
* ライブラリ [`Aspose.Slides`](/slides/python-net)