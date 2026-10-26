---
title: IColorFormat
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایشگر رنگی که در یک ارائه استفاده می‌شود.
type: docs
url: /fa/com.aspose.slides/icolorformat/
---
**تمام رابط‌های پیاده‌سازی شده:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IColorFormat extends IFillParamSource
```

یک رنگ را که در یک ارائه استفاده می‌شود، نمایش می‌دهد.
## متدها

| متد | توضیح |
| --- | --- |
| [getColorType()](#getColorType--) | مقدار بازگردانده یا تنظیم می‌کند روش تعریف رنگ. |
| [setColorType(int value)](#setColorType-int-) | مقدار بازگردانده یا تنظیم می‌کند روش تعریف رنگ. |
| [getColor()](#getColor--) | مقدار بازگردانده می‌کند رنگ نتیجه‌گیری (با تمام تبدیلات رنگی اعمال‌شده). |
| [setColor(Integer value)](#setColor-java.lang.Integer-) | مقدار بازگردانده می‌کند رنگ نتیجه‌گیری (با تمام تبدیلات رنگی اعمال‌شده). |
| [getPresetColor()](#getPresetColor--) | مقدار بازگردانده یا تنظیم می‌کند پیش‌تنظیم رنگ. |
| [setPresetColor(int value)](#setPresetColor-int-) | مقدار بازگردانده یا تنظیم می‌کند پیش‌تنظیم رنگ. |
| [getSystemColor()](#getSystemColor--) | مقدار بازگردانده یا تنظیم می‌کند رنگ شناسایی‌شده توسط جدول رنگ‌های سیستم. |
| [setSystemColor(int value)](#setSystemColor-int-) | مقدار بازگردانده یا تنظیم می‌کند رنگ شناسایی‌شده توسط جدول رنگ‌های سیستم. |
| [getSchemeColor()](#getSchemeColor--) | مقدار بازگردانده یا تنظیم می‌کند رنگ شناسایی‌شده توسط طرح رنگ. |
| [setSchemeColor(int value)](#setSchemeColor-int-) | مقدار بازگردانده یا تنظیم می‌کند رنگ شناسایی‌شده توسط طرح رنگ. |
| [getR()](#getR--) | مقدار بازگردانده یا تنظیم می‌کند مؤلفهٔ قرمز رنگ. |
| [setR(byte value)](#setR-byte-) | مقدار بازگردانده یا تنظیم می‌کند مؤلفهٔ قرمز رنگ. |
| [getG()](#getG--) | مقدار بازگردانده یا تنظیم می‌کند مؤلفهٔ سبز رنگ. |
| [setG(byte value)](#setG-byte-) | مقدار بازگردانده یا تنظیم می‌کند مؤلفهٔ سبز رنگ. |
| [getB()](#getB--) | مقدار بازگردانده یا تنظیم می‌کند مؤلفهٔ آبی رنگ. |
| [setB(byte value)](#setB-byte-) | مقدار بازگردانده یا تنظیم می‌کند مؤلفهٔ آبی رنگ. |
| [getFloatR()](#getFloatR--) | مقدار بازگردانده یا تنظیم می‌کند مؤلفهٔ قرمز رنگ. |
| [setFloatR(float value)](#setFloatR-float-) | مقدار بازگردانده یا تنظیم می‌کند مؤلفهٔ قرمز رنگ. |
| [getFloatG()](#getFloatG--) | مقدار بازگردانده یا تنظیم می‌کند مؤلفهٔ سبز رنگ. |
| [setFloatG(float value)](#setFloatG-float-) | مقدار بازگردانده یا تنظیم می‌کند مؤلفهٔ سبز رنگ. |
| [getFloatB()](#getFloatB--) | مقدار بازگردانده یا تنظیم می‌کند مؤلفهٔ آبی رنگ. |
| [setFloatB(float value)](#setFloatB-float-) | مقدار بازگردانده یا تنظیم می‌کند مؤلفهٔ آبی رنگ. |
| [getHue()](#getHue--) | مقدار بازگردانده یا تنظیم می‌کند مؤلفهٔ هیو رنگ در نمایش HSL. |
| [setHue(float value)](#setHue-float-) | مقدار بازگردانده یا تنظیم می‌کند مؤلفهٔ هیو رنگ در نمایش HSL. |
| [getSaturation()](#getSaturation--) | مقدار بازگردانده یا تنظیم می‌کند مؤلفهٔ اشباع رنگ در نمایش HSL. |
| [setSaturation(float value)](#setSaturation-float-) | مقدار بازگردانده یا تنظیم می‌کند مؤلفهٔ اشباع رنگ در نمایش HSL. |
| [getLuminance()](#getLuminance--) | مقدار بازگردانده یا تنظیم می‌کند مؤلفهٔ روشنایی رنگ در نمایش HSL. |
| [setLuminance(float value)](#setLuminance-float-) | مقدار بازگردانده یا تنظیم می‌کند مؤلفهٔ روشنایی رنگ در نمایش HSL. |
| [getColorTransform()](#getColorTransform--) | مجموعهٔ تبدیلات رنگی اعمال‌شده به یک رنگ را بازمی‌گرداند. |
| [toString(int format)](#toString-int-) | رشته‌ای که قالب رنگ فعلی را نشان می‌دهد، بازمی‌گرداند. |
| [copyFrom(IColorFormat color)](#copyFrom-com.aspose.slides.IColorFormat-) | قالب رنگ را از «color» کپی می‌کند. |
### getColorType() {#getColorType--}
```
public abstract int getColorType()
```

بازگردانده یا تنظیم می‌کند روش تعریف رنگ. خواندن/نوشتن [ColorType](../../com.aspose.slides/colortype).

**بازگشت:**
int
### setColorType(int value) {#setColorType-int-}
```
public abstract void setColorType(int value)
```

بازگردانده یا تنظیم می‌کند روش تعریف رنگ. خواندن/نوشتن [ColorType](../../com.aspose.slides/colortype).

**پارامترها:**
| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| value | int |  |

### getColor() {#getColor--}
```
public abstract Integer getColor()
```

بازگردانده می‌کند رنگ نتیجه‌گیری (با تمام تبدیلات رنگی اعمال‌شده). رنگ‌های RGB را تنظیم می‌کند و تمام تبدیلات رنگی را پاک می‌سازد. خواندن/نوشتن java.lang.Integer.

**بازگشت:**
java.lang.Integer
### setColor(Integer value) {#setColor-java.lang.Integer-}
```
public abstract void setColor(Integer value)
```

بازگردانده می‌کند رنگ نتیجه‌گیری (با تمام تبدیلات رنگی اعمال‌شده). رنگ‌های RGB را تنظیم می‌کند و تمام تبدیلات رنگی را پاک می‌سازد. خواندن/نوشتن java.lang.Integer.

**پارامترها:**
| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| value | java.lang.Integer |  |

### getPresetColor() {#getPresetColor--}
```
public abstract int getPresetColor()
```

بازگردانده یا تنظیم می‌کند پیش‌تنظیم رنگ. خواندن/نوشتن [PresetColor](../../com.aspose.slides/presetcolor).

**بازگشت:**
int
### setPresetColor(int value) {#setPresetColor-int-}
```
public abstract void setPresetColor(int value)
```

بازگردانده یا تنظیم می‌کند پیش‌تنظیم رنگ. خواندن/نوشتن [PresetColor](../../com.aspose.slides/presetcolor).

**پارامترها:**
| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| value | int |  |

### getSystemColor() {#getSystemColor--}
```
public abstract int getSystemColor()
```

بازگردانده یا تنظیم می‌کند رنگ شناسایی‌شده توسط جدول رنگ‌های سیستم. خواندن/نوشتن [SystemColor](../../com.aspose.slides/systemcolor).

**بازگشت:**
int
### setSystemColor(int value) {#setSystemColor-int-}
```
public abstract void setSystemColor(int value)
```

بازگردانده یا تنظیم می‌کند رنگ شناسایی‌شده توسط جدول رنگ‌های سیستم. خواندن/نوشتن [SystemColor](../../com.aspose.slides/systemcolor).

**پارامترها:**
| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| value | int |  |

### getSchemeColor() {#getSchemeColor--}
```
public abstract int getSchemeColor()
```

بازگردانده یا تنظیم می‌کند رنگ شناسایی‌شده توسط یک طرح رنگ. خواندن/نوشتن [SchemeColor](../../com.aspose.slides/schemecolor).

**بازگشت:**
int
### setSchemeColor(int value) {#setSchemeColor-int-}
```
public abstract void setSchemeColor(int value)
```

بازگردانده یا تنظیم می‌کند رنگ شناسایی‌شده توسط یک طرح رنگ. خواندن/نوشتن [SchemeColor](../../com.aspose.slides/schemecolor).

**پارامترها:**
| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| value | int |  |

### getR() {#getR--}
```
public abstract byte getR()
```

بازگردانده یا تنظیم می‌کند مؤلفهٔ قرمز رنگ. تمام تبدیلات رنگی نادیده گرفته می‌شوند. خواندن/نوشتن byte.

**بازگشت:**
byte
### setR(byte value) {#setR-byte-}
```
public abstract void setR(byte value)
```

بازگردانده یا تنظیم می‌کند مؤلفهٔ قرمز رنگ. تمام تبدیلات رنگی نادیده گرفته می‌شوند. خواندن/نوشتن byte.

**پارامترها:**
| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| value | byte |  |

### getG() {#getG--}
```
public abstract byte getG()
```

بازگردانده یا تنظیم می‌کند مؤلفهٔ سبز رنگ. تمام تبدیلات رنگی نادیده گرفته می‌شوند. خواندن/نوشتن byte.

**بازگشت:**
byte
### setG(byte value) {#setG-byte-}
```
public abstract void setG(byte value)
```

بازگردانده یا تنظیم می‌کند مؤلفهٔ سبز رنگ. تمام تبدیلات رنگی نادیده گرفته می‌شوند. خواندن/نوشتن byte.

**پارامترها:**
| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| value | byte |  |

### getB() {#getB--}
```
public abstract byte getB()
```

بازگردانده یا تنظیم می‌کند مؤلفهٔ آبی رنگ. تمام تبدیلات رنگی نادیده گرفته می‌شوند. خواندن/نوشتن byte.

**بازگشت:**
byte
### setB(byte value) {#setB-byte-}
```
public abstract void setB(byte value)
```

بازگردانده یا تنظیم می‌کند مؤلفهٔ آبی رنگ. تمام تبدیلات رنگی نادیده گرفته می‌شوند. خواندن/نوشتن byte.

**پارامترها:**
| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| value | byte |  |

### getFloatR() {#getFloatR--}
```
public abstract float getFloatR()
```

بازگردانده یا تنظیم می‌کند مؤلفهٔ قرمز رنگ. تمام تبدیلات رنگی نادیده گرفته می‌شوند. خواندن/نوشتن float.

**بازگشت:**
float
### setFloatR(float value) {#setFloatR-float-}
```
public abstract void setFloatR(float value)
```

بازگردانده یا تنظیم می‌کند مؤلفهٔ قرمز رنگ. تمام تبدیلات رنگی نادیده گرفته می‌شوند. خواندن/نوشتن float.

**پارامترها:**
| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| value | float |  |

### getFloatG() {#getFloatG--}
```
public abstract float getFloatG()
```

بازگردانده یا تنظیم می‌کند مؤلفهٔ سبز رنگ. تمام تبدیلات رنگی نادیده گرفته می‌شوند. خواندن/نوشتن float.

**بازگشت:**
float
### setFloatG(float value) {#setFloatG-float-}
```
public abstract void setFloatG(float value)
```

بازگردانده یا تنظیم می‌کند مؤلفهٔ سبز رنگ. تمام تبدیلات رنگی نادیده گرفته می‌شوند. خواندن/نوشتن float.

**پارامترها:**
| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| value | float |  |

### getFloatB() {#getFloatB--}
```
public abstract float getFloatB()
```

بازگردانده یا تنظیم می‌کند مؤلفهٔ آبی رنگ. تمام تبدیلات رنگی نادیده گرفته می‌شوند. خواندن/نوشتن float.

**بازگشت:**
float
### setFloatB(float value) {#setFloatB-float-}
```
public abstract void setFloatB(float value)
```

بازگردانده یا تنظیم می‌کند مؤلفهٔ آبی رنگ. تمام تبدیلات رنگی نادیده گرفته می‌شوند. خواندن/نوشتن float.

**پارامترها:**
| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| value | float |  |

### getHue() {#getHue--}
```
public abstract float getHue()
```

بازگردانده یا تنظیم می‌کند مؤلفهٔ هیو رنگ در نمایش HSL. تمام تبدیلات رنگی نادیده گرفته می‌شوند. خواندن/نوشتن float.

**بازگشت:**
float
### setHue(float value) {#setHue-float-}
```
public abstract void setHue(float value)
```

بازگردانده یا تنظیم می‌کند مؤلفهٔ هیو رنگ در نمایش HSL. تمام تبدیلات رنگی نادیده گرفته می‌شوند. خواندن/نوشتن float.

**پارامترها:**
| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| value | float |  |

### getSaturation() {#getSaturation--}
```
public abstract float getSaturation()
```

بازگردانده یا تنظیم می‌کند مؤلفهٔ اشباع رنگ در نمایش HSL. تمام تبدیلات رنگی نادیده گرفته می‌شوند. خواندن/نوشتن float.

**بازگشت:**
float
### setSaturation(float value) {#setSaturation-float-}
```
public abstract void setSaturation(float value)
```

بازگردانده یا تنظیم می‌کند مؤلفهٔ اشباع رنگ در نمایش HSL. تمام تبدیلات رنگی نادیده گرفته می‌شوند. خواندن/نوشتن float.

**پارامترها:**
| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| value | float |  |

### getLuminance() {#getLuminance--}
```
public abstract float getLuminance()
```

بازگردانده یا تنظیم می‌کند مؤلفهٔ روشنایی رنگ در نمایش HSL. تمام تبدیلات رنگی نادیده گرفته می‌شوند. خواندن/نوشتن float.

**بازگشت:**
float
### setLuminance(float value) {#setLuminance-float-}
```
public abstract void setLuminance(float value)
```

بازگردانده یا تنظیم می‌کند مؤلفهٔ روشنایی رنگ در نمایش HSL. تمام تبدیلات رنگی نادیده گرفته می‌شوند. خواندن/نوشتن float.

**پارامترها:**
| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| value | float |  |

### getColorTransform() {#getColorTransform--}
```
public abstract IColorOperationCollection getColorTransform()
```

مجموعهٔ تبدیلات رنگی اعمال‌شده به یک رنگ را بازمی‌گرداند. فقط-خواندنی [IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection).

**بازگشت:**
[IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection)
### toString(int format) {#toString-int-}
```
public abstract String toString(int format)
```

رشته‌ای که قالب رنگ فعلی را نشان می‌دهد را بازمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| format | int | نوع قالب رشته رنگ. |

**بازگشت:**
java.lang.String - رشته‌ای که قالب رنگ فعلی را نشان می‌دهد.
### copyFrom(IColorFormat color) {#copyFrom-com.aspose.slides.IColorFormat-}
```
public abstract void copyFrom(IColorFormat color)
```

قالب رنگ را از "color" کپی می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| color | [IColorFormat](../../com.aspose.slides/icolorformat) | رنگ [IColorFormat](../../com.aspose.slides/icolorformat) |