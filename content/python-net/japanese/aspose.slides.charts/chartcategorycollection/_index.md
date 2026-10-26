---
title: ChartCategoryCollection class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.charts/chartcategorycollection/
---
## ChartCategoryCollection クラス

[`ChartCategory`](/slides/python-net/ja/aspose.slides.charts/chartcategory) のコレクションを表します。

The ChartCategoryCollection type exposes the following members:

## プロパティ

| Property | 説明 |
| :- | :- |
| [`use_cells`](/slides/python-net/ja/aspose.slides.charts/chartcategorycollection/use_cells/) | true の場合、ワークシートがカテゴリの保存に使用されます（このケースは多階層カテゴリをサポートします）。<br/>            false の場合、ワークシートは値の保存に使用されません（このケースは多階層カテゴリをサポートしません）。<br/>            読み取り/書き込み **bool**。 |
| [`grouping_level_count`](/slides/python-net/ja/aspose.slides.charts/chartcategorycollection/grouping_level_count/) | 使用されているカテゴリ グループ化レベルの数を返します。<br/>            多階層カテゴリの場合は 1 より大きくなります。<br/>            読み取り専用 **int**。 |

指定されたインデックスの要素を取得します。

## インデクサ

| 名前 | 説明 |
| :- | :- |
| [`[index]`](/slides/python-net/ja/aspose.slides.charts/chartcategorycollection/__getitem__/) |  |

## メソッド

| メソッド | 説明 |
| :- | :- |
| [`add(self, chart_data_cell)`](/slides/python-net/ja/aspose.slides.charts/chartcategorycollection/add/#ichartdatacell) | コレクションにカテゴリが存在する場合はそれを返します。<br/>            それ以外の場合、[`IChartDataCell`](/slides/python-net/ja/aspose.slides.charts/ichartdatacell) から新しいチャートカテゴリを作成し、コレクションに追加します。 |
| [`add(self, value)`](/slides/python-net/ja/aspose.slides.charts/chartcategorycollection/add/#any) | 値から新しい [`ChartCategory`](/slides/python-net/ja/aspose.slides.charts/chartcategory) を作成し、コレクションに追加します。 |
| [`index_of(self, value)`](/slides/python-net/ja/aspose.slides.charts/chartcategorycollection/index_of/#ichartcategory) | 指定された [`ChartCategory`](/slides/python-net/ja/aspose.slides.charts/chartcategory) を検索し、コレクション全体で最初に見つかった位置のゼロベースインデックスを返します。 |
| [`remove(self, value)`](/slides/python-net/ja/aspose.slides.charts/chartcategorycollection/remove/#ichartcategory) | 指定された値を削除します。 |
| [`remove_at(self, index)`](/slides/python-net/ja/aspose.slides.charts/chartcategorycollection/remove_at/#int) | 指定されたインデックスの要素を削除します。 |
| [`clear(self)`](/slides/python-net/ja/aspose.slides.charts/chartcategorycollection/clear/#) | コレクションからすべての要素を削除します。 |


### 参照
* クラス [`ChartCategory`](/slides/python-net/ja/aspose.slides.charts/chartcategory)
* モジュール [`aspose.slides.charts`](/slides/python-net/ja/aspose.slides.charts)
* ライブラリ [`Aspose.Slides`](/slides/python-net)