---
title: ExcelWorkbookImporter
second_title: Aspose.Slides voor Android via Java API-referentie
description: Biedt functionaliteit voor het importeren van inhoud vanuit een Excel-werkmap in een presentatie.
type: docs
url: /nl/com.aspose.slides/excelworkbookimporter/
---
**Erfenis:**
java.lang.Object
```
public class ExcelWorkbookImporter
```

Biedt functionaliteit om inhoud vanuit een Excel-werkmap te importeren in een presentatie.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, int chartIndex, boolean embedAllWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-int-boolean-) | Haalt een grafiek op uit de opgegeven Excel-werkmap en voegt deze toe aan het einde van de opgegeven vormverzameling op de opgegeven coördinaten. |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String chartName, boolean embedAllWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-boolean-) | Haalt een grafiek op uit de opgegeven Excel-werkmap en voegt deze toe aan het einde van de opgegeven vormverzameling op de opgegeven coördinaten. |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String chartName, boolean embedAllWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-boolean-) | Haalt een grafiek op uit de opgegeven Excel-werkmap en voegt deze toe aan het einde van de opgegeven vormverzameling op de opgegeven coördinaten. |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String chartName, boolean embedWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-boolean-) | Haalt een grafiek op uit de opgegeven Excel-werkmap en voegt deze toe aan het einde van de opgegeven vormverzameling op de opgegeven coördinaten. |
| [addTableFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String cellRange)](#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-) | Haalt een tabel op uit de opgegeven Excel-werkmap en voegt deze toe aan het einde van de opgegeven vormverzameling op de opgegeven coördinaten. |
| [addTableFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String cellRange)](#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-) | Haalt een tabel op uit de opgegeven Excel-werkmap-bestand en voegt deze toe aan het einde van de opgegeven vormverzameling op de opgegeven coördinaten. |
| [addTableFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String cellRange)](#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-) | Haalt een tabel op uit de opgegeven Excel-werkmap-bestand en voegt deze toe aan het einde van de opgegeven vormverzameling op de opgegeven coördinaten. |

### addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, int chartIndex, boolean embedAllWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-int-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, int chartIndex, boolean embedAllWorkbook)
```

Haalt een grafiek op uit de opgegeven Excel-werkmap en voegt deze toe aan het einde van de opgegeven vormverzameling op de opgegeven coördinaten.

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | De vormverzameling waaraan de grafiek wordt toegevoegd. |
| x | float | De X-coördinaat voor het positioneren van de grafiek. |
| y | float | De Y-coördinaat voor het positioneren van de grafiek. |
| workbook | [IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook) | De Excel-werkmap. |
| worksheetName | java.lang.String | De naam van het werkblad dat de grafiek bevat. |
| chartIndex | int | De nulgebaseerde index van de grafiekvorm die moet worden ingevoegd. Deze index kan worden verkregen met behulp van de [IExcelDataWorkbook.getChartsFromWorksheet(String)](../../com.aspose.slides/iexceldataworkbook\#getChartsFromWorksheet-String-)-methode. |
| embedAllWorkbook | boolean | Indien true, wordt de volledige werkmap in de grafiek ingesloten; indien false, worden alleen de grafiekgegevens ingesloten. |

**Retour:**
[IChart](../../com.aspose.slides/ichart) - De grafiek die aan de vormverzameling is toegevoegd.

### addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String chartName, boolean embedAllWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String chartName, boolean embedAllWorkbook)
```

Haalt een grafiek op uit de opgegeven Excel-werkmap en voegt deze toe aan het einde van de opgegeven vormverzameling op de opgegeven coördinaten.

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | De vormverzameling waaraan de grafiek wordt toegevoegd. |
| x | float | De X-coördinaat voor het positioneren van de grafiek. |
| y | float | De Y-coördinaat voor het positioneren van de grafiek. |
| workbook | [IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook) | De Excel-werkmap. |
| worksheetName | java.lang.String | De naam van het werkblad dat de grafiek bevat. |
| chartName | java.lang.String | De naam van de toe te voegen grafiek. |
| embedAllWorkbook | boolean | Indien true, wordt de volledige werkmap in de grafiek ingesloten; indien false, worden alleen de grafiekgegevens ingesloten. |

**Retour:**
[IChart](../../com.aspose.slides/ichart) - De grafiek die aan de vormverzameling is toegevoegd.

### addChartFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String chartName, boolean embedAllWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String chartName, boolean embedAllWorkbook)
```

Haalt een grafiek op uit de opgegeven Excel-werkmap en voegt deze toe aan het einde van de opgegeven vormverzameling op de opgegeven coördinaten.

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | De vormverzameling waaraan de grafiek wordt toegevoegd. |
| x | float | De X-coördinaat voor het positioneren van de grafiek. |
| y | float | De Y-coördinaat voor het positioneren van de grafiek. |
| workbookStream | java.io.InputStream | Een stream die de werkmapgegevens bevat. |
| worksheetName | java.lang.String | De naam van het werkblad dat de grafiek bevat. |
| chartName | java.lang.String | De naam van de toe te voegen grafiek. |
| embedAllWorkbook | boolean | Indien true, wordt de volledige werkmap in de grafiek ingesloten; indien false, worden alleen de grafiekgegevens ingesloten. |

**Retour:**
[IChart](../../com.aspose.slides/ichart) - De grafiek die aan de vormverzameling is toegevoegd.

### addChartFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String chartName, boolean embedWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String chartName, boolean embedWorkbook)
```

Haalt een grafiek op uit de opgegeven Excel-werkmap en voegt deze toe aan het einde van de opgegeven vormverzameling op de opgegeven coördinaten.

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | De vormverzameling waaraan de grafiek wordt toegevoegd. |
| x | float | De X-coördinaat voor het positioneren van de grafiek. |
| y | float | De Y-coördinaat voor het positioneren van de grafiek. |
| workbookPath | java.lang.String | Het bestandspad naar de werkmap die de grafiek bevat. |
| worksheetName | java.lang.String | De naam van het werkblad dat de grafiek bevat. |
| chartName | java.lang.String | De naam van de toe te voegen grafiek. |
| embedWorkbook | boolean | Indien true, wordt de werkmap in de grafiek ingesloten; indien false, zal de grafiek koppelen aan de externe werkmap. |

**Retour:**
[IChart](../../com.aspose.slides/ichart) - De grafiek die aan de vormverzameling is toegevoegd.

### addTableFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String cellRange) {#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-}
```
public static ITable addTableFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String cellRange)
```

Haalt een tabel op uit de opgegeven Excel-werkmap en voegt deze toe aan het einde van de opgegeven vormverzameling op de opgegeven coördinaten.

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | De vormverzameling waaraan de tabel wordt toegevoegd. |
| x | float | De X-coördinaat voor het positioneren van de tabel. |
| y | float | De Y-coördinaat voor het positioneren van de tabel. |
| workbook | [IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook) | De Excel-werkmap. |
| worksheetName | java.lang.String | De naam van het werkblad dat de tabel bevat. |
| cellRange | java.lang.String | Het celbereik dat de tabel definieert (bijvoorbeeld "A1:D10"). |

**Retour:**
[ITable](../../com.aspose.slides/itable) - De tabel die aan de vormverzameling is toegevoegd.

### addTableFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String cellRange) {#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-}
```
public static ITable addTableFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String cellRange)
```

Haalt een tabel op uit het opgegeven Excel-werkmap-bestand en voegt deze toe aan het einde van de opgegeven vormverzameling op de opgegeven coördinaten.

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | De vormverzameling waaraan de tabel wordt toegevoegd. |
| x | float | De X-coördinaat voor het positioneren van de tabel. |
| y | float | De Y-coördinaat voor het positioneren van de tabel. |
| workbookPath | java.lang.String | Het pad naar het Excel-werkmap-bestand. |
| worksheetName | java.lang.String | De naam van het werkblad dat de tabel bevat. |
| cellRange | java.lang.String | Het celbereik dat de tabel definieert (bijvoorbeeld "A1:D10"). |

**Retour:**
[ITable](../../com.aspose.slides/itable) - De tabel die aan de vormverzameling is toegevoegd.

### addTableFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String cellRange) {#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-}
```
public static ITable addTableFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String cellRange)
```

Haalt een tabel op uit het opgegeven Excel-werkmap-bestand en voegt deze toe aan het einde van de opgegeven vormverzameling op de opgegeven coördinaten.

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | De vormverzameling waaraan de tabel wordt toegevoegd. |
| x | float | De X-coördinaat voor het positioneren van de tabel. |
| y | float | De Y-coördinaat voor het positioneren van de tabel. |
| workbookStream | java.io.InputStream | Een stream die de werkmapgegevens bevat. |
| worksheetName | java.lang.String | De naam van het werkblad dat de tabel bevat. |
| cellRange | java.lang.String | Het celbereik dat de tabel definieert (bijvoorbeeld "A1:D10"). |

**Retour:**
[ITable](../../com.aspose.slides/itable) - De tabel die aan de vormverzameling is toegevoegd.