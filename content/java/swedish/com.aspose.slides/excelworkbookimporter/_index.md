---
title: ExcelWorkbookImporter
second_title: Aspose.Slides för Java API-referens
description: Tillhandahåller funktionalitet för att importera innehåll från en Excel-arbetsbok till en presentation.
type: docs
url: /sv/com.aspose.slides/excelworkbookimporter/
---
**Arv:**
java.lang.Object
```
public class ExcelWorkbookImporter
```

Tillhandahåller funktionalitet för att importera innehåll från en Excel-arbetsbok till en presentation.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, int chartIndex, boolean embedAllWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-int-boolean-) | Hämtar ett chart från den angivna Excel-arbetsboken och lägger till det i slutet av den angivna shape-samlingen på de angivna koordinaterna. |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String chartName, boolean embedAllWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-boolean-) | Hämtar ett chart från den angivna Excel-arbetsboken och lägger till det i slutet av den angivna shape-samlingen på de angivna koordinaterna. |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String chartName, boolean embedAllWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-boolean-) | Hämtar ett chart från den angivna Excel-arbetsboken och lägger till det i slutet av den angivna shape-samlingen på de angivna koordinaterna. |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String chartName, boolean embedWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-boolean-) | Hämtar ett chart från den angivna Excel-arbetsboken och lägger till det i slutet av den angivna shape-samlingen på de angivna koordinaterna. |
| [addTableFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String cellRange)](#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-) | Hämtar en table från den angivna Excel-arbetsboken och lägger till den i slutet av den angivna shape-samlingen på de angivna koordinaterna. |
| [addTableFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String cellRange)](#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-) | Hämtar en table från den angivna Excel-arbetsbokfilen och lägger till den i slutet av den angivna shape-samlingen på de angivna koordinaterna. |
| [addTableFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String cellRange)](#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-) | Hämtar en table från den angivna Excel-arbetsbokfilen och lägger till den i slutet av den angivna shape-samlingen på de angivna koordinaterna. |
### addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, int chartIndex, boolean embedAllWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-int-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, int chartIndex, boolean embedAllWorkbook)
```


Hämtar ett chart från den angivna Excel-arbetsboken och lägger till det i slutet av den angivna shape-samlingen på de angivna koordinaterna.

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

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | Shape-samlingen som chart ska läggas till i. |
| x | float | X-koordinaten för placering av chart. |
| y | float | Y-koordinaten för placering av chart. |
| workbook | [IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook) | Excel-arbetsboken. |
| worksheetName | java.lang.String | Namnet på arbetsbladet som innehåller chart. |
| chartIndex | int | Det nollbaserade indexet för chart-formen som ska infogas. Detta index kan erhållas med [IExcelDataWorkbook.getChartsFromWorksheet(String)](../../com.aspose.slides/iexceldataworkbook\#getChartsFromWorksheet-String-)-metoden. |
| embedAllWorkbook | boolean | Om true kommer hela arbetsboken att bäddas in i chart; om false kommer endast chart-data att bäddas in. |

**Returnerar:**
[IChart](../../com.aspose.slides/ichart) - Chart som lades till i shape-samlingen.
### addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String chartName, boolean embedAllWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String chartName, boolean embedAllWorkbook)
```


Hämtar ett chart från den angivna Excel-arbetsboken och lägger till det i slutet av den angivna shape-samlingen på de angivna koordinaterna.

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

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | Shape-samlingen som chart ska läggas till i. |
| x | float | X-koordinaten för placering av chart. |
| y | float | Y-koordinaten för placering av chart. |
| workbook | [IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook) | Excel-arbetsboken. |
| worksheetName | java.lang.String | Namnet på arbetsbladet som innehåller chart. |
| chartName | java.lang.String | Namnet på chart som ska läggas till. |
| embedAllWorkbook | boolean | Om true kommer hela arbetsboken att bäddas in i chart; om false kommer endast chart-data att bäddas in. |

**Returnerar:**
[IChart](../../com.aspose.slides/ichart) - Chart som lades till i shape-samlingen.
### addChartFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String chartName, boolean embedAllWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String chartName, boolean embedAllWorkbook)
```


Hämtar ett chart från den angivna Excel-arbetsboken och lägger till det i slutet av den angivna shape-samlingen på de angivna koordinaterna.

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

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | Shape-samlingen som chart ska läggas till i. |
| x | float | X-koordinaten för placering av chart. |
| y | float | Y-koordinaten för placering av chart. |
| workbookStream | java.io.InputStream | En ström som innehåller arbetsboksdata. |
| worksheetName | java.lang.String | Namnet på arbetsbladet som innehåller chart. |
| chartName | java.lang.String | Namnet på chart som ska läggas till. |
| embedAllWorkbook | boolean | Om true kommer hela arbetsboken att bäddas in i chart; om false kommer endast chart-data att bäddas in. |

**Returnerar:**
[IChart](../../com.aspose.slides/ichart) - Chart som lades till i shape-samlingen.
### addChartFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String chartName, boolean embedWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String chartName, boolean embedWorkbook)
```


Hämtar ett chart från den angivna Excel-arbetsboken och lägger till det i slutet av den angivna shape-samlingen på de angivna koordinaterna.

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

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | Shape-samlingen som chart ska läggas till i. |
| x | float | X-koordinaten för placering av chart. |
| y | float | Y-koordinaten för placering av chart. |
| workbookPath | java.lang.String | Filvägen till arbetsboken som innehåller chart. |
| worksheetName | java.lang.String | Namnet på arbetsbladet som innehåller chart. |
| chartName | java.lang.String | Namnet på chart som ska läggas till. |
| embedWorkbook | boolean | Om true kommer arbetsboken att bäddas in i chart; om false kommer chart att länkas till den externa arbetsboken. |

**Returnerar:**
[IChart](../../com.aspose.slides/ichart) - Chart som lades till i shape-samlingen.
### addTableFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String cellRange) {#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-}
```
public static ITable addTableFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String cellRange)
```


Hämtar en table från den angivna Excel-arbetsboken och lägger till den i slutet av den angivna shape-samlingen på de angivna koordinaterna.

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

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | Shape-samlingen som table ska läggas till i. |
| x | float | X-koordinaten för placering av table. |
| y | float | Y-koordinaten för placering av table. |
| workbook | [IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook) | Excel-arbetsboken. |
| worksheetName | java.lang.String | Namnet på arbetsbladet som innehåller table. |
| cellRange | java.lang.String | Cellområdet som definierar table (till exempel "A1:D10"). |

**Returnerar:**
[ITable](../../com.aspose.slides/itable) - Table som lades till i shape-samlingen.
### addTableFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String cellRange) {#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-}
```
public static ITable addTableFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String cellRange)
```


Hämtar en table från den angivna Excel-arbetsbokfilen och lägger till den i slutet av den angivna shape-samlingen på de angivna koordinaterna.

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

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | Shape-samlingen som table ska läggas till i. |
| x | float | X-koordinaten för placering av table. |
| y | float | Y-koordinaten för placering av table. |
| workbookPath | java.lang.String | Sökvägen till Excel-arbetsbokfilen. |
| worksheetName | java.lang.String | Namnet på arbetsbladet som innehåller table. |
| cellRange | java.lang.String | Cellområdet som definierar table (till exempel "A1:D10"). |

**Returnerar:**
[ITable](../../com.aspose.slides/itable) - Table som lades till i shape-samlingen.
### addTableFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String cellRange) {#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-}
```
public static ITable addTableFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String cellRange)
```


Hämtar en table från den angivna Excel-arbetsbokfilen och lägger till den i slutet av den angivna shape-samlingen på de angivna koordinaterna.

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

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | Shape-samlingen som table ska läggas till i. |
| x | float | X-koordinaten för placering av table. |
| y | float | Y-koordinaten för placering av table. |
| workbookStream | java.io.InputStream | En ström som innehåller arbetsboksdata. |
| worksheetName | java.lang.String | Namnet på arbetsbladet som innehåller table. |
| cellRange | java.lang.String | Cellområdet som definierar table (till exempel "A1:D10"). |

**Returnerar:**
[ITable](../../com.aspose.slides/itable) - Table som lades till i shape-samlingen.