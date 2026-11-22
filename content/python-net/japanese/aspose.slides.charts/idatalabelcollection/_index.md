---
title: IDataLabelCollection class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.charts/idatalabelcollection/
---
## IDataLabelCollection クラス

シリーズ ラベルを表します。

IDataLabelCollection 型は次のメンバーを公開します。

## プロパティ

| Property | Description |
| :- | :- |
| [`default_data_label_format`](/slides/python-net/ja/aspose.slides.charts/idatalabelcollection/default_data_label_format/) | コレクション内のすべてのデータ ラベルのデフォルト書式を返します。<br/>            読み取り専用 [`IDataLabelFormat`](/slides/python-net/ja/aspose.slides.charts/idatalabelformat). |
| [`leader_lines_format`](/slides/python-net/ja/aspose.slides.charts/idatalabelcollection/leader_lines_format/) | データ ラベルのリーダーライン書式を表します。<br/>            読み取り専用 [`IChartLinesFormat`](/slides/python-net/ja/aspose.slides.charts/ichartlinesformat). |
| [`is_visible`](/slides/python-net/ja/aspose.slides.charts/idatalabelcollection/is_visible/) | False の場合、デフォルトでデータ ラベルは表示されません (したがって DefaultDataLabelFormat プロパティのすべての Show*-フラグ (ShowValue, ...) が false になります)。<br/>            読み取り専用 **bool**. |
| [`count_of_visible_data_labels`](/slides/python-net/ja/aspose.slides.charts/idatalabelcollection/count_of_visible_data_labels/) | コレクション内の表示可能なデータ ラベルの数を取得します。<br/>            読み取り専用 **int**. |
| [`count`](/slides/python-net/ja/aspose.slides.charts/idatalabelcollection/count/) | コレクション内のすべてのデータ ラベルの数を取得します。<br/>            読み取り専用 **int**. |
| [`parent_series`](/slides/python-net/ja/aspose.slides.charts/idatalabelcollection/parent_series/) | 親チャート シリーズを返します。<br/>            読み取り専用 [`IChartSeries`](/slides/python-net/ja/aspose.slides.charts/ichartseries). |
| [`default_label_shape_type`](/slides/python-net/ja/aspose.slides.charts/idatalabelcollection/default_label_shape_type/) | データ ラベルのデフォルト シェイプ タイプを取得または設定します。<br/>            シェイプが定義されていない場合は [`ShapeType.NOT_DEFINED`](/slides/python-net/ja/aspose.slides/shapetype/NOT_DEFINED) を返します。 |
| [`chart`](/slides/python-net/ja/aspose.slides.charts/idatalabelcollection/chart/) |  |
| [`slide`](/slides/python-net/ja/aspose.slides.charts/idatalabelcollection/slide/) |  |
| [`presentation`](/slides/python-net/ja/aspose.slides.charts/idatalabelcollection/presentation/) |  |

指定したインデックスのデータ ポイントに対するデータ ラベルを取得します。

## インデクサー

| 名前 | 説明 |
| :- | :- |
| [`[index]`](/slides/python-net/ja/aspose.slides.charts/idatalabelcollection/__getitem__/) |  |

## メソッド

| Method | Description |
| :- | :- |
| [`hide(self)`](/slides/python-net/ja/aspose.slides.charts/idatalabelcollection/hide/#) | すべての Show*-flags (ShowValue, ...) を false に設定して、デフォルトでデータ ラベルを非表示にします。<br/>IsVisible はこの後 false になります。 |
| [`index_of(self, value)`](/slides/python-net/ja/aspose.slides.charts/idatalabelcollection/index_of/#idatalabel) | コレクション内の指定された DataLabel のインデックスを返します。 |

### 参照
* モジュール [`aspose.slides.charts`](/slides/python-net/ja/aspose.slides.charts)
* ライブラリ [`Aspose.Slides`](/slides/python-net)