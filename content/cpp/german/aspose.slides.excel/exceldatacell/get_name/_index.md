---
title: get_Name()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt den Namen der Diagrammdatenzelle zurück.
type: docs
weight: 14
url: /de/aspose.slides.excel/exceldatacell/get_name/
---
## ExcelDataCell::get_Name() Methode


Gibt den Namen der Diagrammdatenzelle zurück.

```cpp
System::String Aspose::Slides::Excel::ExcelDataCell::get_Name() override
```

## Hinweise


Beispiel: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(cell->get_Name());
```




## Siehe auch

* Klasse [String](../../../system/string/)
* Klasse [ExcelDataCell](../)
* Namensraum [Aspose::Slides::Excel](../../)
* Bibliothek [Aspose.Slides](../../../)