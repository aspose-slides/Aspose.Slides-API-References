---
title: AddChartFromWorkbook()
second_title: Aspose.Slides voor C++ API Referentie
description: Haalt een diagram op uit de opgegeven Excel-werkmap en voegt het toe aan het einde van de opgegeven vormverzameling op de gespecificeerde coördinaten.
type: docs
weight: 1
url: /nl/aspose.slides.import/excelworkbookimporter/addchartfromworkbook/
---
## ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::SharedPtr\<Aspose::Slides::Excel::IExcelDataWorkbook\>, System::String, int32_t, bool) methode


Haalt een diagram op uit de opgegeven [Excel](../../../aspose.slides.excel/) werkmap en voegt het toe aan het einde van de opgegeven vormverzameling op de gespecificeerde coördinaten.

```cpp
static System::SharedPtr<Aspose::Slides::Charts::IChart> Aspose::Slides::Import::ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::SharedPtr<Aspose::Slides::Excel::IExcelDataWorkbook> workbook, System::String worksheetName, int32_t chartIndex, bool embedAllWorkbook)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | De vormverzameling waaraan het diagram wordt toegevoegd. |
| x | **float** | De X-coördinaat voor het positioneren van het diagram. |
| y | **float** | De Y-coördinaat voor het positioneren van het diagram. |
| workbook | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Excel::IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook/)\> | De [Excel](../../../aspose.slides.excel/) werkmap. |
| worksheetName | [System::String](../../../system/string/) | De naam van het werkblad dat het diagram bevat. |
| chartIndex | **int32_t** | De nulgebaseerde index van de diagramvorm die moet worden ingevoegd. Deze index kan worden verkregen met de [IExcelDataWorkbook::GetChartsFromWorksheet(string)](../) methode. |
| embedAllWorkbook | **bool** | Als **true**, wordt de volledige werkmap in het diagram ingesloten; als **false**, worden alleen de diagramgegevens ingesloten. |

### Retourwaarde

Het diagram dat aan de vormverzameling is toegevoegd.
## Opmerkingen



Voorbeeld: 
```cpp
System::SharedPtr<IExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_Slide(0)->get_Shapes(), 10.0f, 10.0f, wb, worksheetName, chartName, false);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::SharedPtr\<Aspose::Slides::Excel::IExcelDataWorkbook\>, System::String, System::String, bool) methode


Haalt een diagram op uit de opgegeven [Excel](../../../aspose.slides.excel/) werkmap en voegt het toe aan het einde van de opgegeven vormverzameling op de gespecificeerde coördinaten.

```cpp
static System::SharedPtr<Aspose::Slides::Charts::IChart> Aspose::Slides::Import::ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::SharedPtr<Aspose::Slides::Excel::IExcelDataWorkbook> workbook, System::String worksheetName, System::String chartName, bool embedAllWorkbook)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | De vormverzameling waaraan het diagram wordt toegevoegd. |
| x | **float** | De X-coördinaat voor het positioneren van het diagram. |
| y | **float** | De Y-coördinaat voor het positioneren van het diagram. |
| workbook | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Excel::IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook/)\> | De [Excel](../../../aspose.slides.excel/) werkmap. |
| worksheetName | [System::String](../../../system/string/) | De naam van het werkblad dat het diagram bevat. |
| chartName | [System::String](../../../system/string/) | De naam van het diagram dat moet worden toegevoegd. |
| embedAllWorkbook | **bool** | Als **true**, wordt de volledige werkmap in het diagram ingesloten; als **false**, worden alleen de diagramgegevens ingesloten. |

### Retourwaarde

Het diagram dat aan de vormverzameling is toegevoegd.
## Opmerkingen



Voorbeeld: 
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

## ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::SharedPtr\<System::IO::Stream\>, System::String, System::String, bool) methode


Haalt een diagram op uit de opgegeven [Excel](../../../aspose.slides.excel/) werkmap en voegt het toe aan het einde van de opgegeven vormverzameling op de gespecificeerde coördinaten.

```cpp
static System::SharedPtr<Aspose::Slides::Charts::IChart> Aspose::Slides::Import::ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::SharedPtr<System::IO::Stream> workbookStream, System::String worksheetName, System::String chartName, bool embedAllWorkbook)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | De vormverzameling waaraan het diagram wordt toegevoegd. |
| x | **float** | De X-coördinaat voor het positioneren van het diagram. |
| y | **float** | De Y-coördinaat voor het positioneren van het diagram. |
| workbookStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Een stream die de werkmapgegevens bevat. |
| worksheetName | [System::String](../../../system/string/) | De naam van het werkblad dat het diagram bevat. |
| chartName | [System::String](../../../system/string/) | De naam van het diagram dat moet worden toegevoegd. |
| embedAllWorkbook | **bool** | Als **true**, wordt de volledige werkmap in het diagram ingesloten; als **false**, worden alleen de diagramgegevens ingesloten. |

### Retourwaarde

Het diagram dat aan de vormverzameling is toegevoegd.
## Opmerkingen



Voorbeeld: 
```cpp
auto fStream = System::MakeObject<System::IO::FileStream>(workbookPath, System::IO::FileMode::Open, System::IO::FileAccess::Read);
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_LayoutSlide(0)->get_Shapes(), 10.0f, 10.0f, fStream, worksheetName, chartName, true);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::String, System::String, System::String, bool) methode


Haalt een diagram op uit de opgegeven [Excel](../../../aspose.slides.excel/) werkmap en voegt het toe aan het einde van de opgegeven vormverzameling op de gespecificeerde coördinaten.

```cpp
static System::SharedPtr<Aspose::Slides::Charts::IChart> Aspose::Slides::Import::ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::String workbookPath, System::String worksheetName, System::String chartName, bool embedWorkbook)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | De vormverzameling waaraan het diagram wordt toegevoegd. |
| x | **float** | De X-coördinaat voor het positioneren van het diagram. |
| y | **float** | De Y-coördinaat voor het positioneren van het diagram. |
| workbookPath | [System::String](../../../system/string/) | Het bestandspad naar de werkmap die het diagram bevat. |
| worksheetName | [System::String](../../../system/string/) | De naam van het werkblad dat het diagram bevat. |
| chartName | [System::String](../../../system/string/) | De naam van het diagram dat moet worden toegevoegd. |
| embedWorkbook | **bool** | Als **true**, wordt de werkmap in het diagram ingesloten; als **false**, zal het diagram naar de externe werkmap linken. |

### Retourwaarde

Het diagram dat aan de vormverzameling is toegevoegd.
## Opmerkingen



Voorbeeld: 
```cpp
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_Slide(0)->get_Shapes(), 10.0f, 10.0f, workbookPath, worksheetName, chartName, false);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChart](../../../aspose.slides.charts/ichart/)
* Class [IShapeCollection](../../../aspose.slides/ishapecollection/)
* Class [IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook/)
* Class [String](../../../system/string/)
* Class [ExcelWorkbookImporter](../)
* Class [Stream](../../../system.io/stream/)
* Namespace [Aspose::Slides::Import](../../)
* Library [Aspose.Slides](../../../)