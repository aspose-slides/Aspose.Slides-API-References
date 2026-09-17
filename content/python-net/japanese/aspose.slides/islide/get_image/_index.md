---
title: get_image method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/islide/get_image/
weight: 40
---
## get_image(self) {#}
サムネイル画像オブジェクト (実サイズの20%) を返します。

### 戻り値

画像オブジェクト **aspose.slides.Bitmap**



```python
def get_image(self):
    ...
```



## get_image(self, image_size) {#asposepydrawingsize}
指定されたサイズの画像オブジェクトを返します。

### 戻り値

Bitmap オブジェクト。



```python
def get_image(self, image_size):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| image_size | **aspose.slides.Size** | 作成する画像のサイズ。 |


## get_image(self, options) {#asposeslidesexportitiffoptions}
指定されたパラメータでサムネイル TIFF ビットマップオブジェクトを返します。

### 戻り値

画像オブジェクト。



```python
def get_image(self, options):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| options | [`ITiffOptions`](/slides/python-net/ja/aspose.slides.export/itiffoptions) | Tiff オプション。 |


## get_image(self, options) {#asposeslidesexportirenderingoptions}
サムネイル Bitmap オブジェクトを返します。

### 戻り値

Bitmap オブジェクト。



```python
def get_image(self, options):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/ja/aspose.slides.export/irenderingoptions) | レンダリングオプション。 |


## get_image(self, scale_x, scale_y) {#float-float}
カスタムスケーリングで画像オブジェクトを返します。

### 戻り値

画像オブジェクト **aspose.slides.Bitmap**



```python
def get_image(self, scale_x, scale_y):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| scale_x | **float** | このサムネイルを x 軸方向に拡大縮小する値。 |
| scale_y | **float** | このサムネイルを y 軸方向に拡大縮小する値。 |


## get_image(self, options, image_size) {#asposeslidesexportirenderingoptions-asposepydrawingsize}
指定されたサイズでサムネイル Bitmap オブジェクトを返します。

### 戻り値

Bitmap オブジェクト。



```python
def get_image(self, options, image_size):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/ja/aspose.slides.export/irenderingoptions) | レンダリングオプション。 |
| image_size | **aspose.slides.Size** | 作成する画像のサイズ。 |


## get_image(self, options, scale_x, scale_y) {#asposeslidesexportirenderingoptions-float-float}
カスタムスケーリングでサムネイル Bitmap オブジェクトを返します。

### 戻り値

Bitmap オブジェクト。



```python
def get_image(self, options, scale_x, scale_y):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/ja/aspose.slides.export/irenderingoptions) | レンダリングオプション。 |
| scale_x | **float** | このサムネイルを x 軸方向に拡大縮小する値。 |
| scale_y | **float** | このサムネイルを y 軸方向に拡大縮小する値。 |



### 参照
* クラス [`IImage`](/slides/python-net/ja/aspose.slides/iimage)
* クラス [`IRenderingOptions`](/slides/python-net/ja/aspose.slides.export/irenderingoptions)
* クラス [`ISlide`](/slides/python-net/ja/aspose.slides/islide)
* クラス [`ITiffOptions`](/slides/python-net/ja/aspose.slides.export/itiffoptions)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)