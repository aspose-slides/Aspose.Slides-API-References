---
title: ITextToHtmlConversionOptions
second_title: Aspose.Slides for Android via Java API 参考
description: 从 Pptx 文本提取 HTML 的选项。
type: docs
url: /zh/com.aspose.slides/itexttohtmlconversionoptions/
---```
public interface ITextToHtmlConversionOptions
```

从 Pptx 文本提取 HTML 的选项。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getAddClipboardFragmentHeader()](#getAddClipboardFragmentHeader--) | 返回或设置值，指示是否应添加剪贴板标题。 |
| [setAddClipboardFragmentHeader(boolean value)](#setAddClipboardFragmentHeader-boolean-) | 返回或设置值，指示是否应添加剪贴板标题。 |
| [getTextInheritanceLimit()](#getTextInheritanceLimit--) | 返回或设置文本属性的继承深度。 |
| [setTextInheritanceLimit(int value)](#setTextInheritanceLimit-int-) | 返回或设置文本属性的继承深度。 |
| [getLinkEmbedController()](#getLinkEmbedController--) | 返回或设置一个回调对象，用于控制外部对象的存储方式。 |
| [setLinkEmbedController(ILinkEmbedController value)](#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-) | 返回或设置一个回调对象，用于控制外部对象的存储方式。 |
| [getEncodingName()](#getEncodingName--) | 返回或设置 HTML 编码名称。 |
| [setEncodingName(String value)](#setEncodingName-java.lang.String-) | 返回或设置 HTML 编码名称。 |
### getAddClipboardFragmentHeader() {#getAddClipboardFragmentHeader--}
```
public abstract boolean getAddClipboardFragmentHeader()
```

返回或设置值，指示是否应添加剪贴板标题。 读写布尔。

**返回:**
boolean
### setAddClipboardFragmentHeader(boolean value) {#setAddClipboardFragmentHeader-boolean-}
```
public abstract void setAddClipboardFragmentHeader(boolean value)
```

返回或设置值，指示是否应添加剪贴板标题。 读写布尔。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getTextInheritanceLimit() {#getTextInheritanceLimit--}
```
public abstract int getTextInheritanceLimit()
```

返回或设置文本属性的继承深度。 读写 [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit)(\#getTextInheritanceLimit.getTextInheritanceLimit/\#setTextInheritanceLimit(int).setTextInheritanceLimit(int))。

**返回:**
int
### setTextInheritanceLimit(int value) {#setTextInheritanceLimit-int-}
```
public abstract void setTextInheritanceLimit(int value)
```

返回或设置文本属性的继承深度。 读写 [TextInheritanceLimit](../../com.aspose.slides/textinheritancelimit)(\#getTextInheritanceLimit.getTextInheritanceLimit/\#setTextInheritanceLimit(int).setTextInheritanceLimit(int))。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getLinkEmbedController() {#getLinkEmbedController--}
```
public abstract ILinkEmbedController getLinkEmbedController()
```

返回或设置一个回调对象，用于控制外部对象的存储方式。 读写 [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller)。

**返回:**
[ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller)
### setLinkEmbedController(ILinkEmbedController value) {#setLinkEmbedController-com.aspose.slides.ILinkEmbedController-}
```
public abstract void setLinkEmbedController(ILinkEmbedController value)
```

返回或设置一个回调对象，用于控制外部对象的存储方式。 读写 [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) |  |

### getEncodingName() {#getEncodingName--}
```
public abstract String getEncodingName()
```

返回或设置 HTML 编码名称。 此值将保存到生成的 HTML 文件中，但由调用者确保文件以此编码保存。 读写 String。

**返回:**
java.lang.String
### setEncodingName(String value) {#setEncodingName-java.lang.String-}
```
public abstract void setEncodingName(String value)
```

返回或设置 HTML 编码名称。 此值将保存到生成的 HTML 文件中，但由调用者确保文件以此编码保存。 读写 String。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |