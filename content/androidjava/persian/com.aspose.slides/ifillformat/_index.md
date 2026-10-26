---
title: IFillFormat
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایانگر گزینه‌های قالب‌بندی پر کردن است.
type: docs
url: /fa/com.aspose.slides/ifillformat/
---
**تمام اینترفیس‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IFillFormat extends IFillParamSource
```

نمایانگر گزینه‌های قالب‌بندی پر کردن است.
## متدها

| متد | توضیح |
| --- | --- |
| [getFillType()](#getFillType--) | مقدار یا تنظیم نوع پر کردن. |
| [setFillType(byte value)](#setFillType-byte-) | مقدار یا تنظیم نوع پر کردن. |
| [getSolidFillColor()](#getSolidFillColor--) | رنگ پر کردن را برمی‌گرداند. |
| [getGradientFormat()](#getGradientFormat--) | قالب گرادیان پر کردن را برمی‌گرداند. |
| [getPatternFormat()](#getPatternFormat--) | قالب الگوی پر کردن را برمی‌گرداند. |
| [getPictureFillFormat()](#getPictureFillFormat--) | قالب تصویر پر کردن را برمی‌گرداند. |
| [getRotateWithShape()](#getRotateWithShape--) | تشخیص می‌دهد که آیا پر کردن باید با شکل چرخانده شود یا نه. |
| [setRotateWithShape(byte value)](#setRotateWithShape-byte-) | تشخیص می‌دهد که آیا پر کردن باید با شکل چرخانده شود یا نه. |
| [getEffective()](#getEffective--) | داده‌های مؤثر قالب‌بندی پر کردن را با اعمال ارث‌بری دریافت می‌کند. |
### getFillType() {#getFillType--}
```
public abstract byte getFillType()
```

مقدار یا تنظیم نوع پر کردن. خواندنی/نوشتنی [FillType](../../com.aspose.slides/filltype).

**بازگشت:**
byte
### setFillType(byte value) {#setFillType-byte-}
```
public abstract void setFillType(byte value)
```

مقدار یا تنظیم نوع پر کردن. خواندنی/نوشتنی [FillType](../../com.aspose.slides/filltype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |
### getSolidFillColor() {#getSolidFillColor--}
```
public abstract IColorFormat getSolidFillColor()
```

رنگ پر کردن را برمی‌گرداند. فقط‌خواندنی [IColorFormat](../../com.aspose.slides/icolorformat).

**بازگشت:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormat getGradientFormat()
```

قالب گرادیان پر کردن را برمی‌گرداند. فقط‌خواندنی [IGradientFormat](../../com.aspose.slides/igradientformat).

**بازگشت:**
[IGradientFormat](../../com.aspose.slides/igradientformat)
### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormat getPatternFormat()
```

قالب الگوی پر کردن را برمی‌گرداند. فقط‌خواندنی [IPatternFormat](../../com.aspose.slides/ipatternformat).

**بازگشت:**
[IPatternFormat](../../com.aspose.slides/ipatternformat)
### getPictureFillFormat() {#getPictureFillFormat--}
```
public abstract IPictureFillFormat getPictureFillFormat()
```

قالب تصویر پر کردن را برمی‌گرداند. فقط‌خواندنی [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**بازگشت:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract byte getRotateWithShape()
```

تشخیص می‌دهد که آیا پر کردن باید با شکل چرخانده شود یا نه. خواندنی/نوشتنی [NullableBool](../../com.aspose.slides/nullablebool).

**بازگشت:**
byte
### setRotateWithShape(byte value) {#setRotateWithShape-byte-}
```
public abstract void setRotateWithShape(byte value)
```

تشخیص می‌دهد که آیا پر کردن باید با شکل چرخانده شود یا نه. خواندنی/نوشتنی [NullableBool](../../com.aspose.slides/nullablebool).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |
### getEffective() {#getEffective--}
```
public abstract IFillFormatEffectiveData getEffective()
```

داده‌های مؤثر قالب‌بندی پر کردن را با اعمال ارث‌بری دریافت می‌کند.

**بازگشت:**
[IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) - A [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata).