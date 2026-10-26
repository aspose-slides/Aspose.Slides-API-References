---
title: AddTableFromWorkbook
second_title: Aspose.Sildes för .NET API-referens
description: Hämtar en tabell från den angivna Excel-arbetsboken och lägger till den i slutet av den angivna formsamlingen på de angivna koordinaterna.
type: docs
weight: 20
url: /sv/aspose.slides.import/excelworkbookimporter/addtablefromworkbook/
---
## AddTableFromWorkbook(IShapeCollection, float, float, IExcelDataWorkbook, string, string) {#addtablefromworkbook}

Hämtar en tabell från den angivna Excel-arbetsboken och lägger till den i slutet av den angivna formsamlingen på de angivna koordinaterna.

```csharp
public static ITable AddTableFromWorkbook(IShapeCollection shapes, float x, float y, 
    IExcelDataWorkbook workbook, string worksheetName, string cellRange)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| shapes | IShapeCollection | Formsamlingen som tabellen kommer att läggas till i. |
| x | Single | X-koordinaten för placering av tabellen. |
| y | Single | Y-koordinaten för placering av tabellen. |
| workbook | IExcelDataWorkbook | Excel-arbetsboken. |
| worksheetName | String | Namnet på kalkylbladet som innehåller tabellen. |
| cellRange | String | Cellområdet som definierar tabellen (till exempel "A1:D10"). |

### Returvärde

Tabellen som lades till i formsamlingen.

### Undantag

| Undantag | Villkor |
| --- | --- |
| ArgumentException | Kastas när någon obligatorisk parameter är null eller tom, eller när det angivna kalkylbladet eller cellområdet är ogiltigt. |
| InvalidOperationException | Kastas när indata är i ett format som inte stöds. |

### Exempel

```csharp
[C#]
IExcelDataWorkbook workbook = new ExcelDataWorkbook(testFile);
using (var pres = new Presentation())
{
    ExcelWorkbookImporter.AddTableFromWorkbook(pres.Slides[0].Shapes, 10, 10, workbook, worksheetName, "A1:D10");
    pres.Save("result.pptx", SaveFormat.Pptx);
}
```

### Se även

* gränssnitt [ITable](../../../aspose.slides/itable)
* gränssnitt [IShapeCollection](../../../aspose.slides/ishapecollection)
* gränssnitt [IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook)
* klass [ExcelWorkbookImporter](../../excelworkbookimporter)
* namnrymd [Aspose.Slides.Import](../../excelworkbookimporter)
* samling [Aspose.Slides](../../../)

---

## AddTableFromWorkbook(IShapeCollection, float, float, string, string, string) {#addtablefromworkbook_2}

Hämtar en tabell från den angivna Excel-arbetsbokfilen och lägger till den i slutet av den angivna formsamlingen på de angivna koordinaterna.

```csharp
public static ITable AddTableFromWorkbook(IShapeCollection shapes, float x, float y, 
    string workbookPath, string worksheetName, string cellRange)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| shapes | IShapeCollection | Formsamlingen som tabellen kommer att läggas till i. |
| x | Single | X-koordinaten för placering av tabellen. |
| y | Single | Y-koordinaten för placering av tabellen. |
| workbookPath | String | Sökvägen till Excel-arbetsbokfilen. |
| worksheetName | String | Namnet på kalkylbladet som innehåller tabellen. |
| cellRange | String | Cellområdet som definierar tabellen (till exempel "A1:D10"). |

### Returvärde

Tabellen som lades till i formsamlingen.

### Undantag

| Undantag | Villkor |
| --- | --- |
| ArgumentException | Kastas när någon obligatorisk parameter är null eller tom, eller när det angivna kalkylbladet eller cellområdet är ogiltigt. |
| IOException | Kastas när ett I/O-fel uppstår vid åtkomst av arbetsbokfilen. |
| InvalidOperationException | Kastas när indata är i ett format som inte stöds. |

### Exempel

```csharp
[C#]
using (var pres = new Presentation())
{
    ExcelWorkbookImporter.AddTableFromWorkbook(pres.Slides[0].Shapes, 10, 10, workbookPath, worksheetName, "A1:D10");
    pres.Save("result.pptx", SaveFormat.Pptx);
}
```

### Se även

* gränssnitt [ITable](../../../aspose.slides/itable)
* gränssnitt [IShapeCollection](../../../aspose.slides/ishapecollection)
* klass [ExcelWorkbookImporter](../../excelworkbookimporter)
* namnrymd [Aspose.Slides.Import](../../excelworkbookimporter)
* samling [Aspose.Slides](../../../)

---

## AddTableFromWorkbook(IShapeCollection, float, float, Stream, string, string) {#addtablefromworkbook_1}

Hämtar en tabell från den angivna Excel-arbetsbokfilen och lägger till den i slutet av den angivna formsamlingen på de angivna koordinaterna.

```csharp
public static ITable AddTableFromWorkbook(IShapeCollection shapes, float x, float y, 
    Stream workbookStream, string worksheetName, string cellRange)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| shapes | IShapeCollection | Formsamlingen som tabellen kommer att läggas till i. |
| x | Single | X-koordinaten för placering av tabellen. |
| y | Single | Y-koordinaten för placering av tabellen. |
| workbookStream | Stream | En ström som innehåller arbetsbokdata. |
| worksheetName | String | Namnet på kalkylbladet som innehåller tabellen. |
| cellRange | String | Cellområdet som definierar tabellen (till exempel "A1:D10"). |

### Returvärde

Tabellen som lades till i formsamlingen.

### Undantag

| Undantag | Villkor |
| --- | --- |
| ArgumentException | Kastas när någon obligatorisk parameter är null eller tom, eller när det angivna kalkylbladet eller cellområdet är ogiltigt. |
| InvalidOperationException | Kastas när indata är i ett format som inte stöds. |

### Exempel

```csharp
[C#]
using (var fStream = new FileStream(workbookPath, FileMode.Open, FileAccess.Read))
using (var pres = new Presentation())
{
    ExcelWorkbookImporter.AddTableFromWorkbook(pres.Slides[0].Shapes, 10, 10, fStream, worksheetName, "A1:D10");
    pres.Save("result.pptx", SaveFormat.Pptx);
}
```

### Se även

* gränssnitt [ITable](../../../aspose.slides/itable)
* gränssnitt [IShapeCollection](../../../aspose.slides/ishapecollection)
* klass [ExcelWorkbookImporter](../../excelworkbookimporter)
* namnrymd [Aspose.Slides.Import](../../excelworkbookimporter)
* samling [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->