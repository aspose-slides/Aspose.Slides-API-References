---
title: ExcelDataWorkbook
second_title: Aspose.Slides for Java API 參考
description: 表示一個工作簿，可提供對 Excel 資料的一般存取。
type: docs
url: /zh-hant/com.aspose.slides/exceldataworkbook/
---
**繼承:**
java.lang.Object

**所有已實作的介面:**
[com.aspose.slides.IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook)
```
public class ExcelDataWorkbook implements IExcelDataWorkbook
```

表示一個工作簿，可提供對 Excel 資料的一般存取。
## 建構函式

| 建構函式 | 說明 |
| --- | --- |
| [ExcelDataWorkbook(String filePath)](#ExcelDataWorkbook-java.lang.String-) | 使用指定的檔案路徑初始化新實例。 |
| [ExcelDataWorkbook(InputStream stream)](#ExcelDataWorkbook-java.io.InputStream-) | 使用提供的串流初始化類別的新實例。 |
## 方法

| 方法 | 說明 |
| --- | --- |
| [getCells(String formula, boolean skipHiddenCells)](#getCells-java.lang.String-boolean-) | 從工作簿中擷取符合指定公式的儲存格集合。 |
| [getCell(int worksheetIndex, int row, int column)](#getCell-int-int-int-) | 使用索引與儲存格座標從指定工作表擷取儲存格。 |
| [getCell(String worksheetName, int row, int column)](#getCell-java.lang.String-int-int-) | 使用名稱與儲存格座標從指定工作表擷取儲存格。 |
| [getCell(int worksheetIndex, String cellName)](#getCell-int-java.lang.String-) | 使用索引與 Excel 風格的儲存格名稱（例如 "B2"）從指定工作表擷取儲存格。 |
| [getCell(String worksheetName, String cellName)](#getCell-java.lang.String-java.lang.String-) | 使用 Excel 風格的儲存格名稱（例如 "B2"）從指定工作表擷取儲存格。 |
| [getChartsFromWorksheet(String worksheetName)](#getChartsFromWorksheet-java.lang.String-) | 擷取包含 Excel 工作簿中指定工作表所有圖表的索引與名稱的字典。 |
| [getWorksheetNames()](#getWorksheetNames--) | 擷取 Excel 工作簿中所有工作表的名稱。 |
### ExcelDataWorkbook(String filePath) {#ExcelDataWorkbook-java.lang.String-}
```
public ExcelDataWorkbook(String filePath)
```


使用指定的檔案路徑初始化新實例。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| filePath | java.lang.String | Excel 工作簿檔案的完整路徑。 |

### ExcelDataWorkbook(InputStream stream) {#ExcelDataWorkbook-java.io.InputStream-}
```
public ExcelDataWorkbook(InputStream stream)
```


使用提供的串流初始化類別的新實例。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| stream | java.io.InputStream | 包含 Excel 工作簿資料的串流。 |

### getCells(String formula, boolean skipHiddenCells) {#getCells-java.lang.String-boolean-}
```
public final System.Collections.Generic.List<IExcelDataCell> getCells(String formula, boolean skipHiddenCells)
```


從工作簿中擷取符合指定公式的儲存格集合。

--------------------

> ```
> ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  List<IExcelDataCell> cells = wb.getCells("Sheet1!A2:A6", false);
>  System.out.println(cells.size()); //輸出: 5
> ```


**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| formula | java.lang.String | 用於識別目標儲存格的公式或範圍表達式（例如 "Sheet1!A1:B3"）。 |
| skipHiddenCells | boolean | 如果為 true，隱藏的儲存格（例如隱藏的列或欄）將從結果中排除。 |

**傳回值：**
com.aspose.ms.System.Collections.Generic.List<com.aspose.slides.IExcelDataCell> - 只讀的儲存格清單，符合指定的公式。

### getCell(int worksheetIndex, int row, int column) {#getCell-int-int-int-}
```
public final IExcelDataCell getCell(int worksheetIndex, int row, int column)
```


使用索引與儲存格座標從指定工作表擷取儲存格。

--------------------

> ```
> 範例：
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getValue().toString());
> ```


**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| worksheetIndex | int | 工作表的零基索引。 |
| row | int | 儲存格的零基列索引。 |
| column | int | 儲存格的零基欄索引。 |

**傳回值：**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - 指定位置的儲存格。

### getCell(String worksheetName, int row, int column) {#getCell-java.lang.String-int-int-}
```
public final IExcelDataCell getCell(String worksheetName, int row, int column)
```


使用名稱與儲存格座標從指定工作表擷取儲存格。

--------------------

> ```
> 範例：
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell("Sheet1", 1, 1);
>  System.out.println(cell.getValue().toString());
> ```


**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| worksheetName | java.lang.String | 工作表的名稱。 |
| row | int | 儲存格的零基列索引。 |
| column | int | 儲存格的零基欄索引。 |

**傳回值：**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - 指定位置的儲存格。

### getCell(int worksheetIndex, String cellName) {#getCell-int-java.lang.String-}
```
public final IExcelDataCell getCell(int worksheetIndex, String cellName)
```


使用索引與 Excel 風格的儲存格名稱（例如 "B2"）從指定工作表擷取儲存格。

--------------------

> ```
> 範例：
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, "B2");
>  System.out.println(cell.getValue().toString());
> ```


**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| worksheetIndex | int | 工作表的零基索引。 |
| cellName | java.lang.String | Excel 風格的儲存格參照（例如 "A1", "C5"）。 |

**傳回值：**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - 指定位置的儲存格。

### getCell(String worksheetName, String cellName) {#getCell-java.lang.String-java.lang.String-}
```
public final IExcelDataCell getCell(String worksheetName, String cellName)
```


使用 Excel 風格的儲存格名稱（例如 "B2"）從指定工作表擷取儲存格。

--------------------

> ```
> 範例：
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell("Sheet1", "B2");
>  System.out.println(cell.getValue().toString());
> ```


**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| worksheetName | java.lang.String | 工作表的名稱。 |
| cellName | java.lang.String | Excel 風格的儲存格參照（例如 "A1", "C5"）。 |

**傳回值：**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - 指定位置的儲存格。

### getChartsFromWorksheet(String worksheetName) {#getChartsFromWorksheet-java.lang.String-}
```
public final System.Collections.Generic.Dictionary<Integer,String> getChartsFromWorksheet(String worksheetName)
```


擷取包含 Excel 工作簿中指定工作表所有圖表的索引與名稱的字典。

--------------------

> ```
> 範例：
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
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| worksheetName | java.lang.String | 要搜尋圖表的工作表名稱。 |

**傳回值：**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.Integer,java.lang.String> - 字典，鍵為圖表索引，值為圖表名稱。

### getWorksheetNames() {#getWorksheetNames--}
```
public final System.Collections.Generic.List<String> getWorksheetNames()
```


擷取 Excel 工作簿中所有工作表的名稱。

--------------------

> ```
> 範例：
>  
>  IExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  List<String> sheetNames = wb.getWorksheetNames();
>  for (String name : sheetNames)
>      System.out.println(name);
> ```


**傳回值：**
com.aspose.ms.System.Collections.Generic.List<java.lang.String> - 工作表名稱的清單