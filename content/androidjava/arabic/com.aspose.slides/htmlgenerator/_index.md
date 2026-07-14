---
title: HtmlGenerator
second_title: Aspose.Slides لنظام Android عبر مرجع API جافا
description: مولد HTML.
type: docs
url: /ar/com.aspose.slides/htmlgenerator/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المنفذة:**
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
| [addText(String text)](#addText-java.lang.String-) | يضيف نصًا عاديًا إلى ملفات HTML، مع استبدال الأحرف الخاصة بكيانات HTML. |
| [addText(char[] text)](#addText-char---) | يضيف نصًا عاديًا إلى ملفات HTML، مع استبدال الأحرف الخاصة بكيانات HTML. |
| [addText(char[] text, int startIndex, int length)](#addText-char---int-int-) | يضيف نصًا عاديًا إلى ملفات HTML، مع استبدال الأحرف الخاصة بكيانات HTML. |
| [addAttributeValue(String value)](#addAttributeValue-java.lang.String-) | يقتبس قيمة الخاصية ويضيفها إلى ملف HTML. |
| [addAttributeValue(char[] value)](#addAttributeValue-char---) | يقتبس قيمة الخاصية ويضيفها إلى ملف HTML. |
| [addAttributeValue(char[] value, int startIndex, int length)](#addAttributeValue-char---int-int-) | يقتبس قيمة الخاصية ويضيفها إلى ملف HTML. |
| [getSlideImageSize()](#getSlideImageSize--) | يعيد حجم صورة الشريحة. |
| [getSlideImageSizeUnit()](#getSlideImageSizeUnit--) | يعيد الوحدة التي يُحدَّد بها حجم صورة الشريحة. |
| [getSlideImageSizeUnitCode()](#getSlideImageSizeUnitCode--) | يعيد رمز CSS للوحدة التي يُحدَّد بها حجم صورة الشريحة. |
| [getPreviousSlideIndex()](#getPreviousSlideIndex--) | يعيد فهرس الشريحة التي تم عرضها مسبقًا أو -1 إذا كانت الشريحة الأولى تُعرض. |
| [getSlideIndex()](#getSlideIndex--) | يعيد فهرس الشريحة الحالية التي تُعرض. |
| [getNextSlideIndex()](#getNextSlideIndex--) | يعيد فهرس شريحة سيتم عرضها بعد الشريحة الحالية أو -1 إذا كانت الشريحة الأخيرة تُعرض حاليًا. |

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
| startIndex | int | الفهرس الابتدائي للجزء المراد إضافته. |
| length | int | طول الجزء المراد إضافته. |

### addText(String text) {#addText-java.lang.String-}
```
public final void addText(String text)
```

يضيف نصًا عاديًا إلى ملفات HTML، مع استبدال الأحرف الخاصة بكيانات HTML. لا يتم استبدال فواصل الأسطر والمسافات البيضاء.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| text | java.lang.String | النص المراد إضافته. |

### addText(char[] text) {#addText-char---}
```
public final void addText(char[] text)
```

يضيف نصًا عاديًا إلى ملفات HTML، مع استبدال الأحرف الخاصة بكيانات HTML. لا يتم استبدال فواصل الأسطر والمسافات البيضاء.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| text | char[] | النص المراد إضافته. |

### addText(char[] text, int startIndex, int length) {#addText-char---int-int-}
```
public final void addText(char[] text, int startIndex, int length)
```

يضيف نصًا عاديًا إلى ملفات HTML، مع استبدال الأحرف الخاصة بكيانات HTML. لا يتم استبدال فواصل الأسطر والمسافات البيضاء.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| text | char[] | النص المراد إضافته. |
| startIndex | int | الفهرس الابتدائي للجزء المراد إضافته. |
| length | int | طول الجزء المراد إضافته. |

### addAttributeValue(String value) {#addAttributeValue-java.lang.String-}
```
public final void addAttributeValue(String value)
```

يقتبس قيمة الخاصية ويضيفها إلى ملف HTML.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String | سلسلة قيمة الخاصية. |

### addAttributeValue(char[] value) {#addAttributeValue-char---}
```
public final void addAttributeValue(char[] value)
```

يقتبس قيمة الخاصية ويضيفها إلى ملف HTML.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | char[] | سلسلة قيمة الخاصية. |

### addAttributeValue(char[] value, int startIndex, int length) {#addAttributeValue-char---int-int-}
```
public final void addAttributeValue(char[] value, int startIndex, int length)
```

يقتبس قيمة الخاصية ويضيفها إلى ملف HTML.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | char[] | سلسلة قيمة الخاصية. |
| startIndex | int | الفهرس الابتدائي للجزء المراد إضافته. |
| length | int | طول الجزء المراد إضافته. |

### getSlideImageSize() {#getSlideImageSize--}
```
public final SizeF getSlideImageSize()
```

يعيد حجم صورة الشريحة. للقراءة فقط [SizeF](../../com.aspose.slides.android/sizef).

**القيمة المرجعة:**
[SizeF](../../com.aspose.slides.android/sizef)

### getSlideImageSizeUnit() {#getSlideImageSizeUnit--}
```
public final int getSlideImageSizeUnit()
```

يعيد الوحدة التي يُحدَّد بها حجم صورة الشريحة. للقراءة فقط [SvgCoordinateUnit](../../com.aspose.slides/svgcoordinateunit).

**القيمة المرجعة:**
int

### getSlideImageSizeUnitCode() {#getSlideImageSizeUnitCode--}
```
public final String getSlideImageSizeUnitCode()
```

يعيد رمز CSS للوحدة التي يُحدَّد بها حجم صورة الشريحة. للقراءة فقط String.

**القيمة المرجعة:**
java.lang.String

### getPreviousSlideIndex() {#getPreviousSlideIndex--}
```
public final int getPreviousSlideIndex()
```

يعيد فهرس الشريحة التي تم عرضها مسبقًا أو -1 إذا كانت الشريحة الأولى تُعرض. للقراءة فقط int.

**القيمة المرجعة:**
int

### getSlideIndex() {#getSlideIndex--}
```
public final int getSlideIndex()
```

يعيد فهرس الشريحة الحالية التي تُعرض. للقراءة فقط int.

**القيمة المرجعة:**
int

### getNextSlideIndex() {#getNextSlideIndex--}
```
public final int getNextSlideIndex()
```

يعيد فهرس شريحة سيتم عرضها بعد الشريحة الحالية أو -1 إذا كانت الشريحة الأخيرة تُعرض حاليًا. للقراءة فقط int.

**القيمة المرجعة:**
int