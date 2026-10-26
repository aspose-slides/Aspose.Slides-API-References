---
title: IFillFormat
second_title: Aspose.Slides برای مرجع API جاوا
description: نمایانگر گزینه‌های قالب‌بندی پر است.
type: docs
url: /fa/com.aspose.slides/ifillformat/
---
**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IFillFormat extends IFillParamSource
```

نمایانگر گزینه‌های قالب‌بندی پر.

## متدها

| متد | توضیح |
| --- | --- |
| [getFillType()](#getFillType--) | مقدار یا تنظیم نوع پر. |
| [setFillType(byte value)](#setFillType-byte-) | مقدار یا تنظیم نوع پر. |
| [getSolidFillColor()](#getSolidFillColor--) | رنگ پر را باز می‌گرداند. |
| [getGradientFormat()](#getGradientFormat--) | قالب پرش گرادیان را باز می‌گرداند. |
| [getPatternFormat()](#getPatternFormat--) | قالب پرش الگو را باز می‌گرداند. |
| [getPictureFillFormat()](#getPictureFillFormat--) | قالب پرش تصویر را باز می‌گرداند. |
| [getRotateWithShape()](#getRotateWithShape--) | تعیین می‌کند که آیا پرش باید با شکل چرخانده شود یا نه. |
| [setRotateWithShape(byte value)](#setRotateWithShape-byte-) | تعیین می‌کند که آیا پرش باید با شکل چرخانده شود یا نه. |
| [getEffective()](#getEffective--) | داده‌های قالب‌بندی مؤثر پرش با اعمال ارث‌بری را دریافت می‌کند. |
### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```

مقدار یا تنظیم نوع پر. خواندنی/نوشتنی [FillType](../../com.aspose.slides/filltype).

**بازگشت:**
byte
### setFillType(byte value) {#setFillType-byte-}
```
public abstract void setFillType(byte value)
```

مقدار یا تنظیم نوع پر. خواندنی/نوشتنی [FillType](../../com.aspose.slides/filltype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |
### getSolidFillColor() {#getSolidFillColor--}
```
public abstract IColorFormat getSolidFillColor()
```

رنگ پر را باز می‌گرداند. فقط خواندنی [IColorFormat](../../com.aspose.slides/icolorformat).

**بازگشت:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormat getGradientFormat()
```

قالب پرش گرادیان را باز می‌گرداند. فقط خواندنی [IGradientFormat](../../com.aspose.slides/igradientformat).

**بازگشت:**
[IGradientFormat](../../com.aspose.slides/igradientformat)
### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormat getPatternFormat()
```

قالب پرش الگو را باز می‌گرداند. فقط خواندنی [IPatternFormat](../../com.aspose.slides/ipatternformat).

**بازگشت:**
[IPatternFormat](../../com.aspose.slides/ipatternformat)
### getPictureFillFormat() {#getPictureFillFormat--}
```
public abstract IPictureFillFormat getPictureFillFormat()
```

قالب پرش تصویر را باز می‌گرداند. فقط خواندنی [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**بازگشت:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract byte getRotateWithShape()
```

تعیین می‌کند که آیا پرش باید با شکل چرخانده شود یا نه. خواندنی/نوشتنی [NullableBool](../../com.aspose.slides/nullablebool).

**بازگشت:**
byte
### setRotateWithShape(byte value) {#setRotateWithShape-byte-}
```
public abstract void setRotateWithShape(byte value)
```

تعیین می‌کند که آیا پرش باید با شکل چرخانده شود یا نه. خواندنی/نوشتنی [NullableBool](../../com.aspose.slides/nullablebool).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |
### getEffective() {#getEffective--}
```
public abstract IFillFormatEffectiveData getEffective()
```

داده‌های قالب‌بندی مؤثر پرش با اعمال ارث‌بری را دریافت می‌کند.

**بازگشت:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) - یک [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).