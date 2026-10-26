---
title: add_image method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/imagecollection/add_image/
weight: 10
---
## add_image(self, image_source) {#ippimage}
別のプレゼンテーションから画像のコピーを追加します。

### 戻り値

追加された画像。

```python
def add_image(self, image_source):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| image_source | [`IPPImage`](/slides/python-net/ja/aspose.slides/ippimage) | ソース画像。 |

## add_image(self, image) {#iimage}
プレゼンテーションに画像を追加します。

### 戻り値

追加された画像。

```python
def add_image(self, image):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| image | [`IImage`](/slides/python-net/ja/aspose.slides/iimage) | 追加する画像。 |

## add_image(self, stream) {#iorawiobase}
ストリームからプレゼンテーションに画像を追加します。

### 戻り値

追加された画像。

```python
def add_image(self, stream):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| stream | **io.RawIOBase** | 画像を追加するストリーム。 |

### 備考

このメソッドは、WMF/EMF メタファイルをラスタ PNG 画像に変換せずにプレゼンテーションに追加できます。

## add_image(self, buffer) {#bytes}
指定されたバッファからプレゼンテーションに画像を追加します。

### 戻り値

追加された画像。

```python
def add_image(self, buffer):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| buffer | **bytes** | バッファ。 |

## add_image(self, svg_image) {#isvgimage}
Svg オブジェクトからプレゼンテーションに画像を追加します。

### 戻り値

追加された画像。

```python
def add_image(self, svg_image):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| svg_image | [`ISvgImage`](/slides/python-net/ja/aspose.slides/isvgimage) | Svg 画像オブジェクト [`ISvgImage`](/slides/python-net/ja/aspose.slides/isvgimage) |

### 例外

| 例外 | 説明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | svgImage パラメータが None の場合。 |

## add_image(self, stream, loading_stream_behavior) {#iorawiobase-loadingstreambehavior}
ストリームからプレゼンテーションに画像を作成し、追加します。

### 戻り値

追加された [`IPPImage`](/slides/python-net/ja/aspose.slides/ippimage)。

```python
def add_image(self, stream, loading_stream_behavior):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| stream | **io.RawIOBase** | 画像ファイルを追加するストリーム。 |
| loading_stream_behavior | [`LoadingStreamBehavior`](/slides/python-net/ja/aspose.slides/loadingstreambehavior) | ストリームに適用される動作。 |

### 参照
* クラス [`IImage`](/slides/python-net/ja/aspose.slides/iimage)
* クラス [`ImageCollection`](/slides/python-net/ja/aspose.slides/imagecollection)
* クラス [`IPPImage`](/slides/python-net/ja/aspose.slides/ippimage)
* クラス [`ISvgImage`](/slides/python-net/ja/aspose.slides/isvgimage)
* 列挙体 [`LoadingStreamBehavior`](/slides/python-net/ja/aspose.slides/loadingstreambehavior)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)