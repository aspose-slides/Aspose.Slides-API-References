---
title: IHtmlGenerator
second_title: Aspose.Slides for Android via Java API Reference
description: Html generator.
type: docs
url: /com.aspose.slides/ihtmlgenerator/
---```
public interface IHtmlGenerator
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
public abstract void addHtml(String html)
```


Adds formatted HTML text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| html | java.lang.String | Text to add. |

### addHtml(char[] html) {#addHtml-char---}
```
public abstract void addHtml(char[] html)
```


Adds formatted HTML text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| html | char[] | Text to add. |

### addHtml(char[] html, int startIndex, int length) {#addHtml-char---int-int-}
```
public abstract void addHtml(char[] html, int startIndex, int length)
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
public abstract void addText(String text)
```


Adds plain text to the html files, replacing special characters with html entities. Linebreaks and whitespaces aren't replaced.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Text to add. |

### addText(char[] text) {#addText-char---}
```
public abstract void addText(char[] text)
```


Adds plain text to the html files, replacing special characters with html entities. Linebreaks and whitespaces aren't replaced.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | char[] | Text to add. |

### addText(char[] text, int startIndex, int length) {#addText-char---int-int-}
```
public abstract void addText(char[] text, int startIndex, int length)
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
public abstract void addAttributeValue(String value)
```


Quotes attribute value and adds it to the html file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | Attribute value string. |

### addAttributeValue(char[] value) {#addAttributeValue-char---}
```
public abstract void addAttributeValue(char[] value)
```


Quotes attribute value and adds it to the html file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | char[] | Attribute value string. |

### addAttributeValue(char[] value, int startIndex, int length) {#addAttributeValue-char---int-int-}
```
public abstract void addAttributeValue(char[] value, int startIndex, int length)
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
public abstract SizeF getSlideImageSize()
```


Returns slide image size. Read-only [SizeF](../../com.aspose.slides.android/sizef).

**Returns:**
[SizeF](../../com.aspose.slides.android/sizef)
### getSlideImageSizeUnit() {#getSlideImageSizeUnit--}
```
public abstract int getSlideImageSizeUnit()
```


Returns a unit in which slide image size is specified. Read-only [SvgCoordinateUnit](../../com.aspose.slides/svgcoordinateunit).

**Returns:**
int
### getSlideImageSizeUnitCode() {#getSlideImageSizeUnitCode--}
```
public abstract String getSlideImageSizeUnitCode()
```


Returns a css code of unit in which slide image size is specified. Read-only String.

**Returns:**
java.lang.String
### getPreviousSlideIndex() {#getPreviousSlideIndex--}
```
public abstract int getPreviousSlideIndex()
```


Returns index of previously rendered slide or -1 if first slide is rendering. Read-only int.

**Returns:**
int
### getSlideIndex() {#getSlideIndex--}
```
public abstract int getSlideIndex()
```


Returns index of currently rendering slide. Read-only int.

**Returns:**
int
### getNextSlideIndex() {#getNextSlideIndex--}
```
public abstract int getNextSlideIndex()
```


Returns index of a slide, which will be rendered after the current slide or -1 if currently rendering last slide. Read-only int.

**Returns:**
int
