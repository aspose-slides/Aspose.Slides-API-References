---
title: IChartData class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.charts/ichartdata/
---
## IChartData クラス

Represents data used for a chart plotting.

The IChartData type exposes the following members:

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`chart_data_workbook`](/slides/python-net/ja/aspose.slides.charts/ichartdata/chart_data_workbook/) | チャートの系列またはカテゴリで使用されるセルを作成するためのセルファクトリを取得します。<br/>            読み取り専用 [`IChartDataWorkbook`](/slides/python-net/ja/aspose.slides.charts/ichartdataworkbook)。 |
| [`series`](/slides/python-net/ja/aspose.slides.charts/ichartdata/series/) | 系列を取得します。<br/>            読み取り専用 [`IChartSeriesCollection`](/slides/python-net/ja/aspose.slides.charts/ichartseriescollection)。 |
| [`series_groups`](/slides/python-net/ja/aspose.slides.charts/ichartdata/series_groups/) | 系列のグループを取得します。<br/>            読み取り専用 [`IChartSeriesGroupCollection`](/slides/python-net/ja/aspose.slides.charts/ichartseriesgroupcollection)。 |
| [`categories`](/slides/python-net/ja/aspose.slides.charts/ichartdata/categories/) | プライマリカテゴリを取得します（[`IChartData.use_secondary_categories`](/slides/python-net/ja/aspose.slides.charts/ichartdata/use_secondary_categories) プロパティが false の場合、プライマリとセカンダリの両方のカテゴリを取得します）。<br/>            読み取り専用 [`IChartCategoryCollection`](/slides/python-net/ja/aspose.slides.charts/ichartcategorycollection)。 |
| [`use_secondary_categories`](/slides/python-net/ja/aspose.slides.charts/ichartdata/use_secondary_categories/) | false の場合、[`IChartData.secondary_categories`](/slides/python-net/ja/aspose.slides.charts/ichartdata/secondary_categories) プロパティは None を返し、[`IChartData.categories`](/slides/python-net/ja/aspose.slides.charts/ichartdata/categories) プロパティのデータはプライマリとセカンダリの系列の両方に使用されます。<br/>            true の場合、[`IChartData.secondary_categories`](/slides/python-net/ja/aspose.slides.charts/ichartdata/secondary_categories) プロパティのデータはセカンダリ系列に、[`IChartData.categories`](/slides/python-net/ja/aspose.slides.charts/ichartdata/categories) プロパティのデータはプライマリ系列に使用されます。<br/>            読み書き可能 **bool**。 |
| [`secondary_categories`](/slides/python-net/ja/aspose.slides.charts/ichartdata/secondary_categories/) | [`IChartData.use_secondary_categories`](/slides/python-net/ja/aspose.slides.charts/ichartdata/use_secondary_categories) プロパティが true の場合、セカンダリカテゴリを取得します。<br/>            読み取り専用 [`IChartCategoryCollection`](/slides/python-net/ja/aspose.slides.charts/ichartcategorycollection)。 |
| [`data_source_type`](/slides/python-net/ja/aspose.slides.charts/ichartdata/data_source_type/) | チャートのデータソースを表します。 |
| [`external_workbook_path`](/slides/python-net/ja/aspose.slides.charts/ichartdata/external_workbook_path/) | データソースが外部の場合の外部ブックパスを表します。そうでない場合は None です。 |
| [`embedded_workbook_type`](/slides/python-net/ja/aspose.slides.charts/ichartdata/embedded_workbook_type/) | 埋め込みブックのタイプを取得します。<br/>            [`IChartData.data_source_type`](/slides/python-net/ja/aspose.slides.charts/ichartdata/data_source_type) が [`ChartDataSourceType.EXTERNAL_WORKBOOK`](/slides/python-net/ja/aspose.slides.charts/chartdatasourcetype/EXTERNAL_WORKBOOK) の場合、[`WorkbookType.NOT_DEFINED`](/slides/python-net/ja/aspose.slides.charts/workbooktype/NOT_DEFINED) を返します。<br/>            読み取り専用 [`WorkbookType`](/slides/python-net/ja/aspose.slides.charts/workbooktype)。 |

## メソッド

| メソッド | 説明 |
| :- | :- |
| [`set_external_workbook(self, workbook_path)`](/slides/python-net/ja/aspose.slides.charts/ichartdata/set_external_workbook/#str) | 外部ブックをチャートのデータソースとして設定します。チャートデータは対象ブックから更新されます。 |
| [`set_external_workbook(self, workbook_path, update_chart_data)`](/slides/python-net/ja/aspose.slides.charts/ichartdata/set_external_workbook/#str-bool) | 外部ブックをチャートのデータソースとして設定します。 |
| [`read_workbook_stream(self)`](/slides/python-net/ja/aspose.slides.charts/ichartdata/read_workbook_stream/#) | 内部に含まれる Excel ブックを書き込み、メモリストリームに出力します。 |
| [`write_workbook_stream(self, ms)`](/slides/python-net/ja/aspose.slides.charts/ichartdata/write_workbook_stream/#iorawiobase) | 内部に含まれる Excel ブックをユーザー指定の値で初期化します。 |
| [`set_range(self, formula)`](/slides/python-net/ja/aspose.slides.charts/ichartdata/set_range/#str) | チャートのデータ範囲を設定します。系列とカテゴリは新しいデータ範囲に基づいて更新されます。<br/>            データ範囲の系列数がチャートデータの系列数より多い場合、現在のコレクションの最後の系列と同じタイプの追加系列がコレクションの末尾に追加されます。 |
| [`get_range(self)`](/slides/python-net/ja/aspose.slides.charts/ichartdata/get_range/#) | チャートのデータ範囲を取得します。 |
| [`switch_row_column(self)`](/slides/python-net/ja/aspose.slides.charts/ichartdata/switch_row_column/#) | 軸上のデータを入れ替えます。X 軸でチャートされているデータが Y 軸に移動し、その逆も同様です。 |
| [`refresh_data(self)`](/slides/python-net/ja/aspose.slides.charts/ichartdata/refresh_data/#) | ソースブックから再読み込みしてチャートデータを更新します。 |

### 参照
* モジュール [`aspose.slides.charts`](/slides/python-net/ja/aspose.slides.charts)
* ライブラリ [`Aspose.Slides`](/slides/python-net)