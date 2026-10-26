---
title: ISpreadsheetOptions
second_title: Aspose.Slides for Android Java API リファレンス
description: 追加のスプレッドシート動作を指定するために使用できるオプションを表します。
type: docs
url: /ja/com.aspose.slides/ispreadsheetoptions/
---```
public interface ISpreadsheetOptions
```

追加のスプレッドシート動作を指定するために使用できるオプションを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getPreferredCulture()](#getPreferredCulture--) | ダブルバイト文字セット（DBCS）を使用する言語向けの一部関数の計算に使用する優先カルチャ情報を取得または設定します。 |
| [setPreferredCulture(Locale value)](#setPreferredCulture-java.util.Locale-) | ダブルバイト文字セット（DBCS）を使用する言語向けの一部関数の計算に使用する優先カルチャ情報を取得または設定します。 |
| [getRecoverWorkbookFromChartCache()](#getRecoverWorkbookFromChartCache--) | チャートのデータ ソースが外部ブックで利用できない場合、チャート キャッシュから復元されます。 |
| [setRecoverWorkbookFromChartCache(boolean value)](#setRecoverWorkbookFromChartCache-boolean-) | チャートのデータ ソースが外部ブックで利用できない場合、チャート キャッシュから復元されます。 |
### getPreferredCulture() {#getPreferredCulture--}
```
public abstract Locale getPreferredCulture()
```


ダブルバイト文字セット（DBCS）を使用する言語向けの一部関数の計算に使用する優先カルチャ情報を取得または設定します。

**戻り値:**
java.util.Locale
### setPreferredCulture(Locale value) {#setPreferredCulture-java.util.Locale-}
```
public abstract void setPreferredCulture(Locale value)
```


ダブルバイト文字セット（DBCS）を使用する言語向けの一部関数の計算に使用する優先カルチャ情報を取得または設定します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.util.Locale |  |

### getRecoverWorkbookFromChartCache() {#getRecoverWorkbookFromChartCache--}
```
public abstract boolean getRecoverWorkbookFromChartCache()
```


チャートのデータ ソースが外部ブックで利用できない場合、チャート キャッシュから復元されます。

--------------------

> ```
> Example:
>   
>   SpreadsheetOptions spreadOptions = new SpreadsheetOptions();
>   spreadOptions.setRecoverWorkbookFromChartCache(true);
> 
>   LoadOptions loadOptions = new LoadOptions();
>   loadOptions.setSpreadsheetOptions(spreadOptions);
> 
>   Presentation pres = new Presentation("Presentation.pptx", loadOptions);
>   try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IChartDataWorkbook recoveredWorkbook = chart.getChartData().getChartDataWorkbook();
>   } finally {
>      if (pres != null) pres.dispose();
>   }
> ```

**戻り値:**
boolean
### setRecoverWorkbookFromChartCache(boolean value) {#setRecoverWorkbookFromChartCache-boolean-}
```
public abstract void setRecoverWorkbookFromChartCache(boolean value)
```


チャートのデータ ソースが外部ブックで利用できない場合、チャート キャッシュから復元されます。

--------------------

> ```
> Example:
>   
>   SpreadsheetOptions spreadOptions = new SpreadsheetOptions();
>   spreadOptions.setRecoverWorkbookFromChartCache(true);
> 
>   LoadOptions loadOptions = new LoadOptions();
>   loadOptions.setSpreadsheetOptions(spreadOptions);
> 
>   Presentation pres = new Presentation("Presentation.pptx", loadOptions);
>   try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IChartDataWorkbook recoveredWorkbook = chart.getChartData().getChartDataWorkbook();
>   } finally {
>      if (pres != null) pres.dispose();
>   }
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |