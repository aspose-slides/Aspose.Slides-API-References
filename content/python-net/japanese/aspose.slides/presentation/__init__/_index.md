---
title: Presentation constructor
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/presentation/__init__/
weight: 10
---
## __init__(self) {#}
This constructor creates new presentation from scratch.
            作成されたプレゼンテーションには、空のスライドが 1 枚含まれます。


```python
def __init__(self):
    ...
```



## __init__(self, load_options) {#loadoptions}
This constructor creates new presentation from scratch.
            作成されたプレゼンテーションには、空のスライドが 1 枚含まれます。


```python
def __init__(self, load_options):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| load_options | [`LoadOptions`](/slides/python-net/ja/aspose.slides/loadoptions) | 追加のロードオプション。 |


## __init__(self, stream) {#iorawiobase}
This constructor is the primary mechanism for reading an existing Presentation.


```python
def __init__(self, stream):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| stream | **io.RawIOBase** | 入力ストリーム。 |


## __init__(self, file) {#str}
This constructor gets a source file path from which
             プレゼンテーションの内容が読み取られます。


```python
def __init__(self, file):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| file | **str** | 入力ファイル。 |

### 例外

| 例外 | 説明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 入力ファイルの長さがゼロの場合にスローされます |


## __init__(self, stream, load_options) {#iorawiobase-loadoptions}
This constructor is the primary mechanism for reading an existing Presentation.


```python
def __init__(self, stream, load_options):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| stream | **io.RawIOBase** | 入力ストリーム。 |
| load_options | [`LoadOptions`](/slides/python-net/ja/aspose.slides/loadoptions) | 追加のロードオプション。 |


## __init__(self, file, load_options) {#str-loadoptions}
This constructor gets a source file path from which
            プレゼンテーションの内容が読み取られます。


```python
def __init__(self, file, load_options):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| file | **str** | 入力ファイル。 |
| load_options | [`LoadOptions`](/slides/python-net/ja/aspose.slides/loadoptions) | 追加のロードオプション。 |

### 例外

| 例外 | 説明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 入力ファイルの長さがゼロの場合にスローされます |



### 参照
* クラス [`LoadOptions`](/slides/python-net/ja/aspose.slides/loadoptions)
* クラス [`Presentation`](/slides/python-net/ja/aspose.slides/presentation)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)