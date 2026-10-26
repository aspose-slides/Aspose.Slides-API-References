---
title: IExcelDataWorkbook class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.excel/iexceldataworkbook/
---
## IExcelDataWorkbook クラス

Excel データへの一般的な使用のためのアクセスを提供するブックを表します。

IExcelDataWorkbook 型は次のメンバーを公開します。

## メソッド

| メソッド | 説明 |
| :- | :- |
| [`get_cell(self, worksheet_index, row, column)`](/slides/python-net/ja/aspose.slides.excel/iexceldataworkbook/get_cell/#int-int-int) | 指定したワークシートから、インデックスとセル座標を使用してセルを取得します。 |
| [`get_cell(self, worksheet_name, row, column)`](/slides/python-net/ja/aspose.slides.excel/iexceldataworkbook/get_cell/#str-int-int) | 指定したワークシートから、名前とセル座標を使用してセルを取得します。 |
| [`get_cell(self, worksheet_index, cell_name)`](/slides/python-net/ja/aspose.slides.excel/iexceldataworkbook/get_cell/#int-str) | 指定したワークシートから、インデックスと Excel 形式のセル名 (例: "B2") を使用してセルを取得します。 |
| [`get_cell(self, worksheet_name, cell_name)`](/slides/python-net/ja/aspose.slides.excel/iexceldataworkbook/get_cell/#str-str) | 指定したワークシートから、Excel 形式のセル名 (例: "B2") を使用してセルを取得します。 |
| [`get_cells(self, formula, skip_hidden_cells)`](/slides/python-net/ja/aspose.slides.excel/iexceldataworkbook/get_cells/#str-bool) | 指定された数式に一致するセルのコレクションをワークブックから取得します。 |
| [`get_charts_from_worksheet(self, worksheet_name)`](/slides/python-net/ja/aspose.slides.excel/iexceldataworkbook/get_charts_from_worksheet/#str) | Excel ワークブックの指定されたワークシート内のすべてのチャートのインデックスと名前を含む辞書を取得します。 |
| [`get_worksheet_names(self)`](/slides/python-net/ja/aspose.slides.excel/iexceldataworkbook/get_worksheet_names/#) | Excel ワークブックに含まれるすべてのワークシートの名前を取得します。 |

### 参照
* モジュール [`aspose.slides.excel`](/slides/python-net/ja/aspose.slides.excel)
* ライブラリ [`Aspose.Slides`](/slides/python-net)