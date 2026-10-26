---
title: get_Name()
second_title: Αναφορά API του Aspose.Slides για C++
description: Λαμβάνει το όνομα του κελιού δεδομένων του διαγράμματος.
type: docs
weight: 14
url: /el/aspose.slides.excel/exceldatacell/get_name/
---
## ExcelDataCell::get_Name() μέθοδος


Λαμβάνει το όνομα του κελιού δεδομένων του διαγράμματος.

```cpp
System::String Aspose::Slides::Excel::ExcelDataCell::get_Name() override
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
* Κλάση [ExcelDataCell](../)
* Χώρος ονομάτων [Aspose::Slides::Excel](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)