---
title: IChartCategory
second_title: Aspose.Slides for Java API Reference
description: Mewakili kategori grafik.
type: docs
url: /id/com.aspose.slides/ichartcategory/
---```
public interface IChartCategory
```

Mewakili kategori grafik.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getUseCell()](#getUseCell--) | Jika true maka properti AsCell adalah yang aktual. |
| [getAsCell()](#getAsCell--) | Mengembalikan atau mengatur objek IChartDataCell. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | Mengembalikan atau mengatur objek IChartDataCell. |
| [getAsLiteral()](#getAsLiteral--) | Mengembalikan atau mengatur AsLiteral jika UseCell false. |
| [setAsLiteral(Object value)](#setAsLiteral-java.lang.Object-) | Mengembalikan atau mengatur AsLiteral jika UseCell false. |
| [getValue()](#getValue--) | Jika UseCell true maka properti ini mewakili properti AsCell.Value. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Jika UseCell true maka properti ini mewakili properti AsCell.Value. |
| [getCachedValue()](#getCachedValue--) | Mendapatkan nilai cache dari kategori grafik. |
| [getGroupingLevels()](#getGroupingLevels--) | Kontainer terkelola dari nilai-nilai tingkat pengelompokan kategori grafik. |
| [remove()](#remove--) | Menghapus kategori dari grafik. |
### getUseCell() {#getUseCell--}
```
public abstract boolean getUseCell()
```

Jika true maka properti AsCell adalah yang aktual. Dengan kata lain, worksheet digunakan untuk menyimpan kategori (kasus ini mendukung kategori multi-level). Jika false maka properti AsLiteral adalah yang aktual. Dengan kata lain, worksheet TIDAK digunakan untuk menyimpan kategori (dan kasus ini tidak mendukung kategori multi-level). Hanya-baca boolean.

--------------------

Untuk mengubah nilai properti ini (untuk semua kategori dalam koleksi) tetapkan nilai baru ke properti [ChartCategoryCollection.getUseCells()](../../com.aspose.slides/chartcategorycollection\#getUseCells--).

**Mengembalikan:**
boolean
### getAsCell() {#getAsCell--}
```
public abstract IChartDataCell getAsCell()
```

Mengembalikan atau mengatur objek IChartDataCell. Jika kategori multi-level maka IChartDataCell yang digunakan untuk level "0". Baca/tulis [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Mengembalikan:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setAsCell(IChartDataCell value)
```

Mengembalikan atau mengatur objek IChartDataCell. Jika kategori multi-level maka IChartDataCell yang digunakan untuk level "0". Baca/tulis [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getAsLiteral() {#getAsLiteral--}
```
public abstract Object getAsLiteral()
```

Mengembalikan atau mengatur AsLiteral jika UseCell false. Baca/tulis Object.

**Mengembalikan:**
java.lang.Object
### setAsLiteral(Object value) {#setAsLiteral-java.lang.Object-}
```
public abstract void setAsLiteral(Object value)
```

Mengembalikan atau mengatur AsLiteral jika UseCell false. Baca/tulis Object.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.Object |  |

### getValue() {#getValue--}
```
public abstract Object getValue()
```

Jika UseCell true maka properti ini mewakili properti AsCell.Value. Jika UseCell false maka properti ini mewakili properti AsLiteral. Baca/tulis Object.

**Mengembalikan:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```

Jika UseCell true maka properti ini mewakili properti AsCell.Value. Jika UseCell false maka properti ini mewakili properti AsLiteral. Baca/tulis Object.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.Object |  |

### getCachedValue() {#getCachedValue--}
```
public abstract ICachedChartValue getCachedValue()
```

Mendapatkan nilai cache dari kategori grafik. Hanya-baca [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
> 
>      // Cetak semua nilai kategori grafik yang di-cache.
>      for (IChartCategory category : chart.getChartData().getCategories())
>          System.out.println(category.getCachedValue().toString());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Mengembalikan:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
### getGroupingLevels() {#getGroupingLevels--}
```
public abstract IChartCategoryLevelsManager getGroupingLevels()
```

Kontainer terkelola dari nilai-nilai tingkat pengelompokan kategori grafik. Kategori multi-level berisi lebih dari satu tingkat pengelompokan. Pengindeksan tingkat pengelompokan berbasis nol. Hanya-baca [IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager).

**Mengembalikan:**
[IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager)
### remove() {#remove--}
```
public abstract void remove()
```

Menghapus kategori dari grafik.