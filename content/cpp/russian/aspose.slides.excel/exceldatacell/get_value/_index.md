---
title: get_Value()
second_title: Aspose.Slides для C++ справочник API
description: Получает значение, содержащееся в ячейке Excel.
type: docs
weight: 1
url: /ru/aspose.slides.excel/exceldatacell/get_value/
---
## ExcelDataCell::get_Value() метод

Получает значение, содержащееся в ячейке [Excel](../../).

```cpp
System::SharedPtr<System::Object> Aspose::Slides::Excel::ExcelDataCell::get_Value() override
```

## Примечания

Пример:
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## См. также

* Типовое определение [SharedPtr](../../../system/sharedptr/)
* Класс [Object](../../../system/object/)
* Класс [ExcelDataCell](../)
* Пространство имен [Aspose::Slides::Excel](../../)
* Библиотека [Aspose.Slides](../../../)