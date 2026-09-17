---
title: copy_to method
second_title: Aspose.Slides の Python 用 (.NET 経由) API リファレンス
description: 
type: docs
url: /ja/aspose.slides/paragraphcollection/copy_to/
weight: 50
---
## copy_to(self, array, array_index) {#listiparagraph-int}
**System.Collections.Generic.ICollection`1** の要素を **System.Array** にコピーします。特定の **System.Array** インデックスから開始します。

```python
def copy_to(self, array, array_index):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| array | **List[IParagraph]** | **System.Collections.Generic.ICollection`1** からコピーされた要素の宛先となる一次元 **System.Array**。**System.Array** はゼロベースのインデックスを持つ必要があります。 |
| array_index | **int** | コピーを開始する `array` 内のゼロベースインデックス。 |

### 例外

| 例外 | 説明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `array` が None です。 |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | `array_index` が 0 未満です。 |
| **RuntimeError(Proxy error(ArgumentException))** | ソース **System.Collections.Generic.ICollection`1** の要素数が、宛先 `array` の `array_index` から末尾までの空きスペースより多いです。 |

### 参照
* クラス [`ParagraphCollection`](/slides/python-net/ja/aspose.slides/paragraphcollection)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)