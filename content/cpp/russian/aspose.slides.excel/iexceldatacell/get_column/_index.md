---
title: get_Column()
second_title: Aspose.Slides для C++ API справочник
description: Возвращает нулевой-основанный индекс столбца в листе, где находится ячейка. Только для чтения int32_t.
type: docs
weight: 40
url: /ru/aspose.slides.excel/iexceldatacell/get_column/
---
## IExcelDataCell::get_Column() метод

Получает нулевой-основанный индекс столбца в листе, где находится ячейка. Только для чтения **int32_t**.

```cpp
virtual int32_t Aspose::Slides::Excel::IExcelDataCell::get_Column()=0
```

## Примечания

Пример:
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(cell->get_Column());
```

## См. также

* Класс [IExcelDataCell](../)
* Пространство имён [Aspose::Slides::Excel](../../)
* Библиотека [Aspose.Slides](../../../)