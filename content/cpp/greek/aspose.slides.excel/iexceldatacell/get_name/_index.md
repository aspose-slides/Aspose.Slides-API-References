---
title: get_Name()
second_title: Aspose.Slides για C++ Αναφορά API
description: "Λαμβάνει το όνομα του κελιού δεδομένων του διαγράμματος. Μόνο για ανάγνωση System::String."
type: docs
weight: 14
url: /el/aspose.slides.excel/iexceldatacell/get_name/
---
## IExcelDataCell::get_Name() μέθοδος

Λαμβάνει το όνομα του κελιού δεδομένων του διαγράμματος. Μόνο για ανάγνωση [System::String](../../../system/string/).

```cpp
virtual System::String Aspose::Slides::Excel::IExcelDataCell::get_Name()=0
```

## Παρατηρήσεις

Παράδειγμα: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(cell->get_Name());
```

## Δείτε επίσης

* Κλάση [String](../../../system/string/)
* Κλάση [IExcelDataCell](../)
* Χώρος ονομάτων [Aspose::Slides::Excel](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)