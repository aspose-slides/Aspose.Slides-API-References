---
title: get_Value()
second_title: Aspose.Slides dla C++ - odniesienie API
description: "Pobiera wartość zawartą w komórce Excel. Tylko do odczytu System::Object."
type: docs
weight: 1
url: /pl/aspose.slides.excel/iexceldatacell/get_value/
---
## IExcelDataCell::get_Value() metoda

Pobiera wartość zawartą w komórce [Excel](../../). Tylko do odczytu [System::Object](../../../system/object/).

```cpp
virtual System::SharedPtr<System::Object> Aspose::Slides::Excel::IExcelDataCell::get_Value()=0
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
* Klasa [IExcelDataCell](../)
* Przestrzeń nazw [Aspose::Slides::Excel](../../)
* Biblioteka [Aspose.Slides](../../../)