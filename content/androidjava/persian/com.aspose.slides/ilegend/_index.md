---
title: ILegend
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: خواص لگند نمودارها را نشان می‌دهد.
type: docs
url: /fa/com.aspose.slides/ilegend/
---
**همه رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface ILegend extends ILayoutable, IFormattedTextContainer, IActualLayout
```

خواص لگند نمودار را نشان می‌دهد.
## متدها

| متد | توضیح |
| --- | --- |
| [getOverlay()](#getOverlay--) | تعیین می‌کند که آیا سایر عناصر نمودار مجاز به پوشش لگند هستند یا نه. |
| [setOverlay(boolean value)](#setOverlay-boolean-) | تعیین می‌کند که آیا سایر عناصر نمودار مجاز به پوشش لگند هستند یا نه. |
| [getPosition()](#getPosition--) | موقعیت لگند را در یک نمودار مشخص می‌کند. |
| [setPosition(int value)](#setPosition-int-) | موقعیت لگند را در یک نمودار مشخص می‌کند. |
| [getFormat()](#getFormat--) | قالب یک لگند را بازمی‌گرداند. |
| [getEntries()](#getEntries--) | ورودی‌های لگند را دریافت می‌کند. |
### getOverlay() {#getOverlay--}
```
public abstract boolean getOverlay()
```


تعیین می‌کند که آیا سایر عناصر نمودار مجاز به پوشش لگند هستند یا نه. قابل خواندن/نوشتن boolean.

**بازمی‌گرداند:**
boolean
### setOverlay(boolean value) {#setOverlay-boolean-}
```
public abstract void setOverlay(boolean value)
```


تعیین می‌کند که آیا سایر عناصر نمودار مجاز به پوشش لگند هستند یا نه. قابل خواندن/نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getPosition() {#getPosition--}
```
public abstract int getPosition()
```


موقعیت لگند را در یک نمودار مشخص می‌کند. مقادیر غیر-NaN ویژگی‌های X، Y، Width، Height اثر این ویژگی را لغو می‌کنند. قابل خواندن/نوشتن [LegendPositionType](../../com.aspose.slides/legendpositiontype).

**بازمی‌گرداند:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```


موقعیت لگند را در یک نمودار مشخص می‌کند. مقادیر غیر-NaN ویژگی‌های X، Y، Width، Height اثر این ویژگی را لغو می‌کنند. قابل خواندن/نوشتن [LegendPositionType](../../com.aspose.slides/legendpositiontype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```


قالب یک لگند را بازمی‌گرداند. فقط خواندنی [IFormat](../../com.aspose.slides/iformat).

**بازمی‌گرداند:**
[IFormat](../../com.aspose.slides/iformat)
### getEntries() {#getEntries--}
```
public abstract ILegendEntryCollection getEntries()
```


ورودی‌های لگند را دریافت می‌کند. فقط خواندنی [ILegendEntryCollection](../../com.aspose.slides/ilegendentrycollection).

**بازمی‌گرداند:**
[ILegendEntryCollection](../../com.aspose.slides/ilegendentrycollection)