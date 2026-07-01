---
title: AddChartFromWorkbook
second_title: Aspose.Sildes för .NET API-referens
description: Hämtar ett diagram från den angivna Excel-arbetsboken och lägger till det i slutet av den angivna formsamlingen på de angivna koordinaterna.
type: docs
weight: 10
url: /sv/aspose.slides.import/excelworkbookimporter/addchartfromworkbook/
---
## AddChartFromWorkbook(IShapeCollection, float, float, IExcelDataWorkbook, string, int, bool) {#addchartfromworkbook}

Hämtar ett diagram från den angivna Excel-arbetsboken och lägger till det i slutet av den angivna formsamlingen på de angivna koordinaterna.

```csharp
public static IChart AddChartFromWorkbook(IShapeCollection shapes, float x, float y, 
    IExcelDataWorkbook workbook, string worksheetName, int chartIndex, bool embedAllWorkbook)
```

| Parameter | Type | Description |
| --- | --- | --- |
| shapes | IShapeCollection | Formsamlingen som diagrammet ska läggas till i. |
| x | Single | X-koordinaten för placering av diagrammet. |
| y | Single | Y-koordinaten för placering av diagrammet. |
| workbook | IExcelDataWorkbook | Excel-arbetsboken. |
| worksheetName | String | Namnet på kalkylbladet som innehåller diagrammet. |
| chartIndex | Int32 | Det nollbaserade indexet för diagramformen som ska infogas. Detta index kan erhållas med hjälp av [`GetChartsFromWorksheet`](../../../aspose.slides.excel/iexceldataworkbook/getchartsfromworksheet)-metoden. |
| embedAllWorkbook | Boolean | Om `true` kommer hela arbetsboken att bäddas in i diagrammet; om `false` kommer endast diagramdata att bäddas in. |

### Returvärde

Diagrammet som lades till i formsamlingen.

### Undantag

| exception | condition |
| --- | --- |
| ArgumentException | Kastas när någon obligatorisk parameter är null, tom eller om diagrammet inte kan hittas i arbetsboken. |

### Exempel

Exempel:

```csharp
[C#]
IExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
using (var pres = new Presentation())
{
    ExcelWorkbookImporter.AddChartFromWorkbook(pres.Slides[0].Shapes, 10, 10, wb, worksheetName, chartName, false);
    pres.Save("result.pptx", SaveFormat.Pptx);
}
```

### Se även

* gränssnitt [IChart](../../../aspose.slides.charts/ichart)
* gränssnitt [IShapeCollection](../../../aspose.slides/ishapecollection)
* gränssnitt [IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook)
* klass [ExcelWorkbookImporter](../../excelworkbookimporter)
* namnrymd [Aspose.Slides.Import](../../excelworkbookimporter)
* assembly [Aspose.Slides](../../../)

---

## AddChartFromWorkbook(IShapeCollection, float, float, IExcelDataWorkbook, string, string, bool) {#addchartfromworkbook_1}

Hämtar ett diagram från den angivna Excel-arbetsboken och lägger till det i slutet av den angivna formsamlingen på de angivna koordinaterna.

```csharp
public static IChart AddChartFromWorkbook(IShapeCollection shapes, float x, float y, 
    IExcelDataWorkbook workbook, string worksheetName, string chartName, bool embedAllWorkbook)
```

| Parameter | Type | Description |
| --- | --- | --- |
| shapes | IShapeCollection | Formsamlingen som diagrammet ska läggas till i. |
| x | Single | X-koordinaten för placering av diagrammet. |
| y | Single | Y-koordinaten för placering av diagrammet. |
| workbook | IExcelDataWorkbook | Excel-arbetsboken. |
| worksheetName | String | Namnet på kalkylbladet som innehåller diagrammet. |
| chartName | String | Namnet på diagrammet som ska läggas till. |
| embedAllWorkbook | Boolean | Om `true` kommer hela arbetsboken att bäddas in i diagrammet; om `false` kommer endast diagramdata att bäddas in. |

### Returvärde

Diagrammet som lades till i formsamlingen.

### Undantag

| exception | condition |
| --- | --- |
| ArgumentException | Kastas när någon obligatorisk parameter är null, tom eller om diagrammet inte kan hittas i arbetsboken. |

### Exempel

Exempel:

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

### Se även

* gränssnitt [IChart](../../../aspose.slides.charts/ichart)
* gränssnitt [IShapeCollection](../../../aspose.slides/ishapecollection)
* gränssnitt [IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook)
* klass [ExcelWorkbookImporter](../../excelworkbookimporter)
* namnrymd [Aspose.Slides.Import](../../excelworkbookimporter)
* assembly [Aspose.Slides](../../../)

---

## AddChartFromWorkbook(IShapeCollection, float, float, Stream, string, string, bool) {#addchartfromworkbook_2}

Hämtar ett diagram från den angivna Excel-arbetsboken och lägger till det i slutet av den angivna formsamlingen på de angivna koordinaterna.

```csharp
public static IChart AddChartFromWorkbook(IShapeCollection shapes, float x, float y, 
    Stream workbookStream, string worksheetName, string chartName, bool embedAllWorkbook)
```

| Parameter | Type | Description |
| --- | --- | --- |
| shapes | IShapeCollection | Formsamlingen som diagrammet ska läggas till i. |
| x | Single | X-koordinaten för placering av diagrammet. |
| y | Single | Y-koordinaten för placering av diagrammet. |
| workbookStream | Stream | En ström som innehåller arbetsboksdata. |
| worksheetName | String | Namnet på kalkylbladet som innehåller diagrammet. |
| chartName | String | Namnet på diagrammet som ska läggas till. |
| embedAllWorkbook | Boolean | Om `true` kommer hela arbetsboken att bäddas in i diagrammet; om `false` kommer endast diagramdata att bäddas in. |

### Returvärde

Diagrammet som lades till i formsamlingen.

### Undantag

| exception | condition |
| --- | --- |
| ArgumentException | Kastas när någon obligatorisk parameter är null, tom eller om diagrammet inte kan hittas i arbetsboken. |
| InvalidOperationException | Kastas när indata är i ett format som inte stöds. |

### Exempel

Exempel:

```csharp
[C#]
using (var fStream = new FileStream(workbookPath, FileMode.Open, FileAccess.Read))
using (var pres = new Presentation())
{
    ExcelWorkbookImporter.AddChartFromWorkbook(pres.LayoutSlides[0].Shapes, 10, 10, fStream, worksheetName, chartName, true);
    pres.Save("result.pptx", SaveFormat.Pptx);
}
```

### Se även

* gränssnitt [IChart](../../../aspose.slides.charts/ichart)
* gränssnitt [IShapeCollection](../../../aspose.slides/ishapecollection)
* klass [ExcelWorkbookImporter](../../excelworkbookimporter)
* namnrymd [Aspose.Slides.Import](../../excelworkbookimporter)
* assembly [Aspose.Slides](../../../)

---

## AddChartFromWorkbook(IShapeCollection, float, float, string, string, string, bool) {#addchartfromworkbook_3}

Hämtar ett diagram från den angivna Excel-arbetsboken och lägger till det i slutet av den angivna formsamlingen på de angivna koordinaterna.

```csharp
public static IChart AddChartFromWorkbook(IShapeCollection shapes, float x, float y, 
    string workbookPath, string worksheetName, string chartName, bool embedWorkbook)
```

| Parameter | Type | Description |
| --- | --- | --- |
| shapes | IShapeCollection | Formsamlingen som diagrammet ska läggas till i. |
| x | Single | X-koordinaten för placering av diagrammet. |
| y | Single | Y-koordinaten för placering av diagrammet. |
| workbookPath | String | Filsökvägen till arbetsboken som innehåller diagrammet. |
| worksheetName | String | Namnet på kalkylbladet som innehåller diagrammet. |
| chartName | String | Namnet på diagrammet som ska läggas till. |
| embedWorkbook | Boolean | Om `true` kommer arbetsboken att bäddas in i diagrammet; om `false` kommer diagrammet att länkas till den externa arbetsboken. |

### Returvärde

Diagrammet som lades till i formsamlingen.

### Undantag

| exception | condition |
| --- | --- |
| ArgumentException | Kastas när någon obligatorisk parameter är null, tom eller om diagrammet inte kan hittas i arbetsboken. |
| IOException | Kastas när ett I/O-fel inträffar vid åtkomst till filen. |
| InvalidOperationException | Kastas när indata är i ett format som inte stöds. |

### Exempel

Exempel:

```csharp
[C#]
using (var pres = new Presentation())
{
    ExcelWorkbookImporter.AddChartFromWorkbook(pres.Slides[0].Shapes, 10, 10, workbookPath, worksheetName, chartName, false);
    pres.Save("result.pptx", SaveFormat.Pptx);
}
```

### Se även

* gränssnitt [IChart](../../../aspose.slides.charts/ichart)
* gränssnitt [IShapeCollection](../../../aspose.slides/ishapecollection)
* klass [ExcelWorkbookImporter](../../excelworkbookimporter)
* namnrymd [Aspose.Slides.Import](../../excelworkbookimporter)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->