---
title: AddChartFromWorkbook()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Pobiera wykres z określonego skoroszytu Excel i dodaje go na koniec podanej kolekcji kształtów w określonych współrzędnych.
type: docs
weight: 1
url: /pl/aspose.slides.import/excelworkbookimporter/addchartfromworkbook/
---
## ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::SharedPtr\<Aspose::Slides::Excel::IExcelDataWorkbook\>, System::String, int32_t, bool) metoda

Pobiera wykres z określonego [Excel](../../../aspose.slides.excel/) skoroszytu i dodaje go na koniec podanej kolekcji kształtów w określonych współrzędnych.

```cpp
static System::SharedPtr<Aspose::Slides::Charts::IChart> Aspose::Slides::Import::ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::SharedPtr<Aspose::Slides::Excel::IExcelDataWorkbook> workbook, System::String worksheetName, int32_t chartIndex, bool embedAllWorkbook)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | Kolekcja kształtów, do której zostanie dodany wykres. |
| x | **float** | Współrzędna X określająca położenie wykresu. |
| y | **float** | Współrzędna Y określająca położenie wykresu. |
| workbook | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Excel::IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook/)\> | Skoroszyt [Excel](../../../aspose.slides.excel/). |
| worksheetName | [System::String](../../../system/string/) | Nazwa arkusza, który zawiera wykres. |
| chartIndex | **int32_t** | Indeks wykresu w kolekcji kształtów, liczony od zera. Ten indeks można uzyskać przy użyciu metody [IExcelDataWorkbook::GetChartsFromWorksheet(string)](../). |
| embedAllWorkbook | **bool** | Jeśli **true**, cały skoroszyt zostanie osadzony w wykresie; jeśli **false**, osadzone zostaną jedynie dane wykresu. |

### Wartość zwracana

Wykres, który został dodany do kolekcji kształtów.

## Uwagi



Przykład: 
```cpp
System::SharedPtr<IExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_Slide(0)->get_Shapes(), 10.0f, 10.0f, wb, worksheetName, chartName, false);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::SharedPtr\<Aspose::Slides::Excel::IExcelDataWorkbook\>, System::String, System::String, bool) metoda


Pobiera wykres z określonego [Excel](../../../aspose.slides.excel/) skoroszytu i dodaje go na koniec podanej kolekcji kształtów w określonych współrzędnych.

```cpp
static System::SharedPtr<Aspose::Slides::Charts::IChart> Aspose::Slides::Import::ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::SharedPtr<Aspose::Slides::Excel::IExcelDataWorkbook> workbook, System::String worksheetName, System::String chartName, bool embedAllWorkbook)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | Kolekcja kształtów, do której zostanie dodany wykres. |
| x | **float** | Współrzędna X określająca położenie wykresu. |
| y | **float** | Współrzędna Y określająca położenie wykresu. |
| workbook | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Excel::IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook/)\> | Skoroszyt [Excel](../../../aspose.slides.excel/). |
| worksheetName | [System::String](../../../system/string/) | Nazwa arkusza, który zawiera wykres. |
| chartName | [System::String](../../../system/string/) | Nazwa wykresu, który ma zostać dodany. |
| embedAllWorkbook | **bool** | Jeśli **true**, cały skoroszyt zostanie osadzony w wykresie; jeśli **false**, osadzone zostaną jedynie dane wykresu. |

### Wartość zwracana

Wykres, który został dodany do kolekcji kształtów.

## Uwagi



Przykład: 
```cpp
System::SharedPtr<IExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
auto pres = System::MakeObject<Presentation>();

System::String worksheetName = u"worksheet name";
auto worksheetCharts = wb->GetChartsFromWorksheet(worksheetName);
for (auto&& chart : worksheetCharts)
{
    System::SharedPtr<ISlide> slide = pres->get_Slides()->AddEmptySlide(pres->get_LayoutSlides()->idx_get(0));
    ExcelWorkbookImporter::AddChartFromWorkbook(slide->get_Shapes(), 10.0f, 10.0f, wb, worksheetName, chart.get_Key(), false);
}
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::SharedPtr\<System::IO::Stream\>, System::String, System::String, bool) metoda


Pobiera wykres z określonego [Excel](../../../aspose.slides.excel/) skoroszytu i dodaje go na koniec podanej kolekcji kształtów w określonych współrzędnych.

```cpp
static System::SharedPtr<Aspose::Slides::Charts::IChart> Aspose::Slides::Import::ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::SharedPtr<System::IO::Stream> workbookStream, System::String worksheetName, System::String chartName, bool embedAllWorkbook)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | Kolekcja kształtów, do której zostanie dodany wykres. |
| x | **float** | Współrzędna X określająca położenie wykresu. |
| y | **float** | Współrzędna Y określająca położenie wykresu. |
| workbookStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Strumień zawierający dane skoroszytu. |
| worksheetName | [System::String](../../../system/string/) | Nazwa arkusza, który zawiera wykres. |
| chartName | [System::String](../../../system/string/) | Nazwa wykresu, który ma zostać dodany. |
| embedAllWorkbook | **bool** | Jeśli **true**, cały skoroszyt zostanie osadzony w wykresie; jeśli **false**, osadzone zostaną jedynie dane wykresu. |

### Wartość zwracana

Wykres, który został dodany do kolekcji kształtów.

## Uwagi



Przykład: 
```cpp
auto fStream = System::MakeObject<System::IO::FileStream>(workbookPath, System::IO::FileMode::Open, System::IO::FileAccess::Read);
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_LayoutSlide(0)->get_Shapes(), 10.0f, 10.0f, fStream, worksheetName, chartName, true);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::String, System::String, System::String, bool) metoda


Pobiera wykres z określonego [Excel](../../../aspose.slides.excel/) skoroszytu i dodaje go na koniec podanej kolekcji kształtów w określonych współrzędnych.

```cpp
static System::SharedPtr<Aspose::Slides::Charts::IChart> Aspose::Slides::Import::ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::String workbookPath, System::String worksheetName, System::String chartName, bool embedWorkbook)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | Kolekcja kształtów, do której zostanie dodany wykres. |
| x | **float** | Współrzędna X określająca położenie wykresu. |
| y | **float** | Współrzędna Y określająca położenie wykresu. |
| workbookPath | [System::String](../../../system/string/) | Ścieżka do pliku skoroszytu zawierającego wykres. |
| worksheetName | [System::String](../../../system/string/) | Nazwa arkusza, który zawiera wykres. |
| chartName | [System::String](../../../system/string/) | Nazwa wykresu, który ma zostać dodany. |
| embedWorkbook | **bool** | Jeśli **true**, skoroszyt zostanie osadzony w wykresie; jeśli **false**, wykres będzie odwoływał się do zewnętrznego skoroszytu. |

### Wartość zwracana

Wykres, który został dodany do kolekcji kształtów.

## Uwagi



Przykład: 
```cpp
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_Slide(0)->get_Shapes(), 10.0f, 10.0f, workbookPath, worksheetName, chartName, false);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IChart](../../../aspose.slides.charts/ichart/)
* Klasa [IShapeCollection](../../../aspose.slides/ishapecollection/)
* Klasa [IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook/)
* Klasa [String](../../../system/string/)
* Klasa [ExcelWorkbookImporter](../)
* Klasa [Stream](../../../system.io/stream/)
* Przestrzeń nazw [Aspose::Slides::Import](../../)
* Biblioteka [Aspose.Slides](../../../)