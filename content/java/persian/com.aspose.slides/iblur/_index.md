---
title: IBlur
second_title: مرجع API Aspose.Slides برای Java
description: نمایانگر یک اثر تار شدن است که بر تمام شکل، از جمله پرش آن، اعمال می‌شود.
type: docs
url: /fa/com.aspose.slides/iblur/
---
**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IBlur extends IImageTransformOperation, IAccessiblePVIObject<IBlurEffectiveData>
```

نمایانگر یک اثر تار شدن است که بر تمام شکل، از جمله پرش آن اعمال می‌شود. تمام کانال‌های رنگ، از جمله آلفا، تحت تأثیر قرار می‌گیرند.
## متدها

| متد | توضیح |
| --- | --- |
| [getRadius()](#getRadius--) | مقدار شعاع تاری را باز می‌گرداند یا تنظیم می‌کند. |
| [setRadius(double value)](#setRadius-double-) | مقدار شعاع تاری را باز می‌گرداند یا تنظیم می‌کند. |
| [getGrow()](#getGrow--) | تعیین می‌کند که آیا مرزهای شی به‌دلیل تاری گسترش یابد یا خیر. |
| [setGrow(boolean value)](#setGrow-boolean-) | تعیین می‌کند که آیا مرزهای شی به‌دلیل تاری گسترش یابد یا خیر. |
### getRadius() {#getRadius--}
```
public abstract double getRadius()
```

مقدار شعاع تاری را باز می‌گرداند یا تنظیم می‌کند. خواندنی/قابل‌نوشت double.

**بازگشت:**
double
### setRadius(double value) {#setRadius-double-}
```
public abstract void setRadius(double value)
```

مقدار شعاع تاری را باز می‌گرداند یا تنظیم می‌کند. خواندنی/قابل‌نوشت double.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | double |  |
### getGrow() {#getGrow--}
```
public abstract boolean getGrow()
```

تعیین می‌کند که آیا مرزهای شی به‌دلیل تاری گسترش یابد یا خیر. مقدار true نشان می‌دهد که مرزها گسترش می‌یابند در حالی که false نشان می‌دهد که این‌طور نیست. خواندنی/قابل‌نوشت boolean.

**بازگشت:**
boolean
### setGrow(boolean value) {#setGrow-boolean-}
```
public abstract void setGrow(boolean value)
```

تعیین می‌کند که آیا مرزهای شی به‌دلیل تاری گسترش یابد یا خیر. مقدار true نشان می‌دهد که مرزها گسترش می‌یابند در حالی که false نشان می‌دهد که این‌طور نیست. خواندنی/قابل‌نوشت boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |