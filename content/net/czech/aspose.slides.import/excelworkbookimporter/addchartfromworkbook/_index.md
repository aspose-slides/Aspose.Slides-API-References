---
title: AddChartFromWorkbook
second_title: Aspose.Sildes pro .NET API Reference
description: Načte graf ze zadaného sešitu Excel a přidá jej na konec dané sbírky tvarů na určených souřadnicích.
type: docs
weight: 10
url: /cs/aspose.slides.import/excelworkbookimporter/addchartfromworkbook/
---
## AddChartFromWorkbook(IShapeCollection, float, float, IExcelDataWorkbook, string, int, bool) {#addchartfromworkbook}

Načte graf z určeného sešitu Excel a přidá jej na konec dané sbírky tvarů na zadaných souřadnicích.

```csharp
public static IChart AddChartFromWorkbook(IShapeCollection shapes, float x, float y, 
    IExcelDataWorkbook workbook, string worksheetName, int chartIndex, bool embedAllWorkbook)
```

| Parametr | Typ | Popis |
| --- | --- | --- |
| shapes | IShapeCollection | Sbírka tvarů, do které bude graf přidán. |
| x | Single | Souřadnice X pro umístění grafu. |
| y | Single | Souřadnice Y pro umístění grafu. |
| workbook | IExcelDataWorkbook | Sešit Excel. |
| worksheetName | String | Název listu, který obsahuje graf. |
| chartIndex | Int32 | Nulový index grafického tvaru, který se má vložit. Tento index lze získat pomocí metody [`GetChartsFromWorksheet`](../../../aspose.slides.excel/iexceldataworkbook/getchartsfromworksheet). |
| embedAllWorkbook | Boolean | Pokud je `true`, bude celý sešit vložen do grafu; pokud je `false`, budou vložena pouze data grafu. |

### Návratová hodnota

Graf, který byl přidán do sbírky tvarů.

### Výjimky

| výjimka | podmínka |
| --- | --- |
| ArgumentException | Vyvolána, když je některý požadovaný parametr null, prázdný, nebo pokud graf nelze v sešitu najít. |

### Příklady

Příklad:

```csharp
[C#]
IExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
using (var pres = new Presentation())
{
    ExcelWorkbookImporter.AddChartFromWorkbook(pres.Slides[0].Shapes, 10, 10, wb, worksheetName, chartName, false);
    pres.Save("result.pptx", SaveFormat.Pptx);
}
```

### Viz také

* rozhraní [IChart](../../../aspose.slides.charts/ichart)
* rozhraní [IShapeCollection](../../../aspose.slides/ishapecollection)
* rozhraní [IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook)
* třída [ExcelWorkbookImporter](../../excelworkbookimporter)
* jmenný prostor [Aspose.Slides.Import](../../excelworkbookimporter)
* sestavení [Aspose.Slides](../../../)

---

## AddChartFromWorkbook(IShapeCollection, float, float, IExcelDataWorkbook, string, string, bool) {#addchartfromworkbook_1}

Načte graf z určeného sešitu Excel a přidá jej na konec dané sbírky tvarů na zadaných souřadnicích.

```csharp
public static IChart AddChartFromWorkbook(IShapeCollection shapes, float x, float y, 
    IExcelDataWorkbook workbook, string worksheetName, string chartName, bool embedAllWorkbook)
```

| Parametr | Typ | Popis |
| --- | --- | --- |
| shapes | IShapeCollection | Sbírka tvarů, do které bude graf přidán. |
| x | Single | Souřadnice X pro umístění grafu. |
| y | Single | Souřadnice Y pro umístění grafu. |
| workbook | IExcelDataWorkbook | Sešit Excel. |
| worksheetName | String | Název listu, který obsahuje graf. |
| chartName | String | Název grafu, který má být přidán. |
| embedAllWorkbook | Boolean | Pokud je `true`, bude celý sešit vložen do grafu; pokud je `false`, budou vložena pouze data grafu. |

### Návratová hodnota

Graf, který byl přidán do sbírky tvarů.

### Výjimky

| výjimka | podmínka |
| --- | --- |
| ArgumentException | Vyvolána, když je některý požadovaný parametr null, prázdný, nebo pokud graf nelze v sešitu najít. |

### Příklady

Příklad:

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

### Viz také

* rozhraní [IChart](../../../aspose.slides.charts/ichart)
* rozhraní [IShapeCollection](../../../aspose.slides/ishapecollection)
* rozhraní [IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook)
* třída [ExcelWorkbookImporter](../../excelworkbookimporter)
* jmenný prostor [Aspose.Slides.Import](../../excelworkbookimporter)
* sestavení [Aspose.Slides](../../../)

---

## AddChartFromWorkbook(IShapeCollection, float, float, Stream, string, string, bool) {#addchartfromworkbook_2}

Načte graf z určeného sešitu Excel a přidá jej na konec dané sbírky tvarů na zadaných souřadnicích.

```csharp
public static IChart AddChartFromWorkbook(IShapeCollection shapes, float x, float y, 
    Stream workbookStream, string worksheetName, string chartName, bool embedAllWorkbook)
```

| Parametr | Typ | Popis |
| --- | --- | --- |
| shapes | IShapeCollection | Sbírka tvarů, do které bude graf přidán. |
| x | Single | Souřadnice X pro umístění grafu. |
| y | Single | Souřadnice Y pro umístění grafu. |
| workbookStream | Stream | Proud obsahující data sešitu. |
| worksheetName | String | Název listu, který obsahuje graf. |
| chartName | String | Název grafu, který má být přidán. |
| embedAllWorkbook | Boolean | Pokud je `true`, bude celý sešit vložen do grafu; pokud je `false`, budou vložena pouze data grafu. |

### Návratová hodnota

Graf, který byl přidán do sbírky tvarů.

### Výjimky

| výjimka | podmínka |
| --- | --- |
| ArgumentException | Vyvolána, když je některý požadovaný parametr null, prázdný, nebo pokud graf nelze v sešitu najít. |
| InvalidOperationException | Vyvolána, když jsou vstupní data ve formátu, který není podporován. |

### Příklady

Příklad:

```csharp
[C#]
using (var fStream = new FileStream(workbookPath, FileMode.Open, FileAccess.Read))
using (var pres = new Presentation())
{
    ExcelWorkbookImporter.AddChartFromWorkbook(pres.LayoutSlides[0].Shapes, 10, 10, fStream, worksheetName, chartName, true);
    pres.Save("result.pptx", SaveFormat.Pptx);
}
```

### Viz také

* rozhraní [IChart](../../../aspose.slides.charts/ichart)
* rozhraní [IShapeCollection](../../../aspose.slides/ishapecollection)
* třída [ExcelWorkbookImporter](../../excelworkbookimporter)
* jmenný prostor [Aspose.Slides.Import](../../excelworkbookimporter)
* sestavení [Aspose.Slides](../../../)

---

## AddChartFromWorkbook(IShapeCollection, float, float, string, string, string, bool) {#addchartfromworkbook_3}

Načte graf z určeného sešitu Excel a přidá jej na konec dané sbírky tvarů na zadaných souřadnicích.

```csharp
public static IChart AddChartFromWorkbook(IShapeCollection shapes, float x, float y, 
    string workbookPath, string worksheetName, string chartName, bool embedWorkbook)
```

| Parametr | Typ | Popis |
| --- | --- | --- |
| shapes | IShapeCollection | Sbírka tvarů, do které bude graf přidán. |
| x | Single | Souřadnice X pro umístění grafu. |
| y | Single | Souřadnice Y pro umístění grafu. |
| workbookPath | String | Cesta k souboru sešitu obsahujícímu graf. |
| worksheetName | String | Název listu, který obsahuje graf. |
| chartName | String | Název grafu, který má být přidán. |
| embedWorkbook | Boolean | Pokud je `true`, bude sešit vložen do grafu; pokud je `false`, bude graf odkazovat na externí sešit. |

### Návratová hodnota

Graf, který byl přidán do sbírky tvarů.

### Výjimky

| výjimka | podmínka |
| --- | --- |
| ArgumentException | Vyvolána, když je některý požadovaný parametr null, prázdný, nebo pokud graf nelze v sešitu najít. |
| IOException | Vyvolána, když nastane chyba V/V při přístupu k souboru. |
| InvalidOperationException | Vyvolána, když jsou vstupní data ve formátu, který není podporován. |

### Příklady

Příklad:

```csharp
[C#]
using (var pres = new Presentation())
{
    ExcelWorkbookImporter.AddChartFromWorkbook(pres.Slides[0].Shapes, 10, 10, workbookPath, worksheetName, chartName, false);
    pres.Save("result.pptx", SaveFormat.Pptx);
}
```

### Viz také

* rozhraní [IChart](../../../aspose.slides.charts/ichart)
* rozhraní [IShapeCollection](../../../aspose.slides/ishapecollection)
* třída [ExcelWorkbookImporter](../../excelworkbookimporter)
* jmenný prostor [Aspose.Slides.Import](../../excelworkbookimporter)
* sestavení [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->