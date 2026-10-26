---
title: get_Row()
second_title: Aspose.Slides für C++ API Referenz
description: Liefert den nullbasierten Index der Zeile im Arbeitsblatt, in dem sich die Zelle befindet. Schreibgeschützt int32_t.
type: docs
weight: 27
url: /de/aspose.slides.excel/iexceldatacell/get_row/
---
## IExcelDataCell::get_Row() Methode

Liefert den nullbasierten Index der Zeile im Arbeitsblatt, in dem sich die Zelle befindet. Schreibgeschützt **int32_t**.

```cpp
virtual int32_t Aspose::Slides::Excel::IExcelDataCell::get_Row()=0
```

## Hinweise

Beispiel: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(cell->get_Row());
```

## Siehe auch

* Klasse [IExcelDataCell](../)
* Namensraum [Aspose::Slides::Excel](../../)
* Library [Aspose.Slides](../../../)