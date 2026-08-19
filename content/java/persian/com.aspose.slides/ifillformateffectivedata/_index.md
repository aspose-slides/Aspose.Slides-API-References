---
title: IFillFormatEffectiveData
second_title: Aspose.Slides برای جاوا - مرجع API
description: شیء غیرقابل تغییر که شامل ویژگی‌های قالب‌بندی پر کردن مؤثر است.
type: docs
url: /fa/com.aspose.slides/ifillformateffectivedata/
---
**تمام رابط‌های پیاده‌سازی شده:**  
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IFillFormatEffectiveData extends IFillParamSource
```

شیء غیرقابل تغییر که شامل ویژگی‌های قالب‌بندی پر کردن مؤثر است.

--------------------

این رابط همراه با رابط [IFillFormat](../../com.aspose.slides/ifillformat) برای بازگرداندن مقادیر قالب‌بندی مؤثر با اعمال وراثت استفاده می‌شود.
## متدها

| متد | توضیحات |
| --- | --- |
| [getFillType()](#getFillType--) | نوع پر کردن را بازمی‌گرداند. |
| [getSolidFillColor()](#getSolidFillColor--) | رنگ پر کردن را بازمی‌گرداند. |
| [getSolidFillSchemeColor()](#getSolidFillSchemeColor--) | رنگ پر کردن تعریف‌شده توسط طرح رنگ را دریافت می‌کند. |
| [getGradientFormat()](#getGradientFormat--) | قالب پر کردن گرادیان را بازمی‌گرداند. |
| [getPatternFormat()](#getPatternFormat--) | قالب پر کردن الگو را بازمی‌گرداند. |
| [getPictureFillFormat()](#getPictureFillFormat--) | قالب پر کردن تصویر را بازمی‌گرداند. |
| [getRotateWithShape()](#getRotateWithShape--) | تعیین می‌کند آیا پر کردن باید با شکل چرخانده شود یا خیر. |
### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```

نوع پر کردن را بازمی‌گرداند. فقط-خواندنی [FillType](../../com.aspose.slides/filltype).

**بازگشت:**  
byte
### getSolidFillColor() {#getSolidFillColor--}
```
public abstract Color getSolidFillColor()
```

رنگ پر کردن را بازمی‌گرداند. فقط-خواندنی java.awt.Color.

**بازگشت:**  
java.awt.Color
### getSolidFillSchemeColor() {#getSolidFillSchemeColor--}
```
public abstract int getSolidFillSchemeColor()
```

رنگ پر کردن تعریف‌شده توسط طرح رنگ را دریافت می‌کند. مقدار [SchemeColor.NotDefined](../../com.aspose.slides/schemecolor\#NotDefined) نشان می‌دهد که SolidFillColor (\#getSolidFillColor.getSolidFillColor) یک رنگ طرح نیست. فقط-خواندنی [SchemeColor](../../com.aspose.slides/schemecolor).

**بازگشت:**  
int
### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormatEffectiveData getGradientFormat()
```

قالب پر کردن گرادیان را بازمی‌گرداند. فقط-خواندنی [IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata).

**بازگشت:**  
[IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata)
### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormatEffectiveData getPatternFormat()
```

قالب پر کردن الگو را بازمی‌گرداند. فقط-خواندنی [IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata).

**بازگشت:**  
[IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata)
### getPictureFillFormat() {#getPictureFillFormat--}
```
public abstract IPictureFillFormatEffectiveData getPictureFillFormat()
```

قالب پر کردن تصویر را بازمی‌گرداند. فقط-خواندنی [IPictureFillFormatEffectiveData](../../com.aspose.slides/ipicturefillformateffectivedata).

**بازگشت:**  
[IPictureFillFormatEffectiveData](../../com.aspose.slides/ipicturefillformateffectivedata)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract boolean getRotateWithShape()
```

تعیین می‌کند آیا پر کردن باید با شکل چرخانده شود یا خیر. فقط-خواندنی boolean.

**بازگشت:**  
boolean