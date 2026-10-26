---
title: AddChartFromWorkbook()
second_title: Aspose.Slides for C++ API 参考
description: 从指定的 Excel 工作簿中检索图表，并将其添加到给定形状集合的末尾，位于指定的坐标处。
type: docs
weight: 1
url: /zh/aspose.slides.import/excelworkbookimporter/addchartfromworkbook/
---
## ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::SharedPtr\<Aspose::Slides::Excel::IExcelDataWorkbook\>, System::String, int32_t, bool) method

检索指定的 [Excel](../../../aspose.slides.excel/) 工作簿中的图表，并将其添加到给定形状集合的末尾，位于指定的坐标处。

```cpp
static System::SharedPtr<Aspose::Slides::Charts::IChart> Aspose::Slides::Import::ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::SharedPtr<Aspose::Slides::Excel::IExcelDataWorkbook> workbook, System::String worksheetName, int32_t chartIndex, bool embedAllWorkbook)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | 要将图表添加到的形状集合。 |
| x | **float** | 用于定位图表的 X 坐标。 |
| y | **float** | 用于定位图表的 Y 坐标。 |
| workbook | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Excel::IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook/)\> | [Excel](../../../aspose.slides.excel/) 工作簿。 |
| worksheetName | [System::String](../../../system/string/) | 包含该图表的工作表名称。 |
| chartIndex | **int32_t** | 要插入的图表形状的零基索引。可使用 [IExcelDataWorkbook::GetChartsFromWorksheet(string)](../) 方法获取此索引。 |
| embedAllWorkbook | **bool** | 如果为 **true**，则整个工作簿将嵌入到图表中；如果为 **false**，则仅嵌入图表数据。 |

### 返回值

已添加到形状集合的图表。

## 备注

示例：
```cpp
System::SharedPtr<IExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_Slide(0)->get_Shapes(), 10.0f, 10.0f, wb, worksheetName, chartName, false);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::SharedPtr\<Aspose::Slides::Excel::IExcelDataWorkbook\>, System::String, System::String, bool) method

检索指定的 [Excel](../../../aspose.slides.excel/) 工作簿中的图表，并将其添加到给定形状集合的末尾，位于指定的坐标处。

```cpp
static System::SharedPtr<Aspose::Slides::Charts::IChart> Aspose::Slides::Import::ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::SharedPtr<Aspose::Slides::Excel::IExcelDataWorkbook> workbook, System::String worksheetName, System::String chartName, bool embedAllWorkbook)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | 要将图表添加到的形状集合。 |
| x | **float** | 用于定位图表的 X 坐标。 |
| y | **float** | 用于定位图表的 Y 坐标。 |
| workbook | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Excel::IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook/)\> | [Excel](../../../aspose.slides.excel/) 工作簿。 |
| worksheetName | [System::String](../../../system/string/) | 包含该图表的工作表名称。 |
| chartName | [System::String](../../../system/string/) | 要添加的图表名称。 |
| embedAllWorkbook | **bool** | 如果为 **true**，则整个工作簿将嵌入到图表中；如果为 **false**，则仅嵌入图表数据。 |

### 返回值

已添加到形状集合的图表。

## 备注

示例：
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

检索指定的 [Excel](../../../aspose.slides.excel/) 工作簿中的图表，并将其添加到给定形状集合的末尾，位于指定的坐标处。

```cpp
static System::SharedPtr<Aspose::Slides::Charts::IChart> Aspose::Slides::Import::ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::SharedPtr<System::IO::Stream> workbookStream, System::String worksheetName, System::String chartName, bool embedAllWorkbook)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | 要将图表添加到的形状集合。 |
| x | **float** | 用于定位图表的 X 坐标。 |
| y | **float** | 用于定位图表的 Y 坐标。 |
| workbookStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 包含工作簿数据的流。 |
| worksheetName | [System::String](../../../system/string/) | 包含该图表的工作表名称。 |
| chartName | [System::String](../../../system/string/) | 要添加的图表名称。 |
| embedAllWorkbook | **bool** | 如果为 **true**，则整个工作簿将嵌入到图表中；如果为 **false**，则仅嵌入图表数据。 |

### 返回值

已添加到形状集合的图表。

## 备注

示例：
```cpp
auto fStream = System::MakeObject<System::IO::FileStream>(workbookPath, System::IO::FileMode::Open, System::IO::FileAccess::Read);
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_LayoutSlide(0)->get_Shapes(), 10.0f, 10.0f, fStream, worksheetName, chartName, true);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::String, System::String, System::String, bool) method

检索指定的 [Excel](../../../aspose.slides.excel/) 工作簿中的图表，并将其添加到给定形状集合的末尾，位于指定的坐标处。

```cpp
static System::SharedPtr<Aspose::Slides::Charts::IChart> Aspose::Slides::Import::ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::String workbookPath, System::String worksheetName, System::String chartName, bool embedWorkbook)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | 要将图表添加到的形状集合。 |
| x | **float** | 用于定位图表的 X 坐标。 |
| y | **float** | 用于定位图表的 Y 坐标。 |
| workbookPath | [System::String](../../../system/string/) | 包含图表的工作簿文件路径。 |
| worksheetName | [System::String](../../../system/string/) | 包含该图表的工作表名称。 |
| chartName | [System::String](../../../system/string/) | 要添加的图表名称。 |
| embedWorkbook | **bool** | 如果为 **true**，则工作簿将嵌入到图表中；如果为 **false**，图表将链接到外部工作簿。 |

### 返回值

已添加到形状集合的图表。

## 备注

示例：
```cpp
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_Slide(0)->get_Shapes(), 10.0f, 10.0f, workbookPath, worksheetName, chartName, false);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## 另请参见

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChart](../../../aspose.slides.charts/ichart/)
* Class [IShapeCollection](../../../aspose.slides/ishapecollection/)
* Class [IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook/)
* Class [String](../../../system/string/)
* Class [ExcelWorkbookImporter](../)
* Class [Stream](../../../system.io/stream/)
* Namespace [Aspose::Slides::Import](../../)
* Library [Aspose.Slides](../../../)