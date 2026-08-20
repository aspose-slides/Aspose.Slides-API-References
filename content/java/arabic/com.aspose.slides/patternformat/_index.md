---
title: PatternFormat
second_title: مرجع API لـ Aspose.Slides للغة Java
description: يمثل نمطًا لملء شكل.
type: docs
url: /ar/com.aspose.slides/patternformat/
---
**الوراثة:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**جميع الواجهات المُطبقة:**
[com.aspose.slides.IPatternFormat](../../com.aspose.slides/ipatternformat)
```
public final class PatternFormat extends PVIObject implements IPatternFormat
```

يمثل نمطًا لملء شكل.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getPatternStyle()](#getPatternStyle--) | إرجاع أو تعيين نمط النمط. |
| [setPatternStyle(byte value)](#setPatternStyle-byte-) | إرجاع أو تعيين نمط النمط. |
| [getForeColor()](#getForeColor--) | إرجاع لون النمط الأمامي. |
| [getBackColor()](#getBackColor--) | إرجاع لون النمط الخلفي. |
| [getTile(Color background, Color foreground)](#getTile-java.awt.Color-java.awt.Color-) | إنشاء صورة بلاطة لملء النمط بألوان محددة. |
| [getTile(Color styleColor)](#getTile-java.awt.Color-) | إنشاء صورة بلاطة لملء النمط. |
### getVersion() {#getVersion--}
```
public long getVersion()
```


الإصدار. للقراءة فقط long.

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


إرجاع لون النمط الأمامي. للقراءة فقط [IColorFormat](../../com.aspose.slides/icolorformat).

**الإرجاع:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getBackColor() {#getBackColor--}
```
public final IColorFormat getBackColor()
```


إرجاع لون النمط الخلفي. للقراءة فقط [IColorFormat](../../com.aspose.slides/icolorformat).

**الإرجاع:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getTile(Color background, Color foreground) {#getTile-java.awt.Color-java.awt.Color-}
```
public final IImage getTile(Color background, Color foreground)
```


إنشاء صورة بلاطة لملء النمط بألوان محددة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| background | java.awt.Color | لون الخلفية java.awt.Color للنمط. |
| foreground | java.awt.Color | لون الأمام java.awt.Color للنمط. |

**الإرجاع:**
[IImage](../../com.aspose.slides/iimage) - بلاطة [IImage](../../com.aspose.slides/iimage).
### getTile(Color styleColor) {#getTile-java.awt.Color-}
```
public final IImage getTile(Color styleColor)
```


إنشاء صورة بلاطة لملء النمط.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| styleColor | java.awt.Color | لون java.awt.Color الافتراضي |

**الإرجاع:**
[IImage](../../com.aspose.slides/iimage) - بلاطة [IImage](../../com.aspose.slides/iimage).