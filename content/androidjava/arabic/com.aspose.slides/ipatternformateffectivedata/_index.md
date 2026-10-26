---
title: IPatternFormatEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: كائن غير قابل للتغيير يحتوي على خصائص تعبئة النمط الفعّالة.
type: docs
url: /ar/com.aspose.slides/ipatternformateffectivedata/
---```
public interface IPatternFormatEffectiveData
```

كائن غير قابل للتغيير يحتوي على خصائص تعبئة النمط الفعّالة.

--------------------

يتم استخدام هذه الواجهة كجزء من [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) and [ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata).
## Methods

| الطريقة | الوصف |
| --- | --- |
| [getPatternStyle()](#getPatternStyle--) | يرجع نمط النمط. |
| [getForeColor()](#getForeColor--) | يرجع لون نمط المقدمة. |
| [getBackColor()](#getBackColor--) | يرجع لون نمط الخلفية. |
| [getTileIImage(Integer background, Integer foreground)](#getTileIImage-java.lang.Integer-java.lang.Integer-) | إنشاء صورة بلاطة لتعبئة النمط بألوان محددة. |
### getPatternStyle() {#getPatternStyle--}
```
public abstract byte getPatternStyle()
```


يرجع نمط النمط. للقراءة فقط [PatternStyle](../../com.aspose.slides/patternstyle).

**Returns:**
byte
### getForeColor() {#getForeColor--}
```
public abstract Integer getForeColor()
```


يرجع لون نمط المقدمة. للقراءة فقط java.lang.Integer.

**Returns:**
java.lang.Integer
### getBackColor() {#getBackColor--}
```
public abstract Integer getBackColor()
```


يرجع لون نمط الخلفية. للقراءة فقط java.lang.Integer.

**Returns:**
java.lang.Integer
### getTileIImage(Integer background, Integer foreground) {#getTileIImage-java.lang.Integer-java.lang.Integer-}
```
public abstract IImage getTileIImage(Integer background, Integer foreground)
```


إنشاء صورة بلاطة لتعبئة النمط بألوان محددة.

**Parameters:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| background | java.lang.Integer | قيمة java.lang.Integer للخلفية للنمط. |
| foreground | java.lang.Integer | قيمة java.lang.Integer للمقدمة للنمط. |

**Returns:**
[IImage](../../com.aspose.slides/iimage) - بلاطة [IImage](../../com.aspose.slides/iimage).