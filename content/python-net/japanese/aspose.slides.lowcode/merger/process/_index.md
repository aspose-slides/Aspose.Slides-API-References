---
title: process method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.lowcode/merger/process/
weight: 10
---
## process(input_file_names, output_file_name) {#liststr-str}
同じ形式の複数のPowerPointプレゼンテーションを単一のプレゼンテーションファイルに結合します。


```python
@staticmethod
def process(input_file_names, output_file_name):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| input_file_names | **List[str]** | 入力プレゼンテーションファイル名の配列。 |
| output_file_name | **str** | 結合されたプレゼンテーションファイルの出力ファイル名。 |

### 例外

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 入力ファイル名が無効または形式が一致しない場合にスローされます。 |


## process(input_file_names, output_stream) {#liststr-iorawiobase}
同じ形式の複数のPowerPointプレゼンテーションを単一のプレゼンテーションファイルに結合します。


```python
@staticmethod
def process(input_file_names, output_stream):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| input_file_names | **List[str]** | 入力プレゼンテーションファイル名の配列。 |
| output_stream | **io.RawIOBase** | 出力ストリーム。 |

### 例外

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 入力ファイル名が無効または形式が一致しない場合にスローされます。 |


## process(input_file_names, output_file_name, options) {#liststr-str-asposeslidesexportisaveoptions}
同じ形式の複数のPowerPointプレゼンテーションを単一のプレゼンテーションファイルに結合します。


```python
@staticmethod
def process(input_file_names, output_file_name, options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| input_file_names | **List[str]** | 入力プレゼンテーションファイル名の配列。 |
| output_file_name | **str** | 結合されたプレゼンテーションファイルの出力ファイル名。 |
| options | [`ISaveOptions`](/slides/python-net/ja/aspose.slides.export/isaveoptions) | 結合されたプレゼンテーションの保存方法を定義する追加オプション。 |

### 例外

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 入力ファイル名が無効または形式が一致しない場合にスローされます。 |


## process(input_file_names, output_stream, options) {#liststr-iorawiobase-asposeslidesexportisaveoptions}
同じ形式の複数のPowerPointプレゼンテーションを単一のプレゼンテーションファイルに結合します。


```python
@staticmethod
def process(input_file_names, output_stream, options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| input_file_names | **List[str]** | 入力プレゼンテーションファイル名の配列。 |
| output_stream | **io.RawIOBase** | 出力ストリーム。 |
| options | [`ISaveOptions`](/slides/python-net/ja/aspose.slides.export/isaveoptions) | 結合されたプレゼンテーションの保存方法を定義する追加オプション。 |

### 例外

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 入力ファイル名が無効または形式が一致しない場合にスローされます。 |



### 参照
* クラス [`ISaveOptions`](/slides/python-net/ja/aspose.slides.export/isaveoptions)
* クラス [`Merger`](/slides/python-net/ja/aspose.slides.lowcode/merger)
* モジュール [`aspose.slides.lowcode`](/slides/python-net/ja/aspose.slides.lowcode)
* ライブラリ [`Aspose.Slides`](/slides/python-net)