---
title: IChartTitle
second_title: Aspose.Slides برای مرجع API جاوا
description: خواص عنوان نمودار را نشان می‌دهد.
type: docs
url: /fa/com.aspose.slides/icharttitle/
---
**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IOverridableText](../../com.aspose.slides/ioverridabletext), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IChartTitle extends ILayoutable, IOverridableText, IActualLayout
```

خواص عنوان نمودار را نشان می‌دهد.
## متدها

| متد | توضیح |
| --- | --- |
| [getOverlay()](#getOverlay--) | تعیین می‌کند آیا عناصر دیگر نمودار می‌توانند روی عنوان قرار گیرند. |
| [setOverlay(boolean value)](#setOverlay-boolean-) | تعیین می‌کند آیا عناصر دیگر نمودار می‌توانند روی عنوان قرار گیرند. |
| [getFormat()](#getFormat--) | مقداردهی‌های پر، خط و اثرهای یک عنوان را برمی‌گرداند. |
### getOverlay() {#getOverlay--}
```
public abstract boolean getOverlay()
```

تعیین می‌کند آیا عناصر دیگر نمودار می‌توانند روی عنوان قرار گیرند. خواندنی/نوشتنی boolean.

**بازگشت:**
boolean
### setOverlay(boolean value) {#setOverlay-boolean-}
```
public abstract void setOverlay(boolean value)
```

تعیین می‌کند آیا عناصر دیگر نمودار می‌توانند روی عنوان قرار گیرند. خواندنی/نوشتنی boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

مقداردهی‌های پر، خط و اثرهای یک عنوان را برمی‌گرداند. فقط‌خواندنی [IFormat](../../com.aspose.slides/iformat).

**بازگشت:**
[IFormat](../../com.aspose.slides/iformat)