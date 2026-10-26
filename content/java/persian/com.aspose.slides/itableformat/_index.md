---
title: ITableFormat
second_title: Aspose.Slides for Java API Reference
description: نمایان‌گر فرمت یک جدول است.
type: docs
url: /fa/com.aspose.slides/itableformat/
---```
public interface ITableFormat
```

نمایان‌گر فرمت یک جدول است.
## Methods

| Method | Description |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | یک شیء خصوصیات پر کردن جدول را برمی‌گرداند. |
| [getTransparency()](#getTransparency--) | شفافیت رنگ پر کردن را دریافت یا تنظیم می‌کند. |
| [setTransparency(float value)](#setTransparency-float-) | شفافیت رنگ پر کردن را دریافت یا تنظیم می‌کند. |
| [getEffective()](#getEffective--) | خصوصیات قالب‌بندی جدول مؤثر را با به‌کارگیری وراثت و سبک‌های جدول دریافت می‌کند. |
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

یک شیء خصوصیات پر کردن جدول را برمی‌گرداند. فقط-خواندنی [IFillFormat](../../com.aspose.slides/ifillformat).

**بازگشت:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getTransparency() {#getTransparency--}
```
public abstract float getTransparency()
```

شفافیت رنگ پر کردن را دریافت یا تنظیم می‌کند. قابل-خواندن/قابل-نوشتن  float .

**بازگشت:**
float
### setTransparency(float value) {#setTransparency-float-}
```
public abstract void setTransparency(float value)
```

شفافیت رنگ پر کردن را دریافت یا تنظیم می‌کند. قابل-خواندن/قابل-نوشتن  float .

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |
### getEffective() {#getEffective--}
```
public abstract ITableFormatEffectiveData getEffective()
```

خصوصیات قالب‌بندی جدول مؤثر را با به‌کارگیری وراثت و سبک‌های جدول دریافت می‌کند.

**بازگشت:**
[ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata) - یک [ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata).