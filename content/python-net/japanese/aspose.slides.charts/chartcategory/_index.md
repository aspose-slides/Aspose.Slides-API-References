---
title: ChartCategory class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.charts/chartcategory/
---
## ChartCategory クラス

ChartCategory 型は次のメンバーを公開します。

## プロパティ

| Property | Description |
| :- | :- |
| [`use_cell`](/slides/python-net/ja/aspose.slides.charts/chartcategory/use_cell/) | true の場合、AsCell プロパティが有効です。言い換えると、worksheet は<br/>            カテゴリの保存に使用されます（このケースはマルチレベルカテゴリをサポートします）。<br/>            false の場合、AsLiteral プロパティが有効です。言い換えると、worksheet はカテゴリの保存に使用されません<br/>            （このケースはマルチレベルカテゴリをサポートしません）。<br/>            読み取り専用 **bool**。 |
| [`as_cell`](/slides/python-net/ja/aspose.slides.charts/chartcategory/as_cell/) | IChartDataCell オブジェクトを取得または設定します。<br/>            カテゴリがマルチレベルの場合、レベル "0" に IChartDataCell オブジェクトが使用されます。<br/>            読み書き可能 [`IChartDataCell`](/slides/python-net/ja/aspose.slides.charts/ichartdatacell)。 |
| [`as_literal`](/slides/python-net/ja/aspose.slides.charts/chartcategory/as_literal/) | AsLiteral オブジェクトを取得または設定します。<br/>            読み書き可能 **any**。 |
| [`value`](/slides/python-net/ja/aspose.slides.charts/chartcategory/value/) | UseCell が true の場合、このプロパティは AsCell.Value プロパティを表します。<br/>            UseCell が false の場合、このプロパティは AsLiteral プロパティを表します。<br/>            読み書き可能 **any**。 |
| [`grouping_levels`](/slides/python-net/ja/aspose.slides.charts/chartcategory/grouping_levels/) | チャートカテゴリのグルーピングレベルの値を管理するコンテナです。<br/>            マルチレベルカテゴリは複数のグルーピングレベルを含みます。<br/>            グルーピングレベルのインデックスはゼロベースです。<br/>            読み取り専用 [`IChartCategoryLevelsManager`](/slides/python-net/ja/aspose.slides.charts/ichartcategorylevelsmanager)。 |

## メソッド

| Method | Description |
| :- | :- |
| [`remove(self)`](/slides/python-net/ja/aspose.slides.charts/chartcategory/remove/#) | チャートからカテゴリを削除します。 |

### 参照
* モジュール [`aspose.slides.charts`](/slides/python-net/ja/aspose.slides.charts)
* ライブラリ [`Aspose.Slides`](/slides/python-net)