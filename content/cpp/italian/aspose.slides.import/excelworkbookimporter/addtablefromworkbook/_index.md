---
title: AddTableFromWorkbook()
second_title: Riferimento API di Aspose.Slides per C++
description: Recupera una tabella dal workbook Excel specificato e la aggiunge alla fine della collezione di forme fornita alle coordinate specificate.
type: docs
weight: 14
url: /it/aspose.slides.import/excelworkbookimporter/addtablefromworkbook/
---
## ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::SharedPtr\<Aspose::Slides::Excel::IExcelDataWorkbook\>, System::String, System::String) metodo

Recupera una tabella dal workbook [Excel](../../../aspose.slides.excel/) specificato e la aggiunge alla fine della collezione di forme fornita alle coordinate specificate.

```cpp
static System::SharedPtr<Aspose::Slides::ITable> Aspose::Slides::Import::ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::SharedPtr<Aspose::Slides::Excel::IExcelDataWorkbook> workbook, System::String worksheetName, System::String cellRange)
```

### Parametri

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | La collezione di forme a cui verrà aggiunta la tabella. |
| x | **float** | La coordinata X per posizionare la tabella. |
| y | **float** | La coordinata Y per posizionare la tabella. |
| workbook | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Excel::IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook/)\> | Il workbook [Excel](../../../aspose.slides.excel/). |
| worksheetName | [System::String](../../../system/string/) | Il nome del foglio di lavoro che contiene la tabella. |
| cellRange | [System::String](../../../system/string/) | L'intervallo di celle che definisce la tabella (ad esempio, "A1:D10"). |

### Valore di ritorno

La tabella che è stata aggiunta alla collezione di forme.

## Osservazioni

```cpp
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_Slide(0)->get_Shapes(), 10.0f, 10.0f, workbook, worksheetName, cellRange);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::String, System::String, System::String) metodo

Recupera una tabella dal file workbook [Excel](../../../aspose.slides.excel/) specificato e la aggiunge alla fine della collezione di forme fornita alle coordinate specificate.

```cpp
static System::SharedPtr<Aspose::Slides::ITable> Aspose::Slides::Import::ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::String workbookPath, System::String worksheetName, System::String cellRange)
```

### Parametri

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | La collezione di forme a cui verrà aggiunta la tabella. |
| x | **float** | La coordinata X per posizionare la tabella. |
| y | **float** | La coordinata Y per posizionare la tabella. |
| workbookPath | [System::String](../../../system/string/) | Il percorso al file workbook [Excel](../../../aspose.slides.excel/). |
| worksheetName | [System::String](../../../system/string/) | Il nome del foglio di lavoro che contiene la tabella. |
| cellRange | [System::String](../../../system/string/) | L'intervallo di celle che definisce la tabella (ad esempio, "A1:D10"). |

### Valore di ritorno

La tabella che è stata aggiunta alla collezione di forme.

## Osservazioni

```cpp
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_Slide(0)->get_Shapes(), 10.0f, 10.0f, workbookPath, worksheetName, cellRange);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::SharedPtr\<System::IO::Stream\>, System::String, System::String) metodo

Recupera una tabella dal file workbook [Excel](../../../aspose.slides.excel/) specificato e la aggiunge alla fine della collezione di forme fornita alle coordinate specificate.

```cpp
static System::SharedPtr<Aspose::Slides::ITable> Aspose::Slides::Import::ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::SharedPtr<System::IO::Stream> workbookStream, System::String worksheetName, System::String cellRange)
```

### Parametri

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | La collezione di forme a cui verrà aggiunta la tabella. |
| x | **float** | La coordinata X per posizionare la tabella. |
| y | **float** | La coordinata Y per posizionare la tabella. |
| workbookStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Uno stream contenente i dati del workbook. |
| worksheetName | [System::String](../../../system/string/) | Il nome del foglio di lavoro che contiene la tabella. |
| cellRange | [System::String](../../../system/string/) | L'intervallo di celle che definisce la tabella (ad esempio, "A1:D10"). |

### Valore di ritorno

La tabella che è stata aggiunta alla collezione di forme.

## Osservazioni

```cpp
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_Slide(0)->get_Shapes(), 10.0f, 10.0f, fStream, worksheetName, cellRange);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ITable](../../../aspose.slides/itable/)
* Class [IShapeCollection](../../../aspose.slides/ishapecollection/)
* Class [IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook/)
* Class [String](../../../system/string/)
* Class [ExcelWorkbookImporter](../)
* Class [Stream](../../../system.io/stream/)
* Namespace [Aspose::Slides::Import](../../)
* Library [Aspose.Slides](../../../)