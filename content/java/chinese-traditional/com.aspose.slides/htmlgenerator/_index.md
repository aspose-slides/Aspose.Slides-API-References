---
title: HtmlGenerator
second_title: Aspose.Slides for Java API 參考文件
description: Html 產生器。
type: docs
url: /zh-hant/com.aspose.slides/htmlgenerator/
---
**繼承:**
java.lang.Object

**所有已實作的介面:**
[com.aspose.slides.IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator)
```
public final class HtmlGenerator implements IHtmlGenerator
```

Html 產生器。
## 方法

| 方法 | 說明 |
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

新增格式化的 HTML 文字。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| html | java.lang.String | 要新增的文字。 |

### addHtml(char[] html) {#addHtml-char---}
```
public final void addHtml(char[] html)
```

新增格式化的 HTML 文字。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| html | char[] | 要新增的文字。 |

### addHtml(char[] html, int startIndex, int length) {#addHtml-char---int-int-}
```
public final void addHtml(char[] html, int startIndex, int length)
```

新增格式化的 HTML 文字。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| html | char[] | 要新增的文字。 |
| startIndex | int | 要新增之部分的起始索引。 |
| length | int | 要新增之部分的長度。 |

### addText(String text) {#addText-java.lang.String-}
```
public final void addText(String text)
```

將純文字新增至 HTML 檔案，將特殊字元替換為 HTML 實體。換行與空白不會被取代。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| text | java.lang.String | 要新增的文字。 |

### addText(char[] text) {#addText-char---}
```
public final void addText(char[] text)
```

將純文字新增至 HTML 檔案，將特殊字元替換為 HTML 實體。換行與空白不會被取代。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| text | char[] | 要新增的文字。 |

### addText(char[] text, int startIndex, int length) {#addText-char---int-int-}
```
public final void addText(char[] text, int startIndex, int length)
```

將純文字新增至 HTML 檔案，將特殊字元替換為 HTML 實體。換行與空白不會被取代。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| text | char[] | 要新增的文字。 |
| startIndex | int | 要新增之部分的起始索引。 |
| length | int | 要新增之部分的長度。 |

### addAttributeValue(String value) {#addAttributeValue-java.lang.String-}
```
public final void addAttributeValue(String value)
```

將屬性值加上引號並新增至 HTML 檔案。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String | 屬性值字串。 |

### addAttributeValue(char[] value) {#addAttributeValue-char---}
```
public final void addAttributeValue(char[] value)
```

將屬性值加上引號並新增至 HTML 檔案。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | char[] | 屬性值字串。 |

### addAttributeValue(char[] value, int startIndex, int length) {#addAttributeValue-char---int-int-}
```
public final void addAttributeValue(char[] value, int startIndex, int length)
```

將屬性值加上引號並新增至 HTML 檔案。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | char[] | 屬性值字串。 |
| startIndex | int | 要新增之部分的起始索引。 |
| length | int | 要新增之部分的長度。 |

### getSlideImageSize() {#getSlideImageSize--}
```
public final Dimension2D getSlideImageSize()
```

傳回投影片影像大小。唯讀 java.awt.geom.Dimension2D。

**傳回值:**
java.awt.geom.Dimension2D
### getSlideImageSizeUnit() {#getSlideImageSizeUnit--}
```
public final int getSlideImageSizeUnit()
```

傳回指定投影片影像大小的單位。唯讀 [SvgCoordinateUnit](../../com.aspose.slides/svgcoordinateunit)。

**傳回值:**
int
### getSlideImageSizeUnitCode() {#getSlideImageSizeUnitCode--}
```
public final String getSlideImageSizeUnitCode()
```

傳回指定投影片影像大小的單位之 CSS 代碼。唯讀 String。

**傳回值:**
java.lang.String
### getPreviousSlideIndex() {#getPreviousSlideIndex--}
```
public final int getPreviousSlideIndex()
```

傳回先前已呈現投影片的索引，若為第一張投影片則傳回 -1。唯讀 int。

**傳回值:**
int
### getSlideIndex() {#getSlideIndex--}
```
public final int getSlideIndex()
```

傳回目前正在呈現的投影片索引。唯讀 int。

**傳回值:**
int
### getNextSlideIndex() {#getNextSlideIndex--}
```
public final int getNextSlideIndex()
```

傳回在目前投影片之後將被呈現的投影片索引，若目前為最後一張投影片則傳回 -1。唯讀 int。

**傳回值:**
int