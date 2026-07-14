---
title: PatternFormat
second_title: Aspose.Slides لأندرويد عبر مرجع واجهة برمجة التطبيقات لجافا
description: يمثل نمطًا لتعبئة شكل.
type: docs
url: /ar/com.aspose.slides/patternformat/
---
**الوراثة:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**جميع الواجهات المنفذة:**
[com.aspose.slides.IPatternFormat](../../com.aspose.slides/ipatternformat)
```
public final class PatternFormat extends PVIObject implements IPatternFormat
```

يمثل نمطًا لتعبئة شكل.

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getPatternStyle()](#getPatternStyle--) | إرجاع أو تعيين نمط النمط. |
| [setPatternStyle(byte value)](#setPatternStyle-byte-) | إرجاع أو تعيين نمط النمط. |
| [getForeColor()](#getForeColor--) | إرجاع لون نمط المقدمة. |
| [getBackColor()](#getBackColor--) | إرجاع لون نمط الخلفية. |
| [getTile(Integer background, Integer foreground)](#getTile-java.lang.Integer-java.lang.Integer-) | إنشاء صورة بلاط لتعبئة النمط بألوان محددة. |
| [getTile(Integer styleColor)](#getTile-java.lang.Integer-) | إنشاء صورة بلاط لتعبئة النمط. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

الإصدار. قراءة فقط long.

**الإرجاع:**
long

### getPatternStyle() {#getPatternStyle--}
```
public final byte getPatternStyle()
```

إرجاع أو تعيين نمط النمط. قراءة/كتابة [PatternStyle](../../com.aspose.slides/patternstyle).

**الإرجاع:**
byte

### setPatternStyle(byte value) {#setPatternStyle-byte-}
```
public final void setPatternStyle(byte value)
```

إرجاع أو تعيين نمط النمط. قراءة/كتابة [PatternStyle](../../com.aspose.slides/patternstyle).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getForeColor() {#getForeColor--}
```
public final IColorFormat getForeColor()
```

إرجاع لون نمط المقدمة. قراءة فقط [IColorFormat](../../com.aspose.slides/icolorformat).

**الإرجاع:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getBackColor() {#getBackColor--}
```
public final IColorFormat getBackColor()
```

إرجاع لون نمط الخلفية. قراءة فقط [IColorFormat](../../com.aspose.slides/icolorformat).

**الإرجاع:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getTile(Integer background, Integer foreground) {#getTile-java.lang.Integer-java.lang.Integer-}
```
public final IImage getTile(Integer background, Integer foreground)
```

إنشاء صورة بلاط لتعبئة النمط بألوان محددة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| background | java.lang.Integer | الـ java.lang.Integer الخلفي للنمط. |
| foreground | java.lang.Integer | الـ java.lang.Integer الأمامي للنمط. |

**الإرجاع:**
[IImage](../../com.aspose.slides/iimage) - بلاط [IImage](../../com.aspose.slides/iimage).

### getTile(Integer styleColor) {#getTile-java.lang.Integer-}
```
public final IImage getTile(Integer styleColor)
```

إنشاء صورة بلاط لتعبئة النمط.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| styleColor | java.lang.Integer | الـ java.lang.Integer الافتراضي |

**الإرجاع:**
[IImage](../../com.aspose.slides/iimage) - بلاط [IImage](../../com.aspose.slides/iimage).