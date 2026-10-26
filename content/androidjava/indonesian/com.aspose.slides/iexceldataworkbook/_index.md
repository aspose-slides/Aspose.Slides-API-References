---
title: IExcelDataWorkbook
second_title: Aspose.Slides for Android via Java API Reference
description: Mewakili sebuah workbook yang menyediakan akses ke data Excel untuk penggunaan umum.
type: docs
url: /id/com.aspose.slides/iexceldataworkbook/
---```
public interface IExcelDataWorkbook
```

Mewakili sebuah workbook yang menyediakan akses ke data Excel untuk penggunaan umum.

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getCells(String formula, boolean skipHiddenCells)](#getCells-java.lang.String-boolean-) | Mengambil sekumpulan sel dari workbook yang cocok dengan rumus yang ditentukan. |
| [getCell(int worksheetIndex, int row, int column)](#getCell-int-int-int-) | Mengambil sel dari worksheet yang ditentukan menggunakan indeks dan koordinat selnya. |
| [getCell(String worksheetName, int row, int column)](#getCell-java.lang.String-int-int-) | Mengambil sel dari worksheet yang ditentukan menggunakan namanya dan koordinat sel. |
| [getCell(int worksheetIndex, String cellName)](#getCell-int-java.lang.String-) | Mengambil sel dari worksheet yang ditentukan menggunakan indeksnya dan nama sel gaya Excel (misalnya "B2"). |
| [getCell(String worksheetName, String cellName)](#getCell-java.lang.String-java.lang.String-) | Mengambil sel dari worksheet yang ditentukan menggunakan nama sel gaya Excel (misalnya "B2"). |
| [getChartsFromWorksheet(String worksheetName)](#getChartsFromWorksheet-java.lang.String-) | Mengambil kamus yang berisi indeks dan nama semua diagram dalam worksheet yang ditentukan dari sebuah workbook Excel. |
| [getWorksheetNames()](#getWorksheetNames--) | Mengambil nama semua worksheet yang terdapat dalam workbook Excel. |

### getCells(String formula, boolean skipHiddenCells) {#getCells-java.lang.String-boolean-}
```
public abstract System.Collections.Generic.List<IExcelDataCell> getCells(String formula, boolean skipHiddenCells)
```

Mengambil sekumpulan sel dari workbook yang cocok dengan rumus yang ditentukan.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  List<IExcelDataCell> cells = wb.getCells("Sheet1!A2:A6", false);
>  System.out.println(cells.size()); //Output: 5
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| formula | java.lang.String | Sebuah rumus atau ekspresi rentang (misalnya "Sheet1!A1:B3") yang digunakan untuk mengidentifikasi sel target. |
| skipHiddenCells | boolean | Jika true, sel tersembunyi (misalnya pada baris atau kolom tersembunyi) akan dikeluarkan dari hasil. |

**Mengembalikan:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.slides.IExcelDataCell> - Daftar sel read-only yang cocok dengan rumus yang ditentukan.

### getCell(int worksheetIndex, int row, int column) {#getCell-int-int-int-}
```
public abstract IExcelDataCell getCell(int worksheetIndex, int row, int column)
```

Mengambil sel dari worksheet yang ditentukan menggunakan indeks dan koordinat selnya.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getValue().toString());
> ```


**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| worksheetIndex | int | Indeks worksheet berbasis nol. |
| row | int | Indeks baris sel berbasis nol. |
| column | int | Indeks kolom sel berbasis nol. |

**Mengembalikan:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - Sel pada lokasi yang ditentukan.

### getCell(String worksheetName, int row, int column) {#getCell-java.lang.String-int-int-}
```
public abstract IExcelDataCell getCell(String worksheetName, int row, int column)
```

Mengambil sel dari worksheet yang ditentukan menggunakan namanya dan koordinat sel.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell("Sheet1", 1, 1);
>  System.out.println(cell.getValue().toString());
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| worksheetName | java.lang.String | Nama worksheet. |
| row | int | Indeks baris sel berbasis nol. |
| column | int | Indeks kolom sel berbasis nol. |

**Mengembalikan:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - Sel pada lokasi yang ditentukan.

### getCell(int worksheetIndex, String cellName) {#getCell-int-java.lang.String-}
```
public abstract IExcelDataCell getCell(int worksheetIndex, String cellName)
```

Mengambil sel dari worksheet yang ditentukan menggunakan indeksnya dan nama sel gaya Excel (misalnya "B2").

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, "B2");
>  System.out.println(cell.getValue().toString());
> ```


**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| worksheetIndex | int | Indeks worksheet berbasis nol. |
| cellName | java.lang.String | Referensi sel gaya Excel (misalnya "A1", "C5"). |

**Mengembalikan:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - Sel pada lokasi yang ditentukan.

### getCell(String worksheetName, String cellName) {#getCell-java.lang.String-java.lang.String-}
```
public abstract IExcelDataCell getCell(String worksheetName, String cellName)
```

Mengambil sel dari worksheet yang ditentukan menggunakan nama sel gaya Excel (misalnya "B2").

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell("Sheet1", "B2");
>  System.out.println(cell.getValue().toString());
> ```


**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| worksheetName | java.lang.String | Nama worksheet. |
| cellName | java.lang.String | Referensi sel gaya Excel (misalnya "A1", "C5"). |

**Mengembalikan:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - Sel pada lokasi yang ditentukan.

### getChartsFromWorksheet(String worksheetName) {#getChartsFromWorksheet-java.lang.String-}
```
public abstract System.Collections.Generic.Dictionary<Integer,String> getChartsFromWorksheet(String worksheetName)
```

Mengambil kamus yang berisi indeks dan nama semua diagram dalam worksheet yang ditentukan dari sebuah workbook Excel.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  Dictionary.Enumerator<Integer, String> sheetCharts = wb.getChartsFromWorksheet("worksheetName").iterator();
>  while (sheetCharts.hasNext())
>  {
>      KeyValuePair<Integer, String> chart = sheetCharts.next();
>      System.out.println(chart.getKey() + " : " + chart.getValue());
>  }
> ```


**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| worksheetName | java.lang.String | Nama worksheet yang akan dicari diagramnya. |

**Mengembalikan:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.Integer,java.lang.String> - Kamus dimana kunci adalah indeks diagram dan nilai adalah nama diagram.

### getWorksheetNames() {#getWorksheetNames--}
```
public abstract System.Collections.Generic.List<String> getWorksheetNames()
```

Mengambil nama semua worksheet yang terdapat dalam workbook Excel.

--------------------

> ```
> Example:
>  
>  IExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  List<String> sheetNames = wb.getWorksheetNames();
>  for (String name : sheetNames)
>      System.out.println(name);
> ```

**Mengembalikan:**
com.aspose.ms.System.Collections.Generic.List<java.lang.String> - Daftar nama worksheet