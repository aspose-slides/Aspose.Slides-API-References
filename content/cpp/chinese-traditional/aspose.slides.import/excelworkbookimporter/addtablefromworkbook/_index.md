---
title: AddTableFromWorkbook()
second_title: Aspose.Slides for C++ API 參考文件
description: 從指定的 Excel 活頁簿中擷取表格，並在指定的座標將其新增至給定形狀集合的末端。
type: docs
weight: 14
url: /zh-hant/aspose.slides.import/excelworkbookimporter/addtablefromworkbook/
---
## ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::SharedPtr\<Aspose::Slides::Excel::IExcelDataWorkbook\>, System::String, System::String) 方法

從指定的 [Excel](../../../aspose.slides.excel/) 活頁簿中擷取表格，並在指定的座標將其新增至給定形狀集合的末端。

```cpp
static System::SharedPtr<Aspose::Slides::ITable> Aspose::Slides::Import::ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::SharedPtr<Aspose::Slides::Excel::IExcelDataWorkbook> workbook, System::String worksheetName, System::String cellRange)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | 將加入表格的形狀集合。 |
| x | **float** | 定位表格的 X 座標。 |
| y | **float** | 定位表格的 Y 座標。 |
| workbook | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Excel::IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook/)\> | [Excel](../../../aspose.slides.excel/) 活頁簿。 |
| worksheetName | [System::String](../../../system/string/) | 包含該表格的工作表名稱。 |
| cellRange | [System::String](../../../system/string/) | 定義表格的儲存格範圍（例如 "A1:D10"）。 |

### 傳回值

已加入形狀集合的表格。

## 備註

```cpp
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_Slide(0)->get_Shapes(), 10.0f, 10.0f, workbook, worksheetName, cellRange);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::String, System::String, System::String) 方法

從指定的 [Excel](../../../aspose.slides.excel/) 活頁簿檔案中擷取表格，並在指定的座標將其新增至給定形狀集合的末端。

```cpp
static System::SharedPtr<Aspose::Slides::ITable> Aspose::Slides::Import::ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::String workbookPath, System::String worksheetName, System::String cellRange)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | 將加入表格的形狀集合。 |
| x | **float** | 定位表格的 X 座標。 |
| y | **float** | 定位表格的 Y 座標。 |
| workbookPath | [System::String](../../../system/string/) | 指向 [Excel](../../../aspose.slides.excel/) 活頁簿檔案的路徑。 |
| worksheetName | [System::String](../../../system/string/) | 包含該表格的工作表名稱。 |
| cellRange | [System::String](../../../system/string/) | 定義表格的儲存格範圍（例如 "A1:D10"）。 |

### 傳回值

已加入形狀集合的表格。

## 備註

```cpp
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_Slide(0)->get_Shapes(), 10.0f, 10.0f, workbookPath, worksheetName, cellRange);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::SharedPtr\<System::IO::Stream\>, System::String, System::String) 方法

從指定的 [Excel](../../../aspose.slides.excel/) 活頁簿檔案中擷取表格，並在指定的座標將其新增至給定形狀集合的末端。

```cpp
static System::SharedPtr<Aspose::Slides::ITable> Aspose::Slides::Import::ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::SharedPtr<System::IO::Stream> workbookStream, System::String worksheetName, System::String cellRange)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | 將加入表格的形狀集合。 |
| x | **float** | 定位表格的 X 座標。 |
| y | **float** | 定位表格的 Y 座標。 |
| workbookStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 包含活頁簿資料的串流。 |
| worksheetName | [System::String](../../../system/string/) | 包含該表格的工作表名稱。 |
| cellRange | [System::String](../../../system/string/) | 定義表格的儲存格範圍（例如 "A1:D10"）。 |

### 傳回值

已加入形狀集合的表格。

## 備註

```cpp
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_Slide(0)->get_Shapes(), 10.0f, 10.0f, fStream, worksheetName, cellRange);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## 另見

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [ITable](../../../aspose.slides/itable/)
* 類別 [IShapeCollection](../../../aspose.slides/ishapecollection/)
* 類別 [IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook/)
* 類別 [String](../../../system/string/)
* 類別 [ExcelWorkbookImporter](../)
* 類別 [Stream](../../../system.io/stream/)
* 命名空間 [Aspose::Slides::Import](../../)
* 函式庫 [Aspose.Slides](../../../)