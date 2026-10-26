---
title: AddTableFromWorkbook
second_title: Riferimento API Aspose.Sildes per .NET
description: Recupera una tabella dal workbook Excel specificato e la aggiunge alla fine della collezione di forme fornita alle coordinate specificate.
type: docs
weight: 20
url: /it/aspose.slides.import/excelworkbookimporter/addtablefromworkbook/
---
## AddTableFromWorkbook(IShapeCollection, float, float, IExcelDataWorkbook, string, string) {#addtablefromworkbook}

Recupera una tabella dal workbook Excel specificato e la aggiunge alla fine della collezione di forme fornita alle coordinate specificate.

```csharp
public static ITable AddTableFromWorkbook(IShapeCollection shapes, float x, float y, 
    IExcelDataWorkbook workbook, string worksheetName, string cellRange)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| shapes | IShapeCollection | La collezione di forme a cui la tabella verrà aggiunta. |
| x | Single | La coordinata X per posizionare la tabella. |
| y | Single | La coordinata Y per posizionare la tabella. |
| workbook | IExcelDataWorkbook | Il workbook Excel. |
| worksheetName | String | Il nome del foglio di lavoro che contiene la tabella. |
| cellRange | String | L’intervallo di celle che definisce la tabella (ad es., "A1:D10"). |

### Valore di ritorno

La tabella che è stata aggiunta alla collezione di forme.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentException | Viene sollevata quando un parametro obbligatorio è nullo o vuoto, o quando il foglio di lavoro o l’intervallo di celle specificati sono non validi. |
| InvalidOperationException | Viene sollevata quando i dati di input sono in un formato non supportato. |

### Esempi

```csharp
[C#]
IExcelDataWorkbook workbook = new ExcelDataWorkbook(testFile);
using (var pres = new Presentation())
{
    ExcelWorkbookImporter.AddTableFromWorkbook(pres.Slides[0].Shapes, 10, 10, workbook, worksheetName, "A1:D10");
    pres.Save("result.pptx", SaveFormat.Pptx);
}
```

### Vedi anche

* interfaccia [ITable](../../../aspose.slides/itable)
* interfaccia [IShapeCollection](../../../aspose.slides/ishapecollection)
* interfaccia [IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook)
* classe [ExcelWorkbookImporter](../../excelworkbookimporter)
* namespace [Aspose.Slides.Import](../../excelworkbookimporter)
* assembly [Aspose.Slides](../../../)

---

## AddTableFromWorkbook(IShapeCollection, float, float, string, string, string) {#addtablefromworkbook_2}

Recupera una tabella dal file workbook Excel specificato e la aggiunge alla fine della collezione di forme fornita alle coordinate specificate.

```csharp
public static ITable AddTableFromWorkbook(IShapeCollection shapes, float x, float y, 
    string workbookPath, string worksheetName, string cellRange)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| shapes | IShapeCollection | La collezione di forme a cui la tabella verrà aggiunta. |
| x | Single | La coordinata X per posizionare la tabella. |
| y | Single | La coordinata Y per posizionare la tabella. |
| workbookPath | String | Il percorso al file workbook Excel. |
| worksheetName | String | Il nome del foglio di lavoro che contiene la tabella. |
| cellRange | String | L’intervallo di celle che definisce la tabella (ad es., "A1:D10"). |

### Valore di ritorno

La tabella che è stata aggiunta alla collezione di forme.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentException | Viene sollevata quando un parametro obbligatorio è nullo o vuoto, o quando il foglio di lavoro o l’intervallo di celle specificati sono non validi. |
| IOException | Viene sollevata quando si verifica un errore di I/O durante l’accesso al file workbook. |
| InvalidOperationException | Viene sollevata quando i dati di input sono in un formato non supportato. |

### Esempi

```csharp
[C#]
using (var pres = new Presentation())
{
    ExcelWorkbookImporter.AddTableFromWorkbook(pres.Slides[0].Shapes, 10, 10, workbookPath, worksheetName, "A1:D10");
    pres.Save("result.pptx", SaveFormat.Pptx);
}
```

### Vedi anche

* interfaccia [ITable](../../../aspose.slides/itable)
* interfaccia [IShapeCollection](../../../aspose.slides/ishapecollection)
* classe [ExcelWorkbookImporter](../../excelworkbookimporter)
* namespace [Aspose.Slides.Import](../../excelworkbookimporter)
* assembly [Aspose.Slides](../../../)

---

## AddTableFromWorkbook(IShapeCollection, float, float, Stream, string, string) {#addtablefromworkbook_1}

Recupera una tabella dal file workbook Excel specificato e la aggiunge alla fine della collezione di forme fornita alle coordinate specificate.

```csharp
public static ITable AddTableFromWorkbook(IShapeCollection shapes, float x, float y, 
    Stream workbookStream, string worksheetName, string cellRange)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| shapes | IShapeCollection | La collezione di forme a cui la tabella verrà aggiunta. |
| x | Single | La coordinata X per posizionare la tabella. |
| y | Single | La coordinata Y per posizionare la tabella. |
| workbookStream | Stream | Un flusso contenente i dati del workbook. |
| worksheetName | String | Il nome del foglio di lavoro che contiene la tabella. |
| cellRange | String | L’intervallo di celle che definisce la tabella (ad es., "A1:D10"). |

### Valore di ritorno

La tabella che è stata aggiunta alla collezione di forme.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentException | Viene sollevata quando un parametro obbligatorio è nullo o vuoto, o quando il foglio di lavoro o l’intervallo di celle specificati sono non validi. |
| InvalidOperationException | Viene sollevata quando i dati di input sono in un formato non supportato. |

### Esempi

```csharp
[C#]
using (var fStream = new FileStream(workbookPath, FileMode.Open, FileAccess.Read))
using (var pres = new Presentation())
{
    ExcelWorkbookImporter.AddTableFromWorkbook(pres.Slides[0].Shapes, 10, 10, fStream, worksheetName, "A1:D10");
    pres.Save("result.pptx", SaveFormat.Pptx);
}
```

### Vedi anche

* interfaccia [ITable](../../../aspose.slides/itable)
* interfaccia [IShapeCollection](../../../aspose.slides/ishapecollection)
* classe [ExcelWorkbookImporter](../../excelworkbookimporter)
* namespace [Aspose.Slides.Import](../../excelworkbookimporter)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->