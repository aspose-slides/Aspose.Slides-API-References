---
title: IColorFormat
second_title: مرجع API Aspose.Slides برای Java
description: نمایانگر رنگی است که در یک ارائه استفاده می‌شود.
type: docs
url: /fa/com.aspose.slides/icolorformat/
---
**تمام رابط‌های پیاده‌سازی شده:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IColorFormat extends IFillParamSource
```

نمایانگر رنگی است که در یک ارائه استفاده می‌شود.
## روش‌ها

| متد | توضیح |
| --- | --- |
| [getColorType()](#getColorType--) | مقداردهی یا دریافت روش تعریف رنگ. |
| [setColorType(int value)](#setColorType-int-) | مقداردهی یا دریافت روش تعریف رنگ. |
| [getColor()](#getColor--) | رنگ حاصل را برمی‌گرداند (با تمام تبدیلات رنگی اعمال‌شده). |
| [setColor(Color value)](#setColor-java.awt.Color-) | رنگ حاصل را برمی‌گرداند (با تمام تبدیلات رنگی اعمال‌شده). |
| [getPresetColor()](#getPresetColor--) | مقداردهی یا دریافت پیش‌تنظیم رنگ. |
| [setPresetColor(int value)](#setPresetColor-int-) | مقداردهی یا دریافت پیش‌تنظیم رنگ. |
| [getSystemColor()](#getSystemColor--) | مقداردهی یا دریافت رنگ شناسایی‌شده توسط جدول رنگ‌های سیستم. |
| [setSystemColor(int value)](#setSystemColor-int-) | مقداردهی یا دریافت رنگ شناسایی‌شده توسط جدول رنگ‌های سیستم. |
| [getSchemeColor()](#getSchemeColor--) | مقداردهی یا دریافت رنگ شناسایی‌شده توسط یک طرح رنگ. |
| [setSchemeColor(int value)](#setSchemeColor-int-) | مقداردهی یا دریافت رنگ شناسایی‌شده توسط یک طرح رنگ. |
| [getR()](#getR--) | مقداردهی یا دریافت مؤلفهٔ قرمز یک رنگ. |
| [setR(byte value)](#setR-byte-) | مقداردهی یا دریافت مؤلفهٔ قرمز یک رنگ. |
| [getG()](#getG--) | مقداردهی یا دریافت مؤلفهٔ سبز یک رنگ. |
| [setG(byte value)](#setG-byte-) | مقداردهی یا دریافت مؤلفهٔ سبز یک رنگ. |
| [getB()](#getB--) | مقداردهی یا دریافت مؤلفهٔ آبی یک رنگ. |
| [setB(byte value)](#setB-byte-) | مقداردهی یا دریافت مؤلفهٔ آبی یک رنگ. |
| [getFloatR()](#getFloatR--) | مقداردهی یا دریافت مؤلفهٔ قرمز یک رنگ. |
| [setFloatR(float value)](#setFloatR-float-) | مقداردهی یا دریافت مؤلفهٔ قرمز یک رنگ. |
| [getFloatG()](#getFloatG--) | مقداردهی یا دریافت مؤلفهٔ سبز یک رنگ. |
| [setFloatG(float value)](#setFloatG-float-) | مقداردهی یا دریافت مؤلفهٔ سبز یک رنگ. |
| [getFloatB()](#getFloatB--) | مقداردهی یا دریافت مؤلفهٔ آبی یک رنگ. |
| [setFloatB(float value)](#setFloatB-float-) | مقداردهی یا دریافت مؤلفهٔ آبی یک رنگ. |
| [getHue()](#getHue--) | مقداردهی یا دریافت مؤلفهٔ هیو یک رنگ در نمایش HSL. |
| [setHue(float value)](#setHue-float-) | مقداردهی یا دریافت مؤلفهٔ هیو یک رنگ در نمایش HSL. |
| [getSaturation()](#getSaturation--) | مقداردهی یا دریافت مؤلفهٔ اشباع یک رنگ در نمایش HSL. |
| [setSaturation(float value)](#setSaturation-float-) | مقداردهی یا دریافت مؤلفهٔ اشباع یک رنگ در نمایش HSL. |
| [getLuminance()](#getLuminance--) | مقداردهی یا دریافت مؤلفهٔ روشنایی یک رنگ در نمایش HSL. |
| [setLuminance(float value)](#setLuminance-float-) | مقداردهی یا دریافت مؤلفهٔ روشنایی یک رنگ در نمایش HSL. |
| [getColorTransform()](#getColorTransform--) | مجموعهٔ تبدیلات رنگی اعمال‌شده بر یک رنگ را برمی‌گرداند. |
| [toString(int format)](#toString-int-) | یک String که نمایانگر قالب رنگ فعلی است را برمی‌گرداند. |
| [copyFrom(IColorFormat color)](#copyFrom-com.aspose.slides.IColorFormat-) | قالب رنگ را از "color" کپی می‌کند. |
### getColorType() {#getColorType--}
```
public abstract int getColorType()
```

مقداردهی یا دریافت روش تعریف رنگ. خواندن/نوشتن [ColorType](../../com.aspose.slides/colortype).

**بازگشت:**
int
### setColorType(int value) {#setColorType-int-}
```
public abstract void setColorType(int value)
```

مقداردهی یا دریافت روش تعریف رنگ. خواندن/نوشتن [ColorType](../../com.aspose.slides/colortype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |
### getColor() {#getColor--}
```
public abstract Color getColor()
```

رنگ حاصل را برمی‌گرداند (با تمام تبدیلات رنگی اعمال‌شده). رنگ‌های RGB تنظیم می‌شود و تمام تبدیلات رنگی پاک می‌شوند. خواندن/نوشتن java.awt.Color.

**بازگشت:**
java.awt.Color
### setColor(Color value) {#setColor-java.awt.Color-}
```
public abstract void setColor(Color value)
```

رنگ حاصل را برمی‌گرداند (با تمام تبدیلات رنگی اعمال‌شده). رنگ‌های RGB تنظیم می‌شود و تمام تبدیلات رنگی پاک می‌شوند. خواندن/نوشتن java.awt.Color.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.awt.Color |  |
### getPresetColor() {#getPresetColor--}
```
public abstract int getPresetColor()
```

مقداردهی یا دریافت پیش‌تنظیم رنگ. خواندن/نوشتن [PresetColor](../../com.aspose.slides/presetcolor).

**بازگشت:**
int
### setPresetColor(int value) {#setPresetColor-int-}
```
public abstract void setPresetColor(int value)
```

مقداردهی یا دریافت پیش‌تنظیم رنگ. خواندن/نوشتن [PresetColor](../../com.aspose.slides/presetcolor).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |
### getSystemColor() {#getSystemColor--}
```
public abstract int getSystemColor()
```

مقداردهی یا دریافت رنگ شناسایی‌شده توسط جدول رنگ‌های سیستم. خواندن/نوشتن [SystemColor](../../com.aspose.slides/systemcolor).

**بازگشت:**
int
### setSystemColor(int value) {#setSystemColor-int-}
```
public abstract void setSystemColor(int value)
```

مقداردهی یا دریافت رنگ شناسایی‌شده توسط جدول رنگ‌های سیستم. خواندن/نوشتن [SystemColor](../../com.aspose.slides/systemcolor).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |
### getSchemeColor() {#getSchemeColor--}
```
public abstract int getSchemeColor()
```

مقداردهی یا دریافت رنگ شناسایی‌شده توسط یک طرح رنگ. خواندن/نوشتن [SchemeColor](../../com.aspose.slides/schemecolor).

**بازگشت:**
int
### setSchemeColor(int value) {#setSchemeColor-int-}
```
public abstract void setSchemeColor(int value)
```

مقداردهی یا دریافت رنگ شناسایی‌شده توسط یک طرح رنگ. خواندن/نوشتن [SchemeColor](../../com.aspose.slides/schemecolor).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |
### getR() {#getR--}
```
public abstract byte getR()
```

مقداردهی یا دریافت مؤلفهٔ قرمز یک رنگ. تمام تبدیلات رنگی نادیده گرفته می‌شوند. خواندن/نوشتن byte.

**بازگشت:**
byte
### setR(byte value) {#setR-byte-}
```
public abstract void setR(byte value)
```

مقداردهی یا دریافت مؤلفهٔ قرمز یک رنگ. تمام تبدیلات رنگی نادیده گرفته می‌شوند. خواندن/نوشتن byte.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |
### getG() {#getG--}
```
public abstract byte getG()
```

مقداردهی یا دریافت مؤلفهٔ سبز یک رنگ. تمام تبدیلات رنگی نادیده گرفته می‌شوند. خواندن/نوشتن byte.

**بازگشت:**
byte
### setG(byte value) {#setG-byte-}
```
public abstract void setG(byte value)
```

مقداردهی یا دریافت مؤلفهٔ سبز یک رنگ. تمام تبدیلات رنگی نادیده گرفته می‌شوند. خواندن/نوشتن byte.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |
### getB() {#getB--}
```
public abstract byte getB()
```

مقداردهی یا دریافت مؤلفهٔ آبی یک رنگ. تمام تبدیلات رنگی نادیده گرفته می‌شوند. خواندن/نوشتن byte.

**بازگشت:**
byte
### setB(byte value) {#setB-byte-}
```
public abstract void setB(byte value)
```

مقداردهی یا دریافت مؤلفهٔ آبی یک رنگ. تمام تبدیلات رنگی نادیده گرفته می‌شوند. خواندن/نوشتن byte.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |
### getFloatR() {#getFloatR--}
```
public abstract float getFloatR()
```

مقداردهی یا دریافت مؤلفهٔ قرمز یک رنگ. تمام تبدیلات رنگی نادیده گرفته می‌شوند. خواندن/نوشتن float.

**بازگشت:**
float
### setFloatR(float value) {#setFloatR-float-}
```
public abstract void setFloatR(float value)
```

مقداردهی یا دریافت مؤلفهٔ قرمز یک رنگ. تمام تبدیلات رنگی نادیده گرفته می‌شوند. خواندن/نوشتن float.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |
### getFloatG() {#getFloatG--}
```
public abstract float getFloatG()
```

مقداردهی یا دریافت مؤلفهٔ سبز یک رنگ. تمام تبدیلات رنگی نادیده گرفته می‌شوند. خواندن/نوشتن float.

**بازگشت:**
float
### setFloatG(float value) {#setFloatG-float-}
```
public abstract void setFloatG(float value)
```

مقداردهی یا دریافت مؤلفهٔ سبز یک رنگ. تمام تبدیلات رنگی نادیده گرفته می‌شوند. خواندن/نوشتن float.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |
### getFloatB() {#getFloatB--}
```
public abstract float getFloatB()
```

مقداردهی یا دریافت مؤلفهٔ آبی یک رنگ. تمام تبدیلات رنگی نادیده گرفته می‌شوند. خواندن/نوشتن float.

**بازگشت:**
float
### setFloatB(float value) {#setFloatB-float-}
```
public abstract void setFloatB(float value)
```

مقداردهی یا دریافت مؤلفهٔ آبی یک رنگ. تمام تبدیلات رنگی نادیده گرفته می‌شوند. خواندن/نوشتن float.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |
### getHue() {#getHue--}
```
public abstract float getHue()
```

مقداردهی یا دریافت مؤلفهٔ هیو یک رنگ در نمایش HSL. تمام تبدیلات رنگی نادیده گرفته می‌شوند. خواندن/نوشتن float.

**بازگشت:**
float
### setHue(float value) {#setHue-float-}
```
public abstract void setHue(float value)
```

مقداردهی یا دریافت مؤلفهٔ هیو یک رنگ در نمایش HSL. تمام تبدیلات رنگی نادیده گرفته می‌شوند. خواندن/نوشتن float.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |
### getSaturation() {#getSaturation--}
```
public abstract float getSaturation()
```

مقداردهی یا دریافت مؤلفهٔ اشباع یک رنگ در نمایش HSL. تمام تبدیلات رنگی نادیده گرفته می‌شوند. خواندن/نوشتن float.

**بازگشت:**
float
### setSaturation(float value) {#setSaturation-float-}
```
public abstract void setSaturation(float value)
```

مقداردهی یا دریافت مؤلفهٔ اشباع یک رنگ در نمایش HSL. تمام تبدیلات رنگی نادیده گرفته می‌شوند. خواندن/نوشتن float.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |
### getLuminance() {#getLuminance--}
```
public abstract float getLuminance()
```

مقداردهی یا دریافت مؤلفهٔ روشنایی یک رنگ در نمایش HSL. تمام تبدیلات رنگی نادیده گرفته می‌شوند. خواندن/نوشتن float.

**بازگشت:**
float
### setLuminance(float value) {#setLuminance-float-}
```
public abstract void setLuminance(float value)
```

مقداردهی یا دریافت مؤلفهٔ روشنایی یک رنگ در نمایش HSL. تمام تبدیلات رنگی نادیده گرفته می‌شوند. خواندن/نوشتن float.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |
### getColorTransform() {#getColorTransform--}
```
public abstract IColorOperationCollection getColorTransform()
```

مجموعهٔ تبدیلات رنگی اعمال‌شده بر یک رنگ را برمی‌گرداند. فقط-خواندنی [IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection).

**بازگشت:**
[IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection)
### toString(int format) {#toString-int-}
```
public abstract String toString(int format)
```

یک String که نمایانگر قالب رنگ فعلی است را برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| format | int | نوع قالب رشتهٔ رنگ. |

**بازگشت:**
java.lang.String - رشته‌ای که نمایانگر قالب رنگ فعلی است.
### copyFrom(IColorFormat color) {#copyFrom-com.aspose.slides.IColorFormat-}
```
public abstract void copyFrom(IColorFormat color)
```

قالب رنگ را از "color" کپی می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| color | [IColorFormat](../../com.aspose.slides/icolorformat) | Color [IColorFormat](../../com.aspose.slides/icolorformat) |