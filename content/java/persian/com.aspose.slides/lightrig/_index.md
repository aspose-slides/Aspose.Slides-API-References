---
title: LightRig
second_title: مرجع API Aspose.Slides برای جاوا
description: نمایانگر LightRig.
type: docs
url: /fa/com.aspose.slides/lightrig/
---
**وراثت:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.ILightRig](../../com.aspose.slides/ilightrig)
```
public final class LightRig extends PVIObject implements ILightRig
```

نمایانگر LightRig.
## متدها

| متد | توضیح |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getDirection()](#getDirection--) | جهت نور. |
| [setDirection(int value)](#setDirection-int-) | جهت نور. |
| [getLightType()](#getLightType--) | نمایانگر یک نور پیش‌فرض راست که می‌تواند به یک شکل اعمال شود. |
| [setLightType(int value)](#setLightType-int-) | نمایانگر یک نور پیش‌فرض راست که می‌تواند به یک شکل اعمال شود. |
| [setRotation(float latitude, float longitude, float revolution)](#setRotation-float-float-float-) | یک چرخش از طریق استفاده از مختصات عرض جغرافیایی، مختصات طول جغرافیایی و یک دوران حول محور به عنوان مختصات عرض و طول تعریف می‌شود. |
| [getRotation()](#getRotation--) | یک چرخش از طریق استفاده از مختصات عرض جغرافیایی، مختصات طول جغرافیایی و یک دوران حول محور به عنوان مختصات عرض و طول تعریف می‌شود. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

نسخه. فقط خواندنی long.

**بازگرداندن:**
long
### getDirection() {#getDirection--}
```
public final int getDirection()
```

جهت نور. خواندن/نوشتن [LightingDirection](../../com.aspose.slides/lightingdirection).

**بازگرداندن:**
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

نمایانگر یک نور پیش‌فرض راست که می‌تواند به یک شکل اعمال شود. مجموعه نورها به‌صورت خاصی نسبت به صحنه سه‌بعدی جهت‌دار است. خواندن/نوشتن [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**بازگرداندن:**
int
### setLightType(int value) {#setLightType-int-}
```
public final void setLightType(int value)
```

نمایانگر یک نور پیش‌فرض راست که می‌تواند به یک شکل اعمال شود. مجموعه نورها به‌صورت خاصی نسبت به صحنه سه‌بعدی جهت‌دار است. خواندن/نوشتن [LightRigPresetType](../../com.aspose.slides/lightrigpresettype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |
### setRotation(float latitude, float longitude, float revolution) {#setRotation-float-float-float-}
```
public final void setRotation(float latitude, float longitude, float revolution)
```

یک چرخش از طریق استفاده از مختصات عرض جغرافیایی، مختصات طول جغرافیایی و یک دوران حول محور به عنوان مختصات عرض و طول تعریف می‌شود. اگر هر یک از مقادیر مختصات Float.NaN باشد، تمام چرخش تعریف‌نشده است.

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

یک چرخش از طریق استفاده از مختصات عرض جغرافیایی، مختصات طول جغرافیایی و یک دوران حول محور به عنوان مختصات عرض و طول تعریف می‌شود. اولین عنصر در آرایه بازگشتی - عرض، دومین - طول، سومین - دوران. اگر چرخشی تعریف نشده باشد، مقدار null برگردانده می‌شود.

**بازگرداندن:**
float[]