---
title: DataLabelFormat
second_title: Aspose.Slides for Java API リファレンス
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
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | 読み取り/書き込み boolean。 |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | 読み取り/書き込み boolean。 |
| [getNumberFormat()](#getNumberFormat--) | DataLabels オブジェクトの書式文字列を表します。 |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | DataLabels オブジェクトの書式文字列を表します。 |
| [getFormat()](#getFormat--) | データラベルの書式を表します。 |
| [getPosition()](#getPosition--) | データラベルの位置を表します。 |
| [setPosition(int value)](#setPosition-int-) | データラベルの位置を表します。 |
| [getShowLegendKey()](#getShowLegendKey--) | 指定したチャートのデータラベルの凡例キー表示動作を表します。 |
| [setShowLegendKey(boolean value)](#setShowLegendKey-boolean-) | 指定したチャートのデータラベルの凡例キー表示動作を表します。 |
| [getShowValue()](#getShowValue--) | 指定したチャートのデータラベルのパーセンテージ値表示動作を表します。 |
| [setShowValue(boolean value)](#setShowValue-boolean-) | 指定したチャートのデータラベルのパーセンテージ値表示動作を表します。 |
| [getShowCategoryName()](#getShowCategoryName--) | 指定したチャートのデータラベルのカテゴリ名表示動作を表します。 |
| [setShowCategoryName(boolean value)](#setShowCategoryName-boolean-) | 指定したチャートのデータラベルのカテゴリ名表示動作を表します。 |
| [getShowSeriesName()](#getShowSeriesName--) | チャート上のデータラベルの系列名表示動作を示す Boolean を取得または設定します。 |
| [setShowSeriesName(boolean value)](#setShowSeriesName-boolean-) | チャート上のデータラベルの系列名表示動作を示す Boolean を取得または設定します。 |
| [getShowPercentage()](#getShowPercentage--) | 指定したチャートのデータラベルのパーセンテージ値表示動作を表します。 |
| [setShowPercentage(boolean value)](#setShowPercentage-boolean-) | 指定したチャートのデータラベルのパーセンテージ値表示動作を表します。 |
| [getShowBubbleSize()](#getShowBubbleSize--) | 指定したチャートのデータラベルのバブルサイズ値表示動作を表します。 |
| [setShowBubbleSize(boolean value)](#setShowBubbleSize-boolean-) | 指定したチャートのデータラベルのバブルサイズ値表示動作を表します。 |
| [getShowLeaderLines()](#getShowLeaderLines--) | 指定したチャートのデータラベルのリーダーライン表示動作を表します。 |
| [setShowLeaderLines(boolean value)](#setShowLeaderLines-boolean-) | 指定したチャートのデータラベルのリーダーライン表示動作を表します。 |
| [getShowLabelValueFromCell()](#getShowLabelValueFromCell--) | 指定したチャートのデータラベルのセル値表示動作を表します。 |
| [setShowLabelValueFromCell(boolean value)](#setShowLabelValueFromCell-boolean-) | 指定したチャートのデータラベルのセル値表示動作を表します。 |
| [getShowLabelAsDataCallout()](#getShowLabelAsDataCallout--) | 指定したチャートのデータラベルがデータ呼び出しとして表示されるか、データラベルとして表示されるかを決定します。 |
| [setShowLabelAsDataCallout(boolean value)](#setShowLabelAsDataCallout-boolean-) | 指定したチャートのデータラベルがデータ呼び出しとして表示されるか、データラベルとして表示されるかを決定します。 |
| [getSeparator()](#getSeparator--) | チャート上のデータラベルで使用される区切り文字を表す Variant を取得または設定します。 |
| [setSeparator(String value)](#setSeparator-java.lang.String-) | チャート上のデータラベルで使用される区切り文字を表す Variant を取得または設定します。 |
| [getTextFormat()](#getTextFormat--) | チャートのテキスト書式を取得します。 |
| [getChart()](#getChart--) | チャートを取得します。 |
### getVersion() {#getVersion--}
```
public long getVersion()
```

バージョン。読み取り専用の long。

**戻り値:**
long
### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public final boolean isNumberFormatLinkedToSource()
```

読み取り/書き込み boolean。

--------------------

親オブジェクトが DataLabelCollection（データラベルのコレクション）である場合、このプロパティは DataLabelCollection 内の新しいデータラベルに対する IsNumberFormatLinkedToSource プロパティの既定値を取得または設定します。値を設定すると、同じ値が DataLabelCollection 内のすべてのデータラベルの IsNumberFormatLinkedToSource プロパティにも設定されます（例: `"DataLabels.getDefaultDataLabelFormat().isNumberFormatLinkedToSource(val);"` により `DataLabels.get_Item(i).isNumberFormatLinkedToSource()` がすべて val と等しくなります）。

**戻り値:**
boolean
### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public final void setNumberFormatLinkedToSource(boolean value)
```

読み取り/書き込み boolean。

--------------------

親オブジェクトが DataLabelCollection（データラベルのコレクション）である場合、このプロパティは DataLabelCollection 内の新しいデータラベルに対する IsNumberFormatLinkedToSource プロパティの既定値を取得または設定します。値を設定すると、同じ値が DataLabelCollection 内のすべてのデータラベルの IsNumberFormatLinkedToSource プロパティにも設定されます（例: `"DataLabels.getDefaultDataLabelFormat().isNumberFormatLinkedToSource(val);"` により `DataLabels.get_Item(i).isNumberFormatLinkedToSource()` がすべて val と等しくなります）。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |
### getNumberFormat() {#getNumberFormat--}
```
public final String getNumberFormat()
```

DataLabels オブジェクトの書式文字列を表します。読み取り/書き込み String。

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```


--------------------

親オブジェクトが DataLabelCollection（データラベルのコレクション）である場合、このプロパティは DataLabelCollection 内の新しいデータラベルに対する NumberFormat プロパティの既定値を取得または設定します。値を設定すると、同じ値が DataLabelCollection 内のすべてのデータラベルの NumberFormat プロパティにも設定されます（例: `"DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);"` により `DataLabels.get_Item(i).getNumberFormat()` がすべて val と等しくなります）。

**戻り値:**
java.lang.String
### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public final void setNumberFormat(String value)
```

DataLabels オブジェクトの書式文字列を表します。読み取り/書き込み String。

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```

--------------------

親オブジェクトが DataLabelCollection（データラベルのコレクション）である場合、このプロパティは DataLabelCollection 内の新しいデータラベルに対する NumberFormat プロパティの既定値を取得または設定します。値を設定すると、同じ値が DataLabelCollection 内のすべてのデータラベルの NumberFormat プロパティにも設定されます（例: `"DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);"` により `DataLabels.get_Item(i).getNumberFormat()` がすべて val と等しくなります）。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |
### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

データラベルの書式を表します。読み取り [IFormat](../../com.aspose.slides/iformat)。

--------------------

親オブジェクトが DataLabelCollection（データラベルのコレクション）である場合、このプロパティは DataLabelCollection 内の新しいデータラベルの既定書式を表します。

**戻り値:**
[IFormat](../../com.aspose.slides/iformat)
### getPosition() {#getPosition--}
```
public final int getPosition()
```

データラベルの位置を表します。読み取り/書き込み [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition)。

--------------------

親オブジェクトが DataLabelCollection（データラベルのコレクション）である場合、このプロパティは DataLabelCollection 内の新しいデータラベルに対する Position プロパティの既定値を取得または設定します。データラベルオブジェクトの位置を表します。値を設定すると、同じ値が DataLabelCollection 内のすべてのデータラベルの Position プロパティにも設定されます（例: `"DataLabels.getDefaultDataLabelFormat().setPosition(val);"` により `DataLabels.get_Item(i).getPosition()` がすべて val と等しくなります）。

**戻り値:**
int
### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```

データラベルの位置を表します。読み取り/書き込み [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition)。

--------------------

親オブジェクトが DataLabelCollection（データラベルのコレクション）である場合、このプロパティは DataLabelCollection 内の新しいデータラベルに対する Position プロパティの既定値を取得または設定します。データラベルオブジェクトの位置を表します。値を設定すると、同じ値が DataLabelCollection 内のすべてのデータラベルの Position プロパティにも設定されます（例: `"DataLabels.getDefaultDataLabelFormat().setPosition(val);"` により `DataLabels.get_Item(i).getPosition()` がすべて val と等しくなります）。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |
### getShowLegendKey() {#getShowLegendKey--}
```
public final boolean getShowLegendKey()
```

指定したチャートのデータラベルの凡例キー表示動作を表します。凡例キーが表示されている場合は true。読み取り/書き込み boolean。

--------------------

親オブジェクトが DataLabelCollection（データラベルのコレクション）である場合、このプロパティは DataLabelCollection 内の新しいデータラベルに対する ShowLegendKey プロパティの既定値を取得または設定します。値を設定すると、同じ値が DataLabelCollection 内のすべてのデータラベルの ShowLegendKey プロパティにも設定されます（例: `"DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);"` により `DataLabels.get_Item(i).getShowLegendKey()` がすべて val と等しくなります）。

**戻り値:**
boolean
### setShowLegendKey(boolean value) {#setShowLegendKey-boolean-}
```
public final void setShowLegendKey(boolean value)
```

指定したチャートのデータラベルの凡例キー表示動作を表します。凡例キーが表示されている場合は true。読み取り/書き込み boolean。

--------------------

親オブジェクトが DataLabelCollection（データラベルのコレクション）である場合、このプロパティは DataLabelCollection 内の新しいデータラベルに対する ShowLegendKey プロパティの既定値を取得または設定します。値を設定すると、同じ値が DataLabelCollection 内のすべてのデータラベルの ShowLegendKey プロパティにも設定されます（例: `"DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);"` により `DataLabels.get_Item(i).getShowLegendKey()` がすべて val と等しくなります）。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |
### getShowValue() {#getShowValue--}
```
public final boolean getShowValue()
```

指定したチャートのデータラベルのパーセンテージ値表示動作を表します。true の場合はパーセンテージ値を表示し、false の場合は非表示にします。読み取り/書き込み boolean。

--------------------

親オブジェクトが DataLabelCollection（データラベルのコレクション）である場合、このプロパティは DataLabelCollection 内の新しいデータラベルに対する ShowValue プロパティの既定値を取得または設定します。値を設定すると、同じ値が DataLabelCollection 内のすべてのデータラベルの ShowValue プロパティにも設定されます（例: `"DataLabels.getDefaultDataLabelFormat().setShowValue(val);"` により `DataLabels.get_Item(i).getShowValue()` がすべて val と等しくなります）。

**戻り値:**
boolean
### setShowValue(boolean value) {#setShowValue-boolean-}
```
public final void setShowValue(boolean value)
```

指定したチャートのデータラベルのパーセンテージ値表示動作を表します。true の場合はパーセンテージ値を表示し、false の場合は非表示にします。読み取り/書き込み boolean。

--------------------

親オブジェクトが DataLabelCollection（データラベルのコレクション）である場合、このプロパティは DataLabelCollection 内の新しいデータラベルに対する ShowValue プロパティの既定値を取得または設定します。値を設定すると、同じ値が DataLabelCollection 内のすべてのデータラベルの ShowValue プロパティにも設定されます（例: `"DataLabels.getDefaultDataLabelFormat().setShowValue(val);"` により `DataLabels.get_Item(i).getShowValue()` がすべて val と等しくなります）。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |
### getShowCategoryName() {#getShowCategoryName--}
```
public final boolean getShowCategoryName()
```

指定したチャートのデータラベルのカテゴリ名表示動作を表します。true の場合はカテゴリ名を表示し、false の場合は非表示にします。読み取り/書き込み boolean。

--------------------

親オブジェクトが DataLabelCollection（データラベルのコレクション）である場合、このプロパティは DataLabelCollection 内の新しいデータラベルに対する ShowCategoryName プロパティの既定値を取得または設定します。値を設定すると、同じ値が DataLabelCollection 内のすべてのデータラベルの ShowCategoryName プロパティにも設定されます（例: `"DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);"` により `DataLabels.get_Item(i).getShowCategoryName()` がすべて val と等しくなります）。

**戻り値:**
boolean
### setShowCategoryName(boolean value) {#setShowCategoryName-boolean-}
```
public final void setShowCategoryName(boolean value)
```

指定したチャートのデータラベルのカテゴリ名表示動作を表します。true の場合はカテゴリ名を表示し、false の場合は非表示にします。読み取り/書き込み boolean。

--------------------
If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowCategoryName property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowCategoryName property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" cause to all DataLabels.get_Item(i).getShowCategoryName() is equal to val).

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getShowSeriesName() {#getShowSeriesName--}
```
public final boolean getShowSeriesName()
```

チャート上のデータ ラベルの系列名表示動作を示す Boolean を取得または設定します。True は系列名を表示し、False は非表示にします。読み取り/書き込み ブール型。

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowSeriesName property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowSeriesName property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" cause to all DataLabels.get_Item(i).getShowSeriesName() is equal to val).

**戻り値:**
boolean
### setShowSeriesName(boolean value) {#setShowSeriesName-boolean-}
```
public final void setShowSeriesName(boolean value)
```

チャート上のデータ ラベルの系列名表示動作を示す Boolean を取得または設定します。True は系列名を表示し、False は非表示にします。読み取り/書き込み ブール型。

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowSeriesName property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowSeriesName property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" cause to all DataLabels.get_Item(i).getShowSeriesName() is equal to val).

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getShowPercentage() {#getShowPercentage--}
```
public final boolean getShowPercentage()
```

指定されたチャートのデータ ラベルのパーセンテージ値表示動作を表します。True はパーセンテージ値を表示し、False は非表示にします。読み取り/書き込み ブール型。

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowPercentage property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowPercentage property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" cause to all DataLabels.get_Item(i).getShowPercentage() is equal to val).

**戻り値:**
boolean
### setShowPercentage(boolean value) {#setShowPercentage-boolean-}
```
public final void setShowPercentage(boolean value)
```

指定されたチャートのデータ ラベルのパーセンテージ値表示動作を表します。True はパーセンテージ値を表示し、False は非表示にします。読み取り/書き込み ブール型。

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowPercentage property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowPercentage property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" cause to all DataLabels.get_Item(i).getShowPercentage() is equal to val).

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getShowBubbleSize() {#getShowBubbleSize--}
```
public final boolean getShowBubbleSize()
```

指定されたチャートのデータ ラベルのバブル サイズ値表示動作を表します。True はバブル サイズ値を表示し、False は非表示にします。読み取り/書き込み ブール型。

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowBubbleSize property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowBubbleSize property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" cause to all DataLabels.get_Item(i).getShowBubbleSize() is equal to val).

**戻り値:**
boolean
### setShowBubbleSize(boolean value) {#setShowBubbleSize-boolean-}
```
public final void setShowBubbleSize(boolean value)
```

指定されたチャートのデータ ラベルのバブル サイズ値表示動作を表します。True はバブル サイズ値を表示し、False は非表示にします。読み取り/書き込み ブール型。

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowBubbleSize property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowBubbleSize property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" cause to all DataLabels.get_Item(i).getShowBubbleSize() is equal to val).

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getShowLeaderLines() {#getShowLeaderLines--}
```
public final boolean getShowLeaderLines()
```

指定されたチャートのデータ ラベルのリーダー ライン表示動作を表します。True はリーダー ラインを表示し、False は非表示にします。読み取り/書き込み ブール型。

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowLeaderLines property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowLeaderLines property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" cause to all DataLabels.get_Item(i).getShowLeaderLines() is equal to val).

**戻り値:**
boolean
### setShowLeaderLines(boolean value) {#setShowLeaderLines-boolean-}
```
public final void setShowLeaderLines(boolean value)
```

指定されたチャートのデータ ラベルのリーダー ライン表示動作を表します。True はリーダー ラインを表示し、False は非表示にします。読み取り/書き込み ブール型。

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowLeaderLines property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowLeaderLines property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" cause to all DataLabels.get_Item(i).getShowLeaderLines() is equal to val).

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelValueFromCell() {#getShowLabelValueFromCell--}
```
public final boolean getShowLabelValueFromCell()
```

指定されたチャートのデータ ラベルのセル値表示動作を表します。True はセル値を表示し、False は非表示にします。読み取り/書き込み ブール型。

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowLabelValueFromCell property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowLabelValueFromCell property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" cause to all DataLabels.get_Item(i).getShowLabelValueFromCell() is equal to val).

**戻り値:**
boolean
### setShowLabelValueFromCell(boolean value) {#setShowLabelValueFromCell-boolean-}
```
public final void setShowLabelValueFromCell(boolean value)
```

指定されたチャートのデータ ラベルのセル値表示動作を表します。True はセル値を表示し、False は非表示にします。読み取り/書き込み ブール型。

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowLabelValueFromCell property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowLabelValueFromCell property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" cause to all DataLabels.get_Item(i).getShowLabelValueFromCell() is equal to val).

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelAsDataCallout() {#getShowLabelAsDataCallout--}
```
public final boolean getShowLabelAsDataCallout()
```

指定されたチャートのデータ ラベルがデータ コールアウトとして表示されるか、データ ラベルとして表示されるかを決定します。

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowLabelAsDataCallout property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowLabelAsDataCallout property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" cause to all DataLabels.get_Item(i).getShowLabelAsDataCallout() is equal to val).

**戻り値:**
boolean
### setShowLabelAsDataCallout(boolean value) {#setShowLabelAsDataCallout-boolean-}
```
public final void setShowLabelAsDataCallout(boolean value)
```

指定されたチャートのデータ ラベルがデータ コールアウトとして表示されるか、データ ラベルとして表示されるかを決定します。

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowLabelAsDataCallout property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowLabelAsDataCallout property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" cause to all DataLabels.get_Item(i).getShowLabelAsDataCallout() is equal to val).

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getSeparator() {#getSeparator--}
```
public final String getSeparator()
```

チャート上のデータ ラベルで使用される区切り文字を表す Variant を設定または取得します。読み取り/書き込み 文字列。

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the Separator property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the Separator property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" cause to all DataLabels.get_Item(i).getSeparator() is equal to val).

**戻り値:**
java.lang.String
### setSeparator(String value) {#setSeparator-java.lang.String-}
```
public final void setSeparator(String value)
```

チャート上のデータ ラベルで使用される区切り文字を表す Variant を設定または取得します。読み取り/書き込み 文字列。

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the Separator property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the Separator property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" cause to all DataLabels.get_Item(i).getSeparator() is equal to val).
**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```


チャートのテキストフォーマットを返します。読み取り専用 [IChartTextFormat](../../com.aspose.slides/icharttextformat)。

**戻り値:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### getChart() {#getChart--}
```
public final IChart getChart()
```


チャートを返します。読み取り専用 [IChart](../../com.aspose.slides/ichart)。

**戻り値:**
[IChart](../../com.aspose.slides/ichart)