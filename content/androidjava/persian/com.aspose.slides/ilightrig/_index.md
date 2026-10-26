---
title: ILightRig
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایگر LightRig است.
type: docs
url: /fa/com.aspose.slides/ilightrig/
---```
public interface ILightRig
```

نمایش LightRig است.
## Methods

| متد | توضیح |
| --- | --- |
| [getDirection()](#getDirection--) | جهت نور. |
| [setDirection(int value)](#setDirection-int-) | جهت نور. |
| [getLightType()](#getLightType--) | نمایانگر یک نور پیش‌تنظیم سمت راست است که می‌تواند به یک شکل اعمال شود. |
| [setLightType(int value)](#setLightType-int-) | نمایانگر یک نور پیش‌تنظیم سمت راست است که می‌تواند به یک شکل اعمال شود. |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | چرخش از طریق استفاده از مختصات عرض، مختصات طول، و یک گردش حول محور به عنوان مختصات عرض و طول تعریف می‌شود. |
| [getRotation()](#getRotation--) | چرخش از طریق استفاده از مختصات عرض، مختصات طول، و یک گردش حول محور به عنوان مختصات عرض و طول تعریف می‌شود. |
### getDirection() {#getDirection--}
```
public abstract int getDirection()
```

جهت نور. خواندنی/نوشتنی [LightingDirection](../../com.aspose.slides/lightingdirection).

**بازگرداندن:**
int
### setDirection(int value) {#setDirection-int-}
```
public abstract void setDirection(int value)
```

جهت نور. خواندنی/نوشتنی [LightingDirection](../../com.aspose.slides/lightingdirection).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getLightType() {#getLightType--}
```
public abstract int getLightType()
```

نمایانگر یک نور پیش‌تنظیم سمت راست است که می‌تواند به یک شکل اعمال شود. Light rig نمایانگر یک گروه از نورها است که به‌طرز خاصی نسبت به صحنهٔ 3D جهت‌دار شده‌اند. خواندنی/نوشتنی [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**بازگرداندن:**
int
### setLightType(int value) {#setLightType-int-}
```
public abstract void setLightType(int value)
```

نمایانگر یک نور پیش‌تنظیم سمت راست است که می‌تواند به یک شکل اعمال شود. Light rig نمایانگر یک گروه از نورها است که به‌طرز خاصی نسبت به صحنهٔ 3D جهت‌دار شده‌اند. خواندنی/نوشتنی [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public abstract void setRotation(float latitude, float longitude, float revolution)
```

چرخش از طریق استفاده از مختصات عرض، مختصات طول، و یک گردش حول محور به عنوان مختصات عرض و طول تعریف می‌شود.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| latitude | float | مختصات عرض (float) |
| longitude | float | مختصات طول (float) |
| revolution | float | مختصات گردش (float) |

### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```

چرخش از طریق استفاده از مختصات عرض، مختصات طول، و یک گردش حول محور به عنوان مختصات عرض و طول تعریف می‌شود. اولین عنصر در آرایهٔ بازگشتی - عرض، دومین - طول، سومین - گردش.

**بازگرداندن:**
float[] - مختصات چرخش به صورت float[]