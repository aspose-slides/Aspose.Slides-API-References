---
title: get_Column()
second_title: Справочник API Aspose.Slides для C++
description: Получает ноль-основной индекс столбца в листе, где находится ячейка. Только для чтения int32_t.
type: docs
weight: 40
url: /ru/aspose.slides.excel/exceldatacell/get_column/
---
## ExcelDataCell::get_Column() метод


Получает ноль-основной индекс столбца в листе, где находится ячейка. Только для чтения **int32_t**.

```cpp
int32_t Aspose::Slides::Excel::ExcelDataCell::get_Column() override
```

## Примечания


Пример: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(cell->get_Column());
```

## Смотрите также

* Класс [ExcelDataCell](../)
* Пространство имён [Aspose::Slides::Excel](../../)
* Библиотека [Aspose.Slides](../../../)