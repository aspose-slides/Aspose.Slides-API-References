---
title: ColorFormat
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایانگر رنگی که در یک ارائه استفاده می‌شود.
type: docs
url: /fa/com.aspose.slides/colorformat/
---
**وراثت:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**تمام اینترفیس‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IColorFormat](../../com.aspose.slides/icolorformat)
```
public final class ColorFormat extends PVIObject implements IColorFormat
```

نمایانگر رنگی که در یک ارائه استفاده می‌شود.
## متدها

| متد | توضیح |
| --- | --- |
| [getColorType()](#getColorType--) | مقدار یا تنظیم متد تعریف رنگ. |
| [setColorType(int value)](#setColorType-int-) | مقدار یا تنظیم متد تعریف رنگ. |
| [getColor()](#getColor--) | رنگ حاصل را بر می‌گرداند (با تمام تبدیل‌های رنگ اعمال‌شده). |
| [setColor(Integer value)](#setColor-java.lang.Integer-) | رنگ حاصل را بر می‌گرداند (با تمام تبدیل‌های رنگ اعمال‌شده). |
| [getPresetColor()](#getPresetColor--) | مقدار یا تنظیم پیش‌تنظیم رنگ. |
| [setPresetColor(int value)](#setPresetColor-int-) | مقدار یا تنظیم پیش‌تنظیم رنگ. |
| [getSystemColor()](#getSystemColor--) | مقدار یا تنظیم رنگ شناسایی‌شده توسط جدول رنگ سیستم. |
| [setSystemColor(int value)](#setSystemColor-int-) | مقدار یا تنظیم رنگ شناسایی‌شده توسط جدول رنگ سیستم. |
| [getSchemeColor()](#getSchemeColor--) | مقدار یا تنظیم رنگ شناسایی‌شده توسط طرح رنگ. |
| [setSchemeColor(int value)](#setSchemeColor-int-) | مقدار یا تنظیم رنگ شناسایی‌شده توسط طرح رنگ. |
| [getR()](#getR--) | مقدار یا تنظیم مؤلفهٔ قرمز یک رنگ. |
| [setR(byte value)](#setR-byte-) | مقدار یا تنظیم مؤلفهٔ قرمز یک رنگ. |
| [getG()](#getG--) | مقدار یا تنظیم مؤلفهٔ سبز یک رنگ. |
| [setG(byte value)](#setG-byte-) | مقدار یا تنظیم مؤلفهٔ سبز یک رنگ. |
| [getB()](#getB--) | مقدار یا تنظیم مؤلفهٔ آبی یک رنگ. |
| [setB(byte value)](#setB-byte-) | مقدار یا تنظیم مؤلفهٔ آبی یک رنگ. |
| [getFloatR()](#getFloatR--) | مقدار یا تنظیم مؤلفهٔ قرمز یک رنگ. |
| [setFloatR(float value)](#setFloatR-float-) | مقدار یا تنظیم مؤلفهٔ قرمز یک رنگ. |
| [getFloatG()](#getFloatG--) | مقدار یا تنظیم مؤلفهٔ سبز یک رنگ. |
| [setFloatG(float value)](#setFloatG-float-) | مقدار یا تنظیم مؤلفهٔ سبز یک رنگ. |
| [getFloatB()](#getFloatB--) | مقدار یا تنظیم مؤلفهٔ آبی یک رنگ. |
| [setFloatB(float value)](#setFloatB-float-) | مقدار یا تنظیم مؤلفهٔ آبی یک رنگ. |
| [getHue()](#getHue--) | مقدار یا تنظیم مؤلفهٔ هیو (Hue) یک رنگ در نمایهٔ HSL. |
| [setHue(float value)](#setHue-float-) | مقدار یا تنظیم مؤلفهٔ هیو (Hue) یک رنگ در نمایهٔ HSL. |
| [getSaturation()](#getSaturation--) | مقدار یا تنظیم مؤلفهٔ اشباع (Saturation) یک رنگ در نمایهٔ HSL. |
| [setSaturation(float value)](#setSaturation-float-) | مقدار یا تنظیم مؤلفهٔ اشباع (Saturation) یک رنگ در نمایهٔ HSL. |
| [getLuminance()](#getLuminance--) | مقدار یا تنظیم مؤلفهٔ روشنایی (Luminance) یک رنگ در نمایهٔ HSL. |
| [setLuminance(float value)](#setLuminance-float-) | مقدار یا تنظیم مؤلفهٔ روشنایی (Luminance) یک رنگ در نمایهٔ HSL. |
| [getColorTransform()](#getColorTransform--) | مجموعهٔ تبدیل‌های رنگ اعمال‌شده بر یک رنگ را بر می‌گرداند. |
| [toString(int format)](#toString-int-) | یک String که نمایانگر قالب رنگ فعلی است را بر می‌گرداند. |
| [copyFrom(IColorFormat color)](#copyFrom-com.aspose.slides.IColorFormat-) | قالب رنگ را از "color" کپی می‌کند. |
| [equals(Object obj)](#equals-java.lang.Object-) | برابری با شیء مشخص‌شده را بررسی می‌کند. |
| [hashCode()](#hashCode--) | کد هش را بر می‌گرداند. |
| [getVersion()](#getVersion--) |  |
| [getParent_ISlideComponent()](#getParent-ISlideComponent--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |

### getColorType() {#getColorType--}
```
public final int getColorType()
```

مقدار یا تنظیم متد تعریف رنگ. خواندنی/نوشتنی [ColorType](../../com.aspose.slides/colortype).

**بازگشت:**
int

### setColorType(int value) {#setColorType-int-}
```
public final void setColorType(int value)
```

مقدار یا تنظیم متد تعریف رنگ. خواندنی/نوشتنی [ColorType](../../com.aspose.slides/colortype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getColor() {#getColor--}
```
public final Integer getColor()
```

رنگ حاصل را بر می‌گرداند (با تمام تبدیل‌های رنگ اعمال‌شده). تنظیم رنگ‌های RGB و پاک کردن همه تبدیل‌های رنگ. خواندنی/نوشتنی java.lang.Integer.

**بازگشت:**
java.lang.Integer

### setColor(Integer value) {#setColor-java.lang.Integer-}
```
public final void setColor(Integer value)
```

رنگ حاصل را بر می‌گرداند (با تمام تبدیل‌های رنگ اعمال‌شده). تنظیم رنگ‌های RGB و پاک کردن همه تبدیل‌های رنگ. خواندنی/نوشتنی java.lang.Integer.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.Integer |  |

### getPresetColor() {#getPresetColor--}
```
public final int getPresetColor()
```

مقدار یا تنظیم پیش‌تنظیم رنگ. خواندنی/نوشتنی [PresetColor](../../com.aspose.slides/presetcolor).

**بازگشت:**
int

### setPresetColor(int value) {#setPresetColor-int-}
```
public final void setPresetColor(int value)
```

مقدار یا تنظیم پیش‌تنظیم رنگ. خواندنی/نوشتنی [PresetColor](../../com.aspose.slides/presetcolor).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getSystemColor() {#getSystemColor--}
```
public final int getSystemColor()
```

مقدار یا تنظیم رنگ شناسایی‌شده توسط جدول رنگ سیستم. خواندنی/نوشتنی [SystemColor](../../com.aspose.slides/systemcolor).

**بازگشت:**
int

### setSystemColor(int value) {#setSystemColor-int-}
```
public final void setSystemColor(int value)
```

مقدار یا تنظیم رنگ شناسایی‌شده توسط جدول رنگ سیستم. خواندنی/نوشتنی [SystemColor](../../com.aspose.slides/systemcolor).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getSchemeColor() {#getSchemeColor--}
```
public final int getSchemeColor()
```

مقدار یا تنظیم رنگ شناسایی‌شده توسط طرح رنگ. خواندنی/نوشتنی [SchemeColor](../../com.aspose.slides/schemecolor).

**بازگشت:**
int

### setSchemeColor(int value) {#setSchemeColor-int-}
```
public final void setSchemeColor(int value)
```

مقدار یا تنظیم رنگ شناسایی‌شده توسط طرح رنگ. خواندنی/نوشتنی [SchemeColor](../../com.aspose.slides/schemecolor).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getR() {#getR--}
```
public final byte getR()
```

مقدار یا تنظیم مؤلفهٔ قرمز یک رنگ. همه تبدیل‌های رنگ نادیده گرفته می‌شوند. خواندنی/نوشتنی byte .

**بازگشت:**
byte

### setR(byte value) {#setR-byte-}
```
public final void setR(byte value)
```

مقدار یا تنظیم مؤلفهٔ قرمز یک رنگ. همه تبدیل‌های رنگ نادیده گرفته می‌شوند. خواندنی/نوشتنی byte .

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getG() {#getG--}
```
public final byte getG()
```

مقدار یا تنظیم مؤلفهٔ سبز یک رنگ. همه تبدیل‌های رنگ نادیده گرفته می‌شوند.

**بازگشت:**
byte

### setG(byte value) {#setG-byte-}
```
public final void setG(byte value)
```

مقدار یا تنظیم مؤلفهٔ سبز یک رنگ. همه تبدیل‌های رنگ نادیده گرفته می‌شوند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getB() {#getB--}
```
public final byte getB()
```

مقدار یا تنظیم مؤلفهٔ آبی یک رنگ. همه تبدیل‌های رنگ نادیده گرفته می‌شوند. خواندنی/نوشتنی byte .

**بازگشت:**
byte

### setB(byte value) {#setB-byte-}
```
public final void setB(byte value)
```

مقدار یا تنظیم مؤلفهٔ آبی یک رنگ. همه تبدیل‌های رنگ نادیده گرفته می‌شوند. خواندنی/نوشتنی byte .

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getFloatR() {#getFloatR--}
```
public final float getFloatR()
```

مقدار یا تنظیم مؤلفهٔ قرمز یک رنگ. همه تبدیل‌های رنگ نادیده گرفته می‌شوند. خواندنی/نوشتنی float .

**بازگشت:**
float

### setFloatR(float value) {#setFloatR-float-}
```
public final void setFloatR(float value)
```

مقدار یا تنظیم مؤلفهٔ قرمز یک رنگ. همه تبدیل‌های رنگ نادیده گرفته می‌شوند. خواندنی/نوشتنی float .

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### getFloatG() {#getFloatG--}
```
public final float getFloatG()
```

مقدار یا تنظیم مؤلفهٔ سبز یک رنگ. همه تبدیل‌های رنگ نادیده گرفته می‌شوند. خواندنی/نوشتنی float .

**بازگشت:**
float

### setFloatG(float value) {#setFloatG-float-}
```
public final void setFloatG(float value)
```

مقدار یا تنظیم مؤلفهٔ سبز یک رنگ. همه تبدیل‌های رنگ نادیده گرفته می‌شوند. خواندنی/نوشتنی float .

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### getFloatB() {#getFloatB--}
```
public final float getFloatB()
```

مقدار یا تنظیم مؤلفهٔ آبی یک رنگ. همه تبدیل‌های رنگ نادیده گرفته می‌شوند. خواندنی/نوشتنی float .

**بازگشت:**
float

### setFloatB(float value) {#setFloatB-float-}
```
public final void setFloatB(float value)
```

مقدار یا تنظیم مؤلفهٔ آبی یک رنگ. همه تبدیل‌های رنگ نادیده گرفته می‌شوند. خواندنی/نوشتنی float .

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### getHue() {#getHue--}
```
public final float getHue()
```

مقدار یا تنظیم مؤلفهٔ هیو (Hue) یک رنگ در نمایهٔ HSL. همه تبدیل‌های رنگ نادیده گرفته می‌شوند. خواندنی/نوشتنی float .

**بازگشت:**
float

### setHue(float value) {#setHue-float-}
```
public final void setHue(float value)
```

مقدار یا تنظیم مؤلفهٔ هیو (Hue) یک رنگ در نمایهٔ HSL. همه تبدیل‌های رنگ نادیده گرفته می‌شوند. خواندنی/نوشتنی float .

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### getSaturation() {#getSaturation--}
```
public final float getSaturation()
```

مقدار یا تنظیم مؤلفهٔ اشباع (Saturation) یک رنگ در نمایهٔ HSL. همه تبدیل‌های رنگ نادیده گرفته می‌شوند. خواندنی/نوشتنی float .

**بازگشت:**
float

### setSaturation(float value) {#setSaturation-float-}
```
public final void setSaturation(float value)
```

مقدار یا تنظیم مؤلفهٔ اشباع (Saturation) یک رنگ در نمایهٔ HSL. همه تبدیل‌های رنگ نادیده گرفته می‌شوند. خواندنی/نوشتنی float .

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### getLuminance() {#getLuminance--}
```
public final float getLuminance()
```

مقدار یا تنظیم مؤلفهٔ روشنایی (Luminance) یک رنگ در نمایهٔ HSL. همه تبدیل‌های رنگ نادیده گرفته می‌شوند. خواندنی/نوشتنی float .

**بازگشت:**
float

### setLuminance(float value) {#setLuminance-float-}
```
public final void setLuminance(float value)
```

مقدار یا تنظیم مؤلفهٔ روشنایی (Luminance) یک رنگ در نمایهٔ HSL. همه تبدیل‌های رنگ نادیده گرفته می‌شوند. خواندنی/نوشتنی float .

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### getColorTransform() {#getColorTransform--}
```
public final IColorOperationCollection getColorTransform()
```

مجموعهٔ تبدیل‌های رنگ اعمال‌شده بر یک رنگ را بر می‌گرداند. فقط‌خواندنی [IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection).

**بازگشت:**
[IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection)

### toString(int format) {#toString-int-}
```
public final String toString(int format)
```

یک String که نمایانگر قالب رنگ فعلی است را بر می‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| format | int | A type of color string format. |

**بازگشت:**
java.lang.String - A string that represents the current color format.

### copyFrom(IColorFormat color) {#copyFrom-com.aspose.slides.IColorFormat-}
```
public final void copyFrom(IColorFormat color)
```

قالب رنگ را از "color" کپی می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| color | [IColorFormat](../../com.aspose.slides/icolorformat) |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

برابری با شیء مشخص‌شده را بررسی می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| obj | java.lang.Object | Object. |

**بازگشت:**
boolean - True if objects are equal, otherwise false.

### hashCode() {#hashCode--}
```
public int hashCode()
```

کد هش را بر می‌گرداند.

**بازگشت:**
int - Hash code.

### getVersion() {#getVersion--}
```
public long getVersion()
```

نسخه. فقط‌خواندنی long.

**بازگشت:**
long

### getParent_ISlideComponent() {#getParent-ISlideComponent--}
```
public final ISlideComponent getParent_ISlideComponent()
```

**بازگشت:**
[ISlideComponent](../../com.aspose.slides/islidecomponent)

### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

والد IPresentationComponent را بر می‌گرداند. فقط‌خواندنی [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**بازگشت:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)