---
title: IExcelDataCell
second_title: Aspose.Slides for Java API 參考
description: 表示 Excel 活頁簿中的單一儲存格。
type: docs
url: /zh-hant/com.aspose.slides/iexceldatacell/
---```
public interface IExcelDataCell
```

表示 Excel 活頁簿中的單一儲存格。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getValue()](#getValue--) | 取得 Excel 儲存格中包含的值。 |
| [getName()](#getName--) | 取得圖表資料儲存格的名稱。 |
| [getRow()](#getRow--) | 取得儲存格所在工作表中列的零基索引。 |
| [getColumn()](#getColumn--) | 取得儲存格所在工作表中欄的零基索引。 |
### getValue() {#getValue--}
```
public abstract Object getValue()
```


取得 Excel 儲存格中包含的值。唯讀  Object .

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getValue().toString());
> ```

**傳回:**  
java.lang.Object
### getName() {#getName--}
```
public abstract String getName()
```


取得圖表資料儲存格的名稱。唯讀 String.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getName()); //輸出: "B2"
> ```

**傳回:**  
java.lang.String
### getRow() {#getRow--}
```
public abstract int getRow()
```


取得儲存格所在工作表中列的零基索引。唯讀 int.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getRow()); //輸出: 1
> ```

**傳回:**  
int
### getColumn() {#getColumn--}
```
public abstract int getColumn()
```


取得儲存格所在工作表中欄的零基索引。唯讀 int.

--------------------

> ```
> Example:
>  
> v
> ```

**傳回:**  
int