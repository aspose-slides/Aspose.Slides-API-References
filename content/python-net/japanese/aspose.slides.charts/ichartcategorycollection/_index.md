---
title: IChartCategoryCollection class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.charts/ichartcategorycollection/
---
## IChartCategoryCollection クラス

[`IChartCategory`](/slides/python-net/ja/aspose.slides.charts/ichartcategory) のコレクションを表します。

IChartCategoryCollection 型は次のメンバーを公開します。

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`use_cells`](/slides/python-net/ja/aspose.slides.charts/ichartcategorycollection/use_cells/) | true の場合、ワークシートはカテゴリの保存に使用されます（このケースはマルチレベルのカテゴリをサポートします）。<br/>            false の場合、ワークシートは値の保存に使用されません（このケースはマルチレベルのカテゴリをサポートしません）。<br/>            読み書き可能 **bool**。 |
| [`grouping_level_count`](/slides/python-net/ja/aspose.slides.charts/ichartcategorycollection/grouping_level_count/) | 使用されているカテゴリ グルーピングレベルの数を返します。<br/>            マルチレベルのカテゴリでは 1 以上です。<br/>            読み取り専用 **int**。 |

指定されたインデックスの要素を取得します。

## インデクサ

| 名前 | 説明 |
| :- | :- |
| [`[index]`](/slides/python-net/ja/aspose.slides.charts/ichartcategorycollection/__getitem__/) |  |

## メソッド

| メソッド | 説明 |
| :- | :- |
| [`add(self, chart_data_cell)`](/slides/python-net/ja/aspose.slides.charts/ichartcategorycollection/add/#ichartdatacell) | コレクションにカテゴリが存在する場合、返します。<br/>            それ以外の場合、[`IChartDataCell`](/slides/python-net/ja/aspose.slides.charts/ichartdatacell) から新しいチャートカテゴリを作成し、コレクションに追加します。 |
| [`add(self, value)`](/slides/python-net/ja/aspose.slides.charts/ichartcategorycollection/add/#any) | 値から新しい [`IChartCategory`](/slides/python-net/ja/aspose.slides.charts/ichartcategory) を作成し、コレクションに追加します。 |
| [`index_of(self, value)`](/slides/python-net/ja/aspose.slides.charts/ichartcategorycollection/index_of/#ichartcategory) | 指定された [`IChartCategory`](/slides/python-net/ja/aspose.slides.charts/ichartcategory) を検索し、コレクション全体で最初に見つかった位置のゼロベースインデックスを返します。 |
| [`remove(self, value)`](/slides/python-net/ja/aspose.slides.charts/ichartcategorycollection/remove/#ichartcategory) | 指定された値を削除します。 |
| [`remove_at(self, index)`](/slides/python-net/ja/aspose.slides.charts/ichartcategorycollection/remove_at/#int) | 指定されたインデックスの要素を削除します。 |
| [`clear(self)`](/slides/python-net/ja/aspose.slides.charts/ichartcategorycollection/clear/#) | コレクションからすべての要素を削除します。 |

### 参照
* クラス [`IChartCategory`](/slides/python-net/ja/aspose.slides.charts/ichartcategory)
* モジュール [`aspose.slides.charts`](/slides/python-net/ja/aspose.slides.charts)
* ライブラリ [`Aspose.Slides`](/slides/python-net)