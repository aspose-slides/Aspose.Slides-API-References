---
title: IExcelDataCell
second_title: Aspose.Slides for Android via Java API リファレンス
description: Excel ワークブックの単一セルを表します。
type: docs
url: /ja/com.aspose.slides/iexceldatacell/
---```
public interface IExcelDataCell
```

Excel ワークブックの単一セルを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getValue()](#getValue--) | Excel セルに含まれる値を取得します。 |
| [getName()](#getName--) | チャート データ セルの名前を取得します。 |
| [getRow()](#getRow--) | セルが配置されているワークシート内の行の zero-based インデックスを取得します。 |
| [getColumn()](#getColumn--) | セルが配置されているワークシート内の列の zero-based インデックスを取得します。 |
### getValue() {#getValue--}
```
public abstract Object getValue()
```


Excel セルに含まれる値を取得します。 読み取り専用  Object .

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getValue().toString());
> ```

**戻り値:**
java.lang.Object
### getName() {#getName--}
```
public abstract String getName()
```


チャート データ セルの名前を取得します。 読み取り専用 String.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getName()); //出力: "B2"
> ```

**戻り値:**
java.lang.String
### getRow() {#getRow--}
```
public abstract int getRow()
```


セルが配置されているワークシート内の行の zero-based インデックスを取得します。 読み取り専用 int.

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getRow()); //出力: 1
> ```

**戻り値:**
int
### getColumn() {#getColumn--}
```
public abstract int getColumn()
```


セルが配置されているワークシート内の列の zero-based インデックスを取得します。 読み取り専用 int.

--------------------

> ```
> Example:
>  
> v
> ```

**戻り値:**
int