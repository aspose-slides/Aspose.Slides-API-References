---
title: IHtmlGenerator
second_title: Aspose.Slides for Android via Java API 參考
description: HTML 產生器。
type: docs
url: /zh-hant/com.aspose.slides/ihtmlgenerator/
---```
public interface IHtmlGenerator
```

HTML 產生器。

## 方法

| 方法 | 說明 |
| --- | --- |
| [addHtml(String html)](#addHtml-java.lang.String-) | 新增格式化的 HTML 文字。 |
| [addHtml(char[] html)](#addHtml-char---) | 新增格式化的 HTML 文字。 |
| [addHtml(char[] html, int startIndex, int length)](#addHtml-char---int-int-) | 新增格式化的 HTML 文字。 |
| [addText(String text)](#addText-java.lang.String-) | 將純文字新增至 HTML 檔案，並將特殊字元替換為 HTML 實體。 |
| [addText(char[] text)](#addText-char---) | 將純文字新增至 HTML 檔案，並將特殊字元替換為 HTML 實體。 |
| [addText(char[] text, int startIndex, int length)](#addText-char---int-int-) | 將純文字新增至 HTML 檔案，並將特殊字元替換為 HTML 實體。 |
| [addAttributeValue(String value)](#addAttributeValue-java.lang.String-) | 將屬性值加上引號並新增至 HTML 檔案。 |
| [addAttributeValue(char[] value)](#addAttributeValue-char---) | 將屬性值加上引號並新增至 HTML 檔案。 |
| [addAttributeValue(char[] value, int startIndex, int length)](#addAttributeValue-char---int-int-) | 將屬性值加上引號並新增至 HTML 檔案。 |
| [getSlideImageSize()](#getSlideImageSize--) | 傳回投影片影像大小。 |
| [getSlideImageSizeUnit()](#getSlideImageSizeUnit--) | 傳回投影片影像大小所使用的單位。 |
| [getSlideImageSizeUnitCode()](#getSlideImageSizeUnitCode--) | 傳回投影片影像大小所使用單位的 CSS 代碼。 |
| [getPreviousSlideIndex()](#getPreviousSlideIndex--) | 傳回先前已渲染投影片的索引，若為第一張投影片則傳回 -1。 |
| [getSlideIndex()](#getSlideIndex--) | 傳回目前正在渲染的投影片索引。 |
| [getNextSlideIndex()](#getNextSlideIndex--) | 傳回在目前投影片之後將要渲染的投影片索引；若目前為最後一張投影片則傳回 -1。 |

### addHtml(String html) {#addHtml-java.lang.String-}
```
public abstract void addHtml(String html)
```

新增格式化的 HTML 文字。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| html | java.lang.String | 要新增的文字。 |

### addHtml(char[] html) {#addHtml-char---}
```
public abstract void addHtml(char[] html)
```

新增格式化的 HTML 文字。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| html | char[] | 要新增的文字。 |

### addHtml(char[] html, int startIndex, int length) {#addHtml-char---int-int-}
```
public abstract void addHtml(char[] html, int startIndex, int length)
```

新增格式化的 HTML 文字。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| html | char[] | 要新增的文字。 |
| startIndex | int | 要新增部分的起始索引。 |
| length | int | 要新增部分的長度。 |

### addText(String text) {#addText-java.lang.String-}
```
public abstract void addText(String text)
```

將純文字新增至 HTML 檔案，並將特殊字元替換為 HTML 實體。換行符與空白字元不會被替換。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| text | java.lang.String | 要新增的文字。 |

### addText(char[] text) {#addText-char---}
```
public abstract void addText(char[] text)
```

將純文字新增至 HTML 檔案，並將特殊字元替換為 HTML 實體。換行符與空白字元不會被替換。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| text | char[] | 要新增的文字。 |

### addText(char[] text, int startIndex, int length) {#addText-char---int-int-}
```
public abstract void addText(char[] text, int startIndex, int length)
```

將純文字新增至 HTML 檔案，並將特殊字元替換為 HTML 實體。換行符與空白字元不會被替換。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| text | char[] | 要新增的文字。 |
| startIndex | int | 要新增部分的起始索引。 |
| length | int | 要新增部分的長度。 |

### addAttributeValue(String value) {#addAttributeValue-java.lang.String-}
```
public abstract void addAttributeValue(String value)
```

將屬性值加上引號並新增至 HTML 檔案。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String | 屬性值字串。 |

### addAttributeValue(char[] value) {#addAttributeValue-char---}
```
public abstract void addAttributeValue(char[] value)
```

將屬性值加上引號並新增至 HTML 檔案。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | char[] | 屬性值字串。 |

### addAttributeValue(char[] value, int startIndex, int length) {#addAttributeValue-char---int-int-}
```
public abstract void addAttributeValue(char[] value, int startIndex, int length)
```

將屬性值加上引號並新增至 HTML 檔案。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | char[] | 屬性值字串。 |
| startIndex | int | 要新增部分的起始索引。 |
| length | int | 要新增部分的長度。 |

### getSlideImageSize() {#getSlideImageSize--}
```
public abstract SizeF getSlideImageSize()
```

傳回投影片影像大小。唯讀 [SizeF](../../com.aspose.slides.android/sizef)。

**傳回:**
[SizeF](../../com.aspose.slides.android/sizef)

### getSlideImageSizeUnit() {#getSlideImageSizeUnit--}
```
public abstract int getSlideImageSizeUnit()
```

傳回投影片影像大小所使用的單位。唯讀 [SvgCoordinateUnit](../../com.aspose.slides/svgcoordinateunit)。

**傳回:**
int

### getSlideImageSizeUnitCode() {#getSlideImageSizeUnitCode--}
```
public abstract String getSlideImageSizeUnitCode()
```

傳回投影片影像大小所使用單位的 CSS 代碼。唯讀 String。

**傳回:**
java.lang.String

### getPreviousSlideIndex() {#getPreviousSlideIndex--}
```
public abstract int getPreviousSlideIndex()
```

傳回先前已渲染投影片的索引，若為第一張投影片則傳回 -1。唯讀 int。

**傳回:**
int

### getSlideIndex() {#getSlideIndex--}
```
public abstract int getSlideIndex()
```

傳回目前正在渲染的投影片索引。唯讀 int。

**傳回:**
int

### getNextSlideIndex() {#getNextSlideIndex--}
```
public abstract int getNextSlideIndex()
```

傳回在目前投影片之後將要渲染的投影片索引；若目前為最後一張投影片則傳回 -1。唯讀 int。

**傳回:**
int