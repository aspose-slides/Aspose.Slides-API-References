---
title: save method
second_title: Aspose.Slides 用於 Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/iimage/save/
weight: 10
---
## save(self, filename) {#str}
將圖像儲存到檔案。


```python
def save(self, filename):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| filename | **str** | 圖像將被儲存的檔案路徑。 |


## save(self, filename, format) {#str-imageformat}
將圖像以指定格式儲存至檔案。


```python
def save(self, filename, format):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| filename | **str** | 圖像將被儲存的檔案路徑。 |
| format | [`ImageFormat`](/slides/python-net/zh-hant/aspose.slides/imageformat) | 圖像格式。 |


## save(self, stream, format) {#iorawiobase-imageformat}
將圖像以指定格式儲存至串流。


```python
def save(self, stream, format):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| stream | **io.RawIOBase** | 圖像將被儲存的串流。 |
| format | [`ImageFormat`](/slides/python-net/zh-hant/aspose.slides/imageformat) | 圖像格式。 |


## save(self, filename, format, quality) {#str-imageformat-int}
將圖像以指定的格式與品質儲存至檔案。


```python
def save(self, filename, format, quality):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| filename | **str** | 圖像將被儲存的檔案路徑。 |
| format | [`ImageFormat`](/slides/python-net/zh-hant/aspose.slides/imageformat) | 圖像格式。 |
| quality | **int** | 已儲存圖像的品質 (0 到 100)。  <br/><br/>            此參數僅在 [`ImageFormat.JPEG`](/slides/python-net/zh-hant/aspose.slides/imageformat/JPEG) 中的儲存時有效；對於所有其他格式，將被忽略。 |


## save(self, stream, format, quality) {#iorawiobase-imageformat-int}
將圖像以指定的格式與品質儲存至串流。


```python
def save(self, stream, format, quality):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| stream | **io.RawIOBase** | 圖像將被儲存的串流。 |
| format | [`ImageFormat`](/slides/python-net/zh-hant/aspose.slides/imageformat) | 圖像格式。 |
| quality | **int** | 已儲存圖像的品質 (0 到 100)。  <br/><br/>            此參數僅在 [`ImageFormat.JPEG`](/slides/python-net/zh-hant/aspose.slides/imageformat/JPEG) 中的儲存時有效；對於所有其他格式，將被忽略。 |



### 另見
* 類 [`IImage`](/slides/python-net/zh-hant/aspose.slides/iimage)
* 列舉 [`ImageFormat`](/slides/python-net/zh-hant/aspose.slides/imageformat)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 程式庫 [`Aspose.Slides`](/slides/python-net)