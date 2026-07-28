---
title: get_Column()
second_title: Aspose.Slides for C++ – Referencja API
description: Zwraca zerowy indeks kolumny w arkuszu kalkulacyjnym, w którym znajduje się komórka. Tylko do odczytu int32_t.
type: docs
weight: 40
url: /pl/aspose.slides.excel/iexceldatacell/get_column/
---
## IExcelDataCell::get_Column() metoda


Pobiera zerowy indeks kolumny w arkuszu kalkulacyjnym, w którym znajduje się komórka. Tylko do odczytu **int32_t**.

```cpp
virtual int32_t Aspose::Slides::Excel::IExcelDataCell::get_Column()=0
```

## Uwagi


Przykład: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(cell->get_Column());
```

## Zobacz także

* Klasa [IExcelDataCell](../)
* Przestrzeń nazw [Aspose::Slides::Excel](../../)
* Biblioteka [Aspose.Slides](../../../)