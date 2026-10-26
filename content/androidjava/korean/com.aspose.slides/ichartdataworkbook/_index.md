---
title: IChartDataWorkbook
second_title: Aspose.Slides for Android via Java API Reference
description: 포함된 Excel 통합 문서에 대한 액세스를 제공합니다
type: docs
url: /ko/com.aspose.slides/ichartdataworkbook/
---```
public interface IChartDataWorkbook
```

포함된 Excel 통합 문서에 대한 액세스를 제공합니다
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [calculateFormulas()](#calculateFormulas--) | 통합 문서의 모든 수식을 계산하고 해당 셀 값을 업데이트합니다. |
| [getCellCollection(String formula, boolean skipHiddenCells)](#getCellCollection-java.lang.String-boolean-) | 셀 집합을 가져옵니다. |
| [getCell(String worksheetName, int row, int column)](#getCell-java.lang.String-int-int-) | 차트 시리즈 또는 카테고리에 사용할 수 있는 셀을 가져옵니다 |
| [getCell(int worksheetIndex, int row, int column)](#getCell-int-int-int-) | 차트 시리즈 또는 카테고리에 사용할 수 있는 셀을 가져옵니다 |
| [getCell(int worksheetIndex, String cellName)](#getCell-int-java.lang.String-) | 차트 시리즈 또는 카테고리에 사용할 수 있는 셀을 가져옵니다 |
| [getCell(int worksheetIndex, String cellName, Object value)](#getCell-int-java.lang.String-java.lang.Object-) | 차트 시리즈 또는 카테고리에 사용할 수 있는 셀을 가져옵니다 |
| [getCell(int worksheetIndex, int row, int column, Object value)](#getCell-int-int-int-java.lang.Object-) | 차트 시리즈 또는 카테고리에 사용할 수 있는 셀을 가져옵니다 |
| [clear(int sheetIndex)](#clear-int-) | 시트의 모든 셀 값을 지웁니다 |
| [getWorksheets()](#getWorksheets--) | 워크시트 컬렉션을 가져옵니다. |
### calculateFormulas() {#calculateFormulas--}
```
public abstract void calculateFormulas()
```


통합 문서의 모든 수식을 계산하고 해당 셀 값을 업데이트합니다.

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

### getCellCollection(String formula, boolean skipHiddenCells) {#getCellCollection-java.lang.String-boolean-}
```
public abstract IChartCellCollection getCellCollection(String formula, boolean skipHiddenCells)
```


셀 집합을 가져옵니다.

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| formula | java.lang.String | “Sheet1!$A$2:$A$5”와 같은 Excel 수식 |
| skipHiddenCells | boolean | true인 경우 숨겨진 셀을 제외한 컬렉션을 반환합니다. |

**반환값:**
[IChartCellCollection](../../com.aspose.slides/ichartcellcollection) - 셀 집합 [IChartCellCollection](../../com.aspose.slides/ichartcellcollection)
### getCell(String worksheetName, int row, int column) {#getCell-java.lang.String-int-int-}
```
public abstract IChartDataCell getCell(String worksheetName, int row, int column)
```


차트 시리즈 또는 카테고리에 사용할 수 있는 셀을 가져옵니다

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| worksheetName | java.lang.String | 워크시트 이름 |
| row | int | 행 번호 |
| column | int | 열 번호 |

**반환값:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - 셀 객체
### getCell(int worksheetIndex, int row, int column) {#getCell-int-int-int-}
```
public abstract IChartDataCell getCell(int worksheetIndex, int row, int column)
```


차트 시리즈 또는 카테고리에 사용할 수 있는 셀을 가져옵니다

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| worksheetIndex | int | 워크시트 인덱스 |
| row | int | 행 번호 |
| column | int | 열 번호 |

**반환값:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - 셀 객체
### getCell(int worksheetIndex, String cellName) {#getCell-int-java.lang.String-}
```
public abstract IChartDataCell getCell(int worksheetIndex, String cellName)
```


차트 시리즈 또는 카테고리에 사용할 수 있는 셀을 가져옵니다

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| worksheetIndex | int | 워크시트 인덱스 |
| cellName | java.lang.String | 셀 이름 |

**반환값:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - 셀 객체
### getCell(int worksheetIndex, String cellName, Object value) {#getCell-int-java.lang.String-java.lang.Object-}
```
public abstract IChartDataCell getCell(int worksheetIndex, String cellName, Object value)
```


차트 시리즈 또는 카테고리에 사용할 수 있는 셀을 가져옵니다

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| worksheetIndex | int | 워크시트 인덱스 |
| cellName | java.lang.String | 셀 이름 |
| value | java.lang.Object | 값 |

**반환값:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - 셀 객체
### getCell(int worksheetIndex, int row, int column, Object value) {#getCell-int-int-int-java.lang.Object-}
```
public abstract IChartDataCell getCell(int worksheetIndex, int row, int column, Object value)
```


차트 시리즈 또는 카테고리에 사용할 수 있는 셀을 가져옵니다

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| worksheetIndex | int | 워크시트 인덱스 |
| row | int | 행 번호 |
| column | int | 열 번호 |
| value | java.lang.Object | 값 |

**반환값:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - 셀 객체
### clear(int sheetIndex) {#clear-int-}
```
public abstract void clear(int sheetIndex)
```


시트의 모든 셀 값을 지웁니다

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| sheetIndex | int | 시트 인덱스 |

### getWorksheets() {#getWorksheets--}
```
public abstract IChartDataWorksheetCollection getWorksheets()
```


워크시트 컬렉션을 가져옵니다.

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