---
title: ILightRig
second_title: Aspose.Slides for Java API Reference
description: Represents LightRig.
type: docs
url: /fa/com.aspose.slides/ilightrig/
---```
public interface ILightRig
```

نمایانگر LightRig است.
## روش‌ها

| متد | توضیح |
| --- | --- |
| [getDirection()](#getDirection--) | جهت نور. |
| [setDirection(int value)](#setDirection-int-) | جهت نور. |
| [getLightType()](#getLightType--) | نمایانگر یک نور پیش‌تنظیم شده به سمت راست که می‌تواند به یک شکل اعمال شود. |
| [setLightType(int value)](#setLightType-int-) | نمایانگر یک نور پیش‌تنظیم شده به سمت راست که می‌تواند به یک شکل اعمال شود. |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | یک چرخش از طریق استفاده از مختصات عرض، مختصات طول و یک دور حول محور به عنوان مختصات عرض و طول تعریف می‌شود. |
| [getRotation()](#getRotation--) | یک چرخش از طریق استفاده از مختصات عرض، مختصات طول و یک دور حول محور به عنوان مختصات عرض و طول تعریف می‌شود. |
### getDirection() {#getDirection--}
```
public abstract int getDirection()
```

جهت نور. خواندنی/نوشتنی [LightingDirection](../../com.aspose.slides/lightingdirection).

**بازگشت:**
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

نمایانگر یک نور پیش‌تنظیم شده به سمت راست که می‌تواند به یک شکل اعمال شود. light rig نمایانگر یک گروه از نورهاست که به‌صورت خاصی نسبت به یک صحنهٔ 3 بعدی جهت‌گیری می‌کنند. خواندنی/نوشتنی [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**بازگشت:**
int
### setLightType(int value) {#setLightType-int-}
```
public abstract void setLightType(int value)
```

نمایانگر یک نور پیش‌تنظیم شده به سمت راست که می‌تواند به یک شکل اعمال شود. light rig نمایانگر یک گروه از نورهاست که به‌صورت خاصی نسبت به یک صحنهٔ 3 بعدی جهت‌گیری می‌کنند. خواندنی/نوشتنی [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public abstract void setRotation(float latitude, float longitude, float revolution)
```

یک چرخش از طریق استفاده از مختصات عرض، مختصات طول و یک دور حول محور به عنوان مختصات عرض و طول تعریف می‌شود.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| latitude | float | مختصات عرض (float) |
| longitude | float | مختصات طول (float) |
| revolution | float | مختصات دور (float) |

### getRotation() {#getRotation--}
```
public abstract float[] getRotation()
```

یک چرخش از طریق استفاده از مختصات عرض، مختصات طول و یک دور حول محور به عنوان مختصات عرض و طول تعریف می‌شود. اولین عنصر در آرایهٔ بازگشتی - عرض، دوم - طول، سوم - دور.

**بازگشت:**
float[] - مختصات چرخش به صورت float[]