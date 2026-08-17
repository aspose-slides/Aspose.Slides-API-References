---
title: IChartData
second_title: Aspose.Slides for Java API Reference
description: Represents data used for a chart plotting.
type: docs
url: /ja/com.aspose.slides/ichartdata/
---```
public interface IChartData
```

チャートのプロットに使用されるデータを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getChartDataWorkbook()](#getChartDataWorkbook--) | チャートシリーズまたはカテゴリに使用されるセルを作成するためのセルファクトリを取得します。 |
| [getSeries()](#getSeries--) | シリーズを取得します。 |
| [getSeriesGroups()](#getSeriesGroups--) | シリーズのグループを取得します。 |
| [getCategories()](#getCategories--) | プライマリカテゴリ（または、(\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) プロパティが false の場合はプライマリおよびセカンダリカテゴリの両方）を取得します。 |
| [getUseSecondaryCategories()](#getUseSecondaryCategories--) | false の場合、(\#getSecondaryCategories.getSecondaryCategories) プロパティは null を返し、(\#getCategories.getCategories) プロパティのデータはプライマリとセカンダリの両方のシリーズに使用されます。 |
| [setUseSecondaryCategories(boolean value)](#setUseSecondaryCategories-boolean-) | false の場合、(\#getSecondaryCategories.getSecondaryCategories) プロパティは null を返し、(\#getCategories.getCategories) プロパティのデータはプライマリとセカンダリの両方のシリーズに使用されます。 |
| [getSecondaryCategories()](#getSecondaryCategories--) | (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) プロパティが true の場合、セカンダリカテゴリを取得します。 |
| [readWorkbookStream()](#readWorkbookStream--) | 内部に含まれる Excel ブックをメモリ内ストリームに書き込みます。 |
| [writeWorkbookStream(byte[] ms)](#writeWorkbookStream-byte---) | 内部に含まれる Excel ブックをユーザー指定の値で初期化します。 |
| [setRange(String formula)](#setRange-java.lang.String-) | チャートのデータ範囲を設定します。 |
| [getRange()](#getRange--) | チャートのデータ範囲を取得します。 |
| [getDataSourceType()](#getDataSourceType--) | チャートのデータソースを表します。 |
| [getExternalWorkbookPath()](#getExternalWorkbookPath--) | データソースが外部の場合は外部ブックパスを表し、そうでない場合は null を返します。 |
| [getEmbeddedWorkbookType()](#getEmbeddedWorkbookType--) | 埋め込みブックのタイプを取得します。 |
| [switchRowColumn()](#switchRowColumn--) | 軸上のデータを入れ替えます。 |
| [setExternalWorkbook(String workbookPath)](#setExternalWorkbook-java.lang.String-) | 外部ブックをチャートのデータソースとして設定します。 |
| [setExternalWorkbook(String workbookPath, boolean updateChartData)](#setExternalWorkbook-java.lang.String-boolean-) | 外部ブックをチャートのデータソースとして設定します。 |
### getChartDataWorkbook() {#getChartDataWorkbook--}
```
public abstract IChartDataWorkbook getChartDataWorkbook()
```


チャートシリーズまたはカテゴリに使用されるセルを作成するためのセルファクトリを取得します。読み取り専用 [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)。

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

1) 各シリーズグループは、組み合わせ可能なタイプのシリーズを含みます。組み合わせ可能なシリーズタイプのグループは CombinableSeriesTypesGroup 列挙体で定義および記述されています。また、各シリーズグループは、プライマリ軸またはセカンダリ軸のいずれかにプロットされるシリーズを含みます（同一グループ内で両方にプロットされることはありません）。したがって、シリーズのグルーピングの原則は、上記のタイプグループとプライマリ/セカンダリのプロットタイプによるグルーピングです。2) シリーズグループは、グループ内の各シリーズに共通するいくつかのシリーズプロパティ（「シリーズグループプロパティ」）を含みます。ChartSeriesGroup クラスの「シリーズグループプロパティ」は読み書き可能です。各「シリーズグループプロパティ」には、ChartSeries クラスで読み取り専用の投影が存在する場合があります。

**戻り値:**
[IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection)
### getCategories() {#getCategories--}
```
public abstract IChartCategoryCollection getCategories()
```


プライマリカテゴリ（または、(\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) プロパティが false の場合はプライマリおよびセカンダリカテゴリの両方）を取得します。読み取り専用 [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)。

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // 関連するカテゴリは series.getChart().getChartData().getSecondaryCategories() です
>  }
>  else
>  {
>      // 関連するカテゴリは series.getChart().getChartData().getCategories() です
>  }
```

--------------------

(\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) プロパティが false の場合、(\#getSecondaryCategories.getSecondaryCategories) プロパティは null を返し、この (\#getCategories.getCategories) プロパティのデータはプライマリおよびセカンダリシリーズの両方に使用されます。(\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) プロパティが true の場合、(\#getSecondaryCategories.getSecondaryCategories) プロパティのデータはセカンダリシリーズに、そしてこの (\#getCategories.getCategories) プロパティのデータはプライマリシリーズに使用されます。

**戻り値:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
### getUseSecondaryCategories() {#getUseSecondaryCategories--}
```
public abstract boolean getUseSecondaryCategories()
```


false の場合、(\#getSecondaryCategories.getSecondaryCategories) プロパティは null を返し、(\#getCategories.getCategories) プロパティのデータはプライマリおよびセカンダリシリーズの両方に使用されます。true の場合、(\#getSecondaryCategories.getSecondaryCategories) プロパティのデータはセカンダリシリーズに、(\#getCategories.getCategories) プロパティのデータはプライマリシリーズに使用されます。読み書き可能な boolean。

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // 関連するカテゴリは series.getChart().getChartData().getSecondaryCategories() です
>  }
>  else
>  {
>      // 関連するカテゴリは series.getChart().getChartData().getCategories() です
>  }
> ```

**戻り値:**
boolean
### setUseSecondaryCategories(boolean value) {#setUseSecondaryCategories-boolean-}
```
public abstract void setUseSecondaryCategories(boolean value)
```


false の場合、(\#getSecondaryCategories.getSecondaryCategories) プロパティは null を返し、(\#getCategories.getCategories) プロパティのデータはプライマリおよびセカンダリシリーズの両方に使用されます。true の場合、(\#getSecondaryCategories.getSecondaryCategories) プロパティのデータはセカンダリシリーズに、(\#getCategories.getCategories) プロパティのデータはプライマリシリーズに使用されます。読み書き可能な boolean。

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // 関連するカテゴリは series.getChart().getChartData().getSecondaryCategories() です
>  }
>  else
>  {
>      // 関連するカテゴリは series.getChart().getChartData().getCategories() です
>  }
> ```

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |
### getSecondaryCategories() {#getSecondaryCategories--}
```
public abstract IChartCategoryCollection getSecondaryCategories()
```


(\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) プロパティが true の場合、セカンダリカテゴリを取得します。読み取り専用 [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)。

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // 関連するカテゴリは series.getChart().getChartData().getSecondaryCategories() です
>  }
>  else
>  {
>      // 関連するカテゴリは series.getChart().getChartData().getCategories() です
>  }
> ```


--------------------

(\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) プロパティが false の場合、この (\#getSecondaryCategories.getSecondaryCategories) プロパティは null を返し、(\#getCategories.getCategories) プロパティのデータはプライマリおよびセカンダリシリーズの両方に使用されます。(\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) プロパティが true の場合、この (\#getSecondaryCategories.getSecondaryCategories) プロパティのデータはセカンダリシリーズに、(\#getCategories.getCategories) プロパティのデータはプライマリシリーズに使用されます。

**戻り値:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
### readWorkbookStream() {#readWorkbookStream--}
```
public abstract byte[] readWorkbookStream()
```


内部に含まれる Excel ブックをメモリ内ストリームに書き込みます。

**戻り値:**
byte[] - 内部に含まれる Excel ブックのコピーを含むバイト配列を返します。
### writeWorkbookStream(byte[] ms) {#writeWorkbookStream-byte---}
```
public abstract void writeWorkbookStream(byte[] ms)
```


内部に含まれる Excel ブックをユーザー指定の値で初期化します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| ms | byte[] | ユーザーが提供した、Excel ブック全体を含むストリーム。 |
### setRange(String formula) {#setRange-java.lang.String-}
```
public abstract void setRange(String formula)
```


チャートのデータ範囲を設定します。シリーズとカテゴリは新しいデータ範囲に基づいて更新されます。データ範囲内のシリーズ数がチャートデータ内のシリーズ数より多い場合、現在のコレクションの最後のシリーズと同じタイプの追加シリーズがコレクションの末尾に追加されます。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| formula | java.lang.String | セルのデータ範囲の式。例: "Sheet1!$A$1:$C$4" , "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5"。 |
### getRange() {#getRange--}
```
public abstract String getRange()
```


チャートのデータ範囲を取得します。

--------------------

> ```
> Presentation pres = new Presentation();
>  {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.PercentsStackedBar, 100, 100, 500, 400);
>      String result = ((ChartData)chart.getChartData()).getRange();
>  }
> ```

**戻り値:**
java.lang.String - セルのデータ範囲式。例: "Sheet1!$A$1:$C$4"
### getDataSourceType() {#getDataSourceType--}
```
public abstract int getDataSourceType()
```


チャートのデータソースを表します。

**戻り値:**
int
### getExternalWorkbookPath() {#getExternalWorkbookPath--}
```
public abstract String getExternalWorkbookPath()
```


データソースが外部の場合は外部ブックパスを表し、そうでない場合は null を返します。

**戻り値:**
java.lang.String
### getEmbeddedWorkbookType() {#getEmbeddedWorkbookType--}
```
public abstract int getEmbeddedWorkbookType()
```


埋め込みブックのタイプを取得します。DataSourceType (\#getDataSourceType.getDataSourceType) が [ChartDataSourceType.ExternalWorkbook](../../com.aspose.slides/chartdatasourcetype\#ExternalWorkbook) の場合は [WorkbookType.NotDefined](../../com.aspose.slides/workbooktype\#NotDefined) を返します。読み取り専用 [WorkbookType](../../com.aspose.slides/workbooktype)。

**戻り値:**
int
### switchRowColumn() {#switchRowColumn--}
```
public abstract void switchRowColumn()
```


軸上のデータを入れ替えます。X 軸でチャート化されたデータは Y 軸へ、逆も同様に移動します。
### setExternalWorkbook(String workbookPath) {#setExternalWorkbook-java.lang.String-}
```
public abstract void setExternalWorkbook(String workbookPath)
```


外部ブックをチャートのデータソースとして設定します。チャートデータは対象ブックから更新されます。

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

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| workbookPath | java.lang.String | 対象ブックへのパス |
### setExternalWorkbook(String workbookPath, boolean updateChartData) {#setExternalWorkbook-java.lang.String-boolean-}
```
public abstract void setExternalWorkbook(String workbookPath, boolean updateChartData)
```


外部ブックをチャートのデータソースとして設定します。

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


**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| workbookPath | java.lang.String | 対象ブックへのパス |
| updateChartData | boolean | false の場合、ブックパスのみが更新され、チャートデータは対象ブックからロードおよび更新されません。対象ブックが存在しない場合や利用できない場合に使用できます。true の場合、チャートデータは対象ブックから更新されます。 |