---
title: IStringChartValue class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.charts/istringchartvalue/
---
## IStringChartValue クラス

pptx プレゼンテーション ドキュメントに 2 つの方法で格納できる文字列値を表します:
1) チャートに関連付けられたワークブックのセル/セル群に格納する;
2) リテラル値として格納する.

IStringChartValue 型は次のメンバーを公開します:

## プロパティ

| プロパティ | 説明 |
| :- | :- |
| [`as_literal_string`](/slides/python-net/ja/aspose.slides.charts/istringchartvalue/as_literal_string/) | DataSourceType プロパティが DataSourceType.StringLiterals の場合、リテラル文字列を取得または設定します。<br/>            読み書き可能 **str**. |
| [`as_cells`](/slides/python-net/ja/aspose.slides.charts/istringchartvalue/as_cells/) |  |
| [`data_source_type`](/slides/python-net/ja/aspose.slides.charts/istringchartvalue/data_source_type/) |  |
| [`data`](/slides/python-net/ja/aspose.slides.charts/istringchartvalue/data/) |  |

## メソッド

| メソッド | 説明 |
| :- | :- |
| [`to_string(self)`](/slides/python-net/ja/aspose.slides.charts/istringchartvalue/to_string/#) | 文字列表現を返します。 |
| [`set_from_one_cell(self, cell)`](/slides/python-net/ja/aspose.slides.charts/istringchartvalue/set_from_one_cell/#ichartdatacell) | 指定されたセルから値を設定します。 |
| [`get_cells_address_in_workbook(self)`](/slides/python-net/ja/aspose.slides.charts/istringchartvalue/get_cells_address_in_workbook/#) | DataSourceType プロパティが DataSourceType.Worksheet の場合、このメソッドは文字列データを表すワークブック内のセルのアドレスを返します。<br/>            それ以外の場合は空文字列を返します。 |

### 参照
* モジュール [`aspose.slides.charts`](/slides/python-net/ja/aspose.slides.charts)
* ライブラリ [`Aspose.Slides`](/slides/python-net)