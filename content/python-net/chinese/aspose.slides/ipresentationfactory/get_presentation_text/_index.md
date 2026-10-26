---
title: get_presentation_text method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/ipresentationfactory/get_presentation_text/
weight: 30
---
## get_presentation_text(self, file, mode) {#str-textextractionarrangingmode}
检索幻灯片的原始文本

### 返回值

包含表示原始幻灯片文本的 SlideText 数组的 PresentationText 实例



```python
def get_presentation_text(self, file, mode):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| file | **str** | 输入文件 |
| mode | [`TextExtractionArrangingMode`](/slides/python-net/zh/aspose.slides/textextractionarrangingmode) | 提取模式 |


## get_presentation_text(self, stream, mode) {#iorawiobase-textextractionarrangingmode}
检索幻灯片的原始文本

### 返回值

包含表示原始幻灯片文本的 SlideText 数组的 PresentationText 实例



```python
def get_presentation_text(self, stream, mode):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| stream | **io.RawIOBase** | 输入流 |
| mode | [`TextExtractionArrangingMode`](/slides/python-net/zh/aspose.slides/textextractionarrangingmode) | 提取模式 |


## get_presentation_text(self, stream, mode, options) {#iorawiobase-textextractionarrangingmode-iloadoptions}
检索幻灯片的原始文本

### 返回值

包含表示原始幻灯片文本的 SlideText 数组的 PresentationText 实例



```python
def get_presentation_text(self, stream, mode, options):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| stream | **io.RawIOBase** | 输入流 |
| mode | [`TextExtractionArrangingMode`](/slides/python-net/zh/aspose.slides/textextractionarrangingmode) | 提取模式 |
| options | [`ILoadOptions`](/slides/python-net/zh/aspose.slides/iloadoptions) | 加载选项 |



### 另见
* 类 [`ILoadOptions`](/slides/python-net/zh/aspose.slides/iloadoptions)
* 类 [`IPresentationFactory`](/slides/python-net/zh/aspose.slides/ipresentationfactory)
* 类 [`IPresentationText`](/slides/python-net/zh/aspose.slides/ipresentationtext)
* 枚举 [`TextExtractionArrangingMode`](/slides/python-net/zh/aspose.slides/textextractionarrangingmode)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)