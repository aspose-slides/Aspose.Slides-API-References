---
title: get_Column()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar det nollbaserade indexet för kolumnen i arbetsbladet där cellen är placerad. Skrivskyddad int32_t.
type: docs
weight: 40
url: /sv/aspose.slides.excel/iexceldatacell/get_column/
---
## IExcelDataCell::get_Column() metod


Hämtar det nollbaserade indexet för kolumnen i arbetsbladet där cellen är placerad. Skrivskyddad **int32_t**.

```cpp
virtual int32_t Aspose::Slides::Excel::IExcelDataCell::get_Column()=0
```

## Anmärkningar


Exempel: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(cell->get_Column());
```

## Se också

* Klass [IExcelDataCell](../)
* Namnrymd [Aspose::Slides::Excel](../../)
* Bibliotek [Aspose.Slides](../../../)