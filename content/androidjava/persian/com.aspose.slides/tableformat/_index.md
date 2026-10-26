---
title: TableFormat
second_title: مرجع API جاوا برای Aspose.Slides برای Android
description: قالب جدول را نمایش می‌دهد.
type: docs
url: /fa/com.aspose.slides/tableformat/
---
**ارث‌بری:**
java.lang.Object, com.aspose.slides.DomObject

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.ITableFormat](../../com.aspose.slides/itableformat), com.aspose.slides.IPVIObject
```
public final class TableFormat extends DomObject<Table> implements ITableFormat, IPVIObject
```

قالب جدول را نمایش می‌دهد.
## متدها

| متد | توضیح |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | یک شیء ویژگی‌های پرکن جدول را بازمی‌گرداند. |
| [getTransparency()](#getTransparency--) | شفافیت رنگ پرکن را دریافت یا تنظیم می‌کند. |
| [setTransparency(float value)](#setTransparency-float-) | شفافیت رنگ پرکن را دریافت یا تنظیم می‌کند. |
| [getEffective()](#getEffective--) | ویژگی‌های فرمت جدول مؤثر را با ارث‌بری و سبک‌های جدول دریافت می‌کند. |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```

یک شیء ویژگی‌های پرکن جدول را بازمی‌گرداند. فقط-خواندنی [IFillFormat](../../com.aspose.slides/ifillformat).

**بازگشت:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getTransparency() {#getTransparency--}
```
public final float getTransparency()
```

شفافیت رنگ پرکن را دریافت یا تنظیم می‌کند. خواندنی/نوشتنی  float .

**بازگشت:**
float
### setTransparency(float value) {#setTransparency-float-}
```
public final void setTransparency(float value)
```

شفافیت رنگ پرکن را دریافت یا تنظیم می‌کند. خواندنی/نوشتنی  float .

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |
### getEffective() {#getEffective--}
```
public final ITableFormatEffectiveData getEffective()
```

ویژگی‌های فرمت جدول مؤثر را با ارث‌بری و سبک‌های جدول دریافت می‌کند.

--------------------

> ```
> این مثال نحوه دریافت قالب پرکن مؤثر برای بخش‌های مختلف منطق جدول را نشان می‌دهد.
>  لطفاً توجه داشته باشید که قالب‌بندی سلول همواره اولویت بالاتری نسبت به قالب‌بندی ردیف دارد، ردیف بالاتر از ستون، ستون بالاتر از کل جدول.
>  در نهایت ویژگی‌های CellFormatEffectiveData همیشه برای رسم جدول استفاده می‌شوند. کد زیر فقط یک مثال از API است.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>      ITable tbl = (Table)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IFillFormatEffectiveData tableFillFormatEffective = tbl.getTableFormat().getEffective().getFillFormat();
>      IFillFormatEffectiveData rowFillFormatEffective = tbl.getRows().get_Item(0).getRowFormat().getEffective().getFillFormat();
>      IFillFormatEffectiveData columnFillFormatEffective = tbl.getColumns().get_Item(0).getColumnFormat().getEffective().getFillFormat();
>      IFillFormatEffectiveData cellFillFormatEffective = tbl.get_Item(0, 0).getCellFormat().getEffective().getFillFormat();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**بازگشت:**
[ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata) - A [ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata).
### getVersion() {#getVersion--}
```
public final long getVersion()
```

نسخه. فقط-خواندنی long.

**بازگشت:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

والد IPresentationComponent را بازمی‌گرداند. فقط-خواندنی [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**بازگشت:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)