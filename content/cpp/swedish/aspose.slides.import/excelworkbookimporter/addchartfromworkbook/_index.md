---
title: AddChartFromWorkbook()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar ett diagram från den angivna Excel-arbetsboken och lägger till det i slutet av den givna formsamlingen på de angivna koordinaterna.
type: docs
weight: 1
url: /sv/aspose.slides.import/excelworkbookimporter/addchartfromworkbook/
---
## ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::SharedPtr\<Aspose::Slides::Excel::IExcelDataWorkbook\>, System::String, int32_t, bool) method


Hämtar ett diagram från den specifika [Excel](../../../aspose.slides.excel/) arbetsboken och lägger till det i slutet av den angivna formsamlingen på de angivna koordinaterna.

```cpp
static System::SharedPtr<Aspose::Slides::Charts::IChart> Aspose::Slides::Import::ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::SharedPtr<Aspose::Slides::Excel::IExcelDataWorkbook> workbook, System::String worksheetName, int32_t chartIndex, bool embedAllWorkbook)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | Formsamlingen som diagrammet kommer att läggas till i. |
| x | **float** | X-koordinaten för att placera diagrammet. |
| y | **float** | Y-koordinaten för att placera diagrammet. |
| workbook | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Excel::IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook/)\> | Den [Excel](../../../aspose.slides.excel/) arbetsboken. |
| worksheetName | [System::String](../../../system/string/) | Namnet på kalkylbladet som innehåller diagrammet. |
| chartIndex | **int32_t** | Det nollbaserade indexet för diagramformen som ska infogas. Detta index kan erhållas med hjälp av [IExcelDataWorkbook::GetChartsFromWorksheet(string)](../)-metoden. |
| embedAllWorkbook | **bool** | Om **true**, kommer hela arbetsboken att bäddas in i diagrammet; om **false**, kommer endast diagramdata att bäddas in. |

### Returvärde

Diagrammet som lades till i formsamlingen.
## Anmärkningar



Exempel: 
```cpp
System::SharedPtr<IExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_Slide(0)->get_Shapes(), 10.0f, 10.0f, wb, worksheetName, chartName, false);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::SharedPtr\<Aspose::Slides::Excel::IExcelDataWorkbook\>, System::String, System::String, bool) method


Hämtar ett diagram från den specifika [Excel](../../../aspose.slides.excel/) arbetsboken och lägger till det i slutet av den angivna formsamlingen på de angivna koordinaterna.

```cpp
static System::SharedPtr<Aspose::Slides::Charts::IChart> Aspose::Slides::Import::ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::SharedPtr<Aspose::Slides::Excel::IExcelDataWorkbook> workbook, System::String worksheetName, System::String chartName, bool embedAllWorkbook)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | Formsamlingen som diagrammet kommer att läggas till i. |
| x | **float** | X-koordinaten för att placera diagrammet. |
| y | **float** | Y-koordinaten för att placera diagrammet. |
| workbook | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Excel::IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook/)\> | Den [Excel](../../../aspose.slides.excel/) arbetsboken. |
| worksheetName | [System::String](../../../system/string/) | Namnet på kalkylbladet som innehåller diagrammet. |
| chartName | [System::String](../../../system/string/) | Namnet på diagrammet som ska läggas till. |
| embedAllWorkbook | **bool** | Om **true**, kommer hela arbetsboken att bäddas in i diagrammet; om **false**, kommer endast diagramdata att bäddas in. |

### Returvärde

Diagrammet som lades till i formsamlingen.
## Anmärkningar



Exempel: 
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

## ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::SharedPtr\<System::IO::Stream\>, System::String, System::String, bool) method


Hämtar ett diagram från den specifika [Excel](../../../aspose.slides.excel/) arbetsboken och lägger till det i slutet av den angivna formsamlingen på de angivna koordinaterna.

```cpp
static System::SharedPtr<Aspose::Slides::Charts::IChart> Aspose::Slides::Import::ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::SharedPtr<System::IO::Stream> workbookStream, System::String worksheetName, System::String chartName, bool embedAllWorkbook)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | Formsamlingen som diagrammet kommer att läggas till i. |
| x | **float** | X-koordinaten för att placera diagrammet. |
| y | **float** | Y-koordinaten för att placera diagrammet. |
| workbookStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | En ström som innehåller arbetsbokens data. |
| worksheetName | [System::String](../../../system/string/) | Namnet på kalkylbladet som innehåller diagrammet. |
| chartName | [System::String](../../../system/string/) | Namnet på diagrammet som ska läggas till. |
| embedAllWorkbook | **bool** | Om **true**, kommer hela arbetsboken att bäddas in i diagrammet; om **false**, kommer endast diagramdata att bäddas in. |

### Returvärde

Diagrammet som lades till i formsamlingen.
## Anmärkningar



Exempel: 
```cpp
auto fStream = System::MakeObject<System::IO::FileStream>(workbookPath, System::IO::FileMode::Open, System::IO::FileAccess::Read);
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_LayoutSlide(0)->get_Shapes(), 10.0f, 10.0f, fStream, worksheetName, chartName, true);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::String, System::String, System::String, bool) method


Hämtar ett diagram från den specifika [Excel](../../../aspose.slides.excel/) arbetsboken och lägger till det i slutet av den angivna formsamlingen på de angivna koordinaterna.

```cpp
static System::SharedPtr<Aspose::Slides::Charts::IChart> Aspose::Slides::Import::ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::String workbookPath, System::String worksheetName, System::String chartName, bool embedWorkbook)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | Formsamlingen som diagrammet kommer att läggas till i. |
| x | **float** | X-koordinaten för att placera diagrammet. |
| y | **float** | Y-koordinaten för att placera diagrammet. |
| workbookPath | [System::String](../../../system/string/) | Filvägen till arbetsboken som innehåller diagrammet. |
| worksheetName | [System::String](../../../system/string/) | Namnet på kalkylbladet som innehåller diagrammet. |
| chartName | [System::String](../../../system/string/) | Namnet på diagrammet som ska läggas till. |
| embedWorkbook | **bool** | Om **true**, kommer arbetsboken att bäddas in i diagrammet; om **false**, kommer diagrammet att länka till den externa arbetsboken. |

### Returvärde

Diagrammet som lades till i formsamlingen.
## Anmärkningar



Exempel: 
```cpp
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_Slide(0)->get_Shapes(), 10.0f, 10.0f, workbookPath, worksheetName, chartName, false);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## Se också

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IChart](../../../aspose.slides.charts/ichart/)
* Klass [IShapeCollection](../../../aspose.slides/ishapecollection/)
* Klass [IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook/)
* Klass [String](../../../system/string/)
* Klass [ExcelWorkbookImporter](../)
* Klass [Stream](../../../system.io/stream/)
* Namnrymd [Aspose::Slides::Import](../../)
* Bibliotek [Aspose.Slides](../../../)