---
title: get_image method
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/slide/get_image/
weight: 40
---
## get_image(self) {#}
傳回一個 Thumbnail Image 物件（實際大小的 20%）。

```python
def get_image(self):
    ...
```

## get_image(self, image_size) {#asposeslidessize}
傳回一個 Thumbnail Image 物件，使用指定的大小。

### 返回值

Image 物件。

```python
def get_image(self, image_size):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| image_size | [`Size`](/slides/python-net/zh-hant/aspose.slides/size) | 要建立的影像大小。 |

## get_image(self, options) {#asposeslidesexportitiffoptions}
傳回一個 Thumbnail tiff 影像物件，使用指定的參數。

### 返回值

Image 物件。

```python
def get_image(self, options):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| options | [`ITiffOptions`](/slides/python-net/zh-hant/aspose.slides.export/itiffoptions) | Tiff 選項。 |

### 例外情況

| 例外 | 說明 |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | 當 options.SlideLayoutOption 為 NotesCommentsLayoutingOptions 且其屬性 NotesPosition 取得值 NotesPositions.BottomFull 時拋出此例外。 |

## get_image(self, options) {#asposeslidesexportirenderingoptions}
傳回一個 Thumbnail Image 物件。

### 返回值

Image 物件。

```python
def get_image(self, options):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/zh-hant/aspose.slides.export/irenderingoptions) | Rendering 選項。 |

### 例外情況

| 例外 | 說明 |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | 當 notesCommentsLayouting.NotesPosition 取得值 NotesPositions.BottomFull 時拋出此例外。 |

## get_image(self, scale_x, scale_y) {#float-float}
傳回一個 Thumbnail Image 物件，使用自訂縮放。

### 返回值

IImage 物件。

```python
def get_image(self, scale_x, scale_y):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| scale_x | **float** | 用於在 X 軸方向上縮放此 Thumbnail 的數值。 |
| scale_y | **float** | 用於在 Y 軸方向上縮放此 Thumbnail 的數值。 |

## get_image(self, options, image_size) {#asposeslidesexportirenderingoptions-asposeslidessize}
傳回一個 Thumbnail Image 物件，使用指定的大小。

### 返回值

Image 物件。

```python
def get_image(self, options, image_size):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/zh-hant/aspose.slides.export/irenderingoptions) | Rendering 選項。 |
| image_size | [`Size`](/slides/python-net/zh-hant/aspose.slides/size) | 要建立的影像大小。 |

### 例外情況

| 例外 | 說明 |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | 當 options.SlideLayoutOption 為 NotesCommentsLayoutingOptions 且其屬性 NotesPosition 取得值 NotesPositions.BottomFull 時拋出此例外。 |

## get_image(self, options, scale_x, scale_y) {#asposeslidesexportirenderingoptions-float-float}
傳回一個 Thumbnail Image 物件，使用自訂縮放。

### 返回值

Bitmap 物件。

```python
def get_image(self, options, scale_x, scale_y):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| options | [`IRenderingOptions`](/slides/python-net/zh-hant/aspose.slides.export/irenderingoptions) | Rendering 選項。 |
| scale_x | **float** | 用於在 X 軸方向上縮放此 Thumbnail 的數值。 |
| scale_y | **float** | 用於在 Y 軸方向上縮放此 Thumbnail 的數值。 |

### 例外情況

| 例外 | 說明 |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | 當 notesCommentsLayouting.NotesPosition 取得值 NotesPositions.BottomFull 時拋出此例外。 |

### 另請參閱
* 類別 [`IImage`](/slides/python-net/zh-hant/aspose.slides/iimage)
* 類別 [`IRenderingOptions`](/slides/python-net/zh-hant/aspose.slides.export/irenderingoptions)
* 類別 [`ITiffOptions`](/slides/python-net/zh-hant/aspose.slides.export/itiffoptions)
* 類別 [`Slide`](/slides/python-net/zh-hant/aspose.slides/slide)
* 類別 [`Size`](/slides/python-net/zh-hant/aspose.slides/size)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)