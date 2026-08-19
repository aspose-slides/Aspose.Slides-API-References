---
title: IActualLayout
second_title: Aspose.Slides for Java API Reference
description: موقعیت واقعی یک عنصر نمودار را مشخص می‌کند.
type: docs
url: /fa/com.aspose.slides/iactuallayout/
---```
public interface IActualLayout
```

موقعیت واقعی یک عنصر نمودار را مشخص می‌کند.
## روش‌ها

| Method | Description |
| --- | --- |
| [getActualX()](#getActualX--) | موقعیت واقعی x (چپ) عنصر نمودار را نسبت به گوشهٔ بالای چپ نمودار مشخص می‌کند. |
| [getActualY()](#getActualY--) | موقعیت واقعی بالای عنصر نمودار را نسبت به گوشهٔ بالای چپ نمودار مشخص می‌کند. |
| [getActualWidth()](#getActualWidth--) | عرض واقعی عنصر نمودار را مشخص می‌کند. |
| [getActualHeight()](#getActualHeight--) | ارتفاع واقعی عنصر نمودار را مشخص می‌کند. |
### getActualX() {#getActualX--}
```
public abstract float getActualX()
```


موقعیت واقعی x (چپ) عنصر نمودار را نسبت به گوشهٔ بالای چپ نمودار مشخص می‌کند. قبل از دریافت مقادیر واقعی، متد IChart.ValidateChartLayout() را صدا بزنید. float خوانده می‌شود.

**بازگشت:**
float
### getActualY() {#getActualY--}
```
public abstract float getActualY()
```


موقعیت واقعی بالای عنصر نمودار را نسبت به گوشهٔ بالای چپ نمودار مشخص می‌کند. قبل از دریافت مقادیر واقعی، متد IChart.ValidateChartLayout() را صدا بزنید. float خوانده می‌شود.

**بازگشت:**
float
### getActualWidth() {#getActualWidth--}
```
public abstract float getActualWidth()
```


عرض واقعی عنصر نمودار را مشخص می‌کند. قبل از دریافت مقادیر واقعی، متد IChart.ValidateChartLayout() را صدا بزنید. float خوانده می‌شود.

**بازگشت:**
float
### getActualHeight() {#getActualHeight--}
```
public abstract float getActualHeight()
```


ارتفاع واقعی عنصر نمودار را مشخص می‌کند. قبل از دریافت مقادیر واقعی، متد IChart.ValidateChartLayout() را صدا بزنید. float خوانده می‌شود.

**بازگشت:**
float