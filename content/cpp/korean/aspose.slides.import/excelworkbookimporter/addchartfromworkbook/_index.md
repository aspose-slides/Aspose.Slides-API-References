---
title: AddChartFromWorkbook()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 Excel 워크북에서 차트를 가져와 지정된 좌표에 있는 주어진 shape 컬렉션의 끝에 추가합니다.
type: docs
weight: 1
url: /ko/aspose.slides.import/excelworkbookimporter/addchartfromworkbook/
---
## ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::SharedPtr\<Aspose::Slides::Excel::IExcelDataWorkbook\>, System::String, int32_t, bool) method

지정된 [Excel](../../../aspose.slides.excel/) 워크북에서 차트를 가져와 지정된 좌표에 있는 주어진 shape 컬렉션의 끝에 추가합니다.

```cpp
static System::SharedPtr<Aspose::Slides::Charts::IChart> Aspose::Slides::Import::ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::SharedPtr<Aspose::Slides::Excel::IExcelDataWorkbook> workbook, System::String worksheetName, int32_t chartIndex, bool embedAllWorkbook)
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | 차트가 추가될 shape 컬렉션입니다. |
| x | **float** | 차트를 배치하기 위한 X 좌표입니다. |
| y | **float** | 차트를 배치하기 위한 Y 좌표입니다. |
| workbook | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Excel::IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook/)\> | [Excel](../../../aspose.slides.excel/) 워크북입니다. |
| worksheetName | [System::String](../../../system/string/) | 차트를 포함하고 있는 워크시트 이름입니다. |
| chartIndex | **int32_t** | 삽입할 차트 shape의 0부터 시작하는 인덱스입니다. 이 인덱스는 [IExcelDataWorkbook::GetChartsFromWorksheet(string)](../) 메서드를 사용하여 얻을 수 있습니다. |
| embedAllWorkbook | **bool** | **true**이면 전체 워크북이 차트에 포함되고, **false**이면 차트 데이터만 포함됩니다. |

### 반환값

shape 컬렉션에 추가된 차트입니다.

## 비고



예제:
```cpp
System::SharedPtr<IExcelDataWorkbook> wb = System::MakeObject<ExcelDataWorkbook>(testFile);
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_Slide(0)->get_Shapes(), 10.0f, 10.0f, wb, worksheetName, chartName, false);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::SharedPtr\<Aspose::Slides::Excel::IExcelDataWorkbook\>, System::String, System::String, bool) method

지정된 [Excel](../../../aspose.slides.excel/) 워크북에서 차트를 가져와 지정된 좌표에 있는 주어진 shape 컬렉션의 끝에 추가합니다.

```cpp
static System::SharedPtr<Aspose::Slides::Charts::IChart> Aspose::Slides::Import::ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::SharedPtr<Aspose::Slides::Excel::IExcelDataWorkbook> workbook, System::String worksheetName, System::String chartName, bool embedAllWorkbook)
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | 차트가 추가될 shape 컬렉션입니다. |
| x | **float** | 차트를 배치하기 위한 X 좌표입니다. |
| y | **float** | 차트를 배치하기 위한 Y 좌표입니다. |
| workbook | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Excel::IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook/)\> | [Excel](../../../aspose.slides.excel/) 워크북입니다. |
| worksheetName | [System::String](../../../system/string/) | 차트를 포함하고 있는 워크시트 이름입니다. |
| chartName | [System::String](../../../system/string/) | 추가될 차트의 이름입니다. |
| embedAllWorkbook | **bool** | **true**이면 전체 워크북이 차트에 포함되고, **false**이면 차트 데이터만 포함됩니다. |

### 반환값

shape 컬렉션에 추가된 차트입니다.

## 비고



예제:
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

지정된 [Excel](../../../aspose.slides.excel/) 워크북에서 차트를 가져와 지정된 좌표에 있는 주어진 shape 컬렉션의 끝에 추가합니다.

```cpp
static System::SharedPtr<Aspose::Slides::Charts::IChart> Aspose::Slides::Import::ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::SharedPtr<System::IO::Stream> workbookStream, System::String worksheetName, System::String chartName, bool embedAllWorkbook)
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | 차트가 추가될 shape 컬렉션입니다. |
| x | **float** | 차트를 배치하기 위한 X 좌표입니다. |
| y | **float** | 차트를 배치하기 위한 Y 좌표입니다. |
| workbookStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 워크북 데이터를 포함하는 스트림입니다. |
| worksheetName | [System::String](../../../system/string/) | 차트를 포함하고 있는 워크시트 이름입니다. |
| chartName | [System::String](../../../system/string/) | 추가될 차트의 이름입니다. |
| embedAllWorkbook | **bool** | **true**이면 전체 워크북이 차트에 포함되고, **false**이면 차트 데이터만 포함됩니다. |

### 반환값

shape 컬렉션에 추가된 차트입니다.

## 비고



예제:
```cpp
auto fStream = System::MakeObject<System::IO::FileStream>(workbookPath, System::IO::FileMode::Open, System::IO::FileAccess::Read);
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_LayoutSlide(0)->get_Shapes(), 10.0f, 10.0f, fStream, worksheetName, chartName, true);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::String, System::String, System::String, bool) method

지정된 [Excel](../../../aspose.slides.excel/) 워크북에서 차트를 가져와 지정된 좌표에 있는 주어진 shape 컬렉션의 끝에 추가합니다.

```cpp
static System::SharedPtr<Aspose::Slides::Charts::IChart> Aspose::Slides::Import::ExcelWorkbookImporter::AddChartFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::String workbookPath, System::String worksheetName, System::String chartName, bool embedWorkbook)
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | 차트가 추가될 shape 컬렉션입니다. |
| x | **float** | 차트를 배치하기 위한 X 좌표입니다. |
| y | **float** | 차트를 배치하기 위한 Y 좌표입니다. |
| workbookPath | [System::String](../../../system/string/) | 차트를 포함하는 워크북의 파일 경로입니다. |
| worksheetName | [System::String](../../../system/string/) | 차트를 포함하고 있는 워크시트 이름입니다. |
| chartName | [System::String](../../../system/string/) | 추가될 차트의 이름입니다. |
| embedWorkbook | **bool** | **true**이면 워크북이 차트에 포함되고, **false**이면 차트가 외부 워크북에 링크됩니다. |

### 반환값

shape 컬렉션에 추가된 차트입니다.

## 비고



예제:
```cpp
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_Slide(0)->get_Shapes(), 10.0f, 10.0f, workbookPath, worksheetName, chartName, false);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IChart](../../../aspose.slides.charts/ichart/)
* 클래스 [IShapeCollection](../../../aspose.slides/ishapecollection/)
* 클래스 [IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook/)
* 클래스 [String](../../../system/string/)
* 클래스 [ExcelWorkbookImporter](../)
* 클래스 [Stream](../../../system.io/stream/)
* 네임스페이스 [Aspose::Slides::Import](../../)
* 라이브러리 [Aspose.Slides](../../../)