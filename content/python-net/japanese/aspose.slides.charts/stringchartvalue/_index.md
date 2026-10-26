---
title: StringChartValue class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.charts/stringchartvalue/
---
## StringChartValue クラス

pptx プレゼンテーションドキュメントに保存できる文字列値を、2つの方法で表します:
            1) チャートに関連付けられたワークブックのセル/セル群に格納する;
            2) リテラル値として.

**継承:**[`StringChartValue`](/slides/python-net/ja/aspose.slides.charts/stringchartvalue) → [`BaseChartValue`](/slides/python-net/ja/aspose.slides.charts/basechartvalue)

StringChartValue 型は以下のメンバーを公開します:

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`data_source_type`](/slides/python-net/ja/aspose.slides.charts/stringchartvalue/data_source_type/) | 子クラスで AsCell、AsCells、AsLiteralString、または AsLiteralDouble <br/>            プロパティが実際に使用されているかを指定します。言い換えれば、Data プロパティの値の型を指定します。<br/>            読み書き [`DataSourceType`](/slides/python-net/ja/aspose.slides.charts/datasourcetype). |
| [`data`](/slides/python-net/ja/aspose.slides.charts/stringchartvalue/data/) | Data オブジェクトを取得または設定します。<br/>            読み書き **any**. |
| [`as_cells`](/slides/python-net/ja/aspose.slides.charts/stringchartvalue/as_cells/) | null 値の代入は許可されていません。<br/>            返される値は常に None です。<br/>            読み書き [`IChartCellCollection`](/slides/python-net/ja/aspose.slides.charts/ichartcellcollection). |
| [`as_literal_string`](/slides/python-net/ja/aspose.slides.charts/stringchartvalue/as_literal_string/) | リテラル文字列として値を取得または設定します。<br/>            読み書き **str**. |

## メソッド

| メソッド | 説明 |
| :- | :- |
| [`set_from_one_cell(self, cell)`](/slides/python-net/ja/aspose.slides.charts/stringchartvalue/set_from_one_cell/#ichartdatacell) | 指定されたセルから値を設定します。 |
| [`get_cells_address_in_workbook(self)`](/slides/python-net/ja/aspose.slides.charts/stringchartvalue/get_cells_address_in_workbook/#) | DataSourceType プロパティが DataSourceType.Worksheet の場合、このメソッドは文字列データを表すワークブックのセルのアドレスを返します。<br/>            それ以外の場合は空文字列を返します。 |

### 参照
* クラス [`BaseChartValue`](/slides/python-net/ja/aspose.slides.charts/basechartvalue)
* クラス [`StringChartValue`](/slides/python-net/ja/aspose.slides.charts/stringchartvalue)
* モジュール [`aspose.slides.charts`](/slides/python-net/ja/aspose.slides.charts)
* ライブラリ [`Aspose.Slides`](/slides/python-net)