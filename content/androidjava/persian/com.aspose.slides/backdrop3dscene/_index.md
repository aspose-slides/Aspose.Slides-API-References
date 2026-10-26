---
title: Backdrop3DScene
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: یک صفحه تعریف می‌کند که افکت‌هایی مانند تابش و سایه نسبت به شکلی که بر روی آن اعمال می‌شوند، اعمال می‌گردند.
type: docs
url: /fa/com.aspose.slides/backdrop3dscene/
---
**ارث‌برداری:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**تمام رابط‌های پیاده‌سازی‌شده:**  
[com.aspose.slides.IBackdrop3DScene](../../com.aspose.slides/ibackdrop3dscene)  
```
public final class Backdrop3DScene extends PVIObject implements IBackdrop3DScene
```

یک صفحه تعریف می‌کند که افکت‌هایی مانند تابش و سایه نسبت به شکل اعمال می‌شوند.

## متدها

| متد | توضیح |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getNormalVector()](#getNormalVector--) | بازمی‌گرداند یا تنظیم می‌کند یک بردار نرمال. |
| [setNormalVector(float[] value)](#setNormalVector-float---) | بازمی‌گرداند یا تنظیم می‌کند یک بردار نرمال. |
| [getAnchorPoint()](#getAnchorPoint--) | بازمی‌گرداند یا تنظیم می‌کند یک نقطه در فضاهای 3-بعدی. |
| [setAnchorPoint(float[] value)](#setAnchorPoint-float---) | بازمی‌گرداند یا تنظیم می‌کند یک نقطه در فضاهای 3-بعدی. |
| [getUpVector()](#getUpVector--) | بازمی‌گرداند یا تنظیم می‌کند یک بردار نشان‌دهنده جهت بالا. |
| [setUpVector(float[] value)](#setUpVector-float---) | بازمی‌گرداند یا تنظیم می‌کند یک بردار نشان‌دهنده جهت بالا. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

نسخه. فقط-خواندنی long.

**بازمی‌گرداند:**  
long

### getNormalVector() {#getNormalVector--}
```
public final float[] getNormalVector()
```

بازمی‌گرداند یا تنظیم می‌کند یک بردار نرمال. برای دقیق‌تر شدن، این ویژگی یک بردار عمود بر سطح صفحه پس‌زمینه را تعریف می‌کند. بردار با آرایه‌ای از ۳ مقدار شناور که مختصات X، Y و Z را تعیین می‌کنند، نشان داده می‌شود. خواندنی/نوشتنی float[].

**بازمی‌گرداند:**  
float[]

### setNormalVector(float[] value) {#setNormalVector-float---}
```
public final void setNormalVector(float[] value)
```

بازمی‌گرداند یا تنظیم می‌کند یک بردار نرمال. برای دقیق‌تر شدن، این ویژگی یک بردار عمود بر سطح صفحه پس‌زمینه را تعریف می‌کند. بردار با آرایه‌ای از ۳ مقدار شناور که مختصات X، Y و Z را تعیین می‌کنند، نشان داده می‌شود. خواندنی/نوشتنی float[].

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float[] |  |

### getAnchorPoint() {#getAnchorPoint--}
```
public final float[] getAnchorPoint()
```

بازمی‌گرداند یا تنظیم می‌کند یک نقطه در فضاهای 3-بعدی. این نقطه محل لنگر صفحه پس‌زمینه است. نقطه 3-بعدی با آرایه‌ای از ۳ مقدار شناور که مختصات X، Y و Z را تعیین می‌کنند، نشان داده می‌شود. خواندنی/نوشتنی float[].

**بازمی‌گرداند:**  
float[]

### setAnchorPoint(float[] value) {#setAnchorPoint-float---}
```
public final void setAnchorPoint(float[] value)
```

بازمی‌گرداند یا تنظیم می‌کند یک نقطه در فضاهای 3-بعدی. این نقطه محل لنگر صفحه پس‌زمینه است. نقطه 3-بعدی با آرایه‌ای از ۳ مقدار شناور که مختصات X، Y و Z را تعیین می‌کنند، نشان داده می‌شود. خواندنی/نوشتنی float[].

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float[] |  |

### getUpVector() {#getUpVector--}
```
public final float[] getUpVector()
```

بازمی‌گرداند یا تنظیم می‌کند یک بردار نشان‌دهنده جهت بالا. برای دقیق‌تر شدن، این ویژگی یک بردار نشان‌دهنده جهت بالا نسبت به سطح صفحه پس‌زمینه را تعریف می‌کند. بردار با آرایه‌ای از ۳ مقدار شناور که مختصات X، Y و Z را تعیین می‌کنند، نشان داده می‌شود. خواندنی/نوشتنی float[].

**بازمی‌گرداند:**  
float[]

### setUpVector(float[] value) {#setUpVector-float---}
```
public final void setUpVector(float[] value)
```

بازمی‌گرداند یا تنظیم می‌کند یک بردار نشان‌دهنده جهت بالا. برای دقیق‌تر شدن، این ویژگی یک بردار نشان‌دهنده جهت بالا نسبت به سطح صفحه پس‌زمینه را تعریف می‌کند. بردار با آرایه‌ای از ۳ مقدار شناور که مختصات X، Y و Z را تعیین می‌کنند، نشان داده می‌شود. خواندنی/نوشتنی float[].

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float[] |  |