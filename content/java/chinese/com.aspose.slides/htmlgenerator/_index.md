---
title: HtmlGenerator
second_title: Aspose.Slides for Java API 参考
description: Html 生成器。
type: docs
url: /zh/com.aspose.slides/htmlgenerator/
---
**继承:**  
java.lang.Object

**已实现的接口:**  
[com.aspose.slides.IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator)  
```
public final class HtmlGenerator implements IHtmlGenerator
```

Html 生成器。

## 方法

| 方法 | 描述 |
| --- | --- |
| [addHtml(String html)](#addHtml-java.lang.String-) | 添加格式化的HTML文本。 |
| [addHtml(char[] html)](#addHtml-char---) | 添加格式化的HTML文本。 |
| [addHtml(char[] html, int startIndex, int length)](#addHtml-char---int-int-) | 添加格式化的HTML文本。 |
| [addText(String text)](#addText-java.lang.String-) | 向html文件添加纯文本，并将特殊字符替换为html实体。 |
| [addText(char[] text)](#addText-char---) | 向html文件添加纯文本，并将特殊字符替换为html实体。 |
| [addText(char[] text, int startIndex, int length)](#addText-char---int-int-) | 向html文件添加纯文本，并将特殊字符替换为html实体。 |
| [addAttributeValue(String value)](#addAttributeValue-java.lang.String-) | 对属性值加引号并将其添加到html文件中。 |
| [addAttributeValue(char[] value)](#addAttributeValue-char---) | 对属性值加引号并将其添加到html文件中。 |
| [addAttributeValue(char[] value, int startIndex, int length)](#addAttributeValue-char---int-int-) | 对属性值加引号并将其添加到html文件中。 |
| [getSlideImageSize()](#getSlideImageSize--) | 返回幻灯片图像尺寸。 |
| [getSlideImageSizeUnit()](#getSlideImageSizeUnit--) | 返回指定幻灯片图像尺寸的单位。 |
| [getSlideImageSizeUnitCode()](#getSlideImageSizeUnitCode--) | 返回指定幻灯片图像尺寸的单位的CSS代码。 |
| [getPreviousSlideIndex()](#getPreviousSlideIndex--) | 返回先前渲染的幻灯片的索引，如果是第一张幻灯片正在渲染则返回-1。 |
| [getSlideIndex()](#getSlideIndex--) | 返回当前渲染的幻灯片的索引。 |
| [getNextSlideIndex()](#getNextSlideIndex--) | 返回在当前幻灯片之后将要渲染的幻灯片的索引，如果当前渲染的是最后一张幻灯片则返回-1。 |

### addHtml(String html) {#addHtml-java.lang.String-}
```
public final void addHtml(String html)
```

添加格式化的HTML文本。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| html | java.lang.String | 要添加的文本。 |

### addHtml(char[] html) {#addHtml-char---}
```
public final void addHtml(char[] html)
```

添加格式化的HTML文本。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| html | char[] | 要添加的文本。 |

### addHtml(char[] html, int startIndex, int length) {#addHtml-char---int-int-}
```
public final void addHtml(char[] html, int startIndex, int length)
```

添加格式化的HTML文本。

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

向html文件添加纯文本，并将特殊字符替换为html实体。换行符和空白字符不会被替换。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| text | java.lang.String | 要添加的文本。 |

### addText(char[] text) {#addText-char---}
```
public final void addText(char[] text)
```

向html文件添加纯文本，并将特殊字符替换为html实体。换行符和空白字符不会被替换。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| text | char[] | 要添加的文本。 |

### addText(char[] text, int startIndex, int length) {#addText-char---int-int-}
```
public final void addText(char[] text, int startIndex, int length)
```

向html文件添加纯文本，并将特殊字符替换为html实体。换行符和空白字符不会被替换。

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

对属性值加引号并将其添加到html文件中。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 属性值字符串。 |

### addAttributeValue(char[] value) {#addAttributeValue-char---}
```
public final void addAttributeValue(char[] value)
```

对属性值加引号并将其添加到html文件中。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | char[] | 属性值字符串。 |

### addAttributeValue(char[] value, int startIndex, int length) {#addAttributeValue-char---int-int-}
```
public final void addAttributeValue(char[] value, int startIndex, int length)
```

对属性值加引号并将其添加到html文件中。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | char[] | 属性值字符串。 |
| startIndex | int | 要添加部分的起始索引。 |
| length | int | 要添加部分的长度。 |

### getSlideImageSize() {#getSlideImageSize--}
```
public final Dimension2D getSlideImageSize()
```

返回幻灯片图像尺寸。只读 java.awt.geom.Dimension2D。

**返回值:**
java.awt.geom.Dimension2D

### getSlideImageSizeUnit() {#getSlideImageSizeUnit--}
```
public final int getSlideImageSizeUnit()
```

返回指定幻灯片图像尺寸的单位。只读 [SvgCoordinateUnit](../../com.aspose.slides/svgcoordinateunit)。

**返回值:**
int

### getSlideImageSizeUnitCode() {#getSlideImageSizeUnitCode--}
```
public final String getSlideImageSizeUnitCode()
```

返回指定幻灯片图像尺寸的单位的CSS代码。只读 String。

**返回值:**
java.lang.String

### getPreviousSlideIndex() {#getPreviousSlideIndex--}
```
public final int getPreviousSlideIndex()
```

返回先前渲染的幻灯片的索引，如果是第一张幻灯片正在渲染则返回-1。只读 int。

**返回值:**
int

### getSlideIndex() {#getSlideIndex--}
```
public final int getSlideIndex()
```

返回当前渲染的幻灯片的索引。只读 int。

**返回值:**
int

### getNextSlideIndex() {#getNextSlideIndex--}
```
public final int getNextSlideIndex()
```

返回在当前幻灯片之后将要渲染的幻灯片的索引，如果当前渲染的是最后一张幻灯片则返回-1。只读 int。

**返回值:**
int