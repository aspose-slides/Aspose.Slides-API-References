---
title: AddChartFromWorkbook()
second_title: Aspose.Slides für C++ API-Referenz
description: Ruft ein Diagramm aus der angegebenen Excel-Arbeitsmappe ab und fügt es am Ende der angegebenen Formsammlung an den angegebenen Koordinaten ein.
type: docs
weight: 1
url: /de/aspose.slides.import/excelworkbookimporter/addchartfromworkbook/
---
## ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::SharedPtr\<Aspose::Slides::Excel::IExcelDataWorkbook\>, System::String, int32_t, bool) method

Ruft ein Diagramm aus der angegebenen [Excel](../../../aspose.slides.excel/) Arbeitsmappe ab und fügt es am Ende der angegebenen Formsammlung an den angegebenen Koordinaten ein.

```cpp
static System::SharedPtr<Aspose::Slides::Charts::IChart> Aspose::Slides::Import::ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::SharedPtr<Aspose::Slides::Excel::IExcelDataWorkbook> workbook, System::String worksheetName, int32_t chartIndex, bool embedAllWorkbook)
```

### Argumente

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | Die Formsammlung, zu der das Diagramm hinzugefügt wird. |
| x | **float** | Die X-Koordinate zur Positionierung des Diagramms. |
| y | **float** | Die Y-Koordinate zur Positionierung des Diagramms. |
| workbook | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Excel::IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook/)\> | Die [Excel](../../../aspose.slides.excel/) Arbeitsmappe. |
| worksheetName | [System::String](../../../system/string/) | Der Name des Arbeitsblatts, das das Diagramm enthält. |
| chartIndex | **int32_t** | Der nullbasierte Index der einzufügenden Diagrammform. Dieser Index kann mit der [IExcelDataWorkbook::GetChartsFromWorksheet(string)](../)-Methode ermittelt werden. |
| embedAllWorkbook | **bool** | Wenn **true**, wird die gesamte Arbeitsmappe in das Diagramm eingebettet; wenn **false**, werden nur die Diagrammdaten eingebettet. |

### Rückgabewert

Das Diagramm, das der Formsammlung hinzugefügt wurde.

## Anmerkungen



Beispiel: 
```cpp
System::SharedPtr<IExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_Slide(0)->get_Shapes(), 10.0f, 10.0f, wb, worksheetName, chartName, false);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::SharedPtr\<Aspose::Slides::Excel::IExcelDataWorkbook\>, System::String, System::String, bool) method

Ruft ein Diagramm aus der angegebenen [Excel](../../../aspose.slides.excel/) Arbeitsmappe ab und fügt es am Ende der angegebenen Formsammlung an den angegebenen Koordinaten ein.

```cpp
static System::SharedPtr<Aspose::Slides::Charts::IChart> Aspose::Slides::Import::ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::SharedPtr<Aspose::Slides::Excel::IExcelDataWorkbook> workbook, System::String worksheetName, System::String chartName, bool embedAllWorkbook)
```

### Argumente

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | Die Formsammlung, zu der das Diagramm hinzugefügt wird. |
| x | **float** | Die X-Koordinate zur Positionierung des Diagramms. |
| y | **float** | Die Y-Koordinate zur Positionierung des Diagramms. |
| workbook | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Excel::IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook/)\> | Die [Excel](../../../aspose.slides.excel/) Arbeitsmappe. |
| worksheetName | [System::String](../../../system/string/) | Der Name des Arbeitsblatts, das das Diagramm enthält. |
| chartName | [System::String](../../../system/string/) | Der Name des hinzuzufügenden Diagramms. |
| embedAllWorkbook | **bool** | Wenn **true**, wird die gesamte Arbeitsmappe in das Diagramm eingebettet; wenn **false**, werden nur die Diagrammdaten eingebettet. |

### Rückgabewert

Das Diagramm, das der Formsammlung hinzugefügt wurde.

## Anmerkungen



Beispiel: 
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

Ruft ein Diagramm aus der angegebenen [Excel](../../../aspose.slides.excel/) Arbeitsmappe ab und fügt es am Ende der angegebenen Formsammlung an den angegebenen Koordinaten ein.

```cpp
static System::SharedPtr<Aspose::Slides::Charts::IChart> Aspose::Slides::Import::ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::SharedPtr<System::IO::Stream> workbookStream, System::String worksheetName, System::String chartName, bool embedAllWorkbook)
```

### Argumente

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | Die Formsammlung, zu der das Diagramm hinzugefügt wird. |
| x | **float** | Die X-Koordinate zur Positionierung des Diagramms. |
| y | **float** | Die Y-Koordinate zur Positionierung des Diagramms. |
| workbookStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Ein Stream, der die Arbeitsmappe-Daten enthält. |
| worksheetName | [System::String](../../../system/string/) | Der Name des Arbeitsblatts, das das Diagramm enthält. |
| chartName | [System::String](../../../system/string/) | Der Name des hinzuzufügenden Diagramms. |
| embedAllWorkbook | **bool** | Wenn **true**, wird die gesamte Arbeitsmappe in das Diagramm eingebettet; wenn **false**, werden nur die Diagrammdaten eingebettet. |

### Rückgabewert

Das Diagramm, das der Formsammlung hinzugefügt wurde.

## Anmerkungen



Beispiel: 
```cpp
auto fStream = System::MakeObject<System::IO::FileStream>(workbookPath, System::IO::FileMode::Open, System::IO::FileAccess::Read);
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_LayoutSlide(0)->get_Shapes(), 10.0f, 10.0f, fStream, worksheetName, chartName, true);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::String, System::String, System::String, bool) method

Ruft ein Diagramm aus der angegebenen [Excel](../../../aspose.slides.excel/) Arbeitsmappe ab und fügt es am Ende der angegebenen Formsammlung an den angegebenen Koordinaten ein.

```cpp
static System::SharedPtr<Aspose::Slides::Charts::IChart> Aspose::Slides::Import::ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::String workbookPath, System::String worksheetName, System::String chartName, bool embedWorkbook)
```

### Argumente

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | Die Formsammlung, zu der das Diagramm hinzugefügt wird. |
| x | **float** | Die X-Koordinate zur Positionierung des Diagramms. |
| y | **float** | Die Y-Koordinate zur Positionierung des Diagramms. |
| workbookPath | [System::String](../../../system/string/) | Der Dateipfad zur Arbeitsmappe, die das Diagramm enthält. |
| worksheetName | [System::String](../../../system/string/) | Der Name des Arbeitsblatts, das das Diagramm enthält. |
| chartName | [System::String](../../../system/string/) | Der Name des hinzuzufügenden Diagramms. |
| embedWorkbook | **bool** | Wenn **true**, wird die Arbeitsmappe in das Diagramm eingebettet; wenn **false**, wird das Diagramm auf die externe Arbeitsmappe verweisen. |

### Rückgabewert

Das Diagramm, das der Formsammlung hinzugefügt wurde.

## Anmerkungen



Beispiel: 
```cpp
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_Slide(0)->get_Shapes(), 10.0f, 10.0f, workbookPath, worksheetName, chartName, false);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IChart](../../../aspose.slides.charts/ichart/)
* Klasse [IShapeCollection](../../../aspose.slides/ishapecollection/)
* Klasse [IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook/)
* Klasse [String](../../../system/string/)
* Klasse [ExcelWorkbookImporter](../)
* Klasse [Stream](../../../system.io/stream/)
* Namensraum [Aspose::Slides::Import](../../)
* Library [Aspose.Slides](../../../)