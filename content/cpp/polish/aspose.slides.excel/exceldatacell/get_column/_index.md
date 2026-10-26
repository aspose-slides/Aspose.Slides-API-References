---
title: get_Column()
second_title: Aspose.Slides dla C++ referencja API
description: Zwraca indeks kolumny liczony od zera w arkuszu, w którym znajduje się komórka. Tylko do odczytu int32_t.
type: docs
weight: 40
url: /pl/aspose.slides.excel/exceldatacell/get_column/
---
## ExcelDataCell::get_Column() metoda

Zwraca indeks kolumny liczony od zera w arkuszu, w którym znajduje się komórka. Tylko do odczytu **int32_t**.

```cpp
int32_t Aspose::Slides::Excel::ExcelDataCell::get_Column() override
```

## Uwagi

Przykład:
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(cell->get_Column());
```

## Zobacz także

* Klasa [ExcelDataCell](../)
* Przestrzeń nazw [Aspose::Slides::Excel](../../)
* Biblioteka [Aspose.Slides](../../../)