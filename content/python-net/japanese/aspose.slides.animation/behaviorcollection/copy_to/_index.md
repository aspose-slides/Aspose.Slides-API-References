---
title: copy_to method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.animation/behaviorcollection/copy_to/
weight: 40
---
## copy_to(self, array, array_index) {#listibehavior-int}
**System.Collections.Generic.ICollection`1** の要素を **System.Array** にコピーし、特定の **System.Array** インデックスから開始します。

```python
def copy_to(self, array, array_index):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| array | **List[IBehavior]** | **System.Collections.Generic.ICollection`1** からコピーされた要素の宛先となる一次元 **System.Array**。**System.Array** はゼロベースインデックスである必要があります。 |
| array_index | **int** | `array` でコピーを開始するゼロベースインデックス。 |

### 例外

| 例外 | 説明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `array` は None です。 |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | `array_index` は 0 未満です。 |
| **RuntimeError(Proxy error(ArgumentException))** | ソース **System.Collections.Generic.ICollection`1** の要素数が、`array_index` から宛先 `array` の末尾までの利用可能なスペースよりも大きいです。 |

### 参照
* クラス [`BehaviorCollection`](/slides/python-net/ja/aspose.slides.animation/behaviorcollection)
* モジュール [`aspose.slides.animation`](/slides/python-net/ja/aspose.slides.animation)
* ライブラリ [`Aspose.Slides`](/slides/python-net)