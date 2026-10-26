---
title: GetCells()
second_title: Aspose.Slides для C++ API Справочник
description: Получает коллекцию ячеек из рабочей книги, которые соответствуют указанной формуле.
type: docs
weight: 1
url: /ru/aspose.slides.excel/iexceldataworkbook/getcells/
---
## IExcelDataWorkbook::GetCells(System::String, bool) метод


Получает коллекцию ячеек из рабочей книги, которые соответствуют указанной формуле.

```cpp
virtual System::SharedPtr<System::Collections::ObjectModel::ReadOnlyCollection<System::SharedPtr<IExcelDataCell>>> Aspose::Slides::Excel::IExcelDataWorkbook::GetCells(System::String formula, bool skipHiddenCells)=0
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| formula | [System::String](../../../system/string/) | Формула или выражение диапазона (например, \"Sheet1!A1:B3\") используется для идентификации целевых ячеек. |
| skipHiddenCells | **bool** | Если **true**, скрытые ячейки (например, в скрытых строках или столбцах) будут исключены из результата. |

### Возвращаемое значение

Только для чтения список ячеек, которые соответствуют указанной формуле.
## Примечания



Пример: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<System::Collections::ObjectModel::ReadOnlyCollection<System::SharedPtr<IExcelDataCell>>> cells = wb->GetCells(u"Sheet1!A2:A6", false);
System::Console::WriteLine(cells->get_Count());
```

## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [ReadOnlyCollection](../../../system.collections.objectmodel/readonlycollection/)
* Класс [IExcelDataCell](../../iexceldatacell/)
* Класс [String](../../../system/string/)
* Класс [IExcelDataWorkbook](../)
* Пространство имен [Aspose::Slides::Excel](../../)
* Библиотека [Aspose.Slides](../../../)