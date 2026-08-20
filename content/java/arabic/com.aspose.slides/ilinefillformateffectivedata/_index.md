---
title: ILineFillFormatEffectiveData
second_title: مرجع API لـ Aspose.Slides للجاوة
description: كائن غير قابل للتغيير يحتوي على خصائص تعبئة الخط الفعالة.
type: docs
url: /ar/com.aspose.slides/ilinefillformateffectivedata/
---
**جميع الواجهات التي تم تنفيذها:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface ILineFillFormatEffectiveData extends IFillParamSource
```

كائن غير قابل للتغيير يحتوي على خصائص تعبئة الخط الفعالة.

--------------------

يُستخدم هذا الواجهة كجزء من [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getFillType()](#getFillType--) | يعيد نوع التعبئة. |
| [getSolidFillColor()](#getSolidFillColor--) | يعيد لون تعبئة صلبة. |
| [getGradientFormat()](#getGradientFormat--) | يعيد تنسيق تعبئة التدرج. |
| [getPatternFormat()](#getPatternFormat--) | يعيد تنسيق تعبئة النمط. |
| [getRotateWithShape()](#getRotateWithShape--) | يحدد ما إذا كان يجب تدوير التعبئة مع الشكل. |
### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```


يعيد نوع التعبئة. للقراءة فقط [FillType](../../com.aspose.slides/filltype).

**القيمة المرجعة:**
byte
### getSolidFillColor() {#getSolidFillColor--}
```
public abstract Color getSolidFillColor()
```


يعيد لون تعبئة صلبة. للقراءة فقط java.awt.Color.

**القيمة المرجعة:**
java.awt.Color
### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormatEffectiveData getGradientFormat()
```


يعيد تنسيق تعبئة التدرج. للقراءة فقط [IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata).

**القيمة المرجعة:**
[IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata)
### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormatEffectiveData getPatternFormat()
```


يعيد تنسيق تعبئة النمط. للقراءة فقط [IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata).

**القيمة المرجعة:**
[IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract boolean getRotateWithShape()
```


يحدد ما إذا كان يجب تدوير التعبئة مع الشكل. للقراءة فقط boolean.

**القيمة المرجعة:**
boolean