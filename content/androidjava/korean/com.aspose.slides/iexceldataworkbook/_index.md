---
title: IExcelDataWorkbook
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a workbook that provides access to Excel data for general use.
type: docs
url: /ko/com.aspose.slides/iexceldataworkbook/
---```
public interface IExcelDataWorkbook
```

일반적인 사용을 위해 Excel 데이터를 액세스할 수 있는 워크북을 나타냅니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getCells(String formula, boolean skipHiddenCells)](#getCells-java.lang.String-boolean-) | Retrieves a collection of cells from the workbook that match the specified formula. |
| [getCell(int worksheetIndex, int row, int column)](#getCell-int-int-int-) | Retrieves a cell from the specified worksheet using its index and cell coordinates. |
| [getCell(String worksheetName, int row, int column)](#getCell-java.lang.String-int-int-) | Retrieves a cell from the specified worksheet using its name and cell coordinates. |
| [getCell(int worksheetIndex, String cellName)](#getCell-int-java.lang.String-) | Retrieves a cell from the specified worksheet using its index and Excel-style cell name (e.g., "B2"). |
| [getCell(String worksheetName, String cellName)](#getCell-java.lang.String-java.lang.String-) | Retrieves a cell from the specified worksheet using Excel-style cell name (e.g., "B2"). |
| [getChartsFromWorksheet(String worksheetName)](#getChartsFromWorksheet-java.lang.String-) | Retrieves a dictionary containing the indexes and names of all charts in the specified worksheet of an Excel workbook. |
| [getWorksheetNames()](#getWorksheetNames--) | Retrieves the names of all worksheets contained in the Excel workbook. |
### getCells(String formula, boolean skipHiddenCells) {#getCells-java.lang.String-boolean-}
```
public abstract System.Collections.Generic.List<IExcelDataCell> getCells(String formula, boolean skipHiddenCells)
```

지정된 수식과 일치하는 워크북의 셀 컬렉션을 가져옵니다.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  List<IExcelDataCell> cells = wb.getCells("Sheet1!A2:A6", false);
>  System.out.println(cells.size()); //출력: 5
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| formula | java.lang.String | 대상 셀을 식별하기 위해 사용되는 수식 또는 범위 표현식(예: "Sheet1!A1:B3")입니다. |
| skipHiddenCells | boolean | true인 경우 숨겨진 셀(숨겨진 행이나 열에 있는 셀 등)이 결과에서 제외됩니다. |

**반환값:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.slides.IExcelDataCell> - 지정된 수식과 일치하는 셀의 읽기 전용 목록입니다.
### getCell(int worksheetIndex, int row, int column) {#getCell-int-int-int-}
```
public abstract IExcelDataCell getCell(int worksheetIndex, int row, int column)
```

인덱스와 셀 좌표를 사용하여 지정된 워크시트에서 셀을 가져옵니다.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getValue().toString());
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| worksheetIndex | int | 워크시트의 0부터 시작하는 인덱스입니다. |
| row | int | 셀의 0부터 시작하는 행 인덱스입니다. |
| column | int | 셀의 0부터 시작하는 열 인덱스입니다. |

**반환값:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - 지정된 위치에 있는 셀입니다.
### getCell(String worksheetName, int row, int column) {#getCell-java.lang.String-int-int-}
```
public abstract IExcelDataCell getCell(String worksheetName, int row, int column)
```

워크시트 이름과 셀 좌표를 사용하여 지정된 워크시트에서 셀을 가져옵니다.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell("Sheet1", 1, 1);
>  System.out.println(cell.getValue().toString());
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| worksheetName | java.lang.String | 워크시트의 이름입니다. |
| row | int | 셀의 0부터 시작하는 행 인덱스입니다. |
| column | int | 셀의 0부터 시작하는 열 인덱스입니다. |

**반환값:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - 지정된 위치에 있는 셀입니다.
### getCell(int worksheetIndex, String cellName) {#getCell-int-java.lang.String-}
```
public abstract IExcelDataCell getCell(int worksheetIndex, String cellName)
```

인덱스와 Excel 형식 셀 이름(예: "B2")을 사용하여 지정된 워크시트에서 셀을 가져옵니다.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, "B2");
>  System.out.println(cell.getValue().toString());
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| worksheetIndex | int | 워크시트의 0부터 시작하는 인덱스입니다. |
| cellName | java.lang.String | Excel 형식 셀 참조(예: "A1", "C5")입니다. |

**반환값:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - 지정된 위치에 있는 셀입니다.
### getCell(String worksheetName, String cellName) {#getCell-java.lang.String-java.lang.String-}
```
public abstract IExcelDataCell getCell(String worksheetName, String cellName)
```

Excel 형식 셀 이름(예: "B2")을 사용하여 지정된 워크시트에서 셀을 가져옵니다.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell("Sheet1", "B2");
>  System.out.println(cell.getValue().toString());
> ```

**매개변수:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| worksheetName | java.lang.String | 워크시트의 이름입니다. |
| cellName | java.lang.String | Excel 형식 셀 참조(예: "A1", "C5")입니다. |

**반환값:**
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
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| worksheetName | java.lang.String | 차트를 검색할 워크시트의 이름입니다. |

**반환값:**
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

**반환값:**
com.aspose.ms.System.Collections.Generic.List<java.lang.String> - 워크시트 이름 목록입니다.