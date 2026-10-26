---
title: get_cells method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.excel/exceldataworkbook/get_cells/
weight: 30
---
## get_cells(self, formula, skip_hidden_cells) {#str-bool}
指定された数式に一致するセルのコレクションをワークブックから取得します。

### 返り値

指定された数式に一致するセルの読み取り専用リストです。

```python
def get_cells(self, formula, skip_hidden_cells):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| formula | **str** | ターゲットセルを識別するために使用される数式または範囲式（例: "Sheet1!A1:B3"）。 |
| skip_hidden_cells | **bool** | `true` の場合、非表示のセル（例: 非表示行や列のセル）は結果から除外されます。 |

### 参照
* クラス [`ExcelDataWorkbook`](/slides/python-net/ja/aspose.slides.excel/exceldataworkbook)
* モジュール [`aspose.slides.excel`](/slides/python-net/ja/aspose.slides.excel)
* ライブラリ [`Aspose.Slides`](/slides/python-net)