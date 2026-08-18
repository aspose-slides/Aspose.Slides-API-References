---
title: IExcelDataWorkbook
second_title: Aspose.Slides for Java API Reference
description: 一般的な使用のために Excel データへのアクセスを提供するワークブックを表します。
type: docs
url: /ja/com.aspose.slides/iexceldataworkbook/
---```
public interface IExcelDataWorkbook
```

一般的な使用のために Excel データへのアクセスを提供するワークブックを表します。

## メソッド

| メソッド | 説明 |
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

指定された数式に一致するセルのコレクションを取得します。

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  List<IExcelDataCell> cells = wb.getCells("Sheet1!A2:A6", false);
>  System.out.println(cells.size()); //出力: 5
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| formula | java.lang.String | ターゲットセルを識別するために使用される数式または範囲式 (例: "Sheet1!A1:B3")。 |
| skipHiddenCells | boolean | true の場合、非表示の行や列にあるセルは結果から除外されます。 |

**戻り値:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.slides.IExcelDataCell> - 指定された数式に一致するセルの読み取り専用リスト。
### getCell(int worksheetIndex, int row, int column) {#getCell-int-int-int-}
```
public abstract IExcelDataCell getCell(int worksheetIndex, int row, int column)
```

指定されたワークシートから、インデックスとセル座標を使用してセルを取得します。

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, 1, 1);
>  System.out.println(cell.getValue().toString());
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| worksheetIndex | int | ワークシートのゼロベースのインデックス。 |
| row | int | セルのゼロベースの行インデックス。 |
| column | int | セルのゼロベースの列インデックス。 |

**戻り値:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - 指定された位置にあるセル。
### getCell(String worksheetName, int row, int column) {#getCell-java.lang.String-int-int-}
```
public abstract IExcelDataCell getCell(String worksheetName, int row, int column)
```

指定されたワークシートから、名前とセル座標を使用してセルを取得します。

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell("Sheet1", 1, 1);
>  System.out.println(cell.getValue().toString());
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| worksheetName | java.lang.String | ワークシートの名前。 |
| row | int | セルのゼロベースの行インデックス。 |
| column | int | セルのゼロベースの列インデックス。 |

**戻り値:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - 指定された位置にあるセル。
### getCell(int worksheetIndex, String cellName) {#getCell-int-java.lang.String-}
```
public abstract IExcelDataCell getCell(int worksheetIndex, String cellName)
```

指定されたワークシートから、インデックスと Excel 形式のセル名 (例: "B2") を使用してセルを取得します。

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell(1, "B2");
>  System.out.println(cell.getValue().toString());
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| worksheetIndex | int | ワークシートのゼロベースのインデックス。 |
| cellName | java.lang.String | Excel 形式のセル参照 (例: "A1", "C5")。 |

**戻り値:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - 指定された位置にあるセル。
### getCell(String worksheetName, String cellName) {#getCell-java.lang.String-java.lang.String-}
```
public abstract IExcelDataCell getCell(String worksheetName, String cellName)
```

Excel 形式のセル名 (例: "B2") を使用して、指定されたワークシートからセルを取得します。

--------------------

> ```
> Example:
>  
>  ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  IExcelDataCell cell = wb.getCell("Sheet1", "B2");
>  System.out.println(cell.getValue().toString());
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| worksheetName | java.lang.String | ワークシートの名前。 |
| cellName | java.lang.String | Excel 形式のセル参照 (例: "A1", "C5")。 |

**戻り値:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - 指定された位置にあるセル。
### getChartsFromWorksheet(String worksheetName) {#getChartsFromWorksheet-java.lang.String-}
```
public abstract System.Collections.Generic.Dictionary<Integer,String> getChartsFromWorksheet(String worksheetName)
```

Excel ワークブックの指定されたワークシートに含まれるすべてのチャートのインデックスと名前を含む辞書を取得します。

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

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| worksheetName | java.lang.String | チャートを検索するワークシートの名前。 |

**戻り値:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.Integer,java.lang.String> - キーがチャートインデックス、値がチャート名である辞書。
### getWorksheetNames() {#getWorksheetNames--}
```
public abstract System.Collections.Generic.List<String> getWorksheetNames()
```

Excel ワークブックに含まれるすべてのワークシートの名前を取得します。

--------------------

> ```
> Example:
>  
>  IExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  List<String> sheetNames = wb.getWorksheetNames();
>  for (String name : sheetNames)
>      System.out.println(name);
> ```

**戻り値:**
com.aspose.ms.System.Collections.Generic.List<java.lang.String> - ワークシート名のリスト