---
title: get_Column()
second_title: Αναφορά API Aspose.Slides για C++
description: Αποκτά τον δείκτη μηδενικής βάσης της στήλης στο φύλλο εργασίας όπου βρίσκεται το κελί. Μόνο για ανάγνωση int32_t.
type: docs
weight: 40
url: /el/aspose.slides.excel/iexceldatacell/get_column/
---
## IExcelDataCell::get_Column() μέθοδος


Αποκτά τον δείκτη μηδενικής βάσης της στήλης στο φύλλο εργασίας όπου βρίσκεται το κελί. Μόνο για ανάγνωση **int32_t**.

```cpp
virtual int32_t Aspose::Slides::Excel::IExcelDataCell::get_Column()=0
```

## Παρατηρήσεις

Παράδειγμα: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(cell->get_Column());
```

## Δείτε επίσης

* Κλάση [IExcelDataCell](../)
* Χώρος ονομάτων [Aspose::Slides::Excel](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)