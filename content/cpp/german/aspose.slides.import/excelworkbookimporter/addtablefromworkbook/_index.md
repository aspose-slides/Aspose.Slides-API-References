---
title: AddTableFromWorkbook()
second_title: Aspose.Slides für C++ API Referenz
description: Ruft eine Tabelle aus der angegebenen Excel-Arbeitsmappe ab und fügt sie am Ende der angegebenen Shape-Collection an den angegebenen Koordinaten ein.
type: docs
weight: 14
url: /de/aspose.slides.import/excelworkbookimporter/addtablefromworkbook/
---
## ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::SharedPtr\<Aspose::Slides::Excel::IExcelDataWorkbook\>, System::String, System::String) Methode

Ruft eine Tabelle aus der angegebenen [Excel](../../../aspose.slides.excel/) Arbeitsmappe ab und fügt sie am Ende der angegebenen Shape-Collection an den angegebenen Koordinaten ein.

```cpp
static System::SharedPtr<Aspose::Slides::ITable> Aspose::Slides::Import::ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::SharedPtr<Aspose::Slides::Excel::IExcelDataWorkbook> workbook, System::String worksheetName, System::String cellRange)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | Die Shape-Collection, zu der die Tabelle hinzugefügt wird. |
| x | **float** | Die X-Koordinate zum Positionieren der Tabelle. |
| y | **float** | Die Y-Koordinate zum Positionieren der Tabelle. |
| workbook | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Excel::IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook/)\> | Die [Excel](../../../aspose.slides.excel/) Arbeitsmappe. |
| worksheetName | [System::String](../../../system/string/) | Der Name des Arbeitsblatts, das die Tabelle enthält. |
| cellRange | [System::String](../../../system/string/) | Der Zellbereich, der die Tabelle definiert (zum Beispiel "A1:D10"). |

### Rückgabewert

Die Tabelle, die zur Shape-Collection hinzugefügt wurde.
## Bemerkungen

```cpp
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_Slide(0)->get_Shapes(), 10.0f, 10.0f, workbook, worksheetName, cellRange);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::String, System::String, System::String) Methode

Ruft eine Tabelle aus der angegebenen [Excel](../../../aspose.slides.excel/) Arbeitsmappe-Datei ab und fügt sie am Ende der angegebenen Shape-Collection an den angegebenen Koordinaten ein.

```cpp
static System::SharedPtr<Aspose::Slides::ITable> Aspose::Slides::Import::ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::String workbookPath, System::String worksheetName, System::String cellRange)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | Die Shape-Collection, zu der die Tabelle hinzugefügt wird. |
| x | **float** | Die X-Koordinate zum Positionieren der Tabelle. |
| y | **float** | Die Y-Koordinate zum Positionieren der Tabelle. |
| workbookPath | [System::String](../../../system/string/) | Der Pfad zur [Excel](../../../aspose.slides.excel/) Arbeitsmappe-Datei. |
| worksheetName | [System::String](../../../system/string/) | Der Name des Arbeitsblatts, das die Tabelle enthält. |
| cellRange | [System::String](../../../system/string/) | Der Zellbereich, der die Tabelle definiert (zum Beispiel "A1:D10"). |

### Rückgabewert

Die Tabelle, die zur Shape-Collection hinzugefügt wurde.
## Bemerkungen

```cpp
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_Slide(0)->get_Shapes(), 10.0f, 10.0f, workbookPath, worksheetName, cellRange);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::SharedPtr\<System::IO::Stream\>, System::String, System::String) Methode

Ruft eine Tabelle aus der angegebenen [Excel](../../../aspose.slides.excel/) Arbeitsmappe-Datei ab und fügt sie am Ende der angegebenen Shape-Collection an den angegebenen Koordinaten ein.

```cpp
static System::SharedPtr<Aspose::Slides::ITable> Aspose::Slides::Import::ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::SharedPtr<System::IO::Stream> workbookStream, System::String worksheetName, System::String cellRange)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | Die Shape-Collection, zu der die Tabelle hinzugefügt wird. |
| x | **float** | Die X-Koordinate zum Positionieren der Tabelle. |
| y | **float** | Die Y-Koordinate zum Positionieren der Tabelle. |
| workbookStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Ein Stream, der die Arbeitsmappendaten enthält. |
| worksheetName | [System::String](../../../system/string/) | Der Name des Arbeitsblatts, das die Tabelle enthält. |
| cellRange | [System::String](../../../system/string/) | Der Zellbereich, der die Tabelle definiert (zum Beispiel "A1:D10"). |

### Rückgabewert

Die Tabelle, die zur Shape-Collection hinzugefügt wurde.
## Bemerkungen

```cpp
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_Slide(0)->get_Shapes(), 10.0f, 10.0f, fStream, worksheetName, cellRange);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [ITable](../../../aspose.slides/itable/)
* Klasse [IShapeCollection](../../../aspose.slides/ishapecollection/)
* Klasse [IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook/)
* Klasse [String](../../../system/string/)
* Klasse [ExcelWorkbookImporter](../)
* Klasse [Stream](../../../system.io/stream/)
* Namensraum [Aspose::Slides::Import](../../)
* Bibliothek [Aspose.Slides](../../../)