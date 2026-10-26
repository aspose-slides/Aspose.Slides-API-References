---
title: show_percentage property
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.charts/datalabelformat/show_percentage/
weight: 180
---
## show_percentage プロパティ
指定されたチャートのデータラベルのパーセンテージ値の表示動作を表します。  
True はパーセンテージ値を表示し、False は非表示にします。  
読み書き **bool**。

### 備考

この DataLabelFormat オブジェクトの親がデータラベルの DataLabelCollection コレクションである場合、この
            property は DataLabelCollection コレクション内の新しいデータラベルに対する ShowPercentage プロパティのデフォルト値を取得または設定します。
            この property に値を設定すると、DataLabelCollection コレクション内のすべてのデータラベルの ShowPercentage プロパティにも同じ値が設定されます
            (例: "DataLabels.DefaultDataLabelFormat.ShowPercentage = val;" により、すべての DataLabels[i].ShowPercentage が val と等しくなります)。

### 定義:
```python
@property
def show_percentage(self):
    ...

@show_percentage.setter
def show_percentage(self, value):
    ...
```

### 参照
* クラス [`DataLabelFormat`](/slides/python-net/ja/aspose.slides.charts/datalabelformat)
* モジュール [`aspose.slides.charts`](/slides/python-net/ja/aspose.slides.charts)
* ライブラリ [`Aspose.Slides`](/slides/python-net)