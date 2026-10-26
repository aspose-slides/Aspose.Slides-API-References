---
title: DataLabelFormat
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: DataLabel の書式設定オプションを表します。
type: docs
url: /ja/com.aspose.slides/datalabelformat/
---
**継承:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**実装されているすべてのインターフェイス:**  
[com.aspose.slides.IDataLabelFormat](../../com.aspose.slides/idatalabelformat)  
```
public final class DataLabelFormat extends PVIObject implements IDataLabelFormat
```

DataLabel の書式設定オプションを表します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | 読み書き可能 boolean. |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | 読み書き可能 boolean. |
| [getNumberFormat()](#getNumberFormat--) | DataLabels オブジェクトの書式文字列を表します。 |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | DataLabels オブジェクトの書式文字列を表します。 |
| [getFormat()](#getFormat--) | データ ラベルの書式を表します。 |
| [getPosition()](#getPosition--) | データ ラベルの位置を表します。 |
| [setPosition(int value)](#setPosition-int-) | データ ラベルの位置を表します。 |
| [getShowLegendKey()](#getShowLegendKey--) | 指定されたチャートのデータ ラベルの凡例キーの表示動作を表します。 |
| [setShowLegendKey(boolean value)](#setShowLegendKey-boolean-) | 指定されたチャートのデータ ラベルの凡例キーの表示動作を表します。 |
| [getShowValue()](#getShowValue--) | 指定されたチャートのデータ ラベルのパーセンテージ値の表示動作を表します。 |
| [setShowValue(boolean value)](#setShowValue-boolean-) | 指定されたチャートのデータ ラベルのパーセンテージ値の表示動作を表します。 |
| [getShowCategoryName()](#getShowCategoryName--) | 指定されたチャートのデータ ラベルのカテゴリ名の表示動作を表します。 |
| [setShowCategoryName(boolean value)](#setShowCategoryName-boolean-) | 指定されたチャートのデータ ラベルのカテゴリ名の表示動作を表します。 |
| [getShowSeriesName()](#getShowSeriesName--) | チャート上のデータ ラベルのシリーズ名の表示動作を示す Boolean を取得または設定します。 |
| [setShowSeriesName(boolean value)](#setShowSeriesName-boolean-) | チャート上のデータ ラベルのシリーズ名の表示動作を示す Boolean を取得または設定します。 |
| [getShowPercentage()](#getShowPercentage--) | 指定されたチャートのデータ ラベルのパーセンテージ値の表示動作を表します。 |
| [setShowPercentage(boolean value)](#setShowPercentage-boolean-) | 指定されたチャートのデータ ラベルのパーセンテージ値の表示動作を表します。 |
| [getShowBubbleSize()](#getShowBubbleSize--) | 指定されたチャートのデータ ラベルのバブル サイズ値の表示動作を表します。 |
| [setShowBubbleSize(boolean value)](#setShowBubbleSize-boolean-) | 指定されたチャートのデータ ラベルのバブル サイズ値の表示動作を表します。 |
| [getShowLeaderLines()](#getShowLeaderLines--) | 指定されたチャートのデータ ラベルのリーダー ラインの表示動作を表します。 |
| [setShowLeaderLines(boolean value)](#setShowLeaderLines-boolean-) | 指定されたチャートのデータ ラベルのリーダー ラインの表示動作を表します。 |
| [getShowLabelValueFromCell()](#getShowLabelValueFromCell--) | 指定されたチャートのデータ ラベルのセル値の表示動作を表します。 |
| [setShowLabelValueFromCell(boolean value)](#setShowLabelValueFromCell-boolean-) | 指定されたチャートのデータ ラベルのセル値の表示動作を表します。 |
| [getShowLabelAsDataCallout()](#getShowLabelAsDataCallout--) | 指定されたチャートのデータ ラベルがデータ コールアウトとして表示されるかデータ ラベルとして表示されるかを決定します。 |
| [setShowLabelAsDataCallout(boolean value)](#setShowLabelAsDataCallout-boolean-) | 指定されたチャートのデータ ラベルがデータ コールアウトとして表示されるかデータ ラベルとして表示されるかを決定します。 |
| [getSeparator()](#getSeparator--) | チャート上のデータ ラベルで使用される区切り文字を表す Variant を設定または取得します。 |
| [setSeparator(String value)](#setSeparator-java.lang.String-) | チャート上のデータ ラベルで使用される区切り文字を表す Variant を設定または取得します。 |
| [getTextFormat()](#getTextFormat--) | チャートのテキスト書式を返します。 |
| [getChart()](#getChart--) | チャートを返します。 |

### getVersion() {#getVersion--}
```
public long getVersion()
```

バージョン。読み取り専用 long.

**戻り値:**  
long

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public final boolean isNumberFormatLinkedToSource()
```

読み書き可能 boolean.

--------------------

この DataLabelFormat オブジェクトの親が DataLabelCollection（データ ラベルのコレクション）である場合、このプロパティは DataLabelCollection 内の新しいデータ ラベルの IsNumberFormatLinkedToSource プロパティの既定値を取得または設定します。値でこのプロパティを設定すると、DataLabelCollection 内のすべてのデータ ラベルの IsNumberFormatLinkedToSource プロパティにも同じ値が設定されます（例: "DataLabels.getDefaultDataLabelFormat().isNumberFormatLinkedToSource(val);" はすべての DataLabels.get_Item(i).isNumberFormatLinkedToSource() が val と等しくなることを引き起こします）。

**戻り値:**  
boolean

### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public final void setNumberFormatLinkedToSource(boolean value)
```

読み書き可能 boolean.

--------------------

この DataLabelFormat オブジェクトの親が DataLabelCollection（データ ラベルのコレクション）である場合、このプロパティは DataLabelCollection 内の新しいデータ ラベルの IsNumberFormatLinkedToSource プロパティの既定値を取得または設定します。値でこのプロパティを設定すると、DataLabelCollection 内のすべてのデータ ラベルの IsNumberFormatLinkedToSource プロパティにも同じ値が設定されます（例: "DataLabels.getDefaultDataLabelFormat().isNumberFormatLinkedToSource(val);" はすべての DataLabels.get_Item(i).isNumberFormatLinkedToSource() が val と等しくなることを引き起こします）。

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public final String getNumberFormat()
```

DataLabels オブジェクトの書式文字列を表します。読み書き可能 String.

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```


--------------------

この DataLabelFormat オブジェクトの親が DataLabelCollection（データ ラベルのコレクション）である場合、このプロパティは DataLabelCollection 内の新しいデータ ラベルの NumberFormat プロパティの既定値を取得または設定します。値でこのプロパティを設定すると、DataLabelCollection 内のすべてのデータ ラベルの NumberFormat プロパティにも同じ値が設定されます（例: "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" はすべての DataLabels.get_Item(i).getNumberFormat() が val と等しくなることを引き起こします）。

**戻り値:**  
java.lang.String

### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public final void setNumberFormat(String value)
```

DataLabels オブジェクトの書式文字列を表します。読み書き可能 String.

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```

--------------------

この DataLabelFormat オブジェクトの親が DataLabelCollection（データ ラベルのコレクション）である場合、このプロパティは DataLabelCollection 内の新しいデータ ラベルの NumberFormat プロパティの既定値を取得または設定します。値でこのプロパティを設定すると、DataLabelCollection 内のすべてのデータ ラベルの NumberFormat プロパティにも同じ値が設定されます（例: "DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);" はすべての DataLabels.get_Item(i).getNumberFormat() が val と等しくなることを引き起こします）。

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

データ ラベルの書式を表します。読み取り専用 [IFormat](../../com.aspose.slides/iformat).

--------------------

この DataLabelFormat オブジェクトの親が DataLabelCollection（データ ラベルのコレクション）である場合、このプロパティは DataLabelCollection 内の新しいデータ ラベルの既定の書式を表します。

**戻り値:**  
[IFormat](../../com.aspose.slides/iformat)

### getPosition() {#getPosition--}
```
public final int getPosition()
```

データ ラベルの位置を表します。読み書き可能 [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

この DataLabelFormat オブジェクトの親が DataLabelCollection（データ ラベルのコレクション）である場合、このプロパティは DataLabelCollection 内の新しいデータ ラベルの Position プロパティの既定値を取得または設定します。DataLabel オブジェクトの位置を表します。値でこのプロパティを設定すると、DataLabelCollection 内のすべてのデータ ラベルの Position プロパティにも同じ値が設定されます（例: "DataLabels.getDefaultDataLabelFormat().setPosition(val);" はすべての DataLabels.get_Item(i).getPosition() が val と等しくなることを引き起こします）。

**戻り値:**  
int

### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```

データ ラベルの位置を表します。読み書き可能 [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition).

--------------------

この DataLabelFormat オブジェクトの親が DataLabelCollection（データ ラベルのコレクション）である場合、このプロパティは DataLabelCollection 内の新しいデータ ラベルの Position プロパティの既定値を取得または設定します。DataLabel オブジェクトの位置を表します。値でこのプロパティを設定すると、DataLabelCollection 内のすべてのデータ ラベルの Position プロパティにも同じ値が設定されます（例: "DataLabels.getDefaultDataLabelFormat().setPosition(val);" はすべての DataLabels.get_Item(i).getPosition() が val と等しくなることを引き起こします）。

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getShowLegendKey() {#getShowLegendKey--}
```
public final boolean getShowLegendKey()
```

指定されたチャートのデータ ラベルの凡例キーの表示動作を表します。データ ラベルの凡例キーが表示されている場合は true。読み書き可能 boolean.

--------------------

この DataLabelFormat オブジェクトの親が DataLabelCollection（データ ラベルのコレクション）である場合、このプロパティは DataLabelCollection 内の新しいデータ ラベルの ShowLegendKey プロパティの既定値を取得または設定します。値でこのプロパティを設定すると、DataLabelCollection 内のすべてのデータ ラベルの ShowLegendKey プロパティにも同じ値が設定されます（例: "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" はすべての DataLabels.get_Item(i).getShowLegendKey() が val と等しくなることを引き起こします）。

**戻り値:**  
boolean

### setShowLegendKey(boolean value) {#setShowLegendKey-boolean-}
```
public final void setShowLegendKey(boolean value)
```

指定されたチャートのデータ ラベルの凡例キーの表示動作を表します。データ ラベルの凡例キーが表示されている場合は true。読み書き可能 boolean.

--------------------

この DataLabelFormat オブジェクトの親が DataLabelCollection（データ ラベルのコレクション）である場合、このプロパティは DataLabelCollection 内の新しいデータ ラベルの ShowLegendKey プロパティの既定値を取得または設定します。値でこのプロパティを設定すると、DataLabelCollection 内のすべてのデータ ラベルの ShowLegendKey プロパティにも同じ値が設定されます（例: "DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);" はすべての DataLabels.get_Item(i).getShowLegendKey() が val と等しくなることを引き起こします）。

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getShowValue() {#getShowValue--}
```
public final boolean getShowValue()
```

指定されたチャートのデータ ラベルのパーセンテージ値の表示動作を表します。true の場合、パーセンテージ値が表示されます。false の場合、非表示です。読み書き可能 boolean.

--------------------

この DataLabelFormat オブジェクトの親が DataLabelCollection（データ ラベルのコレクション）である場合、このプロパティは DataLabelCollection 内の新しいデータ ラベルの ShowValue プロパティの既定値を取得または設定します。値でこのプロパティを設定すると、DataLabelCollection 内のすべてのデータ ラベルの ShowValue プロパティにも同じ値が設定されます（例: "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" はすべての DataLabels.get_Item(i).getShowValue() が val と等しくなることを引き起こします）。

**戻り値:**  
boolean

### setShowValue(boolean value) {#setShowValue-boolean-}
```
public final void setShowValue(boolean value)
```

指定されたチャートのデータ ラベルのパーセンテージ値の表示動作を表します。true の場合、パーセンテージ値が表示されます。false の場合、非表示です。読み書き可能 boolean.

--------------------

この DataLabelFormat オブジェクトの親が DataLabelCollection（データ ラベルのコレクション）である場合、このプロパティは DataLabelCollection 内の新しいデータ ラベルの ShowValue プロパティの既定値を取得または設定します。値でこのプロパティを設定すると、DataLabelCollection 内のすべてのデータ ラベルの ShowValue プロパティにも同じ値が設定されます（例: "DataLabels.getDefaultDataLabelFormat().setShowValue(val);" はすべての DataLabels.get_Item(i).getShowValue() が val と等しくなることを引き起こします）。

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getShowCategoryName() {#getShowCategoryName--}
```
public final boolean getShowCategoryName()
```

指定されたチャートのデータ ラベルのカテゴリ名の表示動作を表します。true の場合、チャート上のデータ ラベルにカテゴリ名が表示されます。false の場合、非表示です。読み書き可能 boolean.

--------------------

この DataLabelFormat オブジェクトの親が DataLabelCollection（データ ラベルのコレクション）である場合、このプロパティは DataLabelCollection 内の新しいデータ ラベルの ShowCategoryName プロパティの既定値を取得または設定します。値でこのプロパティを設定すると、DataLabelCollection 内のすべてのデータ ラベルの ShowCategoryName プロパティにも同じ値が設定されます（例: "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" はすべての DataLabels.get_Item(i).getShowCategoryName() が val と等しくなることを引き起こします）。

**戻り値:**  
boolean

### setShowCategoryName(boolean value) {#setShowCategoryName-boolean-}
```
public final void setShowCategoryName(boolean value)
```

指定されたチャートのデータ ラベルのカテゴリ名の表示動作を表します。true の場合、チャート上のデータ ラベルにカテゴリ名が表示されます。false の場合、非表示です。読み書き可能 boolean.

--------------------

この DataLabelFormat オブジェクトの親が DataLabelCollection（データ ラベルのコレクション）である場合、このプロパティは DataLabelCollection 内の新しいデータ ラベルの ShowCategoryName プロパティの既定値を取得または設定します。値でこのプロパティを設定すると、DataLabelCollection 内のすべてのデータ ラベルの ShowCategoryName プロパティにも同じ値が設定されます（例: "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" はすべての DataLabels.get_Item(i).getShowCategoryName() が val と等しくなることを引き起こします）。

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getShowSeriesName() {#getShowSeriesName--}
```
public final boolean getShowSeriesName()
```

チャート上のデータ ラベルのシリーズ名の表示動作を示す Boolean を取得または設定します。true の場合、シリーズ名が表示されます。false の場合、非表示です。読み書き可能 boolean.

--------------------

この DataLabelFormat オブジェクトの親が DataLabelCollection（データ ラベルのコレクション）である場合、このプロパティは DataLabelCollection 内の新しいデータ ラベルの ShowSeriesName プロパティの既定値を取得または設定します。値でこのプロパティを設定すると、DataLabelCollection 内のすべてのデータ ラベルの ShowSeriesName プロパティにも同じ値が設定されます（例: "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" はすべての DataLabels.get_Item(i).getShowSeriesName() が val と等しくなることを引き起こします）。

**戻り値:**  
boolean

### setShowSeriesName(boolean value) {#setShowSeriesName-boolean-}
```
public final void setShowSeriesName(boolean value)
```

チャート上のデータ ラベルのシリーズ名の表示動作を示す Boolean を取得または設定します。true の場合、シリーズ名が表示されます。false の場合、非表示です。読み書き可能 boolean.

--------------------

この DataLabelFormat オブジェクトの親が DataLabelCollection（データ ラベルのコレクション）である場合、このプロパティは DataLabelCollection 内の新しいデータ ラベルの ShowSeriesName プロパティの既定値を取得または設定します。値でこのプロパティを設定すると、DataLabelCollection 内のすべてのデータ ラベルの ShowSeriesName プロパティにも同じ値が設定されます（例: "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" はすべての DataLabels.get_Item(i).getShowSeriesName() が val と等しくなることを引き起こします）。

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getShowPercentage() {#getShowPercentage--}
```
public final boolean getShowPercentage()
```

指定されたチャートのデータ ラベルのパーセンテージ値の表示動作を表します。true の場合、パーセンテージ値が表示されます。false の場合、非表示です。読み書き可能 boolean.

--------------------

この DataLabelFormat オブジェクトの親が DataLabelCollection（データ ラベルのコレクション）である場合、このプロパティは DataLabelCollection 内の新しいデータ ラベルの ShowPercentage プロパティの既定値を取得または設定します。値でこのプロパティを設定すると、DataLabelCollection 内のすべてのデータ ラベルの ShowPercentage プロパティにも同じ値が設定されます（例: "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" はすべての DataLabels.get_Item(i).getShowPercentage() が val と等しくなることを引き起こします）。

**戻り値:**  
boolean

### setShowPercentage(boolean value) {#setShowPercentage-boolean-}
```
public final void setShowPercentage(boolean value)
```

指定されたチャートのデータ ラベルのパーセンテージ値の表示動作を表します。true の場合、パーセンテージ値が表示されます。false の場合、非表示です。読み書き可能 boolean.

--------------------

この DataLabelFormat オブジェクトの親が DataLabelCollection（データ ラベルのコレクション）である場合、このプロパティは DataLabelCollection 内の新しいデータ ラベルの ShowPercentage プロパティの既定値を取得または設定します。値でこのプロパティを設定すると、DataLabelCollection 内のすべてのデータ ラベルの ShowPercentage プロパティにも同じ値が設定されます（例: "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" はすべての DataLabels.get_Item(i).getShowPercentage() が val と等しくなることを引き起こします）。

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getShowBubbleSize() {#getShowBubbleSize--}
```
public final boolean getShowBubbleSize()
```

指定されたチャートのデータ ラベルのバブル サイズ値の表示動作を表します。true の場合、バブル サイズ値が表示されます。false の場合、非表示です。読み書き可能 boolean.

--------------------

この DataLabelFormat オブジェクトの親が DataLabelCollection（データ ラベルのコレクション）である場合、このプロパティは DataLabelCollection 内の新しいデータ ラベルの ShowBubbleSize プロパティの既定値を取得または設定します。値でこのプロパティを設定すると、DataLabelCollection 内のすべてのデータ ラベルの ShowBubbleSize プロパティにも同じ値が設定されます（例: "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" はすべての DataLabels.get_Item(i).getShowBubbleSize() が val と等しくなることを引き起こします）。

**戻り値:**  
boolean

### setShowBubbleSize(boolean value) {#setShowBubbleSize-boolean-}
```
public final void setShowBubbleSize(boolean value)
```

指定されたチャートのデータ ラベルのバブル サイズ値の表示動作を表します。true の場合、バブル サイズ値が表示されます。false の場合、非表示です。読み書き可能 boolean.

--------------------

この DataLabelFormat オブジェクトの親が DataLabelCollection（データ ラベルのコレクション）である場合、このプロパティは DataLabelCollection 内の新しいデータ ラベルの ShowBubbleSize プロパティの既定値を取得または設定します。値でこのプロパティを設定すると、DataLabelCollection 内のすべてのデータ ラベルの ShowBubbleSize プロパティにも同じ値が設定されます（例: "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" はすべての DataLabels.get_Item(i).getShowBubbleSize() が val と等しくなることを引き起こします）。

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getShowLeaderLines() {#getShowLeaderLines--}
```
public final boolean getShowLeaderLines()
```

指定されたチャートのデータ ラベルのリーダー ラインの表示動作を表します。true の場合、リーダー ラインが表示されます。false の場合、非表示です。読み書き可能 boolean.

--------------------

この DataLabelFormat オブジェクトの親が DataLabelCollection（データ ラベルのコレクション）である場合、このプロパティは DataLabelCollection 内の新しいデータ ラベルの ShowLeaderLines プロパティの既定値を取得または設定します。値でこのプロパティを設定すると、DataLabelCollection 内のすべてのデータ ラベルの ShowLeaderLines プロパティにも同じ値が設定されます（例: "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" はすべての DataLabels.get_Item(i).getShowLeaderLines() が val と等しくなることを引き起こします）。

**戻り値:**  
boolean

### setShowLeaderLines(boolean value) {#setShowLeaderLines-boolean-}
```
public final void setShowLeaderLines(boolean value)
```

指定されたチャートのデータ ラベルのリーダー ラインの表示動作を表します。true の場合、リーダー ラインが表示されます。false の場合、非表示です。読み書き可能 boolean.

--------------------

この DataLabelFormat オブジェクトの親が DataLabelCollection（データ ラベルのコレクション）である場合、このプロパティは DataLabelCollection 内の新しいデータ ラベルの ShowLeaderLines プロパティの既定値を取得または設定します。値でこのプロパティを設定すると、DataLabelCollection 内のすべてのデータ ラベルの ShowLeaderLines プロパティにも同じ値が設定されます（例: "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" はすべての DataLabels.get_Item(i).getShowLeaderLines() が val と等しくなることを引き起こします）。

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelValueFromCell() {#getShowLabelValueFromCell--}
```
public final boolean getShowLabelValueFromCell()
```

指定されたチャートのデータ ラベルのセル値の表示動作を表します。true の場合、セル値が表示されます。false の場合、非表示です。読み書き可能 boolean.

--------------------

この DataLabelFormat オブジェクトの親が DataLabelCollection（データ ラベルのコレクション）である場合、このプロパティは DataLabelCollection 内の新しいデータ ラベルの ShowLabelValueFromCell プロパティの既定値を取得または設定します。値でこのプロパティを設定すると、DataLabelCollection 内のすべてのデータ ラベルの ShowLabelValueFromCell プロパティにも同じ値が設定されます（例: "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" はすべての DataLabels.get_Item(i).getShowLabelValueFromCell() が val と等しくなることを引き起こします）。

**戻り値:**  
boolean

### setShowLabelValueFromCell(boolean value) {#setShowLabelValueFromCell-boolean-}
```
public final void setShowLabelValueFromCell(boolean value)
```

指定されたチャートのデータ ラベルのセル値の表示動作を表します。true の場合、セル値が表示されます。false の場合、非表示です。読み書き可能 boolean.

--------------------

この DataLabelFormat オブジェクトの親が DataLabelCollection（データ ラベルのコレクション）である場合、このプロパティは DataLabelCollection 内の新しいデータ ラベルの ShowLabelValueFromCell プロパティの既定値を取得または設定します。値でこのプロパティを設定すると、DataLabelCollection 内のすべてのデータ ラベルの ShowLabelValueFromCell プロパティにも同じ値が設定されます（例: "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" はすべての DataLabels.get_Item(i).getShowLabelValueFromCell() が val と等しくなることを引き起こします）。

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelAsDataCallout() {#getShowLabelAsDataCallout--}
```
public final boolean getShowLabelAsDataCallout()
```

指定されたチャートのデータ ラベルがデータ コールアウトとして表示されるかデータ ラベルとして表示されるかを決定します。

--------------------

この DataLabelFormat オブジェクトの親が DataLabelCollection（データ ラベルのコレクション）である場合、このプロパティは DataLabelCollection 内の新しいデータ ラベルの ShowLabelAsDataCallout プロパティの既定値を取得または設定します。値でこのプロパティを設定すると、DataLabelCollection 内のすべてのデータ ラベルの ShowLabelAsDataCallout プロパティにも同じ値が設定されます（例: "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" はすべての DataLabels.get_Item(i).getShowLabelAsDataCallout() が val と等しくなることを引き起こします）。

**戻り値:**  
boolean

### setShowLabelAsDataCallout(boolean value) {#setShowLabelAsDataCallout-boolean-}
```
public final void setShowLabelAsDataCallout(boolean value)
```

指定されたチャートのデータ ラベルがデータ コールアウトとして表示されるかデータ ラベルとして表示されるかを決定します。

--------------------

この DataLabelFormat オブジェクトの親が DataLabelCollection（データ ラベルのコレクション）である場合、このプロパティは DataLabelCollection 内の新しいデータ ラベルの ShowLabelAsDataCallout プロパティの既定値を取得または設定します。値でこのプロパティを設定すると、DataLabelCollection 内のすべてのデータ ラベルの ShowLabelAsDataCallout プロパティにも同じ値が設定されます（例: "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" はすべての DataLabels.get_Item(i).getShowLabelAsDataCallout() が val と等しくなることを引き起こします）。

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getSeparator() {#getSeparator--}
```
public final String getSeparator()
```

チャート上のデータ ラベルで使用される区切り文字を表す Variant を設定または取得します。読み書き可能 String.

--------------------

この DataLabelFormat オブジェクトの親が DataLabelCollection（データ ラベルのコレクション）である場合、このプロパティは DataLabelCollection 内の新しいデータ ラベルの Separator プロパティの既定値を取得または設定します。値でこのプロパティを設定すると、DataLabelCollection 内のすべてのデータ ラベルの Separator プロパティにも同じ値が設定されます（例: "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" はすべての DataLabels.get_Item(i).getSeparator() が val と等しくなることを引き起こします）。

**戻り値:**  
java.lang.String

### setSeparator(String value) {#setSeparator-java.lang.String-}
```
public final void setSeparator(String value)
```

チャート上のデータ ラベルで使用される区切り文字を表す Variant を設定または取得します。読み書き可能 String.

--------------------

この DataLabelFormat オブジェクトの親が DataLabelCollection（データ ラベルのコレクション）である場合、このプロパティは DataLabelCollection 内の新しいデータ ラベルの Separator プロパティの既定値を取得または設定します。値でこのプロパティを設定すると、DataLabelCollection 内のすべてのデータ ラベルの Separator プロパティにも同じ値が設定されます（例: "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" はすべての DataLabels.get_Item(i).getSeparator() が val と等しくなることを引き起こします）。

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

チャートのテキスト書式を返します。読み取り専用 [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**戻り値:**  
[IChartTextFormat](../../com.aspose.slides/icharttextformat)

### getChart() {#getChart--}
```
public final IChart getChart()
```

チャートを返します。読み取り専用 [IChart](../../com.aspose.slides/ichart).

**戻り値:**  
[IChart](../../com.aspose.slides/ichart)