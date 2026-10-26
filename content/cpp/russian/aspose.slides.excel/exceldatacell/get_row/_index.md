---
title: get_Row()
second_title: Справочник API Aspose.Slides для C++
description: Получает нулевой индекс строки в листе, где находится ячейка. Только для чтения int32_t.
type: docs
weight: 27
url: /ru/aspose.slides.excel/exceldatacell/get_row/
---
## ExcelDataCell::get_Row() метод

Получает нулевой индекс строки в листе, где находится ячейка. Только для чтения **int32_t**.

```cpp
int32_t Aspose::Slides::Excel::ExcelDataCell::get_Row() override
```

## Примечание


Пример: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(cell->get_Row());
```


## Смотрите также

* Класс [ExcelDataCell](../)
* Пространство имён [Aspose::Slides::Excel](../../)
* Библиотека [Aspose.Slides](../../../)