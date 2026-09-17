---
title: IChartDataCell class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.charts/ichartdatacell/
---
## IChartDataCell クラス

チャート データのセルを表します。

IChartDataCell 型は次のメンバーを公開します。

## プロパティ

| Property | Description |
| :- | :- |
| [`row`](/slides/python-net/ja/aspose.slides.charts/ichartdatacell/row/) | セルが所在するワークシートの行インデックスを返します。<br/>            読み取り専用 **int**. |
| [`column`](/slides/python-net/ja/aspose.slides.charts/ichartdatacell/column/) | セルが所在するワークシートの列インデックスを返します。<br/>            読み取り専用 **int**. |
| [`value`](/slides/python-net/ja/aspose.slides.charts/ichartdatacell/value/) | セルの値を取得または設定します。<br/>            読み書き可能 **any**. |
| [`formula`](/slides/python-net/ja/aspose.slides.charts/ichartdatacell/formula/) | A1 形式の数式を取得または設定します。 |
| [`r1c1_formula`](/slides/python-net/ja/aspose.slides.charts/ichartdatacell/r1c1_formula/) | R1C1 形式の数式を取得または設定します。 |
| [`chart_data_worksheet`](/slides/python-net/ja/aspose.slides.charts/ichartdatacell/chart_data_worksheet/) | ワークシートを取得します。<br/>            読み取り専用 [`IChartDataWorksheet`](/slides/python-net/ja/aspose.slides.charts/ichartdataworksheet). |
| [`is_hidden`](/slides/python-net/ja/aspose.slides.charts/ichartdatacell/is_hidden/) | セルが非表示かどうかを判定します。<br/>            読み取り専用 **bool**. |
| [`custom_number_format`](/slides/python-net/ja/aspose.slides.charts/ichartdatacell/custom_number_format/) | 数値および日付のカスタム表示形式を取得または設定します。<br/>            値が空の場合は PresetNumberFormat の値が使用されます。<br/>            読み書き可能 **str**. |
| [`preset_number_format`](/slides/python-net/ja/aspose.slides.charts/ichartdatacell/preset_number_format/) | 数値および日付の組み込み表示形式を取得または設定します。プリセット番号は [0..22] または [37..49] の範囲でなければなりません。<br/>            読み書き可能 **int**. |

## メソッド

| Method | Description |
| :- | :- |
| [`calculate(self, update_values)`](/slides/python-net/ja/aspose.slides.charts/ichartdatacell/calculate/#bool) | セルに数式が含まれている場合、値はその数式に基づいて更新されます。 |

### 参照
* モジュール [`aspose.slides.charts`](/slides/python-net/ja/aspose.slides.charts)
* ライブラリ [`Aspose.Slides`](/slides/python-net)