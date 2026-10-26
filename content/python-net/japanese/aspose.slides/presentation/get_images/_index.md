---
title: get_images method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/presentation/get_images/
weight: 20
---
## get_images(self, options) {#asposeslidesexportirenderingoptions}
プレゼンテーションのすべてのスライドの Image オブジェクトを返します。

### 戻り値
Image オブジェクト。

```python
def get_images(self, options):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/ja/aspose.slides.export/irenderingoptions) | Tiff オプション。 |


## get_images(self, options, slides) {#asposeslidesexportirenderingoptions-listint}
指定されたスライドの Thumbnail Image オブジェクトを返します。

### 戻り値
Image オブジェクト。

```python
def get_images(self, options, slides):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/ja/aspose.slides.export/irenderingoptions) | Tiff オプション。 |
| slides | **List[int]** | スライド位置の配列（1 から開始）。 |


## get_images(self, options, image_size) {#asposeslidesexportirenderingoptions-asposeslidessize}
指定されたサイズでプレゼンテーションのすべてのスライドの Thumbnail Image オブジェクトを返します。

### 戻り値
Image オブジェクト。

```python
def get_images(self, options, image_size):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/ja/aspose.slides.export/irenderingoptions) | Tiff オプション。 |
| image_size | [`Size`](/slides/python-net/ja/aspose.slides/size) | 作成する画像のサイズ。 |


## get_images(self, options, scale_x, scale_y) {#asposeslidesexportirenderingoptions-float-float}
カスタムスケーリングでプレゼンテーションのすべてのスライドの Thumbnail Image オブジェクトを返します。

### 戻り値
Image オブジェクト。

```python
def get_images(self, options, scale_x, scale_y):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/ja/aspose.slides.export/irenderingoptions) | Tiff オプション。 |
| scale_x | **float** | x 軸方向にこの Thumbnail をスケーリングする値。 |
| scale_y | **float** | y 軸方向にこの Thumbnail をスケーリングする値。 |


## get_images(self, options, slides, image_size) {#asposeslidesexportirenderingoptions-listint-asposeslidessize}
指定されたサイズで指定されたスライドの Thumbnail Image オブジェクトを返します。

### 戻り値
Image オブジェクト。

```python
def get_images(self, options, slides, image_size):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/ja/aspose.slides.export/irenderingoptions) | Tiff オプション。 |
| slides | **List[int]** | スライド位置の配列（1 から開始）。 |
| image_size | [`Size`](/slides/python-net/ja/aspose.slides/size) | 作成する画像のサイズ。 |


## get_images(self, options, slides, scale_x, scale_y) {#asposeslidesexportirenderingoptions-listint-float-float}
指定されたスライドのカスタムスケーリングで Thumbnail Image オブジェクトを返します。

### 戻り値
Image オブジェクト。

```python
def get_images(self, options, slides, scale_x, scale_y):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/ja/aspose.slides.export/irenderingoptions) | Tiff オプション。 |
| slides | **List[int]** | スライド位置の配列（1 から開始）。 |
| scale_x | **float** | x 軸方向にこの Thumbnail をスケーリングする値。 |
| scale_y | **float** | y 軸方向にこの Thumbnail をスケーリングする値。 |


### 参照
* クラス [`IRenderingOptions`](/slides/python-net/ja/aspose.slides.export/irenderingoptions)
* クラス [`Presentation`](/slides/python-net/ja/aspose.slides/presentation)
* クラス [`Size`](/slides/python-net/ja/aspose.slides/size)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)