---
title: get_Value()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar värdet som finns i Excel-cellen.
type: docs
weight: 1
url: /sv/aspose.slides.excel/exceldatacell/get_value/
---
## ExcelDataCell::get_Value() metod


Hämtar värdet som finns i cellen [Excel](../../).

```cpp
System::SharedPtr<System::Object> Aspose::Slides::Excel::ExcelDataCell::get_Value() override
```

## Anmärkningar


Exempel: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```




## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [Object](../../../system/object/)
* Klass [ExcelDataCell](../)
* Namnrymd [Aspose::Slides::Excel](../../)
* Bibliotek [Aspose.Slides](../../../)