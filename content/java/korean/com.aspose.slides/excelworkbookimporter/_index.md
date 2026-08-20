---
title: ExcelWorkbookImporter
second_title: Aspose.Slides for Java API 레퍼런스
description: Excel 워크북에서 프레젠테이션으로 콘텐츠를 가져오는 기능을 제공합니다.
type: docs
url: /ko/com.aspose.slides/excelworkbookimporter/
---
**Inheritance:**
java.lang.Object
```
public class ExcelWorkbookImporter
```

Excel 워크북에서 프레젠테이션으로 내용을 가져오는 기능을 제공합니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, int chartIndex, boolean embedAllWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-int-boolean-) | 지정된 Excel 워크북에서 차트를 가져와 지정된 좌표에 있는 주어진 shape collection의 끝에 추가합니다. |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String chartName, boolean embedAllWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-boolean-) | 지정된 Excel 워크북에서 차트를 가져와 지정된 좌표에 있는 주어진 shape collection의 끝에 추가합니다. |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String chartName, boolean embedAllWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-boolean-) | 지정된 Excel 워크북에서 차트를 가져와 지정된 좌표에 있는 주어진 shape collection의 끝에 추가합니다. |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String chartName, boolean embedWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-boolean-) | 지정된 Excel 워크북에서 차트를 가져와 지정된 좌표에 있는 주어진 shape collection의 끝에 추가합니다. |
| [addTableFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String cellRange)](#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-) | 지정된 Excel 워크북에서 표를 가져와 지정된 좌표에 있는 주어진 shape collection의 끝에 추가합니다. |
| [addTableFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String cellRange)](#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-) | 지정된 Excel 워크북 파일에서 표를 가져와 지정된 좌표에 있는 주어진 shape collection의 끝에 추가합니다. |
| [addTableFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String cellRange)](#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-) | 지정된 Excel 워크북 파일에서 표를 가져와 지정된 좌표에 있는 주어진 shape collection의 끝에 추가합니다. |
### addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, int chartIndex, boolean embedAllWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-int-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, int chartIndex, boolean embedAllWorkbook)
```

지정된 Excel 워크북에서 차트를 가져와 지정된 좌표에 있는 주어진 shape collection의 끝에 추가합니다.

--------------------

> ```
> Example:
>  
>  IExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  Presentation pres = new Presentation();
>  try {
>      ExcelWorkbookImporter.addChartFromWorkbook(pres.getSlides().get_Item(0).getShapes(), 10, 10, wb, worksheetName, chartName, false);
>      pres.save("result.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | 차트가 추가될 shape collection |
| x | float | 차트를 배치하기 위한 X 좌표 |
| y | float | 차트를 배치하기 위한 Y 좌표 |
| workbook | [IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook) | Excel 워크북 |
| worksheetName | java.lang.String | 차트를 포함하고 있는 워크시트 이름 |
| chartIndex | int | 삽입할 차트 shape의 0부터 시작하는 인덱스. 이 인덱스는 [IExcelDataWorkbook.getChartsFromWorksheet(String)](../../com.aspose.slides/iexceldataworkbook\#getChartsFromWorksheet-String-) 메서드를 사용해 얻을 수 있습니다. |
| embedAllWorkbook | boolean | true인 경우 전체 워크북이 차트에 포함되고, false인 경우 차트 데이터만 포함됩니다. |

**반환값:**
[IChart](../../com.aspose.slides/ichart) - shape collection에 추가된 차트
### addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String chartName, boolean embedAllWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String chartName, boolean embedAllWorkbook)
```

지정된 Excel 워크북에서 차트를 가져와 지정된 좌표에 있는 주어진 shape collection의 끝에 추가합니다.

--------------------

> ```
> Example:
>  
>  IExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  Presentation pres = new Presentation();
>  try {
>      String worksheetName = "worksheet name";
>      Dictionary.Enumerator<Integer, String> worksheetCharts = wb.getChartsFromWorksheet(worksheetName).iterator();
>      while (worksheetCharts.hasNext())
>      {
>          KeyValuePair<Integer, String> chart = worksheetCharts.next();
>          ISlide slide = pres.getSlides().addEmptySlide(pres.getLayoutSlides().get_Item(0));
>          ExcelWorkbookImporter.addChartFromWorkbook(slide.getShapes(), 10, 10, wb, worksheetName, chart.getKey(), false);
>      }
>      pres.save("result.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | 차트가 추가될 shape collection |
| x | float | 차트를 배치하기 위한 X 좌표 |
| y | float | 차트를 배치하기 위한 Y 좌표 |
| workbook | [IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook) | Excel 워크북 |
| worksheetName | java.lang.String | 차트를 포함하고 있는 워크시트 이름 |
| chartName | java.lang.String | 추가될 차트 이름 |
| embedAllWorkbook | boolean | true인 경우 전체 워크북이 차트에 포함되고, false인 경우 차트 데이터만 포함됩니다. |

**반환값:**
[IChart](../../com.aspose.slides/ichart) - shape collection에 추가된 차트
### addChartFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String chartName, boolean embedAllWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String chartName, boolean embedAllWorkbook)
```

지정된 Excel 워크북에서 차트를 가져와 지정된 좌표에 있는 주어진 shape collection의 끝에 추가합니다.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream fStream = new FileInputStream(workbookPath);
>      ExcelWorkbookImporter.addChartFromWorkbook(pres.getLayoutSlides().get_Item(0).getShapes(), 10, 10, fStream, worksheetName, chartName, true);
>      fStream.close();
>      pres.save("result.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | 차트가 추가될 shape collection |
| x | float | 차트를 배치하기 위한 X 좌표 |
| y | float | 차트를 배치하기 위한 Y 좌표 |
| workbookStream | java.io.InputStream | 워크북 데이터를 포함하는 스트림 |
| worksheetName | java.lang.String | 차트를 포함하고 있는 워크시트 이름 |
| chartName | java.lang.String | 추가될 차트 이름 |
| embedAllWorkbook | boolean | true인 경우 전체 워크북이 차트에 포함되고, false인 경우 차트 데이터만 포함됩니다. |

**반환값:**
[IChart](../../com.aspose.slides/ichart) - shape collection에 추가된 차트
### addChartFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String chartName, boolean embedWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String chartName, boolean embedWorkbook)
```

지정된 Excel 워크북에서 차트를 가져와 지정된 좌표에 있는 주어진 shape collection의 끝에 추가합니다.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ExcelWorkbookImporter.addChartFromWorkbook(pres.getSlides().get_Item(0).getShapes(), 10, 10, workbookPath, worksheetName, chartName, false);
>      pres.save("result.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | 차트가 추가될 shape collection |
| x | float | 차트를 배치하기 위한 X 좌표 |
| y | float | 차트를 배치하기 위한 Y 좌표 |
| workbookPath | java.lang.String | 차트를 포함하고 있는 워크북 파일 경로 |
| worksheetName | java.lang.String | 차트를 포함하고 있는 워크시트 이름 |
| chartName | java.lang.String | 추가될 차트 이름 |
| embedWorkbook | boolean | true인 경우 워크북이 차트에 포함되고, false인 경우 차트가 외부 워크북에 링크됩니다. |

**반환값:**
[IChart](../../com.aspose.slides/ichart) - shape collection에 추가된 차트
### addTableFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String cellRange) {#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-}
```
public static ITable addTableFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String cellRange)
```

지정된 Excel 워크북에서 표를 가져와 지정된 좌표에 있는 주어진 shape collection의 끝에 추가합니다.

--------------------

> ```
> IExcelDataWorkbook workbook = new ExcelDataWorkbook(testFile);
>  Presentation pres = new Presentation();
>  try {
>      ExcelWorkbookImporter.addTableFromWorkbook(pres.getSlides().get_Item(0).getShapes(), 10, 10, workbook, worksheetName, "A1:D10");
>      pres.save("result.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | 표가 추가될 shape collection |
| x | float | 표를 배치하기 위한 X 좌표 |
| y | float | 표를 배치하기 위한 Y 좌표 |
| workbook | [IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook) | Excel 워크북 |
| worksheetName | java.lang.String | 표를 포함하고 있는 워크시트 이름 |
| cellRange | java.lang.String | 표를 정의하는 셀 범위(예: "A1:D10") |

**반환값:**
[ITable](../../com.aspose.slides/itable) - shape collection에 추가된 표
### addTableFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String cellRange) {#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-}
```
public static ITable addTableFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String cellRange)
```

지정된 Excel 워크북 파일에서 표를 가져와 지정된 좌표에 있는 주어진 shape collection의 끝에 추가합니다.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      ExcelWorkbookImporter.addTableFromWorkbook(pres.getSlides().get_Item(0).getShapes(), 10, 10, workbookPath, worksheetName, "A1:D10");
>      pres.save("result.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | 표가 추가될 shape collection |
| x | float | 표를 배치하기 위한 X 좌표 |
| y | float | 표를 배치하기 위한 Y 좌표 |
| workbookPath | java.lang.String | Excel 워크북 파일 경로 |
| worksheetName | java.lang.String | 표를 포함하고 있는 워크시트 이름 |
| cellRange | java.lang.String | 표를 정의하는 셀 범위(예: "A1:D10") |

**반환값:**
[ITable](../../com.aspose.slides/itable) - shape collection에 추가된 표
### addTableFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String cellRange) {#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-}
```
public static ITable addTableFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String cellRange)
```

지정된 Excel 워크북 파일에서 표를 가져와 지정된 좌표에 있는 주어진 shape collection의 끝에 추가합니다.

--------------------

> ```
> FileInputStream fStream = new FileInputStream(workbookPath);
>  Presentation pres = new Presentation();
>  try {
>      ExcelWorkbookImporter.addTableFromWorkbook(pres.getSlides().get_Item(0).getShapes(), 10, 10, fStream, worksheetName, "A1:D10");
>      pres.save("result.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | 표가 추가될 shape collection |
| x | float | 표를 배치하기 위한 X 좌표 |
| y | float | 표를 배치하기 위한 Y 좌표 |
| workbookStream | java.io.InputStream | 워크북 데이터를 포함하는 스트림 |
| worksheetName | java.lang.String | 표를 포함하고 있는 워크시트 이름 |
| cellRange | java.lang.String | 표를 정의하는 셀 범위(예: "A1:D10") |

**반환값:**
[ITable](../../com.aspose.slides/itable) - shape collection에 추가된 표