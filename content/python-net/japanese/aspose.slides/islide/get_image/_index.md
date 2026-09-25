---
title: get_image method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/islide/get_image/
weight: 40
---
## get_image(self) {#}
指定サイズの20%のサムネイル画像オブジェクトを返します。

### 戻り値

Image object **aspose.slides.IImage**



```python
def get_image(self):
    ...
```



## get_image(self, image_size) {#asposeslidessize}
指定されたサイズの画像オブジェクトを返します。

### 戻り値

Bitmap object.



```python
def get_image(self, image_size):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| image_size | [`Size`](/slides/python-net/ja/aspose.slides/size) | 作成する画像のサイズ。 |


## get_image(self, options) {#asposeslidesexportitiffoptions}
指定されたパラメータでサムネイル TIFF ビットマップオブジェクトを返します。

### 戻り値

Image object.



```python
def get_image(self, options):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| options | [`ITiffOptions`](/slides/python-net/ja/aspose.slides.export/itiffoptions) | TIFF オプション。 |


## get_image(self, options) {#asposeslidesexportirenderingoptions}
サムネイルビットマップオブジェクトを返します。

### 戻り値

Bitmap objects.



```python
def get_image(self, options):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/ja/aspose.slides.export/irenderingoptions) | レンダリング オプション。 |


## get_image(self, scale_x, scale_y) {#float-float}
カスタムスケーリングされた画像オブジェクトを返します。

### 戻り値

Image object **aspose.slides.IImage**



```python
def get_image(self, scale_x, scale_y):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| scale_x | **float** | X 軸方向にこのサムネイルを拡大縮小する値。 |
| scale_y | **float** | Y 軸方向にこのサムネイルを拡大縮小する値。 |


## get_image(self, options, image_size) {#asposeslidesexportirenderingoptions-asposeslidessize}
指定されたサイズのサムネイルビットマップオブジェクトを返します。

### 戻り値

Bitmap objects.



```python
def get_image(self, options, image_size):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/ja/aspose.slides.export/irenderingoptions) | レンダリング オプション。 |
| image_size | [`Size`](/slides/python-net/ja/aspose.slides/size) | 作成する画像のサイズ。 |


## get_image(self, options, scale_x, scale_y) {#asposeslidesexportirenderingoptions-float-float}
カスタムスケーリングされたサムネイルビットマップオブジェクトを返します。

### 戻り値

Bitmap objects.



```python
def get_image(self, options, scale_x, scale_y):
    ...
```

| パラメータ | 型 | 説明 |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/ja/aspose.slides.export/irenderingoptions) | レンダリング オプション。 |
| scale_x | **float** | X 軸方向にこのサムネイルを拡大縮小する値。 |
| scale_y | **float** | Y 軸方向にこのサムネイルを拡大縮小する値。 |



### 参照
* クラス [`IImage`](/slides/python-net/ja/aspose.slides/iimage)
* クラス [`IRenderingOptions`](/slides/python-net/ja/aspose.slides.export/irenderingoptions)
* クラス [`ISlide`](/slides/python-net/ja/aspose.slides/islide)
* クラス [`ITiffOptions`](/slides/python-net/ja/aspose.slides.export/itiffoptions)
* クラス [`Size`](/slides/python-net/ja/aspose.slides/size)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)