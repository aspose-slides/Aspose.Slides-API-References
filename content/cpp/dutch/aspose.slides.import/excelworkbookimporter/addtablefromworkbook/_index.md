---
title: AddTableFromWorkbook()
second_title: Aspose.Slides voor C++ API-referentie
description: Haalt een tabel op uit de opgegeven Excel-werkmap en voegt deze toe aan het einde van de opgegeven shape-collectie op de gespecificeerde coördinaten.
type: docs
weight: 14
url: /nl/aspose.slides.import/excelworkbookimporter/addtablefromworkbook/
---
## ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::SharedPtr\<Aspose::Slides::Excel::IExcelDataWorkbook\>, System::String, System::String) methode


Haalt een tabel op uit de gespecificeerde [Excel](../../../aspose.slides.excel/)-werkmap en voegt deze toe aan het einde van de opgegeven shape-collectie op de gespecificeerde coördinaten.

```cpp
static System::SharedPtr<Aspose::Slides::ITable> Aspose::Slides::Import::ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::SharedPtr<Aspose::Slides::Excel::IExcelDataWorkbook> workbook, System::String worksheetName, System::String cellRange)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | De shape-collectie waaraan de tabel zal worden toegevoegd. |
| x | **float** | De X-coördinaat voor het positioneren van de tabel. |
| y | **float** | De Y-coördinaat voor het positioneren van de tabel. |
| workbook | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Excel::IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook/)\> | De [Excel](../../../aspose.slides.excel/)-werkmap. |
| worksheetName | [System::String](../../../system/string/) | De naam van het werkblad dat de tabel bevat. |
| cellRange | [System::String](../../../system/string/) | Het celbereik dat de tabel definieert (bijvoorbeeld "A1:D10"). |

### Retourwaarde

De tabel die aan de shape-collectie is toegevoegd.
## Opmerkingen




```cpp
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_Slide(0)->get_Shapes(), 10.0f, 10.0f, workbook, worksheetName, cellRange);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::String, System::String, System::String) methode


Haalt een tabel op uit het gespecificeerde [Excel](../../../aspose.slides.excel/)-werkmapbestand en voegt deze toe aan het einde van de opgegeven shape-collectie op de gespecificeerde coördinaten.

```cpp
static System::SharedPtr<Aspose::Slides::ITable> Aspose::Slides::Import::ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::String workbookPath, System::String worksheetName, System::String cellRange)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | De shape-collectie waaraan de tabel zal worden toegevoegd. |
| x | **float** | De X-coördinaat voor het positioneren van de tabel. |
| y | **float** | De Y-coördinaat voor het positioneren van de tabel. |
| workbookPath | [System::String](../../../system/string/) | Het pad naar het [Excel](../../../aspose.slides.excel/)-werkmapbestand. |
| worksheetName | [System::String](../../../system/string/) | De naam van het werkblad dat de tabel bevat. |
| cellRange | [System::String](../../../system/string/) | Het celbereik dat de tabel definieert (bijvoorbeeld "A1:D10"). |

### Retourwaarde

De tabel die aan de shape-collectie is toegevoegd.
## Opmerkingen




```cpp
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_Slide(0)->get_Shapes(), 10.0f, 10.0f, workbookPath, worksheetName, cellRange);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::SharedPtr\<System::IO::Stream\>, System::String, System::String) methode


Haalt een tabel op uit het gespecificeerde [Excel](../../../aspose.slides.excel/)-werkmapbestand en voegt deze toe aan het einde van de opgegeven shape-collectie op de gespecificeerde coördinaten.

```cpp
static System::SharedPtr<Aspose::Slides::ITable> Aspose::Slides::Import::ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::SharedPtr<System::IO::Stream> workbookStream, System::String worksheetName, System::String cellRange)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | De shape-collectie waaraan de tabel zal worden toegevoegd. |
| x | **float** | De X-coördinaat voor het positioneren van de tabel. |
| y | **float** | De Y-coördinaat voor het positioneren van de tabel. |
| workbookStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Een stream die de werkmapdata bevat. |
| worksheetName | [System::String](../../../system/string/) | De naam van het werkblad dat de tabel bevat. |
| cellRange | [System::String](../../../system/string/) | Het celbereik dat de tabel definieert (bijvoorbeeld "A1:D10"). |

### Retourwaarde

De tabel die aan de shape-collectie is toegevoegd.
## Opmerkingen




```cpp
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_Slide(0)->get_Shapes(), 10.0f, 10.0f, fStream, worksheetName, cellRange);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [ITable](../../../aspose.slides/itable/)
* Klasse [IShapeCollection](../../../aspose.slides/ishapecollection/)
* Klasse [IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook/)
* Klasse [String](../../../system/string/)
* Klasse [ExcelWorkbookImporter](../)
* Klasse [Stream](../../../system.io/stream/)
* Namespace [Aspose::Slides::Import](../../)
* Bibliotheek [Aspose.Slides](../../../)