---
title: overlap property
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.charts/ichartseries/overlap/
weight: 310
---
## 重なりプロパティ
2-D チャートの棒と列がどれだけ重なるかをパーセンテージ（-100% から 100%）で指定します。
            このプロパティはこのシリーズだけでなく、親シリーズグループのすべてのシリーズに適用されます。
            親シリーズグループの該当プロパティの投影であり、このプロパティは読み取り専用です。
            値を変更するには、ParentSeriesGroup.Overlap の読み書きプロパティを使用します。
            読み取り専用 **int**.

### 備考

重なりは、棒や列の幅に対するパーセンテージで、重なり具合または間隔を指定します。
            - -100%: 最大の間隔（棒が完全に分離されます）。
            - 0%: 棒が重なりも間隔もなく並びます。
            - 100%: 最大の重なり（棒が互いに完全に重なります）。
            これはプロパティ ParentSeriesGroup.Overlap の投影です。

### 定義:
```python
@property
def overlap(self):
    ...
```

### 参照
* クラス [`IChartSeries`](/slides/python-net/ja/aspose.slides.charts/ichartseries)
* モジュール [`aspose.slides.charts`](/slides/python-net/ja/aspose.slides.charts)
* ライブラリ [`Aspose.Slides`](/slides/python-net)