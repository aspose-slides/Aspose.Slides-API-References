---
title: get_Column()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar det nollbaserade indexet för kolumnen i kalkylbladet där cellen är placerad. Skrivskyddad int32_t.
type: docs
weight: 40
url: /sv/aspose.slides.excel/exceldatacell/get_column/
---
## ExcelDataCell::get_Column() metod

Hämtar det nollbaserade indexet för kolumnen i kalkylbladet där cellen är placerad. Skrivskyddad **int32_t**.

```cpp
int32_t Aspose::Slides::Excel::ExcelDataCell::get_Column() override
```

## Anmärkningar

Exempel:
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(cell->get_Column());
```

## Se även

* Klass [ExcelDataCell](../)
* Namnrymd [Aspose::Slides::Excel](../../)
* Library [Aspose.Slides](../../../)