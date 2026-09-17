---
title: delete_column method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.mathtext/mathmatrix/delete_column/
weight: 40
---
## delete_column(self, column_index) {#int}
指定された列を削除します

```python
def delete_column(self, column_index):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| column_index | **int** | 削除する列のゼロベースインデックスです。 |

### 例外

| 例外 | 説明 |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | 行列の最後の単一列を削除しようとしたとき |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | columnIndex が 0 未満、または ColumnCount 以上の場合 |

### 参照
* クラス [`MathMatrix`](/slides/python-net/ja/aspose.slides.mathtext/mathmatrix)
* モジュール [`aspose.slides.mathtext`](/slides/python-net/ja/aspose.slides.mathtext)
* ライブラリ [`Aspose.Slides`](/slides/python-net)