---
title: ICell
second_title: Referensi API Java Aspose.Slides untuk Android
description: Mewakili sebuah sel dalam tabel.
type: docs
url: /id/com.aspose.slides/icell/
---
**All Implemented Interfaces:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface ICell extends ISlideComponent
```

Mewakili sebuah sel dalam tabel.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getOffsetX()](#getOffsetX--) | Mengembalikan jarak dari sisi kiri tabel ke sisi kiri sel. |
| [getOffsetY()](#getOffsetY--) | Mengembalikan jarak dari sisi atas tabel ke sisi atas sel. |
| [getFirstRowIndex()](#getFirstRowIndex--) | Mengembalikan indeks baris pertama yang dicakup oleh sel. |
| [getFirstColumnIndex()](#getFirstColumnIndex--) | Mengembalikan indeks kolom pertama yang dicakup oleh sel. |
| [getWidth()](#getWidth--) | Mengembalikan lebar sel. |
| [getHeight()](#getHeight--) | Mengembalikan tinggi sel. |
| [getMinimalHeight()](#getMinimalHeight--) | Mengembalikan tinggi minimum sel. |
| [getMarginLeft()](#getMarginLeft--) | Mengembalikan atau mengatur margin kiri dalam TextFrame. |
| [setMarginLeft(double value)](#setMarginLeft-double-) | Mengembalikan atau mengatur margin kiri dalam TextFrame. |
| [getMarginRight()](#getMarginRight--) | Mengembalikan atau mengatur margin kanan dalam TextFrame. |
| [setMarginRight(double value)](#setMarginRight-double-) | Mengembalikan atau mengatur margin kanan dalam TextFrame. |
| [getMarginTop()](#getMarginTop--) | Mengembalikan atau mengatur margin atas dalam TextFrame. |
| [setMarginTop(double value)](#setMarginTop-double-) | Mengembalikan atau mengatur margin atas dalam TextFrame. |
| [getMarginBottom()](#getMarginBottom--) | Mengembalikan atau mengatur margin bawah dalam TextFrame. |
| [setMarginBottom(double value)](#setMarginBottom-double-) | Mengembalikan atau mengatur margin bawah dalam TextFrame. |
| [getTextVerticalType()](#getTextVerticalType--) | Mengembalikan atau mengatur tipe teks vertikal. |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | Mengembalikan atau mengatur tipe teks vertikal. |
| [getTextAnchorType()](#getTextAnchorType--) | Mengembalikan atau mengatur tipe jangkar teks. |
| [setTextAnchorType(byte value)](#setTextAnchorType-byte-) | Mengembalikan atau mengatur tipe jangkar teks. |
| [getAnchorCenter()](#getAnchorCenter--) | Menentukan apakah kotak teks dipusatkan di dalam sel atau tidak. |
| [setAnchorCenter(boolean value)](#setAnchorCenter-boolean-) | Menentukan apakah kotak teks dipusatkan di dalam sel atau tidak. |
| [getFirstColumn()](#getFirstColumn--) | Mendapatkan kolom pertama sel. |
| [getFirstRow()](#getFirstRow--) | Mendapatkan baris pertama sel. |
| [getColSpan()](#getColSpan--) | Mengembalikan jumlah kolom kisi pada tabel induk yang akan dicakup oleh sel saat ini. |
| [getRowSpan()](#getRowSpan--) | Mengembalikan jumlah baris yang dicakup oleh sel yang digabung. |
| [getTextFrame()](#getTextFrame--) | Mengembalikan frame teks sel. |
| [getTable()](#getTable--) | Mengembalikan objek Table induk untuk sel. |
| [isMergedCell()](#isMergedCell--) | Mengembalikan true jika sel digabung dengan sel lain yang disesuaikan, false jika tidak. |
| [getCellFormat()](#getCellFormat--) | Mengembalikan objek CellFormat yang berisi properti pemformatan untuk sel ini. |
| [splitByColSpan(int index)](#splitByColSpan-int-) | Membagi sel menjadi dua sel berdasarkan indeks kolom. |
| [splitByRowSpan(int index)](#splitByRowSpan-int-) | Membagi sel menjadi dua sel berdasarkan indeks baris. |
| [splitByHeight(double height)](#splitByHeight-double-) | Membagi sel berdasarkan tinggi. |
| [splitByWidth(double width)](#splitByWidth-double-) | Membagi sel berdasarkan lebar. |
### getOffsetX() {#getOffsetX--}
```
public abstract double getOffsetX()
```

Mengembalikan jarak dari sisi kiri tabel ke sisi kiri sel. Hanya-baca double.

**Mengembalikan:**
double
### getOffsetY() {#getOffsetY--}
```
public abstract double getOffsetY()
```

Mengembalikan jarak dari sisi atas tabel ke sisi atas sel. Hanya-baca double.

**Mengembalikan:**
double
### getFirstRowIndex() {#getFirstRowIndex--}
```
public abstract int getFirstRowIndex()
```

Mengembalikan indeks baris pertama yang dicakup oleh sel. Hanya-baca int.

**Mengembalikan:**
int
### getFirstColumnIndex() {#getFirstColumnIndex--}
```
public abstract int getFirstColumnIndex()
```

Mengembalikan indeks kolom pertama yang dicakup oleh sel. Hanya-baca int.

**Mengembalikan:**
int
### getWidth() {#getWidth--}
```
public abstract double getWidth()
```

Mengembalikan lebar sel. Hanya-baca double.

**Mengembalikan:**
double
### getHeight() {#getHeight--}
```
public abstract double getHeight()
```

Mengembalikan tinggi sel. Hanya-baca double.

**Mengembalikan:**
double
### getMinimalHeight() {#getMinimalHeight--}
```
public abstract double getMinimalHeight()
```

Mengembalikan tinggi minimum sel. Ini merupakan jumlah tinggi minimum semua baris yang dicakup oleh sel. Hanya-baca double.

**Mengembalikan:**
double
### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```

Mengembalikan atau mengatur margin kiri dalam TextFrame. Baca/tulis double.

**Mengembalikan:**
double
### setMarginLeft(double value) {#setMarginLeft-double-}
```
public abstract void setMarginLeft(double value)
```

Mengembalikan atau mengatur margin kiri dalam TextFrame. Baca/tulis double.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | double |  |
### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```

Mengembalikan atau mengatur margin kanan dalam TextFrame. Baca/tulis double.

**Mengembalikan:**
double
### setMarginRight(double value) {#setMarginRight-double-}
```
public abstract void setMarginRight(double value)
```

Mengembalikan atau mengatur margin kanan dalam TextFrame. Baca/tulis double.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | double |  |
### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```

Mengembalikan atau mengatur margin atas dalam TextFrame. Baca/tulis double.

**Mengembalikan:**
double
### setMarginTop(double value) {#setMarginTop-double-}
```
public abstract void setMarginTop(double value)
```

Mengembalikan atau mengatur margin atas dalam TextFrame. Baca/tulis double.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | double |  |
### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```

Mengembalikan atau mengatur margin bawah dalam TextFrame. Baca/tulis double.

**Mengembalikan:**
double
### setMarginBottom(double value) {#setMarginBottom-double-}
```
public abstract void setMarginBottom(double value)
```

Mengembalikan atau mengatur margin bawah dalam TextFrame. Baca/tulis double.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | double |  |
### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```

Mengembalikan atau mengatur tipe teks vertikal. Baca/tulis [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Mengembalikan:**
byte
### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public abstract void setTextVerticalType(byte value)
```

Mengembalikan atau mengatur tipe teks vertikal. Baca/tulis [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | byte |  |
### getTextAnchorType() {#getTextAnchorType--}
```
public abstract byte getTextAnchorType()
```

Mengembalikan atau mengatur tipe jangkar teks. Baca/tulis [TextAnchorType](../../com.aspose.slides/textanchortype).

**Mengembalikan:**
byte
### setTextAnchorType(byte value) {#setTextAnchorType-byte-}
```
public abstract void setTextAnchorType(byte value)
```

Mengembalikan atau mengatur tipe jangkar teks. Baca/tulis [TextAnchorType](../../com.aspose.slides/textanchortype).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | byte |  |
### getAnchorCenter() {#getAnchorCenter--}
```
public abstract boolean getAnchorCenter()
```

Menentukan apakah kotak teks dipusatkan di dalam sel atau tidak. Baca/tulis boolean.

**Mengembalikan:**
boolean
### setAnchorCenter(boolean value) {#setAnchorCenter-boolean-}
```
public abstract void setAnchorCenter(boolean value)
```

Menentukan apakah kotak teks dipusatkan di dalam sel atau tidak. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |
### getFirstColumn() {#getFirstColumn--}
```
public abstract IColumn getFirstColumn()
```

Mendapatkan kolom pertama sel. Hanya-baca [IColumn](../../com.aspose.slides/icolumn).

**Mengembalikan:**
[IColumn](../../com.aspose.slides/icolumn)
### getFirstRow() {#getFirstRow--}
```
public abstract IRow getFirstRow()
```

Mendapatkan baris pertama sel. Hanya-baca [IRow](../../com.aspose.slides/irow).

**Mengembalikan:**
[IRow](../../com.aspose.slides/irow)
### getColSpan() {#getColSpan--}
```
public abstract int getColSpan()
```

Mengembalikan jumlah kolom kisi pada tabel induk yang akan dicakup oleh sel saat ini. Properti ini memungkinkan sel tampak digabung, karena mereka melintasi batas vertikal sel lain dalam tabel. Hanya-baca int.

**Mengembalikan:**
int
### getRowSpan() {#getRowSpan--}
```
public abstract int getRowSpan()
```

Mengembalikan jumlah baris yang dicakup oleh sel yang digabung. Ini digunakan bersama atribut vMerge pada sel lain untuk menentukan sel awal penggabungan horizontal. Hanya-baca int.

**Mengembalikan:**
int
### getTextFrame() {#getTextFrame--}
```
public abstract ITextFrame getTextFrame()
```

Mengembalikan frame teks sel. Hanya-baca [ITextFrame](../../com.aspose.slides/itextframe).

**Mengembalikan:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTable() {#getTable--}
```
public abstract ITable getTable()
```

Mengembalikan objek Table induk untuk sel. Hanya-baca [ITable](../../com.aspose.slides/itable).

**Mengembalikan:**
[ITable](../../com.aspose.slides/itable)
### isMergedCell() {#isMergedCell--}
```
public abstract boolean isMergedCell()
```

Mengembalikan true jika sel digabung dengan sel lain yang disesuaikan, false jika tidak. Hanya-baca boolean.

**Mengembalikan:**
boolean
### getCellFormat() {#getCellFormat--}
```
public abstract ICellFormat getCellFormat()
```

Mengembalikan objek CellFormat yang berisi properti pemformatan untuk sel ini. Hanya-baca [ICellFormat](../../com.aspose.slides/icellformat).

**Mengembalikan:**
[ICellFormat](../../com.aspose.slides/icellformat)
### splitByColSpan(int index) {#splitByColSpan-int-}
```
public abstract void splitByColSpan(int index)
```

Membagi sel menjadi dua sel berdasarkan indeks kolom.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks kolom. |
### splitByRowSpan(int index) {#splitByRowSpan-int-}
```
public abstract void splitByRowSpan(int index)
```

Membagi sel menjadi dua sel berdasarkan indeks baris.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks baris. |
### splitByHeight(double height) {#splitByHeight-double-}
```
public abstract void splitByHeight(double height)
```

Membagi sel berdasarkan tinggi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| height | double | Tinggi baris. |
### splitByWidth(double width) {#splitByWidth-double-}
```
public abstract void splitByWidth(double width)
```

Membagi sel berdasarkan lebar.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| width | double | Lebar kolom. |