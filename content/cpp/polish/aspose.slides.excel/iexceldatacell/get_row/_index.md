---
title: get_Row()
second_title: Aspose.Slides dla C++ – odwołanie API
description: Zwraca indeks wiersza w arkuszu, rozpoczynający się od zera, w którym znajduje się komórka. Tylko do odczytu int32_t.
type: docs
weight: 27
url: /pl/aspose.slides.excel/iexceldatacell/get_row/
---
## IExcelDataCell::get_Row() metoda


Zwraca indeks wiersza w arkuszu, zaczynający się od zera, w którym znajduje się komórka. Tylko do odczytu **int32_t**.

```cpp
virtual int32_t Aspose::Slides::Excel::IExcelDataCell::get_Row()=0
```

## Uwagi


Przykład: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(cell->get_Row());
```




## Zobacz także

* Klasa [IExcelDataCell](../)
* Przestrzeń nazw [Aspose::Slides::Excel](../../)
* Biblioteka [Aspose.Slides](../../../)