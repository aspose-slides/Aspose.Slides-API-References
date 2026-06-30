---
title: AddChartFromWorkbook
second_title: Aspose.Sildes dla .NET – Dokumentacja API
description: Pobiera wykres z określonego skoroszytu Excel i dodaje go na koniec podanej kolekcji kształtów w określonych współrzędnych.
type: docs
weight: 10
url: /pl/aspose.slides.import/excelworkbookimporter/addchartfromworkbook/
---
## AddChartFromWorkbook(IShapeCollection, float, float, IExcelDataWorkbook, string, int, bool) {#addchartfromworkbook}

Pobiera wykres z określonego skoroszytu Excel i dodaje go na koniec podanej kolekcji kształtów w określonych współrzędnych.

```csharp
public static IChart AddChartFromWorkbook(IShapeCollection shapes, float x, float y, 
    IExcelDataWorkbook workbook, string worksheetName, int chartIndex, bool embedAllWorkbook)
```

| Parametr | Typ | Opis |
| --- | --- | --- |
| shapes | IShapeCollection | Kolekcja kształtów, do której zostanie dodany wykres. |
| x | Single | Współrzędna X określająca położenie wykresu. |
| y | Single | Współrzędna Y określająca położenie wykresu. |
| workbook | IExcelDataWorkbook | Skoroszyt Excel. |
| worksheetName | String | Nazwa arkusza, który zawiera wykres. |
| chartIndex | Int32 | Indeks zero-bazowy kształtu wykresu do wstawienia. Ten indeks można uzyskać przy pomocy metody [`GetChartsFromWorksheet`](../../../aspose.slides.excel/iexceldataworkbook/getchartsfromworksheet). |
| embedAllWorkbook | Boolean | Jeśli `true`, cały skoroszyt zostanie osadzony w wykresie; jeśli `false`, zostaną osadzone tylko dane wykresu. |

### Wartość zwracana

Wykres, który został dodany do kolekcji kształtów.

### Wyjątki

| wyjątek | warunek |
| --- | --- |
| ArgumentException | Rzucany, gdy którykolwiek wymagany parametr jest nullem, pusty lub gdy wykres nie może zostać odnaleziony w skoroszycie. |

### Przykłady

Przykład:

```csharp
[C#]
IExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
using (var pres = new Presentation())
{
    ExcelWorkbookImporter.AddChartFromWorkbook(pres.Slides[0].Shapes, 10, 10, wb, worksheetName, chartName, false);
    pres.Save("result.pptx", SaveFormat.Pptx);
}
```

### Zobacz także

* interfejs [IChart](../../../aspose.slides.charts/ichart)
* interfejs [IShapeCollection](../../../aspose.slides/ishapecollection)
* interfejs [IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook)
* klasa [ExcelWorkbookImporter](../../excelworkbookimporter)
* przestrzeń nazw [Aspose.Slides.Import](../../excelworkbookimporter)
* zestaw [Aspose.Slides](../../../)

---

## AddChartFromWorkbook(IShapeCollection, float, float, IExcelDataWorkbook, string, string, bool) {#addchartfromworkbook_1}

Pobiera wykres z określonego skoroszytu Excel i dodaje go na koniec podanej kolekcji kształtów w określonych współrzędnych.

```csharp
public static IChart AddChartFromWorkbook(IShapeCollection shapes, float x, float y, 
    IExcelDataWorkbook workbook, string worksheetName, string chartName, bool embedAllWorkbook)
```

| Parametr | Typ | Opis |
| --- | --- | --- |
| shapes | IShapeCollection | Kolekcja kształtów, do której zostanie dodany wykres. |
| x | Single | Współrzędna X określająca położenie wykresu. |
| y | Single | Współrzędna Y określająca położenie wykresu. |
| workbook | IExcelDataWorkbook | Skoroszyt Excel. |
| worksheetName | String | Nazwa arkusza, który zawiera wykres. |
| chartName | String | Nazwa wykresu, który ma zostać dodany. |
| embedAllWorkbook | Boolean | Jeśli `true`, cały skoroszyt zostanie osadzony w wykresie; jeśli `false`, zostaną osadzone tylko dane wykresu. |

### Wartość zwracana

Wykres, który został dodany do kolekcji kształtów.

### Wyjątki

| wyjątek | warunek |
| --- | --- |
| ArgumentException | Rzucany, gdy którykolwiek wymagany parametr jest nullem, pusty lub gdy wykres nie może zostać odnaleziony w skoroszycie. |

### Przykłady

Przykład:

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

### Zobacz także

* interfejs [IChart](../../../aspose.slides.charts/ichart)
* interfejs [IShapeCollection](../../../aspose.slides/ishapecollection)
* interfejs [IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook)
* klasa [ExcelWorkbookImporter](../../excelworkbookimporter)
* przestrzeń nazw [Aspose.Slides.Import](../../excelworkbookimporter)
* zestaw [Aspose.Slides](../../../)

---

## AddChartFromWorkbook(IShapeCollection, float, float, Stream, string, string, bool) {#addchartfromworkbook_2}

Pobiera wykres z określonego skoroszytu Excel i dodaje go na koniec podanej kolekcji kształtów w określonych współrzędnych.

```csharp
public static IChart AddChartFromWorkbook(IShapeCollection shapes, float x, float y, 
    Stream workbookStream, string worksheetName, string chartName, bool embedAllWorkbook)
```

| Parametr | Typ | Opis |
| --- | --- | --- |
| shapes | IShapeCollection | Kolekcja kształtów, do której zostanie dodany wykres. |
| x | Single | Współrzędna X określająca położenie wykresu. |
| y | Single | Współrzędna Y określająca położenie wykresu. |
| workbookStream | Stream | Strumień zawierający dane skoroszytu. |
| worksheetName | String | Nazwa arkusza, który zawiera wykres. |
| chartName | String | Nazwa wykresu, który ma zostać dodany. |
| embedAllWorkbook | Boolean | Jeśli `true`, cały skoroszyt zostanie osadzony w wykresie; jeśli `false`, zostaną osadzone tylko dane wykresu. |

### Wartość zwracana

Wykres, który został dodany do kolekcji kształtów.

### Wyjątki

| wyjątek | warunek |
| --- | --- |
| ArgumentException | Rzucany, gdy którykolwiek wymagany parametr jest nullem, pusty lub gdy wykres nie może zostać odnaleziony w skoroszycie. |
| InvalidOperationException | Rzucany, gdy dane wejściowe mają nieobsługiwany format. |

### Przykłady

Przykład:

```csharp
[C#]
using (var fStream = new FileStream(workbookPath, FileMode.Open, FileAccess.Read))
using (var pres = new Presentation())
{
    ExcelWorkbookImporter.AddChartFromWorkbook(pres.LayoutSlides[0].Shapes, 10, 10, fStream, worksheetName, chartName, true);
    pres.Save("result.pptx", SaveFormat.Pptx);
}
```

### Zobacz także

* interfejs [IChart](../../../aspose.slides.charts/ichart)
* interfejs [IShapeCollection](../../../aspose.slides/ishapecollection)
* klasa [ExcelWorkbookImporter](../../excelworkbookimporter)
* przestrzeń nazw [Aspose.Slides.Import](../../excelworkbookimporter)
* zestaw [Aspose.Slides](../../../)

---

## AddChartFromWorkbook(IShapeCollection, float, float, string, string, string, bool) {#addchartfromworkbook_3}

Pobiera wykres z określonego skoroszytu Excel i dodaje go na koniec podanej kolekcji kształtów w określonych współrzędnych.

```csharp
public static IChart AddChartFromWorkbook(IShapeCollection shapes, float x, float y, 
    string workbookPath, string worksheetName, string chartName, bool embedWorkbook)
```

| Parametr | Typ | Opis |
| --- | --- | --- |
| shapes | IShapeCollection | Kolekcja kształtów, do której zostanie dodany wykres. |
| x | Single | Współrzędna X określająca położenie wykresu. |
| y | Single | Współrzędna Y określająca położenie wykresu. |
| workbookPath | String | Ścieżka do pliku skoroszytu zawierającego wykres. |
| worksheetName | String | Nazwa arkusza, który zawiera wykres. |
| chartName | String | Nazwa wykresu, który ma zostać dodany. |
| embedWorkbook | Boolean | Jeśli `true`, skoroszyt zostanie osadzony w wykresie; jeśli `false`, wykres będzie odwoływał się do zewnętrznego skoroszytu. |

### Wartość zwracana

Wykres, który został dodany do kolekcji kształtów.

### Wyjątki

| wyjątek | warunek |
| --- | --- |
| ArgumentException | Rzucany, gdy którykolwiek wymagany parametr jest nullem, pusty lub gdy wykres nie może zostać odnaleziony w skoroszycie. |
| IOException | Rzucany, gdy wystąpi błąd we/wy podczas dostępu do pliku. |
| InvalidOperationException | Rzucany, gdy dane wejściowe mają nieobsługiwany format. |

### Przykłady

Przykład:

```csharp
[C#]
using (var pres = new Presentation())
{
    ExcelWorkbookImporter.AddChartFromWorkbook(pres.Slides[0].Shapes, 10, 10, workbookPath, worksheetName, chartName, false);
    pres.Save("result.pptx", SaveFormat.Pptx);
}
```

### Zobacz także

* interfejs [IChart](../../../aspose.slides.charts/ichart)
* interfejs [IShapeCollection](../../../aspose.slides/ishapecollection)
* klasa [ExcelWorkbookImporter](../../excelworkbookimporter)
* przestrzeń nazw [Aspose.Slides.Import](../../excelworkbookimporter)
* zestaw [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->