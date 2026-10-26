---
title: AddTableFromWorkbook()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 Excel 워크북에서 표를 가져와 지정된 좌표에 있는 주어진 shape 컬렉션의 끝에 추가합니다.
type: docs
weight: 14
url: /ko/aspose.slides.import/excelworkbookimporter/addtablefromworkbook/
---
## ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::SharedPtr\<Aspose::Slides::Excel::IExcelDataWorkbook\>, System::String, System::String) method

지정된 [Excel](../../../aspose.slides.excel/) 워크북에서 표를 검색하여 지정된 좌표에 있는 주어진 shape 컬렉션의 끝에 추가합니다.

```cpp
static System::SharedPtr<Aspose::Slides::ITable> Aspose::Slides::Import::ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::SharedPtr<Aspose::Slides::Excel::IExcelDataWorkbook> workbook, System::String worksheetName, System::String cellRange)
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | 표가 추가될 shape 컬렉션입니다. |
| x | **float** | 표를 배치하기 위한 X 좌표입니다. |
| y | **float** | 표를 배치하기 위한 Y 좌표입니다. |
| workbook | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Excel::IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook/)\> | [Excel](../../../aspose.slides.excel/) 워크북. |
| worksheetName | [System::String](../../../system/string/) | 표를 포함하는 워크시트의 이름입니다. |
| cellRange | [System::String](../../../system/string/) | 표를 정의하는 셀 범위입니다(예: "A1:D10"). |

### 반환 값

shape 컬렉션에 추가된 표입니다.

## 비고

```cpp
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_Slide(0)->get_Shapes(), 10.0f, 10.0f, workbook, worksheetName, cellRange);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::String, System::String, System::String) method

지정된 [Excel](../../../aspose.slides.excel/) 워크북 파일에서 표를 검색하여 지정된 좌표에 있는 주어진 shape 컬렉션의 끝에 추가합니다.

```cpp
static System::SharedPtr<Aspose::Slides::ITable> Aspose::Slides::Import::ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::String workbookPath, System::String worksheetName, System::String cellRange)
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | 표가 추가될 shape 컬렉션입니다. |
| x | **float** | 표를 배치하기 위한 X 좌표입니다. |
| y | **float** | 표를 배치하기 위한 Y 좌표입니다. |
| workbookPath | [System::String](../../../system/string/) | [Excel](../../../aspose.slides.excel/) 워크북 파일의 경로입니다. |
| worksheetName | [System::String](../../../system/string/) | 표를 포함하는 워크시트의 이름입니다. |
| cellRange | [System::String](../../../system/string/) | 표를 정의하는 셀 범위입니다(예: "A1:D10"). |

### 반환 값

shape 컬렉션에 추가된 표입니다.

## 비고

```cpp
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_Slide(0)->get_Shapes(), 10.0f, 10.0f, workbookPath, worksheetName, cellRange);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr\<Aspose::Slides::IShapeCollection\>, float, float, System::SharedPtr\<System::IO::Stream\>, System::String, System::String) method

지정된 [Excel](../../../aspose.slides.excel/) 워크북 파일에서 표를 검색하여 지정된 좌표에 있는 주어진 shape 컬렉션의 끝에 추가합니다.

```cpp
static System::SharedPtr<Aspose::Slides::ITable> Aspose::Slides::Import::ExcelWorkbookImporter::AddTableFromWorkbook(System::SharedPtr<Aspose::Slides::IShapeCollection> shapes, float x, float y, System::SharedPtr<System::IO::Stream> workbookStream, System::String worksheetName, System::String cellRange)
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| shapes | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::IShapeCollection](../../../aspose.slides/ishapecollection/)\> | 표가 추가될 shape 컬렉션입니다. |
| x | **float** | 표를 배치하기 위한 X 좌표입니다. |
| y | **float** | 표를 배치하기 위한 Y 좌표입니다. |
| workbookStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | 워크북 데이터를 포함하는 스트림입니다. |
| worksheetName | [System::String](../../../system/string/) | 표를 포함하는 워크시트의 이름입니다. |
| cellRange | [System::String](../../../system/string/) | 표를 정의하는 셀 범위입니다(예: "A1:D10"). |

### 반환 값

shape 컬렉션에 추가된 표입니다.

## 비고

```cpp
auto pres = System::MakeObject<Presentation>();
ExcelWorkbookImporter::AddChartFromWorkbook(pres->get_Slide(0)->get_Shapes(), 10.0f, 10.0f, fStream, worksheetName, cellRange);
pres->Save(u"result.pptx", SaveFormat::Pptx);
```

## 관련 항목

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [ITable](../../../aspose.slides/itable/)
* 클래스 [IShapeCollection](../../../aspose.slides/ishapecollection/)
* 클래스 [IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook/)
* 클래스 [String](../../../system/string/)
* 클래스 [ExcelWorkbookImporter](../)
* 클래스 [Stream](../../../system.io/stream/)
* 네임스페이스 [Aspose::Slides::Import](../../)
* 라이브러리 [Aspose.Slides](../../../)