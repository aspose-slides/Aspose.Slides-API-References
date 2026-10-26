---
title: ExcelDataWorkbook
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 表示一個提供一般使用之 Excel 資料存取的活頁簿。
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

表示一個提供一般使用的 Excel 資料存取的活頁簿。

## 建構函式

| 建構子 | 說明 |
| --- | --- |
| [ExcelDataWorkbook(String filePath)](#ExcelDataWorkbook-java.lang.String-) | 使用指定的檔案路徑初始化新實例。 |
| [ExcelDataWorkbook(InputStream stream)](#ExcelDataWorkbook-java.io.InputStream-) | 使用提供的串流初始化此類別的新實例。 |

## 方法

| 方法 | 說明 |
| --- | --- |
| [getCells(String formula, boolean skipHiddenCells)](#getCells-java.lang.String-boolean-) | 取得活頁簿中符合指定公式的儲存格集合。 |
| [getCell(int worksheetIndex, int row, int column)](#getCell-int-int-int-) | 依索引與儲存格座標從指定的工作表取得儲存格。 |
| [getCell(String worksheetName, int row, int column)](#getCell-java.lang.String-int-int-) | 依名稱與儲存格座標從指定的工作表取得儲存格。 |
| [getCell(int worksheetIndex, String cellName)](#getCell-int-java.lang.String-) | 依索引與 Excel 風格的儲存格名稱（例如「B2」）從指定的工作表取得儲存格。 |
| [getCell(String worksheetName, String cellName)](#getCell-java.lang.String-java.lang.String-) | 依 Excel 風格的儲存格名稱（例如「B2」）從指定的工作表取得儲存格。 |
| [getChartsFromWorksheet(String worksheetName)](#getChartsFromWorksheet-java.lang.String-) | 取得包含 Excel 活頁簿中指定工作表所有圖表之索引與名稱的字典。 |
| [getWorksheetNames()](#getWorksheetNames--) | 取得 Excel 活頁簿中所有工作表的名稱。 |

### ExcelDataWorkbook(String filePath) {#ExcelDataWorkbook-java.lang.String-}
```
public ExcelDataWorkbook(String filePath)
```

使用指定的檔案路徑初始化新實例。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| filePath | java.lang.String | Excel 活頁簿檔案的完整路徑。 |

### ExcelDataWorkbook(InputStream stream) {#ExcelDataWorkbook-java.io.InputStream-}
```
public ExcelDataWorkbook(InputStream stream)
```

使用提供的串流初始化此類別的新實例。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| stream | java.io.InputStream | 包含 Excel 活頁簿資料的串流。 |

### getCells(String formula, boolean skipHiddenCells) {#getCells-java.lang.String-boolean-}
```
public final System.Collections.Generic.List<IExcelDataCell> getCells(String formula, boolean skipHiddenCells)
```

取得活頁簿中符合指定公式的儲存格集合。

--------------------

> ```
> ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  List<IExcelDataCell> cells = wb.getCells("Sheet1!A2:A6", false);
>  System.out.println(cells.size()); //輸出: 5
> ```


**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| formula | java.lang.String | 用於識別目標儲存格的公式或範圍表達式（例如「Sheet1!A1:B3」）。 |
| skipHiddenCells | boolean | 如果為 true，隱藏的儲存格（例如在隱藏的列或欄中）將被排除在結果之外。 |

**返回值:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.slides.IExcelDataCell> - 只讀的儲存格清單，符合指定的公式。

### getCell(int worksheetIndex, int row, int column) {#getCell-int-int-int-}
```
public final IExcelDataCell getCell(int worksheetIndex, int row, int column)
```

依索引與儲存格座標從指定的工作表取得儲存格。

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
public final IExcelDataCell getCell(String worksheetName, int row, int column)
```

依名稱與儲存格座標從指定的工作表取得儲存格。

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
public final IExcelDataCell getCell(int worksheetIndex, String cellName)
```

依索引與 Excel 風格的儲存格名稱（例如「B2」）從指定的工作表取得儲存格。

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
| cellName | java.lang.String | Excel 風格的儲存格參照（例如「A1」,「C5」）。 |

**返回值:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - 指定位置的儲存格。

### getCell(String worksheetName, String cellName) {#getCell-java.lang.String-java.lang.String-}
```
public final IExcelDataCell getCell(String worksheetName, String cellName)
```

依 Excel 風格的儲存格名稱（例如「B2」）從指定的工作表取得儲存格。

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
| cellName | java.lang.String | Excel 風格的儲存格參照（例如「A1」,「C5」）。 |

**返回值:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - 指定位置的儲存格。

### getChartsFromWorksheet(String worksheetName) {#getChartsFromWorksheet-java.lang.String-}
```
public final System.Collections.Generic.Dictionary<Integer,String> getChartsFromWorksheet(String worksheetName)
```

取得包含 Excel 活頁簿中指定工作表所有圖表之索引與名稱的字典。

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
| worksheetName | java.lang.String | 要搜尋圖表之工作表的名稱。 |

**返回值:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.Integer,java.lang.String> - 字典，其中鍵為圖表索引，值為圖表名稱。

### getWorksheetNames() {#getWorksheetNames--}
```
public final System.Collections.Generic.List<String> getWorksheetNames()
```

取得 Excel 活頁簿中所有工作表的名稱。

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
com.aspose.ms.System.Collections.Generic.List<java.lang.String> - 工作表名稱的清單。