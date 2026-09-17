---
title: get_image method
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/slide/get_image/
weight: 40
---
## get_image(self) {#}
サムネイル Image オブジェクトを返します（実際のサイズの20％）。

```python
def get_image(self):
    ...
```

## get_image(self, image_size) {#asposepydrawingsize}
指定されたサイズのサムネイル Image オブジェクトを返します。

### 戻り値

Image オブジェクト。

```python
def get_image(self, image_size):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| image_size | **aspose.slides.Size** | 作成する画像のサイズ。 |

## get_image(self, options) {#asposeslidesexportitiffoptions}
指定されたパラメーターでサムネイル tiff Image オブジェクトを返します。

### 戻り値

Image オブジェクト。

```python
def get_image(self, options):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| options | [`ITiffOptions`](/slides/python-net/ja/aspose.slides.export/itiffoptions) | Tiff オプション。 |

### 例外

| 例外 | 説明 |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | options.SlideLayoutOption が NotesCommentsLayoutingOptions で、そのプロパティ NotesPosition が NotesPositions.BottomFull の値を取る場合にスローされます。 |

## get_image(self, options) {#asposeslidesexportirenderingoptions}
サムネイル Image オブジェクトを返します。

### 戻り値

Image オブジェクト。

```python
def get_image(self, options):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/ja/aspose.slides.export/irenderingoptions) | レンダリング オプション。 |

### 例外

| 例外 | 説明 |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | notesCommentsLayouting.NotesPosition が NotesPositions.BottomFull の値を取る場合にスローされます。 |

## get_image(self, scale_x, scale_y) {#float-float}
カスタムスケーリングでサムネイル Image オブジェクトを返します。

### 戻り値

IImage オブジェクト。

```python
def get_image(self, scale_x, scale_y):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| scale_x | **float** | X 軸方向にこのサムネイルを拡大縮小する値。 |
| scale_y | **float** | Y 軸方向にこのサムネイルを拡大縮小する値。 |

## get_image(self, options, image_size) {#asposeslidesexportirenderingoptions-asposepydrawingsize}
指定されたサイズのサムネイル Image オブジェクトを返します。

### 戻り値

Image オブジェクト。

```python
def get_image(self, options, image_size):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/ja/aspose.slides.export/irenderingoptions) | レンダリング オプション。 |
| image_size | **aspose.slides.Size** | 作成する画像のサイズ。 |

### 例外

| 例外 | 説明 |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | options.SlideLayoutOption が NotesCommentsLayoutingOptions で、そのプロパティ NotesPosition が NotesPositions.BottomFull の値を取る場合にスローされます。 |

## get_image(self, options, scale_x, scale_y) {#asposeslidesexportirenderingoptions-float-float}
カスタムスケーリングでサムネイル Image オブジェクトを返します。

### 戻り値

Bitmap オブジェクト。

```python
def get_image(self, options, scale_x, scale_y):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/ja/aspose.slides.export/irenderingoptions) | レンダリング オプション。 |
| scale_x | **float** | X 軸方向にこのサムネイルを拡大縮小する値。 |
| scale_y | **float** | Y 軸方向にこのサムネイルを拡大縮小する値。 |

### 例外

| 例外 | 説明 |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | notesCommentsLayouting.NotesPosition が NotesPositions.BottomFull の値を取る場合にスローされます。 |

### 参照
* クラス [`IImage`](/slides/python-net/ja/aspose.slides/iimage)
* クラス [`IRenderingOptions`](/slides/python-net/ja/aspose.slides.export/irenderingoptions)
* クラス [`ITiffOptions`](/slides/python-net/ja/aspose.slides.export/itiffoptions)
* クラス [`Slide`](/slides/python-net/ja/aspose.slides/slide)
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)