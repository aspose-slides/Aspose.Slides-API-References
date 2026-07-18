---
title: AddChartFromWorkbook()
second_title: Aspose.Slides για C++ Αναφορά API
description: Ανακτά ένα γράφημα από το καθορισμένο βιβλίο εργασίας Excel και το προσθέτει στο τέλος της δεδομένης συλλογής σχημάτων στις καθορισμένες συντεταγμένες.
type: docs
weight: 1
url: /el/aspose.slides.import/excelworkbookimporter/addchartfromworkbook/
---
## ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::SharedPtr\<Aspose::Slides::Excel::IExcelDataWorkbook\>, System::String, int32_t, bool) μέθοδος

Ανακτά ένα γράφημα από το καθορισμένο [Excel](../../../aspose.slides.excel/) βιβλίο εργασίας και το προσθέτει στο τέλος της δεδομένης συλλογής σχημάτων στις καθορισμένες συντεταγμένες.

```cpp
static System::SharedPtr<Aspose::Slides::Charts::IChart> Aspose::Slides::Import::ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::SharedPtr<Aspose::Slides::Excel::IExcelDataWorkbook> workbook, System::String worksheetName, int32_t chartIndex, bool embedAllWorkbook)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | Η συλλογή σχημάτων στην οποία θα προστεθεί το γράφημα. |
| x | **float** | Η συντεταγμένη X για την τοποθέτηση του γραφήματος. |
| y | **float** | Η συντεταγμένη Y για την τοποθέτηση του γραφήματος. |
| workbook | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Excel::IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook/)\> | Το [Excel](../../../aspose.slides.excel/) βιβλίο εργασίας. |
| worksheetName | [System::String](../../../system/string/) | Το όνομα του φύλλου εργασίας που περιέχει το γράφημα. |
| chartIndex | **int32_t** | Ο μηδενικής βάσης δείκτης του σχήματος γραφήματος που θα εισαχθεί. Αυτός ο δείκτης μπορεί να ληφθεί χρησιμοποιώντας τη μέθοδο [IExcelDataWorkbook::GetChartsFromWorksheet(string)](../). |
| embedAllWorkbook | **bool** | Αν **true**, ολόκληρο το βιβλίο εργασίας θα ενσωματωθεί στο γράφημα· αν **false**, μόνο τα δεδομένα του γραφήματος θα ενσωματωθούν. |

### Τιμή Επιστροφής

Το γράφημα που προστέθηκε στη συλλογή σχημάτων.

## Παρατηρήσεις

Παράδειγμα: 
```cpp
System::SharedPtr<IExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_Slide(0)->get_Shapes(), 10.0f, 10.0f, wb, worksheetName, chartName, false);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::SharedPtr\<Aspose::Slides::Excel::IExcelDataWorkbook\>, System::String, System::String, bool) μέθοδος

Ανακτά ένα γράφημα από το καθορισμένο [Excel](../../../aspose.slides.excel/) βιβλίο εργασίας και το προσθέτει στο τέλος της δοθείσας συλλογής σχημάτων στις καθορισμένες συντεταγμένες.

```cpp
static System::SharedPtr<Aspose::Slides::Charts::IChart> Aspose::Slides::Import::ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::SharedPtr<Aspose::Slides::Excel::IExcelDataWorkbook> workbook, System::String worksheetName, System::String chartName, bool embedAllWorkbook)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | Η συλλογή σχημάτων στην οποία θα προστεθεί το γράφημα. |
| x | **float** | Η συντεταγμένη X για την τοποθέτηση του γραφήματος. |
| y | **float** | Η συντεταγμένη Y για την τοποθέτηση του γραφήματος. |
| workbook | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Excel::IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook/)\> | Το [Excel](../../../aspose.slides.excel/) βιβλίο εργασίας. |
| worksheetName | [System::String](../../../system/string/) | Το όνομα του φύλλου εργασίας που περιέχει το γράφημα. |
| chartName | [System::String](../../../system/string/) | Το όνομα του γραφήματος που θα προστεθεί. |
| embedAllWorkbook | **bool** | Αν **true**, ολόκληρο το βιβλίο εργασίας θα ενσωματωθεί στο γράφημα· αν **false**, μόνο τα δεδομένα του γραφήματος θα ενσωματωθούν. |

### Τιμή Επιστροφής

Το γράφημα που προστέθηκε στη συλλογή σχημάτων.

## Παρατηρήσεις

Παράδειγμα: 
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

## ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::SharedPtr\<System::IO::Stream\>, System::String, System::String, bool) μέθοδος

Ανακτά ένα γράφημα από το καθορισμένο [Excel](../../../aspose.slides.excel/) βιβλίο εργασίας και το προσθέτει στο τέλος της δοθείσας συλλογής σχημάτων στις καθορισμένες συντεταγμένες.

```cpp
static System::SharedPtr<Aspose::Slides::Charts::IChart> Aspose::Slides::Import::ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::SharedPtr<System::IO::Stream> workbookStream, System::String worksheetName, System::String chartName, bool embedAllWorkbook)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | Η συλλογή σχημάτων στην οποία θα προστεθεί το γράφημα. |
| x | **float** | Η συντεταγμένη X για την τοποθέτηση του γραφήματος. |
| y | **float** | Η συντεταγμένη Y για την τοποθέτηση του γραφήματος. |
| workbookStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Ένα ρεύμα που περιέχει τα δεδομένα του βιβλίου εργασίας. |
| worksheetName | [System::String](../../../system/string/) | Το όνομα του φύλλου εργασίας που περιέχει το γράφημα. |
| chartName | [System::String](../../../system/string/) | Το όνομα του γραφήματος που θα προστεθεί. |
| embedAllWorkbook | **bool** | Αν **true**, ολόκληρο το βιβλίο εργασίας θα ενσωματωθεί στο γράφημα· αν **false**, μόνο τα δεδομένα του γραφήματος θα ενσωματωθούν. |

### Τιμή Επιστροφής

Το γράφημα που προστέθηκε στη συλλογή σχημάτων.

## Παρατηρήσεις

Παράδειγμα: 
```cpp
auto fStream = System::MakeObject<System::IO::FileStream>(workbookPath, System::IO::FileMode::Open, System::IO::FileAccess::Read);
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_LayoutSlide(0)->get_Shapes(), 10.0f, 10.0f, fStream, worksheetName, chartName, true);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::String, System::String, System::String, bool) μέθοδος

Ανακτά ένα γράφημα από το καθορισμένο [Excel](../../../aspose.slides.excel/) βιβλίο εργασίας και το προσθέτει στο τέλος της δοθείσας συλλογής σχημάτων στις καθορισμένες συντεταγμένες.

```cpp
static System::SharedPtr<Aspose::Slides::Charts::IChart> Aspose::Slides::Import::ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::String workbookPath, System::String worksheetName, System::String chartName, bool embedWorkbook)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | Η συλλογή σχημάτων στην οποία θα προστεθεί το γράφημα. |
| x | **float** | Η συντεταγμένη X για την τοποθέτηση του γραφήματος. |
| y | **float** | Η συντεταγμένη Y για την τοποθέτηση του γραφήματος. |
| workbookPath | [System::String](../../../system/string/) | Η διαδρομή του αρχείου προς το βιβλίο εργασίας που περιέχει το γράφημα. |
| worksheetName | [System::String](../../../system/string/) | Το όνομα του φύλλου εργασίας που περιέχει το γράφημα. |
| chartName | [System::String](../../../system/string/) | Το όνομα του γραφήματος που θα προστεθεί. |
| embedWorkbook | **bool** | Αν **true**, το βιβλίο εργασίας θα ενσωματωθεί στο γράφημα· αν **false**, το γράφημα θα συνδεθεί με το εξωτερικό βιβλίο εργασίας. |

### Τιμή Επιστροφής

Το γράφημα που προστέθηκε στη συλλογή σχημάτων.

## Παρατηρήσεις

Παράδειγμα: 
```cpp
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_Slide(0)->get_Shapes(), 10.0f, 10.0f, workbookPath, worksheetName, chartName, false);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IChart](../../../aspose.slides.charts/ichart/)
* Κλάση [IShapeCollection](../../../aspose.slides/ishapecollection/)
* Κλάση [IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook/)
* Κλάση [String](../../../system/string/)
* Κλάση [ExcelWorkbookImporter](../)
* Κλάση [Stream](../../../system.io/stream/)
* Χώρος ονομάτων [Aspose::Slides::Import](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)