---
title: ExcelWorkbookImporter
second_title: Aspose.Slides untuk Android melalui Referensi API Java
description: Menyediakan fungsionalitas untuk mengimpor konten dari workbook Excel ke dalam presentasi.
type: docs
url: /id/com.aspose.slides/excelworkbookimporter/
---
**Pewarisan:**
java.lang.Object
```
public class ExcelWorkbookImporter
```

Menyediakan fungsionalitas untuk mengimpor konten dari workbook Excel ke dalam presentasi.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, int chartIndex, boolean embedAllWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-int-boolean-) | Mengambil chart dari workbook Excel yang ditentukan dan menambahkannya ke akhir koleksi shape yang diberikan pada koordinat yang ditentukan. |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String chartName, boolean embedAllWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-boolean-) | Mengambil chart dari workbook Excel yang ditentukan dan menambahkannya ke akhir koleksi shape yang diberikan pada koordinat yang ditentukan. |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String chartName, boolean embedAllWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-boolean-) | Mengambil chart dari workbook Excel yang ditentukan dan menambahkannya ke akhir koleksi shape yang diberikan pada koordinat yang ditentukan. |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String chartName, boolean embedWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-boolean-) | Mengambil chart dari workbook Excel yang ditentukan dan menambahkannya ke akhir koleksi shape yang diberikan pada koordinat yang ditentukan. |
| [addTableFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String cellRange)](#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-) | Mengambil tabel dari workbook Excel yang ditentukan dan menambahkannya ke akhir koleksi shape yang diberikan pada koordinat yang ditentukan. |
| [addTableFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String cellRange)](#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-) | Mengambil tabel dari file workbook Excel dan menambahkannya ke akhir koleksi shape yang diberikan pada koordinat yang ditentukan. |
| [addTableFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String cellRange)](#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-) | Mengambil tabel dari file workbook Excel dan menambahkannya ke akhir koleksi shape yang diberikan pada koordinat yang ditentukan. |
### addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, int chartIndex, boolean embedAllWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-int-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, int chartIndex, boolean embedAllWorkbook)
```

Mengambil chart dari workbook Excel yang ditentukan dan menambahkannya ke akhir koleksi shape yang diberikan pada koordinat yang ditentukan.

--------------------

> ```
> Example:
>  
>  IExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  Presentation pres = new Presentation();
>  try {
>      ExcelWorkbookImporter.addChartFromWorkbook(pres.getSlides().get_Item(0).getShapes(), 10, 10, wb, worksheetName, chartName, false);
>      pres.save("result.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | Koleksi shape yang akan ditambahkan chart. |
| x | float | Koordinat X untuk memposisikan chart. |
| y | float | Koordinat Y untuk memposisikan chart. |
| workbook | [IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook) | Workbook Excel. |
| worksheetName | java.lang.String | Nama worksheet yang berisi chart. |
| chartIndex | int | Indeks nol-berbasis dari shape chart yang akan disisipkan. Indeks ini dapat diperoleh menggunakan metode [IExcelDataWorkbook.getChartsFromWorksheet(String)](../../com.aspose.slides/iexceldataworkbook\#getChartsFromWorksheet-String-). |
| embedAllWorkbook | boolean | Jika true, seluruh workbook akan disematkan dalam chart; jika false, hanya data chart yang akan disematkan. |

**Mengembalikan:**
[IChart](../../com.aspose.slides/ichart) - Chart yang ditambahkan ke koleksi shape.
### addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String chartName, boolean embedAllWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String chartName, boolean embedAllWorkbook)
```

Mengambil chart dari workbook Excel yang ditentukan dan menambahkannya ke akhir koleksi shape yang diberikan pada koordinat yang ditentukan.

--------------------

> ```
> Example:
>  
>  IExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  Presentation pres = new Presentation();
>  try {
>      String worksheetName = "worksheet name";
>      Dictionary.Enumerator<Integer, String> worksheetCharts = wb.getChartsFromWorksheet(worksheetName).iterator();
>      while (worksheetCharts.hasNext())
>      {
>          KeyValuePair<Integer, String> chart = worksheetCharts.next();
>          ISlide slide = pres.getSlides().addEmptySlide(pres.getLayoutSlides().get_Item(0));
>          ExcelWorkbookImporter.addChartFromWorkbook(slide.getShapes(), 10, 10, wb, worksheetName, chart.getKey(), false);
>      }
>      pres.save("result.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | Koleksi shape yang akan ditambahkan chart. |
| x | float | Koordinat X untuk memposisikan chart. |
| y | float | Koordinat Y untuk memposisikan chart. |
| workbook | [IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook) | Workbook Excel. |
| worksheetName | java.lang.String | Nama worksheet yang berisi chart. |
| chartName | java.lang.String | Nama chart yang akan ditambahkan. |
| embedAllWorkbook | boolean | Jika true, seluruh workbook akan disematkan dalam chart; jika false, hanya data chart yang akan disematkan. |

**Mengembalikan:**
[IChart](../../com.aspose.slides/ichart) - Chart yang ditambahkan ke koleksi shape.
### addChartFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String chartName, boolean embedAllWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String chartName, boolean embedAllWorkbook)
```

Mengambil chart dari workbook Excel yang ditentukan dan menambahkannya ke akhir koleksi shape yang diberikan pada koordinat yang ditentukan.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream fStream = new FileInputStream(workbookPath);
>      ExcelWorkbookImporter.addChartFromWorkbook(pres.getLayoutSlides().get_Item(0).getShapes(), 10, 10, fStream, worksheetName, chartName, true);
>      fStream.close();
>      pres.save("result.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | Koleksi shape yang akan ditambahkan chart. |
| x | float | Koordinat X untuk memposisikan chart. |
| y | float | Koordinat Y untuk memposisikan chart. |
| workbookStream | java.io.InputStream | Aliran yang berisi data workbook. |
| worksheetName | java.lang.String | Nama worksheet yang berisi chart. |
| chartName | java.lang.String | Nama chart yang akan ditambahkan. |
| embedAllWorkbook | boolean | Jika true, seluruh workbook akan disematkan dalam chart; jika false, hanya data chart yang akan disematkan. |

**Mengembalikan:**
[IChart](../../com.aspose.slides/ichart) - Chart yang ditambahkan ke koleksi shape.
### addChartFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String chartName, boolean embedWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String chartName, boolean embedWorkbook)
```

Mengambil chart dari workbook Excel yang ditentukan dan menambahkannya ke akhir koleksi shape yang diberikan pada koordinat yang ditentukan.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ExcelWorkbookImporter.addChartFromWorkbook(pres.getSlides().get_Item(0).getShapes(), 10, 10, workbookPath, worksheetName, chartName, false);
>      pres.save("result.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | Koleksi shape yang akan ditambahkan chart. |
| x | float | Koordinat X untuk memposisikan chart. |
| y | float | Koordinat Y untuk memposisikan chart. |
| workbookPath | java.lang.String | Jalur file ke workbook yang berisi chart. |
| worksheetName | java.lang.String | Nama worksheet yang berisi chart. |
| chartName | java.lang.String | Nama chart yang akan ditambahkan. |
| embedWorkbook | boolean | Jika true, workbook akan disematkan dalam chart; jika false, chart akan menautkan ke workbook eksternal. |

**Mengembalikan:**
[IChart](../../com.aspose.slides/ichart) - Chart yang ditambahkan ke koleksi shape.
### addTableFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String cellRange) {#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-}
```
public static ITable addTableFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String cellRange)
```

Mengambil tabel dari workbook Excel yang ditentukan dan menambahkannya ke akhir koleksi shape yang diberikan pada koordinat yang ditentukan.

--------------------

> ```
> IExcelDataWorkbook workbook = new ExcelDataWorkbook(testFile);
>  Presentation pres = new Presentation();
>  try {
>      ExcelWorkbookImporter.addTableFromWorkbook(pres.getSlides().get_Item(0).getShapes(), 10, 10, workbook, worksheetName, "A1:D10");
>      pres.save("result.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | Koleksi shape yang akan ditambahkan tabel. |
| x | float | Koordinat X untuk memposisikan tabel. |
| y | float | Koordinat Y untuk memposisikan tabel. |
| workbook | [IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook) | Workbook Excel. |
| worksheetName | java.lang.String | Nama worksheet yang berisi tabel. |
| cellRange | java.lang.String | Rentang sel yang mendefinisikan tabel (misalnya, "A1:D10"). |

**Mengembalikan:**
[ITable](../../com.aspose.slides/itable) - Tabel yang ditambahkan ke koleksi shape.
### addTableFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String cellRange) {#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-}
```
public static ITable addTableFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String cellRange)
```

Mengambil tabel dari file workbook Excel dan menambahkannya ke akhir koleksi shape yang diberikan pada koordinat yang ditentukan.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      ExcelWorkbookImporter.addTableFromWorkbook(pres.getSlides().get_Item(0).getShapes(), 10, 10, workbookPath, worksheetName, "A1:D10");
>      pres.save("result.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | Koleksi shape yang akan ditambahkan tabel. |
| x | float | Koordinat X untuk memposisikan tabel. |
| y | float | Koordinat Y untuk memposisikan tabel. |
| workbookPath | java.lang.String | Jalur ke file workbook Excel. |
| worksheetName | java.lang.String | Nama worksheet yang berisi tabel. |
| cellRange | java.lang.String | Rentang sel yang mendefinisikan tabel (misalnya, "A1:D10"). |

**Mengembalikan:**
[ITable](../../com.aspose.slides/itable) - Tabel yang ditambahkan ke koleksi shape.
### addTableFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String cellRange) {#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-}
```
public static ITable addTableFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String cellRange)
```

Mengambil tabel dari file workbook Excel dan menambahkannya ke akhir koleksi shape yang diberikan pada koordinat yang ditentukan.

--------------------

> ```
> FileInputStream fStream = new FileInputStream(workbookPath);
>  Presentation pres = new Presentation();
>  try {
>      ExcelWorkbookImporter.addTableFromWorkbook(pres.getSlides().get_Item(0).getShapes(), 10, 10, fStream, worksheetName, "A1:D10");
>      pres.save("result.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | Koleksi shape yang akan ditambahkan tabel. |
| x | float | Koordinat X untuk memposisikan tabel. |
| y | float | Koordinat Y untuk memposisikan tabel. |
| workbookStream | java.io.InputStream | Aliran yang berisi data workbook. |
| worksheetName | java.lang.String | Nama worksheet yang berisi tabel. |
| cellRange | java.lang.String | Rentang sel yang mendefinisikan tabel (misalnya, "A1:D10"). |

**Mengembalikan:**
[ITable](../../com.aspose.slides/itable) - Tabel yang ditambahkan ke koleksi shape.