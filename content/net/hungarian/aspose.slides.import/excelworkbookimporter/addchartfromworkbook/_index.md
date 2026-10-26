---
title: AddChartFromWorkbook
second_title: Aspose.Sildes .NET API referencia
description: Lekéri a diagramot a megadott Excel munkafüzetből, és a megadott koordinátákon a forma gyűjtemény végéhez adja hozzá.
type: docs
weight: 10
url: /hu/aspose.slides.import/excelworkbookimporter/addchartfromworkbook/
---
## AddChartFromWorkbook(IShapeCollection, float, float, IExcelDataWorkbook, string, int, bool) {#addchartfromworkbook}

Lekéri a diagramot a megadott Excel munkafüzetből, és a megadott koordinátákon a forma gyűjtemény végéhez adja hozzá.

```csharp
public static IChart AddChartFromWorkbook(IShapeCollection shapes, float x, float y, 
    IExcelDataWorkbook workbook, string worksheetName, int chartIndex, bool embedAllWorkbook)
```

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| shapes | IShapeCollection | Az a forma gyűjtemény, amelyhez a diagram hozzá lesz adva. |
| x | Single | A diagram X koordinátája. |
| y | Single | A diagram Y koordinátája. |
| workbook | IExcelDataWorkbook | Az Excel munkafüzet. |
| worksheetName | String | A munkalap neve, amely a diagramot tartalmazza. |
| chartIndex | Int32 | A beszúrandó diagram forma nullától számolt indexe. Az index a [`GetChartsFromWorksheet`](../../../aspose.slides.excel/iexceldataworkbook/getchartsfromworksheet) metódussal szerezhető be. |
| embedAllWorkbook | Boolean | Ha `true`, az egész munkafüzet be lesz ágyazva a diagramba; ha `false`, csak a diagram adatai lesznek beágyazva. |

### Visszatérési érték

A forma gyűjteményhez hozzáadott diagram.

### Kivételek

| kivétel | feltétel |
| --- | --- |
| ArgumentException | Akkor dobódik, ha egy kötelező paraméter null, üres, vagy ha a diagram nem található a munkafüzetben. |

### Példák

Példa:

```csharp
[C#]
IExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
using (var pres = new Presentation())
{
    ExcelWorkbookImporter.AddChartFromWorkbook(pres.Slides[0].Shapes, 10, 10, wb, worksheetName, chartName, false);
    pres.Save("result.pptx", SaveFormat.Pptx);
}
```

### Lásd még

* interfész [IChart](../../../aspose.slides.charts/ichart)
* interfész [IShapeCollection](../../../aspose.slides/ishapecollection)
* interfész [IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook)
* osztály [ExcelWorkbookImporter](../../excelworkbookimporter)
* névtér [Aspose.Slides.Import](../../excelworkbookimporter)
* összeállítás [Aspose.Slides](../../../)

---

## AddChartFromWorkbook(IShapeCollection, float, float, IExcelDataWorkbook, string, string, bool) {#addchartfromworkbook_1}

Lekéri a diagramot a megadott Excel munkafüzetből, és a megadott koordinátákon a forma gyűjtemény végéhez adja hozzá.

```csharp
public static IChart AddChartFromWorkbook(IShapeCollection shapes, float x, float y, 
    IExcelDataWorkbook workbook, string worksheetName, string chartName, bool embedAllWorkbook)
```

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| shapes | IShapeCollection | Az a forma gyűjtemény, amelyhez a diagram hozzá lesz adva. |
| x | Single | A diagram X koordinátája. |
| y | Single | A diagram Y koordinátája. |
| workbook | IExcelDataWorkbook | Az Excel munkafüzet. |
| worksheetName | String | A munkalap neve, amely a diagramot tartalmazza. |
| chartName | String | A hozzáadandó diagram neve. |
| embedAllWorkbook | Boolean | Ha `true`, az egész munkafüzet be lesz ágyazva a diagramba; ha `false`, csak a diagram adatai lesznek beágyazva. |

### Visszatérési érték

A forma gyűjteményhez hozzáadott diagram.

### Kivételek

| kivétel | feltétel |
| --- | --- |
| ArgumentException | Akkor dobódik, ha egy kötelező paraméter null, üres, vagy ha a diagram nem található a munkafüzetben. |

### Példák

Példa:

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

### Lásd még

* interfész [IChart](../../../aspose.slides.charts/ichart)
* interfész [IShapeCollection](../../../aspose.slides/ishapecollection)
* interfész [IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook)
* osztály [ExcelWorkbookImporter](../../excelworkbookimporter)
* névtér [Aspose.Slides.Import](../../excelworkbookimporter)
* összeállítás [Aspose.Slides](../../../)

---

## AddChartFromWorkbook(IShapeCollection, float, float, Stream, string, string, bool) {#addchartfromworkbook_2}

Lekéri a diagramot a megadott Excel munkafüzetből, és a megadott koordinátákon a forma gyűjtemény végéhez adja hozzá.

```csharp
public static IChart AddChartFromWorkbook(IShapeCollection shapes, float x, float y, 
    Stream workbookStream, string worksheetName, string chartName, bool embedAllWorkbook)
```

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| shapes | IShapeCollection | Az a forma gyűjtemény, amelyhez a diagram hozzá lesz adva. |
| x | Single | A diagram X koordinátája. |
| y | Single | A diagram Y koordinátája. |
| workbookStream | Stream | A munkafüzet adatot tartalmazó adatfolyam. |
| worksheetName | String | A munkalap neve, amely a diagramot tartalmazza. |
| chartName | String | A hozzáadandó diagram neve. |
| embedAllWorkbook | Boolean | Ha `true`, az egész munkafüzet be lesz ágyazva a diagramba; ha `false`, csak a diagram adatai lesznek beágyazva. |

### Visszatérési érték

A forma gyűjteményhez hozzáadott diagram.

### Kivételek

| kivétel | feltétel |
| --- | --- |
| ArgumentException | Akkor dobódik, ha egy kötelező paraméter null, üres, vagy ha a diagram nem található a munkafüzetben. |
| InvalidOperationException | Akkor dobódik, ha a bemeneti adat nem támogatott formátumban van. |

### Példák

Példa:

```csharp
[C#]
using (var fStream = new FileStream(workbookPath, FileMode.Open, FileAccess.Read))
using (var pres = new Presentation())
{
    ExcelWorkbookImporter.AddChartFromWorkbook(pres.LayoutSlides[0].Shapes, 10, 10, fStream, worksheetName, chartName, true);
    pres.Save("result.pptx", SaveFormat.Pptx);
}
```

### Lásd még

* interfész [IChart](../../../aspose.slides.charts/ichart)
* interfész [IShapeCollection](../../../aspose.slides/ishapecollection)
* osztály [ExcelWorkbookImporter](../../excelworkbookimporter)
* névtér [Aspose.Slides.Import](../../excelworkbookimporter)
* összeállítás [Aspose.Slides](../../../)

---

## AddChartFromWorkbook(IShapeCollection, float, float, string, string, string, bool) {#addchartfromworkbook_3}

Lekéri a diagramot a megadott Excel munkafüzetből, és a megadott koordinátákon a forma gyűjtemény végéhez adja hozzá.

```csharp
public static IChart AddChartFromWorkbook(IShapeCollection shapes, float x, float y, 
    string workbookPath, string worksheetName, string chartName, bool embedWorkbook)
```

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| shapes | IShapeCollection | Az a forma gyűjtemény, amelyhez a diagram hozzá lesz adva. |
| x | Single | A diagram X koordinátája. |
| y | Single | A diagram Y koordinátája. |
| workbookPath | String | A diagramot tartalmazó munkafüzet fájl elérési útja. |
| worksheetName | String | A munkalap neve, amely a diagramot tartalmazza. |
| chartName | String | A hozzáadandó diagram neve. |
| embedWorkbook | Boolean | Ha `true`, a munkafüzet be lesz ágyazva a diagramba; ha `false`, a diagram külső munkafüzetre fog hivatkozni. |

### Visszatérési érték

A forma gyűjteményhez hozzáadott diagram.

### Kivételek

| kivétel | feltétel |
| --- | --- |
| ArgumentException | Akkor dobódik, ha egy kötelező paraméter null, üres, vagy ha a diagram nem található a munkafüzetben. |
| IOException | Akkor dobódik, ha I/O hiba lép fel a fájl elérése közben. |
| InvalidOperationException | Akkor dobódik, ha a bemeneti adat nem támogatott formátumban van. |

### Példák

Példa:

```csharp
[C#]
using (var pres = new Presentation())
{
    ExcelWorkbookImporter.AddChartFromWorkbook(pres.Slides[0].Shapes, 10, 10, workbookPath, worksheetName, chartName, false);
    pres.Save("result.pptx", SaveFormat.Pptx);
}
```

### Lásd még

* interfész [IChart](../../../aspose.slides.charts/ichart)
* interfész [IShapeCollection](../../../aspose.slides/ishapecollection)
* osztály [ExcelWorkbookImporter](../../excelworkbookimporter)
* névtér [Aspose.Slides.Import](../../excelworkbookimporter)
* összeállítás [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->