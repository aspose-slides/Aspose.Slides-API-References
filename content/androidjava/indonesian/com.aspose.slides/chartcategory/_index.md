---
title: ChartCategory
second_title: Aspose.Slides untuk Android melalui Referensi API Java
description: Mewakili kategori chart.
type: docs
url: /id/com.aspose.slides/chartcategory/
---
**Pewarisan:**
java.lang.Object

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IChartCategory](../../com.aspose.slides/ichartcategory), com.aspose.slides.IDOMObject
```
public class ChartCategory implements IChartCategory, IDOMObject
```

Mewakili kategori chart.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getUseCell()](#getUseCell--) | Jika true maka properti AsCell aktual. |
| [getAsCell()](#getAsCell--) | Mengembalikan atau mengatur objek IChartDataCell. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | Mengembalikan atau mengatur objek IChartDataCell. |
| [getAsLiteral()](#getAsLiteral--) | Mengembalikan atau mengatur objek AsLiteral. |
| [setAsLiteral(Object value)](#setAsLiteral-java.lang.Object-) | Mengembalikan atau mengatur objek AsLiteral. |
| [getValue()](#getValue--) | Jika UseCell bernilai true maka properti ini mewakili properti AsCell.Value. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Jika UseCell bernilai true maka properti ini mewakili properti AsCell.Value. |
| [getGroupingLevels()](#getGroupingLevels--) | Kontainer terkelola nilai level pengelompokan kategori chart. |
| [remove()](#remove--) | Menghapus kategori dari chart. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getUseCell() {#getUseCell--}
```
public final boolean getUseCell()
```

Jika true maka properti AsCell aktual. Dengan kata lain, worksheet digunakan untuk menyimpan kategori (kasus ini mendukung kategori multi-level). Jika false maka properti AsLiteral aktual. Dengan kata lain, worksheet TIDAK digunakan untuk menyimpan kategori (dan kasus ini tidak mendukung kategori multi-level). Boolean baca-saja.

Untuk mengubah nilai properti ini (untuk semua kategori dalam koleksi) setel nilai baru ke ChartCategoryCollection.UseCells property.

**Mengembalikan:**
boolean
### getAsCell() {#getAsCell--}
```
public final IChartDataCell getAsCell()
```

Mengembalikan atau mengatur objek IChartDataCell. Jika kategori multi-level maka IChartDataCell yang digunakan untuk level "0". Baca/tulis [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Mengembalikan:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public final void setAsCell(IChartDataCell value)
```

Mengembalikan atau mengatur objek IChartDataCell. Jika kategori multi-level maka IChartDataCell yang digunakan untuk level "0". Baca/tulis [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |
### getAsLiteral() {#getAsLiteral--}
```
public final Object getAsLiteral()
```

Mengembalikan atau mengatur objek AsLiteral. Baca/tulis Object.

**Mengembalikan:**
java.lang.Object
### setAsLiteral(Object value) {#setAsLiteral-java.lang.Object-}
```
public final void setAsLiteral(Object value)
```

Mengembalikan atau mengatur objek AsLiteral. Baca/tulis Object.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.Object |  |
### getValue() {#getValue--}
```
public final Object getValue()
```

Jika UseCell bernilai true maka properti ini mewakili properti AsCell.Value. Jika UseCell bernilai false maka properti ini mewakili properti AsLiteral. Baca/tulis Object.

**Mengembalikan:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```

Jika UseCell bernilai true maka properti ini mewakili properti AsCell.Value. Jika UseCell bernilai false maka properti ini mewakili properti AsLiteral. Baca/tulis Object.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.Object |  |
### getGroupingLevels() {#getGroupingLevels--}
```
public final IChartCategoryLevelsManager getGroupingLevels()
```

Kontainer terkelola nilai level pengelompokan kategori chart. Kategori multi-level mengandung lebih dari satu level pengelompokan. Pengindeksan level pengelompokan berbasis nol. Baca-saja [IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager).

**Mengembalikan:**
[IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager)
### remove() {#remove--}
```
public final void remove()
```

Menghapus kategori dari chart.

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Mengembalikan objek Parent_Immediate. Baca-saja IDOMObject.

**Mengembalikan:**
com.aspose.slides.IDOMObject