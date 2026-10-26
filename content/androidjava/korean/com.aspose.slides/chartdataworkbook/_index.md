---
title: ChartDataWorkbook
second_title: Aspose.Slides for Android용 Java API 레퍼런스
description: 내장된 Excel 워크북에 대한 액세스를 제공합니다
type: docs
url: /ko/com.aspose.slides/chartdataworkbook/
---
**상속:**
java.lang.Object, com.aspose.slides.DomObject

**구현된 모든 인터페이스:**
[com.aspose.slides.IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)
```
public class ChartDataWorkbook extends DomObject<ChartData> implements IChartDataWorkbook
```

내장된 Excel 워크북에 대한 액세스를 제공합니다
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getWorksheets()](#getWorksheets--) | 워크시트 모음을 가져옵니다. |
| [getCellCollection(String formula, boolean skipHiddenCells)](#getCellCollection-java.lang.String-boolean-) | 셀 집합을 가져옵니다. |
| [getCell(String worksheetName, int row, int column)](#getCell-java.lang.String-int-int-) | 차트 시리즈 또는 카테고리에 사용할 수 있는 셀을 가져옵니다 |
| [getCell(int worksheetIndex, int row, int column)](#getCell-int-int-int-) | 차트 시리즈 또는 카테고리에 사용할 수 있는 셀을 가져옵니다 |
| [getCell(int worksheetIndex, String cellName)](#getCell-int-java.lang.String-) | 차트 시리즈 또는 카테고리에 사용할 수 있는 셀을 가져옵니다 |
| [getCell(int worksheetIndex, String cellName, Object value)](#getCell-int-java.lang.String-java.lang.Object-) | 차트 시리즈 또는 카테고리에 사용할 수 있는 셀을 가져옵니다 |
| [getCell(int worksheetIndex, int row, int column, Object value)](#getCell-int-int-int-java.lang.Object-) | 차트 시리즈 또는 카테고리에 사용할 수 있는 셀을 가져옵니다 |
| [clear(int sheetIndex)](#clear-int-) | 시트의 모든 셀 값을 지웁니다 |
| [calculateFormulas()](#calculateFormulas--) | 워크북의 모든 수식을 계산하고 해당 셀 값을 업데이트합니다. |
### getWorksheets() {#getWorksheets--}
```
public final IChartDataWorksheetCollection getWorksheets()
```


워크시트 모음을 가져옵니다.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.Pie, 50, 50, 400, 500);
>      IChartDataWorkbook workbook =  chart.getChartData().getChartDataWorkbook();
>      for (IChartDataWorksheet worksheet : workbook.getWorksheets())
>      {
>          String worksheetName = worksheet.getName();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**반환값:**
[IChartDataWorksheetCollection](../../com.aspose.slides/ichartdataworksheetcollection)
### getCellCollection(String formula, boolean skipHiddenCells) {#getCellCollection-java.lang.String-boolean-}
```
public final IChartCellCollection getCellCollection(String formula, boolean skipHiddenCells)
```


셀 집합을 가져옵니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| formula | java.lang.String | 예: "Sheet1!$A$2:$A$5"와 같은 Excel 수식. |
| skipHiddenCells | boolean | true이면 메서드는 숨겨진 셀을 제외한 컬렉션을 반환합니다. |

**반환값:**
[IChartCellCollection](../../com.aspose.slides/ichartcellcollection)
### getCell(String worksheetName, int row, int column) {#getCell-java.lang.String-int-int-}
```
public final IChartDataCell getCell(String worksheetName, int row, int column)
```


차트 시리즈 또는 카테고리에 사용할 수 있는 셀을 가져옵니다

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| worksheetName | java.lang.String | 워크시트 이름. |
| row | int | 행. |
| column | int | 열. |

**반환값:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell 객체
### getCell(int worksheetIndex, int row, int column) {#getCell-int-int-int-}
```
public final IChartDataCell getCell(int worksheetIndex, int row, int column)
```


차트 시리즈 또는 카테고리에 사용할 수 있는 셀을 가져옵니다

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| worksheetIndex | int | 워크시트 인덱스. |
| row | int | 행. |
| column | int | 열. |

**반환값:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell 객체
### getCell(int worksheetIndex, String cellName) {#getCell-int-java.lang.String-}
```
public final IChartDataCell getCell(int worksheetIndex, String cellName)
```


차트 시리즈 또는 카테고리에 사용할 수 있는 셀을 가져옵니다

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| worksheetIndex | int | 워크시트 인덱스. |
| cellName | java.lang.String | 셀 이름. |

**반환값:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell 객체
### getCell(int worksheetIndex, String cellName, Object value) {#getCell-int-java.lang.String-java.lang.Object-}
```
public final IChartDataCell getCell(int worksheetIndex, String cellName, Object value)
```


차트 시리즈 또는 카테고리에 사용할 수 있는 셀을 가져옵니다

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| worksheetIndex | int | 워크시트 인덱스. |
| cellName | java.lang.String | 셀 이름. |
| value | java.lang.Object | 값. |

**반환값:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell 객체
### getCell(int worksheetIndex, int row, int column, Object value) {#getCell-int-int-int-java.lang.Object-}
```
public final IChartDataCell getCell(int worksheetIndex, int row, int column, Object value)
```


차트 시리즈 또는 카테고리에 사용할 수 있는 셀을 가져옵니다

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| worksheetIndex | int | 워크시트 인덱스. |
| row | int | 행. |
| column | int | 열. |
| value | java.lang.Object | 값. |

**반환값:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell 객체
### clear(int sheetIndex) {#clear-int-}
```
public final void clear(int sheetIndex)
```


시트의 모든 셀 값을 지웁니다

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| sheetIndex | int | 시트 인덱스 |

### calculateFormulas() {#calculateFormulas--}
```
public final void calculateFormulas()
```


워크북의 모든 수식을 계산하고 해당 셀 값을 업데이트합니다.

--------------------

> ```
> Example shows how to assign a formula to the cell and to calculate a value. The value of the "B4" cell is getting set to 5.
>   
>   Presentation pres = new Presentation();
>   try {
>       IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.Pie, 100, 100, 300, 400);
>       IChartDataWorkbook wb = chart.getChartData().getChartDataWorkbook();
>       wb.getCell(0, "B2", 2);
>       wb.getCell(0, "B3", 3);
>       wb.getCell(0, "B4").setFormula("B2+B3");
>       wb.calculateFormulas();
>       ...
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```