---
title: ExcelWorkbookImporter
second_title: Aspose.Slides für Java API-Referenz
description: Bietet Funktionalität zum Importieren von Inhalten aus einer Excel-Arbeitsmappe in eine Präsentation.
type: docs
url: /de/com.aspose.slides/excelworkbookimporter/
---
**Vererbung:**
java.lang.Object
```
public class ExcelWorkbookImporter
```

Bietet Funktionalität zum Importieren von Inhalten aus einer Excel-Arbeitsmappe in eine Präsentation.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, int chartIndex, boolean embedAllWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-int-boolean-) | Ruft ein Diagramm aus der angegebenen Excel-Arbeitsmappe ab und fügt es am Ende der angegebenen Formsammlung an den angegebenen Koordinaten hinzu. |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String chartName, boolean embedAllWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-boolean-) | Ruft ein Diagramm aus der angegebenen Excel-Arbeitsmappe ab und fügt es am Ende der angegebenen Formsammlung an den angegebenen Koordinaten hinzu. |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String chartName, boolean embedAllWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-boolean-) | Ruft ein Diagramm aus der angegebenen Excel-Arbeitsmappe ab und fügt es am Ende der angegebenen Formsammlung an den angegebenen Koordinaten hinzu. |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String chartName, boolean embedWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-boolean-) | Ruft ein Diagramm aus der angegebenen Excel-Arbeitsmappe ab und fügt es am Ende der angegebenen Formsammlung an den angegebenen Koordinaten hinzu. |
| [addTableFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String cellRange)](#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-) | Ruft eine Tabelle aus der angegebenen Excel-Arbeitsmappe ab und fügt sie am Ende der angegebenen Formsammlung an den angegebenen Koordinaten hinzu. |
| [addTableFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String cellRange)](#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-) | Ruft eine Tabelle aus der angegebenen Excel-Arbeitsmappe-Datei ab und fügt sie am Ende der angegebenen Formsammlung an den angegebenen Koordinaten hinzu. |
| [addTableFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String cellRange)](#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-) | Ruft eine Tabelle aus der angegebenen Excel-Arbeitsmappe-Datei ab und fügt sie am Ende der angegebenen Formsammlung an den angegebenen Koordinaten hinzu. |

### addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, int chartIndex, boolean embedAllWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-int-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, int chartIndex, boolean embedAllWorkbook)
```

Ruft ein Diagramm aus der angegebenen Excel-Arbeitsmappe ab und fügt es am Ende der angegebenen Formsammlung an den angegebenen Koordinaten hinzu.

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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | Die Formsammlung, zu der das Diagramm hinzugefügt wird. |
| x | float | Die X-Koordinate für die Platzierung des Diagramms. |
| y | float | Die Y-Koordinate für die Platzierung des Diagramms. |
| workbook | [IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook) | Die Excel-Arbeitsmappe. |
| worksheetName | java.lang.String | Der Name des Arbeitsblatts, das das Diagramm enthält. |
| chartIndex | int | Der nullbasierte Index der einzufügenden Diagrammform. Dieser Index kann mit der [IExcelDataWorkbook.getChartsFromWorksheet(String)](../../com.aspose.slides/iexceldataworkbook\#getChartsFromWorksheet-String-)-Methode ermittelt werden. |
| embedAllWorkbook | boolean | Falls true, wird die gesamte Arbeitsmappe im Diagramm eingebettet; falls false, werden nur die Diagrammdaten eingebettet. |

**Rückgabewert:**
[IChart](../../com.aspose.slides/ichart) - Das Diagramm, das der Formsammlung hinzugefügt wurde.

### addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String chartName, boolean embedAllWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String chartName, boolean embedAllWorkbook)
```

Ruft ein Diagramm aus der angegebenen Excel-Arbeitsmappe ab und fügt es am Ende der angegebenen Formsammlung an den angegebenen Koordinaten hinzu.

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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | Die Formsammlung, zu der das Diagramm hinzugefügt wird. |
| x | float | Die X-Koordinate für die Platzierung des Diagramms. |
| y | float | Die Y-Koordinate für die Platzierung des Diagramms. |
| workbook | [IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook) | Die Excel-Arbeitsmappe. |
| worksheetName | java.lang.String | Der Name des Arbeitsblatts, das das Diagramm enthält. |
| chartName | java.lang.String | Der Name des hinzuzufügenden Diagramms. |
| embedAllWorkbook | boolean | Falls true, wird die gesamte Arbeitsmappe im Diagramm eingebettet; falls false, werden nur die Diagrammdaten eingebettet. |

**Rückgabewert:**
[IChart](../../com.aspose.slides/ichart) - Das Diagramm, das der Formsammlung hinzugefügt wurde.

### addChartFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String chartName, boolean embedAllWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String chartName, boolean embedAllWorkbook)
```

Ruft ein Diagramm aus der angegebenen Excel-Arbeitsmappe ab und fügt es am Ende der angegebenen Formsammlung an den angegebenen Koordinaten hinzu.

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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | Die Formsammlung, zu der das Diagramm hinzugefügt wird. |
| x | float | Die X-Koordinate für die Platzierung des Diagramms. |
| y | float | Die Y-Koordinate für die Platzierung des Diagramms. |
| workbookStream | java.io.InputStream | Ein Stream, der die Arbeitsmappendaten enthält. |
| worksheetName | java.lang.String | Der Name des Arbeitsblatts, das das Diagramm enthält. |
| chartName | java.lang.String | Der Name des hinzuzufügenden Diagramms. |
| embedAllWorkbook | boolean | Falls true, wird die gesamte Arbeitsmappe im Diagramm eingebettet; falls false, werden nur die Diagrammdaten eingebettet. |

**Rückgabewert:**
[IChart](../../com.aspose.slides/ichart) - Das Diagramm, das der Formsammlung hinzugefügt wurde.

### addChartFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String chartName, boolean embedWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String chartName, boolean embedWorkbook)
```

Ruft ein Diagramm aus der angegebenen Excel-Arbeitsmappe ab und fügt es am Ende der angegebenen Formsammlung an den angegebenen Koordinaten hinzu.

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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | Die Formsammlung, zu der das Diagramm hinzugefügt wird. |
| x | float | Die X-Koordinate für die Platzierung des Diagramms. |
| y | float | Die Y-Koordinate für die Platzierung des Diagramms. |
| workbookPath | java.lang.String | Der Dateipfad zur Arbeitsmappe, die das Diagramm enthält. |
| worksheetName | java.lang.String | Der Name des Arbeitsblatts, das das Diagramm enthält. |
| chartName | java.lang.String | Der Name des hinzuzufügenden Diagramms. |
| embedWorkbook | boolean | Falls true, wird die Arbeitsmappe im Diagramm eingebettet; falls false, wird das Diagramm auf die externe Arbeitsmappe verlinken. |

**Rückgabewert:**
[IChart](../../com.aspose.slides/ichart) - Das Diagramm, das der Formsammlung hinzugefügt wurde.

### addTableFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String cellRange) {#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-}
```
public static ITable addTableFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String cellRange)
```

Ruft eine Tabelle aus der angegebenen Excel-Arbeitsmappe ab und fügt sie am Ende der angegebenen Formsammlung an den angegebenen Koordinaten hinzu.

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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | Die Formsammlung, zu der die Tabelle hinzugefügt wird. |
| x | float | Die X-Koordinate für die Platzierung der Tabelle. |
| y | float | Die Y-Koordinate für die Platzierung der Tabelle. |
| workbook | [IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook) | Die Excel-Arbeitsmappe. |
| worksheetName | java.lang.String | Der Name des Arbeitsblatts, das die Tabelle enthält. |
| cellRange | java.lang.String | Der Zellbereich, der die Tabelle definiert (z. B. "A1:D10"). |

**Rückgabewert:**
[ITable](../../com.aspose.slides/itable) - Die Tabelle, die der Formsammlung hinzugefügt wurde.

### addTableFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String cellRange) {#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-}
```
public static ITable addTableFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String cellRange)
```

Ruft eine Tabelle aus der angegebenen Excel-Arbeitsmappe-Datei ab und fügt sie am Ende der angegebenen Formsammlung an den angegebenen Koordinaten hinzu.

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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | Die Formsammlung, zu der die Tabelle hinzugefügt wird. |
| x | float | Die X-Koordinate für die Platzierung der Tabelle. |
| y | float | Die Y-Koordinate für die Platzierung der Tabelle. |
| workbookPath | java.lang.String | Der Pfad zur Excel-Arbeitsdatei. |
| worksheetName | java.lang.String | Der Name des Arbeitsblatts, das die Tabelle enthält. |
| cellRange | java.lang.String | Der Zellbereich, der die Tabelle definiert (z. B. "A1:D10"). |

**Rückgabewert:**
[ITable](../../com.aspose.slides/itable) - Die Tabelle, die der Formsammlung hinzugefügt wurde.

### addTableFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String cellRange) {#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-}
```
public static ITable addTableFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String cellRange)
```

Ruft eine Tabelle aus der angegebenen Excel-Arbeitsmappe-Datei ab und fügt sie am Ende der angegebenen Formsammlung an den angegebenen Koordinaten hinzu.

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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | Die Formsammlung, zu der die Tabelle hinzugefügt wird. |
| x | float | Die X-Koordinate für die Platzierung der Tabelle. |
| y | float | Die Y-Koordinate für die Platzierung der Tabelle. |
| workbookStream | java.io.InputStream | Ein Stream, der die Arbeitsmappendaten enthält. |
| worksheetName | java.lang.String | Der Name des Arbeitsblatts, das die Tabelle enthält. |
| cellRange | java.lang.String | Der Zellbereich, der die Tabelle definiert (z. B. "A1:D10"). |

**Rückgabewert:**
[ITable](../../com.aspose.slides/itable) - Die Tabelle, die der Formsammlung hinzugefügt wurde.