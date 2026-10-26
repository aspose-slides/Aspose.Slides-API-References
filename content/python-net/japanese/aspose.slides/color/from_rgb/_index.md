---
title: from_rgb method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/color/from_rgb/
weight: 50
---
## from_rgb(r, g, b) {#int-int-int}
指定された赤、緑、青の値から不透明な色（アルファは255）を作成します。

### 戻り値

指定された値から作成された色です。



```python
@staticmethod
def from_rgb(r, g, b):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| r | **int** | 赤成分の値。 有効な値は0から255です。 |
| g | **int** | 緑成分の値。 有効な値は0から255です。 |
| b | **int** | 青成分の値。 有効な値は0から255です。 |

### 例外

| 例外 | 説明 |
| :- | :- |
| **ValueError** | 成分の値が0未満または255を超えています。 |



### 参照
* クラス [`Color`](/slides/python-net/ja/aspose.slides/color)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)