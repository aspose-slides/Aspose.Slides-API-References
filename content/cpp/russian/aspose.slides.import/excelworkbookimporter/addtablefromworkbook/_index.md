---
title: AddTableFromWorkbook()
second_title: Справочник API Aspose.Slides для C++
description: Получает таблицу из указанной рабочей книги Excel и добавляет её в конец заданной коллекции фигур на указанных координатах.
type: docs
weight: 14
url: /ru/aspose.slides.import/excelworkbookimporter/addtablefromworkbook/
---
## ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::SharedPtr\<Aspose::Slides::Excel::IExcelDataWorkbook\>, System::String, System::String) method

Получает таблицу из указанной [Excel](../../../aspose.slides.excel/) рабочей книги и добавляет её в конец заданной коллекции фигур на указанных координатах.

```cpp
static System::SharedPtr<Aspose::Slides::ITable> Aspose::Slides::Import::ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::SharedPtr<Aspose::Slides::Excel::IExcelDataWorkbook> workbook, System::String worksheetName, System::String cellRange)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | Коллекция фигур, в которую будет добавлена таблица. |
| x | **float** | Координата X для позиционирования таблицы. |
| y | **float** | Координата Y для позиционирования таблицы. |
| workbook | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Excel::IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook/)\> | [Excel](../../../aspose.slides.excel/) рабочая книга. |
| worksheetName | [System::String](../../../system/string/) | Имя листа, содержащего таблицу. |
| cellRange | [System::String](../../../system/string/) | Диапазон ячеек, определяющий таблицу (например, "A1:D10"). |

### Возвращаемое значение

Таблица, добавленная в коллекцию фигур.

## Замечания

```cpp
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_Slide(0)->get_Shapes(), 10.0f, 10.0f, workbook, worksheetName, cellRange);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::String, System::String, System::String) method

Получает таблицу из указанного [Excel](../../../aspose.slides.excel/) файла рабочей книги и добавляет её в конец заданной коллекции фигур на указанных координатах.

```cpp
static System::SharedPtr<Aspose::Slides::ITable> Aspose::Slides::Import::ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::String workbookPath, System::String worksheetName, System::String cellRange)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | Коллекция фигур, в которую будет добавлена таблица. |
| x | **float** | Координата X для позиционирования таблицы. |
| y | **float** | Координата Y для позиционирования таблицы. |
| workbookPath | [System::String](../../../system/string/) | Путь к [Excel](../../../aspose.slides.excel/) файлу рабочей книги. |
| worksheetName | [System::String](../../../system/string/) | Имя листа, содержащего таблицу. |
| cellRange | [System::String](../../../system/string/) | Диапазон ячеек, определяющий таблицу (например, "A1:D10"). |

### Возвращаемое значение

Таблица, добавленная в коллекцию фигур.

## Замечания

```cpp
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_Slide(0)->get_Shapes(), 10.0f, 10.0f, workbookPath, worksheetName, cellRange);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::SharedPtr\<System::IO::Stream\>, System::String, System::String) method

Получает таблицу из указанного [Excel](../../../aspose.slides.excel/) файла рабочей книги и добавляет её в конец заданной коллекции фигур на указанных координатах.

```cpp
static System::SharedPtr<Aspose::Slides::ITable> Aspose::Slides::Import::ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::SharedPtr<System::IO::Stream> workbookStream, System::String worksheetName, System::String cellRange)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | Коллекция фигур, в которую будет добавлена таблица. |
| x | **float** | Координата X для позиционирования таблицы. |
| y | **float** | Координата Y для позиционирования таблицы. |
| workbookStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Поток, содержащий данные рабочей книги. |
| worksheetName | [System::String](../../../system/string/) | Имя листа, содержащего таблицу. |
| cellRange | [System::String](../../../system/string/) | Диапазон ячеек, определяющий таблицу (например, "A1:D10"). |

### Возвращаемое значение

Таблица, добавленная в коллекцию фигур.

## Замечания

```cpp
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_Slide(0)->get_Shapes(), 10.0f, 10.0f, fStream, worksheetName, cellRange);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [ITable](../../../aspose.slides/itable/)
* Класс [IShapeCollection](../../../aspose.slides/ishapecollection/)
* Класс [IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook/)
* Класс [String](../../../system/string/)
* Класс [ExcelWorkbookImporter](../)
* Класс [Stream](../../../system.io/stream/)
* Пространство имён [Aspose::Slides::Import](../../)
* Библиотека [Aspose.Slides](../../../)