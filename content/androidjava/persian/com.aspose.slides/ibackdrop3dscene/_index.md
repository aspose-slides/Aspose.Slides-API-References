---
title: IBackdrop3DScene
second_title: Aspose.Slides برای Android از طریق مرجع Java API
description: یک صفحه را تعریف می‌کند که اثراتی مانند درخشندگی و سایه در رابطه با شکلی که به آن اعمال می‌شوند، اعمال می‌شود.
type: docs
url: /fa/com.aspose.slides/ibackdrop3dscene/
---```
public interface IBackdrop3DScene
```

یک صفحه را تعریف می‌کند که اثراتی مانند درخشندگی و سایه در رابطه با شکلی که به آن اعمال می‌شوند، اعمال می‌شود.
## متدها

| Method | Description |
| --- | --- |
| [getNormalVector()](#getNormalVector--) | یک بردار نرمال را برمی‌گرداند یا تنظیم می‌کند. |
| [setNormalVector(float[] value)](#setNormalVector-float---) | یک بردار نرمال را برمی‌گرداند یا تنظیم می‌کند. |
| [getAnchorPoint()](#getAnchorPoint--) | یک نقطه در فضای سه‌بعدی را برمی‌گرداند یا تنظیم می‌کند. |
| [setAnchorPoint(float[] value)](#setAnchorPoint-float---) | یک نقطه در فضای سه‌بعدی را برمی‌گرداند یا تنظیم می‌کند. |
| [getUpVector()](#getUpVector--) | یک بردار نشان‌دهنده جهت بالا را برمی‌گرداند یا تنظیم می‌کند. |
| [setUpVector(float[] value)](#setUpVector-float---) | یک بردار نشان‌دهنده جهت بالا را برمی‌گرداند یا تنظیم می‌کند. |
### getNormalVector() {#getNormalVector--}
```
public abstract float[] getNormalVector()
```

یک بردار نرمال را برمی‌گرداند یا تنظیم می‌کند. برای دقیق‌تر شدن، این ویژگی یک بردار عمود بر سطح صفحه-پشت را تعریف می‌کند. بردار توسط آرایه‌ای از ۳ مقدار float که مختصات X، Y و Z را تعیین می‌کند، نشان داده می‌شود. قابل خواندن/نوشتن float[].

**باز می‌گردد:**
float[]
### setNormalVector(float[] value) {#setNormalVector-float---}
```
public abstract void setNormalVector(float[] value)
```

یک بردار نرمال را برمی‌گرداند یا تنظیم می‌کند. برای دقیق‌تر شدن، این ویژگی یک بردار عمود بر سطح صفحه-پشت را تعریف می‌کند. بردار توسط آرایه‌ای از ۳ مقدار float که مختصات X، Y و Z را تعیین می‌کند، نشان داده می‌شود. قابل خواندن/نوشتن float[].

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float[] |  |

### getAnchorPoint() {#getAnchorPoint--}
```
public abstract float[] getAnchorPoint()
```

یک نقطه در فضای سه‌بعدی را برمی‌گرداند یا تنظیم می‌کند. این نقطه نقطه‌ای در فضا است که صفحه-پشت را به آن متصل می‌کند. نقطهٔ سه‌بعدی توسط آرایه‌ای از ۳ مقدار float که مختصات X، Y و Z را تعیین می‌کند، نشان داده می‌شود. قابل خواندن/نوشتن float[].

**باز می‌گردد:**
float[]
### setAnchorPoint(float[] value) {#setAnchorPoint-float---}
```
public abstract void setAnchorPoint(float[] value)
```

یک نقطه در فضای سه‌بعدی را برمی‌گرداند یا تنظیم می‌کند. این نقطه نقطه‌ای در فضا است که صفحه-پشت را به آن متصل می‌کند. نقطهٔ سه‌بعدی توسط آرایه‌ای از ۳ مقدار float که مختصات X، Y و Z را تعیین می‌کند، نشان داده می‌شود. قابل خواندن/نوشتن float[].

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float[] |  |

### getUpVector() {#getUpVector--}
```
public abstract float[] getUpVector()
```

یک بردار نشان‌دهنده جهت بالا را برمی‌گرداند یا تنظیم می‌کند. برای دقیق‌تر شدن، این ویژگی یک بردار نشان‌دهنده جهت بالا نسبت به سطح صفحه-پشت را تعریف می‌کند. بردار توسط آرایه‌ای از ۳ مقدار float که مختصات X، Y و Z را تعیین می‌کند، نشان داده می‌شود. قابل خواندن/نوشتن float[].

**باز می‌گردد:**
float[]
### setUpVector(float[] value) {#setUpVector-float---}
```
public abstract void setUpVector(float[] value)
```

یک بردار نشان‌دهنده جهت بالا را برمی‌گرداند یا تنظیم می‌کند. برای دقیق‌تر شدن، این ویژگی یک بردار نشان‌دهنده جهت بالا نسبت به سطح صفحه-پشت را تعریف می‌کند. بردار توسط آرایه‌ای از ۳ مقدار float که مختصات X، Y و Z را تعیین می‌کند، نشان داده می‌شود. قابل خواندن/نوشتن float[].

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float[] |  |