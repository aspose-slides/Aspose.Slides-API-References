---
title: ExcelDataWorkbook
second_title: Aspose.Slides untuk Android melalui Referensi API Java
description: Mewakili sebuah workbook yang menyediakan akses ke data Excel untuk penggunaan umum.
type: docs
url: /id/com.aspose.slides/exceldataworkbook/
---
**Warisan:**
java.lang.Object

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook)
```
public class ExcelDataWorkbook implements IExcelDataWorkbook
```

Mewakili sebuah workbook yang menyediakan akses ke data Excel untuk penggunaan umum.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [ExcelDataWorkbook(String filePath)](#ExcelDataWorkbook-java.lang.String-) | Menginisialisasi instance baru menggunakan jalur file yang ditentukan. |
| [ExcelDataWorkbook(InputStream stream)](#ExcelDataWorkbook-java.io.InputStream-) | Menginisialisasi instance baru dari kelas menggunakan stream yang disediakan. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getCells(String formula, boolean skipHiddenCells)](#getCells-java.lang.String-boolean-) | Mengambil koleksi sel dari workbook yang cocok dengan formula yang ditentukan. |
| [getCell(int worksheetIndex, int row, int column)](#getCell-int-int-int-) | Mengambil sel dari worksheet yang ditentukan menggunakan indeksnya dan koordinat sel. |
| [getCell(String worksheetName, int row, int column)](#getCell-java.lang.String-int-int-) | Mengambil sel dari worksheet yang ditentukan menggunakan namanya dan koordinat sel. |
| [getCell(int worksheetIndex, String cellName)](#getCell-int-java.lang.String-) | Mengambil sel dari worksheet yang ditentukan menggunakan indeksnya dan nama sel gaya Excel (mis., "B2"). |
| [getCell(String worksheetName, String cellName)](#getCell-java.lang.String-java.lang.String-) | Mengambil sel dari worksheet yang ditentukan menggunakan nama sel gaya Excel (mis., "B2"). |
| [getChartsFromWorksheet(String worksheetName)](#getChartsFromWorksheet-java.lang.String-) | Mengambil kamus yang berisi indeks dan nama semua diagram dalam worksheet yang ditentukan dari sebuah workbook Excel. |
| [getWorksheetNames()](#getWorksheetNames--) | Mengambil nama semua worksheet yang terdapat dalam workbook Excel. |
### ExcelDataWorkbook(String filePath) {#ExcelDataWorkbook-java.lang.String-}
```
public ExcelDataWorkbook(String filePath)
```

Menginisialisasi instance baru menggunakan jalur file yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filePath | java.lang.String | Jalur lengkap ke file workbook Excel. |

### ExcelDataWorkbook(InputStream stream) {#ExcelDataWorkbook-java.io.InputStream-}
```
public ExcelDataWorkbook(InputStream stream)
```

Menginisialisasi instance baru dari kelas menggunakan stream yang disediakan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | java.io.InputStream | Stream yang berisi data workbook Excel. |

### getCells(String formula, boolean skipHiddenCells) {#getCells-java.lang.String-boolean-}
```
public final System.Collections.Generic.List<IExcelDataCell> getCells(String formula, boolean skipHiddenCells)
```

Mengambil koleksi sel dari workbook yang cocok dengan formula yang ditentukan.

--------------------

> ```
> ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  List<IExcelDataCell> cells = wb.getCells("Sheet1!A2:A6", false);
>  System.out.println(cells.size()); //Hasil: 5
> ```


**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| formula | java.lang.String | Sebuah formula atau ekspresi rentang (mis., "Sheet1!A1:B3") yang digunakan untuk mengidentifikasi sel target. |
| skipHiddenCells | boolean | Jika true, sel tersembunyi (mis., pada baris atau kolom tersembunyi) akan dikecualikan dari hasil. |

**Mengembalikan:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.slides.IExcelDataCell> - Daftar baca-saja sel yang cocok dengan formula yang ditentukan.
### getCell(int worksheetIndex, int row, int column) {#getCell-int-int-int-}
```
public final IExcelDataCell getCell(int worksheetIndex, int row, int column)
```

Mengambil sel dari worksheet yang ditentukan menggunakan indeksnya dan koordinat sel.

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
| worksheetIndex | int | Indeks berbasis nol dari worksheet. |
| row | int | Indeks baris berbasis nol dari sel. |
| column | int | Indeks kolom berbasis nol dari sel. |

**Mengembalikan:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - Sel pada lokasi yang ditentukan.
### getCell(String worksheetName, int row, int column) {#getCell-java.lang.String-int-int-}
```
public final IExcelDataCell getCell(String worksheetName, int row, int column)
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
| row | int | Indeks baris berbasis nol dari sel. |
| column | int | Indeks kolom berbasis nol dari sel. |

**Mengembalikan:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - Sel pada lokasi yang ditentukan.
### getCell(int worksheetIndex, String cellName) {#getCell-int-java.lang.String-}
```
public final IExcelDataCell getCell(int worksheetIndex, String cellName)
```

Mengambil sel dari worksheet yang ditentukan menggunakan indeksnya dan nama sel gaya Excel (mis., "B2").

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
| worksheetIndex | int | Indeks berbasis nol dari worksheet. |
| cellName | java.lang.String | Referensi sel gaya Excel (mis., "A1", "C5"). |

**Mengembalikan:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - Sel pada lokasi yang ditentukan.
### getCell(String worksheetName, String cellName) {#getCell-java.lang.String-java.lang.String-}
```
public final IExcelDataCell getCell(String worksheetName, String cellName)
```

Mengambil sel dari worksheet yang ditentukan menggunakan nama sel gaya Excel (mis., "B2").

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
| cellName | java.lang.String | Referensi sel gaya Excel (mis., "A1", "C5"). |

**Mengembalikan:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - Sel pada lokasi yang ditentukan.
### getChartsFromWorksheet(String worksheetName) {#getChartsFromWorksheet-java.lang.String-}
```
public final System.Collections.Generic.Dictionary<Integer,String> getChartsFromWorksheet(String worksheetName)
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
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.Integer,java.lang.String> - Sebuah kamus di mana kunci adalah indeks diagram dan nilai adalah nama diagram.
### getWorksheetNames() {#getWorksheetNames--}
```
public final System.Collections.Generic.List<String> getWorksheetNames()
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
com.aspose.ms.System.Collections.Generic.List<java.lang.String> - Sebuah daftar nama worksheet