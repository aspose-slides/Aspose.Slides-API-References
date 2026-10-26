---
title: IFillFormatEffectiveData
second_title: مرجع API لـ Aspose.Slides للـ Java
description: كائن غير قابل للتغيير يحتوي على خصائص تنسيق التعبئة الفعّالة.
type: docs
url: /ar/com.aspose.slides/ifillformateffectivedata/
---
**جميع الواجهات المطبقة:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IFillFormatEffectiveData extends IFillParamSource
```

كائن غير قابل للتغيير يحتوي على خصائص تنسيق التعبئة الفعّالة.

--------------------

تُستخدم هذه الواجهة مع واجهة [IFillFormat](../../com.aspose.slides/ifillformat) لإرجاع قيم التنسيق الفعّالة مع تطبيق الوراثة.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getFillType()](#getFillType--) | يعيد نوع التعبئة. |
| [getSolidFillColor()](#getSolidFillColor--) | يعيد لون التعبئة. |
| [getSolidFillSchemeColor()](#getSolidFillSchemeColor--) | يحصل على لون التعبئة المحدد بواسطة مخطط ألوان. |
| [getGradientFormat()](#getGradientFormat--) | يعيد تنسيق التعبئة المتدرجة. |
| [getPatternFormat()](#getPatternFormat--) | يعيد تنسيق تعبئة النمط. |
| [getPictureFillFormat()](#getPictureFillFormat--) | يعيد تنسيق تعبئة الصورة. |
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


يعيد لون التعبئة. للقراءة فقط java.awt.Color.

**القيمة المرجعة:**
java.awt.Color
### getSolidFillSchemeColor() {#getSolidFillSchemeColor--}
```
public abstract int getSolidFillSchemeColor()
```


يحصل على لون التعبئة المحدد بواسطة مخطط ألوان. القيمة [SchemeColor.NotDefined](../../com.aspose.slides/schemecolor\#NotDefined) تشير إلى أن SolidFillColor (\#getSolidFillColor.getSolidFillColor) ليست لون مخطط. للقراءة فقط [SchemeColor](../../com.aspose.slides/schemecolor).

**القيمة المرجعة:**
int
### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormatEffectiveData getGradientFormat()
```


يعيد تنسيق التعبئة المتدرجة. للقراءة فقط [IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata).

**القيمة المرجعة:**
[IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata)
### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormatEffectiveData getPatternFormat()
```


يعيد تنسيق تعبئة النمط. للقراءة فقط [IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata).

**القيمة المرجعة:**
[IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata)
### getPictureFillFormat() {#getPictureFillFormat--}
```
public abstract IPictureFillFormatEffectiveData getPictureFillFormat()
```


يعيد تنسيق تعبئة الصورة. للقراءة فقط [IPictureFillFormatEffectiveData](../../com.aspose.slides/ipicturefillformateffectivedata).

**القيمة المرجعة:**
[IPictureFillFormatEffectiveData](../../com.aspose.slides/ipicturefillformateffectivedata)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract boolean getRotateWithShape()
```


يحدد ما إذا كان يجب تدوير التعبئة مع الشكل. للقراءة فقط boolean.

**القيمة المرجعة:**
boolean