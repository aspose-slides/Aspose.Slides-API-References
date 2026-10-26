---
title: ChartDataCell class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.charts/chartdatacell/
---
## ChartDataCell クラス

チャート データ用のセルを表します。

ChartDataCell 型は以下のメンバーを公開します。

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`row`](/slides/python-net/ja/aspose.slides.charts/chartdatacell/row/) | セルが位置するワークシートの行インデックスを返します。<br/>            読み取り専用 **int**. |
| [`column`](/slides/python-net/ja/aspose.slides.charts/chartdatacell/column/) | セルが位置するワークシートの列インデックスを返します。<br/>            読み取り専用 **int**. |
| [`value`](/slides/python-net/ja/aspose.slides.charts/chartdatacell/value/) | セルの値を取得または設定します。<br/>            読み書き **any**. |
| [`formula`](/slides/python-net/ja/aspose.slides.charts/chartdatacell/formula/) | A1 形式の数式を取得または設定します。 |
| [`r1c1_formula`](/slides/python-net/ja/aspose.slides.charts/chartdatacell/r1c1_formula/) | R1C1 形式の数式を取得または設定します。 |
| [`chart_data_worksheet`](/slides/python-net/ja/aspose.slides.charts/chartdatacell/chart_data_worksheet/) | ワークシートを取得します。<br/>            読み取り専用 [`IChartDataWorksheet`](/slides/python-net/ja/aspose.slides.charts/ichartdataworksheet). |
| [`is_hidden`](/slides/python-net/ja/aspose.slides.charts/chartdatacell/is_hidden/) | セルが非表示かどうかを判定します。<br/>            読み取り専用 **bool**. |
| [`custom_number_format`](/slides/python-net/ja/aspose.slides.charts/chartdatacell/custom_number_format/) | 数値と日付のカスタム表示形式を取得または設定します。<br/>            値が空の場合は PresetNumberFormat の値が使用されます。<br/>            読み書き **str**. |
| [`preset_number_format`](/slides/python-net/ja/aspose.slides.charts/chartdatacell/preset_number_format/) | 数値と日付の組み込み表示形式を取得または設定します。プリセット番号は [0..22] または [37..49] の範囲でなければなりません。<br/>            読み書き **int**. |

## メソッド

| メソッド | 説明 |
| :- | :- |
| [`calculate(self, update_values)`](/slides/python-net/ja/aspose.slides.charts/chartdatacell/calculate/#bool) | セルに数式が含まれている場合、その数式に基づいて値が更新されます。 |

### 参照
* モジュール [`aspose.slides.charts`](/slides/python-net/ja/aspose.slides.charts)
* ライブラリ [`Aspose.Slides`](/slides/python-net)