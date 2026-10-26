---
title: ExcelWorkbookImporter
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Fornisce funzionalità per importare contenuti da una cartella di lavoro Excel in una presentazione.
type: docs
url: /it/com.aspose.slides/excelworkbookimporter/
---
**Eredità:**
java.lang.Object
```
public class ExcelWorkbookImporter
```

Fornisce funzionalità per importare contenuti da una cartella di lavoro Excel in una presentazione.

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, int chartIndex, boolean embedAllWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-int-boolean-) | Recupera un grafico dal workbook Excel specificato e lo aggiunge alla fine della collezione di forme fornita alle coordinate specificate. |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String chartName, boolean embedAllWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-boolean-) | Recupera un grafico dal workbook Excel specificato e lo aggiunge alla fine della collezione di forme fornita alle coordinate specificate. |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String chartName, boolean embedAllWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-boolean-) | Recupera un grafico dal workbook Excel specificato e lo aggiunge alla fine della collezione di forme fornita alle coordinate specificate. |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String chartName, boolean embedWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-boolean-) | Recupera un grafico dal workbook Excel specificato e lo aggiunge alla fine della collezione di forme fornita alle coordinate specificate. |
| [addTableFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String cellRange)](#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-) | Recupera una tabella dal workbook Excel specificato e la aggiunge alla fine della collezione di forme fornita alle coordinate specificate. |
| [addTableFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String cellRange)](#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-) | Recupera una tabella dal file di workbook Excel specificato e la aggiunge alla fine della collezione di forme fornita alle coordinate specificate. |
| [addTableFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String cellRange)](#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-) | Recupera una tabella dal file di workbook Excel specificato e la aggiunge alla fine della collezione di forme fornita alle coordinate specificate. |

### addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, int chartIndex, boolean embedAllWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-int-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, int chartIndex, boolean embedAllWorkbook)
```

Recupera un grafico dal workbook Excel specificato e lo aggiunge alla fine della collezione di forme fornita alle coordinate specificate.

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

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | La collezione di forme a cui verrà aggiunto il grafico. |
| x | float | La coordinata X per posizionare il grafico. |
| y | float | La coordinata Y per posizionare il grafico. |
| workbook | [IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook) | La cartella di lavoro Excel. |
| worksheetName | java.lang.String | Il nome del foglio di lavoro che contiene il grafico. |
| chartIndex | int | L'indice basato su zero della forma del grafico da inserire. Questo indice può essere ottenuto usando il metodo [IExcelDataWorkbook.getChartsFromWorksheet(String)](../../com.aspose.slides/iexceldataworkbook\#getChartsFromWorksheet-String-). |
| embedAllWorkbook | boolean | Se true, l'intero workbook sarà incorporato nel grafico; se false, saranno incorporati solo i dati del grafico. |

**Restituisce:**
[IChart](../../com.aspose.slides/ichart) - Il grafico che è stato aggiunto alla collezione di forme.

### addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String chartName, boolean embedAllWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String chartName, boolean embedAllWorkbook)
```

Recupera un grafico dal workbook Excel specificato e lo aggiunge alla fine della collezione di forme fornita alle coordinate specificate.

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

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | La collezione di forme a cui verrà aggiunto il grafico. |
| x | float | La coordinata X per posizionare il grafico. |
| y | float | La coordinata Y per posizionare il grafico. |
| workbook | [IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook) | La cartella di lavoro Excel. |
| worksheetName | java.lang.String | Il nome del foglio di lavoro che contiene il grafico. |
| chartName | java.lang.String | Il nome del grafico da aggiungere. |
| embedAllWorkbook | boolean | Se true, l'intero workbook sarà incorporato nel grafico; se false, saranno incorporati solo i dati del grafico. |

**Restituisce:**
[IChart](../../com.aspose.slides/ichart) - Il grafico che è stato aggiunto alla collezione di forme.

### addChartFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String chartName, boolean embedAllWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String chartName, boolean embedAllWorkbook)
```

Recupera un grafico dal workbook Excel specificato e lo aggiunge alla fine della collezione di forme fornita alle coordinate specificate.

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

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | La collezione di forme a cui verrà aggiunto il grafico. |
| x | float | La coordinata X per posizionare il grafico. |
| y | float | La coordinata Y per posizionare il grafico. |
| workbookStream | java.io.InputStream | Un flusso contenente i dati del workbook. |
| worksheetName | java.lang.String | Il nome del foglio di lavoro che contiene il grafico. |
| chartName | java.lang.String | Il nome del grafico da aggiungere. |
| embedAllWorkbook | boolean | Se true, l'intero workbook sarà incorporato nel grafico; se false, saranno incorporati solo i dati del grafico. |

**Restituisce:**
[IChart](../../com.aspose.slides/ichart) - Il grafico che è stato aggiunto alla collezione di forme.

### addChartFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String chartName, boolean embedWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String chartName, boolean embedWorkbook)
```

Recupera un grafico dal workbook Excel specificato e lo aggiunge alla fine della collezione di forme fornita alle coordinate specificate.

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

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | La collezione di forme a cui verrà aggiunto il grafico. |
| x | float | La coordinata X per posizionare il grafico. |
| y | float | La coordinata Y per posizionare il grafico. |
| workbookPath | java.lang.String | Il percorso del file al workbook contenente il grafico. |
| worksheetName | java.lang.String | Il nome del foglio di lavoro che contiene il grafico. |
| chartName | java.lang.String | Il nome del grafico da aggiungere. |
| embedWorkbook | boolean | Se true, il workbook sarà incorporato nel grafico; se false, il grafico collegherà al workbook esterno. |

**Restituisce:**
[IChart](../../com.aspose.slides/ichart) - Il grafico che è stato aggiunto alla collezione di forme.

### addTableFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String cellRange) {#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-}
```
public static ITable addTableFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String cellRange)
```

Recupera una tabella dal workbook Excel specificato e la aggiunge alla fine della collezione di forme fornita alle coordinate specificate.

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

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | La collezione di forme a cui sarà aggiunta la tabella. |
| x | float | La coordinata X per posizionare la tabella. |
| y | float | La coordinata Y per posizionare la tabella. |
| workbook | [IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook) | La cartella di lavoro Excel. |
| worksheetName | java.lang.String | Il nome del foglio di lavoro che contiene la tabella. |
| cellRange | java.lang.String | L'intervallo di celle che definisce la tabella (ad esempio, "A1:D10"). |

**Restituisce:**
[ITable](../../com.aspose.slides/itable) - La tabella che è stata aggiunta alla collezione di forme.

### addTableFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String cellRange) {#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-}
```
public static ITable addTableFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String cellRange)
```

Recupera una tabella dal file di workbook Excel specificato e la aggiunge alla fine della collezione di forme fornita alle coordinate specificate.

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

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | La collezione di forme a cui sarà aggiunta la tabella. |
| x | float | La coordinata X per posizionare la tabella. |
| y | float | La coordinata Y per posizionare la tabella. |
| workbookPath | java.lang.String | Il percorso al file del workbook Excel. |
| worksheetName | java.lang.String | Il nome del foglio di lavoro che contiene la tabella. |
| cellRange | java.lang.String | L'intervallo di celle che definisce la tabella (ad esempio, "A1:D10"). |

**Restituisce:**
[ITable](../../com.aspose.slides/itable) - La tabella che è stata aggiunta alla collezione di forme.

### addTableFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String cellRange) {#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-}
```
public static ITable addTableFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String cellRange)
```

Recupera una tabella dal file di workbook Excel specificato e la aggiunge alla fine della collezione di forme fornita alle coordinate specificate.

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

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | La collezione di forme a cui sarà aggiunta la tabella. |
| x | float | La coordinata X per posizionare la tabella. |
| y | float | La coordinata Y per posizionare la tabella. |
| workbookStream | java.io.InputStream | Un flusso contenente i dati del workbook. |
| worksheetName | java.lang.String | Il nome del foglio di lavoro che contiene la tabella. |
| cellRange | java.lang.String | L'intervallo di celle che definisce la tabella (ad esempio, "A1:D10"). |

**Restituisce:**
[ITable](../../com.aspose.slides/itable) - La tabella che è stata aggiunta alla collezione di forme.