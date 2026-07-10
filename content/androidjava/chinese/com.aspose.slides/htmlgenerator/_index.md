---
title: HtmlGenerator
second_title: Aspose.Slides for Android via Java API 参考
description: HTML 生成器。
type: docs
url: /zh/com.aspose.slides/htmlgenerator/
---
**继承:**  
java.lang.Object

**所有实现的接口:**  
[com.aspose.slides.IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator)
```
public final class HtmlGenerator implements IHtmlGenerator
```

HTML 生成器。
## 方法

| 方法 | 描述 |
| --- | --- |
| [addHtml(String html)](#addHtml-java.lang.String-) | 添加格式化的 HTML 文本。 |
| [addHtml(char[] html)](#addHtml-char---) | 添加格式化的 HTML 文本。 |
| [addHtml(char[] html, int startIndex, int length)](#addHtml-char---int-int-) | 添加格式化的 HTML 文本。 |
| [addText(String text)](#addText-java.lang.String-) | 将纯文本添加到 html 文件中，并将特殊字符替换为 html 实体。 |
| [addText(char[] text)](#addText-char---) | 将纯文本添加到 html 文件中，并将特殊字符替换为 html 实体。 |
| [addText(char[] text, int startIndex, int length)](#addText-char---int-int-) | 将纯文本添加到 html 文件中，并将特殊字符替换为 html 实体。 |
| [addAttributeValue(String value)](#addAttributeValue-java.lang.String-) | 引用属性值并将其添加到 html 文件。 |
| [addAttributeValue(char[] value)](#addAttributeValue-char---) | 引用属性值并将其添加到 html 文件。 |
| [addAttributeValue(char[] value, int startIndex, int length)](#addAttributeValue-char---int-int-) | 引用属性值并将其添加到 html 文件。 |
| [getSlideImageSize()](#getSlideImageSize--) | 返回幻灯片图像大小。 |
| [getSlideImageSizeUnit()](#getSlideImageSizeUnit--) | 返回指定幻灯片图像大小的单位。 |
| [getSlideImageSizeUnitCode()](#getSlideImageSizeUnitCode--) | 返回指定幻灯片图像大小的单位的 css 代码。 |
| [getPreviousSlideIndex()](#getPreviousSlideIndex--) | 返回先前渲染的幻灯片索引，如果是第一张幻灯片则返回 -1。 |
| [getSlideIndex()](#getSlideIndex--) | 返回当前渲染的幻灯片索引。 |
| [getNextSlideIndex()](#getNextSlideIndex--) | 返回将在当前幻灯片之后渲染的幻灯片索引，如果当前是最后一张则返回 -1。 |
### addHtml(String html) {#addHtml-java.lang.String-}
```
public final void addHtml(String html)
```

添加格式化的 HTML 文本。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| html | java.lang.String | 要添加的文本。 |

### addHtml(char[] html) {#addHtml-char---}
```
public final void addHtml(char[] html)
```

添加格式化的 HTML 文本。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| html | char[] | 要添加的文本。 |

### addHtml(char[] html, int startIndex, int length) {#addHtml-char---int-int-}
```
public final void addHtml(char[] html, int startIndex, int length)
```

添加格式化的 HTML 文本。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| html | char[] | 要添加的文本。 |
| startIndex | int | 要添加部分的起始索引。 |
| length | int | 要添加部分的长度。 |

### addText(String text) {#addText-java.lang.String-}
```
public final void addText(String text)
```

将纯文本添加到 html 文件中，并将特殊字符替换为 html 实体。换行符和空白字符不会被替换。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| text | java.lang.String | 要添加的文本。 |

### addText(char[] text) {#addText-char---}
```
public final void addText(char[] text)
```

将纯文本添加到 html 文件中，并将特殊字符替换为 html 实体。换行符和空白字符不会被替换。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| text | char[] | 要添加的文本。 |

### addText(char[] text, int startIndex, int length) {#addText-char---int-int-}
```
public final void addText(char[] text, int startIndex, int length)
```

将纯文本添加到 html 文件中，并将特殊字符替换为 html 实体。换行符和空白字符不会被替换。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| text | char[] | 要添加的文本。 |
| startIndex | int | 要添加部分的起始索引。 |
| length | int | 要添加部分的长度。 |

### addAttributeValue(String value) {#addAttributeValue-java.lang.String-}
```
public final void addAttributeValue(String value)
```

引用属性值并将其添加到 html 文件。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 属性值字符串。 |

### addAttributeValue(char[] value) {#addAttributeValue-char---}
```
public final void addAttributeValue(char[] value)
```

引用属性值并将其添加到 html 文件。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | char[] | 属性值字符串。 |

### addAttributeValue(char[] value, int startIndex, int length) {#addAttributeValue-char---int-int-}
```
public final void addAttributeValue(char[] value, int startIndex, int length)
```

引用属性值并将其添加到 html 文件。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | char[] | 属性值字符串。 |
| startIndex | int | 要添加部分的起始索引。 |
| length | int | 要添加部分的长度。 |

### getSlideImageSize() {#getSlideImageSize--}
```
public final SizeF getSlideImageSize()
```

返回幻灯片图像大小。只读 [SizeF](../../com.aspose.slides.android/sizef)。

**返回值:**
[SizeF](../../com.aspose.slides.android/sizef)
### getSlideImageSizeUnit() {#getSlideImageSizeUnit--}
```
public final int getSlideImageSizeUnit()
```

返回指定幻灯片图像大小的单位。只读 [SvgCoordinateUnit](../../com.aspose.slides/svgcoordinateunit)。

**返回值:**
int
### getSlideImageSizeUnitCode() {#getSlideImageSizeUnitCode--}
```
public final String getSlideImageSizeUnitCode()
```

返回指定幻灯片图像大小的单位的 css 代码。只读 String。

**返回值:**
java.lang.String
### getPreviousSlideIndex() {#getPreviousSlideIndex--}
```
public final int getPreviousSlideIndex()
```

返回先前渲染的幻灯片索引，如果是第一张幻灯片则返回 -1。只读 int。

**返回值:**
int
### getSlideIndex() {#getSlideIndex--}
```
public final int getSlideIndex()
```

返回当前渲染的幻灯片索引。只读 int。

**返回值:**
int
### getNextSlideIndex() {#getNextSlideIndex--}
```
public final int getNextSlideIndex()
```

返回将在当前幻灯片之后渲染的幻灯片索引，如果当前是最后一张则返回 -1。只读 int。

**返回值:**
int