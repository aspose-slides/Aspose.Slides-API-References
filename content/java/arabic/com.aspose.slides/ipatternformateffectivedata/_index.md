---
title: IPatternFormatEffectiveData
second_title: Aspose.Slides for Java API Reference
description: كائن غير قابل للتغيير يحتوي على خصائص تعبئة النمط الفعالة.
type: docs
url: /ar/com.aspose.slides/ipatternformateffectivedata/
---```
public interface IPatternFormatEffectiveData
```

كائن غير قابل للتغيير يحتوي على خصائص تعبئة النمط الفعالة.

--------------------

يتم استخدام هذه الواجهة كجزء من [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) و [ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata).
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getPatternStyle()](#getPatternStyle--) | يرجع نمط النمط. |
| [getForeColor()](#getForeColor--) | يرجع لون النمط الأمامي. |
| [getBackColor()](#getBackColor--) | يرجع لون النمط الخلفي. |
| [getTileIImage(Color background, Color foreground)](#getTileIImage-java.awt.Color-java.awt.Color-) | ينشئ صورة تجانب للنمط مع الألوان المحددة. |
### getPatternStyle() {#getPatternStyle--}
```
public abstract byte getPatternStyle()
```

يرجع نمط النمط. للقراءة فقط [PatternStyle](../../com.aspose.slides/patternstyle).

**القيمة المرجعة:**
byte
### getForeColor() {#getForeColor--}
```
public abstract Color getForeColor()
```

يرجع لون النمط الأمامي. للقراءة فقط java.awt.Color.

**القيمة المرجعة:**
java.awt.Color
### getBackColor() {#getBackColor--}
```
public abstract Color getBackColor()
```

يرجع لون النمط الخلفي. للقراءة فقط java.awt.Color.

**القيمة المرجعة:**
java.awt.Color
### getTileIImage(Color background, Color foreground) {#getTileIImage-java.awt.Color-java.awt.Color-}
```
public abstract IImage getTileIImage(Color background, Color foreground)
```

ينشئ صورة تجانب للنمط مع الألوان المحددة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| background | java.awt.Color | لون java.awt.Color الخلفي للنمط. |
| foreground | java.awt.Color | لون java.awt.Color الأمامي للنمط. |

**قيمة الإرجاع:**
[IImage](../../com.aspose.slides/iimage) - Tile [IImage](../../com.aspose.slides/iimage).