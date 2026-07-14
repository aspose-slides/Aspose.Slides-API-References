---
title: ColumnFormat
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایانگر فرمت یک ستون جدول است.
type: docs
url: /fa/com.aspose.slides/columnformat/
---
**ارث‌بری:**
java.lang.Object, com.aspose.slides.DomObject

**تمام اینترفیس‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IColumnFormat](../../com.aspose.slides/icolumnformat), com.aspose.slides.IPVIObject
```
public final class ColumnFormat extends DomObject<Column> implements IColumnFormat, IPVIObject
```

نمایانگر فرمت یک ستون جدول است.
## متدها

| متد | توضیح |
| --- | --- |
| [getEffective()](#getEffective--) | ویژگی‌های فرمت مؤثر ستون جدول را با درنظر گرفتن وراثت و سبک‌های جدول دریافت می‌کند. |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
### getEffective() {#getEffective--}
```
public final IColumnFormatEffectiveData getEffective()
```


ویژگی‌های فرمت مؤثر ستون جدول را با درنظر گرفتن وراثت و سبک‌های جدول دریافت می‌کند.

--------------------

> ```
> این مثال نحوه دریافت فرمت پر شدن مؤثر برای بخش‌های مختلف منطق جدول را نشان می‌دهد.
>  لطفاً توجه داشته باشید که قالب‌بندی سلول همیشه اولویت بالاتری نسبت به قالب‌بندی سطر دارد، سطر بالاتر از ستون، ستون بالاتر از کل جدول.
>  در نهایت ویژگی‌های CellFormatEffectiveData همیشه برای رسم جدول استفاده می‌شوند. کد زیر فقط یک مثال از API است.
>  

>  Presentation pres = new Presentation(@"MyPresentation.pptx");
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


**بازمی‌گرداند:**
[IColumnFormatEffectiveData](../../com.aspose.slides/icolumnformateffectivedata) - یک [IColumnFormatEffectiveData](../../com.aspose.slides/icolumnformateffectivedata).
### getVersion() {#getVersion--}
```
public final long getVersion()
```


نسخه. فقط‌خواندنی long.

**بازمی‌گرداند:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```


والد IPresentationComponent را بازمی‌گرداند. فقط‌خواندنی [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**بازمی‌گرداند:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)