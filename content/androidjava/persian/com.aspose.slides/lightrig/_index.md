---
title: LightRig
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایانگر LightRig است.
type: docs
url: /fa/com.aspose.slides/lightrig/
---
**ارث‌بری:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**تمام اینترفیس‌های پیاده‌سازی‌شده:**
[com.aspose.slides.ILightRig](../../com.aspose.slides/ilightrig)
```
public final class LightRig extends PVIObject implements ILightRig
```

نمایانگر LightRig است.
## متدها

| متد | توضیح |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getDirection()](#getDirection--) | جهت نور. |
| [setDirection(int value)](#setDirection-int-) | جهت نور. |
| [getLightType()](#getLightType--) | نمایانگر یک پیش‌تنظیم نور راست است که می‌تواند به یک شکل اعمال شود. |
| [setLightType(int value)](#setLightType-int-) | نمایانگر یک پیش‌تنظیم نور راست است که می‌تواند به یک شکل اعمال شود. |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | چرخش از طریق استفاده از مختصات عرض، مختصات طول و یک دور حول محور به عنوان مختصات عرض و طول تعریف می‌شود. |
| [getRotation()](#getRotation--) | چرخش از طریق استفاده از مختصات عرض، مختصات طول و یک دور حول محور به عنوان مختصات عرض و طول تعریف می‌شود. |
### getVersion() {#getVersion--}
```
public long getVersion()
```


نسخه. فقط-خواندنی long.

**برگشت:**
long
### getDirection() {#getDirection--}
```
public final int getDirection()
```


جهت نور. خواندن/نوشتن [LightingDirection](../../com.aspose.slides/lightingdirection).

**برگشت:**
int
### setDirection(int value) {#setDirection-int-}
```
public final void setDirection(int value)
```


جهت نور. خواندن/نوشتن [LightingDirection](../../com.aspose.slides/lightingdirection).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getLightType() {#getLightType--}
```
public final int getLightType()
```


نمایانگر یک پیش‌تنظیم نور راست است که می‌تواند به یک شکل اعمال شود. LightRig نمایانگر گروهی از نورهاست که به شیوه‌ای خاص نسبت به صحنهٔ 3D جهت‌دار شده‌اند. خواندن/نوشتن [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**برگشت:**
int
### setLightType(int value) {#setLightType-int-}
```
public final void setLightType(int value)
```


نمایانگر یک پیش‌تنظیم نور راست است که می‌تواند به یک شکل اعمال شود. LightRig نمایانگر گروهی از نورهاست که به شیوه‌ای خاص نسبت به صحنهٔ 3D جهت‌دار شده‌اند. خواندن/نوشتن [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public final void setRotation(float latitude, float longitude, float revolution)
```


چرخش از طریق استفاده از مختصات عرض، مختصات طول و یک دور حول محور به عنوان مختصات عرض و طول تعریف می‌شود. اگر هر یک از مقادیر مختصات Float.NaN باشد، تمام چرخش تعریف‌نشده است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| latitude | float |  |
| longitude | float |  |
| revolution | float |  |

### getRotation() {#getRotation--}
```
public final float[] getRotation()
```


چرخش از طریق استفاده از مختصات عرض، مختصات طول و یک دور حول محور به عنوان مختصات عرض و طول تعریف می‌شود. عنصر اول در آرایهٔ بازگشتی – عرض، دوم – طول، سوم – دور. اگر چرخشی تعریف نشده باشد، null برگردانده می‌شود.

**برگشت:**
float[]