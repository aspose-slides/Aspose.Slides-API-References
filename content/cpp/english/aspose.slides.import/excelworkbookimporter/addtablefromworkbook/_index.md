---
title: AddTableFromWorkbook()
second_title: Aspose.Slides for C++ API Reference
description: Retrieves a table from the specified Excel workbook and adds it to the end of the given shape collection at the specified coordinates.
type: docs
weight: 14
url: /aspose.slides.import/excelworkbookimporter/addtablefromworkbook/
---
## ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::SharedPtr\<Aspose::Slides::Excel::IExcelDataWorkbook\>, System::String, System::String) method


Retrieves a table from the specified [Excel](../../../aspose.slides.excel/) workbook and adds it to the end of the given shape collection at the specified coordinates.

```cpp
static System::SharedPtr<Aspose::Slides::ITable> Aspose::Slides::Import::ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::SharedPtr<Aspose::Slides::Excel::IExcelDataWorkbook> workbook, System::String worksheetName, System::String cellRange)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | The shape collection to which the table will be added. |
| x | **float** | The X coordinate for positioning the table. |
| y | **float** | The Y coordinate for positioning the table. |
| workbook | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Excel::IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook/)\> | The [Excel](../../../aspose.slides.excel/) workbook. |
| worksheetName | [System::String](../../../system/string/) | The name of the worksheet that contains the table. |
| cellRange | [System::String](../../../system/string/) | The cell range that defines the table (for example, \"A1:D10\"). |

### Return Value

The table that was added to the shape collection.
## Remarks




```cpp
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_Slide(0)->get_Shapes(), 10.0f, 10.0f, workbook, worksheetName, cellRange);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::String, System::String, System::String) method


Retrieves a table from the specified [Excel](../../../aspose.slides.excel/) workbook file and adds it to the end of the given shape collection at the specified coordinates.

```cpp
static System::SharedPtr<Aspose::Slides::ITable> Aspose::Slides::Import::ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::String workbookPath, System::String worksheetName, System::String cellRange)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | The shape collection to which the table will be added. |
| x | **float** | The X coordinate for positioning the table. |
| y | **float** | The Y coordinate for positioning the table. |
| workbookPath | [System::String](../../../system/string/) | The path to the [Excel](../../../aspose.slides.excel/) workbook file. |
| worksheetName | [System::String](../../../system/string/) | The name of the worksheet that contains the table. |
| cellRange | [System::String](../../../system/string/) | The cell range that defines the table (for example, \"A1:D10\"). |

### Return Value

The table that was added to the shape collection.
## Remarks




```cpp
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_Slide(0)->get_Shapes(), 10.0f, 10.0f, workbookPath, worksheetName, cellRange);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::SharedPtr\<System::IO::Stream\>, System::String, System::String) method


Retrieves a table from the specified [Excel](../../../aspose.slides.excel/) workbook file and adds it to the end of the given shape collection at the specified coordinates.

```cpp
static System::SharedPtr<Aspose::Slides::ITable> Aspose::Slides::Import::ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::SharedPtr<System::IO::Stream> workbookStream, System::String worksheetName, System::String cellRange)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | The shape collection to which the table will be added. |
| x | **float** | The X coordinate for positioning the table. |
| y | **float** | The Y coordinate for positioning the table. |
| workbookStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | A stream containing the workbook data. |
| worksheetName | [System::String](../../../system/string/) | The name of the worksheet that contains the table. |
| cellRange | [System::String](../../../system/string/) | The cell range that defines the table (for example, \"A1:D10\"). |

### Return Value

The table that was added to the shape collection.
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