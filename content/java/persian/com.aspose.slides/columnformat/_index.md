---
title: ColumnFormat
second_title: Aspose.Slides برای مرجع API جاوا
description: قالب یک ستون جدول را نشان می‌دهد.
type: docs
url: /fa/com.aspose.slides/columnformat/
---
**ارث‌بری:**  
java.lang.Object, com.aspose.slides.DomObject

**همه رابط‌های پیاده‌سازی شده:**  
[com.aspose.slides.IColumnFormat](../../com.aspose.slides/icolumnformat), com.aspose.slides.IPVIObject  
```
public final class ColumnFormat extends DomObject<Column> implements IColumnFormat, IPVIObject
```

فرمت ستون جدول را نشان می‌دهد.

## متدها

| متد | توضیح |
| --- | --- |
| [getEffective()](#getEffective--) | خصوصیات فرمت مؤثر ستون جدول را با ارث‌بری و اعمال سبک‌های جدول دریافت می‌کند. |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |

### getEffective() {#getEffective--}
```
public final IColumnFormatEffectiveData getEffective()
```

خصوصیات فرمت مؤثر ستون جدول را با ارث‌بری و اعمال سبک‌های جدول دریافت می‌کند.

--------------------

> ```
> This example demonstrates getting effective fill format for different table logic parts.
>  Please note that cell formatting always has higher priority than row formatting, row - higher than column, column - higher that whole table.
>  So finally CellFormatEffectiveData properties always used to draw the table. The following code is just an example of API.
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


**بازگشت:**  
[IColumnFormatEffectiveData](../../com.aspose.slides/icolumnformateffectivedata) - یک [IColumnFormatEffectiveData](../../com.aspose.slides/icolumnformateffectivedata).

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

والد IPresentationComponent را باز می‌گرداند. فقط-خواندنی [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**بازگشت:**  
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)