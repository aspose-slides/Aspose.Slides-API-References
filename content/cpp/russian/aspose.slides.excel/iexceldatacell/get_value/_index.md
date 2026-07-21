---
title: get_Value()
second_title: Aspose.Slides для C++ справочник API
description: "Получает значение, содержащееся в ячейке Excel. Только для чтения System::Object."
type: docs
weight: 1
url: /ru/aspose.slides.excel/iexceldatacell/get_value/
---
## IExcelDataCell::get_Value() метод


Получает значение, содержащееся в ячейке [Excel](../../). Только для чтения [System::Object](../../../system/object/).

```cpp
virtual System::SharedPtr<System::Object> Aspose::Slides::Excel::IExcelDataCell::get_Value()=0
```

## Замечания


Пример: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```




## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [Object](../../../system/object/)
* Класс [IExcelDataCell](../)
* Пространство имен [Aspose::Slides::Excel](../../)
* Библиотека [Aspose.Slides](../../../)