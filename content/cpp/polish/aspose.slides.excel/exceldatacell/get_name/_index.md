---
title: get_Name()
second_title: Aspose.Slides dla C++ Dokumentacja API
description: Pobiera nazwę komórki danych wykresu.
type: docs
weight: 14
url: /pl/aspose.slides.excel/exceldatacell/get_name/
---
## ExcelDataCell::get_Name() metoda


Pobiera nazwę komórki danych wykresu.

```cpp
System::String Aspose::Slides::Excel::ExcelDataCell::get_Name() override
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
* Klasa [ExcelDataCell](../)
* Przestrzeń nazw [Aspose::Slides::Excel](../../)
* Biblioteka [Aspose.Slides](../../../)