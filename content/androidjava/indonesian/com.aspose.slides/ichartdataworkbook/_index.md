---
title: IChartDataWorkbook
second_title: Aspose.Slides for Android via Java API Reference
description: Menyediakan akses ke buku kerja Excel yang tersemat
type: docs
url: /id/com.aspose.slides/ichartdataworkbook/
---```
public interface IChartDataWorkbook
```

Menyediakan akses ke buku kerja Excel yang tersemat
## Metode

| Metode | Deskripsi |
| --- | --- |
| [calculateFormulas()](#calculateFormulas--) | Menghitung semua formula dalam buku kerja dan memperbarui nilai sel yang sesuai. |
| [getCellCollection(String formula, boolean skipHiddenCells)](#getCellCollection-java.lang.String-boolean-) | Mendapatkan kumpulan sel. |
| [getCell(String worksheetName, int row, int column)](#getCell-java.lang.String-int-int-) | Mendapatkan sel yang dapat digunakan untuk seri atau kategori diagram |
| [getCell(int worksheetIndex, int row, int column)](#getCell-int-int-int-) | Mendapatkan sel yang dapat digunakan untuk seri atau kategori diagram |
| [getCell(int worksheetIndex, String cellName)](#getCell-int-java.lang.String-) | Mendapatkan sel yang dapat digunakan untuk seri atau kategori diagram |
| [getCell(int worksheetIndex, String cellName, Object value)](#getCell-int-java.lang.String-java.lang.Object-) | Mendapatkan sel yang dapat digunakan untuk seri atau kategori diagram |
| [getCell(int worksheetIndex, int row, int column, Object value)](#getCell-int-int-int-java.lang.Object-) | Mendapatkan sel yang dapat digunakan untuk seri atau kategori diagram |
| [clear(int sheetIndex)](#clear-int-) | Menghapus semua nilai sel pada lembar |
| [getWorksheets()](#getWorksheets--) | Mendapatkan koleksi lembar kerja. |
### calculateFormulas() {#calculateFormulas--}
```
public abstract void calculateFormulas()
```

Menghitung semua formula dalam buku kerja dan memperbarui nilai sel yang sesuai.

--------------------

> ```
> Example shows how to assign a formula to the cell and to calculate a value. The value of the "B4" cell is getting set to 5.
>   
>   Presentation pres = new Presentation();
>   try {
>       IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.Pie, 100, 100, 300, 400);
>       IChartDataWorkbook wb = chart.getChartData().getChartDataWorkbook();
>       wb.getCell(0, "B2", 2);
>       wb.getCell(0, "B3", 3);
>       wb.getCell(0, "B4").setFormula("B2+B3");
>       wb.calculateFormulas();
>       ...
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```

### getCellCollection(String formula, boolean skipHiddenCells) {#getCellCollection-java.lang.String-boolean-}
```
public abstract IChartCellCollection getCellCollection(String formula, boolean skipHiddenCells)
```

Mendapatkan kumpulan sel.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| formula | java.lang.String | Formula Excel seperti "Sheet1!$A$2:$A$5". |
| skipHiddenCells | boolean | Jika true maka metode mengembalikan koleksi tanpa sel tersembunyi. |

**Mengembalikan:**
[IChartCellCollection](../../com.aspose.slides/ichartcellcollection) - Kumpulan sel [IChartCellCollection](../../com.aspose.slides/ichartcellcollection)
### getCell(String worksheetName, int row, int column) {#getCell-java.lang.String-int-int-}
```
public abstract IChartDataCell getCell(String worksheetName, int row, int column)
```

Mendapatkan sel yang dapat digunakan untuk seri atau kategori diagram

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| worksheetName | java.lang.String | Nama lembar kerja. |
| row | int | Baris. |
| column | int | Kolom. |

**Mengembalikan:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - objek Cell
### getCell(int worksheetIndex, int row, int column) {#getCell-int-int-int-}
```
public abstract IChartDataCell getCell(int worksheetIndex, int row, int column)
```

Mendapatkan sel yang dapat digunakan untuk seri atau kategori diagram

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| worksheetIndex | int | Indeks lembar kerja. |
| row | int | Baris. |
| column | int | Kolom. |

**Mengembalikan:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - objek Cell
### getCell(int worksheetIndex, String cellName) {#getCell-int-java.lang.String-}
```
public abstract IChartDataCell getCell(int worksheetIndex, String cellName)
```

Mendapatkan sel yang dapat digunakan untuk seri atau kategori diagram

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| worksheetIndex | int | Indeks lembar kerja. |
| cellName | java.lang.String | Nama sel. |

**Mengembalikan:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - objek Cell
### getCell(int worksheetIndex, String cellName, Object value) {#getCell-int-java.lang.String-java.lang.Object-}
```
public abstract IChartDataCell getCell(int worksheetIndex, String cellName, Object value)
```

Mendapatkan sel yang dapat digunakan untuk seri atau kategori diagram

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| worksheetIndex | int | Indeks lembar kerja. |
| cellName | java.lang.String | Nama sel. |
| value | java.lang.Object | Nilainya. |

**Mengembalikan:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - objek Cell
### getCell(int worksheetIndex, int row, int column, Object value) {#getCell-int-int-int-java.lang.Object-}
```
public abstract IChartDataCell getCell(int worksheetIndex, int row, int column, Object value)
```

Mendapatkan sel yang dapat digunakan untuk seri atau kategori diagram

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| worksheetIndex | int | Indeks lembar kerja. |
| row | int | Baris. |
| column | int | Kolom. |
| value | java.lang.Object | Nilainya. |

**Mengembalikan:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - objek Cell
### clear(int sheetIndex) {#clear-int-}
```
public abstract void clear(int sheetIndex)
```

Menghapus semua nilai sel pada lembar

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sheetIndex | int | Indeks lembar |
### getWorksheets() {#getWorksheets--}
```
public abstract IChartDataWorksheetCollection getWorksheets()
```

Mendapatkan koleksi lembar kerja.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.Pie, 50, 50, 400, 500);
>      IChartDataWorkbook workbook =  chart.getChartData().getChartDataWorkbook();
>      for (IChartDataWorksheet worksheet : workbook.getWorksheets())
>      {
>          String worksheetName = worksheet.getName();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Mengembalikan:**
[IChartDataWorksheetCollection](../../com.aspose.slides/ichartdataworksheetcollection)