---
title: get_Value()
second_title: Aspose.Slides für C++ API-Referenz
description: "Ermittelt den in der Excel-Zelle enthaltenen Wert. Nur lesbar System::Object."
type: docs
weight: 1
url: /de/aspose.slides.excel/iexceldatacell/get_value/
---
## IExcelDataCell::get_Value() Methode

Ermittelt den in der [Excel](../../) Zelle enthaltenen Wert. Nur lesbar [System::Object](../../../system/object/).

```cpp
virtual System::SharedPtr<System::Object> Aspose::Slides::Excel::IExcelDataCell::get_Value()=0
```

## Hinweise

Beispiel: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Object](../../../system/object/)
* Klasse [IExcelDataCell](../)
* Namensraum [Aspose::Slides::Excel](../../)
* Bibliothek [Aspose.Slides](../../../)