---
title: IExcelDataWorkbook
second_title: Aspose.Slides for Java API Reference
description: 일반 용도로 Excel 데이터에 접근할 수 있는 워크북을 나타냅니다.
type: docs
url: /ko/com.aspose.slides/iexceldataworkbook/
---```
public interface IExcelDataWorkbook
```

일반 용도로 Excel 데이터에 접근할 수 있는 워크북을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getCells(String formula, boolean skipHiddenCells)](#getCells-java.lang.String-boolean-) | 지정된 수식과 일치하는 셀 컬렉션을 워크북에서 가져옵니다. |
| [getCell(int worksheetIndex, int row, int column)](#getCell-int-int-int-) | 지정된 워크시트를 인덱스와 셀 좌표를 사용하여 셀을 가져옵니다. |
| [getCell(String worksheetName, int row, int column)](#getCell-java.lang.String-int-int-) | 지정된 워크시트를 이름과 셀 좌표를 사용하여 셀을 가져옵니다. |
| [getCell(int worksheetIndex, String cellName)](#getCell-int-java.lang.String-) | 지정된 워크시트를 인덱스와 Excel 스타일 셀 이름(예: "B2")을 사용하여 셀을 가져옵니다. |
| [getCell(String worksheetName, String cellName)](#getCell-java.lang.String-java.lang.String-) | 지정된 워크시트를 Excel 스타일 셀 이름(예: "B2")을 사용하여 셀을 가져옵니다. |
| [getChartsFromWorksheet(String worksheetName)](#getChartsFromWorksheet-java.lang.String-) | Excel 워크북의 지정된 워크시트에 있는 모든 차트의 인덱스와 이름을 포함하는 사전을 가져옵니다. |
| [getWorksheetNames()](#getWorksheetNames--) | Excel 워크북에 포함된 모든 워크시트의 이름을 가져옵니다. |
### getCells(String formula, boolean skipHiddenCells) {#getCells-java.lang.String-boolean-}
```
public abstract System.Collections.Generic.List<IExcelDataCell> getCells(String formula, boolean skipHiddenCells)
```


지정된 수식과 일치하는 셀 컬렉션을 워크북에서 가져옵니다.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  List<IExcelDataCell> cells = wb.getCells("Sheet1!A2:A6", false);
>  System.out.println(cells.size()); //출력: 5
```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| formula | java.lang.String | 대상 셀을 식별하기 위해 사용되는 수식 또는 범위 표현식(예: "Sheet1!A1:B3"). |
| skipHiddenCells | boolean | true인 경우, 숨겨진 셀(숨겨진 행이나 열에 있는 셀)은 결과에서 제외됩니다. |

**반환 값:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.slides.IExcelDataCell> - 지정된 수식과 일치하는 읽기 전용 셀 목록입니다.
### getCell(int worksheetIndex, int row, int column) {#getCell-int-int-int-}
```
public abstract IExcelDataCell getCell(int worksheetIndex, int row, int column)
```


지정된 워크시트를 인덱스와 셀 좌표를 사용하여 셀을 가져옵니다.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getValue().toString());
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| worksheetIndex | int | 워크시트의 0부터 시작하는 인덱스입니다. |
| row | int | 셀의 0부터 시작하는 행 인덱스입니다. |
| column | int | 셀의 0부터 시작하는 열 인덱스입니다. |

**반환 값:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - 지정된 위치에 있는 셀입니다.
### getCell(String worksheetName, int row, int column) {#getCell-java.lang.String-int-int-}
```
public abstract IExcelDataCell getCell(String worksheetName, int row, int column)
```


지정된 워크시트를 이름과 셀 좌표를 사용하여 셀을 가져옵니다.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell("Sheet1", 1, 1);
>  System.out.println(cell.getValue().toString());
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| worksheetName | java.lang.String | 워크시트의 이름입니다. |
| row | int | 셀의 0부터 시작하는 행 인덱스입니다. |
| column | int | 셀의 0부터 시작하는 열 인덱스입니다. |

**반환 값:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - 지정된 위치에 있는 셀입니다.
### getCell(int worksheetIndex, String cellName) {#getCell-int-java.lang.String-}
```
public abstract IExcelDataCell getCell(int worksheetIndex, String cellName)
```


지정된 워크시트를 인덱스와 Excel 스타일 셀 이름(예: "B2")을 사용하여 셀을 가져옵니다.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, "B2");
>  System.out.println(cell.getValue().toString());
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| worksheetIndex | int | 워크시트의 0부터 시작하는 인덱스입니다. |
| cellName | java.lang.String | Excel 스타일 셀 참조(예: "A1", "C5")입니다. |

**반환 값:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - 지정된 위치에 있는 셀입니다.
### getCell(String worksheetName, String cellName) {#getCell-java.lang.String-java.lang.String-}
```
public abstract IExcelDataCell getCell(String worksheetName, String cellName)
```


지정된 워크시트를 Excel 스타일 셀 이름(예: "B2")을 사용하여 셀을 가져옵니다.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell("Sheet1", "B2");
>  System.out.println(cell.getValue().toString());
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| worksheetName | java.lang.String | 워크시트의 이름입니다. |
| cellName | java.lang.String | Excel 스타일 셀 참조(예: "A1", "C5")입니다. |

**반환 값:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - 지정된 위치에 있는 셀입니다.
### getChartsFromWorksheet(String worksheetName) {#getChartsFromWorksheet-java.lang.String-}
```
public abstract System.Collections.Generic.Dictionary<Integer,String> getChartsFromWorksheet(String worksheetName)
```


Excel 워크북의 지정된 워크시트에 있는 모든 차트의 인덱스와 이름을 포함하는 사전을 가져옵니다.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  Dictionary.Enumerator<Integer, String> sheetCharts = wb.getChartsFromWorksheet("worksheetName").iterator();
>  while (sheetCharts.hasNext())
>  {
>      KeyValuePair<Integer, String> chart = sheetCharts.next();
>      System.out.println(chart.getKey() + " : " + chart.getValue());
>  }
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| worksheetName | java.lang.String | 차트를 검색할 워크시트의 이름입니다. |

**반환 값:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.Integer,java.lang.String> - 키가 차트 인덱스이고 값이 차트 이름인 사전입니다.
### getWorksheetNames() {#getWorksheetNames--}
```
public abstract System.Collections.Generic.List<String> getWorksheetNames()
```


Excel 워크북에 포함된 모든 워크시트의 이름을 가져옵니다.

--------------------

> ```
> Example:
>  
>  IExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  List<String> sheetNames = wb.getWorksheetNames();
>  for (String name : sheetNames)
>      System.out.println(name);
> ```

**반환 값:**
com.aspose.ms.System.Collections.Generic.List<java.lang.String> - 워크시트 이름 목록입니다.