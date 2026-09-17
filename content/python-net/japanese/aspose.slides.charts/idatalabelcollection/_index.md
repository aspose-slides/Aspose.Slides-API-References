---
title: IDataLabelCollection class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.charts/idatalabelcollection/
---
## IDataLabelCollection クラス

シリーズのラベルを表します。

IDataLabelCollection 型は次のメンバーを公開します:

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`default_data_label_format`](/slides/python-net/ja/aspose.slides.charts/idatalabelcollection/default_data_label_format/) | コレクション内のすべてのデータ ラベルのデフォルト フォーマットを返します。<br/>            読み取り専用 [`IDataLabelFormat`](/slides/python-net/ja/aspose.slides.charts/idatalabelformat)。 |
| [`leader_lines_format`](/slides/python-net/ja/aspose.slides.charts/idatalabelcollection/leader_lines_format/) | データ ラベルのリーダー ライン形式を表します。<br/>             読み取り専用 [`IChartLinesFormat`](/slides/python-net/ja/aspose.slides.charts/ichartlinesformat)。 |
| [`is_visible`](/slides/python-net/ja/aspose.slides.charts/idatalabelcollection/is_visible/) | False は、データ ラベルがデフォルトで表示されないことを意味します (そのため DefaultDataLabelFormat プロパティのすべての Show*-flags (ShowValue, ...) が false になります)。<br/>            読み取り専用 **bool**。 |
| [`count_of_visible_data_labels`](/slides/python-net/ja/aspose.slides.charts/idatalabelcollection/count_of_visible_data_labels/) | コレクション内の表示されているデータ ラベルの数を取得します。<br/>            読み取り専用 **int**。 |
| [`count`](/slides/python-net/ja/aspose.slides.charts/idatalabelcollection/count/) | コレクション内のすべてのデータ ラベルの数を取得します。<br/>            読み取り専用 **int**。 |
| [`parent_series`](/slides/python-net/ja/aspose.slides.charts/idatalabelcollection/parent_series/) | 親チャート シリーズを返します。<br/>            読み取り専用 [`IChartSeries`](/slides/python-net/ja/aspose.slides.charts/ichartseries)。 |
| [`chart`](/slides/python-net/ja/aspose.slides.charts/idatalabelcollection/chart/) |  |
| [`slide`](/slides/python-net/ja/aspose.slides.charts/idatalabelcollection/slide/) |  |
| [`presentation`](/slides/python-net/ja/aspose.slides.charts/idatalabelcollection/presentation/) |  |

指定されたインデックスのデータ ポイントのデータ ラベルを取得します。

## インデクサ

| 名前 | 説明 |
| :- | :- |
| [`[index]`](/slides/python-net/ja/aspose.slides.charts/idatalabelcollection/__getitem__/) |  |

## メソッド

| メソッド | 説明 |
| :- | :- |
| [`hide(self)`](/slides/python-net/ja/aspose.slides.charts/idatalabelcollection/hide/#) | すべての Show*-flags (ShowValue, ...) を <br/>            DefaultDataLabelFormat プロパティの false 状態に設定することで、デフォルトでデータ ラベルを非表示にします。<br/>            この後、IsVisible は false になります。 |
| [`index_of(self, value)`](/slides/python-net/ja/aspose.slides.charts/idatalabelcollection/index_of/#idatalabel) | コレクション内の指定された DataLabel のインデックスを返します。 |

### 参照
* モジュール [`aspose.slides.charts`](/slides/python-net/ja/aspose.slides.charts)
* ライブラリ [`Aspose.Slides`](/slides/python-net)