---
title: delete_row method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.mathtext/mathmatrix/delete_row/
weight: 50
---
## delete_row(self, row_index) {#int}
指定された行を削除します

```python
def delete_row(self, row_index):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| row_index | **int** | 削除する行の0ベースインデックス。 |

### 例外

| 例外 | 説明 |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | 行列の最後の単一行を削除しようとしたとき |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | rowIndex が 0 未満、または RowCount 以上の場合 |

### 参照
* クラス [`MathMatrix`](/slides/python-net/ja/aspose.slides.mathtext/mathmatrix)
* モジュール [`aspose.slides.mathtext`](/slides/python-net/ja/aspose.slides.mathtext)
* ライブラリ [`Aspose.Slides`](/slides/python-net)