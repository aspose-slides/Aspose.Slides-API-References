---
title: ColumnFormat
second_title: Aspose.Slides لنظام Android عبر مرجع API Java
description: يمثل تنسيق عمود الجدول.
type: docs
url: /ar/com.aspose.slides/columnformat/
---
**الوراثة:**
java.lang.Object, com.aspose.slides.DomObject

**جميع الواجهات المنفذة:**
[com.aspose.slides.IColumnFormat](../../com.aspose.slides/icolumnformat), com.aspose.slides.IPVIObject
```
public final class ColumnFormat extends DomObject<Column> implements IColumnFormat, IPVIObject
```

يمثل تنسيق عمود الجدول.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getEffective()](#getEffective--) | يحصل على خصائص تنسيق عمود الجدول الفعّالة مع تطبيق الوراثة وأنماط الجدول. |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
### getEffective() {#getEffective--}
```
public final IColumnFormatEffectiveData getEffective()
```


يحصل على خصائص تنسيق عمود الجدول الفعّالة مع تطبيق الوراثة وأنماط الجدول.

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


**الإرجاع:**
[IColumnFormatEffectiveData](../../com.aspose.slides/icolumnformateffectivedata) - [IColumnFormatEffectiveData](../../com.aspose.slides/icolumnformateffectivedata).
### getVersion() {#getVersion--}
```
public final long getVersion()
```


الإصدار. للقراءة فقط من النوع long.

**الإرجاع:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```


يعيد العنصر الأصل IPresentationComponent. للقراءة فقط [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**الإرجاع:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)