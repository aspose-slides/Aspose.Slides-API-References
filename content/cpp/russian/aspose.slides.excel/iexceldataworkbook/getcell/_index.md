---
title: GetCell()
second_title: Aspose.Slides для C++ справочник API
description: Получает ячейку из указанного листа, используя её индекс и координаты ячейки.
type: docs
weight: 14
url: /ru/aspose.slides.excel/iexceldataworkbook/getcell/
---
## IExcelDataWorkbook::GetCell(int32_t, int32_t, int32_t) method

Получает ячейку из указанного листа, используя его индекс и координаты ячейки.

```cpp
virtual System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::IExcelDataWorkbook::GetCell(int32_t worksheetIndex, int32_t row, int32_t column)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Индекс листа, начиная с нуля. |
| row | **int32_t** | Индекс строки ячейки, начиная с нуля. |
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

## IExcelDataWorkbook::GetCell(System::String, int32_t, int32_t) method

Получает ячейку из указанного листа, используя его имя и координаты ячейки.

```cpp
virtual System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::IExcelDataWorkbook::GetCell(System::String worksheetName, int32_t row, int32_t column)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | Имя листа. |
| row | **int32_t** | Индекс строки ячейки, начиная с нуля. |
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

## IExcelDataWorkbook::GetCell(int32_t, System::String) method

Получает ячейку из указанного листа, используя его индекс и имя ячейки в стиле Excel (например, "B2").

```cpp
virtual System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::IExcelDataWorkbook::GetCell(int32_t worksheetIndex, System::String cellName)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| worksheetIndex | **int32_t** | Индекс листа, начиная с нуля. |
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

## IExcelDataWorkbook::GetCell(System::String, System::String) method

Получает ячейку из указанного листа, используя имя ячейки в стиле Excel (например, "B2").

```cpp
virtual System::SharedPtr<IExcelDataCell> Aspose::Slides::Excel::IExcelDataWorkbook::GetCell(System::String worksheetName, System::String cellName)=0
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

* Типовое определение [SharedPtr](../../../system/sharedptr/)
* Класс [IExcelDataCell](../../iexceldatacell/)
* Класс [IExcelDataWorkbook](../)
* Класс [String](../../../system/string/)
* Пространство имен [Aspose::Slides::Excel](../../)
* Библиотека [Aspose.Slides](../../../)