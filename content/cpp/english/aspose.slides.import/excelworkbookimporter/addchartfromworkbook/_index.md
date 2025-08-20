---
title: AddChartFromWorkbook()
second_title: Aspose.Slides for C++ API Reference
description: Retrieves a chart from the specified Excel workbook and adds it to the end of the given shape collection at the specified coordinates.
type: docs
weight: 1
url: /aspose.slides.import/excelworkbookimporter/addchartfromworkbook/
---
## ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::SharedPtr\<Aspose::Slides::Excel::IExcelDataWorkbook\>, System::String, int32_t, bool) method


Retrieves a chart from the specified [Excel](../../../aspose.slides.excel/) workbook and adds it to the end of the given shape collection at the specified coordinates.

```cpp
static System::SharedPtr<Aspose::Slides::Charts::IChart> Aspose::Slides::Import::ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::SharedPtr<Aspose::Slides::Excel::IExcelDataWorkbook> workbook, System::String worksheetName, int32_t chartIndex, bool embedAllWorkbook)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | The shape collection to which the chart will be added. |
| x | **float** | The X coordinate for positioning the chart. |
| y | **float** | The Y coordinate for positioning the chart. |
| workbook | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Excel::IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook/)\> | The [Excel](../../../aspose.slides.excel/) workbook. |
| worksheetName | [System::String](../../../system/string/) | The name of the worksheet that contains the chart. |
| chartIndex | **int32_t** | The zero-based index of the chart shape to insert. This index can be obtained using the [IExcelDataWorkbook::GetChartsFromWorksheet(string)](../) method. |
| embedAllWorkbook | **bool** | If **true**, the entire workbook will be embedded in the chart; if **false**, only the chart data will be embedded. |

### Return Value

The chart that was added to the shape collection.
## Remarks



Example: 
```cpp
System::SharedPtr<IExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_Slide(0)->get_Shapes(), 10.0f, 10.0f, wb, worksheetName, chartName, false);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::SharedPtr\<Aspose::Slides::Excel::IExcelDataWorkbook\>, System::String, System::String, bool) method


Retrieves a chart from the specified [Excel](../../../aspose.slides.excel/) workbook and adds it to the end of the given shape collection at the specified coordinates.

```cpp
static System::SharedPtr<Aspose::Slides::Charts::IChart> Aspose::Slides::Import::ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::SharedPtr<Aspose::Slides::Excel::IExcelDataWorkbook> workbook, System::String worksheetName, System::String chartName, bool embedAllWorkbook)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | The shape collection to which the chart will be added. |
| x | **float** | The X coordinate for positioning the chart. |
| y | **float** | The Y coordinate for positioning the chart. |
| workbook | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Excel::IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook/)\> | The [Excel](../../../aspose.slides.excel/) workbook. |
| worksheetName | [System::String](../../../system/string/) | The name of the worksheet that contains the chart. |
| chartName | [System::String](../../../system/string/) | The name of the chart to be added. |
| embedAllWorkbook | **bool** | If **true**, the entire workbook will be embedded in the chart; if **false**, only the chart data will be embedded. |

### Return Value

The chart that was added to the shape collection.
## Remarks



Example: 
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


Retrieves a chart from the specified [Excel](../../../aspose.slides.excel/) workbook and adds it to the end of the given shape collection at the specified coordinates.

```cpp
static System::SharedPtr<Aspose::Slides::Charts::IChart> Aspose::Slides::Import::ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::SharedPtr<System::IO::Stream> workbookStream, System::String worksheetName, System::String chartName, bool embedAllWorkbook)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | The shape collection to which the chart will be added. |
| x | **float** | The X coordinate for positioning the chart. |
| y | **float** | The Y coordinate for positioning the chart. |
| workbookStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | A stream containing the workbook data. |
| worksheetName | [System::String](../../../system/string/) | The name of the worksheet that contains the chart. |
| chartName | [System::String](../../../system/string/) | The name of the chart to be added. |
| embedAllWorkbook | **bool** | If **true**, the entire workbook will be embedded in the chart; if **false**, only the chart data will be embedded. |

### Return Value

The chart that was added to the shape collection.
## Remarks



Example: 
```cpp
auto fStream = System::MakeObject<System::IO::FileStream>(workbookPath, System::IO::FileMode::Open, System::IO::FileAccess::Read);
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_LayoutSlides()->idx_get(0)->get_Shapes(), 10.0f, 10.0f, fStream, worksheetName, chartName, true);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::String, System::String, System::String, bool) method


Retrieves a chart from the specified [Excel](../../../aspose.slides.excel/) workbook and adds it to the end of the given shape collection at the specified coordinates.

```cpp
static System::SharedPtr<Aspose::Slides::Charts::IChart> Aspose::Slides::Import::ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::String workbookPath, System::String worksheetName, System::String chartName, bool embedWorkbook)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | The shape collection to which the chart will be added. |
| x | **float** | The X coordinate for positioning the chart. |
| y | **float** | The Y coordinate for positioning the chart. |
| workbookPath | [System::String](../../../system/string/) | The file path to the workbook containing the chart. |
| worksheetName | [System::String](../../../system/string/) | The name of the worksheet that contains the chart. |
| chartName | [System::String](../../../system/string/) | The name of the chart to be added. |
| embedWorkbook | **bool** | If **true**, the workbook will be embedded in the chart; if **false**, the chart will link to the external workbook. |

### Return Value

The chart that was added to the shape collection.
## Remarks



Example: 
```cpp
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_Slide(0)->get_Shapes(), 10.0f, 10.0f, workbookPath, worksheetName, chartName, false);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChart](../../../aspose.slides.charts/ichart/)
* Class [IShapeCollection](../../../aspose.slides/ishapecollection/)
* Class [IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook/)
* Class [String](../../../system/string/)
* Class [ExcelWorkbookImporter](../)
* Class [Stream](../../../system.io/stream/)
* Namespace [Aspose::Slides::Import](../../)
* Library [Aspose.Slides](../../../)