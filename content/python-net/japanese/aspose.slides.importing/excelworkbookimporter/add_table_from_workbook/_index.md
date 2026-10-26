---
title: add_table_from_workbook method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.importing/excelworkbookimporter/add_table_from_workbook/
weight: 20
---
## add_table_from_workbook(shapes, x, y, workbook, worksheet_name, cell_range) {#ishapecollection-float-float-asposeslidesexceliexceldataworkbook-str-str}
指定された Excel ワークブックからテーブルを取得し、指定された座標で対象のシェイプコレクションの末尾に追加します。

### 戻り値

シェイプコレクションに追加されたテーブルです。

```python
@staticmethod
def add_table_from_workbook(shapes, x, y, workbook, worksheet_name, cell_range):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/ja/aspose.slides/ishapecollection) | テーブルが追加されるシェイプコレクション。 |
| x | **float** | テーブルの位置決めに使用する X 座標です。 |
| y | **float** | テーブルの位置決めに使用する Y 座標です。 |
| workbook | [`IExcelDataWorkbook`](/slides/python-net/ja/aspose.slides.excel/iexceldataworkbook) | Excel ワークブックです。 |
| worksheet_name | **str** | テーブルを含むワークシートの名前です。 |
| cell_range | **str** | テーブルを定義するセル範囲です（例: "A1:D10"）。 |

### 例外

| 例外 | 説明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 必須パラメータが None または空の場合、または指定されたワークシートまたはセル範囲が無効な場合にスローされます。 |
| **RuntimeError(Proxy error(InvalidOperationException))** | 入力データがサポートされていない形式の場合にスローされます。 |

## add_table_from_workbook(shapes, x, y, workbook_path, worksheet_name, cell_range) {#ishapecollection-float-float-str-str-str}
指定された Excel ワークブック ファイルからテーブルを取得し、指定された座標で対象のシェイプコレクションの末尾に追加します。

### 戻り値

シェイプコレクションに追加されたテーブルです。

```python
@staticmethod
def add_table_from_workbook(shapes, x, y, workbook_path, worksheet_name, cell_range):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/ja/aspose.slides/ishapecollection) | テーブルが追加されるシェイプコレクション。 |
| x | **float** | テーブルの位置決めに使用する X 座標です。 |
| y | **float** | テーブルの位置決めに使用する Y 座標です。 |
| workbook_path | **str** | Excel ワークブック ファイルへのパスです。 |
| worksheet_name | **str** | テーブルを含むワークシートの名前です。 |
| cell_range | **str** | テーブルを定義するセル範囲です（例: "A1:D10"）。 |

### 例外

| 例外 | 説明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 必須パラメータが None または空の場合、または指定されたワークシートまたはセル範囲が無効な場合にスローされます。 |
| **RuntimeError(Proxy error(IOException))** | ワークブックファイルへのアクセス中に I/O エラーが発生した場合にスローされます。 |
| **RuntimeError(Proxy error(InvalidOperationException))** | 入力データがサポートされていない形式の場合にスローされます。 |

## add_table_from_workbook(shapes, x, y, workbook_stream, worksheet_name, cell_range) {#ishapecollection-float-float-iorawiobase-str-str}
指定された Excel ワークブック ファイルからテーブルを取得し、指定された座標で対象のシェイプコレクションの末尾に追加します。

### 戻り値

シェイプコレクションに追加されたテーブルです。

```python
@staticmethod
def add_table_from_workbook(shapes, x, y, workbook_stream, worksheet_name, cell_range):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/ja/aspose.slides/ishapecollection) | テーブルが追加されるシェイプコレクション。 |
| x | **float** | テーブルの位置決めに使用する X 座標です。 |
| y | **float** | テーブルの位置決めに使用する Y 座標です。 |
| workbook_stream | **io.RawIOBase** | ワークブック データを含むストリームです。 |
| worksheet_name | **str** | テーブルを含むワークシートの名前です。 |
| cell_range | **str** | テーブルを定義するセル範囲です（例: "A1:D10"）。 |

### 例外

| 例外 | 説明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 必須パラメータが None または空の場合、または指定されたワークシートまたはセル範囲が無効な場合にスローされます。 |
| **RuntimeError(Proxy error(InvalidOperationException))** | 入力データがサポートされていない形式の場合にスローされます。 |

### 参照
* クラス [`ExcelWorkbookImporter`](/slides/python-net/ja/aspose.slides.importing/excelworkbookimporter)
* クラス [`IExcelDataWorkbook`](/slides/python-net/ja/aspose.slides.excel/iexceldataworkbook)
* クラス [`IShapeCollection`](/slides/python-net/ja/aspose.slides/ishapecollection)
* クラス [`ITable`](/slides/python-net/ja/aspose.slides/itable)
* モジュール [`aspose.slides.importing`](/slides/python-net/ja/aspose.slides.importing)
* ライブラリ [`Aspose.Slides`](/slides/python-net)