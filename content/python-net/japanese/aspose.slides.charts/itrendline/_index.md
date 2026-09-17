---
title: ITrendline class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.charts/itrendline/
---
## ITrendline クラス

Class represents trend line of chart series

The ITrendline type exposes the following members:

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`trendline_name`](/slides/python-net/ja/aspose.slides.charts/itrendline/trendline_name/) | trendline の名前を取得または設定します。<br/>            読み書き可能 **str**. |
| [`trendline_type`](/slides/python-net/ja/aspose.slides.charts/itrendline/trendline_type/) | trend line のタイプを取得または設定します。<br/>            読み書き可能 [`ITrendline.trendline_type`](/slides/python-net/ja/aspose.slides.charts/itrendline/trendline_type). |
| [`format`](/slides/python-net/ja/aspose.slides.charts/itrendline/format/) | trend line の書式を表します。<br/>            読み書き可能 [`IFormat`](/slides/python-net/ja/aspose.slides.charts/iformat). |
| [`backward`](/slides/python-net/ja/aspose.slides.charts/itrendline/backward/) | trend line がトレンド対象の系列データの前に伸びるカテゴリ数（または散布図の単位）を指定します。<br/>            散布図および非散布図では、値は任意の非負の数である必要があります。<br/>            読み書き可能 **float**. |
| [`forward`](/slides/python-net/ja/aspose.slides.charts/itrendline/forward/) | trendline がトレンド対象の系列データの後に伸びるカテゴリ数（または散布図の単位）を指定します。<br/>            散布図および非散布図では、値は任意の非負の数である必要があります。<br/>            読み書き可能 **float**. |
| [`intercept`](/slides/python-net/ja/aspose.slides.charts/itrendline/intercept/) | trendline が y 軸と交差する位置の値を指定します。このプロパティは trendline のタイプが exp、linear、または poly の場合にのみサポートされます。<br/>            読み書き可能 **float**. |
| [`display_equation`](/slides/python-net/ja/aspose.slides.charts/itrendline/display_equation/) | trendline の方程式がチャート上（Rsquaredvalue と同じラベルに）表示されるかどうかを指定します。<br/>            読み書き可能 **bool**. |
| [`order`](/slides/python-net/ja/aspose.slides.charts/itrendline/order/) | 多項式 trend line の次数を指定します。他の trend line のタイプでは無視されます。値は 2 から 6 の間でなければなりません。<br/>            読み書き可能 **int**. |
| [`period`](/slides/python-net/ja/aspose.slides.charts/itrendline/period/) | 移動平均 trend line の期間を指定します。他の trend line のバリエーションでは無視されます。値は 2 から 255 の間でなければなりません。<br/>            読み書き可能 **int**. |
| [`display_r_squared_value`](/slides/python-net/ja/aspose.slides.charts/itrendline/display_r_squared_value/) | trendline の R 二乗値がチャート上（方程式と同じラベルに）表示されるかどうかを指定します。<br/>            読み書き可能 **bool**. |
| [`related_legend_entry`](/slides/python-net/ja/aspose.slides.charts/itrendline/related_legend_entry/) | この trendline に関連する凡例エントリを表します。<br/>            読み取り専用 [`ILegendEntryProperties`](/slides/python-net/ja/aspose.slides.charts/ilegendentryproperties). |
| [`text_frame_for_overriding`](/slides/python-net/ja/aspose.slides.charts/itrendline/text_frame_for_overriding/) |  |
| [`text_format`](/slides/python-net/ja/aspose.slides.charts/itrendline/text_format/) |  |
| [`chart`](/slides/python-net/ja/aspose.slides.charts/itrendline/chart/) |  |
| [`slide`](/slides/python-net/ja/aspose.slides.charts/itrendline/slide/) |  |
| [`presentation`](/slides/python-net/ja/aspose.slides.charts/itrendline/presentation/) |  |

## メソッド

| メソッド | 説明 |
| :- | :- |
| [`add_text_frame_for_overriding(self, text)`](/slides/python-net/ja/aspose.slides.charts/itrendline/add_text_frame_for_overriding/#str) |  |

### 関連項目
* モジュール [`aspose.slides.charts`](/slides/python-net/ja/aspose.slides.charts)
* ライブラリ [`Aspose.Slides`](/slides/python-net)