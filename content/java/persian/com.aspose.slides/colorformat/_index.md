---
title: ColorFormat
second_title: Aspose.Slides برای مرجع API جاوا
description: نمایشگر رنگی است که در یک ارائه استفاده می‌شود.
type: docs
url: /fa/com.aspose.slides/colorformat/
---
**ارث‌بری:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**تمام رابط‌های پیاده‌سازی شده:**
[com.aspose.slides.IColorFormat](../../com.aspose.slides/icolorformat)
```
public final class ColorFormat extends PVIObject implements IColorFormat
```

نمایشگر رنگی است که در یک ارائه استفاده می‌شود.
## متدها

| متد | توضیح |
| --- | --- |
| [getColorType()](#getColorType--) | متد تعریف رنگ را برمی‌گرداند یا تنظیم می‌کند. |
| [setColorType(int value)](#setColorType-int-) | متد تعریف رنگ را برمی‌گرداند یا تنظیم می‌کند. |
| [getColor()](#getColor--) | رنگ حاصل را برمی‌گرداند (با تمام تبدیل‌های رنگی اعمال شده). |
| [setColor(Color value)](#setColor-java.awt.Color-) | رنگ حاصل را برمی‌گرداند (با تمام تبدیل‌های رنگی اعمال شده). |
| [getPresetColor()](#getPresetColor--) | پیش‌تنظیم رنگ را برمی‌گرداند یا تنظیم می‌کند. |
| [setPresetColor(int value)](#setPresetColor-int-) | پیش‌تنظیم رنگ را برمی‌گرداند یا تنظیم می‌کند. |
| [getSystemColor()](#getSystemColor--) | رنگ شناخته‌شده توسط جدول رنگ سیستم را برمی‌گرداند یا تنظیم می‌کند. |
| [setSystemColor(int value)](#setSystemColor-int-) | رنگ شناخته‌شده توسط جدول رنگ سیستم را برمی‌گرداند یا تنظیم می‌کند. |
| [getSchemeColor()](#getSchemeColor--) | رنگ شناخته‌شده توسط طرح رنگ را برمی‌گرداند یا تنظیم می‌کند. |
| [setSchemeColor(int value)](#setSchemeColor-int-) | رنگ شناخته‌شده توسط طرح رنگ را برمی‌گرداند یا تنظیم می‌کند. |
| [getR()](#getR--) | مؤلفه قرمز یک رنگ را برمی‌گرداند یا تنظیم می‌کند. |
| [setR(byte value)](#setR-byte-) | مؤلفه قرمز یک رنگ را برمی‌گرداند یا تنظیم می‌کند. |
| [getG()](#getG--) | مؤلفه سبز یک رنگ را برمی‌گرداند یا تنظیم می‌کند. |
| [setG(byte value)](#setG-byte-) | مؤلفه سبز یک رنگ را برمی‌گرداند یا تنظیم می‌کند. |
| [getB()](#getB--) | مؤلفه آبی یک رنگ را برمی‌گرداند یا تنظیم می‌کند. |
| [setB(byte value)](#setB-byte-) | مؤلفه آبی یک رنگ را برمی‌گرداند یا تنظیم می‌کند. |
| [getFloatR()](#getFloatR--) | مؤلفه قرمز یک رنگ را برمی‌گرداند یا تنظیم می‌کند. |
| [setFloatR(float value)](#setFloatR-float-) | مؤلفه قرمز یک رنگ را برمی‌گرداند یا تنظیم می‌کند. |
| [getFloatG()](#getFloatG--) | مؤلفه سبز یک رنگ را برمی‌گرداند یا تنظیم می‌کند. |
| [setFloatG(float value)](#setFloatG-float-) | مؤلفه سبز یک رنگ را برمی‌گرداند یا تنظیم می‌کند. |
| [getFloatB()](#getFloatB--) | مؤلفه آبی یک رنگ را برمی‌گرداند یا تنظیم می‌کند. |
| [setFloatB(float value)](#setFloatB-float-) | مؤلفه آبی یک رنگ را برمی‌گرداند یا تنظیم می‌کند. |
| [getHue()](#getHue--) | مؤلفه hue یک رنگ در نمایش HSL را برمی‌گرداند یا تنظیم می‌کند. |
| [setHue(float value)](#setHue-float-) | مؤلفه hue یک رنگ در نمایش HSL را برمی‌گرداند یا تنظیم می‌کند. |
| [getSaturation()](#getSaturation--) | مؤلفه اشباع یک رنگ در نمایش HSL را برمی‌گرداند یا تنظیم می‌کند. |
| [setSaturation(float value)](#setSaturation-float-) | مؤلفه اشباع یک رنگ در نمایش HSL را برمی‌گرداند یا تنظیم می‌کند. |
| [getLuminance()](#getLuminance--) | مؤلفه روشنایی یک رنگ در نمایش HSL را برمی‌گرداند یا تنظیم می‌کند. |
| [setLuminance(float value)](#setLuminance-float-) | مؤلفه روشنایی یک رنگ در نمایش HSL را برمی‌گرداند یا تنظیم می‌کند. |
| [getColorTransform()](#getColorTransform--) | مجموعه تبدیل‌های رنگی اعمال‌شده بر یک رنگ را برمی‌گرداند. |
| [toString(int format)](#toString-int-) | رشته‌ای که فرمت فعلی رنگ را نشان می‌دهد برمی‌گرداند. |
| [copyFrom(IColorFormat color)](#copyFrom-com.aspose.slides.IColorFormat-) | فرمت رنگ را از «color» کپی می‌کند. |
| [equals(Object obj)](#equals-java.lang.Object-) | برابری را با شیء مشخص شده بررسی می‌کند. |
| [hashCode()](#hashCode--) | مقدار هش را برمی‌گرداند. |
| [getVersion()](#getVersion--) |  |
| [getParent_ISlideComponent()](#getParent-ISlideComponent--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |

### getColorType() {#getColorType--}
```
public final int getColorType()
```

متد تعریف رنگ را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن [ColorType](../../com.aspose.slides/colortype).

**باز می‌گردد:**
int

### setColorType(int value) {#setColorType-int-}
```
public final void setColorType(int value)
```

متد تعریف رنگ را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن [ColorType](../../com.aspose.slides/colortype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getColor() {#getColor--}
```
public final Color getColor()
```

رنگ حاصل را برمی‌گرداند (با تمام تبدیل‌های رنگی اعمال شده). رنگ‌های RGB را تنظیم می‌کند و تمام تبدیل‌های رنگی را پاک می‌کند. خواندن/نوشتن java.awt.Color.

**باز می‌گردد:**
java.awt.Color

### setColor(Color value) {#setColor-java.awt.Color-}
```
public final void setColor(Color value)
```

رنگ حاصل را برمی‌گرداند (با تمام تبدیل‌های رنگی اعمال شده). رنگ‌های RGB را تنظیم می‌کند و تمام تبدیل‌های رنگی را پاک می‌کند. خواندن/نوشتن java.awt.Color.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.awt.Color |  |

### getPresetColor() {#getPresetColor--}
```
public final int getPresetColor()
```

پیش‌تنظیم رنگ را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن [PresetColor](../../com.aspose.slides/presetcolor).

**باز می‌گردد:**
int

### setPresetColor(int value) {#setPresetColor-int-}
```
public final void setPresetColor(int value)
```

پیش‌تنظیم رنگ را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن [PresetColor](../../com.aspose.slides/presetcolor).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getSystemColor() {#getSystemColor--}
```
public final int getSystemColor()
```

رنگ شناخته‌شده توسط جدول رنگ سیستم را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن [SystemColor](../../com.aspose.slides/systemcolor).

**باز می‌گردد:**
int

### setSystemColor(int value) {#setSystemColor-int-}
```
public final void setSystemColor(int value)
```

رنگ شناخته‌شده توسط جدول رنگ سیستم را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن [SystemColor](../../com.aspose.slides/systemcolor).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getSchemeColor() {#getSchemeColor--}
```
public final int getSchemeColor()
```

رنگ شناخته‌شده توسط طرح رنگ را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن [SchemeColor](../../com.aspose.slides/schemecolor).

**باز می‌گردد:**
int

### setSchemeColor(int value) {#setSchemeColor-int-}
```
public final void setSchemeColor(int value)
```

رنگ شناخته‌شده توسط طرح رنگ را برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن [SchemeColor](../../com.aspose.slides/schemecolor).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getR() {#getR--}
```
public final byte getR()
```

مؤلفه قرمز یک رنگ را برمی‌گرداند یا تنظیم می‌کند. تمام تبدیل‌های رنگی نادیده گرفته می‌شوند. خواندن/نوشتن  byte .

**باز می‌گردد:**
byte

### setR(byte value) {#setR-byte-}
```
public final void setR(byte value)
```

مؤلفه قرمز یک رنگ را برمی‌گرداند یا تنظیم می‌کند. تمام تبدیل‌های رنگی نادیده گرفته می‌شوند. خواندن/نوشتن  byte .

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getG() {#getG--}
```
public final byte getG()
```

مؤلفه سبز یک رنگ را برمی‌گرداند یا تنظیم می‌کند. تمام تبدیل‌های رنگی نادیده گرفته می‌شوند.

**باز می‌گردد:**
byte

### setG(byte value) {#setG-byte-}
```
public final void setG(byte value)
```

مؤلفه سبز یک رنگ را برمی‌گرداند یا تنظیم می‌کند. تمام تبدیل‌های رنگی نادیده گرفته می‌شوند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getB() {#getB--}
```
public final byte getB()
```

مؤلفه آبی یک رنگ را برمی‌گرداند یا تنظیم می‌کند. تمام تبدیل‌های رنگی نادیده گرفته می‌شوند. خواندن/نوشتن  byte .

**باز می‌گردد:**
byte

### setB(byte value) {#setB-byte-}
```
public final void setB(byte value)
```

مؤلفه آبی یک رنگ را برمی‌گرداند یا تنظیم می‌کند. تمام تبدیل‌های رنگی نادیده گرفته می‌شوند. خواندن/نوشتن  byte .

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getFloatR() {#getFloatR--}
```
public final float getFloatR()
```

مؤلفه قرمز یک رنگ را برمی‌گرداند یا تنظیم می‌کند. تمام تبدیل‌های رنگی نادیده گرفته می‌شوند. خواندن/نوشتن  float .

**باز می‌گردد:**
float

### setFloatR(float value) {#setFloatR-float-}
```
public final void setFloatR(float value)
```

مؤلفه قرمز یک رنگ را برمی‌گرداند یا تنظیم می‌کند. تمام تبدیل‌های رنگی نادیده گرفته می‌شوند. خواندن/نوشتن  float .

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### getFloatG() {#getFloatG--}
```
public final float getFloatG()
```

مؤلفه سبز یک رنگ را برمی‌گرداند یا تنظیم می‌کند. تمام تبدیل‌های رنگی نادیده گرفته می‌شوند. خواندن/نوشتن  float .

**باز می‌گردد:**
float

### setFloatG(float value) {#setFloatG-float-}
```
public final void setFloatG(float value)
```

مؤلفه سبز یک رنگ را برمی‌گرداند یا تنظیم می‌کند. تمام تبدیل‌های رنگی نادیده گرفته می‌شوند. خواندن/نوشتن  float .

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### getFloatB() {#getFloatB--}
```
public final float getFloatB()
```

مؤلفه آبی یک رنگ را برمی‌گرداند یا تنظیم می‌کند. تمام تبدیل‌های رنگی نادیده گرفته می‌شوند. خواندن/نوشتن  float .

**باز می‌گردد:**
float

### setFloatB(float value) {#setFloatB-float-}
```
public final void setFloatB(float value)
```

مؤلفه آبی یک رنگ را برمی‌گرداند یا تنظیم می‌کند. تمام تبدیل‌های رنگی نادیده گرفته می‌شوند. خواندن/نوشتن  float .

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### getHue() {#getHue--}
```
public final float getHue()
```

مؤلفه hue یک رنگ در نمایش HSL را برمی‌گرداند یا تنظیم می‌کند. تمام تبدیل‌های رنگی نادیده گرفته می‌شوند. خواندن/نوشتن  float .

**باز می‌گردد:**
float

### setHue(float value) {#setHue-float-}
```
public final void setHue(float value)
```

مؤلفه hue یک رنگ در نمایش HSL را برمی‌گرداند یا تنظیم می‌کند. تمام تبدیل‌های رنگی نادیده گرفته می‌شوند. خواندن/نوشتن  float .

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### getSaturation() {#getSaturation--}
```
public final float getSaturation()
```

مؤلفه اشباع یک رنگ در نمایش HSL را برمی‌گرداند یا تنظیم می‌کند. تمام تبدیل‌های رنگی نادیده گرفته می‌شوند. خواندن/نوشتن  float .

**باز می‌گردد:**
float

### setSaturation(float value) {#setSaturation-float-}
```
public final void setSaturation(float value)
```

مؤلفه اشباع یک رنگ در نمایش HSL را برمی‌گرداند یا تنظیم می‌کند. تمام تبدیل‌های رنگی نادیده گرفته می‌شوند. خواندن/نوشتن  float .

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### getLuminance() {#getLuminance--}
```
public final float getLuminance()
```

مؤلفه روشنایی یک رنگ در نمایش HSL را برمی‌گرداند یا تنظیم می‌کند. تمام تبدیل‌های رنگی نادیده گرفته می‌شوند. خواندن/نوشتن  float .

**باز می‌گردد:**
float

### setLuminance(float value) {#setLuminance-float-}
```
public final void setLuminance(float value)
```

مؤلفه روشنایی یک رنگ در نمایش HSL را برمی‌گرداند یا تنظیم می‌کند. تمام تبدیل‌های رنگی نادیده گرفته می‌شوند. خواندن/نوشتن  float .

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### getColorTransform() {#getColorTransform--}
```
public final IColorOperationCollection getColorTransform()
```

مجموعه تبدیل‌های رنگی اعمال‌شده بر یک رنگ را برمی‌گرداند. فقط خواندنی [IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection).

**باز می‌گردد:**
[IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection)

### toString(int format) {#toString-int-}
```
public final String toString(int format)
```

رشته‌ای که فرمت فعلی رنگ را نشان می‌دهد برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| format | int | نوع فرمت رشته رنگ. |

**باز می‌گردد:**
java.lang.String - رشته‌ای که فرمت فعلی رنگ را نشان می‌دهد.

### copyFrom(IColorFormat color) {#copyFrom-com.aspose.slides.IColorFormat-}
```
public final void copyFrom(IColorFormat color)
```

فرمت رنگ را از «color» کپی می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| color | [IColorFormat](../../com.aspose.slides/icolorformat) |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

برابری را با شیء مشخص شده بررسی می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| obj | java.lang.Object | شیء. |

**باز می‌گردد:**
boolean - true اگر اشیاء برابر باشند، در غیر این صورت false.

### hashCode() {#hashCode--}
```
public int hashCode()
```

مقدار هش را برمی‌گرداند.

**باز می‌گردد:**
int - مقدار هش.

### getVersion() {#getVersion--}
```
public long getVersion()
```

نسخه. فقط خواندنی long.

**باز می‌گردد:**
long

### getParent_ISlideComponent() {#getParent-ISlideComponent--}
```
public final ISlideComponent getParent_ISlideComponent()
```

**باز می‌گردد:**
[ISlideComponent](../../com.aspose.slides/islidecomponent)

### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

والد IPresentationComponent را برمی‌گرداند. فقط خواندنی [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**باز می‌گردد:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)