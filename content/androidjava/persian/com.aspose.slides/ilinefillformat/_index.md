---
title: ILineFillFormat
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: ویژگی‌های پر کردن خطوط را نمایندگی می‌کند.
type: docs
url: /fa/com.aspose.slides/ilinefillformat/
---
**تمام رابط‌های پیاده‌سازی شده:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface ILineFillFormat extends IFillParamSource
```

خواص پر کردن خطوط را نمایندگی می‌کند.
## متدها

| متد | توضیح |
| --- | --- |
| [getFillType()](#getFillType--) | مقدار یا تنظیم نوع پر. |
| [setFillType(byte value)](#setFillType-byte-) | مقدار یا تنظیم نوع پر. |
| [getSolidFillColor()](#getSolidFillColor--) | رنگ پر کردن ثابت را برمی‌گرداند. |
| [getGradientFormat()](#getGradientFormat--) | قالب پر کردن گرادیان را برمی‌گرداند. |
| [getPatternFormat()](#getPatternFormat--) | قالب پر کردن الگو را برمی‌گرداند. |
| [getRotateWithShape()](#getRotateWithShape--) | مشخص می‌کند که آیا پر کردن باید همراه با شکل چرخانده شود یا نه. |
| [setRotateWithShape(byte value)](#setRotateWithShape-byte-) | مشخص می‌کند که آیا پر کردن باید همراه با شکل چرخانده شود یا نه. |
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


رنگ پر کردن ثابت را برمی‌گرداند. فقط‌خواندنی [IColorFormat](../../com.aspose.slides/icolorformat).

**بازگشت:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getGradientFormat() {#getGradientFormat--}
```
public abstract IGradientFormat getGradientFormat()
```


قالب پر کردن گرادیان را برمی‌گرداند. فقط‌خواندنی [IGradientFormat](../../com.aspose.slides/igradientformat).

**بازگشت:**
[IGradientFormat](../../com.aspose.slides/igradientformat)
### getPatternFormat() {#getPatternFormat--}
```
public abstract IPatternFormat getPatternFormat()
```


قالب پر کردن الگو را برمی‌گرداند. فقط‌خواندنی [IPatternFormat](../../com.aspose.slides/ipatternformat).

**بازگشت:**
[IPatternFormat](../../com.aspose.slides/ipatternformat)
### getRotateWithShape() {#getRotateWithShape--}
```
public abstract byte getRotateWithShape()
```


مشخص می‌کند که آیا پر کردن باید همراه با شکل چرخانده شود یا نه. خواندنی/نوشتنی [NullableBool](../../com.aspose.slides/nullablebool).

**بازگشت:**
byte
### setRotateWithShape(byte value) {#setRotateWithShape-byte-}
```
public abstract void setRotateWithShape(byte value)
```


مشخص می‌کند که آیا پر کردن باید همراه با شکل چرخانده شود یا نه. خواندنی/نوشتنی [NullableBool](../../com.aspose.slides/nullablebool).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |