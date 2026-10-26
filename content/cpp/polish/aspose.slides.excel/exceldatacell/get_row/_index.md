---
title: get_Row()
second_title: Odwołanie API Aspose.Slides dla C++
description: Zwraca zero-indeksowy numer wiersza w arkuszu, w którym znajduje się komórka. Tylko do odczytu int32_t.
type: docs
weight: 27
url: /pl/aspose.slides.excel/exceldatacell/get_row/
---
## ExcelDataCell::get_Row() metoda


Zwraca zero-indeksowy numer wiersza w arkuszu, w którym znajduje się komórka. Tylko do odczytu **int32_t**.

```cpp
int32_t Aspose::Slides::Excel::ExcelDataCell::get_Row() override
```

## Uwagi


Przykład: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(cell->get_Row());
```




## Zobacz także

* Klasa [ExcelDataCell](../)
* Przestrzeń nazw [Aspose::Slides::Excel](../../)
* Biblioteka [Aspose.Slides](../../../)