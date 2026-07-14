---
title: IBlurEffectiveData
second_title: Aspose.Slides برای اندروید از طریق مرجع API جاوا
description: شیء غیرقابل تغییر که نمایانگر اثر Blur است که بر تمام شکل، از جمله پرکننده آن اعمال می‌شود.
type: docs
url: /fa/com.aspose.slides/iblureffectivedata/
---
**تمام رابط‌های پیاده‌سازی شده:**  
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IBlurEffectiveData extends IEffectEffectiveData
```

شیء غیرقابل تغییر که نمایانگر اثر Blur است که بر تمام شکل، از جمله پرکننده آن اعمال می‌شود. تمام کانال‌های رنگی، از جمله آلفا، تحت تاثیر هستند.

## متدها

| متد | توضیح |
| --- | --- |
| [getRadius()](#getRadius--) | مقدار شعاع تاری را برمی‌گرداند یا تنظیم می‌کند. |
| [getGrow()](#getGrow--) | تعیین می‌کند که آیا مرزهای شیء به‌دلیل تاری بزرگ شوند یا نه. |

### getRadius() {#getRadius--}
```
public abstract double getRadius()
```

بازگرداندن یا تنظیم شعاع تاری. فقط-خواندنی double.

**بازگشت:**  
double

### getGrow() {#getGrow--}
```
public abstract boolean getGrow()
```

تعیین می‌کند که آیا مرزهای شیء به‌دلیل تاری بزرگ شوند یا نه. مقدار True نشان می‌دهد که مرزها بزرگ می‌شوند و مقدار false نشان می‌دهد که این‌گونه نیست. فقط-خواندنی boolean.

**بازگشت:**  
boolean