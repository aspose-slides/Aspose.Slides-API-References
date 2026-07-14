---
title: ITableFormat
second_title: Aspose.Slides for Android via Java API Reference
description: Represents format of a table.
type: docs
url: /fa/com.aspose.slides/itableformat/
---```
public interface ITableFormat
```

قالب جدول را نشان می‌دهد.
## متدها

| Method | Description |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | یک شیء ویژگی‌های پر کردن جدول را برمی‌گرداند. |
| [getTransparency()](#getTransparency--) | شفافیت رنگ پر را دریافت یا تنظیم می‌کند. |
| [setTransparency(float value)](#setTransparency-float-) | شفافیت رنگ پر را دریافت یا تنظیم می‌کند. |
| [getEffective()](#getEffective--) | ویژگی‌های قالب‌بندی جدول مؤثر را با به‌کارگیری وراثت و سبک‌های جدول دریافت می‌کند. |
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

یک شیء ویژگی‌های پر کردن جدول را برمی‌گرداند. فقط-خواندنی [IFillFormat](../../com.aspose.slides/ifillformat).

**بازگشت:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getTransparency() {#getTransparency--}
```
public abstract float getTransparency()
```

شفافیت رنگ پر را دریافت یا تنظیم می‌کند. قابل‌خواندن/قابل‌نوشتن  float .

**بازگشت:**
float
### setTransparency(float value) {#setTransparency-float-}
```
public abstract void setTransparency(float value)
```

شفافیت رنگ پر را دریافت یا تنظیم می‌کند. قابل‌خواندن/قابل‌نوشتن  float .

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |
### getEffective() {#getEffective--}
```
public abstract ITableFormatEffectiveData getEffective()
```

ویژگی‌های قالب‌بندی جدول مؤثر را با به‌کارگیری وراثت و سبک‌های جدول دریافت می‌کند.

**بازگشت:**
[ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata) - یک [ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata).