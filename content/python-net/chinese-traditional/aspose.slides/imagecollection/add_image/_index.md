---
title: add_image method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/imagecollection/add_image/
weight: 10
---
## add_image(self, image_source) {#ippimage}
新增一個來自其他簡報的影像副本。

### 回傳值

已新增的影像。



```python
def add_image(self, image_source):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| image_source | [`IPPImage`](/slides/python-net/zh-hant/aspose.slides/ippimage) | Source image. |


## add_image(self, image) {#iimage}
將影像加入簡報。

### 回傳值

已新增的影像。



```python
def add_image(self, image):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| image | [`IImage`](/slides/python-net/zh-hant/aspose.slides/iimage) | Image to add. |

### 備註

此方法會在插入簡報之前，將 WMF/EMF 中繪圖檔轉換為點陣 PNG 影像。


## add_image(self, stream) {#iorawiobase}
從串流將影像加入簡報。

### 回傳值

已新增的影像。



```python
def add_image(self, stream):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| stream | **io.RawIOBase** | Stream to add image from. |

### 備註

此方法可在不將 WMF/EMF 中繪圖檔轉換為點陣 PNG 影像的情況下，將其加入簡報。


## add_image(self, buffer) {#bytes}
從指定的緩衝區新增影像至簡報。

### 回傳值

已新增的影像。



```python
def add_image(self, buffer):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| buffer | **bytes** | Buffer. |


## add_image(self, svg_image) {#isvgimage}
從 Svg 物件將影像加入簡報。

### 回傳值

已新增的影像。



```python
def add_image(self, svg_image):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| svg_image | [`ISvgImage`](/slides/python-net/zh-hant/aspose.slides/isvgimage) | Svg 圖像物件 [`ISvgImage`](/slides/python-net/zh-hant/aspose.slides/isvgimage) |

### 例外情況

| 例外 | 說明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | 當 svgImage 參數為 None 時。 |


## add_image(self, stream, loading_stream_behavior) {#iorawiobase-loadingstreambehavior}
從串流建立並將影像加入簡報。

### 回傳值

已新增 [`IPPImage`](/slides/python-net/zh-hant/aspose.slides/ippimage)。



```python
def add_image(self, stream, loading_stream_behavior):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| stream | **io.RawIOBase** | Stream to add image file from. |
| loading_stream_behavior | [`LoadingStreamBehavior`](/slides/python-net/zh-hant/aspose.slides/loadingstreambehavior) | The behavior which will be applied to the stream. |



### 另請參閱
* 類別 [`IImage`](/slides/python-net/zh-hant/aspose.slides/iimage)
* 類別 [`ImageCollection`](/slides/python-net/zh-hant/aspose.slides/imagecollection)
* 類別 [`IPPImage`](/slides/python-net/zh-hant/aspose.slides/ippimage)
* 類別 [`ISvgImage`](/slides/python-net/zh-hant/aspose.slides/isvgimage)
* 列舉 [`LoadingStreamBehavior`](/slides/python-net/zh-hant/aspose.slides/loadingstreambehavior)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)