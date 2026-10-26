---
title: TextToHtmlConversionOptions
second_title: Aspose.Slides Android 通过 Java API 参考
description: 从 PPTX 文本中提取 HTML 的选项。
type: docs
url: /zh/com.aspose.slides/texttohtmlconversionoptions/
---
**继承:**  
java.lang.Object

**已实现的所有接口:**  
[com.aspose.slides.ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions)
```
public final class TextToHtmlConversionOptions implements ITextToHtmlConversionOptions
```

提取 PPTX 文本的 HTML 选项。  
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [TextToHtmlConversionOptions()](#TextToHtmlConversionOptions--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getAddClipboardFragmentHeader()](#getAddClipboardFragmentHeader--) | 返回或设置值，指示是否应添加剪贴板标头。 |
| [setAddClipboardFragmentHeader(boolean value)](#setAddClipboardFragmentHeader-boolean-) | 返回或设置值，指示是否应添加剪贴板标头。 |
| [getTextInheritanceLimit()](#getTextInheritanceLimit--) | 返回或设置文本属性的继承深度。 |
| [setTextInheritanceLimit(int value)](#setTextInheritanceLimit-int-) | 返回或设置文本属性的继承深度。 |
| [getLinkEmbedController()](#getLinkEmbedController--) | 返回或设置一个回调对象，用于控制外部对象的存储方式。 |
| [setLinkEmbedController(ILinkEmbedController value)](#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-) | 返回或设置一个回调对象，用于控制外部对象的存储方式。 |
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

返回或设置值，指示是否应添加剪贴板标头。可读/可写 boolean。

**返回:**  
boolean
### setAddClipboardFragmentHeader(boolean value) {#setAddClipboardFragmentHeader-boolean-}
```
public final void setAddClipboardFragmentHeader(boolean value)
```

返回或设置值，指示是否应添加剪贴板标头。可读/可写 boolean。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |
### getTextInheritanceLimit() {#getTextInheritanceLimit--}
```
public final int getTextInheritanceLimit()
```

返回或设置文本属性的继承深度。可读/可写 [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit)。

**返回:**  
int
### setTextInheritanceLimit(int value) {#setTextInheritanceLimit-int-}
```
public final void setTextInheritanceLimit(int value)
```

返回或设置文本属性的继承深度。可读/可写 [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit)。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |
### getLinkEmbedController() {#getLinkEmbedController--}
```
public final ILinkEmbedController getLinkEmbedController()
```

返回或设置一个回调对象，用于控制外部对象的存储方式。可读/可写 [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller)。

**返回:**  
[ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller)
### setLinkEmbedController(ILinkEmbedController value) {#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-}
```
public final void setLinkEmbedController(ILinkEmbedController value)
```

返回或设置一个回调对象，用于控制外部对象的存储方式。可读/可写 [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller)。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) |  |
### getEncodingName() {#getEncodingName--}
```
public final String getEncodingName()
```

返回或设置 html 编码名称。此值将保存到生成的 HTML 文件中，但由调用者确保文件以此编码保存。可读/可写 String。

**返回:**  
java.lang.String
### setEncodingName(String value) {#setEncodingName-java.lang.String-}
```
public final void setEncodingName(String value)
```

返回或设置 html 编码名称。此值将保存到生成的 HTML 文件中，但由调用者确保文件以此编码保存。可读/可写 String。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |