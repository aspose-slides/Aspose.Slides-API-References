---
title: ILineFillFormatEffectiveData
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: كائن غير قابل للتغيير يحتوي على خصائص تعبئة الخط الفعّالة.
type: docs
url: /ar/com.aspose.slides/ilinefillformateffectivedata/
---
**جميع الواجهات المُنفذة:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface ILineFillFormatEffectiveData extends IFillParamSource
```

كائن غير قابل للتغيير يحتوي على خصائص تعبئة الخط الفعّالة.

--------------------

تُستخدم هذه الواجهة كجزء من [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getFillType()](#getFillType--) | يعيد نوع التعبئة. |
| [getSolidFillColor()](#getSolidFillColor--) | يعيد لون التعبئة الصلبة. |
| [getGradientFormat()](#getGradientFormat--) | يعيد تنسيق تعبئة التدرج. |
| [getPatternFormat()](#getPatternFormat--) | يعيد تنسيق تعبئة النمط. |
| [getRotateWithShape()](#getRotateWithShape--) | يحدد ما إذا كان يجب تدوير التعبئة مع الشكل. |

### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```

يعيد نوع التعبئة. للقراءة فقط [FillType](../../com.aspose.slides/filltype).

**الإرجاع:**
byte

### getSolidFillColor() {#getSolidFillColor--}
```
public abstract Integer getSolidFillColor()
```

يعيد لون التعبئة الصلبة. للقراءة فقط java.lang.Integer.

**الإرجاع:**
java.lang.Integer

### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormatEffectiveData getGradientFormat()
```

يعيد تنسيق تعبئة التدرج. للقراءة فقط [IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata).

**الإرجاع:**
[IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata)

### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormatEffectiveData getPatternFormat()
```

يعيد تنسيق تعبئة النمط. للقراءة فقط [IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata).

**الإرجاع:**
[IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata)

### getRotateWithShape() {#getRotateWithShape--}
```
public abstract boolean getRotateWithShape()
```

يحدد ما إذا كان يجب تدوير التعبئة مع الشكل. للقراءة فقط boolean.

**الإرجاع:**
boolean