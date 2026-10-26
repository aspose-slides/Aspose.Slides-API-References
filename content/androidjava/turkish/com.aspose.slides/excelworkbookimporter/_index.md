---
title: ExcelWorkbookImporter
second_title: Java API Referansı aracılığıyla Android için Aspose.Slides
description: Bir Excel çalışma kitabından içeriği bir sunuma içe aktarmak için işlevsellik sağlar.
type: docs
url: /tr/com.aspose.slides/excelworkbookimporter/
---
**Kalıtım:**
java.lang.Object
```
public class ExcelWorkbookImporter
```

Bir Excel çalışma kitabından içeriği bir sunuma içe aktarmak için işlevsellik sağlar.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, int chartIndex, boolean embedAllWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-int-boolean-) | Belirtilen Excel çalışma kitabından bir grafik alır ve belirtilen koordinatlarda verilen şekil koleksiyonunun sonuna ekler. |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String chartName, boolean embedAllWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-boolean-) | Belirtilen Excel çalışma kitabından bir grafik alır ve belirtilen koordinatlarda verilen şekil koleksiyonunun sonuna ekler. |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String chartName, boolean embedAllWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-boolean-) | Belirtilen Excel çalışma kitabından bir grafik alır ve belirtilen koordinatlarda verilen şekil koleksiyonunun sonuna ekler. |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String chartName, boolean embedWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-boolean-) | Belirtilen Excel çalışma kitabından bir grafik alır ve belirtilen koordinatlarda verilen şekil koleksiyonunun sonuna ekler. |
| [addTableFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String cellRange)](#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-) | Belirtilen Excel çalışma kitabından bir tablo alır ve belirtilen koordinatlarda verilen şekil koleksiyonunun sonuna ekler. |
| [addTableFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String cellRange)](#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-) | Belirtilen Excel çalışma kitabı dosyasından bir tablo alır ve belirtilen koordinatlarda verilen şekil koleksiyonunun sonuna ekler. |
| [addTableFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String cellRange)](#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-) | Belirtilen Excel çalışma kitabı dosyasından bir tablo alır ve belirtilen koordinatlarda verilen şekil koleksiyonunun sonuna ekler. |

### addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, int chartIndex, boolean embedAllWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-int-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, int chartIndex, boolean embedAllWorkbook)
```

Belirtilen Excel çalışma kitabından bir grafik alır ve belirtilen koordinatlarda verilen şekil koleksiyonunun sonuna ekler.

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


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | Grafiğin ekleneceği şekil koleksiyonu. |
| x | float | Grafiğin konumlandırılması için X koordinatı. |
| y | float | Grafiğin konumlandırılması için Y koordinatı. |
| workbook | [IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook) | Excel çalışma kitabı. |
| worksheetName | java.lang.String | Grafiği içeren çalışma sayfasının adı. |
| chartIndex | int | Eklenecek grafik şeklinin sıfır tabanlı indeksi. Bu indeks [IExcelDataWorkbook.getChartsFromWorksheet(String)](../../com.aspose.slides/iexceldataworkbook\#getChartsFromWorksheet-String-) yöntemi kullanılarak elde edilebilir. |
| embedAllWorkbook | boolean | Doğru ise, tüm çalışma kitabı grafiğe gömülür; yanlış ise yalnızca grafik verileri gömülür. |

**Dönüş:**
[IChart](../../com.aspose.slides/ichart) - Şekil koleksiyonuna eklenen grafik.

### addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String chartName, boolean embedAllWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String chartName, boolean embedAllWorkbook)
```

Belirtilen Excel çalışma kitabından bir grafik alır ve belirtilen koordinatlarda verilen şekil koleksiyonunun sonuna ekler.

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

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | Grafiğin ekleneceği şekil koleksiyonu. |
| x | float | Grafiğin konumlandırılması için X koordinatı. |
| y | float | Grafiğin konumlandırılması için Y koordinatı. |
| workbook | [IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook) | Excel çalışma kitabı. |
| worksheetName | java.lang.String | Grafiği içeren çalışma sayfasının adı. |
| chartName | java.lang.String | Eklenecek grafiğin adı. |
| embedAllWorkbook | boolean | Doğru ise, tüm çalışma kitabı grafiğe gömülür; yanlış ise yalnızca grafik verileri gömülür. |

**Dönüş:**
[IChart](../../com.aspose.slides/ichart) - Şekil koleksiyonuna eklenen grafik.

### addChartFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String chartName, boolean embedAllWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String chartName, boolean embedAllWorkbook)
```

Belirtilen Excel çalışma kitabından bir grafik alır ve belirtilen koordinatlarda verilen şekil koleksiyonunun sonuna ekler.

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

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | Grafiğin ekleneceği şekil koleksiyonu. |
| x | float | Grafiğin konumlandırılması için X koordinatı. |
| y | float | Grafiğin konumlandırılması için Y koordinatı. |
| workbookStream | java.io.InputStream | Çalışma kitabı verilerini içeren bir akış. |
| worksheetName | java.lang.String | Grafiği içeren çalışma sayfasının adı. |
| chartName | java.lang.String | Eklenecek grafiğin adı. |
| embedAllWorkbook | boolean | Doğru ise, tüm çalışma kitabı grafiğe gömülür; yanlış ise yalnızca grafik verileri gömülür. |

**Dönüş:**
[IChart](../../com.aspose.slides/ichart) - Şekil koleksiyonuna eklenen grafik.

### addChartFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String chartName, boolean embedWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String chartName, boolean embedWorkbook)
```

Belirtilen Excel çalışma kitabından bir grafik alır ve belirtilen koordinatlarda verilen şekil koleksiyonunun sonuna ekler.

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

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | Grafiğin ekleneceği şekil koleksiyonu. |
| x | float | Grafiğin konumlandırılması için X koordinatı. |
| y | float | Grafiğin konumlandırılması için Y koordinatı. |
| workbookPath | java.lang.String | Grafiği içeren çalışma kitabının dosya yolu. |
| worksheetName | java.lang.String | Grafiği içeren çalışma sayfasının adı. |
| chartName | java.lang.String | Eklenecek grafiğin adı. |
| embedWorkbook | boolean | Doğru ise, çalışma kitabı grafiğe gömülür; yanlış ise, grafik harici çalışma kitabına bağlanır. |

**Dönüş:**
[IChart](../../com.aspose.slides/ichart) - Şekil koleksiyonuna eklenen grafik.

### addTableFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String cellRange) {#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-}
```
public static ITable addTableFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String cellRange)
```

Belirtilen Excel çalışma kitabından bir tablo alır ve belirtilen koordinatlarda verilen şekil koleksiyonunun sonuna ekler.

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

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | Tablonun ekleneceği şekil koleksiyonu. |
| x | float | Tabloyu konumlandırmak için X koordinatı. |
| y | float | Tabloyu konumlandırmak için Y koordinatı. |
| workbook | [IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook) | Excel çalışma kitabı. |
| worksheetName | java.lang.String | Tabloyu içeren çalışma sayfasının adı. |
| cellRange | java.lang.String | Tabloyu tanımlayan hücre aralığı (örnek, "A1:D10"). |

**Dönüş:**
[ITable](../../com.aspose.slides/itable) - Şekil koleksiyonuna eklenen tablo.

### addTableFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String cellRange) {#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-}
```
public static ITable addTableFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String cellRange)
```

Belirtilen Excel çalışma kitabı dosyasından bir tablo alır ve belirtilen koordinatlarda verilen şekil koleksiyonunun sonuna ekler.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      ExcelWorkbookImporter.addTableFromWorkbook(pres.getSlides().get_Item(0).getShapes(), 10, 10, workbookPath, worksheetName, "A1:D10");
>      pres.save("result.pptx", SaveFormat.Pptx);
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | Tablonun ekleneceği şekil koleksiyonu. |
| x | float | Tabloyu konumlandırmak için X koordinatı. |
| y | float | Tabloyu konumlandırmak için Y koordinatı. |
| workbookPath | java.lang.String | Excel çalışma kitabı dosyasının yolu. |
| worksheetName | java.lang.String | Tabloyu içeren çalışma sayfasının adı. |
| cellRange | java.lang.String | Tabloyu tanımlayan hücre aralığı (örnek, "A1:D10"). |

**Dönüş:**
[ITable](../../com.aspose.slides/itable) - Şekil koleksiyonuna eklenen tablo.

### addTableFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String cellRange) {#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-}
```
public static ITable addTableFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String cellRange)
```

Belirtilen Excel çalışma kitabı dosyasından bir tablo alır ve belirtilen koordinatlarda verilen şekil koleksiyonunun sonuna ekler.

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

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | Tablonun ekleneceği şekil koleksiyonu. |
| x | float | Tabloyu konumlandırmak için X koordinatı. |
| y | float | Tabloyu konumlandırmak için Y koordinatı. |
| workbookStream | java.io.InputStream | Çalışma kitabı verilerini içeren bir akış. |
| worksheetName | java.lang.String | Tabloyu içeren çalışma sayfasının adı. |
| cellRange | java.lang.String | Tabloyu tanımlayan hücre aralığı (örnek, "A1:D10"). |

**Dönüş:**
[ITable](../../com.aspose.slides/itable) - Şekil koleksiyonuna eklenen tablo.