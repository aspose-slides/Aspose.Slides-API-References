---
title: get_image method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/slide/get_image/
weight: 40
---
## get_image(self) {#}
サムネイル Image オブジェクト (実サイズの 20%) を返します。


```python
def get_image(self):
    ...
```



## get_image(self, image_size) {#asposeslidessize}
指定したサイズのサムネイル Image オブジェクトを返します。

### 戻り値

Image オブジェクト。



```python
def get_image(self, image_size):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| image_size | [`Size`](/slides/python-net/ja/aspose.slides/size) | 作成する画像のサイズ。 |


## get_image(self, options) {#asposeslidesexportitiffoptions}
指定したパラメータでサムネイル tiff 画像オブジェクトを返します。

### 戻り値

Image オブジェクト。



```python
def get_image(self, options):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| options | [`ITiffOptions`](/slides/python-net/ja/aspose.slides.export/itiffoptions) | Tiff オプション。 |

### 例外

| 例外 | 説明 |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | options.SlideLayoutOption が NotesCommentsLayoutingOptions で、プロパティ NotesPosition が NotesPositions.BottomFull の場合にスローされます。 |


## get_image(self, options) {#asposeslidesexportirenderingoptions}
サムネイル Image オブジェクトを返します。

### 戻り値

Image オブジェクト。



```python
def get_image(self, options):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/ja/aspose.slides.export/irenderingoptions) | レンダリング オプション。 |

### 例外

| 例外 | 説明 |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | notesCommentsLayouting.NotesPosition が NotesPositions.BottomFull の場合にスローされます。 |


## get_image(self, scale_x, scale_y) {#float-float}
カスタムスケーリングでサムネイル Image オブジェクトを返します。

### 戻り値

IImage オブジェクト。



```python
def get_image(self, scale_x, scale_y):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| scale_x | **float** | このサムネイルを x 軸方向に拡大する値。 |
| scale_y | **float** | このサムネイルを y 軸方向に拡大する値。 |


## get_image(self, options, image_size) {#asposeslidesexportirenderingoptions-asposeslidessize}
指定したサイズのサムネイル Image オブジェクトを返します。

### 戻り値

Image オブジェクト。



```python
def get_image(self, options, image_size):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/ja/aspose.slides.export/irenderingoptions) | レンダリング オプション。 |
| image_size | [`Size`](/slides/python-net/ja/aspose.slides/size) | 作成する画像のサイズ。 |

### 例外

| 例外 | 説明 |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | options.SlideLayoutOption が NotesCommentsLayoutingOptions で、プロパティ NotesPosition が NotesPositions.BottomFull の場合にスローされます。 |


## get_image(self, options, scale_x, scale_y) {#asposeslidesexportirenderingoptions-float-float}
カスタムスケーリングでサムネイル Image オブジェクトを返します。

### 戻り値

Bitmap オブジェクト。



```python
def get_image(self, options, scale_x, scale_y):
    ...
```


| パラメータ | 型 | 説明 |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/ja/aspose.slides.export/irenderingoptions) | レンダリング オプション。 |
| scale_x | **float** | このサムネイルを x 軸方向に拡大する値。 |
| scale_y | **float** | このサムネイルを y 軸方向に拡大する値。 |

### 例外

| 例外 | 説明 |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | notesCommentsLayouting.NotesPosition が NotesPositions.BottomFull の場合にスローされます。 |



### 参照
* クラス [`IImage`](/slides/python-net/ja/aspose.slides/iimage)
* クラス [`IRenderingOptions`](/slides/python-net/ja/aspose.slides.export/irenderingoptions)
* クラス [`ITiffOptions`](/slides/python-net/ja/aspose.slides.export/itiffoptions)
* クラス [`Slide`](/slides/python-net/ja/aspose.slides/slide)
* クラス [`Size`](/slides/python-net/ja/aspose.slides/size)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)