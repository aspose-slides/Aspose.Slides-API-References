---
title: TextToHtmlConversionOptions
second_title: Aspose.Slides for Java API 参考
description: 从 Pptx 文本提取 HTML 的选项。
type: docs
url: /zh/com.aspose.slides/texttohtmlconversionoptions/
---
**继承：**
java.lang.Object

**所有实现的接口：**
[com.aspose.slides.ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions)
```
public final class TextToHtmlConversionOptions implements ITextToHtmlConversionOptions
```

从 Pptx 文本提取 HTML 的选项。
## 构造函数

| 构造函数 | 说明 |
| --- | --- |
| [TextToHtmlConversionOptions()](#TextToHtmlConversionOptions--) |  |
## 方法

| 方法 | 说明 |
| --- | --- |
| [getAddClipboardFragmentHeader()](#getAddClipboardFragmentHeader--) | 返回或设置值，指示是否应添加 Clipboard 标头。 |
| [setAddClipboardFragmentHeader(boolean value)](#setAddClipboardFragmentHeader-boolean-) | 返回或设置值，指示是否应添加 Clipboard 标头。 |
| [getTextInheritanceLimit()](#getTextInheritanceLimit--) | 返回或设置文本属性的继承深度。 |
| [setTextInheritanceLimit(int value)](#setTextInheritanceLimit-int-) | 返回或设置文本属性的继承深度。 |
| [getLinkEmbedController()](#getLinkEmbedController--) | 返回或设置一个回调对象，该对象控制外部对象的存储方式。 |
| [setLinkEmbedController(ILinkEmbedController value)](#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-) | 返回或设置一个回调对象，该对象控制外部对象的存储方式。 |
| [getEncodingName()](#getEncodingName--) | 返回或设置 html 编码名称。 |
| [setEncodingName(String value)](#setEncodingName-java.lang.String-) | 返回或设置 html 编码名称。 |
### TextToHtmlConversionOptions() {#TextToHtmlConversionOptions--}
```
public TextToHtmlConversionOptions()
```


### getAddClipboardFragmentHeader() {#getAddClipboardFragmentHeader--}
```
public final boolean getAddClipboardFragmentHeader()
```


返回或设置值，指示是否应添加 Clipboard 标头。可读写 boolean。

**返回值：**
boolean
### setAddClipboardFragmentHeader(boolean value) {#setAddClipboardFragmentHeader-boolean-}
```
public final void setAddClipboardFragmentHeader(boolean value)
```


返回或设置值，指示是否应添加 Clipboard 标头。可读写 boolean。

**参数：**
| 参数 | 类型 | 说明 |
| --- | --- | --- |
| value | boolean |  |

### getTextInheritanceLimit() {#getTextInheritanceLimit--}
```
public final int getTextInheritanceLimit()
```


返回或设置文本属性的继承深度。可读写 [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit)。

**返回值：**
int
### setTextInheritanceLimit(int value) {#setTextInheritanceLimit-int-}
```
public final void setTextInheritanceLimit(int value)
```


返回或设置文本属性的继承深度。可读写 [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit)。

**参数：**
| 参数 | 类型 | 说明 |
| --- | --- | --- |
| value | int |  |

### getLinkEmbedController() {#getLinkEmbedController--}
```
public final ILinkEmbedController getLinkEmbedController()
```


返回或设置一个回调对象，该对象控制外部对象的存储方式。可读写 [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller)。

**返回值：**
[ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller)
### setLinkEmbedController(ILinkEmbedController value) {#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-}
```
public final void setLinkEmbedController(ILinkEmbedController value)
```


返回或设置一个回调对象，该对象控制外部对象的存储方式。可读写 [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller)。

**参数：**
| 参数 | 类型 | 说明 |
| --- | --- | --- |
| value | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) |  |

### getEncodingName() {#getEncodingName--}
```
public final String getEncodingName()
```


返回或设置 html 编码名称。此值将保存到生成的 HTML 文件中，但由调用者确保文件以此编码保存。可读写 String。

**返回值：**
java.lang.String
### setEncodingName(String value) {#setEncodingName-java.lang.String-}
```
public final void setEncodingName(String value)
```


返回或设置 html 编码名称。此值将保存到生成的 HTML 文件中，但由调用者确保文件以此编码保存。可读写 String。

**参数：**
| 参数 | 类型 | 说明 |
| --- | --- | --- |
| value | java.lang.String |  |