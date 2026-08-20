---
title: HtmlGenerator
second_title: مرجع Aspose.Slides لواجهة برمجة تطبيقات جافا
description: مولد HTML.
type: docs
url: /ar/com.aspose.slides/htmlgenerator/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator)
```
public final class HtmlGenerator implements IHtmlGenerator
```

مولد HTML.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [addHtml(String html)](#addHtml-java.lang.String-) | يضيف نص HTML منسق. |
| [addHtml(char[] html)](#addHtml-char---) | يضيف نص HTML منسق. |
| [addHtml(char[] html, int startIndex, int length)](#addHtml-char---int-int-) | يضيف نص HTML منسق. |
| [addText(String text)](#addText-java.lang.String-) | يضيف نصًا عاديًا إلى ملفات HTML، مستبدلًا الأحرف الخاصة بكيانات HTML. |
| [addText(char[] text)](#addText-char---) | يضيف نصًا عاديًا إلى ملفات HTML، مستبدلًا الأحرف الخاصة بكيانات HTML. |
| [addText(char[] text, int startIndex, int length)](#addText-char---int-int-) | يضيف نصًا عاديًا إلى ملفات HTML، مستبدلًا الأحرف الخاصة بكيانات HTML. |
| [addAttributeValue(String value)](#addAttributeValue-java.lang.String-) | يقتبس قيمة السمة ويضيفها إلى ملف HTML. |
| [addAttributeValue(char[] value)](#addAttributeValue-char---) | يقتبس قيمة السمة ويضيفها إلى ملف HTML. |
| [addAttributeValue(char[] value, int startIndex, int length)](#addAttributeValue-char---int-int-) | يقتبس قيمة السمة ويضيفها إلى ملف HTML. |
| [getSlideImageSize()](#getSlideImageSize--) | يرجع حجم صورة الشريحة. |
| [getSlideImageSizeUnit()](#getSlideImageSizeUnit--) | يرجع الوحدة التي يُحدَّد بها حجم صورة الشريحة. |
| [getSlideImageSizeUnitCode()](#getSlideImageSizeUnitCode--) | يرجع رمز CSS للوحدة التي يُحدَّد بها حجم صورة الشريحة. |
| [getPreviousSlideIndex()](#getPreviousSlideIndex--) | يرجع فهرس الشريحة التي تم عرضها مسبقًا أو -1 إذا كانت الشريحة الأولى قيد العرض. |
| [getSlideIndex()](#getSlideIndex--) | يرجع فهرس الشريحة الحالية المعروضة. |
| [getNextSlideIndex()](#getNextSlideIndex--) | يرجع فهرس الشريحة التي سيتم عرضها بعد الشريحة الحالية أو -1 إذا كانت الشريحة الحالية هي الأخيرة. |
### addHtml(String html) {#addHtml-java.lang.String-}
```
public final void addHtml(String html)
```


يضيف نص HTML منسق.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| html | java.lang.String | النص المراد إضافته. |

### addHtml(char[] html) {#addHtml-char---}
```
public final void addHtml(char[] html)
```


يضيف نص HTML منسق.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| html | char[] | النص المراد إضافته. |

### addHtml(char[] html, int startIndex, int length) {#addHtml-char---int-int-}
```
public final void addHtml(char[] html, int startIndex, int length)
```


يضيف نص HTML منسق.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| html | char[] | النص المراد إضافته. |
| startIndex | int | فهرس البداية للجزء المراد إضافته. |
| length | int | طول الجزء المراد إضافته. |

### addText(String text) {#addText-java.lang.String-}
```
public final void addText(String text)
```


يضيف نصًا عاديًا إلى ملفات HTML، مستبدلًا الأحرف الخاصة بكيانات HTML. لا يتم استبدال فواصل الأسطر والمسافات البيضاء.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| text | java.lang.String | النص المراد إضافته. |

### addText(char[] text) {#addText-char---}
```
public final void addText(char[] text)
```


يضيف نصًا عاديًا إلى ملفات HTML، مستبدلًا الأحرف الخاصة بكيانات HTML. لا يتم استبدال فواصل الأسطر والمسافات البيضاء.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| text | char[] | النص المراد إضافته. |

### addText(char[] text, int startIndex, int length) {#addText-char---int-int-}
```
public final void addText(char[] text, int startIndex, int length)
```


يضيف نصًا عاديًا إلى ملفات HTML، مستبدلًا الأحرف الخاصة بكيانات HTML. لا يتم استبدال فواصل الأسطر والمسافات البيضاء.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| text | char[] | النص المراد إضافته. |
| startIndex | int | فهرس البداية للجزء المراد إضافته. |
| length | int | طول الجزء المراد إضافته. |

### addAttributeValue(String value) {#addAttributeValue-java.lang.String-}
```
public final void addAttributeValue(String value)
```


يقتبس قيمة السمة ويضيفها إلى ملف HTML.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String | قيمة السمة كنص. |

### addAttributeValue(char[] value) {#addAttributeValue-char---}
```
public final void addAttributeValue(char[] value)
```


يقتبس قيمة السمة ويضيفها إلى ملف HTML.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | char[] | قيمة السمة كنص. |

### addAttributeValue(char[] value, int startIndex, int length) {#addAttributeValue-char---int-int-}
```
public final void addAttributeValue(char[] value, int startIndex, int length)
```


يقتبس قيمة السمة ويضيفها إلى ملف HTML.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | char[] | قيمة السمة كنص. |
| startIndex | int | فهرس البداية للجزء المراد إضافته. |
| length | int | طول الجزء المراد إضافته. |

### getSlideImageSize() {#getSlideImageSize--}
```
public final Dimension2D getSlideImageSize()
```


يرجع حجم صورة الشريحة. قراءة فقط java.awt.geom.Dimension2D.

**الإرجاع:**
java.awt.geom.Dimension2D
### getSlideImageSizeUnit() {#getSlideImageSizeUnit--}
```
public final int getSlideImageSizeUnit()
```


يرجع الوحدة التي يُحدَّد بها حجم صورة الشريحة. قراءة فقط [SvgCoordinateUnit](../../com.aspose.slides/svgcoordinateunit).

**الإرجاع:**
int
### getSlideImageSizeUnitCode() {#getSlideImageSizeUnitCode--}
```
public final String getSlideImageSizeUnitCode()
```


يرجع رمز CSS للوحدة التي يُحدَّد بها حجم صورة الشريحة. قراءة فقط String.

**الإرجاع:**
java.lang.String
### getPreviousSlideIndex() {#getPreviousSlideIndex--}
```
public final int getPreviousSlideIndex()
```


يرجع فهرس الشريحة التي تم عرضها مسبقًا أو -1 إذا كانت الشريحة الأولى قيد العرض. قراءة فقط int.

**الإرجاع:**
int
### getSlideIndex() {#getSlideIndex--}
```
public final int getSlideIndex()
```


يرجع فهرس الشريحة الحالية المعروضة. قراءة فقط int.

**الإرجاع:**
int
### getNextSlideIndex() {#getNextSlideIndex--}
```
public final int getNextSlideIndex()
```


يرجع فهرس الشريحة التي سيتم عرضها بعد الشريحة الحالية أو -1 إذا كانت الشريحة الحالية هي الأخيرة. قراءة فقط int.

**الإرجاع:**
int