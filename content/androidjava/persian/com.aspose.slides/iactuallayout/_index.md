---
title: IActualLayout
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: موقعیت واقعی یک عنصر نمودار را مشخص می‌کند.
type: docs
url: /fa/com.aspose.slides/iactuallayout/
---```
public interface IActualLayout
```

موقعیت واقعی یک عنصر نمودار را مشخص می‌کند.
## متدها

| متد | توضیح |
| --- | --- |
| [getActualX()](#getActualX--) | موقعیت واقعی x (چپ) عنصر نمودار نسبت به گوشه بالای چپ نمودار را مشخص می‌کند. |
| [getActualY()](#getActualY--) | موقعیت واقعی بالا (top) عنصر نمودار نسبت به گوشه بالای چپ نمودار را مشخص می‌کند. |
| [getActualWidth()](#getActualWidth--) | عرض واقعی عنصر نمودار را مشخص می‌کند. |
| [getActualHeight()](#getActualHeight--) | ارتفاع واقعی عنصر نمودار را مشخص می‌کند. |
### getActualX() {#getActualX--}
```
public abstract float getActualX()
```

موقعیت واقعی x (چپ) عنصر نمودار نسبت به گوشه بالای چپ نمودار را مشخص می‌کند. قبل از دریافت مقادیر واقعی، متد IChart.ValidateChartLayout() را فراخوانی کنید. خواندن float.

**بازگشت:**  
float
### getActualY() {#getActualY--}
```
public abstract float getActualY()
```

موقعیت واقعی بالا (top) عنصر نمودار نسبت به گوشه بالای چپ نمودار را مشخص می‌کند. قبل از دریافت مقادیر واقعی، متد IChart.ValidateChartLayout() را فراخوانی کنید. خواندن float.

**بازگشت:**  
float
### getActualWidth() {#getActualWidth--}
```
public abstract float getActualWidth()
```

عرض واقعی عنصر نمودار را مشخص می‌کند. قبل از دریافت مقادیر واقعی، متد IChart.ValidateChartLayout() را فراخوانی کنید. خواندن float.

**بازگشت:**  
float
### getActualHeight() {#getActualHeight--}
```
public abstract float getActualHeight()
```

ارتفاع واقعی عنصر نمودار را مشخص می‌کند. قبل از دریافت مقادیر واقعی، متد IChart.ValidateChartLayout() را فراخوانی کنید. خواندن float.

**بازگشت:**  
float