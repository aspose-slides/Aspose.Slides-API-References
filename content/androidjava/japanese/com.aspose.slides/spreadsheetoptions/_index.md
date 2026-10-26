---
title: SpreadsheetOptions
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: 追加のスプレッドシートの動作を指定するために使用できるオプションを表します。
type: docs
url: /ja/com.aspose.slides/spreadsheetoptions/
---
**継承:**
java.lang.Object

**実装されているすべてのインターフェイス:**
[com.aspose.slides.ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions)
```
public class SpreadsheetOptions implements ISpreadsheetOptions
```

追加のスプレッドシートの動作を指定するために使用できるオプションを表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [SpreadsheetOptions()](#SpreadsheetOptions--) | [SpreadsheetOptions](../../com.aspose.slides/spreadsheetoptions) クラスの新しいインスタンスを初期化します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getPreferredCulture()](#getPreferredCulture--) | ダブルバイト文字セット (DBCS) を使用する言語向けのいくつかの関数を計算するための優先カルチャ情報を取得または設定します。 |
| [setPreferredCulture(Locale value)](#setPreferredCulture-java.util.Locale-) | ダブルバイト文字セット (DBCS) を使用する言語向けのいくつかの関数を計算するための優先カルチャ情報を取得または設定します。 |
| [getRecoverWorkbookFromChartCache()](#getRecoverWorkbookFromChartCache--) | チャートのデータ ソースが外部ブックで利用できない場合、チャート キャッシュから復元されます。 |
| [setRecoverWorkbookFromChartCache(boolean value)](#setRecoverWorkbookFromChartCache-boolean-) | チャートのデータ ソースが外部ブックで利用できない場合、チャート キャッシュから復元されます。 |

### SpreadsheetOptions() {#SpreadsheetOptions--}
```
public SpreadsheetOptions()
```

[SpreadsheetOptions](../../com.aspose.slides/spreadsheetoptions) クラスの新しいインスタンスを初期化します。

### getPreferredCulture() {#getPreferredCulture--}
```
public final Locale getPreferredCulture()
```

ダブルバイト文字セット (DBCS) を使用する言語向けのいくつかの関数を計算するための優先カルチャ情報を取得または設定します。

**戻り値:**
java.util.Locale

### setPreferredCulture(Locale value) {#setPreferredCulture-java.util.Locale-}
```
public final void setPreferredCulture(Locale value)
```

ダブルバイト文字セット (DBCS) を使用する言語向けのいくつかの関数を計算するための優先カルチャ情報を取得または設定します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.util.Locale |  |

### getRecoverWorkbookFromChartCache() {#getRecoverWorkbookFromChartCache--}
```
public final boolean getRecoverWorkbookFromChartCache()
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
public final void setRecoverWorkbookFromChartCache(boolean value)
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

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |