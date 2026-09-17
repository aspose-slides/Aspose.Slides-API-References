---
title: get_images method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/ipresentation/get_images/
weight: 10
---
## get_images(self, options) {#asposeslidesexportirenderingoptions}
プレゼンテーションのすべてのスライドに対するサムネイル画像オブジェクトを返します。

### 戻り値

Bitmap オブジェクト。

```python
def get_images(self, options):
    ...
```

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/ja/aspose.slides.export/irenderingoptions) | レンダリングオプション。 |

## get_images(self, options, slides) {#asposeslidesexportirenderingoptions-listint}
プレゼンテーションの指定されたスライドに対するサムネイル Bitmap オブジェクトを返します。

### 戻り値

Bitmap オブジェクト。

```python
def get_images(self, options, slides):
    ...
```

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/ja/aspose.slides.export/irenderingoptions) | レンダリングオプション。 |
| slides | **List[int]** | スライド位置の配列（1 から始まります）。 |

## get_images(self, options, image_size) {#asposeslidesexportirenderingoptions-asposepydrawingsize}
プレゼンテーションのすべてのスライドに対し、指定されたサイズのサムネイル画像オブジェクトを返します。

### 戻り値

Bitmap オブジェクト。

```python
def get_images(self, options, image_size):
    ...
```

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/ja/aspose.slides.export/irenderingoptions) | レンダリングオプション。 |
| image_size | **aspose.slides.Size** | 作成する画像のサイズ。 |

## get_images(self, options, scale_x, scale_y) {#asposeslidesexportirenderingoptions-float-float}
プレゼンテーションのすべてのスライドに対し、カスタムスケーリングを使用したサムネイル画像オブジェクトを返します。

### 戻り値

Bitmap オブジェクト。

```python
def get_images(self, options, scale_x, scale_y):
    ...
```

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/ja/aspose.slides.export/irenderingoptions) | レンダリングオプション。 |
| scale_x | **float** | x 軸方向にこのサムネイルをスケーリングする値。 |
| scale_y | **float** | y 軸方向にこのサムネイルをスケーリングする値。 |

## get_images(self, options, slides, image_size) {#asposeslidesexportirenderingoptions-listint-asposepydrawingsize}
プレゼンテーションの指定されたスライドに対し、指定されたサイズのサムネイル画像オブジェクトを返します。

### 戻り値

Bitmap オブジェクト。

```python
def get_images(self, options, slides, image_size):
    ...
```

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/ja/aspose.slides.export/irenderingoptions) | レンダリングオプション。 |
| slides | **List[int]** | スライド位置の配列（1 から始まります）。 |
| image_size | **aspose.slides.Size** | 作成する画像のサイズ。 |

## get_images(self, options, slides, scale_x, scale_y) {#asposeslidesexportirenderingoptions-listint-float-float}
プレゼンテーションの指定されたスライドに対し、カスタムスケーリングを使用したサムネイル画像オブジェクトを返します。

### 戻り値

Bitmap オブジェクト。

```python
def get_images(self, options, slides, scale_x, scale_y):
    ...
```

| パラメーター | タイプ | 説明 |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/ja/aspose.slides.export/irenderingoptions) | レンダリングオプション。 |
| slides | **List[int]** | スライド位置の配列（1 から始まります）。 |
| scale_x | **float** | x 軸方向にこのサムネイルをスケーリングする値。 |
| scale_y | **float** | y 軸方向にこのサムネイルをスケーリングする値。 |

### 参照
* クラス [`IPresentation`](/slides/python-net/ja/aspose.slides/ipresentation)
* クラス [`IRenderingOptions`](/slides/python-net/ja/aspose.slides.export/irenderingoptions)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)