---
title: AddChartFromWorkbook
second_title: Riferimento API Aspose.Sildes per .NET
description: Recupera un grafico dal workbook Excel specificato e lo aggiunge alla fine della collezione di forme fornita alle coordinate specificate.
type: docs
weight: 10
url: /it/aspose.slides.import/excelworkbookimporter/addchartfromworkbook/
---
## AddChartFromWorkbook(IShapeCollection, float, float, IExcelDataWorkbook, string, int, bool) {#addchartfromworkbook}

Recupera un grafico dal workbook Excel specificato e lo aggiunge alla fine della collezione di forme fornita alle coordinate specificate.

```csharp
public static IChart AddChartFromWorkbook(IShapeCollection shapes, float x, float y, 
    IExcelDataWorkbook workbook, string worksheetName, int chartIndex, bool embedAllWorkbook)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| shapes | IShapeCollection | La collezione di forme a cui il grafico verrà aggiunto. |
| x | Single | La coordinata X per posizionare il grafico. |
| y | Single | La coordinata Y per posizionare il grafico. |
| workbook | IExcelDataWorkbook | Il workbook Excel. |
| worksheetName | String | Il nome del foglio di lavoro che contiene il grafico. |
| chartIndex | Int32 | L'indice basato su zero della forma del grafico da inserire. Questo indice può essere ottenuto usando il metodo [`GetChartsFromWorksheet`](../../../aspose.slides.excel/iexceldataworkbook/getchartsfromworksheet). |
| embedAllWorkbook | Boolean | Se `true`, l'intero workbook verrà incorporato nel grafico; se `false`, verranno incorporati solo i dati del grafico. |

### Valore restituito

Il grafico che è stato aggiunto alla collezione di forme.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentException | Generata quando un parametro richiesto è null, vuoto, o se il grafico non può essere trovato nel workbook. |

### Esempi

Esempio:

```csharp
[C#]
IExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
using (var pres = new Presentation())
{
    ExcelWorkbookImporter.AddChartFromWorkbook(pres.Slides[0].Shapes, 10, 10, wb, worksheetName, chartName, false);
    pres.Save("result.pptx", SaveFormat.Pptx);
}
```

### Vedi anche

* interface [IChart](../../../aspose.slides.charts/ichart)
* interface [IShapeCollection](../../../aspose.slides/ishapecollection)
* interface [IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook)
* class [ExcelWorkbookImporter](../../excelworkbookimporter)
* namespace [Aspose.Slides.Import](../../excelworkbookimporter)
* assembly [Aspose.Slides](../../../)

---

## AddChartFromWorkbook(IShapeCollection, float, float, IExcelDataWorkbook, string, string, bool) {#addchartfromworkbook_1}

Recupera un grafico dal workbook Excel specificato e lo aggiunge alla fine della collezione di forme fornita alle coordinate specificate.

```csharp
public static IChart AddChartFromWorkbook(IShapeCollection shapes, float x, float y, 
    IExcelDataWorkbook workbook, string worksheetName, string chartName, bool embedAllWorkbook)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| shapes | IShapeCollection | La collezione di forme a cui il grafico verrà aggiunto. |
| x | Single | La coordinata X per posizionare il grafico. |
| y | Single | La coordinata Y per posizionare il grafico. |
| workbook | IExcelDataWorkbook | Il workbook Excel. |
| worksheetName | String | Il nome del foglio di lavoro che contiene il grafico. |
| chartName | String | Il nome del grafico da aggiungere. |
| embedAllWorkbook | Boolean | Se `true`, l'intero workbook verrà incorporato nel grafico; se `false`, verranno incorporati solo i dati del grafico. |

### Valore restituito

Il grafico che è stato aggiunto alla collezione di forme.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentException | Generata quando un parametro richiesto è null, vuoto, o se il grafico non può essere trovato nel workbook. |

### Esempi

Esempio:

```csharp
[C#]
IExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
using (var pres = new Presentation())
{
    string worksheetName = "worksheet name";
    var worksheetCharts = wb.GetChartsFromWorksheet(worksheetName);
    foreach (var chart in worksheetCharts)
    {
        ISlide slide = pres.Slides.AddEmptySlide(pres.LayoutSlides[0]);
        ExcelWorkbookImporter.AddChartFromWorkbook(slide.Shapes, 10, 10, wb, worksheetName, chart.Key, false);
    }
    pres.Save("result.pptx", SaveFormat.Pptx);
}
```

### Vedi anche

* interface [IChart](../../../aspose.slides.charts/ichart)
* interface [IShapeCollection](../../../aspose.slides/ishapecollection)
* interface [IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook)
* class [ExcelWorkbookImporter](../../excelworkbookimporter)
* namespace [Aspose.Slides.Import](../../excelworkbookimporter)
* assembly [Aspose.Slides](../../../)

---

## AddChartFromWorkbook(IShapeCollection, float, float, Stream, string, string, bool) {#addchartfromworkbook_2}

Recupera un grafico dal workbook Excel specificato e lo aggiunge alla fine della collezione di forme fornita alle coordinate specificate.

```csharp
public static IChart AddChartFromWorkbook(IShapeCollection shapes, float x, float y, 
    Stream workbookStream, string worksheetName, string chartName, bool embedAllWorkbook)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| shapes | IShapeCollection | La collezione di forme a cui il grafico verrà aggiunto. |
| x | Single | La coordinata X per posizionare il grafico. |
| y | Single | La coordinata Y per posizionare il grafico. |
| workbookStream | Stream | Un flusso contenente i dati del workbook. |
| worksheetName | String | Il nome del foglio di lavoro che contiene il grafico. |
| chartName | String | Il nome del grafico da aggiungere. |
| embedAllWorkbook | Boolean | Se `true`, l'intero workbook verrà incorporato nel grafico; se `false`, verranno incorporati solo i dati del grafico. |

### Valore restituito

Il grafico che è stato aggiunto alla collezione di forme.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentException | Generata quando un parametro richiesto è null, vuoto, o se il grafico non può essere trovato nel workbook. |
| InvalidOperationException | Generata quando i dati di input sono in un formato non supportato. |

### Esempi

Esempio:

```csharp
[C#]
using (var fStream = new FileStream(workbookPath, FileMode.Open, FileAccess.Read))
using (var pres = new Presentation())
{
    ExcelWorkbookImporter.AddChartFromWorkbook(pres.LayoutSlides[0].Shapes, 10, 10, fStream, worksheetName, chartName, true);
    pres.Save("result.pptx", SaveFormat.Pptx);
}
```

### Vedi anche

* interface [IChart](../../../aspose.slides.charts/ichart)
* interface [IShapeCollection](../../../aspose.slides/ishapecollection)
* class [ExcelWorkbookImporter](../../excelworkbookimporter)
* namespace [Aspose.Slides.Import](../../excelworkbookimporter)
* assembly [Aspose.Slides](../../../)

---

## AddChartFromWorkbook(IShapeCollection, float, float, string, string, string, bool) {#addchartfromworkbook_3}

Recupera un grafico dal workbook Excel specificato e lo aggiunge alla fine della collezione di forme fornita alle coordinate specificate.

```csharp
public static IChart AddChartFromWorkbook(IShapeCollection shapes, float x, float y, 
    string workbookPath, string worksheetName, string chartName, bool embedWorkbook)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| shapes | IShapeCollection | La collezione di forme a cui il grafico verrà aggiunto. |
| x | Single | La coordinata X per posizionare il grafico. |
| y | Single | La coordinata Y per posizionare il grafico. |
| workbookPath | String | Il percorso file del workbook contenente il grafico. |
| worksheetName | String | Il nome del foglio di lavoro che contiene il grafico. |
| chartName | String | Il nome del grafico da aggiungere. |
| embedWorkbook | Boolean | Se `true`, il workbook verrà incorporato nel grafico; se `false`, il grafico collegherà al workbook esterno. |

### Valore restituito

Il grafico che è stato aggiunto alla collezione di forme.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentException | Generata quando un parametro richiesto è null, vuoto, o se il grafico non può essere trovato nel workbook. |
| IOException | Generata quando si verifica un errore di I/O durante l'accesso al file. |
| InvalidOperationException | Generata quando i dati di input sono in un formato non supportato. |

### Esempi

Esempio:

```csharp
[C#]
using (var pres = new Presentation())
{
    ExcelWorkbookImporter.AddChartFromWorkbook(pres.Slides[0].Shapes, 10, 10, workbookPath, worksheetName, chartName, false);
    pres.Save("result.pptx", SaveFormat.Pptx);
}
```

### Vedi anche

* interface [IChart](../../../aspose.slides.charts/ichart)
* interface [IShapeCollection](../../../aspose.slides/ishapecollection)
* class [ExcelWorkbookImporter](../../excelworkbookimporter)
* namespace [Aspose.Slides.Import](../../excelworkbookimporter)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->