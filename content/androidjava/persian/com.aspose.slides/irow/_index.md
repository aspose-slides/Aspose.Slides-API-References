---
title: IRow
second_title: Aspose.Slides برای Android از طریق مرجع API Java
description: نمایانگر یک سطر در جدول.
type: docs
url: /fa/com.aspose.slides/irow/
---
**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.ICellCollection](../../com.aspose.slides/icellcollection), [com.aspose.slides.IBulkTextFormattable](../../com.aspose.slides/ibulktextformattable)
```
public interface IRow extends ICellCollection, IBulkTextFormattable
```

نمایش یک سطر در جدول.
## روش‌ها

| متد | شرح |
| --- | --- |
| [getHeight()](#getHeight--) | ارتفاع یک سطر را بازمی‌گرداند. |
| [getMinimalHeight()](#getMinimalHeight--) | ارتفاع کمینه ممکن یک سطر را بازمی‌گرداند یا تنظیم می‌کند. |
| [setMinimalHeight(double value)](#setMinimalHeight-double-) | ارتفاع کمینه ممکن یک سطر را بازمی‌گرداند یا تنظیم می‌کند. |
| [getRowFormat()](#getRowFormat--) | شیء RowFormat را که شامل ویژگی‌های قالب‌بندی این سطر است بازمی‌گرداند. |
### getHeight() {#getHeight--}
```
public abstract double getHeight()
```

ارتفاع یک سطر را بازمی‌گرداند. فقط خواندنی double.

**بازمی‌گرداند:**  
double
### getMinimalHeight() {#getMinimalHeight--}
```
public abstract double getMinimalHeight()
```

ارتفاع کمینه ممکن یک سطر را بازمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن double.

**بازمی‌گرداند:**  
double
### setMinimalHeight(double value) {#setMinimalHeight-double-}
```
public abstract void setMinimalHeight(double value)
```

ارتفاع کمینه ممکن یک سطر را بازمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن double.

**پارامترها:**
| پارامتر | نوع | شرح |
| --- | --- | --- |
| value | double |  |
### getRowFormat() {#getRowFormat--}
```
public abstract IRowFormat getRowFormat()
```

شیء RowFormat را که شامل ویژگی‌های قالب‌بندی این سطر است بازمی‌گرداند. فقط خواندنی [IRowFormat](../../com.aspose.slides/irowformat).

**بازمی‌گرداند:**  
[IRowFormat](../../com.aspose.slides/irowformat)