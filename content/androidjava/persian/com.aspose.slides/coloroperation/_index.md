---
title: ColorOperation
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایش عملیات‌های مختلف رنگی که برای تبدیل رنگ استفاده می‌شوند.
type: docs
url: /fa/com.aspose.slides/coloroperation/
---
**ارث‌بری:**
java.lang.Object

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IColorOperation](../../com.aspose.slides/icoloroperation)
```
public class ColorOperation implements IColorOperation
```

نمایش عملیات‌های رنگی مختلفی که برای تبدیل رنگ استفاده می‌شوند. شیء تغییرناپذیر.
## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [ColorOperation(int op)](#ColorOperation-int-) | یک عملیات تبدیل رنگ جدید ایجاد می‌کند. |
| [ColorOperation(int op, float parameter)](#ColorOperation-int-float-) | یک عملیات تبدیل رنگ جدید ایجاد می‌کند. |
## متدها

| متد | توضیح |
| --- | --- |
| [getOperationType()](#getOperationType--) | نوع یک عملیات را برمی‌گرداند یا تنظیم می‌کند. |
| [getParameter()](#getParameter--) | یک پارامتر از عملیات را برمی‌گرداند. |
| [equals(Object obj)](#equals-java.lang.Object-) | مشخص می‌کند که آیا دو نمونهٔ ColorOperation برابر هستند یا خیر. |
| [hashCode()](#hashCode--) | به عنوان یک تابع هش برای یک نوع خاص عمل می‌کند که برای استفاده در الگوریتم‌های هش و ساختارهای داده‌ای مانند جدول هش مناسب است. |
### ColorOperation(int op) {#ColorOperation-int-}
```
public ColorOperation(int op)
```


یک عملیات تبدیل رنگ جدید ایجاد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| op | int | نوع عملیات. |

### ColorOperation(int op, float parameter) {#ColorOperation-int-float-}
```
public ColorOperation(int op, float parameter)
```


یک عملیات تبدیل رنگ جدید ایجاد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| op | int | نوع عملیات. |
| parameter | float | پارامتر عملیات. |

### getOperationType() {#getOperationType--}
```
public final int getOperationType()
```


نوع یک عملیات را برمی‌گرداند یا تنظیم می‌کند. فقط‌خواندنی [ColorTransformOperation](../../com.aspose.slides/colortransformoperation).

**بازگشت:**
int
### getParameter() {#getParameter--}
```
public final float getParameter()
```


یک پارامتر از عملیات را برمی‌گرداند. فقط‌خواندنی float.

**بازگشت:**
float
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


مشخص می‌کند که آیا دو نمونهٔ ColorOperation برابر هستند یا خیر.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| obj | java.lang.Object | ColorOperation که با ColorOperation فعلی مقایسه می‌شود. |

**بازگشت:**
boolean - **true** اگر ColorOperation مشخص‌شده برابر با ColorOperation فعلی باشد؛ در غیر این صورت، **false**.
### hashCode() {#hashCode--}
```
public int hashCode()
```


به عنوان یک تابع هش برای یک نوع خاص عمل می‌کند که برای استفاده در الگوریتم‌های هش و ساختارهای داده‌ای مانند جدول هش مناسب است.

**بازگشت:**
int