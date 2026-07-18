---
title: AddTableFromWorkbook()
second_title: Aspose.Slides για C++ API Αναφορά
description: Ανακτά έναν πίνακα από το καθορισμένο βιβλίο εργασίας Excel και τον προσθέτει στο τέλος της δοσμένης συλλογής σχημάτων στις καθορισμένες συντεταγμένες.
type: docs
weight: 14
url: /el/aspose.slides.import/excelworkbookimporter/addtablefromworkbook/
---
## ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::SharedPtr\<Aspose::Slides::Excel::IExcelDataWorkbook\>, System::String, System::String) μέθοδος

Ανακτά έναν πίνακα από το καθορισμένο [Excel](../../../aspose.slides.excel/) βιβλίο εργασίας και τον προσθέτει στο τέλος της δοσμένης συλλογής σχημάτων στις καθορισμένες συντεταγμένες.

```cpp
static System::SharedPtr<Aspose::Slides::ITable> Aspose::Slides::Import::ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::SharedPtr<Aspose::Slides::Excel::IExcelDataWorkbook> workbook, System::String worksheetName, System::String cellRange)
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | Η συλλογή σχημάτων στην οποία θα προστεθεί ο πίνακας. |
| x | **float** | Η συντεταγμένη X για τη θέση του πίνακα. |
| y | **float** | Η συντεταγμένη Y για τη θέση του πίνακα. |
| workbook | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Excel::IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook/)\> | Το [Excel](../../../aspose.slides.excel/) βιβλίο εργασίας. |
| worksheetName | [System::String](../../../system/string/) | Το όνομα του φύλλου εργασίας που περιέχει τον πίνακα. |
| cellRange | [System::String](../../../system/string/) | Η περιοχή κελιών που ορίζει τον πίνακα (για παράδειγμα, "A1:D10"). |

### Τιμή επιστροφής

Ο πίνακας που προστέθηκε στη συλλογή σχημάτων.

## Παρατηρήσεις

```cpp
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_Slide(0)->get_Shapes(), 10.0f, 10.0f, workbook, worksheetName, cellRange);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::String, System::String, System::String) μέθοδος

Ανακτά έναν πίνακα από το καθορισμένο [Excel](../../../aspose.slides.excel/) αρχείο βιβλίου εργασίας και τον προσθέτει στο τέλος της δοσμένης συλλογής σχημάτων στις καθορισμένες συντεταγμένες.

```cpp
static System::SharedPtr<Aspose::Slides::ITable> Aspose::Slides::Import::ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::String workbookPath, System::String worksheetName, System::String cellRange)
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | Η συλλογή σχημάτων στην οποία θα προστεθεί ο πίνακας. |
| x | **float** | Η συντεταγμένη X για τη θέση του πίνακα. |
| y | **float** | Η συντεταγμένη Y για τη θέση του πίνακα. |
| workbookPath | [System::String](../../../system/string/) | Η διαδρομή προς το [Excel](../../../aspose.slides.excel/) αρχείο βιβλίου εργασίας. |
| worksheetName | [System::String](../../../system/string/) | Το όνομα του φύλλου εργασίας που περιέχει τον πίνακα. |
| cellRange | [System::String](../../../system/string/) | Η περιοχή κελιών που ορίζει τον πίνακα (για παράδειγμα, "A1:D10"). |

### Τιμή επιστροφής

Ο πίνακας που προστέθηκε στη συλλογή σχημάτων.

## Παρατηρήσεις

```cpp
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_Slide(0)->get_Shapes(), 10.0f, 10.0f, workbookPath, worksheetName, cellRange);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::SharedPtr\<System::IO::Stream\>, System::String, System::String) μέθοδος

Ανακτά έναν πίνακα από το καθορισμένο [Excel](../../../aspose.slides.excel/) αρχείο βιβλίου εργασίας και τον προσθέτει στο τέλος της δοσμένης συλλογής σχημάτων στις καθορισμένες συντεταγμένες.

```cpp
static System::SharedPtr<Aspose::Slides::ITable> Aspose::Slides::Import::ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::SharedPtr<System::IO::Stream> workbookStream, System::String worksheetName, System::String cellRange)
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | Η συλλογή σχημάτων στην οποία θα προστεθεί ο πίνακας. |
| x | **float** | Η συντεταγμένη X για τη θέση του πίνακα. |
| y | **float** | Η συντεταγμένη Y για τη θέση του πίνακα. |
| workbookStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Ένα ρεύμα που περιέχει τα δεδομένα του βιβλίου εργασίας. |
| worksheetName | [System::String](../../../system/string/) | Το όνομα του φύλλου εργασίας που περιέχει τον πίνακα. |
| cellRange | [System::String](../../../system/string/) | Η περιοχή κελιών που ορίζει τον πίνακα (για παράδειγμα, "A1:D10"). |

### Τιμή επιστροφής

Ο πίνακας που προστέθηκε στη συλλογή σχημάτων.

## Παρατηρήσεις

```cpp
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_Slide(0)->get_Shapes(), 10.0f, 10.0f, fStream, worksheetName, cellRange);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ITable](../../../aspose.slides/itable/)
* Class [IShapeCollection](../../../aspose.slides/ishapecollection/)
* Class [IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook/)
* Class [String](../../../system/string/)
* Class [ExcelWorkbookImporter](../)
* Class [Stream](../../../system.io/stream/)
* Namespace [Aspose::Slides::Import](../../)
* Library [Aspose.Slides](../../../)