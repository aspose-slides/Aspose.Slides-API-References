---
title: IExcelDataWorkbook
second_title: Aspose.Slides for Android via Java API Reference
description: Represents a workbook that provides access to Excel data for general use.
type: docs
url: /zh-hant/com.aspose.slides/iexceldataworkbook/
---```
public interface IExcelDataWorkbook
```

表示一個工作簿，可供一般使用者存取 Excel 資料。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getCells(String formula, boolean skipHiddenCells)](#getCells-java.lang.String-boolean-) | 取得符合指定公式的工作簿儲存格集合。 |
| [getCell(int worksheetIndex, int row, int column)](#getCell-int-int-int-) | 依索引和儲存格座標從指定工作表取得儲存格。 |
| [getCell(String worksheetName, int row, int column)](#getCell-java.lang.String-int-int-) | 依名稱和儲存格座標從指定工作表取得儲存格。 |
| [getCell(int worksheetIndex, String cellName)](#getCell-int-java.lang.String-) | 依索引和 Excel 風格的儲存格名稱（例如 "B2"）從指定工作表取得儲存格。 |
| [getCell(String worksheetName, String cellName)](#getCell-java.lang.String-java.lang.String-) | 依 Excel 風格的儲存格名稱（例如 "B2"）從指定工作表取得儲存格。 |
| [getChartsFromWorksheet(String worksheetName)](#getChartsFromWorksheet-java.lang.String-) | 取得 Excel 工作簿中指定工作表所有圖表的索引與名稱字典。 |
| [getWorksheetNames()](#getWorksheetNames--) | 取得 Excel 工作簿中所有工作表的名稱。 |
### getCells(String formula, boolean skipHiddenCells) {#getCells-java.lang.String-boolean-}
```
public abstract System.Collections.Generic.List<IExcelDataCell> getCells(String formula, boolean skipHiddenCells)
```


取得符合指定公式的工作簿儲存格集合。

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  List<IExcelDataCell> cells = wb.getCells("Sheet1!A2:A6", false);
>  System.out.println(cells.size()); //輸出: 5
> ```

**參數：**
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| formula | java.lang.String | 用於辨識目標儲存格的公式或範圍表達式（例如「Sheet1!A1:B3」）。 |
| skipHiddenCells | boolean | 如果為 true，隱藏的儲存格（例如在隱藏的列或欄中）將從結果中排除。 |

**返回：**
com.aspose.ms.System.Collections.Generic.List<com.aspose.slides.IExcelDataCell> - 一個唯讀的儲存格列表，符合指定的公式。

### getCell(int worksheetIndex, int row, int column) {#getCell-int-int-int-}
```
public abstract IExcelDataCell getCell(int worksheetIndex, int row, int column)
```


依索引和儲存格座標從指定工作表取得儲存格。

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getValue().toString());
> ```

**參數：**
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| worksheetIndex | int | 工作表的零基索引。 |
| row | int | 儲存格的零基列索引。 |
| column | int | 儲存格的零基欄索引。 |

**返回：**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - 指定位置的儲存格。

### getCell(String worksheetName, int row, int column) {#getCell-java.lang.String-int-int-}
```
public abstract IExcelDataCell getCell(String worksheetName, int row, int column)
```


依名稱和儲存格座標從指定工作表取得儲存格。

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell("Sheet1", 1, 1);
>  System.out.println(cell.getValue().toString());
> ```

**參數：**
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| worksheetName | java.lang.String | 工作表的名稱。 |
| row | int | 儲存格的零基列索引。 |
| column | int | 儲存格的零基欄索引。 |

**返回：**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - 指定位置的儲存格。

### getCell(int worksheetIndex, String cellName) {#getCell-int-java.lang.String-}
```
public abstract IExcelDataCell getCell(int worksheetIndex, String cellName)
```


依索引和 Excel 風格的儲存格名稱（例如 "B2"）從指定工作表取得儲存格。

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, "B2");
>  System.out.println(cell.getValue().toString());
> ```

**參數：**
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| worksheetIndex | int | 工作表的零基索引。 |
| cellName | java.lang.String | Excel 風格的儲存格參照（例如「A1」、「C5」）。 |

**返回：**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - 指定位置的儲存格。

### getCell(String worksheetName, String cellName) {#getCell-java.lang.String-java.lang.String-}
```
public abstract IExcelDataCell getCell(String worksheetName, String cellName)
```


依 Excel 風格的儲存格名稱（例如 "B2"）從指定工作表取得儲存格。

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell("Sheet1", "B2");
>  System.out.println(cell.getValue().toString());
> ```

**參數：**
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| worksheetName | java.lang.String | 工作表的名稱。 |
| cellName | java.lang.String | Excel 風格的儲存格參照（例如「A1」、「C5」）。 |

**返回：**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - 指定位置的儲存格。

### getChartsFromWorksheet(String worksheetName) {#getChartsFromWorksheet-java.lang.String-}
```
public abstract System.Collections.Generic.Dictionary<Integer,String> getChartsFromWorksheet(String worksheetName)
```


取得 Excel 工作簿中指定工作表所有圖表的索引與名稱字典。

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

**參數：**
| 參數 | 型別 | 描述 |
| --- | --- | --- |
| worksheetName | java.lang.String | 要搜尋圖表的工作表名稱。 |

**返回：**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.Integer,java.lang.String> - 鍵為圖表索引、值為圖表名稱的字典。

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

**返回：**
com.aspose.ms.System.Collections.Generic.List<java.lang.String> - 工作表名稱的列表