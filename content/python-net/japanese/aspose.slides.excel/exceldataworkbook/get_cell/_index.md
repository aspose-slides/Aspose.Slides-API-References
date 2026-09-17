---
title: get_cell method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.excel/exceldataworkbook/get_cell/
weight: 20
---
## get_cell(self, worksheet_index, cell_name) {#int-str}
指定されたワークシートから、インデックスと Excel 形式のセル名 (例: "B2") を使用してセルを取得します。

### 戻り値

指定された場所のセルです。



```python
def get_cell(self, worksheet_index, cell_name):
    ...
```


| パラメーター | 型 | 説明 |
| :- | :- | :- |
| worksheet_index | **int** | ワークシートのゼロベースインデックスです。 |
| cell_name | **str** | Excel 形式のセル参照 (例: "A1", "C5") です。 |


## get_cell(self, worksheet_name, cell_name) {#str-str}
指定されたワークシートから、Excel 形式のセル名 (例: "B2") を使用してセルを取得します。

### 戻り値

指定された場所のセルです。



```python
def get_cell(self, worksheet_name, cell_name):
    ...
```


| パラメーター | 型 | 説明 |
| :- | :- | :- |
| worksheet_name | **str** | ワークシートの名前です。 |
| cell_name | **str** | Excel 形式のセル参照 (例: "A1", "C5") です。 |


## get_cell(self, worksheet_index, row, column) {#int-int-int}
指定されたワークシートから、インデックスとセル座標を使用してセルを取得します。

### 戻り値

指定された場所のセルです。



```python
def get_cell(self, worksheet_index, row, column):
    ...
```


| パラメーター | 型 | 説明 |
| :- | :- | :- |
| worksheet_index | **int** | ワークシートのゼロベースインデックスです。 |
| row | **int** | セルのゼロベース行インデックスです。 |
| column | **int** | セルのゼロベース列インデックスです。 |


## get_cell(self, worksheet_name, row, column) {#str-int-int}
指定されたワークシートから、名前とセル座標を使用してセルを取得します。

### 戻り値

指定された場所のセルです。



```python
def get_cell(self, worksheet_name, row, column):
    ...
```


| パラメーター | 型 | 説明 |
| :- | :- | :- |
| worksheet_name | **str** | ワークシートの名前です。 |
| row | **int** | セルのゼロベース行インデックスです。 |
| column | **int** | セルのゼロベース列インデックスです。 |



### 参照
* クラス [`ExcelDataWorkbook`](/slides/python-net/ja/aspose.slides.excel/exceldataworkbook)
* クラス [`IExcelDataCell`](/slides/python-net/ja/aspose.slides.excel/iexceldatacell)
* モジュール [`aspose.slides.excel`](/slides/python-net/ja/aspose.slides.excel)
* ライブラリ [`Aspose.Slides`](/slides/python-net)