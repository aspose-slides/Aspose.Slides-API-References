---
title: get_Row()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt den nullbasierten Index der Zeile im Arbeitsblatt zurück, in dem die Zelle liegt. Nur-Lesen int32_t.
type: docs
weight: 27
url: /de/aspose.slides.excel/exceldatacell/get_row/
---
## ExcelDataCell::get_Row() Methode


Gibt den nullbasierten Index der Zeile im Arbeitsblatt zurück, in dem die Zelle liegt. Nur-Lesen **int32_t**.

```cpp
int32_t Aspose::Slides::Excel::ExcelDataCell::get_Row() override
```

## Bemerkungen


Beispiel: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(cell->get_Row());
```




## Siehe auch

* Klasse [ExcelDataCell](../)
* Namensraum [Aspose::Slides::Excel](../../)
* Bibliothek [Aspose.Slides](../../../)