---
title: ColorOperation
second_title: مرجع API Aspose.Slides برای Java
description: نمایان‌گر عملیات‌های رنگی مختلفی است که برای تبدیلات رنگ استفاده می‌شود.
type: docs
url: /fa/com.aspose.slides/coloroperation/
---
**ارث‌بری:**
java.lang.Object

**تمام رابط‌های پیاده‌سازی شده:**
[com.aspose.slides.IColorOperation](../../com.aspose.slides/icoloroperation)
```
public class ColorOperation implements IColorOperation
```

نمایان‌گر عملیات‌های رنگی مختلفی است که برای تبدیل رنگ استفاده می‌شوند. شیء غیرقابل تغییر.
## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [ColorOperation(int op)](#ColorOperation-int-) | Creates new color transform operation. |
| [ColorOperation(int op, float parameter)](#ColorOperation-int-float-) | Creates new color transform operation. |
## متدها

| متد | توضیح |
| --- | --- |
| [getOperationType()](#getOperationType--) | Returns or sets the type of an operation. |
| [getParameter()](#getParameter--) | Returns a parameter of an operation. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the two ColorOperation instances are equal. |
| [hashCode()](#hashCode--) | Serves as a hash function for a particular type, suitable for use in hashing algorithms and data structures like a hash table. |
### ColorOperation(int op) {#ColorOperation-int-}
```
public ColorOperation(int op)
```

Creates new color transform operation.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| op | int | نوع عملیات. |

### ColorOperation(int op, float parameter) {#ColorOperation-int-float-}
```
public ColorOperation(int op, float parameter)
```

Creates new color transform operation.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| op | int | نوع عملیات. |
| parameter | float | پارامتر عملیات. |

### getOperationType() {#getOperationType--}
```
public final int getOperationType()
```

Returns or sets the type of an operation. فقط-خواندنی [ColorTransformOperation](../../com.aspose.slides/colortransformoperation).

**بازگشت:**
int
### getParameter() {#getParameter--}
```
public final float getParameter()
```

Returns a parameter of an operation. فقط-خواندنی float.

**بازگشت:**
float
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Determines whether the two ColorOperation instances are equal.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| obj | java.lang.Object | ColorOperation که برای مقایسه با ColorOperation جاری استفاده می‌شود. |

**بازگشت:**
boolean - **true** اگر ColorOperation مشخص‌شده برابر با ColorOperation جاری باشد؛ در غیر این صورت **false**.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Serves as a hash function for a particular type, suitable for use in hashing algorithms and data structures like a hash table.

**بازگشت:**
int