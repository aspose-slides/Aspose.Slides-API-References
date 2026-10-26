---
title: GetCells()
second_title: Aspose.Slides для C++ API Reference
description: Получает коллекцию ячеек из рабочей книги, соответствующих указанной формуле.
type: docs
weight: 14
url: /ru/aspose.slides.excel/exceldataworkbook/getcells/
---
## ExcelDataWorkbook::GetCells(System::String, bool) метод


Получает коллекцию ячеек из рабочей книги, соответствующих указанной формуле.

```cpp
System::SharedPtr<System::Collections::ObjectModel::ReadOnlyCollection<System::SharedPtr<IExcelDataCell>>> Aspose::Slides::Excel::ExcelDataWorkbook::GetCells(System::String formula, bool skipHiddenCells) override
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| formula | [System::String](../../../system/string/) | Формула или диапазон (например, "Sheet1!A1:B3"), используемые для идентификации целевых ячеек. |
| skipHiddenCells | **bool** | Если **true**, скрытые ячейки (например, в скрытых строках или столбцах) будут исключены из результата. |

### Возвращаемое значение

Только для чтения список ячеек, соответствующих указанной формуле.
## Примечания



Пример:
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<System::Collections::ObjectModel::ReadOnlyCollection<System::SharedPtr<IExcelDataCell>>> cells = wb->GetCells(u"Sheet1!A2:A6", false);
System::Console::WriteLine(cells->get_Count());
```

## Смотрите также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [ReadOnlyCollection](../../../system.collections.objectmodel/readonlycollection/)
* Класс [IExcelDataCell](../../iexceldatacell/)
* Класс [String](../../../system/string/)
* Класс [ExcelDataWorkbook](../)
* Пространство имён [Aspose::Slides::Excel](../../)
* Библиотека [Aspose.Slides](../../../)