---
title: GetCell()
second_title: Aspose.Slides для C++ справочник API
description: Получает ячейку из указанного листа, используя её индекс и координаты ячейки.
type: docs
weight: 27
url: /ru/aspose.slides.excel/exceldataworkbook/getcell/
---
## ExcelDataWorkbook::GetCell(int32_t, int32_t, int32_t) method

Получает ячейку из указанного листа, используя её индекс и координаты ячейки.

```cpp
System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::ExcelDataWorkbook::GetCell(int32_t worksheetIndex, int32_t row, int32_t column) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Индекс листа, начинающийся с нуля. |
| row | **int32_t** | Индекс строки ячейки, начинающийся с нуля. |
| column | **int32_t** | Индекс столбца ячейки, начинающийся с нуля. |

### Возвращаемое значение

Ячейка в указанном месте.

## Примечания



Пример: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## ExcelDataWorkbook::GetCell(System::String, int32_t, int32_t) method

Получает ячейку из указанного листа, используя её имя и координаты ячейки.

```cpp
System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::ExcelDataWorkbook::GetCell(System::String worksheetName, int32_t row, int32_t column) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | Имя листа. |
| row | **int32_t** | Индекс строки ячейки, начинающийся с нуля. |
| column | **int32_t** | Индекс столбца ячейки, начинающийся с нуля. |

### Возвращаемое значение

Ячейка в указанном месте.

## Примечания



Пример: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(u"Sheet1", 1, 1);
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## ExcelDataWorkbook::GetCell(int32_t, System::String) method

Получает ячейку из указанного листа, используя её индекс и название ячейки в стиле Excel (например, "B2").

```cpp
System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::ExcelDataWorkbook::GetCell(int32_t worksheetIndex, System::String cellName) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Индекс листа, начинающийся с нуля. |
| cellName | [System::String](../../../system/string/) | Ссылка на ячейку в стиле Excel (например, "A1", "C5"). |

### Возвращаемое значение

Ячейка в указанном месте.

## Примечания



Пример: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(1, u"B2");
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## ExcelDataWorkbook::GetCell(System::String, System::String) method

Получает ячейку из указанного листа, используя название ячейки в стиле Excel (например, "B2").

```cpp
System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::ExcelDataWorkbook::GetCell(System::String worksheetName, System::String cellName) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | Имя листа. |
| cellName | [System::String](../../../system/string/) | Ссылка на ячейку в стиле Excel (например, "A1", "C5"). |

### Возвращаемое значение

Ячейка в указанном месте.

## Примечания



Пример: 
```cpp
System::SharedPtr<ExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
System::SharedPtr<IExcelDataCell> cell = wb->GetCell(u"Sheet1", u"B2");
System::Console::WriteLine(System::ObjectExt::ToString(cell->get_Value()));
```

## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [IExcelDataCell](../../iexceldatacell/)
* Класс [ExcelDataWorkbook](../)
* Класс [String](../../../system/string/)
* Пространство имён [Aspose::Slides::Excel](../../)
* Библиотека [Aspose.Slides](../../../)