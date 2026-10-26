---
title: get_Row()
second_title: Aspose.Slides για C++ Αναφορά API
description: Επιστρέφει τον μηδενικής βάσης δείκτη της γραμμής στο φύλλο εργασίας όπου βρίσκεται το κελί. Μόνο για ανάγνωση int32_t.
type: docs
weight: 27
url: /el/aspose.slides.excel/exceldatacell/get_row/
---
## ExcelDataCell::get_Row() μέθοδος


Επιστρέφει τον μηδενικής βάσης δείκτη της γραμμής στο φύλλο εργασίας όπου βρίσκεται το κελί. Μόνο για ανάγνωση **int32_t**.

```cpp
int32_t Aspose::Slides::Excel::ExcelDataCell::get_Row() override
```

## Παρατηρήσεις


Παράδειγμα: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(cell->get_Row());
```




## Δείτε επίσης

* Κλάση [ExcelDataCell](../)
* Χώρος ονομάτων [Aspose::Slides::Excel](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)