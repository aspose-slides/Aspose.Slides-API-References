---
title: Cell
second_title: Referensi API Aspose.Slides untuk Java
description: Mewakili sebuah sel dalam tabel.
type: docs
url: /id/com.aspose.slides/cell/
---
**Pewarisan:**
java.lang.Object

**Semua Antarmuka yang Diimplementasikan:**
com.aspose.slides.IDOMObject, [com.aspose.slides.ICell](../../com.aspose.slides/icell)
```
public class Cell implements IDOMObject, ICell
```

Mewakili sel dari sebuah tabel.
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
| [getAnchorCenter()](#getAnchorCenter--) | Menentukan apakah kotak teks berada di tengah sel atau tidak. |
| [setAnchorCenter(boolean value)](#setAnchorCenter-boolean-) | Menentukan apakah kotak teks berada di tengah sel atau tidak. |
| [getFirstRow()](#getFirstRow--) | Mendapatkan baris pertama sel. |
| [getFirstColumn()](#getFirstColumn--) | Mendapatkan kolom pertama sel. |
| [getColSpan()](#getColSpan--) | Mengembalikan jumlah kolom grid pada tabel induk yang akan diisi oleh sel saat ini. |
| [getRowSpan()](#getRowSpan--) | Mengembalikan jumlah baris yang dicakup oleh sel yang digabung. |
| [getTextFrame()](#getTextFrame--) | Mengembalikan kerangka teks sel. |
| [getTable()](#getTable--) | Mengembalikan objek Table induk untuk sebuah sel. |
| [isMergedCell()](#isMergedCell--) | Mengembalikan true jika sel digabung dengan sel lain, false jika tidak. |
| [getCellFormat()](#getCellFormat--) | Mengembalikan objek CellFormat yang berisi properti pemformatan untuk sel ini. |
| [splitByColSpan(int index)](#splitByColSpan-int-) | Membagi sel menjadi dua sel berdasarkan indeks kolom. |
| [splitByRowSpan(int index)](#splitByRowSpan-int-) | Membagi sel menjadi dua sel berdasarkan indeks baris. |
| [splitByHeight(double height)](#splitByHeight-double-) | Membagi sel berdasarkan tinggi. |
| [splitByWidth(double width)](#splitByWidth-double-) | Membagi sel berdasarkan lebar. |
| [getSlide()](#getSlide--) | Mengembalikan slide induk dari sebuah sel. |
| [getPresentation()](#getPresentation--) | Mengembalikan presentasi induk dari sebuah sel. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getOffsetX() {#getOffsetX--}
```
public final double getOffsetX()
```

Mengembalikan jarak dari sisi kiri tabel ke sisi kiri sel. Baca-saja double.

**Mengembalikan:**
double
### getOffsetY() {#getOffsetY--}
```
public final double getOffsetY()
```

Mengembalikan jarak dari sisi atas tabel ke sisi atas sel. Baca-saja double.

**Mengembalikan:**
double
### getFirstRowIndex() {#getFirstRowIndex--}
```
public final int getFirstRowIndex()
```

Mengembalikan indeks baris pertama yang dicakup oleh sel. Baca-saja int.

**Mengembalikan:**
int
### getFirstColumnIndex() {#getFirstColumnIndex--}
```
public final int getFirstColumnIndex()
```

Mengembalikan indeks kolom pertama yang dicakup oleh sel. Baca-saja int.

**Mengembalikan:**
int
### getWidth() {#getWidth--}
```
public final double getWidth()
```

Mengembalikan lebar sel. Baca-saja double.

**Mengembalikan:**
double
### getHeight() {#getHeight--}
```
public final double getHeight()
```

Mengembalikan tinggi sel. Baca-saja double.

**Mengembalikan:**
double
### getMinimalHeight() {#getMinimalHeight--}
```
public final double getMinimalHeight()
```

Mengembalikan tinggi minimum sel. Ini adalah jumlah tinggi minimum semua baris yang dicakup oleh sel. Baca-saja double.

**Mengembalikan:**
double
### getMarginLeft() {#getMarginLeft--}
```
public final double getMarginLeft()
```

Mengembalikan atau mengatur margin kiri dalam TextFrame. Baca/tulis double.

**Mengembalikan:**
double
### setMarginLeft(double value) {#setMarginLeft-double-}
```
public final void setMarginLeft(double value)
```

Mengembalikan atau mengatur margin kiri dalam TextFrame. Baca/tulis double.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | double |  |
### getMarginRight() {#getMarginRight--}
```
public final double getMarginRight()
```

Mengembalikan atau mengatur margin kanan dalam TextFrame. Baca/tulis double.

**Mengembalikan:**
double
### setMarginRight(double value) {#setMarginRight-double-}
```
public final void setMarginRight(double value)
```

Mengembalikan atau mengatur margin kanan dalam TextFrame. Baca/tulis double.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | double |  |
### getMarginTop() {#getMarginTop--}
```
public final double getMarginTop()
```

Mengembalikan atau mengatur margin atas dalam TextFrame. Baca/tulis double.

**Mengembalikan:**
double
### setMarginTop(double value) {#setMarginTop-double-}
```
public final void setMarginTop(double value)
```

Mengembalikan atau mengatur margin atas dalam TextFrame. Baca/tulis double.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | double |  |
### getMarginBottom() {#getMarginBottom--}
```
public final double getMarginBottom()
```

Mengembalikan atau mengatur margin bawah dalam TextFrame. Baca/tulis double.

**Mengembalikan:**
double
### setMarginBottom(double value) {#setMarginBottom-double-}
```
public final void setMarginBottom(double value)
```

Mengembalikan atau mengatur margin bawah dalam TextFrame. Baca/tulis double.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | double |  |
### getTextVerticalType() {#getTextVerticalType--}
```
public final byte getTextVerticalType()
```

Mengembalikan atau mengatur tipe teks vertikal. Baca/tulis [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Mengembalikan:**
byte
### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public final void setTextVerticalType(byte value)
```

Mengembalikan atau mengatur tipe teks vertikal. Baca/tulis [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | byte |  |
### getTextAnchorType() {#getTextAnchorType--}
```
public final byte getTextAnchorType()
```

Mengembalikan atau mengatur tipe jangkar teks. Baca/tulis [TextAnchorType](../../com.aspose.slides/textanchortype).

**Mengembalikan:**
byte
### setTextAnchorType(byte value) {#setTextAnchorType-byte-}
```
public final void setTextAnchorType(byte value)
```

Mengembalikan atau mengatur tipe jangkar teks. Baca/tulis [TextAnchorType](../../com.aspose.slides/textanchortype).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | byte |  |
### getAnchorCenter() {#getAnchorCenter--}
```
public final boolean getAnchorCenter()
```

Menentukan apakah kotak teks berada di tengah sel atau tidak. Baca/tulis boolean.

**Mengembalikan:**
boolean
### setAnchorCenter(boolean value) {#setAnchorCenter-boolean-}
```
public final void setAnchorCenter(boolean value)
```

Menentukan apakah kotak teks berada di tengah sel atau tidak. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |
### getFirstRow() {#getFirstRow--}
```
public final IRow getFirstRow()
```

Mendapatkan baris pertama sel. Baca-saja [IRow](../../com.aspose.slides/irow).

**Mengembalikan:**
[IRow](../../com.aspose.slides/irow)
### getFirstColumn() {#getFirstColumn--}
```
public final IColumn getFirstColumn()
```

Mendapatkan kolom pertama sel. Baca-saja [IColumn](../../com.aspose.slides/icolumn).

**Mengembalikan:**
[IColumn](../../com.aspose.slides/icolumn)
### getColSpan() {#getColSpan--}
```
public final int getColSpan()
```

Mengembalikan jumlah kolom grid pada tabel induk yang akan diisi oleh sel saat ini. Properti ini memungkinkan sel tampak digabung karena melintasi batas vertikal sel lain dalam tabel. Baca-saja int.

**Mengembalikan:**
int
### getRowSpan() {#getRowSpan--}
```
public final int getRowSpan()
```

Mengembalikan jumlah baris yang dicakup oleh sel yang digabung. Properti ini digunakan bersama atribut vMerge pada sel lain untuk menentukan sel awal penggabungan horizontal. Baca-saja int.

**Mengembalikan:**
int
### getTextFrame() {#getTextFrame--}
```
public final ITextFrame getTextFrame()
```

Mengembalikan kerangka teks sel. Baca-saja [ITextFrame](../../com.aspose.slides/itextframe).

**Mengembalikan:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getTable() {#getTable--}
```
public final ITable getTable()
```

Mengembalikan objek Table induk untuk sebuah sel. Baca-saja [ITable](../../com.aspose.slides/itable).

**Mengembalikan:**
[ITable](../../com.aspose.slides/itable)
### isMergedCell() {#isMergedCell--}
```
public final boolean isMergedCell()
```

Mengembalikan true jika sel digabung dengan sel lain, false jika tidak. Baca-saja boolean.

**Mengembalikan:**
boolean
### getCellFormat() {#getCellFormat--}
```
public final ICellFormat getCellFormat()
```

Mengembalikan objek CellFormat yang berisi properti pemformatan untuk sel ini. Baca-saja [ICellFormat](../../com.aspose.slides/icellformat).

**Mengembalikan:**
[ICellFormat](../../com.aspose.slides/icellformat)
### splitByColSpan(int index) {#splitByColSpan-int-}
```
public final void splitByColSpan(int index)
```

Membagi sel menjadi dua sel berdasarkan indeks kolom.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks kolom. |
### splitByRowSpan(int index) {#splitByRowSpan-int-}
```
public final void splitByRowSpan(int index)
```

Membagi sel menjadi dua sel berdasarkan indeks baris.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks baris. |
### splitByHeight(double height) {#splitByHeight-double-}
```
public final void splitByHeight(double height)
```

Membagi sel berdasarkan tinggi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| height | double | Tinggi baris. |
### splitByWidth(double width) {#splitByWidth-double-}
```
public final void splitByWidth(double width)
```

Membagi sel berdasarkan lebar.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| width | double | Lebar kolom. |
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Mengembalikan slide induk dari sebuah sel. Baca-saja [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Mengembalikan:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Mengembalikan presentasi induk dari sebuah sel. Baca-saja [IPresentation](../../com.aspose.slides/ipresentation).

**Mengembalikan:**
[IPresentation](../../com.aspose.slides/ipresentation)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Mengembalikan objek Parent_Immediate. Baca-saja IDOMObject.

**Mengembalikan:**
com.aspose.slides.IDOMObject