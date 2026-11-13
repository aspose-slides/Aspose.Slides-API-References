---
title: ChartData
second_title: Aspose.Slides for Java API リファレンス
description: チャート描画に使用されるデータを表します。
type: docs
url: /ja/com.aspose.slides/chartdata/
---
**継承:**  
java.lang.Object, com.aspose.slides.DomObject

**実装されたすべてのインターフェイス:**  
[com.aspose.slides.IChartData](../../com.aspose.slides/ichartdata)  
```
public class ChartData extends DomObject<Chart> implements IChartData
```

チャート描画に使用されるデータを表します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getChartDataWorkbook()](#getChartDataWorkbook--) | チャートシリーズまたはカテゴリで使用されるセルを作成するためのセルファクトリを取得します。 |
| [getSeries()](#getSeries--) | シリーズを取得します。 |
| [getSeriesGroups()](#getSeriesGroups--) | シリーズのグループを取得します。 |
| [getCategories()](#getCategories--) | プライマリカテゴリ（または、\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) プロパティが false の場合はプライマリおよびセカンダリの両方のカテゴリ）を取得します。 |
| [getUseSecondaryCategories()](#getUseSecondaryCategories--) | false の場合、\#getSecondaryCategories.getSecondaryCategories プロパティは null を返し、\#getCategories.getCategories プロパティのデータはプライマリとセカンダリのシリーズの両方に使用されます。 |
| [setUseSecondaryCategories(boolean value)](#setUseSecondaryCategories-boolean-) | false の場合、\#getSecondaryCategories.getSecondaryCategories プロパティは null を返し、\#getCategories.getCategories プロパティのデータはプライマリとセカンダリのシリーズの両方に使用されます。 |
| [getSecondaryCategories()](#getSecondaryCategories--) | プロパティが true の場合、セカンダリカテゴリを取得します。 |
| [readWorkbookStream()](#readWorkbookStream--) | 内部に含まれる Excel ワークブックをメモリ内ストリームに書き出します。 |
| [writeWorkbookStream(byte[] ms)](#writeWorkbookStream-byte---) | ユーザーが指定した値で内部に含まれる Excel ワークブックを初期化します。 |
| [getDataSourceType()](#getDataSourceType--) | 外部データ ソースの場合は外部ワークブックのパスを表し、そうでない場合は null です。 |
| [getExternalWorkbookPath()](#getExternalWorkbookPath--) | チャートのデータソースを表します。 |
| [getEmbeddedWorkbookType()](#getEmbeddedWorkbookType--) | 埋め込みワークブックのタイプを取得します。 |
| [getRange()](#getRange--) | チャートデータの範囲を取得します。 |
| [setRange(String formula)](#setRange-java.lang.String-) | チャートデータの範囲を設定します。 |
| [setExternalWorkbook(String workbookPath)](#setExternalWorkbook-java.lang.String-) | 外部ワークブックをチャートのデータソースとして設定します。 |
| [setExternalWorkbook(String workbookPath, boolean updateChartData)](#setExternalWorkbook-java.lang.String-boolean-) | 外部ワークブックをチャートのデータソースとして設定します。 |
| [refreshData()](#refreshData--) | ソースワークブックから再読込してチャートデータを更新します。 |
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

1) Each group of series contains series with combinable types. Groups of combinable series types defined and described with CombinableSeriesTypesGroup enum. Also each group of series contains series witch is plotted whether on primary axes or on secondary axes (not both cases in one group). So, principle of series grouping is a grouping by type groups mentioned above and by primary/secondary plotting type. 2) Group of series contains some series properies whitch is common for each series in group ("series group properties"). "Series group properties" in ChartSeriesGroup class is read/write. Each of "series group properties" can have a read-only projection in ChartSeries class.

**戻り値:**  
[IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection)

### getCategories() {#getCategories--}
```
public final IChartCategoryCollection getCategories()
```

プライマリカテゴリ（または、\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) プロパティが false の場合はプライマリおよびセカンダリの両方のカテゴリ）を取得します。読み取り専用 [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)。

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // related categories are series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // related categories are series.getChart().getChartData().getCategories()
>  }
> ```

--------------------

\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) プロパティが false の場合、\#getSecondaryCategories.getSecondaryCategories プロパティは null を返し、\#getCategories.getCategories プロパティのデータはプライマリとセカンダリのシリーズの両方に使用されます。プロパティが true の場合、\#getSecondaryCategories.getSecondaryCategories プロパティのデータはセカンダリシリーズに、\#getCategories.getCategories プロパティのデータはプライマリシリーズに使用されます。

**戻り値:**  
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)

### getUseSecondaryCategories() {#getUseSecondaryCategories--}
```
public final boolean getUseSecondaryCategories()
```

false の場合、\#getSecondaryCategories.getSecondaryCategories プロパティは null を返し、\#getCategories.getCategories プロパティのデータはプライマリとセカンダリのシリーズの両方に使用されます。true の場合、\#getSecondaryCategories.getSecondaryCategories プロパティのデータはセカンダリシリーズに、\#getCategories.getCategories プロパティのデータはプライマリシリーズに使用されます。読み書き可能な boolean。

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

false の場合、\#getSecondaryCategories.getSecondaryCategories プロパティは null を返し、\#getCategories.getCategories プロパティのデータはプライマリとセカンダリのシリーズの両方に使用されます。true の場合、\#getSecondaryCategories.getSecondaryCategories プロパティのデータはセカンダリシリーズに、\#getCategories.getCategories プロパティのデータはプライマリシリーズに使用されます。読み書き可能な boolean。

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
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getSecondaryCategories() {#getSecondaryCategories--}
```
public final IChartCategoryCollection getSecondaryCategories()
```

セカンダリカテゴリを取得します（プロパティが true の場合）。読み取り専用 [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)。

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

\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) プロパティが false の場合、この \#getSecondaryCategories.getSecondaryCategories プロパティは null を返し、\#getCategories.getCategories プロパティのデータはプライマリとセカンダリのシリーズの両方に使用されます。プロパティが true の場合、この \#getSecondaryCategories.getSecondaryCategories プロパティのデータはセカンダリシリーズに、\#getCategories.getCategories プロパティのデータはプライマリシリーズに使用されます。

**戻り値:**  
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)

### readWorkbookStream() {#readWorkbookStream--}
```
public final byte[] readWorkbookStream()
```

内部に含まれる Excel ワークブックをメモリ内ストリームに書き出します。

**戻り値:**  
byte[] - 内部に含まれる Excel ワークブックのコピーを含むバイト配列のインスタンスを返します。

### writeWorkbookStream(byte[] ms) {#writeWorkbookStream-byte---}
```
public final void writeWorkbookStream(byte[] ms)
```

ユーザーが指定した値で内部に含まれる Excel ワークブックを初期化します。

**パラメータ:**  
| Parameter | Type | Description |
| --- | --- | --- |
| ms | byte[] | ユーザーが提供した、Excel ワークブック全体を含むストリームです。 |

### getDataSourceType() {#getDataSourceType--}
```
public final int getDataSourceType()
```

外部データ ソースの場合は外部ワークブックのパスを表し、そうでない場合は null です。

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

埋め込みワークブックのタイプを取得します。DataSourceType（\#getDataSourceType.getDataSourceType）が [ChartDataSourceType.ExternalWorkbook](../../com.aspose.slides/chartdatasourcetype\#ExternalWorkbook) の場合は [WorkbookType.NotDefined](../../com.aspose.slides/workbooktype\#NotDefined) を返します。読み取り専用 [WorkbookType](../../com.aspose.slides/workbooktype)。

**戻り値:**  
int

### getRange() {#getRange--}
```
public final String getRange()
```

チャートデータの範囲を取得します。

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
java.lang.String - セルデータ範囲の数式。例: "Sheet1!$A$1:$C$4"

### setRange(String formula) {#setRange-java.lang.String-}
```
public final void setRange(String formula)
```

チャートデータの範囲を設定します。新しいデータ範囲に基づいてシリーズとカテゴリが更新されます。データ範囲内のシリーズ数がチャートデータ内のシリーズ数を超える場合、現在のコレクションの最後のシリーズと同じタイプの追加シリーズがコレクションの末尾に追加されます。

**パラメータ:**  
| Parameter | Type | Description |
| --- | --- | --- |
| formula | java.lang.String | セルデータ範囲の数式。例: "Sheet1!$A$1:$C$4" , "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

### setExternalWorkbook(String workbookPath) {#setExternalWorkbook-java.lang.String-}
```
public final void setExternalWorkbook(String workbookPath)
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
>     if (pres != null) pres.dispose();
>  }
> ```

**パラメータ:**  
| Parameter | Type | Description |
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
| Parameter | Type | Description |
| --- | --- | --- |
| workbookPath | java.lang.String | 対象ワークブックへのパス |
| updateChartData | boolean | false の場合、ワークブックパスだけが更新され、チャートデータは対象ワークブックから読み込まれません。対象ワークブックが存在しない、または利用できない場合に使用できます。true の場合、チャートデータは対象ワークブックから更新されます。 |

### refreshData() {#refreshData--}
```
public final void refreshData()
```

ソースワークブックから再読込してチャートデータを更新します。

--------------------

> ```
> Presentation presentation = new Presentation("presentationWithChart.pptx");
>  try {
>      IChart chart = (IChart)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      chart.getChartData().refreshData();
>  } finally {
>      presentation.dispose();
>  }
> ```

### switchRowColumn() {#switchRowColumn--}
```
public final void switchRowColumn()
```

軸上のデータを入れ替えます。X 軸にプロットされていたデータが Y 軸に、Y 軸にプロットされていたデータが X 軸に移動します。