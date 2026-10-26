---
title: DataLabel class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.charts/datalabel/
---
## DataLabel クラス

シリーズのラベルを表します。

DataLabel 型は次のメンバーを公開します：

## コンストラクタ

| コンストラクタ | 説明 |
| :- | :- |
| [`__init__(self, parent_immediate)`](/slides/python-net/ja/aspose.slides.charts/datalabel/__init__/#ichartdatapoint) | DataLabel クラスの新しいインスタンスを作成します。 |

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`chart`](/slides/python-net/ja/aspose.slides.charts/datalabel/chart/) | 親チャートを返します。<br/>            読み取り専用 [`IChart`](/slides/python-net/ja/aspose.slides.charts/ichart)。 |
| [`is_visible`](/slides/python-net/ja/aspose.slides.charts/datalabel/is_visible/) | False はデータラベルが表示されないことを意味します (そのためすべての Show*-フラグ (ShowValue, ...) は false になります)。<br/>            読み取り専用 **bool**。 |
| [`text_frame_for_overriding`](/slides/python-net/ja/aspose.slides.charts/datalabel/text_frame_for_overriding/) | リッチ書式テキストを含めることができます。このプロパティが None でない場合、この<br/>            書式テキストの値はデータラベルの自動生成テキストを上書きします。<br/>            データラベルの自動生成テキストとは、ShowSeriesName、<br/>            ShowValue、... プロパティによって管理され、TextFormatManager.TextFormat プロパティで書式設定されたテキストを指します。<br/>            読み取り専用 [`ITextFrame`](/slides/python-net/ja/aspose.slides/itextframe)。 |
| [`text_format`](/slides/python-net/ja/aspose.slides.charts/datalabel/text_format/) | テキスト書式を返します。<br/>            読み取り専用 [`IChartTextFormat`](/slides/python-net/ja/aspose.slides.charts/icharttextformat)。 |
| [`x`](/slides/python-net/ja/aspose.slides.charts/datalabel/x/) | タイトルの x 座標をチャートの幅の割合として取得または設定します。<br/>            読み書き **float**。 |
| [`y`](/slides/python-net/ja/aspose.slides.charts/datalabel/y/) | タイトルの y 座標をチャートの高さの割合として取得または設定します。<br/>            読み書き **float**。 |
| [`width`](/slides/python-net/ja/aspose.slides.charts/datalabel/width/) | タイトルの幅をチャートの幅の割合として取得または設定します。<br/>            読み書き **float**。 |
| [`height`](/slides/python-net/ja/aspose.slides.charts/datalabel/height/) | タイトルの高さをチャートの高さの割合として取得または設定します。<br/>            読み書き **float**。 |
| [`right`](/slides/python-net/ja/aspose.slides.charts/datalabel/right/) | 右。<br/>            読み取り専用 **float**。 |
| [`bottom`](/slides/python-net/ja/aspose.slides.charts/datalabel/bottom/) | 下。<br/>            読み取り専用 **float**。 |
| [`data_label_format`](/slides/python-net/ja/aspose.slides.charts/datalabel/data_label_format/) | データラベルの書式を返します。<br/>            読み取り専用 [`IDataLabelFormat`](/slides/python-net/ja/aspose.slides.charts/idatalabelformat)。 |
| [`value_from_cell`](/slides/python-net/ja/aspose.slides.charts/datalabel/value_from_cell/) | ワークブックのデータセルを取得または設定します。IDataLabelFormat.ShowLabelValueFromCell プロパティが true の場合に適用されます。 |
| [`actual_x`](/slides/python-net/ja/aspose.slides.charts/datalabel/actual_x/) | チャート要素の実際の x 位置（左）を、チャートの左上隅に対する相対位置で指定します。<br/>            実際の値を取得するには、事前に IChart.ValidateChartLayout() メソッドを呼び出してください。 <br/>            読み取り **float**。 |
| [`actual_y`](/slides/python-net/ja/aspose.slides.charts/datalabel/actual_y/) | チャート要素の実際の上端を、チャートの左上隅に対する相対位置で指定します。<br/>            実際の値を取得するには、事前に IChart.ValidateChartLayout() メソッドを呼び出してください。 <br/>            読み取り **float**。 |
| [`actual_width`](/slides/python-net/ja/aspose.slides.charts/datalabel/actual_width/) | チャート要素の実際の幅を指定します。実際の値を取得するには、事前に IChart.ValidateChartLayout() メソッドを呼び出してください。 <br/>            読み取り **float**。 |
| [`actual_height`](/slides/python-net/ja/aspose.slides.charts/datalabel/actual_height/) | チャート要素の実際の高さを指定します。実際の値を取得するには、事前に IChart.ValidateChartLayout() メソッドを呼び出してください。 <br/>            読み取り **float**。 |
| [`slide`](/slides/python-net/ja/aspose.slides.charts/datalabel/slide/) |  |
| [`presentation`](/slides/python-net/ja/aspose.slides.charts/datalabel/presentation/) |  |

## メソッド

| メソッド | 説明 |
| :- | :- |
| [`hide(self)`](/slides/python-net/ja/aspose.slides.charts/datalabel/hide/#) | すべての Show*-フラグ (ShowValue, ...) を false に設定してデータラベルを非表示にします。<br/>            これにより IsVisible は false になります。 |
| [`get_actual_label_text(self)`](/slides/python-net/ja/aspose.slides.charts/datalabel/get_actual_label_text/#) | DataLabelFormat の設定または TextFrameForOverriding.Text の値に基づく実際のラベルテキストを返します。 |
| [`add_text_frame_for_overriding(self, text)`](/slides/python-net/ja/aspose.slides.charts/datalabel/add_text_frame_for_overriding/#str) | パラメータ "text" のテキストで TextFrameForOverriding を初期化します。<br/>            すでに TextFrameForOverriding が初期化されている場合は、そのテキストを単に変更します。 |

### 参照
* モジュール [`aspose.slides.charts`](/slides/python-net/ja/aspose.slides.charts)
* ライブラリ [`Aspose.Slides`](/slides/python-net)