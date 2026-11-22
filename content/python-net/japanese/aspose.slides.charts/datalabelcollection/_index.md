---
title: DataLabelCollection class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.charts/datalabelcollection/
---
## DataLabelCollection クラス

シリーズ ラベルを表します。

DataLabelCollection 型は次のメンバーを公開します：

## プロパティ

| Property | Description |
| :- | :- |
| [`chart`](/slides/python-net/ja/aspose.slides.charts/datalabelcollection/chart/) | 親チャートを返します。<br/>            読み取り専用 [`IChart`](/slides/python-net/ja/aspose.slides.charts/ichart). |
| [`is_visible`](/slides/python-net/ja/aspose.slides.charts/datalabelcollection/is_visible/) | False はデフォルトでデータ ラベルが表示されないことを意味します (したがって DefaultDataLabelFormat プロパティのすべての Show*-フラグ (ShowValue, ...) が false です)。<br/>            読み取り専用 **bool**. |
| [`count_of_visible_data_labels`](/slides/python-net/ja/aspose.slides.charts/datalabelcollection/count_of_visible_data_labels/) | コレクション内の表示されているデータ ラベルの数を取得します。<br/>            読み取り専用 **int**. |
| [`count`](/slides/python-net/ja/aspose.slides.charts/datalabelcollection/count/) | コレクション内のすべてのデータ ラベルの数を取得します。<br/>            読み取り専用 **int**. |
| [`default_data_label_format`](/slides/python-net/ja/aspose.slides.charts/datalabelcollection/default_data_label_format/) | デフォルトのデータ ラベル形式を取得します。<br/>            読み取り専用 [`IDataLabelFormat`](/slides/python-net/ja/aspose.slides.charts/idatalabelformat). |
| [`leader_lines_format`](/slides/python-net/ja/aspose.slides.charts/datalabelcollection/leader_lines_format/) | データ ラベルのリーダー線形式を表します。<br/>             読み取り専用 [`IChartLinesFormat`](/slides/python-net/ja/aspose.slides.charts/ichartlinesformat). |
| [`parent_series`](/slides/python-net/ja/aspose.slides.charts/datalabelcollection/parent_series/) | 親シリーズを取得します。<br/>            読み取り専用 [`IChartSeries`](/slides/python-net/ja/aspose.slides.charts/ichartseries). |
| [`default_label_shape_type`](/slides/python-net/ja/aspose.slides.charts/datalabelcollection/default_label_shape_type/) | データ ラベルのデフォルトのシェイプ タイプを取得または設定します。<br/>             シェイプが定義されていない場合は [`ShapeType.NOT_DEFINED`](/slides/python-net/ja/aspose.slides/shapetype/NOT_DEFINED) を返します。 |
| [`slide`](/slides/python-net/ja/aspose.slides.charts/datalabelcollection/slide/) |  |
| [`presentation`](/slides/python-net/ja/aspose.slides.charts/datalabelcollection/presentation/) |  |

指定されたインデックスのデータ ポイントに対するデータ ラベルを取得します。

## インデクサ

| Name | Description |
| :- | :- |
| [`[index]`](/slides/python-net/ja/aspose.slides.charts/datalabelcollection/__getitem__/) |  |

## メソッド

| Method | Description |
| :- | :- |
| [`hide(self)`](/slides/python-net/ja/aspose.slides.charts/datalabelcollection/hide/#) | すべての Show*-フラグ (ShowValue, ...) を false に設定することで、データ ラベルをデフォルトで非表示にします。<br/>            これにより DefaultDataLabelFormat プロパティが false 状態になります。<br/>            この後 IsVisible は false になります. |
| [`index_of(self, value)`](/slides/python-net/ja/aspose.slides.charts/datalabelcollection/index_of/#idatalabel) | コレクション内の指定された DataLabel のインデックスを返します. |

### 参照
* モジュール [`aspose.slides.charts`](/slides/python-net/ja/aspose.slides.charts)
* ライブラリ [`Aspose.Slides`](/slides/python-net)