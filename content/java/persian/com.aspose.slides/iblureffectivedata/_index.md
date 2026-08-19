---
title: IBlurEffectiveData
second_title: Aspose.Slides برای مرجع API جاوا
description: شیء غیرقابل تغییر که نمایانگر اثر Blur است که بر کل شکل، از جمله پرشده آن، اعمال می‌شود.
type: docs
url: /fa/com.aspose.slides/iblureffectivedata/
---
**All Implemented Interfaces:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IBlurEffectiveData extends IEffectEffectiveData
```

شیء غیرقابل تغییر که نمایانگر اثر Blur است که بر کل شکل، از جمله پرشده آن اعمال می‌شود. تمام کانال‌های رنگ، از جمله آلفا، تحت تأثیر قرار می‌گیرند.
## متدها

| Method | Description |
| --- | --- |
| [getRadius()](#getRadius--) | مقدار یا تنظیم شعاع تاری. |
| [getGrow()](#getGrow--) | تعیین می‌کند که آیا مرزهای شیء به دلیل تاری بزرگ شوند یا نه. |
### getRadius() {#getRadius--}
```
public abstract double getRadius()
```


مقدار یا تنظیم شعاع تاری. فقط-خواندنی double.

**بازگشت:**
double
### getGrow() {#getGrow--}
```
public abstract boolean getGrow()
```


تعیین می‌کند که آیا مرزهای شیء به دلیل تاری بزرگ شوند یا نه. مقدار true نشان می‌دهد که مرزها بزرگ می‌شوند در حالی که false نشان می‌دهد که این‌گونه نیست. فقط-خواندنی boolean.

**بازگشت:**
boolean