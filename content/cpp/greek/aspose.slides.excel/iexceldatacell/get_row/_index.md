---
title: get_Row()
second_title: Aspose.Slides για C++ Αναφορά API
description: Λαμβάνει το μηδενικό ευρετήριο της γραμμής στο φύλλο εργασίας όπου βρίσκεται το κελί. Μόνο για ανάγνωση int32_t.
type: docs
weight: 27
url: /el/aspose.slides.excel/iexceldatacell/get_row/
---
## IExcelDataCell::get_Row() μέθοδος

Λαμβάνει το μηδενικό ευρετήριο της γραμμής στο φύλλο εργασίας όπου βρίσκεται το κελί. Μόνο για ανάγνωση **int32_t**.

```cpp
virtual int32_t Aspose::Slides::Excel::IExcelDataCell::get_Row()=0
```

## Παρατηρήσεις


Παράδειγμα:
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(cell->get_Row());
```




## Δείτε επίσης

* Κλάση [IExcelDataCell](../)
* Χώρος ονομάτων [Aspose::Slides::Excel](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)