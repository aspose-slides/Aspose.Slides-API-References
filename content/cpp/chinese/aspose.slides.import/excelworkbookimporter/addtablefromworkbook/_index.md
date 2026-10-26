---
title: AddTableFromWorkbook()
second_title: Aspose.Slides for C++ API 参考
description: 从指定的 Excel 工作簿检索表格，并将其添加到给定形状集合的末尾，位于指定的坐标处。
type: docs
weight: 14
url: /zh/aspose.slides.import/excelworkbookimporter/addtablefromworkbook/
---
## ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::SharedPtr\<Aspose::Slides::Excel::IExcelDataWorkbook\>, System::String, System::String) method

从指定的 [Excel](../../../aspose.slides.excel/) 工作簿检索表格，并将其添加到给定形状集合的末尾，位于指定的坐标处。

```cpp
static System::SharedPtr<Aspose::Slides::ITable> Aspose::Slides::Import::ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::SharedPtr<Aspose::Slides::Excel::IExcelDataWorkbook> workbook, System::String worksheetName, System::String cellRange)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | 将添加表格的形状集合。 |
| x | **float** | 用于定位表格的 X 坐标。 |
| y | **float** | 用于定位表格的 Y 坐标。 |
| workbook | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Excel::IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook/)\> | [Excel](../../../aspose.slides.excel/) 工作簿。 |
| worksheetName | [System::String](../../../system/string/) | 包含表格的工作表名称。 |
| cellRange | [System::String](../../../system/string/) | 定义表格的单元格范围（例如 "A1:D10"）。 |

### Return Value

已添加到形状集合的表格。

## Remarks

```cpp
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_Slide(0)->get_Shapes(), 10.0f, 10.0f, workbook, worksheetName, cellRange);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::String, System::String, System::String) method

从指定的 [Excel](../../../aspose.slides.excel/) 工作簿文件检索表格，并将其添加到给定形状集合的末尾，位于指定的坐标处。

```cpp
static System::SharedPtr<Aspose::Slides::ITable> Aspose::Slides::Import::ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::String workbookPath, System::String worksheetName, System::String cellRange)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | 将添加表格的形状集合。 |
| x | **float** | 用于定位表格的 X 坐标。 |
| y | **float** | 用于定位表格的 Y 坐标。 |
| workbookPath | [System::String](../../../system/string/) | [Excel](../../../aspose.slides.excel/) 工作簿文件的路径。 |
| worksheetName | [System::String](../../../system/string/) | 包含表格的工作表名称。 |
| cellRange | [System::String](../../../system/string/) | 定义表格的单元格范围（例如 "A1:D10"）。 |

### Return Value

已添加到形状集合的表格。

## Remarks

```cpp
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_Slide(0)->get_Shapes(), 10.0f, 10.0f, workbookPath, worksheetName, cellRange);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::SharedPtr\<System::IO::Stream\>, System::String, System::String) method

从指定的 [Excel](../../../aspose.slides.excel/) 工作簿文件检索表格，并将其添加到给定形状集合的末尾，位于指定的坐标处。

```cpp
static System::SharedPtr<Aspose::Slides::ITable> Aspose::Slides::Import::ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::SharedPtr<System::IO::Stream> workbookStream, System::String worksheetName, System::String cellRange)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | 将添加表格的形状集合。 |
| x | **float** | 用于定位表格的 X 坐标。 |
| y | **float** | 用于定位表格的 Y 坐标。 |
| workbookStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 包含工作簿数据的流。 |
| worksheetName | [System::String](../../../system/string/) | 包含表格的工作表名称。 |
| cellRange | [System::String](../../../system/string/) | 定义表格的单元格范围（例如 "A1:D10"）。 |

### Return Value

已添加到形状集合的表格。

## Remarks

```cpp
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_Slide(0)->get_Shapes(), 10.0f, 10.0f, fStream, worksheetName, cellRange);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ITable](../../../aspose.slides/itable/)
* Class [IShapeCollection](../../../aspose.slides/ishapecollection/)
* Class [IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook/)
* Class [String](../../../system/string/)
* Class [ExcelWorkbookImporter](../)
* Class [Stream](../../../system.io/stream/)
* Namespace [Aspose::Slides::Import](../../)
* Library [Aspose.Slides](../../../)