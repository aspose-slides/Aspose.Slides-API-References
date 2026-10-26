---
title: GetCells()
second_title: Aspose.Slides για C++ Αναφορά API
description: Ανακτά μια συλλογή κελιών από το βιβλίο εργασίας που ταιριάζουν με τον καθορισμένο τύπο.
type: docs
weight: 1
url: /el/aspose.slides.excel/iexceldataworkbook/getcells/
---
## IExcelDataWorkbook::GetCells(System::String, bool) μέθοδος

Επιστρέφει μια συλλογή κελιών από το βιβλίο εργασίας που ταιριάζουν με τον καθορισμένο τύπο.

```cpp
virtual System::SharedPtr<System::Collections::ObjectModel::ReadOnlyCollection<System::SharedPtr<IExcelDataCell>>> Aspose::Slides::Excel::IExcelDataWorkbook::GetCells(System::String formula, bool skipHiddenCells)=0
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| formula | [System::String](../../../system/string/) | Ένας τύπος ή έκφραση περιοχής (π.χ., "Sheet1!A1:B3") που χρησιμοποιείται για την ταυτοποίηση των κελιών-στόχου. |
| skipHiddenCells | **bool** | Αν **true**, τα κρυφά κελιά (π.χ., σε κρυφές γραμμές ή στήλες) θα εξαιρεθούν από το αποτέλεσμα. |

### Τιμή Επιστροφής

Μια λίστα μόνο για ανάγνωση των κελιών που ταιριάζουν με τον καθορισμένο τύπο.

## Παρατηρήσεις

Παράδειγμα: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<System::Collections::ObjectModel::ReadOnlyCollection<System::SharedPtr<IExcelDataCell>>> cells = wb->GetCells(u"Sheet1!A2:A6", false);
System::Console::WriteLine(cells->get_Count());
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [ReadOnlyCollection](../../../system.collections.objectmodel/readonlycollection/)
* Κλάση [IExcelDataCell](../../iexceldatacell/)
* Κλάση [String](../../../system/string/)
* Κλάση [IExcelDataWorkbook](../)
* Χώρος ονομάτων [Aspose::Slides::Excel](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)