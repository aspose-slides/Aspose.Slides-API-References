---
title: save method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/iimagewrapper/save/
weight: 10
---
## save(self, file_name) {#str}
指定されたファイルに画像を保存します

```python
def save(self, file_name):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| file_name | **str** | ファイル名 **str** |

## save(self, stream, image_format) {#iorawiobase-ppimageformat}
指定されたフォーマットで画像を指定されたストリームに保存します。

```python
def save(self, stream, image_format):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| stream | **io.RawIOBase** | 画像を保存するストリーム **io.RawIOBase** |
| image_format | [`PPImageFormat`](/slides/python-net/ja/aspose.slides/ppimageformat) | 画像形式 [`PPImageFormat`](/slides/python-net/ja/aspose.slides/ppimageformat) |

## save(self, file_name, image_format) {#str-ppimageformat}
指定されたフォーマットで画像を指定されたファイルに保存します。

```python
def save(self, file_name, image_format):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| file_name | **str** | ファイル名 **str** |
| image_format | [`PPImageFormat`](/slides/python-net/ja/aspose.slides/ppimageformat) | 画像形式 [`PPImageFormat`](/slides/python-net/ja/aspose.slides/ppimageformat) |

### 参照
* クラス [`IImageWrapper`](/slides/python-net/ja/aspose.slides/iimagewrapper)
* 列挙型 [`PPImageFormat`](/slides/python-net/ja/aspose.slides/ppimageformat)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)