---
title: TableFormat
second_title: Aspose.Slides untuk Android melalui Referensi API Java
description: Mewakili format tabel.
type: docs
url: /id/com.aspose.slides/tableformat/
---
**Warisan:**
java.lang.Object, com.aspose.slides.DomObject

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.ITableFormat](../../com.aspose.slides/itableformat), com.aspose.slides.IPVIObject
```
public final class TableFormat extends DomObject<Table> implements ITableFormat, IPVIObject
```

Mewakili format tabel.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | Mengembalikan objek properti isi tabel. |
| [getTransparency()](#getTransparency--) | Mendapatkan atau mengatur transparansi warna isi. |
| [setTransparency(float value)](#setTransparency-float-) | Mendapatkan atau mengatur transparansi warna isi. |
| [getEffective()](#getEffective--) | Mendapatkan properti pemformatan tabel yang efektif dengan pewarisan dan gaya tabel yang diterapkan. |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```


Mengembalikan objek properti isi tabel. Hanya-baca [IFillFormat](../../com.aspose.slides/ifillformat).

**Mengembalikan:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getTransparency() {#getTransparency--}
```
public final float getTransparency()
```


Mendapatkan atau mengatur transparansi warna isi. Baca/tulis  float .

**Mengembalikan:**
float
### setTransparency(float value) {#setTransparency-float-}
```
public final void setTransparency(float value)
```


Mendapatkan atau mengatur transparansi warna isi. Baca/tulis  float .

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float |  |
### getEffective() {#getEffective--}
```
public final ITableFormatEffectiveData getEffective()
```


Mendapatkan properti pemformatan tabel yang efektif dengan pewarisan dan gaya tabel yang diterapkan.

--------------------

> ```
> Contoh ini menunjukkan cara mendapatkan format isi efektif untuk bagian logika tabel yang berbeda.
>  Harap perhatikan bahwa pemformatan sel selalu memiliki prioritas lebih tinggi daripada pemformatan baris, baris - lebih tinggi daripada kolom, kolom - lebih tinggi daripada seluruh tabel.
>  Jadi akhirnya properti CellFormatEffectiveData selalu digunakan untuk menggambar tabel. Kode berikut hanya contoh penggunaan API.
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


**Mengembalikan:**
[ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata) - sebuah [ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata).
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


Mengembalikan IPresentationComponent induk. Hanya-baca [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Mengembalikan:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)