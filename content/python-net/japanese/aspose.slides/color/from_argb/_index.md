---
title: from_argb method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/color/from_argb/
weight: 20
---
## from_argb(argb) {#int}
32 ビット ARGB 値から色を作成します。

### 戻り値

指定された値から作成された色です。



```python
@staticmethod
def from_argb(argb):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| argb | **int** | 32 ビット ARGB 値（符号付きまたは符号なし）を指定する値です。 |

### 例外

| 例外 | 説明 |
| :- | :- |
| **ValueError** | コンポーネントの値が 0 未満または 255 超です。 |
| **TypeError** | 引数の数または型が正しくありません。 |


## from_argb(alpha, base_color) {#int-color}
指定されたアルファ値と基底色から色を作成します。

### 戻り値

指定された値から作成された色です。



```python
@staticmethod
def from_argb(alpha, base_color):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| alpha | **int** | アルファ コンポーネントの値です。 有効な値は 0 から 255 です。 |
| base_color | [`Color`](/slides/python-net/ja/aspose.slides/color) | 新しい色を作成する元となる色です。 |

### 例外

| 例外 | 説明 |
| :- | :- |
| **ValueError** | コンポーネントの値が 0 未満または 255 超です。 |
| **TypeError** | 引数の数または型が正しくありません。 |


## from_argb(red, green, blue) {#int-int-int}
指定された赤、緑、青の値から不透明な色（アルファは 255）を作成します。

### 戻り値

指定された値から作成された色です。



```python
@staticmethod
def from_argb(red, green, blue):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| red | **int** | 赤コンポーネントの値です。 有効な値は 0 から 255 です。 |
| green | **int** | 緑コンポーネントの値です。 有効な値は 0 から 255 です。 |
| blue | **int** | 青コンポーネントの値です。 有効な値は 0 から 255 です。 |

### 例外

| 例外 | 説明 |
| :- | :- |
| **ValueError** | コンポーネントの値が 0 未満または 255 超です。 |
| **TypeError** | 引数の数または型が正しくありません。 |


## from_argb(alpha, red, green, blue) {#int-int-int-int}
アルファ、赤、緑、青の 4 つの ARGB コンポーネント値から色を作成します。

### 戻り値

指定された値から作成された色です。



```python
@staticmethod
def from_argb(alpha, red, green, blue):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| alpha | **int** | アルファ コンポーネントの値です。 有効な値は 0 から 255 です。 |
| red | **int** | 赤コンポーネントの値です。 有効な値は 0 から 255 です。 |
| green | **int** | 緑コンポーネントの値です。 有効な値は 0 から 255 です。 |
| blue | **int** | 青コンポーネントの値です。 有効な値は 0 から 255 です。 |

### 例外

| 例外 | 説明 |
| :- | :- |
| **ValueError** | コンポーネントの値が 0 未満または 255 超です。 |
| **TypeError** | 引数の数または型が正しくありません。 |



### 参照
* クラス [`Color`](/slides/python-net/ja/aspose.slides/color)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)