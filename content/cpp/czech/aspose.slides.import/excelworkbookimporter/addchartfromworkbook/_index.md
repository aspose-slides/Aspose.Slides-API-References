---
title: AddChartFromWorkbook()
second_title: Aspose.Slides pro C++ - reference API
description: Načte graf ze zadaného Excel sešitu a přidá jej na konec dané kolekce tvarů na zadaných souřadnicích.
type: docs
weight: 1
url: /cs/aspose.slides.import/excelworkbookimporter/addchartfromworkbook/
---
## ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::SharedPtr\<Aspose::Slides::Excel::IExcelDataWorkbook\>, System::String, int32_t, bool) metoda


Načte graf ze zadaného [Excel](../../../aspose.slides.excel/) sešitu a přidá jej na konec dané kolekce tvarů na zadaných souřadnicích.

```cpp
static System::SharedPtr<Aspose::Slides::Charts::IChart> Aspose::Slides::Import::ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::SharedPtr<Aspose::Slides::Excel::IExcelDataWorkbook> workbook, System::String worksheetName, int32_t chartIndex, bool embedAllWorkbook)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | Kolekce tvarů, do které bude graf přidán. |
| x | **float** | Souřadnice X pro umístění grafu. |
| y | **float** | Souřadnice Y pro umístění grafu. |
| workbook | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Excel::IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook/)\> | [Excel](../../../aspose.slides.excel/) sešit. |
| worksheetName | [System::String](../../../system/string/) | Název listu, který obsahuje graf. |
| chartIndex | **int32_t** | Nulový index grafu, který se má vložit. Tento index lze získat pomocí metody [IExcelDataWorkbook::GetChartsFromWorksheet(string)](../). |
| embedAllWorkbook | **bool** | Pokud **true**, celý sešit bude vložen do grafu; pokud **false**, budou vložena pouze data grafu. |

### Návratová hodnota

Graf, který byl přidán do kolekce tvarů.
## Poznámky



Příklad: 
```cpp
System::SharedPtr<IExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_Slide(0)->get_Shapes(), 10.0f, 10.0f, wb, worksheetName, chartName, false);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::SharedPtr\<Aspose::Slides::Excel::IExcelDataWorkbook\>, System::String, System::String, bool) metoda


Načte graf ze zadaného [Excel](../../../aspose.slides.excel/) sešitu a přidá jej na konec dané kolekce tvarů na zadaných souřadnicích.

```cpp
static System::SharedPtr<Aspose::Slides::Charts::IChart> Aspose::Slides::Import::ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::SharedPtr<Aspose::Slides::Excel::IExcelDataWorkbook> workbook, System::String worksheetName, System::String chartName, bool embedAllWorkbook)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | Kolekce tvarů, do které bude graf přidán. |
| x | **float** | Souřadnice X pro umístění grafu. |
| y | **float** | Souřadnice Y pro umístění grafu. |
| workbook | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Excel::IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook/)\> | [Excel](../../../aspose.slides.excel/) sešit. |
| worksheetName | [System::String](../../../system/string/) | Název listu, který obsahuje graf. |
| chartName | [System::String](../../../system/string/) | Název grafu, který má být přidán. |
| embedAllWorkbook | **bool** | Pokud **true**, celý sešit bude vložen do grafu; pokud **false**, budou vložena pouze data grafu. |

### Návratová hodnota

Graf, který byl přidán do kolekce tvarů.
## Poznámky



Příklad: 
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


Načte graf ze zadaného [Excel](../../../aspose.slides.excel/) sešitu a přidá jej na konec dané kolekce tvarů na zadaných souřadnicích.

```cpp
static System::SharedPtr<Aspose::Slides::Charts::IChart> Aspose::Slides::Import::ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::SharedPtr<System::IO::Stream> workbookStream, System::String worksheetName, System::String chartName, bool embedAllWorkbook)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | Kolekce tvarů, do které bude graf přidán. |
| x | **float** | Souřadnice X pro umístění grafu. |
| y | **float** | Souřadnice Y pro umístění grafu. |
| workbookStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Proud obsahující data sešitu. |
| worksheetName | [System::String](../../../system/string/) | Název listu, který obsahuje graf. |
| chartName | [System::String](../../../system/string/) | Název grafu, který má být přidán. |
| embedAllWorkbook | **bool** | Pokud **true**, celý sešit bude vložen do grafu; pokud **false**, budou vložena pouze data grafu. |

### Návratová hodnota

Graf, který byl přidán do kolekce tvarů.
## Poznámky



Příklad: 
```cpp
auto fStream = System::MakeObject<System::IO::FileStream>(workbookPath, System::IO::FileMode::Open, System::IO::FileAccess::Read);
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_LayoutSlide(0)->get_Shapes(), 10.0f, 10.0f, fStream, worksheetName, chartName, true);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::String, System::String, System::String, bool) metoda


Načte graf ze zadaného [Excel](../../../aspose.slides.excel/) sešitu a přidá jej na konec dané kolekce tvarů na zadaných souřadnicích.

```cpp
static System::SharedPtr<Aspose::Slides::Charts::IChart> Aspose::Slides::Import::ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::String workbookPath, System::String worksheetName, System::String chartName, bool embedWorkbook)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | Kolekce tvarů, do které bude graf přidán. |
| x | **float** | Souřadnice X pro umístění grafu. |
| y | **float** | Souřadnice Y pro umístění grafu. |
| workbookPath | [System::String](../../../system/string/) | Cesta k souboru sešitu obsahujícímu graf. |
| worksheetName | [System::String](../../../system/string/) | Název listu, který obsahuje graf. |
| chartName | [System::String](../../../system/string/) | Název grafu, který má být přidán. |
| embedWorkbook | **bool** | Pokud **true**, sešit bude vložen do grafu; pokud **false**, graf bude odkazovat na externí sešit. |

### Návratová hodnota

Graf, který byl přidán do kolekce tvarů.
## Poznámky



Příklad: 
```cpp
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_Slide(0)->get_Shapes(), 10.0f, 10.0f, workbookPath, worksheetName, chartName, false);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IChart](../../../aspose.slides.charts/ichart/)
* Třída [IShapeCollection](../../../aspose.slides/ishapecollection/)
* Třída [IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook/)
* Třída [String](../../../system/string/)
* Třída [ExcelWorkbookImporter](../)
* Třída [Stream](../../../system.io/stream/)
* Obor názvů [Aspose::Slides::Import](../../)
* Library [Aspose.Slides](../../../)