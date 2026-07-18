---
title: GetCells()
second_title: Aspose.Slides για C++ – Αναφορά API
description: Ανακτά μια συλλογή κελιών από το βιβλίο εργασίας που ταιριάζουν με τον καθορισμένο τύπο.
type: docs
weight: 14
url: /el/aspose.slides.excel/exceldataworkbook/getcells/
---
## ExcelDataWorkbook::GetCells(System::String, bool) μέθοδος


Ανακτά μια συλλογή κελιών από το βιβλίο εργασίας που ταιριάζουν με τον καθορισμένο τύπο.

```cpp
System::SharedPtr<System::Collections::ObjectModel::ReadOnlyCollection<System::SharedPtr<IExcelDataCell>>> Aspose::Slides::Excel::ExcelDataWorkbook::GetCells(System::String formula, bool skipHiddenCells) override
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| formula | [System::String](../../../system/string/) | Μια φόρμουλα ή έκφραση περιοχής (π.χ., \"Sheet1!A1:B3\") που χρησιμοποιείται για τον εντοπισμό των κελιών-στόχων. |
| skipHiddenCells | **bool** | Αν **true**, κρυμμένα κελιά (π.χ., σε κρυμμένες γραμμές ή στήλες) θα εξαλειφθούν από το αποτέλεσμα. |

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

* Τύπος [SharedPtr](../../../system/sharedptr/)
* Κλάση [ReadOnlyCollection](../../../system.collections.objectmodel/readonlycollection/)
* Κλάση [IExcelDataCell](../../iexceldatacell/)
* Κλάση [String](../../../system/string/)
* Κλάση [ExcelDataWorkbook](../)
* Χώρος ονομάτων [Aspose::Slides::Excel](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)