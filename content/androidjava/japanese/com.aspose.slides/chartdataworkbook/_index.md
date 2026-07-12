---
title: ChartDataWorkbook
second_title: Aspose.Slides for Android の Java API リファレンス
description: 埋め込み Excel ワークブックへのアクセスを提供します
type: docs
url: /ja/com.aspose.slides/chartdataworkbook/
---
**継承:**
java.lang.Object, com.aspose.slides.DomObject

**実装されているすべてのインターフェイス:**
[com.aspose.slides.IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)
```
public class ChartDataWorkbook extends DomObject<ChartData> implements IChartDataWorkbook
```

埋め込みExcelワークブックへのアクセスを提供します
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getWorksheets()](#getWorksheets--) | ワークシートのコレクションを取得します。 |
| [getCellCollection(String formula, boolean skipHiddenCells)](#getCellCollection-java.lang.String-boolean-) | セルのセットを取得します。 |
| [getCell(String worksheetName, int row, int column)](#getCell-java.lang.String-int-int-) | チャートの系列またはカテゴリに使用できるセルを取得します |
| [getCell(int worksheetIndex, int row, int column)](#getCell-int-int-int-) | チャートの系列またはカテゴリに使用できるセルを取得します |
| [getCell(int worksheetIndex, String cellName)](#getCell-int-java.lang.String-) | チャートの系列またはカテゴリに使用できるセルを取得します |
| [getCell(int worksheetIndex, String cellName, Object value)](#getCell-int-java.lang.String-java.lang.Object-) | チャートの系列またはカテゴリに使用できるセルを取得します |
| [getCell(int worksheetIndex, int row, int column, Object value)](#getCell-int-int-int-java.lang.Object-) | チャートの系列またはカテゴリに使用できるセルを取得します |
| [clear(int sheetIndex)](#clear-int-) | シート上のすべてのセル値をクリアします |
| [calculateFormulas()](#calculateFormulas--) | ワークブック内のすべての数式を計算し、対応するセルの値を更新します。 |

### getWorksheets() {#getWorksheets--}
```
public final IChartDataWorksheetCollection getWorksheets()
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

**戻り値:**
[IChartDataWorksheetCollection](../../com.aspose.slides/ichartdataworksheetcollection)

### getCellCollection(String formula, boolean skipHiddenCells) {#getCellCollection-java.lang.String-boolean-}
```
public final IChartCellCollection getCellCollection(String formula, boolean skipHiddenCells)
```

セルのセットを取得します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| formula | java.lang.String | Excel数式（例: "Sheet1!$A$2:$A$5"） |
| skipHiddenCells | boolean | true の場合、非表示セルを除いたコレクションを返します。 |

**戻り値:**
[IChartCellCollection](../../com.aspose.slides/ichartcellcollection)

### getCell(String worksheetName, int row, int column) {#getCell-java.lang.String-int-int-}
```
public final IChartDataCell getCell(String worksheetName, int row, int column)
```

チャートの系列またはカテゴリに使用できるセルを取得します

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| worksheetName | java.lang.String | ワークシートの名前。 |
| row | int | 行。 |
| column | int | 列。 |

**戻り値:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell オブジェクト

### getCell(int worksheetIndex, int row, int column) {#getCell-int-int-int-}
```
public final IChartDataCell getCell(int worksheetIndex, int row, int column)
```

チャートの系列またはカテゴリに使用できるセルを取得します

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| worksheetIndex | int | ワークシートのインデックス。 |
| row | int | 行。 |
| column | int | 列。 |

**戻り値:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell オブジェクト

### getCell(int worksheetIndex, String cellName) {#getCell-int-java.lang.String-}
```
public final IChartDataCell getCell(int worksheetIndex, String cellName)
```

チャートの系列またはカテゴリに使用できるセルを取得します

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| worksheetIndex | int | ワークシートのインデックス。 |
| cellName | java.lang.String | セルの名前。 |

**戻り値:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell オブジェクト

### getCell(int worksheetIndex, String cellName, Object value) {#getCell-int-java.lang.String-java.lang.Object-}
```
public final IChartDataCell getCell(int worksheetIndex, String cellName, Object value)
```

チャートの系列またはカテゴリに使用できるセルを取得します

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| worksheetIndex | int | ワークシートのインデックス。 |
| cellName | java.lang.String | セルの名前。 |
| value | java.lang.Object | 値。 |

**戻り値:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell オブジェクト

### getCell(int worksheetIndex, int row, int column, Object value) {#getCell-int-int-int-java.lang.Object-}
```
public final IChartDataCell getCell(int worksheetIndex, int row, int column, Object value)
```

チャートの系列またはカテゴリに使用できるセルを取得します

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| worksheetIndex | int | ワークシートのインデックス。 |
| row | int | 行。 |
| column | int | 列。 |
| value | java.lang.Object | 値。 |

**戻り値:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell) - Cell オブジェクト

### clear(int sheetIndex) {#clear-int-}
```
public final void clear(int sheetIndex)
```

シート上のすべてのセル値をクリアします

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| sheetIndex | int | シートのインデックス |

### calculateFormulas() {#calculateFormulas--}
```
public final void calculateFormulas()
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