---
title: get_Name()
second_title: Справочник API Aspose.Slides для C++
description: Получает имя ячейки данных диаграммы.
type: docs
weight: 14
url: /ru/aspose.slides.excel/exceldatacell/get_name/
---
## ExcelDataCell::get_Name() метод


Получает имя ячейки данных диаграммы.

```cpp
System::String Aspose::Slides::Excel::ExcelDataCell::get_Name() override
```

## Примечания


Пример:
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(cell->get_Name());
```




## Смотрите также

* Класс [String](../../../system/string/)
* Класс [ExcelDataCell](../)
* Пространство имён [Aspose::Slides::Excel](../../)
* Библиотека [Aspose.Slides](../../../)