---
title: DataLabelCollection class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.charts/datalabelcollection/
---
## DataLabelCollection クラス

シリーズのラベルを表します。

DataLabelCollection 型は次のメンバーを公開します。

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`chart`](/slides/python-net/ja/aspose.slides.charts/datalabelcollection/chart/) | 親チャートを返します。<br/>            読み取り専用 [`IChart`](/slides/python-net/ja/aspose.slides.charts/ichart)。 |
| [`is_visible`](/slides/python-net/ja/aspose.slides.charts/datalabelcollection/is_visible/) | False は、データラベルがデフォルトで表示されないことを意味します（そのため、DefaultDataLabelFormat プロパティのすべての Show*-フラグ (ShowValue, ...) が false になります）。<br/>            読み取り専用 **bool**。 |
| [`count_of_visible_data_labels`](/slides/python-net/ja/aspose.slides.charts/datalabelcollection/count_of_visible_data_labels/) | コレクション内の表示されているデータラベルの数を取得します。<br/>            読み取り専用 **int**。 |
| [`count`](/slides/python-net/ja/aspose.slides.charts/datalabelcollection/count/) | コレクション内のすべてのデータラベルの数を取得します。<br/>            読み取り専用 **int**。 |
| [`default_data_label_format`](/slides/python-net/ja/aspose.slides.charts/datalabelcollection/default_data_label_format/) | デフォルトのデータラベル形式を取得します。<br/>            読み取り専用 [`IDataLabelFormat`](/slides/python-net/ja/aspose.slides.charts/idatalabelformat)。 |
| [`leader_lines_format`](/slides/python-net/ja/aspose.slides.charts/datalabelcollection/leader_lines_format/) | データラベルのリーダーライン形式を表します。<br/>             読み取り専用 [`IChartLinesFormat`](/slides/python-net/ja/aspose.slides.charts/ichartlinesformat)。 |
| [`parent_series`](/slides/python-net/ja/aspose.slides.charts/datalabelcollection/parent_series/) | 親シリーズを取得します。<br/>            読み取り専用 [`IChartSeries`](/slides/python-net/ja/aspose.slides.charts/ichartseries)。 |
| [`slide`](/slides/python-net/ja/aspose.slides.charts/datalabelcollection/slide/) |  |
| [`presentation`](/slides/python-net/ja/aspose.slides.charts/datalabelcollection/presentation/) |  |

指定されたインデックスを持つデータポイントのデータラベルを取得します。

## インデクサ

| 名前 | 説明 |
| :- | :- |
| [`[index]`](/slides/python-net/ja/aspose.slides.charts/datalabelcollection/__getitem__/) |  |

## メソッド

| メソッド | 説明 |
| :- | :- |
| [`hide(self)`](/slides/python-net/ja/aspose.slides.charts/datalabelcollection/hide/#) | データラベルをデフォルトで非表示にするには、DefaultDataLabelFormat プロパティのすべての Show*-フラグ (ShowValue, ...) を false の状態に設定します。<br/>            この後、IsVisible は false になります。 |
| [`index_of(self, value)`](/slides/python-net/ja/aspose.slides.charts/datalabelcollection/index_of/#idatalabel) | コレクション内の指定された DataLabel のインデックスを返します。 |

### 参照
* モジュール [`aspose.slides.charts`](/slides/python-net/ja/aspose.slides.charts)
* ライブラリ [`Aspose.Slides`](/slides/python-net)