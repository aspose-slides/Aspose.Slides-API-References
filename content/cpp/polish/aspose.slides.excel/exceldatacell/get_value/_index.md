---
title: get_Value()
second_title: Odwołanie API Aspose.Slides dla C++
description: Pobiera wartość zawartą w komórce Excel.
type: docs
weight: 1
url: /pl/aspose.slides.excel/exceldatacell/get_value/
---
## ExcelDataCell::get_Value() metoda


Pobiera wartość zawartą w komórce [Excel](../../).

```cpp
System::SharedPtr<System::Object> Aspose::Slides::Excel::ExcelDataCell::get_Value() override
```

## Uwagi


Przykład:
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```




## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [Object](../../../system/object/)
* Klasa [ExcelDataCell](../)
* Przestrzeń nazw [Aspose::Slides::Excel](../../)
* Biblioteka [Aspose.Slides](../../../)