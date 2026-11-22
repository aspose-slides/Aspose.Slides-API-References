---
title: IChartCategory class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.charts/ichartcategory/
---
## IChartCategory クラス

チャートのカテゴリを表します。

IChartCategory 型は次のメンバーを公開します。

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`use_cell`](/slides/python-net/ja/aspose.slides.charts/ichartcategory/use_cell/) | true の場合、AsCell プロパティが有効になります。つまり、ワークシートはカテゴリの保存に使用されます（この場合はマルチレベルカテゴリをサポートします）。<br/>false の場合、AsLiteral プロパティが有効になります。つまり、ワークシートはカテゴリの保存に使用されません（この場合はマルチレベルカテゴリをサポートしません）。<br/>Read-only **bool**. |
| [`as_cell`](/slides/python-net/ja/aspose.slides.charts/ichartcategory/as_cell/) | IChartDataCell オブジェクトを取得または設定します。<br/>カテゴリがマルチレベルの場合、レベル "0" 用に IChartDataCell オブジェクトが使用されます。<br/>Read/write [`IChartDataCell`](/slides/python-net/ja/aspose.slides.charts/ichartdatacell). |
| [`as_literal`](/slides/python-net/ja/aspose.slides.charts/ichartcategory/as_literal/) | UseCell が false の場合、AsLiteral を取得または設定します。<br/>Read/write **any**. |
| [`value`](/slides/python-net/ja/aspose.slides.charts/ichartcategory/value/) | UseCell が true の場合、このプロパティは AsCell.Value プロパティを表します。<br/>UseCell が false の場合、このプロパティは AsLiteral プロパティを表します。<br/>Read/write **any**. |
| [`cached_value`](/slides/python-net/ja/aspose.slides.charts/ichartcategory/cached_value/) | チャートカテゴリのキャッシュされた値を取得します。<br/>Read-only [`ICachedChartValue`](/slides/python-net/ja/aspose.slides.charts/icachedchartvalue). |
| [`grouping_levels`](/slides/python-net/ja/aspose.slides.charts/ichartcategory/grouping_levels/) | チャートカテゴリのグルーピングレベルの値を管理するコンテナです。<br/>マルチレベルカテゴリは複数のグルーピングレベルを含みます。<br/>グルーピングレベルのインデックスは 0 から始まります。<br/>Read-only [`IChartCategoryLevelsManager`](/slides/python-net/ja/aspose.slides.charts/ichartcategorylevelsmanager). |

## メソッド

| メソッド | 説明 |
| :- | :- |
| [`remove(self)`](/slides/python-net/ja/aspose.slides.charts/ichartcategory/remove/#) | チャートからカテゴリを削除します。 |

### 参照
* モジュール [`aspose.slides.charts`](/slides/python-net/ja/aspose.slides.charts)
* ライブラリ [`Aspose.Slides`](/slides/python-net)