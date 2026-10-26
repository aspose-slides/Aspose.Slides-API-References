---
title: ExcelDataCell
second_title: Aspose.Slides の Java API リファレンス
description: Excel ワークブック内の単一セルを表します。
type: docs
url: /ja/com.aspose.slides/exceldatacell/
---
**継承:**  
java.lang.Object

**実装されているすべてのインターフェイス:**  
[com.aspose.slides.IExcelDataCell](../../com.aspose.slides/iexceldatacell)  
```
public class ExcelDataCell implements IExcelDataCell
```

Excel ワークブック内の単一セルを表します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getValue()](#getValue--) | Excel セルに含まれる値を取得します。 |
| [getName()](#getName--) | チャート データ セルの名前を取得します。 |
| [getRow()](#getRow--) | セルが位置するワークシートの行のゼロベース インデックスを取得します。 |
| [getColumn()](#getColumn--) | セルが位置するワークシートの列のゼロベース インデックスを取得します。 |
### getValue() {#getValue--}
```
public final Object getValue()
```

Excel セルに含まれる値を取得します。

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
public final String getName()
```

チャート データ セルの名前を取得します。

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
public final int getRow()
```

セルが位置するワークシートの行のゼロベース インデックスを取得します。読み取り専用 int。

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
public final int getColumn()
```

セルが位置するワークシートの列のゼロベース インデックスを取得します。読み取り専用 int。

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getColumn()); //出力: 1
> ```


**戻り値:**  
int