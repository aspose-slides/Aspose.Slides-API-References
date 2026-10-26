---
title: ChartData class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.charts/chartdata/
---
## ChartData クラス

チャートのプロットに使用されるデータを表します。  
ChartData 型は以下のメンバーを公開します。

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`chart_data_workbook`](/slides/python-net/ja/aspose.slides.charts/chartdata/chart_data_workbook/) | チャートの系列またはカテゴリで使用されるセルを作成するセルファクトリを取得します。<br/>            読み取り専用 [`IChartDataWorkbook`](/slides/python-net/ja/aspose.slides.charts/ichartdataworkbook). |
| [`series`](/slides/python-net/ja/aspose.slides.charts/chartdata/series/) | 系列を取得します。<br/>            読み取り専用 [`IChartSeriesCollection`](/slides/python-net/ja/aspose.slides.charts/ichartseriescollection). |
| [`series_groups`](/slides/python-net/ja/aspose.slides.charts/chartdata/series_groups/) | 系列のグループを取得します。<br/>            読み取り専用 [`IChartSeriesGroupCollection`](/slides/python-net/ja/aspose.slides.charts/ichartseriesgroupcollection). |
| [`categories`](/slides/python-net/ja/aspose.slides.charts/chartdata/categories/) | 主カテゴリを取得します（[`ChartData.use_secondary_categories`](/slides/python-net/ja/aspose.slides.charts/chartdata/use_secondary_categories) プロパティが false の場合、主カテゴリと副カテゴリの両方を取得します）。<br/>            読み取り専用 [`IChartCategoryCollection`](/slides/python-net/ja/aspose.slides.charts/ichartcategorycollection). |
| [`use_secondary_categories`](/slides/python-net/ja/aspose.slides.charts/chartdata/use_secondary_categories/) | false の場合、[`ChartData.secondary_categories`](/slides/python-net/ja/aspose.slides.charts/chartdata/secondary_categories) プロパティは None を返し、[`ChartData.categories`](/slides/python-net/ja/aspose.slides.charts/chartdata/categories) プロパティのデータは主系列と副系列の両方に使用されます。<br/>            true の場合、[`ChartData.secondary_categories`](/slides/python-net/ja/aspose.slides.charts/chartdata/secondary_categories) プロパティのデータは副系列に使用され、[`ChartData.categories`](/slides/python-net/ja/aspose.slides.charts/chartdata/categories) プロパティのデータは主系列に使用されます。<br/>            読み書き可能 **bool**. |
| [`secondary_categories`](/slides/python-net/ja/aspose.slides.charts/chartdata/secondary_categories/) | [`ChartData.use_secondary_categories`](/slides/python-net/ja/aspose.slides.charts/chartdata/use_secondary_categories) プロパティが true の場合、副カテゴリを取得します。<br/>            読み取り専用 [`IChartCategoryCollection`](/slides/python-net/ja/aspose.slides.charts/ichartcategorycollection). |
| [`data_source_type`](/slides/python-net/ja/aspose.slides.charts/chartdata/data_source_type/) | 外部データソースの場合は外部ブックのパスを表し、そうでない場合は None を表します |
| [`external_workbook_path`](/slides/python-net/ja/aspose.slides.charts/chartdata/external_workbook_path/) | チャートのデータソースを表します |
| [`embedded_workbook_type`](/slides/python-net/ja/aspose.slides.charts/chartdata/embedded_workbook_type/) | 埋め込みブックのタイプを取得します。<br/>            [`ChartData.data_source_type`](/slides/python-net/ja/aspose.slides.charts/chartdata/data_source_type) が [`ChartDataSourceType.EXTERNAL_WORKBOOK`](/slides/python-net/ja/aspose.slides.charts/chartdatasourcetype/EXTERNAL_WORKBOOK) の場合、[`WorkbookType.NOT_DEFINED`](/slides/python-net/ja/aspose.slides.charts/workbooktype/NOT_DEFINED) を返します。<br/>            読み取り専用 [`WorkbookType`](/slides/python-net/ja/aspose.slides.charts/workbooktype). |

## メソッド

| メソッド | 説明 |
| :- | :- |
| [`set_external_workbook(self, workbook_path)`](/slides/python-net/ja/aspose.slides.charts/chartdata/set_external_workbook/#str) | 外部ブックをチャートのデータソースとして設定します。チャートデータは対象ブックから更新されます。 |
| [`set_external_workbook(self, workbook_path, update_chart_data)`](/slides/python-net/ja/aspose.slides.charts/chartdata/set_external_workbook/#str-bool) | 外部ブックをチャートのデータソースとして設定します。 |
| [`read_workbook_stream(self)`](/slides/python-net/ja/aspose.slides.charts/chartdata/read_workbook_stream/#) | 内部に含まれる Excel ブックをストリームに書き込みます。 |
| [`write_workbook_stream(self, ms)`](/slides/python-net/ja/aspose.slides.charts/chartdata/write_workbook_stream/#iorawiobase) | ユーザー指定の値で内部に含まれる Excel ブックを初期化します。 |
| [`get_range(self)`](/slides/python-net/ja/aspose.slides.charts/chartdata/get_range/#) | チャートのデータ範囲を取得します。 |
| [`set_range(self, formula)`](/slides/python-net/ja/aspose.slides.charts/chartdata/set_range/#str) | チャートのデータ範囲を設定します。系列とカテゴリは新しいデータ範囲に基づいて更新されます。<br/>            データ範囲の系列数がチャートデータの系列数を超える場合、現在のコレクションの最後の系列と同じタイプの追加系列がコレクションの末尾に追加されます。 |
| [`switch_row_column(self)`](/slides/python-net/ja/aspose.slides.charts/chartdata/switch_row_column/#) | 軸上のデータを入れ替えます。<br/>            X 軸でチャート化されたデータが Y 軸に移動し、その逆も同様です。 |

### 参照
* モジュール [`aspose.slides.charts`](/slides/python-net/ja/aspose.slides.charts)
* ライブラリ [`Aspose.Slides`](/slides/python-net)