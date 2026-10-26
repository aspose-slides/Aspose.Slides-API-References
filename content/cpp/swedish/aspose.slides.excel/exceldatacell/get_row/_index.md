---
title: get_Row()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar det nollbaserade indexet för raden i kalkylbladet där cellen är placerad. Endast läsning int32_t.
type: docs
weight: 27
url: /sv/aspose.slides.excel/exceldatacell/get_row/
---
## ExcelDataCell::get_Row() metod

Hämtar det nollbaserade indexet för raden i kalkylbladet där cellen är placerad. Endast läsning **int32_t**.

```cpp
int32_t Aspose::Slides::Excel::ExcelDataCell::get_Row() override
```

## Anmärkningar

Exempel:
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(cell->get_Row());
```

## Se även

* Klass [ExcelDataCell](../)
* Namnrymd [Aspose::Slides::Excel](../../)
* Bibliotek [Aspose.Slides](../../../)