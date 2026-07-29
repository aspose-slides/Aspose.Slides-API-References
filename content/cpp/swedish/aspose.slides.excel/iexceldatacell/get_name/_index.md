---
title: get_Name()
second_title: Aspose.Slides för C++ API-referens
description: "Hämtar namnet på diagrammets datacell. Endast läsning System::String."
type: docs
weight: 14
url: /sv/aspose.slides.excel/iexceldatacell/get_name/
---
## IExcelDataCell::get_Name() metod


Hämtar namnet på diagrammets datacell. Endast läsning [System::String](../../../system/string/).

```cpp
virtual System::String Aspose::Slides::Excel::IExcelDataCell::get_Name()=0
```

## Anmärkningar


Exempel: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(cell->get_Name());
```




## Se även

* Klass [String](../../../system/string/)
* Klass [IExcelDataCell](../)
* Namnrymd [Aspose::Slides::Excel](../../)
* Bibliotek [Aspose.Slides](../../../)