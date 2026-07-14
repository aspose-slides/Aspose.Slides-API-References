---
title: IFillFormatEffectiveData
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: شیء غیرقابل تغییر که شامل ویژگی‌های قالب‌بندی پر کردن مؤثر است.
type: docs
url: /fa/com.aspose.slides/ifillformateffectivedata/
---
**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IFillFormatEffectiveData extends IFillParamSource
```

شیء غیرقابل تغییر که شامل ویژگی‌های قالب‌بندی پر کردن مؤثر است.

--------------------

این رابط به همراه رابط [IFillFormat](../../com.aspose.slides/ifillformat) برای بازگرداندن مقادیر قالب‌بندی مؤثر با اعمال ارث‌بری استفاده می‌شود.
## متدها

| متد | توضیح |
| --- | --- |
| [getFillType()](#getFillType--) | نوع پر کردن را برمی‌گرداند. |
| [getSolidFillColor()](#getSolidFillColor--) | رنگ پر کردن را برمی‌گرداند. |
| [getSolidFillSchemeColor()](#getSolidFillSchemeColor--) | رنگ پر کردن تعریف‌شده توسط یک طرح رنگ را دریافت می‌کند. |
| [getGradientFormat()](#getGradientFormat--) | قالب پر کردن گرادیان را برمی‌گرداند. |
| [getPatternFormat()](#getPatternFormat--) | قالب پر کردن الگو را برمی‌گرداند. |
| [getPictureFillFormat()](#getPictureFillFormat--) | قالب پر کردن تصویر را برمی‌گرداند. |
| [getRotateWithShape()](#getRotateWithShape--) | تشخیص می‌دهد که آیا پر کردن باید با شکل چرخانده شود یا نه. |
### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```


نوع پر کردن را برمی‌گرداند. فقط خواندنی [FillType](../../com.aspose.slides/filltype).

**بازگرداندن:**
byte
### getSolidFillColor() {#getSolidFillColor--}
```
public abstract Integer getSolidFillColor()
```


رنگ پر کردن را برمی‌گرداند. فقط خواندنی java.lang.Integer.

**بازگرداندن:**
java.lang.Integer
### getSolidFillSchemeColor() {#getSolidFillSchemeColor--}
```
public abstract int getSolidFillSchemeColor()
```


رنگ پر کردن تعریف‌شده توسط یک طرح رنگ را دریافت می‌کند. مقدار [SchemeColor.NotDefined](../../com.aspose.slides/schemecolor\#NotDefined) نشان می‌دهد که SolidFillColor (\#getSolidFillColor.getSolidFillColor) یک رنگ طرح نیست. فقط خواندنی [SchemeColor](../../com.aspose.slides/schemecolor).

**بازگرداندن:**
int
### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormatEffectiveData getGradientFormat()
```


قالب پر کردن گرادیان را برمی‌گرداند. فقط خواندنی [IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata).

**بازگرداندن:**
[IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata)
### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormatEffectiveData getPatternFormat()
```


قالب پر کردن الگو را برمی‌گرداند. فقط خواندنی [IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata).

**بازگرداندن:**
[IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata)
### getPictureFillFormat() {#getPictureFillFormat--}
```
public abstract IPictureFillFormatEffectiveData getPictureFillFormat()
```


قالب پر کردن تصویر را برمی‌گرداند. فقط خواندنی [IPictureFillFormatEffectiveData](../../com.aspose.slides/ipicturefillformateffectivedata).

**بازگرداندن:**
[IPictureFillFormatEffectiveData](../../com.aspose.slides/ipicturefillformateffectivedata)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract boolean getRotateWithShape()
```


تشخیص می‌دهد که آیا پر کردن باید با شکل چرخانده شود یا نه. فقط خواندنی boolean.

**بازگرداندن:**
boolean