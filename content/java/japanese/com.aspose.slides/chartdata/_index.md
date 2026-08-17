---
title: ChartData
second_title: Aspose.Slides for Java API リファレンス
description: チャートのプロットに使用されるデータを表します。
type: docs
url: /ja/com.aspose.slides/chartdata/
---
**継承:**  
java.lang.Object, com.aspose.slides.DomObject

**実装したすべてのインターフェイス:**  
[com.aspose.slides.IChartData](../../com.aspose.slides/ichartdata)  
```
public class ChartData extends DomObject<Chart> implements IChartData
```

チャートのプロットに使用されるデータを表します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getChartDataWorkbook()](#getChartDataWorkbook--) | チャートシリーズまたはカテゴリで使用されるセルを作成するためのセルファクトリを取得します。 |
| [getSeries()](#getSeries--) | シリーズを取得します。 |
| [getSeriesGroups()](#getSeriesGroups--) | シリーズのグループを取得します。 |
| [getCategories()](#getCategories--) | 一次カテゴリを取得します（または、\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) プロパティが false の場合は一次および二次の両方のカテゴリを取得します）。 |
| [getUseSecondaryCategories()](#getUseSecondaryCategories--) | false の場合、\#getSecondaryCategories.getSecondaryCategories プロパティは null を返し、\#getCategories.getCategories プロパティのデータが一次と二次のシリーズの両方に使用されます。 |
| [setUseSecondaryCategories(boolean value)](#setUseSecondaryCategories-boolean-) | false の場合、\#getSecondaryCategories.getSecondaryCategories プロパティは null を返し、\#getCategories.getCategories プロパティのデータが一次と二次のシリーズの両方に使用されます。 |
| [getSecondaryCategories()](#getSecondaryCategories--) | \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) プロパティが true の場合、二次カテゴリを取得します。 |
| [readWorkbookStream()](#readWorkbookStream--) | 内部に保持されている Excel ワークブックをメモリ内ストリームに書き込みます。 |
| [writeWorkbookStream(byte[] ms)](#writeWorkbookStream-byte---) | ユーザーが指定した値で内部に保持されている Excel ワークブックを初期化します。 |
| [getDataSourceType()](#getDataSourceType--) | 外部データソースの場合は外部ワークブックのパスを表し、そうでない場合は null です。 |
| [getExternalWorkbookPath()](#getExternalWorkbookPath--) | チャートのデータソースを表します。 |
| [getEmbeddedWorkbookType()](#getEmbeddedWorkbookType--) | 埋め込みワークブックのタイプを取得します。 |
| [getRange()](#getRange--) | チャート データ範囲を取得します。 |
| [setRange(String formula)](#setRange-java.lang.String-) | チャート データ範囲を設定します。 |
| [setExternalWorkbook(String workbookPath)](#setExternalWorkbook-java.lang.String-) | 外部ワークブックをチャートのデータソースとして設定します。 |
| [setExternalWorkbook(String workbookPath, boolean updateChartData)](#setExternalWorkbook-java.lang.String-boolean-) | 外部ワークブックをチャートのデータソースとして設定します。 |
| [switchRowColumn()](#switchRowColumn--) | 軸上のデータを入れ替えます。 |

### getChartDataWorkbook() {#getChartDataWorkbook--}
```
public final IChartDataWorkbook getChartDataWorkbook()
```

チャートシリーズまたはカテゴリで使用されるセルを作成するためのセルファクトリを取得します。読み取り専用 [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)。

**戻り値:**  
[IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)

### getSeries() {#getSeries--}
```
public final IChartSeriesCollection getSeries()
```

シリーズを取得します。読み取り専用 [IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)。

**戻り値:**  
[IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)

### getSeriesGroups() {#getSeriesGroups--}
```
public final IChartSeriesGroupCollection getSeriesGroups()
```

シリーズのグループを取得します。読み取り専用 [IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection)。

--------------------

1) 各シリーズグループは組み合わせ可能なタイプのシリーズを含みます。組み合わせ可能なシリーズタイプのグループは **CombinableSeriesTypesGroup** enum で定義および説明されています。また、各グループは一次軸上にプロットされるシリーズまたは二次軸上にプロットされるシリーズのいずれかを含みます（同一グループ内で両方は含みません）。したがって、シリーズのグルーピングの原則は、上記のタイプグループと一次/二次プロットタイプによるグルーピングです。2) シリーズグループは、グループ内のすべてのシリーズに共通するいくつかのプロパティ（「シリーズ グループ プロパティ」）を含みます。**ChartSeriesGroup** クラスの「シリーズ グループ プロパティ」は 読み書き可能 です。各「シリーズ グループ プロパティ」には、**ChartSeries** クラスで読み取り専用の投影が存在する場合があります。

**戻り値:**  
[IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection)

### getCategories() {#getCategories--}
```
public final IChartCategoryCollection getCategories()
```

一次カテゴリを取得します（または、\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) プロパティが false の場合は一次および二次の両方のカテゴリを取得します）。読み取り専用 [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)。

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // 関連するカテゴリは series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // 関連するカテゴリは series.getChart().getChartData().getCategories()
>  }
> ```

--------------------

\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) プロパティが false の場合、\#getSecondaryCategories.getSecondaryCategories プロパティは null を返し、この \#getCategories.getCategories プロパティのデータが一次と二次のシリーズの両方に使用されます。プロパティが true の場合、\#getSecondaryCategories.getSecondaryCategories のデータが二次シリーズに、\#getCategories.getCategories のデータが一次シリーズに使用されます。

**戻り値:**  
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)

### getUseSecondaryCategories() {#getUseSecondaryCategories--}
```
public final boolean getUseSecondaryCategories()
```

false の場合、\#getSecondaryCategories.getSecondaryCategories プロパティは null を返し、\#getCategories.getCategories プロパティのデータが一次と二次のシリーズの両方に使用されます。true の場合、\#getSecondaryCategories.getSecondaryCategories のデータが二次シリーズに、\#getCategories.getCategories のデータが一次シリーズに使用されます。読み書き可能な boolean。

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // 関連するカテゴリは series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // 関連するカテゴリは series.getChart().getChartData().getCategories()
>  }
> ```

**戻り値:**  
boolean

### setUseSecondaryCategories(boolean value) {#setUseSecondaryCategories-boolean-}
```
public final void setUseSecondaryCategories(boolean value)
```

false の場合、\#getSecondaryCategories.getSecondaryCategories プロパティは null を返し、\#getCategories.getCategories プロパティのデータが一次と二次のシリーズの両方に使用されます。true の場合、\#getSecondaryCategories.getSecondaryCategories のデータが二次シリーズに、\#getCategories.getCategories のデータが一次シリーズに使用されます。読み書き可能な boolean。

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // 関連するカテゴリは series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // 関連するカテゴリは series.getChart().getChartData().getCategories()
>  }
> ```

**パラメータ:**  
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getSecondaryCategories() {#getSecondaryCategories--}
```
public final IChartCategoryCollection getSecondaryCategories()
```

二次カテゴリを取得します（\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) プロパティが true の場合）。読み取り専用 [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)。

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // 関連するカテゴリは series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // 関連するカテゴリは series.getChart().getChartData().getCategories()
>  }
> ```

--------------------

\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) プロパティが false の場合、この (\#getSecondaryCategories.getSecondaryCategories) プロパティは null を返し、\#getCategories.getCategories プロパティのデータが一次と二次のシリーズの両方に使用されます。プロパティが true の場合、この \#getSecondaryCategories.getSecondaryCategories のデータが二次シリーズに、\#getCategories.getCategories のデータが一次シリーズに使用されます。

**戻り値:**  
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)

### readWorkbookStream() {#readWorkbookStream--}
```
public final byte[] readWorkbookStream()
```

内部に保持されている Excel ワークブックをメモリ内ストリームに書き込みます。

**戻り値:**  
byte[] - 内部に保持されている Excel ワークブックのコピーを含むバイト配列のインスタンスを返します。

### writeWorkbookStream(byte[] ms) {#writeWorkbookStream-byte---}
```
public final void writeWorkbookStream(byte[] ms)
```

ユーザーが指定した値で内部に保持されている Excel ワークブックを初期化します。

**パラメータ:**  
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| ms | byte[] | ユーザーが提供した、Excel ワークブック全体を含むストリームです。 |

### getDataSourceType() {#getDataSourceType--}
```
public final int getDataSourceType()
```

外部データソースの場合は外部ワークブックのパスを表し、そうでない場合は null です。

**戻り値:**  
int

### getExternalWorkbookPath() {#getExternalWorkbookPath--}
```
public final String getExternalWorkbookPath()
```

チャートのデータソースを表します。

**戻り値:**  
java.lang.String

### getEmbeddedWorkbookType() {#getEmbeddedWorkbookType--}
```
public final int getEmbeddedWorkbookType()
```

埋め込みワークブックのタイプを取得します。**DataSourceType** (\#getDataSourceType.getDataSourceType) が **[ChartDataSourceType.ExternalWorkbook](../../com.aspose.slides/chartdatasourcetype\#ExternalWorkbook)** の場合、[WorkbookType.NotDefined](../../com.aspose.slides/workbooktype\#NotDefined) を返します。読み取り専用 [WorkbookType](../../com.aspose.slides/workbooktype)。

**戻り値:**  
int

### getRange() {#getRange--}
```
public final String getRange()
```

チャート データ範囲を取得します。

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.PercentsStackedBar, 0, 0, 100, 100);
>       String result = ((ChartData)chart.getChartData()).getRange();
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```

**戻り値:**  
java.lang.String - セル データ範囲の数式。例: "Sheet1!$A$1:$C$4"

### setRange(String formula) {#setRange-java.lang.String-}
```
public final void setRange(String formula)
```

チャート データ範囲を設定します。新しいデータ範囲に基づいてシリーズおよびカテゴリが更新されます。データ範囲内のシリーズ数がチャート データのシリーズ数を超える場合、現在のコレクションの最後のシリーズと同じタイプの追加シリーズがコレクションの末尾に追加されます。

**パラメータ:**  
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| formula | java.lang.String | セル データ範囲の数式。例: "Sheet1!$A$1:$C$4"、"SomeSheetName!A1:B100"、"Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5"。 |

### setExternalWorkbook(String workbookPath) {#setExternalWorkbook-java.lang.String-}
```
public final void setExternalWorkbook(String workbookPath)
```

外部ワークブックをチャートのデータソースとして設定します。チャート データは対象ワークブックから更新されます。

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>     IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.Pie, 50, 50, 400, 600, true);
>     IChartData chartData = chart.getChartData();
>     ((ChartData)chartData).setExternalWorkbook("../../workbook.xlsx");
>  } finally {
>     if (pres != null) pres.dispose();
>  }
> ```

**パラメータ:**  
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| workbookPath | java.lang.String | 対象ワークブックへのパス |

### setExternalWorkbook(String workbookPath, boolean updateChartData) {#setExternalWorkbook-java.lang.String-boolean-}
```
public final void setExternalWorkbook(String workbookPath, boolean updateChartData)
```

外部ワークブックをチャートのデータソースとして設定します。

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.Pie, 50, 50, 400, 600, true);
>      IChartData chartData = chart.getChartData();
>      ((ChartData).setExternalWorkbook("http://path/doesnt/exists", false);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**パラメータ:**  
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| workbookPath | java.lang.String | 対象ワークブックへのパス |
| updateChartData | boolean | false の場合、ワークブック パスのみが更新され、チャート データは対象ワークブックから読み込まれません。対象ワークブックが存在しない、または利用できない場合に使用できます。true の場合、チャート データが対象ワークブックから更新されます。 |

### switchRowColumn() {#switchRowColumn--}
```
public final void switchRowColumn()
```

軸上のデータを入れ替えます。X 軸にプロットされていたデータが Y 軸へ、Y 軸にプロットされていたデータが X 軸へ移動します。