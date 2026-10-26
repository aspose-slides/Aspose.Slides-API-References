---
title: get_Row()
second_title: Справочная документация API Aspose.Slides для C++
description: Получает нулевой индекс строки в листе, где расположена ячейка. Только для чтения int32_t.
type: docs
weight: 27
url: /ru/aspose.slides.excel/iexceldatacell/get_row/
---
## IExcelDataCell::get_Row() метод

Получает индекс строки в листе, начиная с нуля, где расположена ячейка. Только для чтения **int32_t**.

```cpp
virtual int32_t Aspose::Slides::Excel::IExcelDataCell::get_Row()=0
```

## Замечания

Пример: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(cell->get_Row());
```

## См. также

* Класс [IExcelDataCell](../)
* Пространство имён [Aspose::Slides::Excel](../../)
* Library [Aspose.Slides](../../../)