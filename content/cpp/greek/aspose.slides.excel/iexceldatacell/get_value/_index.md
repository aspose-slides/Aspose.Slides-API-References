---
title: get_Value()
second_title: Aspose.Slides για C++ API Αναφορά
description: "Λαμβάνει την τιμή που περιέχεται στο κελί Excel. Μόνο για ανάγνωση System::Object."
type: docs
weight: 1
url: /el/aspose.slides.excel/iexceldatacell/get_value/
---
## IExcelDataCell::get_Value() μέθοδος

Λαμβάνει την τιμή που περιέχεται στο κελί [Excel](../../). Μόνο για ανάγνωση [System::Object](../../../system/object/).

```cpp
virtual System::SharedPtr<System::Object> Aspose::Slides::Excel::IExcelDataCell::get_Value()=0
```

## Παρατηρήσεις

Παράδειγμα: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## Δείτε επίσης

* typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [Object](../../../system/object/)
* Κλάση [IExcelDataCell](../)
* Χώρος ονομάτων [Aspose::Slides::Excel](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)