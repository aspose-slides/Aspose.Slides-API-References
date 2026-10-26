---
title: ExcelWorkbookImporter
second_title: Java API 참조를 통한 Android용 Aspose.Slides
description: Excel 워크북의 콘텐츠를 프레젠테이션으로 가져오는 기능을 제공합니다.
type: docs
url: /ko/com.aspose.slides/excelworkbookimporter/
---
**상속:**
java.lang.Object
```
public class ExcelWorkbookImporter
```

Excel 워크북에서 콘텐츠를 가져와 프레젠테이션에 삽입하는 기능을 제공합니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, int chartIndex, boolean embedAllWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-int-boolean-) | 지정된 Excel 워크북에서 차트를 가져와 지정된 좌표에 있는 주어진 shape 컬렉션의 끝에 추가합니다. |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String chartName, boolean embedAllWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-boolean-) | 지정된 Excel 워크북에서 차트를 가져와 지정된 좌표에 있는 주어진 shape 컬렉션의 끝에 추가합니다. |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String chartName, boolean embedAllWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-boolean-) | 지정된 Excel 워크북에서 차트를 가져와 지정된 좌표에 있는 주어진 shape 컬렉션의 끝에 추가합니다. |
| [addChartFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String chartName, boolean embedWorkbook)](#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-boolean-) | 지정된 Excel 워크북에서 차트를 가져와 지정된 좌표에 있는 주어진 shape 컬렉션의 끝에 추가합니다. |
| [addTableFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String cellRange)](#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-) | 지정된 Excel 워크북에서 테이블을 가져와 지정된 좌표에 있는 주어진 shape 컬렉션의 끝에 추가합니다. |
| [addTableFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String cellRange)](#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-) | 지정된 Excel 워크북 파일에서 테이블을 가져와 지정된 좌표에 있는 주어진 shape 컬렉션의 끝에 추가합니다. |
| [addTableFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String cellRange)](#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-) | 지정된 Excel 워크북 파일에서 테이블을 가져와 지정된 좌표에 있는 주어진 shape 컬렉션의 끝에 추가합니다. |
### addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, int chartIndex, boolean embedAllWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-int-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, int chartIndex, boolean embedAllWorkbook)
```

지정된 Excel 워크북에서 차트를 가져와 지정된 좌표에 있는 주어진 shape 컬렉션의 끝에 추가합니다.

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
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | 차트가 추가될 shape 컬렉션입니다. |
| x | float | 차트를 배치하기 위한 X 좌표입니다. |
| y | float | 차트를 배치하기 위한 Y 좌표입니다. |
| workbook | [IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook) | Excel 워크북입니다. |
| worksheetName | java.lang.String | 차트를 포함하는 워크시트의 이름입니다. |
| chartIndex | int | 삽입할 차트 shape의 0 기반 인덱스입니다. 이 인덱스는 [IExcelDataWorkbook.getChartsFromWorksheet(String)](../../com.aspose.slides/iexceldataworkbook\#getChartsFromWorksheet-String-) 메서드를 사용하여 얻을 수 있습니다. |
| embedAllWorkbook | boolean | true이면 차트에 전체 워크북이 포함되고, false이면 차트 데이터만 포함됩니다. |

**반환값:**
[IChart](../../com.aspose.slides/ichart) - shape 컬렉션에 추가된 차트입니다.
### addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String chartName, boolean embedAllWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String chartName, boolean embedAllWorkbook)
```

지정된 Excel 워크북에서 차트를 가져와 지정된 좌표에 있는 주어진 shape 컬렉션의 끝에 추가합니다.

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
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | 차트가 추가될 shape 컬렉션입니다. |
| x | float | 차트를 배치하기 위한 X 좌표입니다. |
| y | float | 차트를 배치하기 위한 Y 좌표입니다. |
| workbook | [IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook) | Excel 워크북입니다. |
| worksheetName | java.lang.String | 차트를 포함하는 워크시트의 이름입니다. |
| chartName | java.lang.String | 추가될 차트의 이름입니다. |
| embedAllWorkbook | boolean | true이면 차트에 전체 워크북이 포함되고, false이면 차트 데이터만 포함됩니다. |

**반환값:**
[IChart](../../com.aspose.slides/ichart) - shape 컬렉션에 추가된 차트입니다.
### addChartFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String chartName, boolean embedAllWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String chartName, boolean embedAllWorkbook)
```

지정된 Excel 워크북에서 차트를 가져와 지정된 좌표에 있는 주어진 shape 컬렉션의 끝에 추가합니다.

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
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | 차트가 추가될 shape 컬렉션입니다. |
| x | float | 차트를 배치하기 위한 X 좌표입니다. |
| y | float | 차트를 배치하기 위한 Y 좌표입니다. |
| workbookStream | java.io.InputStream | 워크북 데이터를 포함하는 스트림입니다. |
| worksheetName | java.lang.String | 차트를 포함하는 워크시트의 이름입니다. |
| chartName | java.lang.String | 추가될 차트의 이름입니다. |
| embedAllWorkbook | boolean | true이면 차트에 전체 워크북이 포함되고, false이면 차트 데이터만 포함됩니다. |

**반환값:**
[IChart](../../com.aspose.slides/ichart) - shape 컬렉션에 추가된 차트입니다.
### addChartFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String chartName, boolean embedWorkbook) {#addChartFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-boolean-}
```
public static IChart addChartFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String chartName, boolean embedWorkbook)
```

지정된 Excel 워크북에서 차트를 가져와 지정된 좌표에 있는 주어진 shape 컬렉션의 끝에 추가합니다.

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
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | 차트가 추가될 shape 컬렉션입니다. |
| x | float | 차트를 배치하기 위한 X 좌표입니다. |
| y | float | 차트를 배치하기 위한 Y 좌표입니다. |
| workbookPath | java.lang.String | 차트를 포함하는 워크북 파일의 경로입니다. |
| worksheetName | java.lang.String | 차트를 포함하는 워크시트의 이름입니다. |
| chartName | java.lang.String | 추가될 차트의 이름입니다. |
| embedWorkbook | boolean | true이면 차트에 워크북이 포함되고, false이면 차트가 외부 워크북에 연결됩니다. |

**반환값:**
[IChart](../../com.aspose.slides/ichart) - shape 컬렉션에 추가된 차트입니다.
### addTableFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String cellRange) {#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-com.aspose.slides.IExcelDataWorkbook-java.lang.String-java.lang.String-}
```
public static ITable addTableFromWorkbook(IShapeCollection shapes, float x, float y, IExcelDataWorkbook workbook, String worksheetName, String cellRange)
```

지정된 Excel 워크북에서 테이블을 가져와 지정된 좌표에 있는 주어진 shape 컬렉션의 끝에 추가합니다.

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
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | 테이블이 추가될 shape 컬렉션입니다. |
| x | float | 테이블을 배치하기 위한 X 좌표입니다. |
| y | float | 테이블을 배치하기 위한 Y 좌표입니다. |
| workbook | [IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook) | Excel 워크북입니다. |
| worksheetName | java.lang.String | 테이블이 포함된 워크시트의 이름입니다. |
| cellRange | java.lang.String | 테이블을 정의하는 셀 범위입니다 (예: "A1:D10"). |

**반환값:**
[ITable](../../com.aspose.slides/itable) - shape 컬렉션에 추가된 테이블입니다.
### addTableFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String cellRange) {#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.lang.String-java.lang.String-java.lang.String-}
```
public static ITable addTableFromWorkbook(IShapeCollection shapes, float x, float y, String workbookPath, String worksheetName, String cellRange)
```

지정된 Excel 워크북 파일에서 테이블을 가져와 지정된 좌표에 있는 주어진 shape 컬렉션의 끝에 추가합니다.

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
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | 테이블이 추가될 shape 컬렉션입니다. |
| x | float | 테이블을 배치하기 위한 X 좌표입니다. |
| y | float | 테이블을 배치하기 위한 Y 좌표입니다. |
| workbookPath | java.lang.String | Excel 워크북 파일의 경로입니다. |
| worksheetName | java.lang.String | 테이블이 포함된 워크시트의 이름입니다. |
| cellRange | java.lang.String | 테이블을 정의하는 셀 범위입니다 (예: "A1:D10"). |

**반환값:**
[ITable](../../com.aspose.slides/itable) - shape 컬렉션에 추가된 테이블입니다.
### addTableFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String cellRange) {#addTableFromWorkbook-com.aspose.slides.IShapeCollection-float-float-java.io.InputStream-java.lang.String-java.lang.String-}
```
public static ITable addTableFromWorkbook(IShapeCollection shapes, float x, float y, InputStream workbookStream, String worksheetName, String cellRange)
```

지정된 Excel 워크북 파일에서 테이블을 가져와 지정된 좌표에 있는 주어진 shape 컬렉션의 끝에 추가합니다.

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
| shapes | [IShapeCollection](../../com.aspose.slides/ishapecollection) | 테이블이 추가될 shape 컬렉션입니다. |
| x | float | 테이블을 배치하기 위한 X 좌표입니다. |
| y | float | 테이블을 배치하기 위한 Y 좌표입니다. |
| workbookStream | java.io.InputStream | 워크북 데이터를 포함하는 스트림입니다. |
| worksheetName | java.lang.String | 테이블이 포함된 워크시트의 이름입니다. |
| cellRange | java.lang.String | 테이블을 정의하는 셀 범위입니다 (예: "A1:D10"). |

**반환값:**
[ITable](../../com.aspose.slides/itable) - shape 컬렉션에 추가된 테이블입니다.