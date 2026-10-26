---
title: add_image method
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/iimagecollection/add_image/
weight: 10
---
## add_image(self, image) {#iimage}
將影像新增至簡報。

### 傳回

已加入的影像。

```python
def add_image(self, image):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| image | [`IImage`](/slides/python-net/zh-hant/aspose.slides/iimage) | 要新增的影像。 |

### 備註

此方法會在插入至簡報之前，將 WMF/EMF 中繪圖檔轉換為點陣 PNG 影像。

## add_image(self, stream) {#iorawiobase}
從串流將影像新增至簡報。

### 傳回

已加入的影像。

```python
def add_image(self, stream):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| stream | **io.RawIOBase** | 要從中新增影像的串流。 |

### 備註

此方法可將 WMF/EMF 中繪圖檔新增至簡報，而不需轉換為點陣 PNG 影像。

## add_image(self, buffer) {#bytes}
從指定的緩衝區將影像新增至簡報。

### 傳回

已加入的影像。

```python
def add_image(self, buffer):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| buffer | **bytes** | 緩衝區。 |

## add_image(self, image_source) {#ippimage}
從另一個簡報新增影像的副本。

### 傳回

已加入的影像。

```python
def add_image(self, image_source):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| image_source | [`IPPImage`](/slides/python-net/zh-hant/aspose.slides/ippimage) | 來源影像。 |

## add_image(self, svg_image) {#isvgimage}
從 SVG 物件將影像新增至簡報。

### 傳回

已加入的影像。

```python
def add_image(self, svg_image):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| svg_image | [`ISvgImage`](/slides/python-net/zh-hant/aspose.slides/isvgimage) | SVG 影像物件 [`ISvgImage`](/slides/python-net/zh-hant/aspose.slides/isvgimage) |

### 例外

| 例外 | 說明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | 當 svgImage 參數為 None 時拋出。 |

## add_image(self, stream, loading_stream_behavior) {#iorawiobase-loadingstreambehavior}
從串流建立並將影像新增至簡報。

### 傳回

已加入 [`IPPImage`](/slides/python-net/zh-hant/aspose.slides/ippimage)。

```python
def add_image(self, stream, loading_stream_behavior):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| stream | **io.RawIOBase** | 要從中新增影像檔案的串流。 |
| loading_stream_behavior | [`LoadingStreamBehavior`](/slides/python-net/zh-hant/aspose.slides/loadingstreambehavior) | 將套用於串流的行為。 |

### 另請參閱
* 類別 [`IImage`](/slides/python-net/zh-hant/aspose.slides/iimage)
* 類別 [`IImageCollection`](/slides/python-net/zh-hant/aspose.slides/iimagecollection)
* 類別 [`IPPImage`](/slides/python-net/zh-hant/aspose.slides/ippimage)
* 類別 [`ISvgImage`](/slides/python-net/zh-hant/aspose.slides/isvgimage)
* 列舉 [`LoadingStreamBehavior`](/slides/python-net/zh-hant/aspose.slides/loadingstreambehavior)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 程式庫 [`Aspose.Slides`](/slides/python-net)