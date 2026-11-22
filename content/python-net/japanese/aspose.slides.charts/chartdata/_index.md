---
title: ChartData class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.charts/chartdata/
---
## ChartData クラス

チャート描画に使用されるデータを表します。

ChartData 型は次のメンバーを公開します：

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`chart_data_workbook`](/slides/python-net/ja/aspose.slides.charts/chartdata/chart_data_workbook/) | チャートシリーズまたはカテゴリで使用されるセルを作成するセルファクトリを取得します。<br/> 読み取り専用 [`IChartDataWorkbook`](/slides/python-net/ja/aspose.slides.charts/ichartdataworkbook)。 |
| [`series`](/slides/python-net/ja/aspose.slides.charts/chartdata/series/) | シリーズを取得します。<br/> 読み取り専用 [`IChartSeriesCollection`](/slides/python-net/ja/aspose.slides.charts/ichartseriescollection)。 |
| [`series_groups`](/slides/python-net/ja/aspose.slides.charts/chartdata/series_groups/) | シリーズのグループを取得します。<br/> 読み取り専用 [`IChartSeriesGroupCollection`](/slides/python-net/ja/aspose.slides.charts/ichartseriesgroupcollection)。 |
| [`categories`](/slides/python-net/ja/aspose.slides.charts/chartdata/categories/) | 主カテゴリを取得します（[`ChartData.use_secondary_categories`](/slides/python-net/ja/aspose.slides.charts/chartdata/use_secondary_categories) プロパティが false の場合、主カテゴリと副カテゴリの両方）。<br/> 読み取り専用 [`IChartCategoryCollection`](/slides/python-net/ja/aspose.slides.charts/ichartcategorycollection)。 |
| [`use_secondary_categories`](/slides/python-net/ja/aspose.slides.charts/chartdata/use_secondary_categories/) | false の場合、[`ChartData.secondary_categories`](/slides/python-net/ja/aspose.slides.charts/chartdata/secondary_categories) プロパティは None を返し、[`ChartData.categories`](/slides/python-net/ja/aspose.slides.charts/chartdata/categories) プロパティのデータは主シリーズと副シリーズの両方に使用されます。<br/> true の場合、[`ChartData.secondary_categories`](/slides/python-net/ja/aspose.slides.charts/chartdata/secondary_categories) プロパティのデータは副シリーズに、[`ChartData.categories`](/slides/python-net/ja/aspose.slides.charts/chartdata/categories) プロパティのデータは主シリーズに使用されます。<br/> 読み書き **bool**。 |
| [`secondary_categories`](/slides/python-net/ja/aspose.slides.charts/chartdata/secondary_categories/) | [`ChartData.use_secondary_categories`](/slides/python-net/ja/aspose.slides.charts/chartdata/use_secondary_categories) プロパティが true の場合、副カテゴリを取得します。<br/> 読み取り専用 [`IChartCategoryCollection`](/slides/python-net/ja/aspose.slides.charts/ichartcategorycollection)。 |
| [`data_source_type`](/slides/python-net/ja/aspose.slides.charts/chartdata/data_source_type/) | 外部データソースの場合は外部ワークブックのパスを表し、そうでない場合は None を表します |
| [`external_workbook_path`](/slides/python-net/ja/aspose.slides.charts/chartdata/external_workbook_path/) | チャートのデータソースを表します |
| [`embedded_workbook_type`](/slides/python-net/ja/aspose.slides.charts/chartdata/embedded_workbook_type/) | 埋め込みワークブックのタイプを取得します。<br/> [`ChartData.data_source_type`](/slides/python-net/ja/aspose.slides.charts/chartdata/data_source_type) が [`ChartDataSourceType.EXTERNAL_WORKBOOK`](/slides/python-net/ja/aspose.slides.charts/chartdatasourcetype/EXTERNAL_WORKBOOK) の場合、[`WorkbookType.NOT_DEFINED`](/slides/python-net/ja/aspose.slides.charts/workbooktype/NOT_DEFINED) を返します。<br/> 読み取り専用 [`WorkbookType`](/slides/python-net/ja/aspose.slides.charts/workbooktype)。 |

## メソッド

| メソッド | 説明 |
| :- | :- |
| [`set_external_workbook(self, workbook_path)`](/slides/python-net/ja/aspose.slides.charts/chartdata/set_external_workbook/#str) | チャートのデータソースとして外部ワークブックを設定します。チャートデータは対象のワークブックから更新されます。 |
| [`set_external_workbook(self, workbook_path, update_chart_data)`](/slides/python-net/ja/aspose.slides.charts/chartdata/set_external_workbook/#str-bool) | チャートのデータソースとして外部ワークブックを設定します。 |
| [`read_workbook_stream(self)`](/slides/python-net/ja/aspose.slides.charts/chartdata/read_workbook_stream/#) | 内部に含まれる Excel ワークブックをストリームに書き込みます。 |
| [`write_workbook_stream(self, ms)`](/slides/python-net/ja/aspose.slides.charts/chartdata/write_workbook_stream/#iorawiobase) | 内部に含まれる Excel ワークブックをユーザー指定の値で初期化します。 |
| [`get_range(self)`](/slides/python-net/ja/aspose.slides.charts/chartdata/get_range/#) | チャートデータ範囲を取得します。 |
| [`set_range(self, formula)`](/slides/python-net/ja/aspose.slides.charts/chartdata/set_range/#str) | チャートデータ範囲を設定します。シリーズとカテゴリは新しいデータ範囲に基づいて更新されます。<br/> データ範囲内のシリーズ数がチャートデータ内のシリーズ数を超える場合、現在のコレクションの最後のシリーズと同じタイプの追加シリーズがコレクションの末尾に追加されます。 |
| [`refresh_data(self)`](/slides/python-net/ja/aspose.slides.charts/chartdata/refresh_data/#) | ソースワークブックから再読み込みしてチャートデータを更新します。 |
| [`switch_row_column(self)`](/slides/python-net/ja/aspose.slides.charts/chartdata/switch_row_column/#) | 軸上のデータを入れ替えます。<br/> X 軸でチャートされたデータは Y 軸へ、Y 軸のデータは X 軸へ移動します。 |

### 参照
* モジュール [`aspose.slides.charts`](/slides/python-net/ja/aspose.slides.charts)
* ライブラリ [`Aspose.Slides`](/slides/python-net)