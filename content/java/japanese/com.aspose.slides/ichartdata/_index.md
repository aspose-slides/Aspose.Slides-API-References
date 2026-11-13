---
title: IChartData
second_title: Aspose.Slides for Java API Reference
description: Represents data used for a chart plotting.
type: docs
url: /ja/com.aspose.slides/ichartdata/
---```
public interface IChartData
```

チャート描画に使用されるデータを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getChartDataWorkbook()](#getChartDataWorkbook--) | チャートシリーズまたはカテゴリで使用されるセルを作成するためのセルファクトリを取得します。 |
| [getSeries()](#getSeries--) | シリーズを取得します。 |
| [getSeriesGroups()](#getSeriesGroups--) | シリーズのグループを取得します。 |
| [getCategories()](#getCategories--) | 主カテゴリを取得します（プロパティ (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) が false の場合は、主カテゴリと副カテゴリの両方を取得します）。 |
| [getUseSecondaryCategories()](#getUseSecondaryCategories--) | false の場合、(\#getSecondaryCategories.getSecondaryCategories) プロパティは null を返し、(\#getCategories.getCategories) プロパティのデータが主シリーズと副シリーズの両方に使用されます。 |
| [setUseSecondaryCategories(boolean value)](#setUseSecondaryCategories-boolean-) | false の場合、(\#getSecondaryCategories.getSecondaryCategories) プロパティは null を返し、(\#getCategories.getCategories) プロパティのデータが主シリーズと副シリーズの両方に使用されます。 |
| [getSecondaryCategories()](#getSecondaryCategories--) | プロパティ (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) が true の場合、二次カテゴリを取得します。 |
| [readWorkbookStream()](#readWorkbookStream--) | 内部に含まれる Excel ワークブックをメモリ内ストリームに書き込みます。 |
| [writeWorkbookStream(byte[] ms)](#writeWorkbookStream-byte---) | Initializes the internally contained Excel workbook with user-specified value. |
| [setRange(String formula)](#setRange-java.lang.String-) | チャートデータ範囲を設定します。 |
| [getRange()](#getRange--) | チャートデータ範囲を取得します。 |
| [getDataSourceType()](#getDataSourceType--) | チャートのデータソースを表します |
| [getExternalWorkbookPath()](#getExternalWorkbookPath--) | データソースが外部の場合は外部ワークブックのパスを表します。そうでない場合は null です |
| [getEmbeddedWorkbookType()](#getEmbeddedWorkbookType--) | 埋め込みワークブックのタイプを取得します。 |
| [switchRowColumn()](#switchRowColumn--) | 軸上のデータを入れ替えます。 |
| [setExternalWorkbook(String workbookPath)](#setExternalWorkbook-java.lang.String-) | 外部ワークブックをチャートのデータソースとして設定します。 |
| [setExternalWorkbook(String workbookPath, boolean updateChartData)](#setExternalWorkbook-java.lang.String-boolean-) | 外部ワークブックをチャートのデータソースとして設定します。 |
| [refreshData()](#refreshData--) | ソースワークブックから再読み込みしてチャートデータを更新します。 |
### getChartDataWorkbook() {#getChartDataWorkbook--}
```
public abstract IChartDataWorkbook getChartDataWorkbook()
```

内部に含まれるセルを作成するためのセルファクトリを取得します。読み取り専用 [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)。

**戻り値:**
[IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)
### getSeries() {#getSeries--}
```
public abstract IChartSeriesCollection getSeries()
```

シリーズを取得します。読み取り専用 [IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)。

**戻り値:**
[IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)
### getSeriesGroups() {#getSeriesGroups--}
```
public abstract IChartSeriesGroupCollection getSeriesGroups()
```

シリーズのグループを取得します。読み取り専用 [IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection)。

--------------------

1) 各シリーズグループは、組み合わせ可能なタイプのシリーズを含みます。組み合わせ可能なシリーズタイプのグループは CombinableSeriesTypesGroup enum で定義および記述されています。また、各シリーズグループは、主軸上にプロットされるシリーズまたは副軸上にプロットされるシリーズを含みます（同一グループ内で両方のケースはありません）。したがって、シリーズのグルーピングの原則は、前述のタイプグループと主/副プロットタイプによるグルーピングです。2) シリーズグループは、グループ内の各シリーズに共通するいくつかのシリーズプロパティ（「シリーズグループプロパティ」）を含みます。ChartSeriesGroup クラスの「Series group properties」は読み書き可能です。「シリーズグループプロパティ」の各項目は、ChartSeries クラスで読み取り専用として投影される可能性があります。

**戻り値:**
[IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection)
### getCategories() {#getCategories--}
```
public abstract IChartCategoryCollection getCategories()
```

主カテゴリを取得します（プロパティ (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) が false の場合は、主カテゴリと副カテゴリの両方を取得します）。読み取り専用 [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)。

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // 対応するカテゴリは series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // 対応するカテゴリは series.getChart().getChartData().getCategories()
>  }
> ```

--------------------

false の場合、(\#getSecondaryCategories.getSecondaryCategories) プロパティは null を返し、(\#getCategories.getCategories) プロパティのデータが主シリーズと副シリーズの両方に使用されます。true の場合、(\#getSecondaryCategories.getSecondaryCategories) プロパティのデータが副シリーズに使用され、(\#getCategories.getCategories) プロパティのデータが主シリーズに使用されます。

**戻り値:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
### getUseSecondaryCategories() {#getUseSecondaryCategories--}
```
public abstract boolean getUseSecondaryCategories()
```

false の場合、(\#getSecondaryCategories.getSecondaryCategories) プロパティは null を返し、(\#getCategories.getCategories) プロパティのデータが主シリーズと副シリーズの両方に使用されます。true の場合、(\#getSecondaryCategories.getSecondaryCategories) プロパティのデータが副シリーズに使用され、(\#getCategories.getCategories) プロパティのデータが主シリーズに使用されます。読み書き boolean。

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
public abstract void setUseSecondaryCategories(boolean value)
```

false の場合、(\#getSecondaryCategories.getSecondaryCategories) プロパティは null を返し、(\#getCategories.getCategories) プロパティのデータが主シリーズと副シリーズの両方に使用されます。true の場合、(\#getSecondaryCategories.getSecondaryCategories) プロパティのデータが副シリーズに使用され、(\#getCategories.getCategories) プロパティのデータが主シリーズに使用されます。読み書き boolean。

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
public abstract IChartCategoryCollection getSecondaryCategories()
```

プロパティ (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) が true の場合、二次カテゴリを取得します。読み取り専用 [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)。

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

false の場合、(\#getSecondaryCategories.getSecondaryCategories) プロパティは null を返し、(\#getCategories.getCategories) プロパティのデータが主シリーズと副シリーズの両方に使用されます。true の場合、(\#getSecondaryCategories.getSecondaryCategories) プロパティのデータが副シリーズに使用され、(\#getCategories.getCategories) プロパティのデータが主シリーズに使用されます。

**戻り値:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
### readWorkbookStream() {#readWorkbookStream--}
```
public abstract byte[] readWorkbookStream()
```

内部に含まれる Excel ワークブックをメモリ内ストリームに書き込みます。

**戻り値:**
byte[] - 内部に含まれる Excel ワークブックのコピーを含むバイト配列を返します。
### writeWorkbookStream(byte[] ms) {#writeWorkbookStream-byte---}
```
public abstract void writeWorkbookStream(byte[] ms)
```

内部に含まれる Excel ワークブックをユーザー指定の値で初期化します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| ms | byte[] | ユーザーが提供した、Excel ワークブック全体を含むストリーム。 |

### setRange(String formula) {#setRange-java.lang.String-}
```
public abstract void setRange(String formula)
```

チャートデータ範囲を設定します。シリーズとカテゴリは新しいデータ範囲に基づいて更新されます。データ範囲内のシリーズ数がチャートデータのシリーズ数を超える場合、現在のコレクションの最後のシリーズと同じタイプの追加シリーズがコレクションの末尾に追加されます。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| formula | java.lang.String | セルデータ範囲の式。例: "Sheet1!$A$1:$C$4" , "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

### getRange() {#getRange--}
```
public abstract String getRange()
```

チャートデータ範囲を取得します。

--------------------

> ```
> Presentation pres = new Presentation();
>  {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.PercentsStackedBar, 100, 100, 500, 400);
>      String result = ((ChartData)chart.getChartData()).getRange();
>  }
> ```


**戻り値:**
java.lang.String - セルデータ範囲の式。例: "Sheet1!$A$1:$C$4"
### getDataSourceType() {#getDataSourceType--}
```
public abstract int getDataSourceType()
```

チャートのデータソースを表します

**戻り値:**
int
### getExternalWorkbookPath() {#getExternalWorkbookPath--}
```
public abstract String getExternalWorkbookPath()
```

データソースが外部の場合は外部ワークブックのパスを表します。そうでない場合は null です

**戻り値:**
java.lang.String
### getEmbeddedWorkbookType() {#getEmbeddedWorkbookType--}
```
public abstract int getEmbeddedWorkbookType()
```

埋め込みワークブックのタイプを取得します。DataSourceType (\#getDataSourceType.getDataSourceType) が [ChartDataSourceType.ExternalWorkbook](../../com.aspose.slides/chartdatasourcetype\#ExternalWorkbook) の場合は [WorkbookType.NotDefined](../../com.aspose.slides/workbooktype\#NotDefined) を返します。読み取り専用 [WorkbookType](../../com.aspose.slides/workbooktype)。

**戻り値:**
int
### switchRowColumn() {#switchRowColumn--}
```
public abstract void switchRowColumn()
```

軸上のデータを入れ替えます。X 軸上でチャート化されているデータは Y 軸に移動し、その逆も同様です。

### setExternalWorkbook(String workbookPath) {#setExternalWorkbook-java.lang.String-}
```
public abstract void setExternalWorkbook(String workbookPath)
```

外部ワークブックをチャートのデータソースとして設定します。チャートデータは対象ワークブックから更新されます。

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>     IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.Pie, 50, 50, 400, 600, true);
>     IChartData chartData = chart.getChartData();
>     ((ChartData)chartData).setExternalWorkbook("../../workbook.xlsx");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| workbookPath | java.lang.String | 対象ワークブックへのパス |

### setExternalWorkbook(String workbookPath, boolean updateChartData) {#setExternalWorkbook-java.lang.String-boolean-}
```
public abstract void setExternalWorkbook(String workbookPath, boolean updateChartData)
```

外部ワークブックをチャートのデータソースとして設定します。

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>     IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.Pie, 50, 50, 400, 600, true);
>     IChartData chartData = chart.getChartData();
>     ((ChartData)chartData).setExternalWorkbook("http://path/doesnt/exists", false);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| workbookPath | java.lang.String | 対象ワークブックへのパス |
| updateChartData | boolean | false の場合はワークブックパスのみが更新され、チャートデータはロードおよび更新されません。対象ワークブックが存在しない、または利用できない場合に使用できます。true の場合はチャートデータが対象ワークブックから更新されます。 |

### refreshData() {#refreshData--}
```
public abstract void refreshData()
```

ソースワークブックから再読み込みしてチャートデータを更新します。

--------------------

> ```
> Presentation presentation = new Presentation("presentationWithChart.pptx");
>  try {
>      IChart chart = (IChart)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      chart.getChartData().refreshData();
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```