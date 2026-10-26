---
title: ILineFillFormatEffectiveData
second_title: مرجع API Aspose.Slides برای جاوا
description: شیء غیرقابل تغییر که ویژگی‌های پر کردن خط مؤثر را شامل می‌شود.
type: docs
url: /fa/com.aspose.slides/ilinefillformateffectivedata/
---
**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface ILineFillFormatEffectiveData extends IFillParamSource
```

شیء غیرقابل تغییر که ویژگی‌های پر کردن خط مؤثر را شامل می‌شود.

--------------------

این رابط به عنوان بخشی از [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata) استفاده می‌شود.
## متدها

| Method | Description |
| --- | --- |
| [getFillType()](#getFillType--) | نوع پر کردن را برمی‌گرداند. |
| [getSolidFillColor()](#getSolidFillColor--) | رنگ پر کردن یک‌پوش را برمی‌گرداند. |
| [getGradientFormat()](#getGradientFormat--) | قالب پر کردن گرادیان را برمی‌گرداند. |
| [getPatternFormat()](#getPatternFormat--) | قالب پر کردن الگو را برمی‌گرداند. |
| [getRotateWithShape()](#getRotateWithShape--) | تعیین می‌کند آیا پر کردن باید با شکل چرخانده شود یا خیر. |
### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```


نوع پر کردن را برمی‌گرداند. فقط خواندنی [FillType](../../com.aspose.slides/filltype).

**برگشت:**  
byte
### getSolidFillColor() {#getSolidFillColor--}
```
public abstract Color getSolidFillColor()
```


رنگ پر کردن یک‌پوش را برمی‌گرداند. فقط خواندنی java.awt.Color.

**برگشت:**  
java.awt.Color
### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormatEffectiveData getGradientFormat()
```


قالب پر کردن گرادیان را برمی‌گرداند. فقط خواندنی [IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata).

**برگشت:**  
[IGradientFormatEffectiveData](../../com.aspose.slides/igradientformateffectivedata)
### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormatEffectiveData getPatternFormat()
```


قالب پر کردن الگو را برمی‌گرداند. فقط خواندنی [IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata).

**برگشت:**  
[IPatternFormatEffectiveData](../../com.aspose.slides/ipatternformateffectivedata)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract boolean getRotateWithShape()
```


تعیین می‌کند آیا پر کردن باید با شکل چرخانده شود یا خیر. فقط خواندنی boolean.

**برگشت:**  
boolean