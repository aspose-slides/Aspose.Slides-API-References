---
title: IHtmlGenerator
second_title: Aspose.Slides for Android via Java API Reference
description: Html generator.
type: docs
url: /ar/com.aspose.slides/ihtmlgenerator/
---```
public interface IHtmlGenerator
```

مولِّد HTML.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [addHtml(String html)](#addHtml-java.lang.String-) | يضيف نص HTML مُنسق. |
| [addHtml(char[] html)](#addHtml-char---) | يضيف نص HTML مُنسق. |
| [addHtml(char[] html, int startIndex, int length)](#addHtml-char---int-int-) | يضيف نص HTML مُنسق. |
| [addText(String text)](#addText-java.lang.String-) | يضيف نصًا عاديًا إلى ملفات HTML، مع استبدال الأحرف الخاصة بكيانات HTML. |
| [addText(char[] text)](#addText-char---) | يضيف نصًا عاديًا إلى ملفات HTML، مع استبدال الأحرف الخاصة بكيانات HTML. |
| [addText(char[] text, int startIndex, int length)](#addText-char---int-int-) | يضيف نصًا عاديًا إلى ملفات HTML، مع استبدال الأحرف الخاصة بكيانات HTML. |
| [addAttributeValue(String value)](#addAttributeValue-java.lang.String-) | يقتبس قيمة السمة ويضيفها إلى ملف HTML. |
| [addAttributeValue(char[] value)](#addAttributeValue-char---) | يقتبس قيمة السمة ويضيفها إلى ملف HTML. |
| [addAttributeValue(char[] value, int startIndex, int length)](#addAttributeValue-char---int-int-) | يقتبس قيمة السمة ويضيفها إلى ملف HTML. |
| [getSlideImageSize()](#getSlideImageSize--) | يعيد حجم صورة الشريحة. |
| [getSlideImageSizeUnit()](#getSlideImageSizeUnit--) | يعيد الوحدة التي يُحدَّد بها حجم صورة الشريحة. |
| [getSlideImageSizeUnitCode()](#getSlideImageSizeUnitCode--) | يعيد رمز CSS للوحدة التي يُحدَّد بها حجم صورة الشريحة. |
| [getPreviousSlideIndex()](#getPreviousSlideIndex--) | يعيد فهرس الشريحة التي تم عرضها مسبقًا أو -1 إذا كانت الشريحة الأولى قيد العرض. |
| [getSlideIndex()](#getSlideIndex--) | يعيد فهرس الشريحة التي تُعرض حاليًا. |
| [getNextSlideIndex()](#getNextSlideIndex--) | يعيد فهرس الشريحة التي ستُعرض بعد الشريحة الحالية أو -1 إذا كانت الشريحة الأخيرة تُعرض حاليًا. |

### addHtml(String html) {#addHtml-java.lang.String-}
```
public abstract void addHtml(String html)
```

يضيف نص HTML مُنسق.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| html | java.lang.String | النص المراد إضافته. |

### addHtml(char[] html) {#addHtml-char---}
```
public abstract void addHtml(char[] html)
```

يضيف نص HTML مُنسق.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| html | char[] | النص المراد إضافته. |

### addHtml(char[] html, int startIndex, int length) {#addHtml-char---int-int-}
```
public abstract void addHtml(char[] html, int startIndex, int length)
```

يضيف نص HTML مُنسق.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| html | char[] | النص المراد إضافته. |
| startIndex | int | الفهرس الابتدائي للجزء المراد إضافته. |
| length | int | طول الجزء المراد إضافته. |

### addText(String text) {#addText-java.lang.String-}
```
public abstract void addText(String text)
```

يضيف نصًا عاديًا إلى ملفات HTML، مع استبدال الأحرف الخاصة بكيانات HTML. لا يتم استبدال فواصل الأسطر والمسافات البيضاء.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| text | java.lang.String | النص المراد إضافته. |

### addText(char[] text) {#addText-char---}
```
public abstract void addText(char[] text)
```

يضيف نصًا عاديًا إلى ملفات HTML، مع استبدال الأحرف الخاصة بكيانات HTML. لا يتم استبدال فواصل الأسطر والمسافات البيضاء.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| text | char[] | النص المراد إضافته. |

### addText(char[] text, int startIndex, int length) {#addText-char---int-int-}
```
public abstract void addText(char[] text, int startIndex, int length)
```

يضيف نصًا عاديًا إلى ملفات HTML، مع استبدال الأحرف الخاصة بكيانات HTML. لا يتم استبدال فواصل الأسطر والمسافات البيضاء.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| text | char[] | النص المراد إضافته. |
| startIndex | int | الفهرس الابتدائي للجزء المراد إضافته. |
| length | int | طول الجزء المراد إضافته. |

### addAttributeValue(String value) {#addAttributeValue-java.lang.String-}
```
public abstract void addAttributeValue(String value)
```

يقتبس قيمة السمة ويضيفها إلى ملف HTML.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String | سلسلة قيمة السمة. |

### addAttributeValue(char[] value) {#addAttributeValue-char---}
```
public abstract void addAttributeValue(char[] value)
```

يقتبس قيمة السمة ويضيفها إلى ملف HTML.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | char[] | سلسلة قيمة السمة. |

### addAttributeValue(char[] value, int startIndex, int length) {#addAttributeValue-char---int-int-}
```
public abstract void addAttributeValue(char[] value, int startIndex, int length)
```

يقتبس قيمة السمة ويضيفها إلى ملف HTML.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | char[] | سلسلة قيمة السمة. |
| startIndex | int | الفهرس الابتدائي للجزء المراد إضافته. |
| length | int | طول الجزء المراد إضافته. |

### getSlideImageSize() {#getSlideImageSize--}
```
public abstract SizeF getSlideImageSize()
```

يعيد حجم صورة الشريحة. للقراءة فقط [SizeF](../../com.aspose.slides.android/sizef).

**القيم المرجعة:**
[SizeF](../../com.aspose.slides.android/sizef)

### getSlideImageSizeUnit() {#getSlideImageSizeUnit--}
```
public abstract int getSlideImageSizeUnit()
```

يعيد الوحدة التي يُحدَّد بها حجم صورة الشريحة. للقراءة فقط [SvgCoordinateUnit](../../com.aspose.slides/svgcoordinateunit).

**القيم المرجعة:**
int

### getSlideImageSizeUnitCode() {#getSlideImageSizeUnitCode--}
```
public abstract String getSlideImageSizeUnitCode()
```

يعيد رمز CSS للوحدة التي يُحدَّد بها حجم صورة الشريحة. للقراءة فقط String.

**القيم المرجعة:**
java.lang.String

### getPreviousSlideIndex() {#getPreviousSlideIndex--}
```
public abstract int getPreviousSlideIndex()
```

يعيد فهرس الشريحة التي تم عرضها مسبقًا أو -1 إذا كانت الشريحة الأولى قيد العرض. للقراءة فقط int.

**القيم المرجعة:**
int

### getSlideIndex() {#getSlideIndex--}
```
public abstract int getSlideIndex()
```

يعيد فهرس الشريحة التي تُعرض حاليًا. للقراءة فقط int.

**القيم المرجعة:**
int

### getNextSlideIndex() {#getNextSlideIndex--}
```
public abstract int getNextSlideIndex()
```

يعيد فهرس الشريحة التي ستُعرض بعد الشريحة الحالية أو -1 إذا كانت الشريحة الأخيرة تُعرض حاليًا. للقراءة فقط int.

**القيم المرجعة:**
int