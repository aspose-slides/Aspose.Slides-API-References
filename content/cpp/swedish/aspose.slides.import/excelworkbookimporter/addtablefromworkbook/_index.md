---
title: AddTableFromWorkbook()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar en tabell från den angivna Excel-arbetsboken och lägger till den i slutet av den angivna formsamlingen på de angivna koordinaterna.
type: docs
weight: 14
url: /sv/aspose.slides.import/excelworkbookimporter/addtablefromworkbook/
---
## ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::SharedPtr\<Aspose::Slides::Excel::IExcelDataWorkbook\>, System::String, System::String) metod


Hämtar en tabell från den angivna [Excel](../../../aspose.slides.excel/) arbetsboken och lägger till den i slutet av den angivna formsamlingen på de angivna koordinaterna.

```cpp
static System::SharedPtr<Aspose::Slides::ITable> Aspose::Slides::Import::ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::SharedPtr<Aspose::Slides::Excel::IExcelDataWorkbook> workbook, System::String worksheetName, System::String cellRange)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | Formsamlingen som tabellen kommer att läggas till i. |
| x | **float** | X-koordinaten för att positionera tabellen. |
| y | **float** | Y-koordinaten för att positionera tabellen. |
| workbook | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Excel::IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook/)\> | Den [Excel](../../../aspose.slides.excel/) arbetsboken. |
| worksheetName | [System::String](../../../system/string/) | Namnet på arbetsbladet som innehåller tabellen. |
| cellRange | [System::String](../../../system/string/) | Cellintervallet som definierar tabellen (till exempel "A1:D10"). |

### Returvärde

Tabellen som lades till i formsamlingen.
## Anmärkningar




```cpp
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_Slide(0)->get_Shapes(), 10.0f, 10.0f, workbook, worksheetName, cellRange);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::String, System::String, System::String) metod


Hämtar en tabell från den angivna [Excel](../../../aspose.slides.excel/) arbetsbokfilen och lägger till den i slutet av den angivna formsamlingen på de angivna koordinaterna.

```cpp
static System::SharedPtr<Aspose::Slides::ITable> Aspose::Slides::Import::ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::String workbookPath, System::String worksheetName, System::String cellRange)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | Formsamlingen som tabellen kommer att läggas till i. |
| x | **float** | X-koordinaten för att positionera tabellen. |
| y | **float** | Y-koordinaten för att positionera tabellen. |
| workbookPath | [System::String](../../../system/string/) | Sökvägen till [Excel](../../../aspose.slides.excel/) arbetsbokfilen. |
| worksheetName | [System::String](../../../system/string/) | Namnet på arbetsbladet som innehåller tabellen. |
| cellRange | [System::String](../../../system/string/) | Cellintervallet som definierar tabellen (till exempel "A1:D10"). |

### Returvärde

Tabellen som lades till i formsamlingen.
## Anmärkningar




```cpp
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_Slide(0)->get_Shapes(), 10.0f, 10.0f, workbookPath, worksheetName, cellRange);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::SharedPtr\<System::IO::Stream\>, System::String, System::String) metod


Hämtar en tabell från den angivna [Excel](../../../aspose.slides.excel/) arbetsbokfilen och lägger till den i slutet av den angivna formsamlingen på de angivna koordinaterna.

```cpp
static System::SharedPtr<Aspose::Slides::ITable> Aspose::Slides::Import::ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::SharedPtr<System::IO::Stream> workbookStream, System::String worksheetName, System::String cellRange)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | Formsamlingen som tabellen kommer att läggas till i. |
| x | **float** | X-koordinaten för att positionera tabellen. |
| y | **float** | Y-koordinaten för att positionera tabellen. |
| workbookStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Strömmen som innehåller arbetsboksdata. |
| worksheetName | [System::String](../../../system/string/) | Namnet på arbetsbladet som innehåller tabellen. |
| cellRange | [System::String](../../../system/string/) | Cellintervallet som definierar tabellen (till exempel "A1:D10"). |

### Returvärde

Tabellen som lades till i formsamlingen.
## Anmärkningar




```cpp
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_Slide(0)->get_Shapes(), 10.0f, 10.0f, fStream, worksheetName, cellRange);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [ITable](../../../aspose.slides/itable/)
* Klass [IShapeCollection](../../../aspose.slides/ishapecollection/)
* Klass [IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook/)
* Klass [String](../../../system/string/)
* Klass [ExcelWorkbookImporter](../)
* Klass [Stream](../../../system.io/stream/)
* Namnrymd [Aspose::Slides::Import](../../)
* Library [Aspose.Slides](../../../)