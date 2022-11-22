---
title: HtmlGenerator
second_title: Aspose.Slides for Java API Reference
description: Html generator.
type: docs
weight: 241
url: /java/com.aspose.slides/htmlgenerator/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator)
```
public final class HtmlGenerator implements IHtmlGenerator
```

Html generator.
## Methods

| Method | Description |
| --- | --- |
| [addHtml(String html)](#addHtml-java.lang.String-) | Adds formatted HTML text. |
| [addHtml(char[] html)](#addHtml-char---) | Adds formatted HTML text. |
| [addHtml(char[] html, int startIndex, int length)](#addHtml-char---int-int-) | Adds formatted HTML text. |
| [addText(String text)](#addText-java.lang.String-) | Adds plain text to the html files, replacing special characters with html entities. |
| [addText(char[] text)](#addText-char---) | Adds plain text to the html files, replacing special characters with html entities. |
| [addText(char[] text, int startIndex, int length)](#addText-char---int-int-) | Adds plain text to the html files, replacing special characters with html entities. |
| [addAttributeValue(String value)](#addAttributeValue-java.lang.String-) | Quotes attribute value and adds it to the html file. |
| [addAttributeValue(char[] value)](#addAttributeValue-char---) | Quotes attribute value and adds it to the html file. |
| [addAttributeValue(char[] value, int startIndex, int length)](#addAttributeValue-char---int-int-) | Quotes attribute value and adds it to the html file. |
| [getSlideImageSize()](#getSlideImageSize--) | Returns slide image size. |
| [getSlideImageSizeUnit()](#getSlideImageSizeUnit--) | Returns a unit in which slide image size is specified. |
| [getSlideImageSizeUnitCode()](#getSlideImageSizeUnitCode--) | Returns a css code of unit in which slide image size is specified. |
| [getPreviousSlideIndex()](#getPreviousSlideIndex--) | Returns index of previously rendered slide or -1 if first slide is rendering. |
| [getSlideIndex()](#getSlideIndex--) | Returns index of currently rendering slide. |
| [getNextSlideIndex()](#getNextSlideIndex--) | Returns index of a slide, which will be rendered after the current slide or -1 if currently rendering last slide. |
### addHtml(String html) {#addHtml-java.lang.String-}
```
public final void addHtml(String html)
```


Adds formatted HTML text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| html | java.lang.String | Text to add. |

### addHtml(char[] html) {#addHtml-char---}
```
public final void addHtml(char[] html)
```


Adds formatted HTML text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| html | char[] | Text to add. |

### addHtml(char[] html, int startIndex, int length) {#addHtml-char---int-int-}
```
public final void addHtml(char[] html, int startIndex, int length)
```


Adds formatted HTML text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| html | char[] | Text to add. |
| startIndex | int | Start index of the portion to add. |
| length | int | Length of the portion to add. |

### addText(String text) {#addText-java.lang.String-}
```
public final void addText(String text)
```


Adds plain text to the html files, replacing special characters with html entities. Linebreaks and whitespaces aren't replaced.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Text to add. |

### addText(char[] text) {#addText-char---}
```
public final void addText(char[] text)
```


Adds plain text to the html files, replacing special characters with html entities. Linebreaks and whitespaces aren't replaced.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | char[] | Text to add. |

### addText(char[] text, int startIndex, int length) {#addText-char---int-int-}
```
public final void addText(char[] text, int startIndex, int length)
```


Adds plain text to the html files, replacing special characters with html entities. Linebreaks and whitespaces aren't replaced.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | char[] | Text to add. |
| startIndex | int | Start index of the portion to add. |
| length | int | Length of the portion to add. |

### addAttributeValue(String value) {#addAttributeValue-java.lang.String-}
```
public final void addAttributeValue(String value)
```


Quotes attribute value and adds it to the html file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | Attribute value string. |

### addAttributeValue(char[] value) {#addAttributeValue-char---}
```
public final void addAttributeValue(char[] value)
```


Quotes attribute value and adds it to the html file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | char[] | Attribute value string. |

### addAttributeValue(char[] value, int startIndex, int length) {#addAttributeValue-char---int-int-}
```
public final void addAttributeValue(char[] value, int startIndex, int length)
```


Quotes attribute value and adds it to the html file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | char[] | Attribute value string. |
| startIndex | int | Start index of the portion to add. |
| length | int | Length of the portion to add. |

### getSlideImageSize() {#getSlideImageSize--}
```
public final Dimension2D getSlideImageSize()
```


Returns slide image size. Read-only java.awt.geom.Dimension2D.

**Returns:**
java.awt.geom.Dimension2D
### getSlideImageSizeUnit() {#getSlideImageSizeUnit--}
```
public final int getSlideImageSizeUnit()
```


Returns a unit in which slide image size is specified. Read-only [SvgCoordinateUnit](../../com.aspose.slides/svgcoordinateunit).

**Returns:**
int
### getSlideImageSizeUnitCode() {#getSlideImageSizeUnitCode--}
```
public final String getSlideImageSizeUnitCode()
```


Returns a css code of unit in which slide image size is specified. Read-only String.

**Returns:**
java.lang.String
### getPreviousSlideIndex() {#getPreviousSlideIndex--}
```
public final int getPreviousSlideIndex()
```


Returns index of previously rendered slide or -1 if first slide is rendering. Read-only int.

**Returns:**
int
### getSlideIndex() {#getSlideIndex--}
```
public final int getSlideIndex()
```


Returns index of currently rendering slide. Read-only int.

**Returns:**
int
### getNextSlideIndex() {#getNextSlideIndex--}
```
public final int getNextSlideIndex()
```


Returns index of a slide, which will be rendered after the current slide or -1 if currently rendering last slide. Read-only int.

**Returns:**
int
