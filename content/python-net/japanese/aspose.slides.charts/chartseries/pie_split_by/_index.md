---
title: pie_split_by property
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.charts/chartseries/pie_split_by/
weight: 340
---
## pie_split_by プロパティ
どのデータポイントが第2のパイまたはバーに
            pie-of-pie または bar-of-pie チャートに含まれるかを決定する方法を指定します。
            このプロパティはこのシリーズだけでなく、すべての親シリーズ
            グループのシリーズにも適用されます - これは適切なグループプロパティの投影です。したがってこのプロパティ
            は読み取り専用です。
            ParentSeriesGroup プロパティを使用して、親シリーズグループにアクセスします。
            ParentSeriesGroup.PieSplitBy 読み取り/書き込み プロパティを使用して値を変更します。
            読み取り専用 [`PieSplitType`](/slides/python-net/ja/aspose.slides.charts/piesplittype)。


### 備考

1) これはプロパティ ParentSeriesGroup.PieSplitBy の投影です。
            2) プロパティの値が PieSplitType.Custom の場合、カスタム分割を定義できます
            ParentSeriesGroup.PieSplitCustomPoints プロパティを使用して情報を指定します。

### 定義:
```python
@property
def pie_split_by(self):
    ...
```


### 参照
* クラス [`ChartSeries`](/slides/python-net/ja/aspose.slides.charts/chartseries)
* 列挙 [`PieSplitType`](/slides/python-net/ja/aspose.slides.charts/piesplittype)
* モジュール [`aspose.slides.charts`](/slides/python-net/ja/aspose.slides.charts)
* ライブラリ [`Aspose.Slides`](/slides/python-net)