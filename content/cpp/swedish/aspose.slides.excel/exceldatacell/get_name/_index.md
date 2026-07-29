---
title: get_Name()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar namnet på diagrammets datacell.
type: docs
weight: 14
url: /sv/aspose.slides.excel/exceldatacell/get_name/
---
## ExcelDataCell::get_Name() metod

Hämtar namnet på diagrammets datacell.

```cpp
System::String Aspose::Slides::Excel::ExcelDataCell::get_Name() override
```

## Anmärkningar

Example: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(cell->get_Name());
```

## Se även

* Klass [String](../../../system/string/)
* Klass [ExcelDataCell](../)
* Namnrymd [Aspose::Slides::Excel](../../)
* Bibliotek [Aspose.Slides](../../../)