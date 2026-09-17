---
title: get_cells method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.excel/iexceldataworkbook/get_cells/
weight: 20
---
## get_cells(self, formula, skip_hidden_cells) {#str-bool}
指定された数式に一致するワークブックからセルのコレクションを取得します。

### 戻り値
指定された数式に一致するセルの読み取り専用リストです。

```python
def get_cells(self, formula, skip_hidden_cells):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| formula | **str** | 対象セルを特定するために使用される数式または範囲式（例: "Sheet1!A1:B3"）です。 |
| skip_hidden_cells | **bool** | `true` の場合、非表示のセル（非表示の行や列にあるものなど）は結果から除外されます。 |

### 参照
* クラス [`IExcelDataWorkbook`](/slides/python-net/ja/aspose.slides.excel/iexceldataworkbook)
* モジュール [`aspose.slides.excel`](/slides/python-net/ja/aspose.slides.excel)
* library [`Aspose.Slides`](/slides/python-net)