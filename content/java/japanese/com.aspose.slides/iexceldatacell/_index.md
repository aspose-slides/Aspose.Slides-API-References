---
title: IExcelDataCell
second_title: Aspose.Slides for Java API Reference
description: Excel ブック内の単一セルを表します。
type: docs
url: /ja/com.aspose.slides/iexceldatacell/
---```
public interface IExcelDataCell
```

Excel ブック内の単一セルを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getValue()](#getValue--) | Excel セルに含まれる値を取得します。 |
| [getName()](#getName--) | チャート データセルの名前を取得します。 |
| [getRow()](#getRow--) | セルが位置するワークシート内の行のゼロベースインデックスを取得します。 |
| [getColumn()](#getColumn--) | セルが位置するワークシート内の列のゼロベースインデックスを取得します。 |
### getValue() {#getValue--}
```
public abstract Object getValue()
```

Excel セルに含まれる値を取得します。読み取り専用 Object .

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

チャート データセルの名前を取得します。読み取り専用 String.

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

セルが位置するワークシート内の行のゼロベースインデックスを取得します。読み取り専用 int.

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

セルが位置するワークシート内の列のゼロベースインデックスを取得します。読み取り専用 int.

--------------------

> ```
> Example:
>  
> v
> ```

**戻り値:**  
int