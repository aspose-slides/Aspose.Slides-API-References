---
title: ILegend
second_title: مرجع API Aspose.Slides برای جاوا
description: خواص افسانهٔ نمودارها را نشان می‌دهد.
type: docs
url: /fa/com.aspose.slides/ilegend/
---
**تمام واسط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface ILegend extends ILayoutable, IFormattedTextContainer, IActualLayout
```

خواص افسانهٔ نمودار را نشان می‌دهد.
## متدها

| متد | توضیح |
| --- | --- |
| [getOverlay()](#getOverlay--) | تعیین می‌کند که آیا عناصر دیگر نمودار مجاز به پوشش افسانه هستند. |
| [setOverlay(boolean value)](#setOverlay-boolean-) | تعیین می‌کند که آیا عناصر دیگر نمودار مجاز به پوشش افسانه هستند. |
| [getPosition()](#getPosition--) | موقعیت افسانه را در نمودار مشخص می‌کند. |
| [setPosition(int value)](#setPosition-int-) | موقعیت افسانه را در نمودار مشخص می‌کند. |
| [getFormat()](#getFormat--) | قالب یک افسانه را برمی‌گرداند. |
| [getEntries()](#getEntries--) | ورودی‌های افسانه را دریافت می‌کند. |
### getOverlay() {#getOverlay--}
```
public abstract boolean getOverlay()
```

تعیین می‌کند که آیا عناصر دیگر نمودار مجاز به پوشش افسانه هستند. قابل خواندن/نوشتن boolean.

**بازگشت:**
boolean
### setOverlay(boolean value) {#setOverlay-boolean-}
```
public abstract void setOverlay(boolean value)
```

تعیین می‌کند که آیا عناصر دیگر نمودار مجاز به پوشش افسانه هستند. قابل خواندن/نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |
### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

موقعیت افسانه را در نمودار مشخص می‌کند. مقادیر غیر NaN X، Y، Width، Height مؤثر این ویژگی را نادیده می‌گیرند. قابل خواندن/نوشتن [LegendPositionType](../../com.aspose.slides/legendpositiontype).

**بازگشت:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

موقعیت افسانه را در نمودار مشخص می‌کند. مقادیر غیر NaN X، Y، Width، Height مؤثر این ویژگی را نادیده می‌گیرند. قابل خواندن/نوشتن [LegendPositionType](../../com.aspose.slides/legendpositiontype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

قالب یک افسانه را برمی‌گرداند. فقط خواندنی [IFormat](../../com.aspose.slides/iformat).

**بازگشت:**
[IFormat](../../com.aspose.slides/iformat)
### getEntries() {#getEntries--}
```
public abstract ILegendEntryCollection getEntries()
```

ورودی‌های افسانه را دریافت می‌کند. فقط خواندنی [ILegendEntryCollection](../../com.aspose.slides/ilegendentrycollection).

**بازگشت:**
[ILegendEntryCollection](../../com.aspose.slides/ilegendentrycollection)