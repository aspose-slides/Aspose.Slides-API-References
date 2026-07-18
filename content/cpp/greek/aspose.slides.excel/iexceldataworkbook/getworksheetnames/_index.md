---
title: GetWorksheetNames()
second_title: Aspose.Slides για Αναφορά API C++
description: Ανακτά τα ονόματα όλων των φύλλων εργασίας που περιέχονται στο βιβλίο εργασίας Excel.
type: docs
weight: 40
url: /el/aspose.slides.excel/iexceldataworkbook/getworksheetnames/
---
## IExcelDataWorkbook::GetWorksheetNames() μέθοδος

Ανακτά τα ονόματα όλων των φύλλων εργασίας που περιέχονται στο βιβλίο εργασίας [Excel](../../).

```cpp
virtual System::SharedPtr<System::Collections::Generic::IList<System::String>> Aspose::Slides::Excel::IExcelDataWorkbook::GetWorksheetNames()=0
```

### Τιμή Επιστροφής

Μια λίστα με τα ονόματα των φύλλων εργασίας
## Σχόλια



Παράδειγμα: 
```cpp
System::SharedPtr<IExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
auto sheetNames = wb->GetWorksheetNames();
for (auto&& name : sheetNames)
{
    System::Console::WriteLine(name);
}
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IList](../../../system.collections.generic/ilist/)
* Κλάση [String](../../../system/string/)
* Κλάση [IExcelDataWorkbook](../)
* Χώρος ονομάτων [Aspose::Slides::Excel](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)