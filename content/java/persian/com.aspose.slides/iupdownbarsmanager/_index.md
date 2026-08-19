---
title: IUpDownBarsManager
second_title: Aspose.Slides for Java API Reference
description: دسترسی به نوارهای بالا/پایین در نمودار خطی یا سهام فراهم می‌کند.
type: docs
url: /fa/com.aspose.slides/iupdownbarsmanager/
---```
public interface IUpDownBarsManager
```

دسترسی به نوارهای بالا/پایین در نمودار خطی یا سهام فراهم می‌کند.
## متدها

| متد | توضیح |
| --- | --- |
| [getUpBarsFormat()](#getUpBarsFormat--) | قالب نوارهای بالا را برمی‌گرداند. |
| [getDownBarsFormat()](#getDownBarsFormat--) | قالب نوارهای پایین را برمی‌گرداند. |
| [hasUpDownBars()](#hasUpDownBars--) | تعیین می‌کند که آیا نمودار نوارهای بالا/پایین دارد یا خیر. |
| [setUpDownBars(boolean value)](#setUpDownBars-boolean-) | تعیین می‌کند که آیا نمودار نوارهای بالا/پایین دارد یا خیر. |
| [getGapWidth()](#getGapWidth--) | عرض فاصله را برمی‌گرداند یا تنظیم می‌کند. |
| [setGapWidth(int value)](#setGapWidth-int-) | عرض فاصله را برمی‌گرداند یا تنظیم می‌کند. |
### getUpBarsFormat() {#getUpBarsFormat--}
```
public abstract IFormat getUpBarsFormat()
```


قالب نوارهای بالا را برمی‌گرداند. فقط خواندنی [IFormat](../../com.aspose.slides/iformat).

**بازگشت:**
[IFormat](../../com.aspose.slides/iformat)
### getDownBarsFormat() {#getDownBarsFormat--}
```
public abstract IFormat getDownBarsFormat()
```


قالب نوارهای پایین را برمی‌گرداند. فقط خواندنی [IFormat](../../com.aspose.slides/iformat).

**بازگشت:**
[IFormat](../../com.aspose.slides/iformat)
### hasUpDownBars() {#hasUpDownBars--}
```
public abstract boolean hasUpDownBars()
```


تعیین می‌کند که آیا نمودار نوارهای بالا/پایین دارد یا خیر. نوشتن/خواندن بولی.

**بازگشت:**
boolean
### setUpDownBars(boolean value) {#setUpDownBars-boolean-}
```
public abstract void setUpDownBars(boolean value)
```


تعیین می‌کند که آیا نمودار نوارهای بالا/پایین دارد یا خیر. نوشتن/خواندن بولی.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```


عرض فاصله را برمی‌گرداند یا تنظیم می‌کند. نوشتن/خواندن عدد صحیح.

**بازگشت:**
int
### setGapWidth(int value) {#setGapWidth-int-}
```
public abstract void setGapWidth(int value)
```


عرض فاصله را برمی‌گرداند یا تنظیم می‌کند. نوشتن/خواندن عدد صحیح.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |