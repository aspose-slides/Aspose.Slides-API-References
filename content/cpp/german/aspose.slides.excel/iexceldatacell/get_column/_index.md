---
title: get_Column()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt den nullbasierten Index der Spalte im Arbeitsblatt zurück, in dem sich die Zelle befindet. Nur lesbar int32_t.
type: docs
weight: 40
url: /de/aspose.slides.excel/iexceldatacell/get_column/
---
## IExcelDataCell::get_Column() Methode

Gibt den nullbasierten Index der Spalte im Arbeitsblatt zurück, in dem sich die Zelle befindet. Nur-Lese **int32_t**.

```cpp
virtual int32_t Aspose::Slides::Excel::IExcelDataCell::get_Column()=0
```

## Hinweise

Beispiel:
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(cell->get_Column());
```

## Siehe auch

* Klasse [IExcelDataCell](../)
* Namensraum [Aspose::Slides::Excel](../../)
* Bibliothek [Aspose.Slides](../../../)