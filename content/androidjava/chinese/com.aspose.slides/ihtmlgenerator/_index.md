---
title: IHtmlGenerator
second_title: Aspose.Slides for Android via Java API Reference
description: Html generator.
type: docs
url: /zh/com.aspose.slides/ihtmlgenerator/
---```
public interface IHtmlGenerator
```

Html 生成器。
## 方法

| 方法 | 描述 |
| --- | --- |
| [addHtml(String html)](#addHtml-java.lang.String-) | 添加格式化的 HTML 文本。 |
| [addHtml(char[] html)](#addHtml-char---) | 添加格式化的 HTML 文本。 |
| [addHtml(char[] html, int startIndex, int length)](#addHtml-char---int-int-) | 添加格式化的 HTML 文本。 |
| [addText(String text)](#addText-java.lang.String-) | 向 html 文件添加纯文本，将特殊字符替换为 html 实体。 |
| [addText(char[] text)](#addText-char---) | 向 html 文件添加纯文本，将特殊字符替换为 html 实体。 |
| [addText(char[] text, int startIndex, int length)](#addText-char---int-int-) | 向 html 文件添加纯文本，将特殊字符替换为 html 实体。 |
| [addAttributeValue(String value)](#addAttributeValue-java.lang.String-) | 对属性值加引号并将其添加到 html 文件。 |
| [addAttributeValue(char[] value)](#addAttributeValue-char---) | 对属性值加引号并将其添加到 html 文件。 |
| [addAttributeValue(char[] value, int startIndex, int length)](#addAttributeValue-char---int-int-) | 对属性值加引号并将其添加到 html 文件。 |
| [getSlideImageSize()](#getSlideImageSize--) | 返回幻灯片图像大小。 |
| [getSlideImageSizeUnit()](#getSlideImageSizeUnit--) | 返回指定幻灯片图像大小的单位。 |
| [getSlideImageSizeUnitCode()](#getSlideImageSizeUnitCode--) | 返回指定幻灯片图像大小的单位的 css 代码。 |
| [getPreviousSlideIndex()](#getPreviousSlideIndex--) | 返回之前渲染的幻灯片索引，如果是第一张幻灯片正在渲染则返回 -1。 |
| [getSlideIndex()](#getSlideIndex--) | 返回当前渲染的幻灯片索引。 |
| [getNextSlideIndex()](#getNextSlideIndex--) | 返回在当前幻灯片之后将要渲染的幻灯片索引，如果当前是最后一张幻灯片则返回 -1。 |
### addHtml(String html) {#addHtml-java.lang.String-}
```
public abstract void addHtml(String html)
```

添加格式化的 HTML 文本。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| html | java.lang.String | 要添加的文本。 |

### addHtml(char[] html) {#addHtml-char---}
```
public abstract void addHtml(char[] html)
```

添加格式化的 HTML 文本。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| html | char[] | 要添加的文本。 |

### addHtml(char[] html, int startIndex, int length) {#addHtml-char---int-int-}
```
public abstract void addHtml(char[] html, int startIndex, int length)
```

添加格式化的 HTML 文本。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| html | char[] | 要添加的文本。 |
| startIndex | int | 要添加部分的起始索引。 |
| length | int | 要添加部分的长度。 |

### addText(String text) {#addText-java.lang.String-}
```
public abstract void addText(String text)
```

向 html 文件添加纯文本，将特殊字符替换为 html 实体。换行符和空白字符不会被替换。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| text | java.lang.String | 要添加的文本。 |

### addText(char[] text) {#addText-char---}
```
public abstract void addText(char[] text)
```

向 html 文件添加纯文本，将特殊字符替换为 html 实体。换行符和空白字符不会被替换。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| text | char[] | 要添加的文本。 |

### addText(char[] text, int startIndex, int length) {#addText-char---int-int-}
```
public abstract void addText(char[] text, int startIndex, int length)
```

向 html 文件添加纯文本，将特殊字符替换为 html 实体。换行符和空白字符不会被替换。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| text | char[] | 要添加的文本。 |
| startIndex | int | 要添加部分的起始索引。 |
| length | int | 要添加部分的长度。 |

### addAttributeValue(String value) {#addAttributeValue-java.lang.String-}
```
public abstract void addAttributeValue(String value)
```

对属性值加引号并将其添加到 html 文件。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 属性值字符串。 |

### addAttributeValue(char[] value) {#addAttributeValue-char---}
```
public abstract void addAttributeValue(char[] value)
```

对属性值加引号并将其添加到 html 文件。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | char[] | 属性值字符串。 |

### addAttributeValue(char[] value, int startIndex, int length) {#addAttributeValue-char---int-int-}
```
public abstract void addAttributeValue(char[] value, int startIndex, int length)
```

对属性值加引号并将其添加到 html 文件。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | char[] | 属性值字符串。 |
| startIndex | int | 要添加部分的起始索引。 |
| length | int | 要添加部分的长度。 |

### getSlideImageSize() {#getSlideImageSize--}
```
public abstract SizeF getSlideImageSize()
```

返回幻灯片图像大小。只读 [SizeF](../../com.aspose.slides.android/sizef)。

**返回：**
[SizeF](../../com.aspose.slides.android/sizef)

### getSlideImageSizeUnit() {#getSlideImageSizeUnit--}
```
public abstract int getSlideImageSizeUnit()
```

返回指定幻灯片图像大小的单位。只读 [SvgCoordinateUnit](../../com.aspose.slides/svgcoordinateunit)。

**返回：**
int

### getSlideImageSizeUnitCode() {#getSlideImageSizeUnitCode--}
```
public abstract String getSlideImageSizeUnitCode()
```

返回指定幻灯片图像大小的单位的 css 代码。只读 String。

**返回：**
java.lang.String

### getPreviousSlideIndex() {#getPreviousSlideIndex--}
```
public abstract int getPreviousSlideIndex()
```

返回之前渲染的幻灯片索引，如果是第一张幻灯片正在渲染则返回 -1。只读 int。

**返回：**
int

### getSlideIndex() {#getSlideIndex--}
```
public abstract int getSlideIndex()
```

返回当前渲染的幻灯片索引。只读 int。

**返回：**
int

### getNextSlideIndex() {#getNextSlideIndex--}
```
public abstract int getNextSlideIndex()
```

返回在当前幻灯片之后将要渲染的幻灯片索引，如果当前是最后一张幻灯片则返回 -1。只读 int。

**返回：**
int