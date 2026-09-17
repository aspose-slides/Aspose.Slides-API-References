---
title: add_chart_from_workbook method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.importing/excelworkbookimporter/add_chart_from_workbook/
weight: 10
---
## add_chart_from_workbook(shapes, x, y, workbook, worksheet_name, chart_index, embed_all_workbook) {#ishapecollection-float-float-asposeslidesexceliexceldataworkbook-str-int-bool}
指定された Excel ワークブックからチャートを取得し、指定された座標で指定されたシェイプコレクションの末尾に追加します。

### 戻り値

シェイプコレクションに追加されたチャートです。

```python
@staticmethod
def add_chart_from_workbook(shapes, x, y, workbook, worksheet_name, chart_index, embed_all_workbook):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/ja/aspose.slides/ishapecollection) | チャートが追加されるシェイプコレクション。 |
| x | **float** | チャートの位置指定に使用する X 座標。 |
| y | **float** | チャートの位置指定に使用する Y 座標。 |
| workbook | [`IExcelDataWorkbook`](/slides/python-net/ja/aspose.slides.excel/iexceldataworkbook) | Excel ワークブック。 |
| worksheet_name | **str** | チャートが含まれるワークシートの名前。 |
| chart_index | **int** | 挿入するチャートシェイプのゼロベースインデックス。 <br/><br/>            このインデックスは **Aspose.Slides.Excel.IExcelDataWorkbook.GetChartsFromWorksheet(Syste** メソッドを使用して取得できます。 |
| embed_all_workbook | **bool** | `true` の場合、ブック全体がチャートに埋め込まれます。<br/><br/>            `false` の場合、チャートデータのみが埋め込まれます。 |

### 例外

| 例外 | 説明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 必須パラメータが None、空、またはワークブック内にチャートが見つからない場合にスローされます。 |

## add_chart_from_workbook(shapes, x, y, workbook, worksheet_name, chart_name, embed_all_workbook) {#ishapecollection-float-float-asposeslidesexceliexceldataworkbook-str-str-bool}
指定された Excel ワークブックからチャートを取得し、指定された座標で指定されたシェイプコレクションの末尾に追加します。

### 戻り値

シェイプコレクションに追加されたチャートです。

```python
@staticmethod
def add_chart_from_workbook(shapes, x, y, workbook, worksheet_name, chart_name, embed_all_workbook):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/ja/aspose.slides/ishapecollection) | チャートが追加されるシェイプコレクション。 |
| x | **float** | チャートの位置指定に使用する X 座標。 |
| y | **float** | チャートの位置指定に使用する Y 座標。 |
| workbook | [`IExcelDataWorkbook`](/slides/python-net/ja/aspose.slides.excel/iexceldataworkbook) | Excel ワークブック。 |
| worksheet_name | **str** | チャートが含まれるワークシートの名前。 |
| chart_name | **str** | 追加されるチャートの名前。 |
| embed_all_workbook | **bool** | `true` の場合、ブック全体がチャートに埋め込まれます。<br/><br/>            `false` の場合、チャートデータのみが埋め込まれます。 |

### 例外

| 例外 | 説明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 必須パラメータが None、空、またはワークブック内にチャートが見つからない場合にスローされます。 |

## add_chart_from_workbook(shapes, x, y, workbook_stream, worksheet_name, chart_name, embed_all_workbook) {#ishapecollection-float-float-iorawiobase-str-str-bool}
指定された Excel ワークブックからチャートを取得し、指定された座標で指定されたシェイプコレクションの末尾に追加します。

### 戻り値

シェイプコレクションに追加されたチャートです。

```python
@staticmethod
def add_chart_from_workbook(shapes, x, y, workbook_stream, worksheet_name, chart_name, embed_all_workbook):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/ja/aspose.slides/ishapecollection) | チャートが追加されるシェイプコレクション。 |
| x | **float** | チャートの位置指定に使用する X 座標。 |
| y | **float** | チャートの位置指定に使用する Y 座標。 |
| workbook_stream | **io.RawIOBase** | ワークブックデータを含むストリーム。 |
| worksheet_name | **str** | チャートが含まれるワークシートの名前。 |
| chart_name | **str** | 追加されるチャートの名前。 |
| embed_all_workbook | **bool** | `true` の場合、ブック全体がチャートに埋め込まれます。<br/><br/>            `false` の場合、チャートデータのみが埋め込まれます。 |

### 例外

| 例外 | 説明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 必須パラメータが None、空、またはワークブック内にチャートが見つからない場合にスローされます。 |
| **RuntimeError(Proxy error(InvalidOperationException))** | 入力データがサポートされていない形式の場合にスローされます。 |

## add_chart_from_workbook(shapes, x, y, workbook_path, worksheet_name, chart_name, embed_workbook) {#ishapecollection-float-float-str-str-str-bool}
指定された Excel ワークブックからチャートを取得し、指定された座標で指定されたシェイプコレクションの末尾に追加します。

### 戻り値

シェイプコレクションに追加されたチャートです。

```python
@staticmethod
def add_chart_from_workbook(shapes, x, y, workbook_path, worksheet_name, chart_name, embed_workbook):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| shapes | [`IShapeCollection`](/slides/python-net/ja/aspose.slides/ishapecollection) | チャートが追加されるシェイプコレクション。 |
| x | **float** | チャートの位置指定に使用する X 座標。 |
| y | **float** | チャートの位置指定に使用する Y 座標。 |
| workbook_path | **str** | チャートを含むワークブックへのファイルパス。 |
| worksheet_name | **str** | チャートが含まれるワークシートの名前。 |
| chart_name | **str** | 追加されるチャートの名前。 |
| embed_workbook | **bool** | `true` の場合、ワークブックがチャートに埋め込まれます。<br/><br/>            `false` の場合、チャートは外部ワークブックへのリンクになります。 |

### 例外

| 例外 | 説明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 必須パラメータが None、空、またはワークブック内にチャートが見つからない場合にスローされます。 |
| **RuntimeError(Proxy error(IOException))** | ファイルにアクセス中に I/O エラーが発生した場合にスローされます。 |
| **RuntimeError(Proxy error(InvalidOperationException))** | 入力データがサポートされていない形式の場合にスローされます。 |

### 参照
* クラス [`ExcelWorkbookImporter`](/slides/python-net/ja/aspose.slides.importing/excelworkbookimporter)
* クラス [`IExcelDataWorkbook`](/slides/python-net/ja/aspose.slides.excel/iexceldataworkbook)
* クラス [`IShapeCollection`](/slides/python-net/ja/aspose.slides/ishapecollection)
* モジュール [`aspose.slides.importing`](/slides/python-net/ja/aspose.slides.importing)
* ライブラリ [`Aspose.Slides`](/slides/python-net)