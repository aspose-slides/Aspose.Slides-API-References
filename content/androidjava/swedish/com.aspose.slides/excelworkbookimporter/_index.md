---
title: ExcelWorkbookImporter
second_title: Aspose.Slides för Android via Java API-referens
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
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, int chartIndex, boolean embedAllWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-int-boolean-) | Hämtar ett diagram från den angivna Excel-arbetsboken och lägger till det i slutet av den angivna formsamlingen på de angivna koordinaterna. |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String chartName, boolean embedAllWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-boolean-) | Hämtar ett diagram från den angivna Excel-arbetsboken och lägger till det i slutet av den angivna formsamlingen på de angivna koordinaterna. |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String chartName, boolean embedAllWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-boolean-) | Hämtar ett diagram från den angivna Excel-arbetsboken och lägger till det i slutet av den angivna formsamlingen på de angivna koordinaterna. |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String chartName, boolean embedWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-boolean-) | Hämtar ett diagram från den angivna Excel-arbetsboken och lägger till det i slutet av den angivna formsamlingen på de angivna koordinaterna. |
| [addTableFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String cellRange)](#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-) | Hämtar en tabell från den angivna Excel-arbetsboken och lägger till den i slutet av den angivna formsamlingen på de angivna koordinaterna. |
| [addTableFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String cellRange)](#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-) | Hämtar en tabell från den angivna Excel-arbetsboksfilen och lägger till den i slutet av den angivna formsamlingen på de angivna koordinaterna. |
| [addTableFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String cellRange)](#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-) | Hämtar en tabell från den angivna Excel-arbetsboksfilen och lägger till den i slutet av den angivna formsamlingen på de angivna koordinaterna. |
### addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, int chartIndex, boolean embedAllWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-int-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, int chartIndex, boolean embedAllWorkbook)
```

Hämtar ett diagram från den angivna Excel-arbetsboken och lägger till det i slutet av den angivna formsamlingen på de angivna koordinaterna.

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
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | Formsamlingen som diagrammet kommer att läggas till i. |
| x | float | X-koordinaten för placering av diagrammet. |
| y | float | Y-koordinaten för placering av diagrammet. |
| workbook | [IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook) | Excel-arbetsboken. |
| worksheetName | java.lang.String | Namnet på arbetsbladet som innehåller diagrammet. |
| chartIndex | int | Nollbaserat index för diagramformen att infoga. Detta index kan erhållas med hjälp av metoden [IExcelDataWorkbook.getChartsFromWorksheet(String)](../../com.aspose.slides/iexceldataworkbook\#getChartsFromWorksheet-String-). |
| embedAllWorkbook | boolean | Om true, kommer hela arbetsboken att bäddas in i diagrammet; om false, kommer endast diagramdata att bäddas in. |

**Returnerar:**
[IChart](../../com.aspose.slides/ichart) – Diagrammet som lades till i formsamlingen.
### addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String chartName, boolean embedAllWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String chartName, boolean embedAllWorkbook)
```

Hämtar ett diagram från den angivna Excel-arbetsboken och lägger till det i slutet av den angivna formsamlingen på de angivna koordinaterna.

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
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | Formsamlingen som diagrammet kommer att läggas till i. |
| x | float | X-koordinaten för placering av diagrammet. |
| y | float | Y-koordinaten för placering av diagrammet. |
| workbook | [IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook) | Excel-arbetsboken. |
| worksheetName | java.lang.String | Namnet på arbetsbladet som innehåller diagrammet. |
| chartName | java.lang.String | Namnet på diagrammet som ska läggas till. |
| embedAllWorkbook | boolean | Om true, kommer hela arbetsboken att bäddas in i diagrammet; om false, kommer endast diagramdata att bäddas in. |

**Returnerar:**
[IChart](../../com.aspose.slides/ichart) – Diagrammet som lades till i formsamlingen.
### addChartFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String chartName, boolean embedAllWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String chartName, boolean embedAllWorkbook)
```

Hämtar ett diagram från den angivna Excel-arbetsboken och lägger till det i slutet av den angivna formsamlingen på de angivna koordinaterna.

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
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | Formsamlingen som diagrammet kommer att läggas till i. |
| x | float | X-koordinaten för placering av diagrammet. |
| y | float | Y-koordinaten för placering av diagrammet. |
| workbookStream | java.io.InputStream | En ström som innehåller arbetsbokens data. |
| worksheetName | java.lang.String | Namnet på arbetsbladet som innehåller diagrammet. |
| chartName | java.lang.String | Namnet på diagrammet som ska läggas till. |
| embedAllWorkbook | boolean | Om true, kommer hela arbetsboken att bäddas in i diagrammet; om false, kommer endast diagramdata att bäddas in. |

**Returnerar:**
[IChart](../../com.aspose.slides/ichart) – Diagrammet som lades till i formsamlingen.
### addChartFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String chartName, boolean embedWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String chartName, boolean embedWorkbook)
```

Hämtar ett diagram från den angivna Excel-arbetsboken och lägger till det i slutet av den angivna formsamlingen på de angivna koordinaterna.

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
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | Formsamlingen som diagrammet kommer att läggas till i. |
| x | float | X-koordinaten för placering av diagrammet. |
| y | float | Y-koordinaten för placering av diagrammet. |
| workbookPath | java.lang.String | Filvägen till arbetsboken som innehåller diagrammet. |
| worksheetName | java.lang.String | Namnet på arbetsbladet som innehåller diagrammet. |
| chartName | java.lang.String | Namnet på diagrammet som ska läggas till. |
| embedWorkbook | boolean | Om true, kommer arbetsboken att bäddas in i diagrammet; om false, kommer diagrammet att länkas till den externa arbetsboken. |

**Returnerar:**
[IChart](../../com.aspose.slides/ichart) – Diagrammet som lades till i formsamlingen.
### addTableFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String cellRange) {#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-}
```
public static ITable addTableFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String cellRange)
```

Hämtar en tabell från den angivna Excel-arbetsboken och lägger till den i slutet av den angivna formsamlingen på de angivna koordinaterna.

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
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | Formsamlingen som tabellen kommer att läggas till i. |
| x | float | X-koordinaten för placering av tabellen. |
| y | float | Y-koordinaten för placering av tabellen. |
| workbook | [IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook) | Excel-arbetsboken. |
| worksheetName | java.lang.String | Namnet på arbetsbladet som innehåller tabellen. |
| cellRange | java.lang.String | Cellerna som definierar tabellen (t.ex. "A1:D10"). |

**Returnerar:**
[ITable](../../com.aspose.slides/itable) – Tabellen som lades till i formsamlingen.
### addTableFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String cellRange) {#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-}
```
public static ITable addTableFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String cellRange)
```

Hämtar en tabell från den angivna Excel-arbetsboksfilen och lägger till den i slutet av den angivna formsamlingen på de angivna koordinaterna.

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
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | Formsamlingen som tabellen kommer att läggas till i. |
| x | float | X-koordinaten för placering av tabellen. |
| y | float | Y-koordinaten för placering av tabellen. |
| workbookPath | java.lang.String | Sökvägen till Excel-arbetsboksfilen. |
| worksheetName | java.lang.String | Namnet på arbetsbladet som innehåller tabellen. |
| cellRange | java.lang.String | Cellerna som definierar tabellen (t.ex. "A1:D10"). |

**Returnerar:**
[ITable](../../com.aspose.slides/itable) – Tabellen som lades till i formsamlingen.
### addTableFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String cellRange) {#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-}
```
public static ITable addTableFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String cellRange)
```

Hämtar en tabell från den angivna Excel-arbetsboksfilen och lägger till den i slutet av den angivna formsamlingen på de angivna koordinaterna.

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
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | Formsamlingen som tabellen kommer att läggas till i. |
| x | float | X-koordinaten för placering av tabellen. |
| y | float | Y-koordinaten för placering av tabellen. |
| workbookStream | java.io.InputStream | En ström som innehåller arbetsbokens data. |
| worksheetName | java.lang.String | Namnet på arbetsbladet som innehåller tabellen. |
| cellRange | java.lang.String | Cellerna som definierar tabellen (t.ex. "A1:D10"). |

**Returnerar:**
[ITable](../../com.aspose.slides/itable) – Tabellen som lades till i formsamlingen.