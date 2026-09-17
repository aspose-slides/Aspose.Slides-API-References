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

### 返り値

Image オブジェクト。

```python
def get_images(self, options):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/ja/aspose.slides.export/irenderingoptions) | Tiff オプション。 |


## get_images(self, options, slides) {#asposeslidesexportirenderingoptions-listint}
指定されたスライドのサムネイル Image オブジェクトを返します。

### 返り値

Image オブジェクト。

```python
def get_images(self, options, slides):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/ja/aspose.slides.export/irenderingoptions) | Tiff オプション。 |
| slides | **List[int]** | 1 から始まるスライド位置の配列。 |


## get_images(self, options, image_size) {#asposeslidesexportirenderingoptions-asposepydrawingsize}
指定されたサイズでプレゼンテーションのすべてのスライドのサムネイル Image オブジェクトを返します。

### 返り値

Image オブジェクト。

```python
def get_images(self, options, image_size):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/ja/aspose.slides.export/irenderingoptions) | Tiff オプション。 |
| image_size | **aspose.slides.Size** | 作成する画像のサイズ。 |


## get_images(self, options, scale_x, scale_y) {#asposeslidesexportirenderingoptions-float-float}
カスタムスケーリングでプレゼンテーションのすべてのスライドのサムネイル Image オブジェクトを返します。

### 返り値

Image オブジェクト。

```python
def get_images(self, options, scale_x, scale_y):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/ja/aspose.slides.export/irenderingoptions) | Tiff オプション。 |
| scale_x | **float** | x 軸方向にこのサムネイルをスケールする値。 |
| scale_y | **float** | y 軸方向にこのサムネイルをスケールする値。 |


## get_images(self, options, slides, image_size) {#asposeslidesexportirenderingoptions-listint-asposepydrawingsize}
指定されたサイズで、指定されたスライドのサムネイル Image オブジェクトを返します。

### 返り値

Image オブジェクト。

```python
def get_images(self, options, slides, image_size):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/ja/aspose.slides.export/irenderingoptions) | Tiff オプション。 |
| slides | **List[int]** | 1 から始まるスライド位置の配列。 |
| image_size | **aspose.slides.Size** | 作成する画像のサイズ。 |


## get_images(self, options, slides, scale_x, scale_y) {#asposeslidesexportirenderingoptions-listint-float-float}
カスタムスケーリングで、指定されたスライドのサムネイル Image オブジェクトを返します。

### 返り値

Image オブジェクト。

```python
def get_images(self, options, slides, scale_x, scale_y):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/ja/aspose.slides.export/irenderingoptions) | Tiff オプション。 |
| slides | **List[int]** | 1 から始まるスライド位置の配列。 |
| scale_x | **float** | x 軸方向にこのサムネイルをスケールする値。 |
| scale_y | **float** | y 軸方向にこのサムネイルをスケールする値。 |

### 参照
* クラス [`IRenderingOptions`](/slides/python-net/ja/aspose.slides.export/irenderingoptions)
* クラス [`Presentation`](/slides/python-net/ja/aspose.slides/presentation)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)