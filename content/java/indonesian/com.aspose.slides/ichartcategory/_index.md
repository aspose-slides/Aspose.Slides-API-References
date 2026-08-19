---
title: IChartCategory
second_title: Aspose.Slides for Java API Reference
description: Mewakili kategori diagram.
type: docs
url: /id/com.aspose.slides/ichartcategory/
---```
public interface IChartCategory
```

Mewakili kategori diagram.
## Metode

| Method | Description |
| --- | --- |
| [getUseCell()](#getUseCell--) | Jika true maka properti AsCell sebenarnya. |
| [getAsCell()](#getAsCell--) | Mengembalikan atau mengatur objek IChartDataCell. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | Mengembalikan atau mengatur objek IChartDataCell. |
| [getAsLiteral()](#getAsLiteral--) | Mengembalikan atau mengatur AsLiteral jika UseCell false. |
| [setAsLiteral(Object value)](#setAsLiteral-java.lang.Object-) | Mengembalikan atau mengatur AsLiteral jika UseCell false. |
| [getValue()](#getValue--) | Jika UseCell true maka properti ini mewakili properti AsCell.Value. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Jika UseCell true maka properti ini mewakili properti AsCell.Value. |
| [getGroupingLevels()](#getGroupingLevels--) | Kontainer terkelola dari nilai-nilai level pengelompokan kategori diagram. |
| [remove()](#remove--) | Menghapus kategori dari diagram. |
### getUseCell() {#getUseCell--}
```
public abstract boolean getUseCell()
```

Jika true maka properti AsCell sebenarnya. Dengan kata lain, worksheet digunakan untuk menyimpan kategori (kasus ini mendukung kategori multi-level). Jika false maka properti AsLiteral sebenarnya. Dengan kata lain, worksheet TIDAK digunakan untuk menyimpan kategori (dan kasus ini tidak mendukung kategori multi-level). Read-only boolean.

--------------------

Untuk mengubah nilai properti ini (untuk semua kategori dalam koleksi) setel nilai baru ke properti [ChartCategoryCollection.getUseCells()](../../com.aspose.slides/chartcategorycollection\#getUseCells--).

**Mengembalikan:**
boolean
### getAsCell() {#getAsCell--}
```
public abstract IChartDataCell getAsCell()
```

Mengembalikan atau mengatur objek IChartDataCell. Jika kategori multi-level maka objek IChartDataCell yang digunakan untuk level "0". Read/write [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Mengembalikan:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setAsCell(IChartDataCell value)
```

Mengembalikan atau mengatur objek IChartDataCell. Jika kategori multi-level maka objek IChartDataCell yang digunakan untuk level "0". Read/write [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getAsLiteral() {#getAsLiteral--}
```
public abstract Object getAsLiteral()
```

Mengembalikan atau mengatur AsLiteral jika UseCell false. Read/write Object.

**Mengembalikan:**
java.lang.Object
### setAsLiteral(Object value) {#setAsLiteral-java.lang.Object-}
```
public abstract void setAsLiteral(Object value)
```

Mengembalikan atau mengatur AsLiteral jika UseCell false. Read/write Object.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.Object |  |

### getValue() {#getValue--}
```
public abstract Object getValue()
```

Jika UseCell true maka properti ini mewakili properti AsCell.Value. Jika UseCell false maka properti ini mewakili properti AsLiteral. Read/write Object.

**Mengembalikan:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```

Jika UseCell true maka properti ini mewakili properti AsCell.Value. Jika UseCell false maka properti ini mewakili properti AsLiteral. Read/write Object.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.Object |  |

### getGroupingLevels() {#getGroupingLevels--}
```
public abstract IChartCategoryLevelsManager getGroupingLevels()
```

Kontainer terkelola dari nilai-nilai level pengelompokan kategori diagram. Kategori multi-level berisi lebih dari satu level pengelompokan. Pengindeksan level pengelompokan berbasis nol. Read-only [IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager).

**Mengembalikan:**
[IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager)
### remove() {#remove--}
```
public abstract void remove()
```

Menghapus kategori dari diagram.