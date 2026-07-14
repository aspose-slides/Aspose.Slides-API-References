---
title: IPatternFormat
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a pattern to fill a shape.
type: docs
url: /ar/com.aspose.slides/ipatternformat/
---```
public interface IPatternFormat
```

يمثل نمطًا لملء شكل.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getPatternStyle()](#getPatternStyle--) | إرجاع أو تعيين نمط النموذج. |
| [setPatternStyle(byte value)](#setPatternStyle-byte-) | إرجاع أو تعيين نمط النموذج. |
| [getForeColor()](#getForeColor--) | إرجاع لون نمط المقدمة. |
| [getBackColor()](#getBackColor--) | إرجاع لون نمط الخلفية. |
| [getTile(Integer background, Integer foreground)](#getTile-java.lang.Integer-java.lang.Integer-) | إنشاء صورة بلاطة لتعبئة النمط بألوان محددة. |
| [getTile(Integer styleColor)](#getTile-java.lang.Integer-) | إنشاء صورة بلاطة لتعبئة النمط. |
### getPatternStyle() {#getPatternStyle--}
```
public abstract byte getPatternStyle()
```

إرجاع أو تعيين نمط النموذج. قراءة/كتابة [PatternStyle](../../com.aspose.slides/patternstyle).

**الإرجاع:**
byte
### setPatternStyle(byte value) {#setPatternStyle-byte-}
```
public abstract void setPatternStyle(byte value)
```

إرجاع أو تعيين نمط النموذج. قراءة/كتابة [PatternStyle](../../com.aspose.slides/patternstyle).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getForeColor() {#getForeColor--}
```
public abstract IColorFormat getForeColor()
```

إرجاع لون نمط المقدمة. للقراءة فقط [IColorFormat](../../com.aspose.slides/icolorformat).

**الإرجاع:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getBackColor() {#getBackColor--}
```
public abstract IColorFormat getBackColor()
```

إرجاع لون نمط الخلفية. للقراءة فقط [IColorFormat](../../com.aspose.slides/icolorformat).

**الإرجاع:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getTile(Integer background, Integer foreground) {#getTile-java.lang.Integer-java.lang.Integer-}
```
public abstract IImage getTile(Integer background, Integer foreground)
```

إنشاء صورة بلاطة لتعبئة النمط بألوان محددة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| background | java.lang.Integer | قيمة java.lang.Integer الخلفية للنمط. |
| foreground | java.lang.Integer | قيمة java.lang.Integer المقدمة للنمط. |

**الإرجاع:**
[IImage](../../com.aspose.slides/iimage) - بلاطة android.graphics.Bitmap.
### getTile(Integer styleColor) {#getTile-java.lang.Integer-}
```
public abstract IImage getTile(Integer styleColor)
```

إنشاء صورة بلاطة لتعبئة النمط.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| styleColor | java.lang.Integer | القيمة الافتراضية java.lang.Integer، المحددة في كائن StyleEx الخاص بـ ShapeEx. يمكن أن تعتمد ألوان التعبئة على هذا. |

**الإرجاع:**
[IImage](../../com.aspose.slides/iimage) - بلاطة android.graphics.Bitmap.