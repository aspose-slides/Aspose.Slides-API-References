---
title: IPatternFormat
second_title: Aspose.Slides for Java API Reference
description: Represents a pattern to fill a shape.
type: docs
url: /ar/com.aspose.slides/ipatternformat/
---```
public interface IPatternFormat
```

يمثل نمطًا لملء شكل.
## الطرق

| Method | Description |
| --- | --- |
| [getPatternStyle()](#getPatternStyle--) | إرجاع أو تعيين نمط النمط. |
| [setPatternStyle(byte value)](#setPatternStyle-byte-) | إرجاع أو تعيين نمط النمط. |
| [getForeColor()](#getForeColor--) | إرجاع لون النمط الأمامي. |
| [getBackColor()](#getBackColor--) | إرجاع لون النمط الخلفي. |
| [getTile(Color background, Color foreground)](#getTile-java.awt.Color-java.awt.Color-) | إنشاء صورة تجانب لملء النمط بألوان محددة. |
| [getTile(Color styleColor)](#getTile-java.awt.Color-) | إنشاء صورة تجانب لملء النمط. |
### getPatternStyle() {#getPatternStyle--}
```
public abstract byte getPatternStyle()
```

إرجاع أو تعيين نمط النمط. قراءة/كتابة [PatternStyle](../../com.aspose.slides/patternstyle).

**القيمة المرتجعة:**
byte
### setPatternStyle(byte value) {#setPatternStyle-byte-}
```
public abstract void setPatternStyle(byte value)
```

إرجاع أو تعيين نمط النمط. قراءة/كتابة [PatternStyle](../../com.aspose.slides/patternstyle).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |
### getForeColor() {#getForeColor--}
```
public abstract IColorFormat getForeColor()
```

إرجاع لون النمط الأمامي. قراءة فقط [IColorFormat](../../com.aspose.slides/icolorformat).

**القيمة المرتجعة:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getBackColor() {#getBackColor--}
```
public abstract IColorFormat getBackColor()
```

إرجاع لون النمط الخلفي. قراءة فقط [IColorFormat](../../com.aspose.slides/icolorformat).

**القيمة المرتجعة:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getTile(Color background, Color foreground) {#getTile-java.awt.Color-java.awt.Color-}
```
public abstract IImage getTile(Color background, Color foreground)
```

إنشاء صورة تجانب لملء النمط بألوان محددة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| background | java.awt.Color | لون الخلفية java.awt.Color للنمط. |
| foreground | java.awt.Color | لون الأمام java.awt.Color للنمط. |

**القيمة المرتجعة:**
[IImage](../../com.aspose.slides/iimage) - بلاطة java.awt.image.BufferedImage.
### getTile(Color styleColor) {#getTile-java.awt.Color-}
```
public abstract IImage getTile(Color styleColor)
```

إنشاء صورة تجانب لملء النمط.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| styleColor | java.awt.Color | لون java.awt.Color الافتراضي، معرف في كائن ShapeEx's StyleEx. يمكن أن تعتمد ألوان التعبئة على هذا. |

**القيمة المرتجعة:**
[IImage](../../com.aspose.slides/iimage) - بلاطة java.awt.image.BufferedImage.