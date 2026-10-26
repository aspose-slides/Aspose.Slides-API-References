---
title: AddChartFromWorkbook()
second_title: Справочник API Aspose.Slides для C++
description: Получает диаграмму из указанной Excel-рабочей книги и добавляет её в конец указанной коллекции фигур в заданных координатах.
type: docs
weight: 1
url: /ru/aspose.slides.import/excelworkbookimporter/addchartfromworkbook/
---
## ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::SharedPtr\<Aspose::Slides::Excel::IExcelDataWorkbook\>, System::String, int32_t, bool) method

Получает диаграмму из указанной [Excel](../../../aspose.slides.excel/) рабочей книги и добавляет её в конец указанной коллекции фигур в заданных координатах.

```cpp
static System::SharedPtr<Aspose::Slides::Charts::IChart> Aspose::Slides::Import::ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::SharedPtr<Aspose::Slides::Excel::IExcelDataWorkbook> workbook, System::String worksheetName, int32_t chartIndex, bool embedAllWorkbook)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | Коллекция фигур, в которую будет добавлена диаграмма. |
| x | **float** | Координата X для размещения диаграммы. |
| y | **float** | Координата Y для размещения диаграммы. |
| workbook | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Excel::IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook/)\> | Рабочая книга [Excel](../../../aspose.slides.excel/). |
| worksheetName | [System::String](../../../system/string/) | Имя листа, содержащего диаграмму. |
| chartIndex | **int32_t** | Нулевой индекс диаграммы для вставки. Этот индекс можно получить с помощью метода [IExcelDataWorkbook::GetChartsFromWorksheet(string)](../). |
| embedAllWorkbook | **bool** | Если **true**, вся рабочая книга будет внедрена в диаграмму; если **false**, будет внедрены только данные диаграммы. |

### Возвращаемое значение

Диаграмма, добавленная в коллекцию фигур.

## Примечания



Пример: 
```cpp
System::SharedPtr<IExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_Slide(0)->get_Shapes(), 10.0f, 10.0f, wb, worksheetName, chartName, false);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::SharedPtr\<Aspose::Slides::Excel::IExcelDataWorkbook\>, System::String, System::String, bool) method

Получает диаграмму из указанной [Excel](../../../aspose.slides.excel/) рабочей книги и добавляет её в конец указанной коллекции фигур в заданных координатах.

```cpp
static System::SharedPtr<Aspose::Slides::Charts::IChart> Aspose::Slides::Import::ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::SharedPtr<Aspose::Slides::Excel::IExcelDataWorkbook> workbook, System::String worksheetName, System::String chartName, bool embedAllWorkbook)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | Коллекция фигур, в которую будет добавлена диаграмма. |
| x | **float** | Координата X для размещения диаграммы. |
| y | **float** | Координата Y для размещения диаграммы. |
| workbook | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Excel::IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook/)\> | Рабочая книга [Excel](../../../aspose.slides.excel/). |
| worksheetName | [System::String](../../../system/string/) | Имя листа, содержащего диаграмму. |
| chartName | [System::String](../../../system/string/) | Имя добавляемой диаграммы. |
| embedAllWorkbook | **bool** | Если **true**, вся рабочая книга будет внедрена в диаграмму; если **false**, будет внедрены только данные диаграммы. |

### Возвращаемое значение

Диаграмма, добавленная в коллекцию фигур.

## Примечания



Пример: 
```cpp
System::SharedPtr<IExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
auto pres = System::MakeObject<Presentation>();

System::String worksheetName = u"worksheet name";
auto worksheetCharts = wb->GetChartsFromWorksheet(worksheetName);
for (auto&& chart : worksheetCharts)
{
    System::SharedPtr<ISlide> slide = pres->get_Slides()->AddEmptySlide(pres->get_LayoutSlides()->idx_get(0));
    ExcelWorkbookImporter::AddChartFromWorkbook(slide->get_Shapes(), 10.0f, 10.0f, wb, worksheetName, chart.get_Key(), false);
}
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::SharedPtr\<System::IO::Stream\>, System::String, System::String, bool) method

Получает диаграмму из указанной [Excel](../../../aspose.slides.excel/) рабочей книги и добавляет её в конец указанной коллекции фигур в заданных координатах.

```cpp
static System::SharedPtr<Aspose::Slides::Charts::IChart> Aspose::Slides::Import::ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::SharedPtr<System::IO::Stream> workbookStream, System::String worksheetName, System::String chartName, bool embedAllWorkbook)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | Коллекция фигур, в которую будет добавлена диаграмма. |
| x | **float** | Координата X для размещения диаграммы. |
| y | **float** | Координата Y для размещения диаграммы. |
| workbookStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Поток, содержащий данные рабочей книги. |
| worksheetName | [System::String](../../../system/string/) | Имя листа, содержащего диаграмму. |
| chartName | [System::String](../../../system/string/) | Имя добавляемой диаграммы. |
| embedAllWorkbook | **bool** | Если **true**, вся рабочая книга будет внедрена в диаграмму; если **false**, будет внедрены только данные диаграммы. |

### Возвращаемое значение

Диаграмма, добавленная в коллекцию фигур.

## Примечания



Пример: 
```cpp
auto fStream = System::MakeObject<System::IO::FileStream>(workbookPath, System::IO::FileMode::Open, System::IO::FileAccess::Read);
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_LayoutSlide(0)->get_Shapes(), 10.0f, 10.0f, fStream, worksheetName, chartName, true);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::String, System::String, System::String, bool) method

Получает диаграмму из указанной [Excel](../../../aspose.slides.excel/) рабочей книги и добавляет её в конец указанной коллекции фигур в заданных координатах.

```cpp
static System::SharedPtr<Aspose::Slides::Charts::IChart> Aspose::Slides::Import::ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::String workbookPath, System::String worksheetName, System::String chartName, bool embedWorkbook)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | Коллекция фигур, в которую будет добавлена диаграмма. |
| x | **float** | Координата X для размещения диаграммы. |
| y | **float** | Координата Y для размещения диаграммы. |
| workbookPath | [System::String](../../../system/string/) | Путь к файлу рабочей книги, содержащей диаграмму. |
| worksheetName | [System::String](../../../system/string/) | Имя листа, содержащего диаграмму. |
| chartName | [System::String](../../../system/string/) | Имя добавляемой диаграммы. |
| embedWorkbook | **bool** | Если **true**, рабочая книга будет внедрена в диаграмму; если **false**, диаграмма будет ссылаться на внешнюю рабочую книгу. |

### Возвращаемое значение

Диаграмма, добавленная в коллекцию фигур.

## Примечания



Пример: 
```cpp
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_Slide(0)->get_Shapes(), 10.0f, 10.0f, workbookPath, worksheetName, chartName, false);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [IChart](../../../aspose.slides.charts/ichart/)
* Класс [IShapeCollection](../../../aspose.slides/ishapecollection/)
* Класс [IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook/)
* Класс [String](../../../system/string/)
* Класс [ExcelWorkbookImporter](../)
* Класс [Stream](../../../system.io/stream/)
* Пространство имён [Aspose::Slides::Import](../../)
* Библиотека [Aspose.Slides](../../../)