---
title: ILineFillFormatEffectiveData
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: شیء غیرقابل تغییر که شامل ویژگی‌های مؤثر پر کردن خط است.
type: docs
url: /fa/com.aspose.slides/ilinefillformateffectivedata/
---
**All Implemented Interfaces:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface ILineFillFormatEffectiveData extends IFillParamSource
```

شیء غیرقابل تغییر که شامل ویژگی‌های پر کردن خط مؤثر است.

--------------------

این رابط به عنوان بخشی از [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata) استفاده می‌شود.
## متدها

| متد | توضیح |
| --- | --- |
| [getFillType()](#getFillType--) | نوع پر کردن را برمی‌گرداند. |
| [getSolidFillColor()](#getSolidFillColor--) | رنگ پر کردن صلب را برمی‌گرداند. |
| [getGradientFormat()](#getGradientFormat--) | قالب پر کردن گرادیان را برمی‌گرداند. |
| [getPatternFormat()](#getPatternFormat--) | قالب پر کردن الگو را برمی‌گرداند. |
| [getRotateWithShape()](#getRotateWithShape--) | تعیین می‌کند که آیا پر کردن باید با شکل چرخانده شود یا نه. |
### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```


نوع پر کردن را برمی‌گرداند. فقط قابل خواندن [FillType](../../com.aspose.slides/filltype).

**بازگشت:**
byte
### getSolidFillColor() {#getSolidFillColor--}
```
public abstract Integer getSolidFillColor()
```


رنگ پر کردن صلب را برمی‌گرداند. فقط قابل خواندن java.lang.Integer.

**بازگشت:**
java.lang.Integer
### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormatEffectiveData getGradientFormat()
```


قالب پر کردن گرادیان را برمی‌گرداند. فقط قابل خواندن [IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata).

**بازگشت:**
[IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata)
### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormatEffectiveData getPatternFormat()
```


قالب پر کردن الگو را برمی‌گرداند. فقط قابل خواندن [IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata).

**بازگشت:**
[IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract boolean getRotateWithShape()
```


تعیین می‌کند که آیا پر کردن باید با شکل چرخانده شود یا نه. فقط قابل خواندن boolean.

**بازگشت:**
boolean