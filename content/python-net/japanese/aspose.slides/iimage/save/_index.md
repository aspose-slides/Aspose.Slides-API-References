---
title: save method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/iimage/save/
weight: 10
---
## save(self, filename) {#str}
画像をファイルに保存します。


```python
def save(self, filename):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| filename | **str** | 画像が保存されるファイルへのパスです。 |


## save(self, filename, format) {#str-imageformat}
指定された形式で画像をファイルに保存します。


```python
def save(self, filename, format):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| filename | **str** | 画像が保存されるファイルへのパスです。 |
| format | [`ImageFormat`](/slides/python-net/ja/aspose.slides/imageformat) | 画像形式です。 |


## save(self, stream, format) {#iorawiobase-imageformat}
指定された形式で画像をストリームに保存します。


```python
def save(self, stream, format):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| stream | **io.RawIOBase** | 画像が保存されるストリームです。 |
| format | [`ImageFormat`](/slides/python-net/ja/aspose.slides/imageformat) | 画像形式です。 |


## save(self, filename, format, quality) {#str-imageformat-int}
指定された形式と品質で画像をファイルに保存します。


```python
def save(self, filename, format, quality):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| filename | **str** | 画像が保存されるファイルへのパスです。 |
| format | [`ImageFormat`](/slides/python-net/ja/aspose.slides/imageformat) | 画像形式です。 |
| quality | **int** | 保存される画像の品質 (0 から 100)。<br/><br/>このパラメータは [`ImageFormat.JPEG`](/slides/python-net/ja/aspose.slides/imageformat/JPEG) での保存にのみ影響し、他のすべての形式では無視されます。 |


## save(self, stream, format, quality) {#iorawiobase-imageformat-int}
指定された形式と品質で画像をストリームに保存します。


```python
def save(self, stream, format, quality):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| stream | **io.RawIOBase** | 画像が保存されるストリームです。 |
| format | [`ImageFormat`](/slides/python-net/ja/aspose.slides/imageformat) | 画像形式です。 |
| quality | **int** | 保存される画像の品質 (0 から 100)。<br/><br/>このパラメータは [`ImageFormat.JPEG`](/slides/python-net/ja/aspose.slides/imageformat/JPEG) での保存にのみ影響し、他のすべての形式では無視されます。 |



### 参照
* クラス [`IImage`](/slides/python-net/ja/aspose.slides/iimage)
* 列挙体 [`ImageFormat`](/slides/python-net/ja/aspose.slides/imageformat)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)