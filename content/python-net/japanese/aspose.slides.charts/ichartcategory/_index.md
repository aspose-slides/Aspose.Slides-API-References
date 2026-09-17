---
title: IChartCategory class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.charts/ichartcategory/
---
## IChartCategory クラス

チャートカテゴリを表します。

IChartCategory タイプは次のメンバーを公開します。

## プロパティ

| Property | 説明 |
| :- | :- |
| [`use_cell`](/slides/python-net/ja/aspose.slides.charts/ichartcategory/use_cell/) | true の場合、AsCell プロパティが実際のものになります。言い換えれば、ワークシートは <br/>            カテゴリの保存に使用されます（このケースではマルチレベルカテゴリをサポートします）。<br/>            false の場合、AsLiteral プロパティが実際のものになります。言い換えれば、ワークシートはカテゴリの保存に使用されません <br/>            （このケースではマルチレベルカテゴリをサポートしません）。<br/>            読み取り専用 **bool**. |
| [`as_cell`](/slides/python-net/ja/aspose.slides.charts/ichartcategory/as_cell/) | IChartDataCell オブジェクトを取得または設定します。<br/>            カテゴリがマルチレベルの場合、レベル "0" の IChartDataCell オブジェクトが使用されます。<br/>            読み書き [`IChartDataCell`](/slides/python-net/ja/aspose.slides.charts/ichartdatacell). |
| [`as_literal`](/slides/python-net/ja/aspose.slides.charts/ichartcategory/as_literal/) | UseCell が false の場合、AsLiteral を取得または設定します。<br/>            読み書き **any**. |
| [`value`](/slides/python-net/ja/aspose.slides.charts/ichartcategory/value/) | UseCell が true の場合、このプロパティは AsCell.Value プロパティを表します。<br/>            UseCell が false の場合、このプロパティは AsLiteral プロパティを表します。<br/>            読み書き **any**. |
| [`grouping_levels`](/slides/python-net/ja/aspose.slides.charts/ichartcategory/grouping_levels/) | チャートカテゴリのグループ化レベルの値を管理するコンテナです。<br/>            マルチレベルカテゴリは複数のグループ化レベルを含みます。<br/>            グループ化レベルのインデックスは 0 ベースです。<br/>            読み取り専用 [`IChartCategoryLevelsManager`](/slides/python-net/ja/aspose.slides.charts/ichartcategorylevelsmanager). |

## メソッド

| Method | 説明 |
| :- | :- |
| [`remove(self)`](/slides/python-net/ja/aspose.slides.charts/ichartcategory/remove/#) | チャートからカテゴリを削除します。 |

### 参照
* モジュール [`aspose.slides.charts`](/slides/python-net/ja/aspose.slides.charts)
* ライブラリ [`Aspose.Slides`](/slides/python-net)