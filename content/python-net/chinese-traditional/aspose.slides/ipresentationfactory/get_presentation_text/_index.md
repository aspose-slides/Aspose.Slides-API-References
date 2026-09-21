---
title: get_presentation_text method
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/ipresentationfactory/get_presentation_text/
weight: 30
---
## get_presentation_text(self, file, mode) {#str-textextractionarrangingmode}
取得投影片的原始文字

### Returns
返回
PresentationText 實例，內含表示投影片原始文字之 SlideText 陣列



```python
def get_presentation_text(self, file, mode):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| file | **str** | 輸入檔案 |
| mode | [`TextExtractionArrangingMode`](/slides/python-net/zh-hant/aspose.slides/textextractionarrangingmode) | 擷取模式 |


## get_presentation_text(self, stream, mode) {#iorawiobase-textextractionarrangingmode}
取得投影片的原始文字

### Returns
返回
PresentationText 實例，內含表示投影片原始文字之 SlideText 陣列



```python
def get_presentation_text(self, stream, mode):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| stream | **io.RawIOBase** | 輸入串流 |
| mode | [`TextExtractionArrangingMode`](/slides/python-net/zh-hant/aspose.slides/textextractionarrangingmode) | 擷取模式 |


## get_presentation_text(self, stream, mode, options) {#iorawiobase-textextractionarrangingmode-iloadoptions}
取得投影片的原始文字

### Returns
返回
PresentationText 實例，內含表示投影片原始文字之 SlideText 陣列



```python
def get_presentation_text(self, stream, mode, options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| stream | **io.RawIOBase** | 輸入串流 |
| mode | [`TextExtractionArrangingMode`](/slides/python-net/zh-hant/aspose.slides/textextractionarrangingmode) | 擷取模式 |
| options | [`ILoadOptions`](/slides/python-net/zh-hant/aspose.slides/iloadoptions) | 載入選項 |



### See Also
* class [`ILoadOptions`](/slides/python-net/zh-hant/aspose.slides/iloadoptions)
* class [`IPresentationFactory`](/slides/python-net/zh-hant/aspose.slides/ipresentationfactory)
* class [`IPresentationText`](/slides/python-net/zh-hant/aspose.slides/ipresentationtext)
* enumeration [`TextExtractionArrangingMode`](/slides/python-net/zh-hant/aspose.slides/textextractionarrangingmode)
* module [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)