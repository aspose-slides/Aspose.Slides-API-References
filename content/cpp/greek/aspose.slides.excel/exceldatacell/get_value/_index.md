---
title: get_Value()
second_title: Aspose.Slides για C++ API Αναφορά
description: Αποκτά την τιμή που περιέχεται στο κελί Excel.
type: docs
weight: 1
url: /el/aspose.slides.excel/exceldatacell/get_value/
---
## ExcelDataCell::get_Value() μέθοδος


Αποκτά την τιμή που περιέχεται στο κελί [Excel](../../).

```cpp
System::SharedPtr<System::Object> Aspose::Slides::Excel::ExcelDataCell::get_Value() override
```

## Παρατηρήσεις


Παράδειγμα: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```




## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [Object](../../../system/object/)
* Κλάση [ExcelDataCell](../)
* Χώρος ονομάτων [Aspose::Slides::Excel](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)