---
title: ICachedChartValue
second_title: Aspose.Slides for Java API Reference
description: نمایانگر یک مقدار کش‌شده از نمودار است، مانند X، Y، اندازه‌ حباب یا مقدار اصلی.
type: docs
url: /fa/com.aspose.slides/icachedchartvalue/
---```
public interface ICachedChartValue
```

نمایانگر یک مقدار کش‌شده از نمودار است (به عنوان مثال X، Y، اندازه‌ حباب یا مقدار اصلی).

## متدها

| Method | Description |
| --- | --- |
| [getData()](#getData--) | آبجکت داده‌های کش‌شده را دریافت می‌کند. |
| [toDouble()](#toDouble--) | مقدار کش‌شده را به double تبدیل می‌کند. |

### getData() {#getData--}
```
public abstract Object getData()
```

آبجکت داده‌های کش‌شده را دریافت می‌کند. فقط‌خواندنی Object.

**بازگشت:**
java.lang.Object

### toDouble() {#toDouble--}
```
public abstract double toDouble()
```

مقدار کش‌شده را به double تبدیل می‌کند.

**بازگشت:**
double - نمایش عددی، یا Double.NaN اگر Data (\#getData.getData) null باشد یا نتواند به double تبدیل شود.