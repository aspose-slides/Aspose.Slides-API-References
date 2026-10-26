---
title: CellFormat
second_title: Referensi API Java Aspose.Slides untuk Android
description: Mewakili format sel tabel.
type: docs
url: /id/com.aspose.slides/cellformat/
---
**Warisan:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.ICellFormat](../../com.aspose.slides/icellformat)
```
public final class CellFormat extends PVIObject implements ICellFormat
```

Mewakili format sel tabel.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getFillFormat()](#getFillFormat--) | Mengembalikan objek properti isi sel. |
| [getBorderLeft()](#getBorderLeft--) | Mengembalikan objek properti garis batas kiri. |
| [getBorderTop()](#getBorderTop--) | Mengembalikan objek properti garis batas atas. |
| [getBorderRight()](#getBorderRight--) | Mengembalikan objek properti garis batas kanan. |
| [getBorderBottom()](#getBorderBottom--) | Mengembalikan objek properti garis batas bawah. |
| [getBorderDiagonalDown()](#getBorderDiagonalDown--) | Mengembalikan objek properti garis diagonal dari kiri-atas ke kanan-bawah. |
| [getBorderDiagonalUp()](#getBorderDiagonalUp--) | Mengembalikan objek properti garis diagonal dari kiri-bawah ke kanan-atas. |
| [getEffective()](#getEffective--) | Mendapatkan properti pemformatan sel tabel yang efektif dengan pewarisan dan gaya tabel yang diterapkan. |
| [getTransparency()](#getTransparency--) | Mendapatkan atau mengatur transparansi warna isi. |
| [setTransparency(float value)](#setTransparency-float-) | Mendapatkan atau mengatur transparansi warna isi. |
### getVersion() {#getVersion--}
```
public long getVersion()
```


Versi. Baca-saja long.

**Mengembalikan:**
long
### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```


Mengembalikan objek properti isi sel. Baca-saja [IFillFormat](../../com.aspose.slides/ifillformat).

**Mengembalikan:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getBorderLeft() {#getBorderLeft--}
```
public final ILineFormat getBorderLeft()
```


Mengembalikan objek properti garis batas kiri. Baca-saja [ILineFormat](../../com.aspose.slides/ilineformat).

**Mengembalikan:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderTop() {#getBorderTop--}
```
public final ILineFormat getBorderTop()
```


Mengembalikan objek properti garis batas atas. Baca-saja [ILineFormat](../../com.aspose.slides/ilineformat).

**Mengembalikan:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderRight() {#getBorderRight--}
```
public final ILineFormat getBorderRight()
```


Mengembalikan objek properti garis batas kanan. Baca-saja [ILineFormat](../../com.aspose.slides/ilineformat).

**Mengembalikan:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderBottom() {#getBorderBottom--}
```
public final ILineFormat getBorderBottom()
```


Mengembalikan objek properti garis batas bawah. Baca-saja [ILineFormat](../../com.aspose.slides/ilineformat).

**Mengembalikan:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderDiagonalDown() {#getBorderDiagonalDown--}
```
public final ILineFormat getBorderDiagonalDown()
```


Mengembalikan objek properti garis diagonal dari kiri-atas ke kanan-bawah. Baca-saja [ILineFormat](../../com.aspose.slides/ilineformat).

**Mengembalikan:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderDiagonalUp() {#getBorderDiagonalUp--}
```
public final ILineFormat getBorderDiagonalUp()
```


Mengembalikan objek properti garis diagonal dari kiri-bawah ke kanan-atas. Baca-saja [ILineFormat](../../com.aspose.slides/ilineformat).

**Mengembalikan:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getEffective() {#getEffective--}
```
public final ICellFormatEffectiveData getEffective()
```


Mendapatkan properti pemformatan sel tabel yang efektif dengan pewarisan dan gaya tabel yang diterapkan.

--------------------

> ```
> This example demonstrates getting effective fill format for different table logic parts.
>  Please note that cell formatting always has higher priority than row formatting, row - higher than column, column - higher that whole table.
>  So finally CellFormatEffectiveData properties always used to draw the table. The following code is just an example of API.
>  
>  Presentation pres = new Presentation(@"MyPresentation.pptx");
>  try
>  {
>      ITable tbl = (ITable) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IFillFormatEffectiveData tableFillFormatEffective = tbl.getTableFormat().getEffective().getFillFormat();
>      IFillFormatEffectiveData rowFillFormatEffective = tbl.getRows().get_Item(0).RowFormat.GetEffective().getFillFormat();
>      IFillFormatEffectiveData columnFillFormatEffective = tbl.getColumns().get_Item(0).getColumnFormat().getEffective().getFillFormat();
>      IFillFormatEffectiveData cellFillFormatEffective = tbl.get_Item(0, 0).getCellFormat().getEffective().getFillFormat();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Mengembalikan:**
[ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata) - A [ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata).
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