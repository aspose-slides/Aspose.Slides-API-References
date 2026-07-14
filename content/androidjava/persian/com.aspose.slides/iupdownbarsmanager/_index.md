---
title: IUpDownBarsManager
second_title: Aspose.Slides for Android via Java API Reference
description: دسترسی به نوارهای بالا/پایین نمودار خط یا سهام را فراهم می‌کند.
type: docs
url: /fa/com.aspose.slides/iupdownbarsmanager/
---```
public interface IUpDownBarsManager
```

Provide access to up/down bars of Line- or Stock-chart.
## متدها

| متد | توضیح |
| --- | --- |
| [getUpBarsFormat()](#getUpBarsFormat--) | قالب نوارهای بالا را بازمی‌گرداند. |
| [getDownBarsFormat()](#getDownBarsFormat--) | قالب نوارهای پایین را بازمی‌گرداند. |
| [hasUpDownBars()](#hasUpDownBars--) | تعیین می‌کند که آیا نمودار نوارهای بالا/پایین دارد یا خیر. |
| [setUpDownBars(boolean value)](#setUpDownBars-boolean-) | تعیین می‌کند که آیا نمودار نوارهای بالا/پایین دارد یا خیر. |
| [getGapWidth()](#getGapWidth--) | عرض فاصله را بازمی‌گرداند یا تنظیم می‌کند. |
| [setGapWidth(int value)](#setGapWidth-int-) | عرض فاصله را بازمی‌گرداند یا تنظیم می‌کند. |
### getUpBarsFormat() {#getUpBarsFormat--}
```
public abstract IFormat getUpBarsFormat()
```


قالب نوارهای بالا را بازمی‌گرداند. فقط-خواندنی [IFormat](../../com.aspose.slides/iformat).

**بازگرداندن:**
[IFormat](../../com.aspose.slides/iformat)
### getDownBarsFormat() {#getDownBarsFormat--}
```
public abstract IFormat getDownBarsFormat()
```


قالب نوارهای پایین را بازمی‌گرداند. فقط-خواندنی [IFormat](../../com.aspose.slides/iformat).

**بازگرداندن:**
[IFormat](../../com.aspose.slides/iformat)
### hasUpDownBars() {#hasUpDownBars--}
```
public abstract boolean hasUpDownBars()
```


تعیین می‌کند که آیا نمودار نوارهای بالا/پایین دارد یا خیر. خواندنی/نوشتنی boolean.

**بازگرداندن:**
boolean
### setUpDownBars(boolean value) {#setUpDownBars-boolean-}
```
public abstract void setUpDownBars(boolean value)
```


تعیین می‌کند که آیا نمودار نوارهای بالا/پایین دارد یا خیر. خواندنی/نوشتنی boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```


عرض فاصله را بازمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی int.

**بازگرداندن:**
int
### setGapWidth(int value) {#setGapWidth-int-}
```
public abstract void setGapWidth(int value)
```


عرض فاصله را بازمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی int.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |