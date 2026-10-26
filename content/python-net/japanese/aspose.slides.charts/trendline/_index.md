---
title: Trendline class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.charts/trendline/
---
## Trendline クラス

クラスはチャート系列のトレンドラインを表します

The Trendline type exposes the following members:

## プロパティ

| Property | Description |
| :- | :- |
| [`trendline_name`](/slides/python-net/ja/aspose.slides.charts/trendline/trendline_name/) | トレンドラインの名前を取得または設定します。<br/>            読み書き **str**. |
| [`trendline_type`](/slides/python-net/ja/aspose.slides.charts/trendline/trendline_type/) | トレンドラインのタイプを取得または設定します。<br/>            読み書き [`TrendlineType`](/slides/python-net/ja/aspose.slides.charts/trendlinetype). |
| [`format`](/slides/python-net/ja/aspose.slides.charts/trendline/format/) | トレンドラインの書式を表します。<br/>            読み書き [`IFormat`](/slides/python-net/ja/aspose.slides.charts/iformat). |
| [`backward`](/slides/python-net/ja/aspose.slides.charts/trendline/backward/) | トレンドラインが伸びる前のカテゴリ数（散布図の場合は単位）を指定します。<br/>            トレンド対象の系列データの前です。散布図および非散布図では、値は非負の任意の値でなければなりません。<br/>            読み書き **float**. |
| [`forward`](/slides/python-net/ja/aspose.slides.charts/trendline/forward/) | トレンドラインが伸びる後のカテゴリ数（散布図の場合は単位）を指定します。<br/>            トレンド対象の系列データの後です。散布図および非散布図では、値は非負の任意の値でなければなりません。<br/>            読み書き **float**. |
| [`intercept`](/slides/python-net/ja/aspose.slides.charts/trendline/intercept/) | トレンドラインが y 軸と交差する位置の値を指定します。このプロパティは trendline タイプが exp、linear、または poly の場合にのみサポートされます。<br/>            読み書き **float**. |
| [`display_equation`](/slides/python-net/ja/aspose.slides.charts/trendline/display_equation/) | トレンドラインの方程式をチャートに表示するかどうかを指定します（Rsquaredvalue と同じラベルに）。<br/>            読み書き **bool**. |
| [`order`](/slides/python-net/ja/aspose.slides.charts/trendline/order/) | 多項式トレンドラインの次数を指定します。他のトレンドラインタイプでは無視されます。値は 2 から 6 の間でなければなりません。<br/>            読み書き **int**. |
| [`period`](/slides/python-net/ja/aspose.slides.charts/trendline/period/) | 移動平均トレンドラインの期間を指定します。他のトレンドラインのバリエーションでは無視されます。値は 2 から 255 の間でなければなりません。<br/>            読み書き **int**. |
| [`display_r_squared_value`](/slides/python-net/ja/aspose.slides.charts/trendline/display_r_squared_value/) | トレンドラインの決定係数 (R-squared) をチャートに表示するかどうかを指定します（方程式と同じラベルに）。<br/>            読み書き **bool**. |
| [`related_legend_entry`](/slides/python-net/ja/aspose.slides.charts/trendline/related_legend_entry/) | このトレンドラインに関連する凡例エントリを表します<br/>            読み取り専用 [`ILegendEntryProperties`](/slides/python-net/ja/aspose.slides.charts/ilegendentryproperties). |
| [`text_frame_for_overriding`](/slides/python-net/ja/aspose.slides.charts/trendline/text_frame_for_overriding/) | リッチテキスト形式を含めることができます。このプロパティが None でない場合、この<br/>            書式設定されたテキスト値はデータラベルの自動生成テキストを上書きします。<br/>            データラベルの自動生成テキストとは、ShowSeriesName、<br/>            ShowValue、... プロパティによって管理され、TextFormatManager.TextFormat プロパティで書式設定されるテキストを指します。<br/>            読み取り専用 [`ITextFrame`](/slides/python-net/ja/aspose.slides/itextframe). |
| [`text_format`](/slides/python-net/ja/aspose.slides.charts/trendline/text_format/) | テキスト書式を返します。<br/>            読み取り専用 [`IChartTextFormat`](/slides/python-net/ja/aspose.slides.charts/icharttextformat). |
| [`chart`](/slides/python-net/ja/aspose.slides.charts/trendline/chart/) | 親チャートを返します。<br/>            読み取り専用 [`IChart`](/slides/python-net/ja/aspose.slides.charts/ichart). |
| [`slide`](/slides/python-net/ja/aspose.slides.charts/trendline/slide/) |  |
| [`presentation`](/slides/python-net/ja/aspose.slides.charts/trendline/presentation/) |  |

## メソッド

| Method | Description |
| :- | :- |
| [`add_text_frame_for_overriding(self, text)`](/slides/python-net/ja/aspose.slides.charts/trendline/add_text_frame_for_overriding/#str) | パラメータ "text" のテキストで TextFrameForOverriding を初期化します。<br/>            既に TextFrameForOverriding が初期化されている場合は、そのテキストを単に変更します。 |

### 参照
* モジュール [`aspose.slides.charts`](/slides/python-net/ja/aspose.slides.charts)
* ライブラリ [`Aspose.Slides`](/slides/python-net)