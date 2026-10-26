---
title: IExcelDataWorkbook
second_title: Aspose.Slides for Java API 參考
description: 代表一個工作簿，提供一般用途的 Excel 資料存取。
type: docs
url: /zh-hant/com.aspose.slides/iexceldataworkbook/
---```
public interface IExcelDataWorkbook
```

代表一個工作簿，提供一般用途的 Excel 資料存取。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getCells(String formula, boolean skipHiddenCells)](#getCells-java.lang.String-boolean-) | 取得工作簿中符合指定公式的儲存格集合。 |
| [getCell(int worksheetIndex, int row, int column)](#getCell-int-int-int-) | 使用索引和儲存格座標從指定的工作表取得儲存格。 |
| [getCell(String worksheetName, int row, int column)](#getCell-java.lang.String-int-int-) | 使用名稱和儲存格座標從指定的工作表取得儲存格。 |
| [getCell(int worksheetIndex, String cellName)](#getCell-int-java.lang.String-) | 使用索引和 Excel 風格的儲存格名稱（例如 "B2"）從指定的工作表取得儲存格。 |
| [getCell(String worksheetName, String cellName)](#getCell-java.lang.String-java.lang.String-) | 使用 Excel 風格的儲存格名稱（例如 "B2"）從指定的工作表取得儲存格。 |
| [getChartsFromWorksheet(String worksheetName)](#getChartsFromWorksheet-java.lang.String-) | 取得字典，包含 Excel 工作簿中指定工作表內所有圖表的索引與名稱。 |
| [getWorksheetNames()](#getWorksheetNames--) | 取得 Excel 工作簿中所有工作表的名稱。 |
### getCells(String formula, boolean skipHiddenCells) {#getCells-java.lang.String-boolean-}
```
public abstract System.Collections.Generic.List<IExcelDataCell> getCells(String formula, boolean skipHiddenCells)
```

取得工作簿中符合指定公式的儲存格集合。

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  List<IExcelDataCell> cells = wb.getCells("Sheet1!A2:A6", false);
>  System.out.println(cells.size()); //輸出: 5
> ```


**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| formula | java.lang.String | 用於識別目標儲存格的公式或範圍表達式（例如 "Sheet1!A1:B3"）。 |
| skipHiddenCells | boolean | 如果為 true，隱藏的儲存格（例如在隱藏的列或欄中）將不會包含在結果中。 |

**返回值:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.slides.IExcelDataCell> - 符合指定公式的唯讀儲存格清單。
### getCell(int worksheetIndex, int row, int column) {#getCell-int-int-int-}
```
public abstract IExcelDataCell getCell(int worksheetIndex, int row, int column)
```

使用索引和儲存格座標從指定的工作表取得儲存格。

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getValue().toString());
> ```


**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| worksheetIndex | int | 工作表的零基索引。 |
| row | int | 儲存格所在列的零基索引。 |
| column | int | 儲存格所在欄的零基索引。 |

**返回值:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - 指定位置的儲存格。
### getCell(String worksheetName, int row, int column) {#getCell-java.lang.String-int-int-}
```
public abstract IExcelDataCell getCell(String worksheetName, int row, int column)
```

使用名稱和儲存格座標從指定的工作表取得儲存格。

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell("Sheet1", 1, 1);
>  System.out.println(cell.getValue().toString());
> ```


**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| worksheetName | java.lang.String | 工作表的名稱。 |
| row | int | 儲存格所在列的零基索引。 |
| column | int | 儲存格所在欄的零基索引。 |

**返回值:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - 指定位置的儲存格。
### getCell(int worksheetIndex, String cellName) {#getCell-int-java.lang.String-}
```
public abstract IExcelDataCell getCell(int worksheetIndex, String cellName)
```

使用索引和 Excel 風格的儲存格名稱（例如 "B2"）從指定的工作表取得儲存格。

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, "B2");
>  System.out.println(cell.getValue().toString());
> ```

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| worksheetIndex | int | 工作表的零基索引。 |
| cellName | java.lang.String | Excel 風格的儲存格參照（例如 "A1", "C5"）。 |

**返回值:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - 指定位置的儲存格。
### getCell(String worksheetName, String cellName) {#getCell-java.lang.String-java.lang.String-}
```
public abstract IExcelDataCell getCell(String worksheetName, String cellName)
```

使用 Excel 風格的儲存格名稱（例如 "B2"）從指定的工作表取得儲存格。

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell("Sheet1", "B2");
>  System.out.println(cell.getValue().toString());
> ```

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| worksheetName | java.lang.String | 工作表的名稱。 |
| cellName | java.lang.String | Excel 風格的儲存格參照（例如 "A1", "C5"）。 |

**返回值:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - 指定位置的儲存格。
### getChartsFromWorksheet(String worksheetName) {#getChartsFromWorksheet-java.lang.String-}
```
public abstract System.Collections.Generic.Dictionary<Integer,String> getChartsFromWorksheet(String worksheetName)
```

取得字典，包含 Excel 工作簿中指定工作表內所有圖表的索引與名稱。

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


**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| worksheetName | java.lang.String | 要搜尋圖表的工作表名稱。 |

**返回值:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.Integer,java.lang.String> - 字典，其中鍵為圖表索引，值為圖表名稱。
### getWorksheetNames() {#getWorksheetNames--}
```
public abstract System.Collections.Generic.List<String> getWorksheetNames()
```

取得 Excel 工作簿中所有工作表的名稱。

--------------------

> ```
> Example:
>  
>  IExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  List<String> sheetNames = wb.getWorksheetNames();
>  for (String name : sheetNames)
>      System.out.println(name);
> ```

**返回值:**
com.aspose.ms.System.Collections.Generic.List<java.lang.String> - 工作表名稱的清單.