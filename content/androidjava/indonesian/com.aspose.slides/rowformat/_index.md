---
title: RowFormat
second_title: Referensi API Java Aspose.Slides untuk Android
description: Mewakili format baris tabel.
type: docs
url: /id/com.aspose.slides/rowformat/
---
**Warisan:**
java.lang.Object, com.aspose.slides.DomObject

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IRowFormat](../../com.aspose.slides/irowformat), com.aspose.slides.IPVIObject
```
public final class RowFormat extends DomObject<Row> implements IRowFormat, IPVIObject
```

Mewakili format baris tabel.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getEffective()](#getEffective--) | Mendapatkan properti pemformatan baris tabel yang efektif dengan pewarisan dan gaya tabel yang diterapkan. |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
### getEffective() {#getEffective--}
```
public final IRowFormatEffectiveData getEffective()
```


Mendapatkan properti pemformatan baris tabel yang efektif dengan pewarisan dan gaya tabel yang diterapkan.

--------------------

> ```
> Contoh ini menunjukkan cara mendapatkan format isi efektif untuk bagian logika tabel yang berbeda.
>  Harap catat bahwa format sel selalu memiliki prioritas lebih tinggi daripada format baris, baris - lebih tinggi daripada kolom, kolom - lebih tinggi daripada seluruh tabel.
>  Jadi akhirnya properti CellFormatEffectiveData selalu digunakan untuk menggambar tabel. Kode berikut hanya contoh penggunaan API.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>      ITable tbl = (ITable)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IFillFormatEffectiveData tableFillFormatEffective = tbl.getTableFormat().getEffective().getFillFormat();
>      IFillFormatEffectiveData rowFillFormatEffective = tbl.getRows().get_Item(0).getRowFormat().getEffective().getFillFormat();
>      IFillFormatEffectiveData columnFillFormatEffective = tbl.getColumns().get_Item(0).getColumnFormat().getEffective().getFillFormat();
>      IFillFormatEffectiveData cellFillFormatEffective = tbl.get_Item(0, 0).getCellFormat().getEffective().getFillFormat();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Mengembalikan:**
[IRowFormatEffectiveData](../../com.aspose.slides/irowformateffectivedata) - sebuah [IRowFormatEffectiveData](../../com.aspose.slides/irowformateffectivedata).
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