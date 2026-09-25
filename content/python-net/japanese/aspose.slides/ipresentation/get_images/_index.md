---
title: get_images method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/ipresentation/get_images/
weight: 10
---
## get_images(self, options) {#asposeslidesexportirenderingoptions}
プレゼンテーションのすべてのスライドに対する Thumbnail Image オブジェクトを返します。

### 戻り値

Bitmap オブジェクト。



```python
def get_images(self, options):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/ja/aspose.slides.export/irenderingoptions) | レンダリング オプション。 |


## get_images(self, options, slides) {#asposeslidesexportirenderingoptions-listint}
プレゼンテーションの指定されたスライドに対する Thumbnail Bitmap オブジェクトを返します。

### 戻り値

Bitmap オブジェクト。



```python
def get_images(self, options, slides):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/ja/aspose.slides.export/irenderingoptions) | レンダリング オプション。 |
| slides | **List[int]** | 1 から始まるスライド位置の配列。 |


## get_images(self, options, image_size) {#asposeslidesexportirenderingoptions-asposeslidessize}
指定されたサイズでプレゼンテーションのすべてのスライドに対する Thumbnail Image オブジェクトを返します。

### 戻り値

Bitmap オブジェクト。



```python
def get_images(self, options, image_size):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/ja/aspose.slides.export/irenderingoptions) | レンダリング オプション。 |
| image_size | [`Size`](/slides/python-net/ja/aspose.slides/size) | 作成する画像のサイズ。 |


## get_images(self, options, scale_x, scale_y) {#asposeslidesexportirenderingoptions-float-float}
カスタムスケーリングでプレゼンテーションのすべてのスライドに対する Thumbnail Image オブジェクトを返します。

### 戻り値

Bitmap オブジェクト。



```python
def get_images(self, options, scale_x, scale_y):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/ja/aspose.slides.export/irenderingoptions) | レンダリング オプション。 |
| scale_x | **float** | この Thumbnail を x 軸方向にスケールする値。 |
| scale_y | **float** | この Thumbnail を y 軸方向にスケールする値。 |


## get_images(self, options, slides, image_size) {#asposeslidesexportirenderingoptions-listint-asposeslidessize}
指定されたサイズでプレゼンテーションの指定されたスライドに対する Thumbnail Image オブジェクトを返します。

### 戻り値

Bitmap オブジェクト。



```python
def get_images(self, options, slides, image_size):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/ja/aspose.slides.export/irenderingoptions) | レンダリング オプション。 |
| slides | **List[int]** | 1 から始まるスライド位置の配列。 |
| image_size | [`Size`](/slides/python-net/ja/aspose.slides/size) | 作成する画像のサイズ。 |


## get_images(self, options, slides, scale_x, scale_y) {#asposeslidesexportirenderingoptions-listint-float-float}
カスタムスケーリングでプレゼンテーションの指定されたスライドに対する Thumbnail Image オブジェクトを返します。

### 戻り値

Bitmap オブジェクト。



```python
def get_images(self, options, slides, scale_x, scale_y):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/ja/aspose.slides.export/irenderingoptions) | レンダリング オプション。 |
| slides | **List[int]** | 1 から始まるスライド位置の配列。 |
| scale_x | **float** | この Thumbnail を x 軸方向にスケールする値。 |
| scale_y | **float** | この Thumbnail を y 軸方向にスケールする値。 |



### 参照
* クラス [`IPresentation`](/slides/python-net/ja/aspose.slides/ipresentation)
* クラス [`IRenderingOptions`](/slides/python-net/ja/aspose.slides.export/irenderingoptions)
* クラス [`Size`](/slides/python-net/ja/aspose.slides/size)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)