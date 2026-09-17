---
title: show_series_name property
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.charts/datalabelformat/show_series_name/
weight: 190
---
## show_series_name プロパティ
チャート上のデータ ラベルに対するシリーズ名の表示動作を示す Boolean を取得または設定します。 
            True を指定するとシリーズ名を表示します。 False を指定すると非表示にします。
            読み書き可能 **bool**.

### 備考

この DataLabelFormat オブジェクトの親がデータラベルの DataLabelCollection コレクションである場合、この
            プロパティは DataLabelCollection コレクション内の新しいデータラベルに対する ShowSeriesName プロパティの既定値を取得または設定します。
            このプロパティに値を設定すると、DataLabelCollection コレクション内のすべてのデータラベルの ShowSeriesName プロパティにも同じ値が設定されます
            (例: "DataLabels.DefaultDataLabelFormat.ShowSeriesName = val;" とすると
            すべての DataLabels[i].ShowSeriesName が val と等しくなります)。

### 定義:
```python
@property
def show_series_name(self):
    ...

@show_series_name.setter
def show_series_name(self, value):
    ...
```

### 参照
* クラス [`DataLabelFormat`](/slides/python-net/ja/aspose.slides.charts/datalabelformat)
* モジュール [`aspose.slides.charts`](/slides/python-net/ja/aspose.slides.charts)
* ライブラリ [`Aspose.Slides`](/slides/python-net)