---
title: ExcelDataWorkbook
second_title: Aspose.Slides for Java API リファレンス
description: 一般的な使用のために Excel データへのアクセスを提供するワークブックを表します。
type: docs
url: /ja/com.aspose.slides/exceldataworkbook/
---
**継承:**
java.lang.Object

**実装されているすべてのインターフェイス:**
[com.aspose.slides.IExcelDataWorkbook](../../com.aspose.slides/iexceldataworkbook)
```
public class ExcelDataWorkbook implements IExcelDataWorkbook
```

一般的な使用のために Excel データへのアクセスを提供するワークブックを表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [ExcelDataWorkbook(String filePath)](#ExcelDataWorkbook-java.lang.String-) | 指定されたファイルパスを使用して新しいインスタンスを初期化します。 |
| [ExcelDataWorkbook(InputStream stream)](#ExcelDataWorkbook-java.io.InputStream-) | 提供されたストリームを使用してクラスの新しいインスタンスを初期化します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getCells(String formula, boolean skipHiddenCells)](#getCells-java.lang.String-boolean-) | 指定された数式に一致するワークブックからセルのコレクションを取得します。 |
| [getCell(int worksheetIndex, int row, int column)](#getCell-int-int-int-) | インデックスとセル座標を使用して、指定されたワークシートからセルを取得します。 |
| [getCell(String worksheetName, int row, int column)](#getCell-java.lang.String-int-int-) | 名前とセル座標を使用して、指定されたワークシートからセルを取得します。 |
| [getCell(int worksheetIndex, String cellName)](#getCell-int-java.lang.String-) | インデックスと Excel 形式のセル名（例: "B2"）を使用して、指定されたワークシートからセルを取得します。 |
| [getCell(String worksheetName, String cellName)](#getCell-java.lang.String-java.lang.String-) | Excel 形式のセル名（例: "B2"）を使用して、指定されたワークシートからセルを取得します。 |
| [getChartsFromWorksheet(String worksheetName)](#getChartsFromWorksheet-java.lang.String-) | Excel ワークブックの指定されたワークシートにあるすべてのチャートのインデックスと名前を含む辞書を取得します。 |
| [getWorksheetNames()](#getWorksheetNames--) | Excel ワークブックに含まれるすべてのワークシートの名前を取得します。 |

### ExcelDataWorkbook(String filePath) {#ExcelDataWorkbook-java.lang.String-}
```
public ExcelDataWorkbook(String filePath)
```

指定されたファイルパスを使用して新しいインスタンスを初期化します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| filePath | java.lang.String | Excel ワークブック ファイルへのフルパス。 |

### ExcelDataWorkbook(InputStream stream) {#ExcelDataWorkbook-java.io.InputStream-}
```
public ExcelDataWorkbook(InputStream stream)
```

提供されたストリームを使用してクラスの新しいインスタンスを初期化します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| stream | java.io.InputStream | Excel ワークブック データを含むストリーム。 |

### getCells(String formula, boolean skipHiddenCells) {#getCells-java.lang.String-boolean-}
```
public final System.Collections.Generic.List<IExcelDataCell> getCells(String formula, boolean skipHiddenCells)
```

指定された数式に一致するワークブックからセルのコレクションを取得します。

--------------------

> ```
> ExcelDataWorkbook wb = new ExcelDataWorkbook(testFile);
>  List<IExcelDataCell> cells = wb.getCells("Sheet1!A2:A6", false);
>  System.out.println(cells.size()); //出力: 5
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| formula | java.lang.String | 対象セルを特定するために使用される数式または範囲式（例: "Sheet1!A1:B3"）。 |
| skipHiddenCells | boolean | true の場合、隠しセル（隠し行や列にあるセルなど）は結果から除外されます。 |

**戻り値:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.slides.IExcelDataCell> - 指定された数式に一致するセルの読み取り専用リスト。

### getCell(int worksheetIndex, int row, int column) {#getCell-int-int-int-}
```
public final IExcelDataCell getCell(int worksheetIndex, int row, int column)
```

インデックスとセル座標を使用して、指定されたワークシートからセルを取得します。

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
| worksheetIndex | int | ワークシートのゼロベースインデックス。 |
| row | int | セルのゼロベース行インデックス。 |
| column | int | セルのゼロベース列インデックス。 |

**戻り値:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - 指定された場所のセル。

### getCell(String worksheetName, int row, int column) {#getCell-java.lang.String-int-int-}
```
public final IExcelDataCell getCell(String worksheetName, int row, int column)
```

名前とセル座標を使用して、指定されたワークシートからセルを取得します。

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
| row | int | セルのゼロベース行インデックス。 |
| column | int | セルのゼロベース列インデックス。 |

**戻り値:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - 指定された場所のセル。

### getCell(int worksheetIndex, String cellName) {#getCell-int-java.lang.String-}
```
public final IExcelDataCell getCell(int worksheetIndex, String cellName)
```

インデックスと Excel 形式のセル名（例: "B2"）を使用して、指定されたワークシートからセルを取得します。

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
| worksheetIndex | int | ワークシートのゼロベースインデックス。 |
| cellName | java.lang.String | Excel 形式のセル参照（例: "A1", "C5"）。 |

**戻り値:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - 指定された場所のセル。

### getCell(String worksheetName, String cellName) {#getCell-java.lang.String-java.lang.String-}
```
public final IExcelDataCell getCell(String worksheetName, String cellName)
```

Excel 形式のセル名（例: "B2"）を使用して、指定されたワークシートからセルを取得します。

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
| cellName | java.lang.String | Excel 形式のセル参照（例: "A1", "C5"）。 |

**戻り値:**
[IExcelDataCell](../../com.aspose.slides/iexceldatacell) - 指定された場所のセル。

### getChartsFromWorksheet(String worksheetName) {#getChartsFromWorksheet-java.lang.String-}
```
public final System.Collections.Generic.Dictionary<Integer,String> getChartsFromWorksheet(String worksheetName)
```

Excel ワークブックの指定されたワークシートにあるすべてのチャートのインデックスと名前を含む辞書を取得します。

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
public final System.Collections.Generic.List<String> getWorksheetNames()
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