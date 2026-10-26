---
title: IChartDataWorkbook
second_title: Aspose.Slides for Android via Java API Reference
description: Provides access to embedded Excel workbook
type: docs
url: /ja/com.aspose.slides/ichartdataworkbook/
---```
public interface IChartDataWorkbook
```

埋め込み Excel ワークブックへのアクセスを提供します
## メソッド

| メソッド | 説明 |
| --- | --- |
| [calculateFormulas()](#calculateFormulas--) | ワークブック内のすべての数式を計算し、対応するセルの値を更新します。 |
| [getCellCollection(String formula, boolean skipHiddenCells)](#getCellCollection-java.lang.String-boolean-) | セルのセットを取得します。 |
| [getCell(String worksheetName, int row, int column)](#getCell-java.lang.String-int-int-) | グラフ系列またはカテゴリに使用できるセルを取得します |
| [getCell(int worksheetIndex, int row, int column)](#getCell-int-int-int-) | グラフ系列またはカテゴリに使用できるセルを取得します |
| [getCell(int worksheetIndex, String cellName)](#getCell-int-java.lang.String-) | グラフ系列またはカテゴリに使用できるセルを取得します |
| [getCell(int worksheetIndex, String cellName, Object value)](#getCell-int-java.lang.String-java.lang.Object-) | グラフ系列またはカテゴリに使用できるセルを取得します |
| [getCell(int worksheetIndex, int row, int column, Object value)](#getCell-int-int-int-java.lang.Object-) | グラフ系列またはカテゴリに使用できるセルを取得します |
| [clear(int sheetIndex)](#clear-int-) | シート上のすべてのセルの値をクリアします |
| [getWorksheets()](#getWorksheets--) | ワークシートのコレクションを取得します。 |
### calculateFormulas() {#calculateFormulas--}
```
public abstract void calculateFormulas()
```

ワークブック内のすべての数式を計算し、対応するセルの値を更新します。

--------------------

> ```
> Example shows how to assign a formula to the cell and to calculate a value. The value of the "B4" cell is getting set to 5.
>   
>   Presentation pres = new Presentation();
>   try {
>       IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.Pie, 100, 100, 300, 400);
>       IChartDataWorkbook wb = chart.getChartData().getChartDataWorkbook();
>       wb.getCell(0, "B2", 2);
>       wb.getCell(0, "B3", 3);
>       wb.getCell(0, "B4").setFormula("B2+B3");
>       wb.calculateFormulas();
>       ...
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```

### getCellCollection(String formula, boolean skipHiddenCells) {#getCellCollection-java.lang.String-boolean-}
```
public abstract IChartCellCollection getCellCollection(String formula, boolean skipHiddenCells)
```

セルのセットを取得します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| formula | java.lang.String | 例: "Sheet1!$A$2:$A$5" のような Excel 数式 |
| skipHiddenCells | boolean | true の場合、非表示セルを除いたコレクションを返します。 |

**リターン:**
[IChartCellCollection](../../com.aspose.slides/ichartcellcollection) - セット of cells [IChartCellCollection](../../com.aspose.slides/ichartcellcollection)
### getCell(String worksheetName, int row, int column) {#getCell-java.lang.String-int-int-}
```
public abstract IChartDataCell getCell(String worksheetName, int row, int column)
```

グラフ系列またはカテゴリに使用できるセルを取得します

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| worksheetName | java.lang.String | ワークシートの名前 |
| row | int | 行 |
| column | int | 列 |

**リターン:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell オブジェクト
### getCell(int worksheetIndex, int row, int column) {#getCell-int-int-int-}
```
public abstract IChartDataCell getCell(int worksheetIndex, int row, int column)
```

グラフ系列またはカテゴリに使用できるセルを取得します

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| worksheetIndex | int | ワークシートのインデックス |
| row | int | 行 |
| column | int | 列 |

**リターン:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell オブジェクト
### getCell(int worksheetIndex, String cellName) {#getCell-int-java.lang.String-}
```
public abstract IChartDataCell getCell(int worksheetIndex, String cellName)
```

グラフ系列またはカテゴリに使用できるセルを取得します

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| worksheetIndex | int | ワークシートのインデックス |
| cellName | java.lang.String | セルの名前 |

**リターン:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell オブジェクト
### getCell(int worksheetIndex, String cellName, Object value) {#getCell-int-java.lang.String-java.lang.Object-}
```
public abstract IChartDataCell getCell(int worksheetIndex, String cellName, Object value)
```

グラフ系列またはカテゴリに使用できるセルを取得します

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| worksheetIndex | int | ワークシートのインデックス |
| cellName | java.lang.String | セルの名前 |
| value | java.lang.Object | 値 |

**リターン:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell オブジェクト
### getCell(int worksheetIndex, int row, int column, Object value) {#getCell-int-int-int-java.lang.Object-}
```
public abstract IChartDataCell getCell(int worksheetIndex, int row, int column, Object value)
```

グラフ系列またはカテゴリに使用できるセルを取得します

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| worksheetIndex | int | ワークシートのインデックス |
| row | int | 行 |
| column | int | 列 |
| value | java.lang.Object | 値 |

**リターン:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell オブジェクト
### clear(int sheetIndex) {#clear-int-}
```
public abstract void clear(int sheetIndex)
```

シート上のすべてのセルの値をクリアします

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| sheetIndex | int | シートのインデックス |

### getWorksheets() {#getWorksheets--}
```
public abstract IChartDataWorksheetCollection getWorksheets()
```

ワークシートのコレクションを取得します。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.Pie, 50, 50, 400, 500);
>      IChartDataWorkbook workbook =  chart.getChartData().getChartDataWorkbook();
>      for (IChartDataWorksheet worksheet : workbook.getWorksheets())
>      {
>          String worksheetName = worksheet.getName();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**リターン:**
[IChartDataWorksheetCollection](../../com.aspose.slides/ichartdataworksheetcollection)