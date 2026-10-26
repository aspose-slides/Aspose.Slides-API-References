---
title: copy_to method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/portioncollection/copy_to/
weight: 40
---
## copy_to(self, array, array_index) {#listiportion-int}
**System.Collections.Generic.ICollection`1** の要素を **System.Array** にコピーします。コピーは特定の **System.Array** のインデックスから開始されます。


```python
def copy_to(self, array, array_index):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| array | **List[IPortion]** | コピー元 **System.Collections.Generic.ICollection`1** からコピーされた要素の宛先となる一次元 **System.Array**。**System.Array** はゼロベースインデックスである必要があります。 |
| array_index | **int** | `array` のゼロベースインデックスで、コピーを開始する位置です。 |

### 例外

| 例外 | 説明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `array` が None です。 |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | `array_index` が 0 未満です。 |
| **RuntimeError(Proxy error(ArgumentException))** | ソース **System.Collections.Generic.ICollection`1** の要素数が、`array_index` から宛先 `array` の末尾までの利用可能なスペースより大きいです。 |



### 参照
* クラス [`PortionCollection`](/slides/python-net/ja/aspose.slides/portioncollection)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)