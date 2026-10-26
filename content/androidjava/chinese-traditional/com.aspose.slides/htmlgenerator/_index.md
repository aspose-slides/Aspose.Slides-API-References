---
title: HtmlGenerator
second_title: Aspose.Slides 於 Android 的 Java API 參考
description: HTML 產生器。
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

Html generator.
## 方法

| 方法 | 說明 |
| --- | --- |
| [addHtml(String html)](#addHtml-java.lang.String-) | 新增格式化的 HTML 文字。 |
| [addHtml(char[] html)](#addHtml-char---) | 新增格式化的 HTML 文字。 |
| [addHtml(char[] html, int startIndex, int length)](#addHtml-char---int-int-) | 新增格式化的 HTML 文字。 |
| [addText(String text)](#addText-java.lang.String-) | 將純文字新增至 HTML 檔案，並以 HTML 實體取代特殊字元。 |
| [addText(char[] text)](#addText-char---) | 將純文字新增至 HTML 檔案，並以 HTML 實體取代特殊字元。 |
| [addText(char[] text, int startIndex, int length)](#addText-char---int-int-) | 將純文字新增至 HTML 檔案，並以 HTML 實體取代特殊字元。 |
| [addAttributeValue(String value)](#addAttributeValue-java.lang.String-) | 為屬性值加上引號並將其新增至 HTML 檔案。 |
| [addAttributeValue(char[] value)](#addAttributeValue-char---) | 為屬性值加上引號並將其新增至 HTML 檔案。 |
| [addAttributeValue(char[] value, int startIndex, int length)](#addAttributeValue-char---int-int-) | 為屬性值加上引號並將其新增至 HTML 檔案。 |
| [getSlideImageSize()](#getSlideImageSize--) | 傳回投影片影像大小。 |
| [getSlideImageSizeUnit()](#getSlideImageSizeUnit--) | 傳回指定投影片影像大小的單位。 |
| [getSlideImageSizeUnitCode()](#getSlideImageSizeUnitCode--) | 傳回指定投影片影像大小的單位之 CSS 代碼。 |
| [getPreviousSlideIndex()](#getPreviousSlideIndex--) | 傳回先前已渲染投影片的索引；若為第一張投影片正在渲染，則傳回 -1。 |
| [getSlideIndex()](#getSlideIndex--) | 傳回目前正在渲染的投影片索引。 |
| [getNextSlideIndex()](#getNextSlideIndex--) | 傳回接在目前投影片之後將被渲染的投影片索引；若目前為最後一張投影片，則傳回 -1。 |
### addHtml(String html) {#addHtml-java.lang.String-}
```
public final void addHtml(String html)
```


新增格式化的 HTML 文字。

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| html | java.lang.String | 要新增的文字。 |

### addHtml(char[] html) {#addHtml-char---}
```
public final void addHtml(char[] html)
```


新增格式化的 HTML 文字。

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| html | char[] | 要新增的文字。 |

### addHtml(char[] html, int startIndex, int length) {#addHtml-char---int-int-}
```
public final void addHtml(char[] html, int startIndex, int length)
```


新增格式化的 HTML 文字。

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| html | char[] | 要新增的文字。 |
| startIndex | int | 要新增部份的起始索引。 |
| length | int | 要新增部份的長度。 |

### addText(String text) {#addText-java.lang.String-}
```
public final void addText(String text)
```


將純文字新增至 HTML 檔案，並以 HTML 實體取代特殊字元。換行符與空白字元不會被取代。

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| text | java.lang.String | 要新增的文字。 |

### addText(char[] text) {#addText-char---}
```
public final void addText(char[] text)
```


將純文字新增至 HTML 檔案，並以 HTML 實體取代特殊字元。換行符與空白字元不會被取代。

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| text | char[] | 要新增的文字。 |

### addText(char[] text, int startIndex, int length) {#addText-char---int-int-}
```
public final void addText(char[] text, int startIndex, int length)
```


將純文字新增至 HTML 檔案，並以 HTML 實體取代特殊字元。換行符與空白字元不會被取代。

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| text | char[] | 要新增的文字。 |
| startIndex | int | 要新增部份的起始索引。 |
| length | int | 要新增部份的長度。 |

### addAttributeValue(String value) {#addAttributeValue-java.lang.String-}
```
public final void addAttributeValue(String value)
```


為屬性值加上引號並將其新增至 HTML 檔案。

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | java.lang.String | 屬性值字串。 |

### addAttributeValue(char[] value) {#addAttributeValue-char---}
```
public final void addAttributeValue(char[] value)
```


為屬性值加上引號並將其新增至 HTML 檔案。

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | char[] | 屬性值字串。 |

### addAttributeValue(char[] value, int startIndex, int length) {#addAttributeValue-char---int-int-}
```
public final void addAttributeValue(char[] value, int startIndex, int length)
```


為屬性值加上引號並將其新增至 HTML 檔案。

**參數:**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | char[] | 屬性值字串。 |
| startIndex | int | 要新增部份的起始索引。 |
| length | int | 要新增部份的長度。 |

### getSlideImageSize() {#getSlideImageSize--}
```
public final SizeF getSlideImageSize()
```


傳回投影片影像大小。唯讀 [SizeF](../../com.aspose.slides.android/sizef)。

**傳回值:**
[SizeF](../../com.aspose.slides.android/sizef)
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


傳回先前已渲染投影片的索引；若為第一張投影片正在渲染，則傳回 -1。唯讀 int。

**傳回值:**
int
### getSlideIndex() {#getSlideIndex--}
```
public final int getSlideIndex()
```


傳回目前正在渲染的投影片索引。唯讀 int。

**傳回值:**
int
### getNextSlideIndex() {#getNextSlideIndex--}
```
public final int getNextSlideIndex()
```


傳回接在目前投影片之後將被渲染的投影片索引；若目前為最後一張投影片，則傳回 -1。唯讀 int。

**傳回值:**
int