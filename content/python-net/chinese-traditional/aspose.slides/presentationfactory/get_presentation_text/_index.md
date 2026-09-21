---
title: get_presentation_text method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/presentationfactory/get_presentation_text/
weight: 40
---
## get_presentation_text(self, file, mode) {#str-textextractionarrangingmode}
從投影片中取得原始文字

### 返回

PresentationText 實例，包含表示原始投影片文字的 SlideText 陣列



```python
def get_presentation_text(self, file, mode):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| file | **str** | 輸入檔案 |
| mode | [`TextExtractionArrangingMode`](/slides/python-net/zh-hant/aspose.slides/textextractionarrangingmode) | 抽取模式 |


## get_presentation_text(self, stream, mode) {#iorawiobase-textextractionarrangingmode}
從投影片中取得原始文字

### 返回

PresentationText 實例，包含表示原始投影片文字的 SlideText 陣列



```python
def get_presentation_text(self, stream, mode):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| stream | **io.RawIOBase** | 輸入串流 |
| mode | [`TextExtractionArrangingMode`](/slides/python-net/zh-hant/aspose.slides/textextractionarrangingmode) | 抽取模式 |


## get_presentation_text(self, stream, mode, options) {#iorawiobase-textextractionarrangingmode-iloadoptions}
從投影片中取得原始文字

### 返回

PresentationText 實例，包含表示原始投影片文字的 SlideText 陣列



```python
def get_presentation_text(self, stream, mode, options):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| stream | **io.RawIOBase** | 輸入串流 |
| mode | [`TextExtractionArrangingMode`](/slides/python-net/zh-hant/aspose.slides/textextractionarrangingmode) | 抽取模式 |
| options | [`ILoadOptions`](/slides/python-net/zh-hant/aspose.slides/iloadoptions) | 載入選項 |



### 另見
* 類別 [`ILoadOptions`](/slides/python-net/zh-hant/aspose.slides/iloadoptions)
* 類別 [`IPresentationText`](/slides/python-net/zh-hant/aspose.slides/ipresentationtext)
* 類別 [`PresentationFactory`](/slides/python-net/zh-hant/aspose.slides/presentationfactory)
* 列舉 [`TextExtractionArrangingMode`](/slides/python-net/zh-hant/aspose.slides/textextractionarrangingmode)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)