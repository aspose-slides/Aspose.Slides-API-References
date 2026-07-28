---
title: get_Name()
second_title: Aspose.Slides dla C++ - Odwołanie API
description: "Pobiera nazwę komórki danych wykresu. Tylko do odczytu System::String."
type: docs
weight: 14
url: /pl/aspose.slides.excel/iexceldatacell/get_name/
---
## IExcelDataCell::get_Name() metoda


Pobiera nazwę komórki danych wykresu. Tylko do odczytu [System::String](../../../system/string/).

```cpp
virtual System::String Aspose::Slides::Excel::IExcelDataCell::get_Name()=0
```

## Uwagi


Przykład: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(cell->get_Name());
```




## Zobacz także

* Klasa [String](../../../system/string/)
* Klasa [IExcelDataCell](../)
* Przestrzeń nazw [Aspose::Slides::Excel](../../)
* Biblioteka [Aspose.Slides](../../../)