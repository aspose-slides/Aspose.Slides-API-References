---
title: GetWorksheetNames()
second_title: Aspose.Slides для C++ справочник API
description: Получает имена всех листов, содержащихся в рабочей книге Excel.
type: docs
weight: 40
url: /ru/aspose.slides.excel/iexceldataworkbook/getworksheetnames/
---
## IExcelDataWorkbook::GetWorksheetNames() method


Получает имена всех листов, содержащихся в рабочей книге [Excel](../../).

```cpp
virtual System::SharedPtr<System::Collections::Generic::IList<System::String>> Aspose::Slides::Excel::IExcelDataWorkbook::GetWorksheetNames()=0
```


### Возвращаемое значение

Список имён листов
## Примечания



Пример: 
```cpp
System::SharedPtr<IExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
auto sheetNames = wb->GetWorksheetNames();
for (auto&& name : sheetNames)
{
    System::Console::WriteLine(name);
}
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IList](../../../system.collections.generic/ilist/)
* Класс [String](../../../system/string/)
* Класс [IExcelDataWorkbook](../)
* Пространство имён [Aspose::Slides::Excel](../../)
* Библиотека [Aspose.Slides](../../../)