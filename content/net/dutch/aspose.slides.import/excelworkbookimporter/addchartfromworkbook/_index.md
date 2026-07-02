---
title: AddChartFromWorkbook
second_title: Aspose.Sildes voor .NET API-referentie
description: Haalt een grafiek op uit de opgegeven Excel-werkmap en voegt deze toe aan het einde van de opgegeven shape-collectie op de opgegeven coördinaten.
type: docs
weight: 10
url: /nl/aspose.slides.import/excelworkbookimporter/addchartfromworkbook/
---
## AddChartFromWorkbook(IShapeCollection, float, float, IExcelDataWorkbook, string, int, bool) {#addchartfromworkbook}

Haalt een grafiek op uit de opgegeven Excel-werkmap en voegt deze toe aan het einde van de opgegeven shape-collectie op de opgegeven coördinaten.

```csharp
public static IChart AddChartFromWorkbook(IShapeCollection shapes, float x, float y, 
    IExcelDataWorkbook workbook, string worksheetName, int chartIndex, bool embedAllWorkbook)
```

| Parameter | Type | Description |
| --- | --- | --- |
| shapes | IShapeCollection | De shape-collectie waaraan de grafiek wordt toegevoegd. |
| x | Single | De X-coördinaat voor het positioneren van de grafiek. |
| y | Single | De Y-coördinaat voor het positioneren van de grafiek. |
| workbook | IExcelDataWorkbook | De Excel-werkmap. |
| worksheetName | String | De naam van het werkblad dat de grafiek bevat. |
| chartIndex | Int32 | De nul-gebaseerde index van de grafiek-shape die moet worden ingevoegd. Deze index kan worden verkregen met de [`GetChartsFromWorksheet`](../../../aspose.slides.excel/iexceldataworkbook/getchartsfromworksheet)-methode. |
| embedAllWorkbook | Boolean | Als `true`, wordt de volledige werkmap in de grafiek ingebed; als `false`, worden alleen de grafiek-gegevens ingebed. |

### Return Value

De grafiek die is toegevoegd aan de shape-collectie.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Wordt gegooid wanneer een vereist argument null, leeg of wanneer de grafiek niet gevonden kan worden in de werkmap. |

### Examples

Voorbeeld:

```csharp
[C#]
IExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
using (var pres = new Presentation())
{
    ExcelWorkbookImporter.AddChartFromWorkbook(pres.Slides[0].Shapes, 10, 10, wb, worksheetName, chartName, false);
    pres.Save("result.pptx", SaveFormat.Pptx);
}
```

### See Also

* interface [IChart](../../../aspose.slides.charts/ichart)
* interface [IShapeCollection](../../../aspose.slides/ishapecollection)
* interface [IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook)
* klasse [ExcelWorkbookImporter](../../excelworkbookimporter)
* naamruimte [Aspose.Slides.Import](../../excelworkbookimporter)
* assembly [Aspose.Slides](../../../)

---

## AddChartFromWorkbook(IShapeCollection, float, float, IExcelDataWorkbook, string, string, bool) {#addchartfromworkbook_1}

Haalt een grafiek op uit de opgegeven Excel-werkmap en voegt deze toe aan het einde van de opgegeven shape-collectie op de opgegeven coördinaten.

```csharp
public static IChart AddChartFromWorkbook(IShapeCollection shapes, float x, float y, 
    IExcelDataWorkbook workbook, string worksheetName, string chartName, bool embedAllWorkbook)
```

| Parameter | Type | Description |
| --- | --- | --- |
| shapes | IShapeCollection | De shape-collectie waaraan de grafiek wordt toegevoegd. |
| x | Single | De X-coördinaat voor het positioneren van de grafiek. |
| y | Single | De Y-coördinaat voor het positioneren van de grafiek. |
| workbook | IExcelDataWorkbook | De Excel-werkmap. |
| worksheetName | String | De naam van het werkblad dat de grafiek bevat. |
| chartName | String | De naam van de grafiek die moet worden toegevoegd. |
| embedAllWorkbook | Boolean | Als `true`, wordt de volledige werkmap in de grafiek ingebed; als `false`, worden alleen de grafiek-gegevens ingebed. |

### Return Value

De grafiek die is toegevoegd aan de shape-collectie.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Wordt gegooid wanneer een vereist argument null, leeg of wanneer de grafiek niet gevonden kan worden in de werkmap. |

### Examples

Voorbeeld:

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

### See Also

* interface [IChart](../../../aspose.slides.charts/ichart)
* interface [IShapeCollection](../../../aspose.slides/ishapecollection)
* interface [IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook)
* klasse [ExcelWorkbookImporter](../../excelworkbookimporter)
* naamruimte [Aspose.Slides.Import](../../excelworkbookimporter)
* assembly [Aspose.Slides](../../../)

---

## AddChartFromWorkbook(IShapeCollection, float, float, Stream, string, string, bool) {#addchartfromworkbook_2}

Haalt een grafiek op uit de opgegeven Excel-werkmap en voegt deze toe aan het einde van de opgegeven shape-collectie op de opgegeven coördinaten.

```csharp
public static IChart AddChartFromWorkbook(IShapeCollection shapes, float x, float y, 
    Stream workbookStream, string worksheetName, string chartName, bool embedAllWorkbook)
```

| Parameter | Type | Description |
| --- | --- | --- |
| shapes | IShapeCollection | De shape-collectie waaraan de grafiek wordt toegevoegd. |
| x | Single | De X-coördinaat voor het positioneren van de grafiek. |
| y | Single | De Y-coördinaat voor het positioneren van de grafiek. |
| workbookStream | Stream | Een stream met de werkmap-gegevens. |
| worksheetName | String | De naam van het werkblad dat de grafiek bevat. |
| chartName | String | De naam van de grafiek die moet worden toegevoegd. |
| embedAllWorkbook | Boolean | Als `true`, wordt de volledige werkmap in de grafiek ingebed; als `false`, worden alleen de grafiek-gegevens ingebed. |

### Return Value

De grafiek die is toegevoegd aan de shape-collectie.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Wordt gegooid wanneer een vereist argument null, leeg of wanneer de grafiek niet gevonden kan worden in de werkmap. |
| InvalidOperationException | Wordt gegooid wanneer de invoergegevens een niet-ondersteund formaat hebben. |

### Examples

Voorbeeld:

```csharp
[C#]
using (var fStream = new FileStream(workbookPath, FileMode.Open, FileAccess.Read))
using (var pres = new Presentation())
{
    ExcelWorkbookImporter.AddChartFromWorkbook(pres.LayoutSlides[0].Shapes, 10, 10, fStream, worksheetName, chartName, true);
    pres.Save("result.pptx", SaveFormat.Pptx);
}
```

### See Also

* interface [IChart](../../../aspose.slides.charts/ichart)
* interface [IShapeCollection](../../../aspose.slides/ishapecollection)
* klasse [ExcelWorkbookImporter](../../excelworkbookimporter)
* naamruimte [Aspose.Slides.Import](../../excelworkbookimporter)
* assembly [Aspose.Slides](../../../)

---

## AddChartFromWorkbook(IShapeCollection, float, float, string, string, string, bool) {#addchartfromworkbook_3}

Haalt een grafiek op uit de opgegeven Excel-werkmap en voegt deze toe aan het einde van de opgegeven shape-collectie op de opgegeven coördinaten.

```csharp
public static IChart AddChartFromWorkbook(IShapeCollection shapes, float x, float y, 
    string workbookPath, string worksheetName, string chartName, bool embedWorkbook)
```

| Parameter | Type | Description |
| --- | --- | --- |
| shapes | IShapeCollection | De shape-collectie waaraan de grafiek wordt toegevoegd. |
| x | Single | De X-coördinaat voor het positioneren van de grafiek. |
| y | Single | De Y-coördinaat voor het positioneren van de grafiek. |
| workbookPath | String | Het bestandspad naar de werkmap die de grafiek bevat. |
| worksheetName | String | De naam van het werkblad dat de grafiek bevat. |
| chartName | String | De naam van de grafiek die moet worden toegevoegd. |
| embedWorkbook | Boolean | Als `true`, wordt de werkmap in de grafiek ingebed; als `false`, zal de grafiek linken naar de externe werkmap. |

### Return Value

De grafiek die is toegevoegd aan de shape-collectie.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Wordt gegooid wanneer een vereist argument null, leeg of wanneer de grafiek niet gevonden kan worden in de werkmap. |
| IOException | Wordt gegooid wanneer er een I/O-fout optreedt bij het openen van het bestand. |
| InvalidOperationException | Wordt gegooid wanneer de invoergegevens een niet-ondersteund formaat hebben. |

### Examples

Voorbeeld:

```csharp
[C#]
using (var pres = new Presentation())
{
    ExcelWorkbookImporter.AddChartFromWorkbook(pres.Slides[0].Shapes, 10, 10, workbookPath, worksheetName, chartName, false);
    pres.Save("result.pptx", SaveFormat.Pptx);
}
```

### See Also

* interface [IChart](../../../aspose.slides.charts/ichart)
* interface [IShapeCollection](../../../aspose.slides/ishapecollection)
* klasse [ExcelWorkbookImporter](../../excelworkbookimporter)
* naamruimte [Aspose.Slides.Import](../../excelworkbookimporter)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->