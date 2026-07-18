---
title: get_Column()
second_title: Aspose.Slides για C++ API Αναφορά
description: Αποκτά το μηδενικό δείκτη της στήλης στο φύλλο εργασίας όπου βρίσκεται το κελί. Μόνο για ανάγνωση int32_t.
type: docs
weight: 40
url: /el/aspose.slides.excel/exceldatacell/get_column/
---
## ExcelDataCell::get_Column() μέθοδος


Αποκτά το μηδενικό δείκτη της στήλης στο φύλλο εργασίας όπου βρίσκεται το κελί. Μόνο για ανάγνωση **int32_t**.

```cpp
int32_t Aspose::Slides::Excel::ExcelDataCell::get_Column() override
```

## Παρατηρήσεις


Παράδειγμα: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(cell->get_Column());
```

## Δείτε επίσης

* Κλάση [ExcelDataCell](../)
* Χώρος ονομάτων [Aspose::Slides::Excel](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)