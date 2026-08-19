---
title: ExcelWorkbookImporter
second_title: Referensi API Aspose.Slides untuk Java
description: Menyediakan fungsionalitas untuk mengimpor konten dari workbook Excel ke dalam presentasi.
type: docs
url: /id/com.aspose.slides/excelworkbookimporter/
---
**Inheritance:**
java.lang.Object
```
public class ExcelWorkbookImporter
```

Menyediakan fungsionalitas untuk mengimpor konten dari workbook Excel ke dalam presentasi.
## Methods

| Method | Description |
| --- | --- |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, int chartIndex, boolean embedAllWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-int-boolean-) | Mengambil chart dari workbook Excel yang ditentukan dan menambahkannya ke akhir koleksi shape yang diberikan pada koordinat yang ditentukan. |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String chartName, boolean embedAllWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-boolean-) | Mengambil chart dari workbook Excel yang ditentukan dan menambahkannya ke akhir koleksi shape yang diberikan pada koordinat yang ditentukan. |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String chartName, boolean embedAllWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-boolean-) | Mengambil chart dari workbook Excel yang ditentukan dan menambahkannya ke akhir koleksi shape yang diberikan pada koordinat yang ditentukan. |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String chartName, boolean embedWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-boolean-) | Mengambil chart dari workbook Excel yang ditentukan dan menambahkannya ke akhir koleksi shape yang diberikan pada koordinat yang ditentukan. |
| [addTableFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String cellRange)](#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-) | Mengambil table dari workbook Excel yang ditentukan dan menambahkannya ke akhir koleksi shape yang diberikan pada koordinat yang ditentukan. |
| [addTableFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String cellRange)](#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-) | Mengambil table dari file workbook Excel yang ditentukan dan menambahkannya ke akhir koleksi shape yang diberikan pada koordinat yang ditentukan. |
| [addTableFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String cellRange)](#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-) | Mengambil table dari file workbook Excel yang ditentukan dan menambahkannya ke akhir koleksi shape yang diberikan pada koordinat yang ditentukan. |
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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | Koleksi shape yang akan ditambahkan chart. |
| x | float | Koordinat X untuk memposisikan chart. |
| y | float | Koordinat Y untuk memposisikan chart. |
| workbook | [IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook) | Workbook Excel. |
| worksheetName | java.lang.String | Nama worksheet yang berisi chart. |
| chartIndex | int | Indeks berbasis nol dari shape chart yang akan disisipkan. Indeks ini dapat diperoleh menggunakan metode [IExcelDataWorkbook.getChartsFromWorksheet(String)](../../com.aspose.slides/iexceldataworkbook\#getChartsFromWorksheet-String-). |
| embedAllWorkbook | boolean | Jika true, seluruh workbook akan disematkan dalam chart; jika false, hanya data chart yang akan disematkan. |

**Returns:**
[IChart](../../com.aspose.slides/ichart) - Chart yang telah ditambahkan ke koleksi shape.
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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | Koleksi shape yang akan ditambahkan chart. |
| x | float | Koordinat X untuk memposisikan chart. |
| y | float | Koordinat Y untuk memposisikan chart. |
| workbook | [IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook) | Workbook Excel. |
| worksheetName | java.lang.String | Nama worksheet yang berisi chart. |
| chartName | java.lang.String | Nama chart yang akan ditambahkan. |
| embedAllWorkbook | boolean | Jika true, seluruh workbook akan disematkan dalam chart; jika false, hanya data chart yang akan disematkan. |

**Returns:**
[IChart](../../com.aspose.slides/ichart) - Chart yang telah ditambahkan ke koleksi shape.
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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | Koleksi shape yang akan ditambahkan chart. |
| x | float | Koordinat X untuk memposisikan chart. |
| y | float | Koordinat Y untuk memposisikan chart. |
| workbookStream | java.io.InputStream | Aliran yang berisi data workbook. |
| worksheetName | java.lang.String | Nama worksheet yang berisi chart. |
| chartName | java.lang.String | Nama chart yang akan ditambahkan. |
| embedAllWorkbook | boolean | Jika true, seluruh workbook akan disematkan dalam chart; jika false, hanya data chart yang akan disematkan. |

**Returns:**
[IChart](../../com.aspose.slides/ichart) - Chart yang telah ditambahkan ke koleksi shape.
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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | Koleksi shape yang akan ditambahkan chart. |
| x | float | Koordinat X untuk memposisikan chart. |
| y | float | Koordinat Y untuk memposisikan chart. |
| workbookPath | java.lang.String | Jalur file ke workbook yang berisi chart. |
| worksheetName | java.lang.String | Nama worksheet yang berisi chart. |
| chartName | java.lang.String | Nama chart yang akan ditambahkan. |
| embedWorkbook | boolean | Jika true, workbook akan disematkan dalam chart; jika false, chart akan menaut ke workbook eksternal. |

**Returns:**
[IChart](../../com.aspose.slides/ichart) - Chart yang telah ditambahkan ke koleksi shape.
### addTableFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String cellRange) {#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-}
```
public static ITable addTableFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String cellRange)
```


Mengambil table dari workbook Excel yang ditentukan dan menambahkannya ke akhir koleksi shape yang diberikan pada koordinat yang ditentukan.

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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | Koleksi shape yang akan ditambahkan table. |
| x | float | Koordinat X untuk memposisikan table. |
| y | float | Koordinat Y untuk memposisikan table. |
| workbook | [IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook) | Workbook Excel. |
| worksheetName | java.lang.String | Nama worksheet yang berisi table. |
| cellRange | java.lang.String | Rentang sel yang mendefinisikan table (misalnya, "A1:D10"). |

**Returns:**
[ITable](../../com.aspose.slides/itable) - Table yang telah ditambahkan ke koleksi shape.
### addTableFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String cellRange) {#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-}
```
public static ITable addTableFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String cellRange)
```


Mengambil table dari file workbook Excel yang ditentukan dan menambahkannya ke akhir koleksi shape yang diberikan pada koordinat yang ditentukan.

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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | Koleksi shape yang akan ditambahkan table. |
| x | float | Koordinat X untuk memposisikan table. |
| y | float | Koordinat Y untuk memposisikan table. |
| workbookPath | java.lang.String | Jalur ke file workbook Excel. |
| worksheetName | java.lang.String | Nama worksheet yang berisi table. |
| cellRange | java.lang.String | Rentang sel yang mendefinisikan table (misalnya, "A1:D10"). |

**Returns:**
[ITable](../../com.aspose.slides/itable) - Table yang telah ditambahkan ke koleksi shape.
### addTableFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String cellRange) {#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-}
```
public static ITable addTableFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String cellRange)
```


Mengambil table dari file workbook Excel yang ditentukan dan menambahkannya ke akhir koleksi shape yang diberikan pada koordinat yang ditentukan.

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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | Koleksi shape yang akan ditambahkan table. |
| x | float | Koordinat X untuk memposisikan table. |
| y | float | Koordinat Y untuk memposisikan table. |
| workbookStream | java.io.InputStream | Aliran yang berisi data workbook. |
| worksheetName | java.lang.String | Nama worksheet yang berisi table. |
| cellRange | java.lang.String | Rentang sel yang mendefinisikan table (misalnya, "A1:D10"). |

**Returns:**
[ITable](../../com.aspose.slides/itable) - Table yang telah ditambahkan ke koleksi shape.