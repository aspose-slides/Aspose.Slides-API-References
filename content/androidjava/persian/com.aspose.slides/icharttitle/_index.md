---
title: IChartTitle
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: ویژگی‌های عنوان نمودار را نمایش می‌دهد.
type: docs
url: /fa/com.aspose.slides/icharttitle/
---
**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IOverridableText](../../com.aspose.slides/ioverridabletext), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IChartTitle extends ILayoutable, IOverridableText, IActualLayout
```

خاصیت‌های عنوان نمودار را نمایش می‌دهد.
## متدها

| متد | توضیح |
| --- | --- |
| [getOverlay()](#getOverlay--) | تعیین می‌کند که آیا عناصر دیگر نمودار اجازه پوشاندن عنوان را داشته باشند یا نه. |
| [setOverlay(boolean value)](#setOverlay-boolean-) | تعیین می‌کند که آیا عناصر دیگر نمودار اجازه پوشاندن عنوان را داشته باشند یا نه. |
| [getFormat()](#getFormat--) | استایل‌های پرکننده، خط و افکت عنوان را برمی‌گرداند. |
### getOverlay() {#getOverlay--}
```
public abstract boolean getOverlay()
```


تعیین می‌کند که آیا عناصر دیگر نمودار اجازه پوشاندن عنوان را داشته باشند یا نه. متغیر بولی خواندنی/نوشتنی.

**بازگشت:**
boolean
### setOverlay(boolean value) {#setOverlay-boolean-}
```
public abstract void setOverlay(boolean value)
```


تعیین می‌کند که آیا عناصر دیگر نمودار اجازه پوشاندن عنوان را داشته باشند یا نه. متغیر بولی خواندنی/نوشتنی.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```


استایل‌های پرکننده، خط و افکت عنوان را برمی‌گرداند. فقط-خواندنی [IFormat](../../com.aspose.slides/iformat).

**بازگشت:**
[IFormat](../../com.aspose.slides/iformat)