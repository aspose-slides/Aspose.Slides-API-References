---
title: ColumnFormat
second_title: Aspose.Slides untuk Android via Referensi API Java
description: Mewakili format kolom tabel.
type: docs
url: /id/com.aspose.slides/columnformat/
---
**Pewarisan:**
java.lang.Object, com.aspose.slides.DomObject

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IColumnFormat](../../com.aspose.slides/icolumnformat), com.aspose.slides.IPVIObject
```
public final class ColumnFormat extends DomObject<Column> implements IColumnFormat, IPVIObject
```

Mewakili format kolom tabel.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getEffective()](#getEffective--) | Mendapatkan properti pemformatan kolom tabel yang efektif dengan pewarisan dan gaya tabel yang diterapkan. |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
### getEffective() {#getEffective--}
```
public final IColumnFormatEffectiveData getEffective()
```


Mendapatkan properti pemformatan kolom tabel yang efektif dengan pewarisan dan gaya tabel yang diterapkan.

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


**Mengembalikan:**
[IColumnFormatEffectiveData](../../com.aspose.slides/icolumnformateffectivedata) - sebuah [IColumnFormatEffectiveData](../../com.aspose.slides/icolumnformateffectivedata).
### getVersion() {#getVersion--}
```
public final long getVersion()
```


Versi. Hanya-baca long.

**Mengembalikan:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```


Mengembalikan induk IPresentationComponent. Hanya-baca [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Mengembalikan:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)