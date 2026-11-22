---
title: ChartCategory class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.charts/chartcategory/
---
## ChartCategory クラス

チャートカテゴリを表します。

ChartCategory 型は以下のメンバーを公開します:

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`use_cell`](/slides/python-net/ja/aspose.slides.charts/chartcategory/use_cell/) | true の場合、AsCell プロパティが実際の値となります。言い換えれば、ワークシートは <br/>            カテゴリの保存に使用されます（この場合はマルチレベルカテゴリをサポート）。<br/>            false の場合、AsLiteral プロパティが実際の値となります。言い換えれば、ワークシートはカテゴリの保存に使用されず <br/>            （この場合はマルチレベルカテゴリをサポートしません）。<br/>            読み取り専用 **bool**。 |
| [`as_cell`](/slides/python-net/ja/aspose.slides.charts/chartcategory/as_cell/) | IChartDataCell オブジェクトを取得または設定します。<br/>            カテゴリがマルチレベルの場合、レベル "0" に IChartDataCell オブジェクトが使用されます。<br/>            読み書き [`IChartDataCell`](/slides/python-net/ja/aspose.slides.charts/ichartdatacell)。 |
| [`as_literal`](/slides/python-net/ja/aspose.slides.charts/chartcategory/as_literal/) | AsLiteral オブジェクトを取得または設定します。<br/>            読み書き **any**。 |
| [`value`](/slides/python-net/ja/aspose.slides.charts/chartcategory/value/) | UseCell が true の場合、このプロパティは AsCell.Value プロパティを表します。<br/>            UseCell が false の場合、このプロパティは AsLiteral プロパティを表します。<br/>            読み書き **any**。 |
| [`grouping_levels`](/slides/python-net/ja/aspose.slides.charts/chartcategory/grouping_levels/) | チャートカテゴリのグループ化レベルの値を管理するコンテナです。<br/>            マルチレベルカテゴリは複数のグループ化レベルを含みます。<br/>            グループ化レベルのインデックスはゼロベースです。<br/>            読み取り専用 [`IChartCategoryLevelsManager`](/slides/python-net/ja/aspose.slides.charts/ichartcategorylevelsmanager)。 |
| [`cached_value`](/slides/python-net/ja/aspose.slides.charts/chartcategory/cached_value/) | チャートカテゴリのキャッシュされた値を取得します。<br/>            読み取り専用 [`ICachedChartValue`](/slides/python-net/ja/aspose.slides.charts/icachedchartvalue)。 |

## メソッド

| メソッド | 説明 |
| :- | :- |
| [`remove(self)`](/slides/python-net/ja/aspose.slides.charts/chartcategory/remove/#) | チャートからカテゴリを削除します。 |

### 参照
* モジュール [`aspose.slides.charts`](/slides/python-net/ja/aspose.slides.charts)
* ライブラリ [`Aspose.Slides`](/slides/python-net)