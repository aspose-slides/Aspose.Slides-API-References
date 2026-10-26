---
title: IFillFormatEffectiveData
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: كائن غير قابل للتغيير يحتوي على خصائص تنسيق التعبئة الفعّالة.
type: docs
url: /ar/com.aspose.slides/ifillformateffectivedata/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IFillFormatEffectiveData extends IFillParamSource
```

كائن غير قابل للتغيير يحتوي على خصائص تنسيق التعبئة الفعّالة.

--------------------

يُستخدم هذا الواجهة مع واجهة [IFillFormat](../../com.aspose.slides/ifillformat) لإرجاع قيم التنسيق الفعّالة مع تطبيق الوراثة.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getFillType()](#getFillType--) | Returns the type of filling. |
| [getSolidFillColor()](#getSolidFillColor--) | Returns the fill color. |
| [getSolidFillSchemeColor()](#getSolidFillSchemeColor--) | Gets the fill color defined by a color scheme. |
| [getGradientFormat()](#getGradientFormat--) | Returns the gradient fill format. |
| [getPatternFormat()](#getPatternFormat--) | Returns the pattern fill format. |
| [getPictureFillFormat()](#getPictureFillFormat--) | Returns the picture fill format. |
| [getRotateWithShape()](#getRotateWithShape--) | Determines whether the fill should be rotated with shape. |
### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```


Returns the type of filling. للقراءة فقط [FillType](../../com.aspose.slides/filltype).

**القيمة المرجعة:**
byte
### getSolidFillColor() {#getSolidFillColor--}
```
public abstract Integer getSolidFillColor()
```


Returns the fill color. للقراءة فقط java.lang.Integer.

**القيمة المرجعة:**
java.lang.Integer
### getSolidFillSchemeColor() {#getSolidFillSchemeColor--}
```
public abstract int getSolidFillSchemeColor()
```


Gets the fill color defined by a color scheme. The [SchemeColor.NotDefined](../../com.aspose.slides/schemecolor\#NotDefined) value indicates that the  SolidFillColor (\#getSolidFillColor.getSolidFillColor) is not a scheme color. للقراءة فقط [SchemeColor](../../com.aspose.slides/schemecolor).

**القيمة المرجعة:**
int
### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormatEffectiveData getGradientFormat()
```


Returns the gradient fill format. للقراءة فقط [IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata).

**القيمة المرجعة:**
[IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata)
### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormatEffectiveData getPatternFormat()
```


Returns the pattern fill format. للقراءة فقط [IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata).

**القيمة المرجعة:**
[IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata)
### getPictureFillFormat() {#getPictureFillFormat--}
```
public abstract IPictureFillFormatEffectiveData getPictureFillFormat()
```


Returns the picture fill format. للقراءة فقط [IPictureFillFormatEffectiveData](../../com.aspose.slides/ipicturefillformateffectivedata).

**القيمة المرجعة:**
[IPictureFillFormatEffectiveData](../../com.aspose.slides/ipicturefillformateffectivedata)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract boolean getRotateWithShape()
```


Determines whether the fill should be rotated with shape. للقراءة فقط boolean.

**القيمة المرجعة:**
boolean