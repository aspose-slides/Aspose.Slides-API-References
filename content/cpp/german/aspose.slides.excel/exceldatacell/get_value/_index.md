---
title: get_Value()
second_title: Aspose.Slides für C++ API-Referenz
description: Ermittelt den in der Excel-Zelle enthaltenen Wert.
type: docs
weight: 1
url: /de/aspose.slides.excel/exceldatacell/get_value/
---
## ExcelDataCell::get_Value() Methode


Ermittelt den in der [Excel](../../) Zelle enthaltenen Wert.

```cpp
System::SharedPtr<System::Object> Aspose::Slides::Excel::ExcelDataCell::get_Value() override
```

## Bemerkungen


Beispiel: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```




## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Object](../../../system/object/)
* Klasse [ExcelDataCell](../)
* Namensraum [Aspose::Slides::Excel](../../)
* Bibliothek [Aspose.Slides](../../../)