---
title: AddChartFromWorkbook()
second_title: Aspose.Slides for C++ API 參考文件
description: 從指定的 Excel 活頁簿檢索圖表，並將其新增到給定形狀集合的末端，位於指定的座標。
type: docs
weight: 1
url: /zh-hant/aspose.slides.import/excelworkbookimporter/addchartfromworkbook/
---
## ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::SharedPtr\<Aspose::Slides::Excel::IExcelDataWorkbook\>, System::String, int32_t, bool) 方法


從指定的 [Excel](../../../aspose.slides.excel/) 活頁簿檢索圖表，並將其新增到給定形狀集合的末端，位於指定的座標。

```cpp
static System::SharedPtr<Aspose::Slides::Charts::IChart> Aspose::Slides::Import::ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::SharedPtr<Aspose::Slides::Excel::IExcelDataWorkbook> workbook, System::String worksheetName, int32_t chartIndex, bool embedAllWorkbook)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | 將要加入圖表的形狀集合。 |
| x | **float** | 用於定位圖表的 X 座標。 |
| y | **float** | 用於定位圖表的 Y 座標。 |
| workbook | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Excel::IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook/)\> | [Excel](../../../aspose.slides.excel/) 活頁簿。 |
| worksheetName | [System::String](../../../system/string/) | 包含圖表之工作表的名稱。 |
| chartIndex | **int32_t** | 要插入的圖表形狀的零基索引。此索引可透過 [IExcelDataWorkbook::GetChartsFromWorksheet(string)](../) 方法取得。 |
| embedAllWorkbook | **bool** | 若 **true**，整個活頁簿將嵌入圖表；若 **false**，僅嵌入圖表資料。 |

### Return Value

已加入形狀集合的圖表。

## 備註



範例： 
```cpp
System::SharedPtr<IExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_Slide(0)->get_Shapes(), 10.0f, 10.0f, wb, worksheetName, chartName, false);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::SharedPtr\<Aspose::Slides::Excel::IExcelDataWorkbook\>, System::String, System::String, bool) 方法


從指定的 [Excel](../../../aspose.slides.excel/) 活頁簿檢索圖表，並將其新增到給定形狀集合的末端，位於指定的座標。

```cpp
static System::SharedPtr<Aspose::Slides::Charts::IChart> Aspose::Slides::Import::ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::SharedPtr<Aspose::Slides::Excel::IExcelDataWorkbook> workbook, System::String worksheetName, System::String chartName, bool embedAllWorkbook)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | 將要加入圖表的形狀集合。 |
| x | **float** | 用於定位圖表的 X 座標。 |
| y | **float** | 用於定位圖表的 Y 座標。 |
| workbook | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Excel::IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook/)\> | [Excel](../../../aspose.slides.excel/) 活頁簿。 |
| worksheetName | [System::String](../../../system/string/) | 包含圖表之工作表的名稱。 |
| chartName | [System::String](../../../system/string/) | 要加入的圖表名稱。 |
| embedAllWorkbook | **bool** | 若 **true**，整個活頁簿將嵌入圖表；若 **false**，僅嵌入圖表資料。 |

### Return Value

已加入形狀集合的圖表。

## 備註



範例： 
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

## ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::SharedPtr\<System::IO::Stream\>, System::String, System::String, bool) 方法


從指定的 [Excel](../../../aspose.slides.excel/) 活頁簿檢索圖表，並將其新增到給定形狀集合的末端，位於指定的座標。

```cpp
static System::SharedPtr<Aspose::Slides::Charts::IChart> Aspose::Slides::Import::ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::SharedPtr<System::IO::Stream> workbookStream, System::String worksheetName, System::String chartName, bool embedAllWorkbook)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | 將要加入圖表的形狀集合。 |
| x | **float** | 用於定位圖表的 X 座標。 |
| y | **float** | 用於定位圖表的 Y 座標。 |
| workbookStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 包含活頁簿資料的串流。 |
| worksheetName | [System::String](../../../system/string/) | 包含圖表之工作表的名稱。 |
| chartName | [System::String](../../../system/string/) | 要加入的圖表名稱。 |
| embedAllWorkbook | **bool** | 若 **true**，整個活頁簿將嵌入圖表；若 **false**，僅嵌入圖表資料。 |

### Return Value

已加入形狀集合的圖表。

## 備註



範例： 
```cpp
auto fStream = System::MakeObject<System::IO::FileStream>(workbookPath, System::IO::FileMode::Open, System::IO::FileAccess::Read);
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_LayoutSlide(0)->get_Shapes(), 10.0f, 10.0f, fStream, worksheetName, chartName, true);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::String, System::String, System::String, bool) 方法


從指定的 [Excel](../../../aspose.slides.excel/) 活頁簿檢索圖表，並將其新增到給定形狀集合的末端，位於指定的座標。

```cpp
static System::SharedPtr<Aspose::Slides::Charts::IChart> Aspose::Slides::Import::ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::String workbookPath, System::String worksheetName, System::String chartName, bool embedWorkbook)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | 將要加入圖表的形狀集合。 |
| x | **float** | 用於定位圖表的 X 座標。 |
| y | **float** | 用於定位圖表的 Y 座標。 |
| workbookPath | [System::String](../../../system/string/) | 包含圖表之活頁簿的檔案路徑。 |
| worksheetName | [System::String](../../../system/string/) | 包含圖表之工作表的名稱。 |
| chartName | [System::String](../../../system/string/) | 要加入的圖表名稱。 |
| embedWorkbook | **bool** | 若 **true**，活頁簿將嵌入圖表；若 **false**，圖表將連結至外部活頁簿。 |

### Return Value

已加入形狀集合的圖表。

## 備註



範例： 
```cpp
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_Slide(0)->get_Shapes(), 10.0f, 10.0f, workbookPath, worksheetName, chartName, false);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## 另請參閱

* 類型定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IChart](../../../aspose.slides.charts/ichart/)
* 類別 [IShapeCollection](../../../aspose.slides/ishapecollection/)
* 類別 [IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook/)
* 類別 [String](../../../system/string/)
* 類別 [ExcelWorkbookImporter](../)
* 類別 [Stream](../../../system.io/stream/)
* 命名空間 [Aspose::Slides::Import](../../)
* 庫 [Aspose.Slides](../../../)