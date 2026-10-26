---
title: get_Row()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar det nollbaserade indexet för raden i kalkylbladet där cellen är placerad. Skrivskyddad int32_t.
type: docs
weight: 27
url: /sv/aspose.slides.excel/iexceldatacell/get_row/
---
## IExcelDataCell::get_Row() metod


Hämtar det nollbaserade indexet för raden i kalkylbladet där cellen är placerad. Skrivskyddad **int32_t**.

```cpp
virtual int32_t Aspose::Slides::Excel::IExcelDataCell::get_Row()=0
```

## Anmärkningar


Exempel:
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(cell->get_Row());
```


## Se även

* Klass [IExcelDataCell](../)
* Namnrymd [Aspose::Slides::Excel](../../)
* Bibliotek [Aspose.Slides](../../../)