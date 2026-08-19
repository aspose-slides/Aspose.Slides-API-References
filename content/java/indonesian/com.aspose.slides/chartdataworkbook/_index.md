---
title: ChartDataWorkbook
second_title: Referensi API Aspose.Slides untuk Java
description: Menyediakan akses ke workbook Excel yang disematkan
type: docs
url: /id/com.aspose.slides/chartdataworkbook/
---
**Pewarisan:**
java.lang.Object, com.aspose.slides.DomObject

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)
```
public class ChartDataWorkbook extends DomObject<ChartData> implements IChartDataWorkbook
```

Menyediakan akses ke workbook Excel yang disematkan
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getWorksheets()](#getWorksheets--) | Mendapatkan koleksi worksheets. |
| [getCellCollection(String formula, boolean skipHiddenCells)](#getCellCollection-java.lang.String-boolean-) | Mendapatkan kumpulan cells. |
| [getCell(String worksheetName, int row, int column)](#getCell-java.lang.String-int-int-) | Mendapatkan cell yang dapat digunakan untuk chart series atau categories |
| [getCell(int worksheetIndex, int row, int column)](#getCell-int-int-int-) | Mendapatkan cell yang dapat digunakan untuk chart series atau categories |
| [getCell(int worksheetIndex, String cellName)](#getCell-int-java.lang.String-) | Mendapatkan cell yang dapat digunakan untuk chart series atau categories |
| [getCell(int worksheetIndex, String cellName, Object value)](#getCell-int-java.lang.String-java.lang.Object-) | Mendapatkan cell yang dapat digunakan untuk chart series atau categories |
| [getCell(int worksheetIndex, int row, int column, Object value)](#getCell-int-int-int-java.lang.Object-) | Mendapatkan cell yang dapat digunakan untuk chart series atau categories |
| [clear(int sheetIndex)](#clear-int-) | Hapus semua nilai cells pada sheet |
| [calculateFormulas()](#calculateFormulas--) | Menghitung semua formula dalam workbook dan memperbarui nilai cells yang bersesuaian. |
### getWorksheets() {#getWorksheets--}
```
public final IChartDataWorksheetCollection getWorksheets()
```


Mendapatkan koleksi worksheets.

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
### getCellCollection(String formula, boolean skipHiddenCells) {#getCellCollection-java.lang.String-boolean-}
```
public final IChartCellCollection getCellCollection(String formula, boolean skipHiddenCells)
```


Mendapatkan kumpulan cells.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| formula | java.lang.String | Formula Excel seperti "Sheet1!$A$2:$A$5". |
| skipHiddenCells | boolean | Jika true maka metode mengembalikan koleksi tanpa hidden cells. |

**Mengembalikan:**
[IChartCellCollection](../../com.aspose.slides/ichartcellcollection)
### getCell(String worksheetName, int row, int column) {#getCell-java.lang.String-int-int-}
```
public final IChartDataCell getCell(String worksheetName, int row, int column)
```


Mendapatkan cell yang dapat digunakan untuk chart series atau categories

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| worksheetName | java.lang.String | Nama worksheet. |
| row | int | Baris. |
| column | int | Kolom. |

**Mengembalikan:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell object
### getCell(int worksheetIndex, int row, int column) {#getCell-int-int-int-}
```
public final IChartDataCell getCell(int worksheetIndex, int row, int column)
```


Mendapatkan cell yang dapat digunakan untuk chart series atau categories

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| worksheetIndex | int | Indeks worksheet. |
| row | int | Baris. |
| column | int | Kolom. |

**Mengembalikan:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell object
### getCell(int worksheetIndex, String cellName) {#getCell-int-java.lang.String-}
```
public final IChartDataCell getCell(int worksheetIndex, String cellName)
```


Mendapatkan cell yang dapat digunakan untuk chart series atau categories

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| worksheetIndex | int | Indeks worksheet. |
| cellName | java.lang.String | Nama cell. |

**Mengembalikan:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell object
### getCell(int worksheetIndex, String cellName, Object value) {#getCell-int-java.lang.String-java.lang.Object-}
```
public final IChartDataCell getCell(int worksheetIndex, String cellName, Object value)
```


Mendapatkan cell yang dapat digunakan untuk chart series atau categories

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| worksheetIndex | int | Indeks worksheet. |
| cellName | java.lang.String | Nama cell. |
| value | java.lang.Object | Nilai. |

**Mengembalikan:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell object
### getCell(int worksheetIndex, int row, int column, Object value) {#getCell-int-int-int-java.lang.Object-}
```
public final IChartDataCell getCell(int worksheetIndex, int row, int column, Object value)
```


Mendapatkan cell yang dapat digunakan untuk chart series atau categories

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| worksheetIndex | int | Indeks worksheet. |
| row | int | Baris. |
| column | int | Kolom. |
| value | java.lang.Object | Nilai. |

**Mengembalikan:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell object
### clear(int sheetIndex) {#clear-int-}
```
public final void clear(int sheetIndex)
```


Hapus semua nilai cells pada sheet

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| sheetIndex | int | Indeks sheet |

### calculateFormulas() {#calculateFormulas--}
```
public final void calculateFormulas()
```


Menghitung semua formula dalam workbook dan memperbarui nilai cells yang bersesuaian.

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