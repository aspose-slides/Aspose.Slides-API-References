---
title: ExcelDataCell
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 代表 Excel 活頁簿中的單一儲存格。
type: docs
url: /zh-hant/com.aspose.slides/exceldatacell/
---
**繼承:**  
java.lang.Object

**所有已實作的介面:**  
[com.aspose.slides.IExcelDataCell](../../com.aspose.slides/iexceldatacell)  
```
public class ExcelDataCell implements IExcelDataCell
```

代表 Excel 活頁簿中的單一儲存格。

## 方法

| 方法 | 說明 |
| --- | --- |
| [getValue()](#getValue--) | 取得 Excel 儲存格中包含的值。 |
| [getName()](#getName--) | 取得圖表資料儲存格的名稱。 |
| [getRow()](#getRow--) | 取得儲存格所在工作表中列的零基索引。 |
| [getColumn()](#getColumn--) | 取得儲存格所在工作表中欄的零基索引。 |

### getValue() {#getValue--}
```
public final Object getValue()
```

取得 Excel 儲存格中包含的值。

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getValue().toString());
> ```

**返回:**  
java.lang.Object

### getName() {#getName--}
```
public final String getName()
```

取得圖表資料儲存格的名稱。

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getName()); //輸出: "B2"
> ```

**返回:**  
java.lang.String

### getRow() {#getRow--}
```
public final int getRow()
```

取得儲存格所在工作表中列的零基索引。唯讀 int。

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getRow()); //輸出: 1
> ```

**返回:**  
int

### getColumn() {#getColumn--}
```
public final int getColumn()
```

取得儲存格所在工作表中欄的零基索引。唯讀 int。

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getColumn()); //輸出: 1
> ```


**返回:**  
int