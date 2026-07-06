---
title: AddChartFromWorkbook
second_title: Aspose.Sildes for .NET API 참조
description: 지정된 Excel 통합 문서에서 차트를 가져와 지정된 좌표에 있는 주어진 shape 컬렉션의 끝에 추가합니다.
type: docs
weight: 10
url: /ko/aspose.slides.import/excelworkbookimporter/addchartfromworkbook/
---
## AddChartFromWorkbook(IShapeCollection, float, float, IExcelDataWorkbook, string, int, bool) {#addchartfromworkbook}

지정된 Excel 통합 문서에서 차트를 가져와 지정된 좌표에 있는 주어진 shape 컬렉션의 끝에 추가합니다.

```csharp
public static IChart AddChartFromWorkbook(IShapeCollection shapes, float x, float y, 
    IExcelDataWorkbook workbook, string worksheetName, int chartIndex, bool embedAllWorkbook)
```

| Parameter | Type | Description |
| --- | --- | --- |
| shapes | IShapeCollection | 차트가 추가될 shape 컬렉션 |
| x | Single | 차트를 배치하기 위한 X 좌표 |
| y | Single | 차트를 배치하기 위한 Y 좌표 |
| workbook | IExcelDataWorkbook | Excel 통합 문서 |
| worksheetName | String | 차트를 포함하고 있는 워크시트의 이름 |
| chartIndex | Int32 | 삽입할 차트 shape의 0 기반 인덱스. 이 인덱스는 [`GetChartsFromWorksheet`](../../../aspose.slides.excel/iexceldataworkbook/getchartsfromworksheet) 메서드를 사용하여 얻을 수 있습니다 |
| embedAllWorkbook | Boolean | `true`이면 전체 통합 문서가 차트에 포함되고, `false`이면 차트 데이터만 포함됩니다 |

### 반환 값

shape 컬렉션에 추가된 차트.

### 예외

| exception | condition |
| --- | --- |
| ArgumentException | 필수 매개 변수가 null이거나 비어 있거나, 통합 문서에서 차트를 찾을 수 없을 때 발생합니다 |

### 예제

Example:

```csharp
[C#]
IExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
using (var pres = new Presentation())
{
    ExcelWorkbookImporter.AddChartFromWorkbook(pres.Slides[0].Shapes, 10, 10, wb, worksheetName, chartName, false);
    pres.Save("result.pptx", SaveFormat.Pptx);
}
```

### 참고

* 인터페이스 [IChart](../../../aspose.slides.charts/ichart)
* 인터페이스 [IShapeCollection](../../../aspose.slides/ishapecollection)
* 인터페이스 [IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook)
* 클래스 [ExcelWorkbookImporter](../../excelworkbookimporter)
* 네임스페이스 [Aspose.Slides.Import](../../excelworkbookimporter)
* 어셈블리 [Aspose.Slides](../../../)

---

## AddChartFromWorkbook(IShapeCollection, float, float, IExcelDataWorkbook, string, string, bool) {#addchartfromworkbook_1}

지정된 Excel 통합 문서에서 차트를 가져와 지정된 좌표에 있는 주어진 shape 컬렉션의 끝에 추가합니다.

```csharp
public static IChart AddChartFromWorkbook(IShapeCollection shapes, float x, float y, 
    IExcelDataWorkbook workbook, string worksheetName, string chartName, bool embedAllWorkbook)
```

| Parameter | Type | Description |
| --- | --- | --- |
| shapes | IShapeCollection | 차트가 추가될 shape 컬렉션 |
| x | Single | 차트를 배치하기 위한 X 좌표 |
| y | Single | 차트를 배치하기 위한 Y 좌표 |
| workbook | IExcelDataWorkbook | Excel 통합 문서 |
| worksheetName | String | 차트를 포함하고 있는 워크시트의 이름 |
| chartName | String | 추가할 차트의 이름 |
| embedAllWorkbook | Boolean | `true`이면 전체 통합 문서가 차트에 포함되고, `false`이면 차트 데이터만 포함됩니다 |

### 반환 값

shape 컬렉션에 추가된 차트.

### 예외

| exception | condition |
| --- | --- |
| ArgumentException | 필수 매개 변수가 null이거나 비어 있거나, 통합 문서에서 차트를 찾을 수 없을 때 발생합니다 |

### 예제

Example:

```csharp
[C#]
IExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
using (var pres = new Presentation())
{
    string worksheetName = "worksheet name";
    var worksheetCharts = wb.GetChartsFromWorksheet(worksheetName);
    foreach (var chart in worksheetCharts)
    {
        ISlide slide = pres.Slides.AddEmptySlide(pres.LayoutSlides[0]);
        ExcelWorkbookImporter.AddChartFromWorkbook(slide.Shapes, 10, 10, wb, worksheetName, chart.Key, false);
    }
    pres.Save("result.pptx", SaveFormat.Pptx);
}
```

### 참고

* 인터페이스 [IChart](../../../aspose.slides.charts/ichart)
* 인터페이스 [IShapeCollection](../../../aspose.slides/ishapecollection)
* 인터페이스 [IExcelDataWorkbook](../../../aspose.slides.excel/iexceldataworkbook)
* 클래스 [ExcelWorkbookImporter](../../excelworkbookimporter)
* 네임스페이스 [Aspose.Slides.Import](../../excelworkbookimporter)
* 어셈블리 [Aspose.Slides](../../../)

---

## AddChartFromWorkbook(IShapeCollection, float, float, Stream, string, string, bool) {#addchartfromworkbook_2}

지정된 Excel 통합 문서에서 차트를 가져와 지정된 좌표에 있는 주어진 shape 컬렉션의 끝에 추가합니다.

```csharp
public static IChart AddChartFromWorkbook(IShapeCollection shapes, float x, float y, 
    Stream workbookStream, string worksheetName, string chartName, bool embedAllWorkbook)
```

| Parameter | Type | Description |
| --- | --- | --- |
| shapes | IShapeCollection | 차트가 추가될 shape 컬렉션 |
| x | Single | 차트를 배치하기 위한 X 좌표 |
| y | Single | 차트를 배치하기 위한 Y 좌표 |
| workbookStream | Stream | 통합 문서 데이터를 포함하는 스트림 |
| worksheetName | String | 차트를 포함하고 있는 워크시트의 이름 |
| chartName | String | 추가할 차트의 이름 |
| embedAllWorkbook | Boolean | `true`이면 전체 통합 문서가 차트에 포함되고, `false`이면 차트 데이터만 포함됩니다 |

### 반환 값

shape 컬렉션에 추가된 차트.

### 예외

| exception | condition |
| --- | --- |
| ArgumentException | 필수 매개 변수가 null이거나 비어 있거나, 통합 문서에서 차트를 찾을 수 없을 때 발생합니다 |
| InvalidOperationException | 입력 데이터가 지원되지 않는 형식일 때 발생합니다 |

### 예제

Example:

```csharp
[C#]
using (var fStream = new FileStream(workbookPath, FileMode.Open, FileAccess.Read))
using (var pres = new Presentation())
{
    ExcelWorkbookImporter.AddChartFromWorkbook(pres.LayoutSlides[0].Shapes, 10, 10, fStream, worksheetName, chartName, true);
    pres.Save("result.pptx", SaveFormat.Pptx);
}
```

### 참고

* 인터페이스 [IChart](../../../aspose.slides.charts/ichart)
* 인터페이스 [IShapeCollection](../../../aspose.slides/ishapecollection)
* 클래스 [ExcelWorkbookImporter](../../excelworkbookimporter)
* 네임스페이스 [Aspose.Slides.Import](../../excelworkbookimporter)
* 어셈블리 [Aspose.Slides](../../../)

---

## AddChartFromWorkbook(IShapeCollection, float, float, string, string, string, bool) {#addchartfromworkbook_3}

지정된 Excel 통합 문서에서 차트를 가져와 지정된 좌표에 있는 주어진 shape 컬렉션의 끝에 추가합니다.

```csharp
public static IChart AddChartFromWorkbook(IShapeCollection shapes, float x, float y, 
    string workbookPath, string worksheetName, string chartName, bool embedWorkbook)
```

| Parameter | Type | Description |
| --- | --- | --- |
| shapes | IShapeCollection | 차트가 추가될 shape 컬렉션 |
| x | Single | 차트를 배치하기 위한 X 좌표 |
| y | Single | 차트를 배치하기 위한 Y 좌표 |
| workbookPath | String | 차트를 포함하고 있는 통합 문서의 파일 경로 |
| worksheetName | String | 차트를 포함하고 있는 워크시트의 이름 |
| chartName | String | 추가할 차트의 이름 |
| embedWorkbook | Boolean | `true`이면 통합 문서가 차트에 포함되고, `false`이면 차트가 외부 통합 문서를 링크합니다 |

### 반환 값

shape 컬렉션에 추가된 차트.

### 예외

| exception | condition |
| --- | --- |
| ArgumentException | 필수 매개 변수가 null이거나 비어 있거나, 통합 문서에서 차트를 찾을 수 없을 때 발생합니다 |
| IOException | 파일에 접근하는 중 I/O 오류가 발생했을 때 발생합니다 |
| InvalidOperationException | 입력 데이터가 지원되지 않는 형식일 때 발생합니다 |

### 예제

Example:

```csharp
[C#]
using (var pres = new Presentation())
{
    ExcelWorkbookImporter.AddChartFromWorkbook(pres.Slides[0].Shapes, 10, 10, workbookPath, worksheetName, chartName, false);
    pres.Save("result.pptx", SaveFormat.Pptx);
}
```

### 참고

* 인터페이스 [IChart](../../../aspose.slides.charts/ichart)
* 인터페이스 [IShapeCollection](../../../aspose.slides/ishapecollection)
* 클래스 [ExcelWorkbookImporter](../../excelworkbookimporter)
* 네임스페이스 [Aspose.Slides.Import](../../excelworkbookimporter)
* 어셈블리 [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->