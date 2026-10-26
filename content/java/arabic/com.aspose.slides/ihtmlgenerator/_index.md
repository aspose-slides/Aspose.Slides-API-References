---
title: IHtmlGenerator
second_title: Aspose.Slides for Java API Reference
description: مولد HTML.
type: docs
url: /ar/com.aspose.slides/ihtmlgenerator/
---```
public interface IHtmlGenerator
```

مولد HTML.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [addHtml(String html)](#addHtml-java.lang.String-) | يضيف نص HTML منسق. |
| [addHtml(char[] html)](#addHtml-char---) | يضيف نص HTML منسق. |
| [addHtml(char[] html, int startIndex, int length)](#addHtml-char---int-int-) | يضيف نص HTML منسق. |
| [addText(String text)](#addText-java.lang.String-) | يضيف نصًا عاديًا إلى ملفات HTML، مع استبدال الأحرف الخاصة بكيانات HTML. لا يتم استبدال فواصل الأسطر والمسافات البيضاء. |
| [addText(char[] text)](#addText-char---) | يضيف نصًا عاديًا إلى ملفات HTML، مع استبدال الأحرف الخاصة بكيانات HTML. لا يتم استبدال فواصل الأسطر والمسافات البيضاء. |
| [addText(char[] text, int startIndex, int length)](#addText-char---int-int-) | يضيف نصًا عاديًا إلى ملفات HTML، مع استبدال الأحرف الخاصة بكيانات HTML. لا يتم استبدال فواصل الأسطر والمسافات البيضاء. |
| [addAttributeValue(String value)](#addAttributeValue-java.lang.String-) | يقوم بقتباس قيمة السمة ويضيفها إلى ملف HTML. |
| [addAttributeValue(char[] value)](#addAttributeValue-char---) | يقوم بقتباس قيمة السمة ويضيفها إلى ملف HTML. |
| [addAttributeValue(char[] value, int startIndex, int length)](#addAttributeValue-char---int-int-) | يقوم بقتباس قيمة السمة ويضيفها إلى ملف HTML. |
| [getSlideImageSize()](#getSlideImageSize--) | يعيد حجم صورة الشريحة. |
| [getSlideImageSizeUnit()](#getSlideImageSizeUnit--) | يعيد الوحدة التي يُحدَّد بها حجم صورة الشريحة. |
| [getSlideImageSizeUnitCode()](#getSlideImageSizeUnitCode--) | يعيد رمز CSS للوحدة التي يُحدَّد بها حجم صورة الشريحة. |
| [getPreviousSlideIndex()](#getPreviousSlideIndex--) | يعيد فهرس الشريحة التي تم عرضها مسبقًا أو -1 إذا كانت الشريحة الأولى قيد العرض. |
| [getSlideIndex()](#getSlideIndex--) | يعيد فهرس الشريحة الحالية قيد العرض. |
| [getNextSlideIndex()](#getNextSlideIndex--) | يعيد فهرس الشريحة التي سيتم عرضها بعد الشريحة الحالية أو -1 إذا كانت الشريحة الحالية هي الأخيرة. |
### addHtml(String html) {#addHtml-java.lang.String-}
```
public abstract void addHtml(String html)
```

يضيف نص HTML منسق.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| html | java.lang.String | النص المراد إضافته. |

### addHtml(char[] html) {#addHtml-char---}
```
public abstract void addHtml(char[] html)
```

يضيف نص HTML منسق.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| html | char[] | النص المراد إضافته. |

### addHtml(char[] html, int startIndex, int length) {#addHtml-char---int-int-}
```
public abstract void addHtml(char[] html, int startIndex, int length)
```

يضيف نص HTML منسق.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| html | char[] | النص المراد إضافته. |
| startIndex | int | فهرس البداية للجزء المراد إضافته. |
| length | int | طول الجزء المراد إضافته. |

### addText(String text) {#addText-java.lang.String-}
```
public abstract void addText(String text)
```

يضيف نصًا عاديًا إلى ملفات HTML، مع استبدال الأحرف الخاصة بكيانات HTML. لا يتم استبدال فواصل الأسطر والمسافات البيضاء.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| text | java.lang.String | النص المراد إضافته. |

### addText(char[] text) {#addText-char---}
```
public abstract void addText(char[] text)
```

يضيف نصًا عاديًا إلى ملفات HTML، مع استبدال الأحرف الخاصة بكيانات HTML. لا يتم استبدال فواصل الأسطر والمسافات البيضاء.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| text | char[] | النص المراد إضافته. |

### addText(char[] text, int startIndex, int length) {#addText-char---int-int-}
```
public abstract void addText(char[] text, int startIndex, int length)
```

يضيف نصًا عاديًا إلى ملفات HTML، مع استبدال الأحرف الخاصة بكيانات HTML. لا يتم استبدال فواصل الأسطر والمسافات البيضاء.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| text | char[] | النص المراد إضافته. |
| startIndex | int | فهرس البداية للجزء المراد إضافته. |
| length | int | طول الجزء المراد إضافته. |

### addAttributeValue(String value) {#addAttributeValue-java.lang.String-}
```
public abstract void addAttributeValue(String value)
```

يقوم بقتباس قيمة السمة ويضيفها إلى ملف HTML.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String | سلسلة قيمة السمة. |

### addAttributeValue(char[] value) {#addAttributeValue-char---}
```
public abstract void addAttributeValue(char[] value)
```

يقوم بقتباس قيمة السمة ويضيفها إلى ملف HTML.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | char[] | سلسلة قيمة السمة. |

### addAttributeValue(char[] value, int startIndex, int length) {#addAttributeValue-char---int-int-}
```
public abstract void addAttributeValue(char[] value, int startIndex, int length)
```

يقوم بقتباس قيمة السمة ويضيفها إلى ملف HTML.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | char[] | سلسلة قيمة السمة. |
| startIndex | int | فهرس البداية للجزء المراد إضافته. |
| length | int | طول الجزء المراد إضافته. |

### getSlideImageSize() {#getSlideImageSize--}
```
public abstract Dimension2D getSlideImageSize()
```

يعيد حجم صورة الشريحة. للقراءة فقط java.awt.geom.Dimension2D.

**القيمة المرجعة:**
java.awt.geom.Dimension2D

### getSlideImageSizeUnit() {#getSlideImageSizeUnit--}
```
public abstract int getSlideImageSizeUnit()
```

يعيد الوحدة التي يُحدَّد بها حجم صورة الشريحة. للقراءة فقط [SvgCoordinateUnit](../../com.aspose.slides/svgcoordinateunit).

**القيمة المرجعة:**
int

### getSlideImageSizeUnitCode() {#getSlideImageSizeUnitCode--}
```
public abstract String getSlideImageSizeUnitCode()
```

يعيد رمز CSS للوحدة التي يُحدَّد بها حجم صورة الشريحة. للقراءة فقط String.

**القيمة المرجعة:**
java.lang.String

### getPreviousSlideIndex() {#getPreviousSlideIndex--}
```
public abstract int getPreviousSlideIndex()
```

يعيد فهرس الشريحة التي تم عرضها مسبقًا أو -1 إذا كانت الشريحة الأولى قيد العرض. للقراءة فقط int.

**القيمة المرجعة:**
int

### getSlideIndex() {#getSlideIndex--}
```
public abstract int getSlideIndex()
```

يعيد فهرس الشريحة الحالية قيد العرض. للقراءة فقط int.

**القيمة المرجعة:**
int

### getNextSlideIndex() {#getNextSlideIndex--}
```
public abstract int getNextSlideIndex()
```

يعيد فهرس الشريحة التي سيتم عرضها بعد الشريحة الحالية أو -1 إذا كانت الشريحة الحالية هي الأخيرة. للقراءة فقط int.

**القيمة المرجعة:**
int