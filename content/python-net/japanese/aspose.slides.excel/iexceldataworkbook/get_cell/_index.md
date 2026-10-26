---
title: get_cell method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.excel/iexceldataworkbook/get_cell/
weight: 10
---
## get_cell(self, worksheet_index, cell_name) {#int-str}
指定されたワークシートから、インデックスと Excel 形式のセル名（例: "B2"）を使用してセルを取得します。

### Returns
指定された場所のセルです。

```python
def get_cell(self, worksheet_index, cell_name):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| worksheet_index | **int** | ワークシートのゼロベースインデックス。 |
| cell_name | **str** | Excel 形式のセル参照（例: "A1", "C5"）。 |

## get_cell(self, worksheet_name, cell_name) {#str-str}
指定されたワークシートから、Excel 形式のセル名（例: "B2"）を使用してセルを取得します。

### Returns
指定された場所のセルです。

```python
def get_cell(self, worksheet_name, cell_name):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| worksheet_name | **str** | ワークシートの名前。 |
| cell_name | **str** | Excel 形式のセル参照（例: "A1", "C5"）。 |

## get_cell(self, worksheet_index, row, column) {#int-int-int}
指定されたワークシートから、インデックスとセル座標を使用してセルを取得します。

### Returns
指定された場所のセルです。

```python
def get_cell(self, worksheet_index, row, column):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| worksheet_index | **int** | ワークシートのゼロベースインデックス。 |
| row | **int** | セルのゼロベース行インデックス。 |
| column | **int** | セルのゼロベース列インデックス。 |

## get_cell(self, worksheet_name, row, column) {#str-int-int}
指定されたワークシートから、名前とセル座標を使用してセルを取得します。

### Returns
指定された場所のセルです。

```python
def get_cell(self, worksheet_name, row, column):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| worksheet_name | **str** | ワークシートの名前。 |
| row | **int** | セルのゼロベース行インデックス。 |
| column | **int** | セルのゼロベース列インデックス。 |

### See Also
* クラス [`IExcelDataCell`](/slides/python-net/ja/aspose.slides.excel/iexceldatacell)
* クラス [`IExcelDataWorkbook`](/slides/python-net/ja/aspose.slides.excel/iexceldataworkbook)
* モジュール [`aspose.slides.excel`](/slides/python-net/ja/aspose.slides.excel)
* ライブラリ [`Aspose.Slides`](/slides/python-net)