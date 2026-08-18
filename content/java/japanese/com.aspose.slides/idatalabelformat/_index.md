---
title: IDataLabelFormat
second_title: Aspose.Slides for Java API リファレンス
description: データラベルの書式設定オプションを表します。
type: docs
url: /ja/com.aspose.slides/idatalabelformat/
---
**All Implemented Interfaces:**
[com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer)
```
public interface IDataLabelFormat extends IFormattedTextContainer
```

DataLabel の書式設定オプションを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | 読み書き可能なブール値。 |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | 読み書き可能なブール値。 |
| [getNumberFormat()](#getNumberFormat--) | DataLabels オブジェクトの書式文字列を表します。 |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | DataLabels オブジェクトの書式文字列を表します。 |
| [getFormat()](#getFormat--) | データラベルの書式を表します。 |
| [getPosition()](#getPosition--) | データラベルの位置を表します。 |
| [setPosition(int value)](#setPosition-int-) | データラベルの位置を表します。 |
| [getShowLegendKey()](#getShowLegendKey--) | 特定のチャートのデータラベル凡例キーの表示動作を表します。 |
| [setShowLegendKey(boolean value)](#setShowLegendKey-boolean-) | 特定のチャートのデータラベル凡例キーの表示動作を表します。 |
| [getShowValue()](#getShowValue--) | 特定のチャートのデータラベルのパーセンテージ値の表示動作を表します。 |
| [setShowValue(boolean value)](#setShowValue-boolean-) | 特定のチャートのデータラベルのパーセンテージ値の表示動作を表します。 |
| [getShowCategoryName()](#getShowCategoryName--) | 特定のチャートのデータラベルのカテゴリ名の表示動作を表します。 |
| [setShowCategoryName(boolean value)](#setShowCategoryName-boolean-) | 特定のチャートのデータラベルのカテゴリ名の表示動作を表します。 |
| [getShowSeriesName()](#getShowSeriesName--) | チャート上のデータラベルに対するシリーズ名の表示動作を示す Boolean を取得または設定します。 |
| [setShowSeriesName(boolean value)](#setShowSeriesName-boolean-) | チャート上のデータラベルに対するシリーズ名の表示動作を示す Boolean を取得または設定します。 |
| [getShowPercentage()](#getShowPercentage--) | 特定のチャートのデータラベルのパーセンテージ値の表示動作を表します。 |
| [setShowPercentage(boolean value)](#setShowPercentage-boolean-) | 特定のチャートのデータラベルのパーセンテージ値の表示動作を表します。 |
| [getShowBubbleSize()](#getShowBubbleSize--) | 特定のチャートのデータラベルのバブルサイズ値の表示動作を表します。 |
| [setShowBubbleSize(boolean value)](#setShowBubbleSize-boolean-) | 特定のチャートのデータラベルのバブルサイズ値の表示動作を表します。 |
| [getShowLeaderLines()](#getShowLeaderLines--) | 特定のチャートのデータラベルのリーダー線の表示動作を表します。 |
| [setShowLeaderLines(boolean value)](#setShowLeaderLines-boolean-) | 特定のチャートのデータラベルのリーダー線の表示動作を表します。 |
| [getShowLabelAsDataCallout()](#getShowLabelAsDataCallout--) | 特定のチャートのデータラベルがデータ呼び出しとして表示されるか、データラベルとして表示されるかを決定します。 |
| [setShowLabelAsDataCallout(boolean value)](#setShowLabelAsDataCallout-boolean-) | 特定のチャートのデータラベルがデータ呼び出しとして表示されるか、データラベルとして表示されるかを決定します。 |
| [getShowLabelValueFromCell()](#getShowLabelValueFromCell--) | 特定のチャートのデータラベルのセル値の表示動作を表します。 |
| [setShowLabelValueFromCell(boolean value)](#setShowLabelValueFromCell-boolean-) | 特定のチャートのデータラベルのセル値の表示動作を表します。 |
| [getSeparator()](#getSeparator--) | チャート上のデータラベルで使用される区切り文字を表す Variant を設定または取得します。 |
| [setSeparator(String value)](#setSeparator-java.lang.String-) | チャート上のデータラベルで使用される区切り文字を表す Variant を設定または取得します。 |
### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public abstract boolean isNumberFormatLinkedToSource()
```

読み書き可能なブール値。

--------------------

この DataLabelFormat オブジェクトの親が DataLabelCollection（データラベルのコレクション）の場合、このプロパティは DataLabelCollection 内の新しいデータラベルに対する IsNumberFormatLinkedToSource プロパティの既定値を取得または設定します。値を設定すると、その値は DataLabelCollection 内のすべてのデータラベルの IsNumberFormatLinkedToSource プロパティにも設定されます（例：`DataLabels.getDefaultDataLabelFormat().setNumberFormatLinkedToSource(val);` により、すべての `DataLabels.get_Item(i).isNumberFormatLinkedToSource()` が val と同じになります）。

**戻り値:**  
boolean
### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public abstract void setNumberFormatLinkedToSource(boolean value)
```

読み書き可能なブール値。

--------------------

この DataLabelFormat オブジェクトの親が DataLabelCollection（データラベルのコレクション）の場合、このプロパティは DataLabelCollection 内の新しいデータラベルに対する IsNumberFormatLinkedToSource プロパティの既定値を取得または設定します。値を設定すると、その値は DataLabelCollection 内のすべてのデータラベルの IsNumberFormatLinkedToSource プロパティにも設定されます（例：`DataLabels.getDefaultDataLabelFormat().setNumberFormatLinkedToSource(val);` により、すべての `DataLabels.get_Item(i).isNumberFormatLinkedToSource()` が val と同じになります）。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |
### getNumberFormat() {#getNumberFormat--}
```
public abstract String getNumberFormat()
```

DataLabels オブジェクトの書式文字列を表します。読み書き可能な String。

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```

--------------------

この DataLabelFormat オブジェクトの親が DataLabelCollection（データラベルのコレクション）の場合、このプロパティは DataLabelCollection 内の新しいデータラベルに対する NumberFormat プロパティの既定値を取得または設定します。値を設定すると、その値は DataLabelCollection 内のすべてのデータラベルの NumberFormat プロパティにも設定されます（例：`DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);` により、すべての `DataLabels.get_Item(i).getNumberFormat()` が val と同じになります）。

**戻り値:**  
java.lang.String
### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public abstract void setNumberFormat(String value)
```

DataLabels オブジェクトの書式文字列を表します。読み書き可能な String。

--------------------

> ```
> series.getLabels().getDefaultDataLabelFormat().setShowValue(true);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormatLinkedToSource(false);
>  series.getLabels().getDefaultDataLabelFormat().setNumberFormat("0.0%");
> ```


--------------------

この DataLabelFormat オブジェクトの親が DataLabelCollection（データラベルのコレクション）の場合、このプロパティは DataLabelCollection 内の新しいデータラベルに対する NumberFormat プロパティの既定値を取得または設定します。値を設定すると、その値は DataLabelCollection 内のすべてのデータラベルの NumberFormat プロパティにも設定されます（例：`DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);` により、すべての `DataLabels.get_Item(i).getNumberFormat()` が val と同じになります）。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

データラベルの書式を表します。読み取り専用 [IFormat](../../com.aspose.slides/iformat)。

--------------------

この DataLabelFormat オブジェクトの親が DataLabelCollection（データラベルのコレクション）の場合、このプロパティは DataLabelCollection 内の新しいデータラベルに対する既定の書式を表します。

**戻り値:**  
[IFormat](../../com.aspose.slides/iformat)
### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

データラベルの位置を表します。読み書き可能な [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition)。

--------------------

この DataLabelFormat オブジェクトの親が DataLabelCollection（データラベルのコレクション）の場合、このプロパティは DataLabelCollection 内の新しいデータラベルに対する Position プロパティの既定値を取得または設定します。DataLabel オブジェクトの位置を表します。値を設定すると、その値は DataLabelCollection 内のすべてのデータラベルの Position プロパティにも設定されます（例：`DataLabels.getDefaultDataLabelFormat().setPosition(val)` により、すべての `DataLabels.get_Item(i).getPosition()` が val と同じになります）。

**戻り値:**  
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

データラベルの位置を表します。読み書き可能な [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition)。

--------------------

この DataLabelFormat オブジェクトの親が DataLabelCollection（データラベルのコレクション）の場合、このプロパティは DataLabelCollection 内の新しいデータラベルに対する Position プロパティの既定値を取得または設定します。DataLabel オブジェクトの位置を表します。値を設定すると、その値は DataLabelCollection 内のすべてのデータラベルの Position プロパティにも設定されます（例：`DataLabels.getDefaultDataLabelFormat().setPosition(val)` により、すべての `DataLabels.get_Item(i).getPosition()` が val と同じになります）。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |
### getShowLegendKey() {#getShowLegendKey--}
```
public abstract boolean getShowLegendKey()
```

特定のチャートのデータラベル凡例キーの表示動作を表します。データラベル凡例キーが表示されている場合は true、非表示の場合は false です。読み書き可能なブール値。

--------------------

この DataLabelFormat オブジェクトの親が DataLabelCollection（データラベルのコレクション）の場合、このプロパティは DataLabelCollection 内の新しいデータラベルに対する ShowLegendKey プロパティの既定値を取得または設定します。値を設定すると、その値は DataLabelCollection 内のすべてのデータラベルの ShowLegendKey プロパティにも設定されます（例：`DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);` により、すべての `DataLabels.get_Item(i).getShowLegendKey()` が val と同じになります）。

**戻り値:**  
boolean
### setShowLegendKey(boolean value) {#setShowLegendKey-boolean-}
```
public abstract void setShowLegendKey(boolean value)
```

特定のチャートのデータラベル凡例キーの表示動作を表します。データラベル凡例キーが表示されている場合は true、非表示の場合は false です。読み書き可能なブール値。

--------------------

この DataLabelFormat オブジェクトの親が DataLabelCollection（データラベルのコレクション）の場合、このプロパティは DataLabelCollection 内の新しいデータラベルに対する ShowLegendKey プロパティの既定値を取得または設定します。値を設定すると、その値は DataLabelCollection 内のすべてのデータラベルの ShowLegendKey プロパティにも設定されます（例：`DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);` により、すべての `DataLabels.get_Item(i).getShowLegendKey()` が val と同じになります）。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |
### getShowValue() {#getShowValue--}
```
public abstract boolean getShowValue()
```

特定のチャートのデータラベルのパーセンテージ値の表示動作を表します。true の場合はパーセンテージ値を表示し、false の場合は非表示にします。読み書き可能なブール値。

--------------------

この DataLabelFormat オブジェクトの親が DataLabelCollection（データラベルのコレクション）の場合、このプロパティは DataLabelCollection 内の新しいデータラベルに対する ShowValue プロパティの既定値を取得または設定します。値を設定すると、その値は DataLabelCollection 内のすべてのデータラベルの ShowValue プロパティにも設定されます（例：`DataLabels.getDefaultDataLabelFormat().setShowValue(val);` により、すべての `DataLabels.get_Item(i).getShowValue()` が val と同じになります）。

**戻り値:**  
boolean
### setShowValue(boolean value) {#setShowValue-boolean-}
```
public abstract void setShowValue(boolean value)
```

特定のチャートのデータラベルのパーセンテージ値の表示動作を表します。true の場合はパーセンテージ値を表示し、false の場合は非表示にします。読み書き可能なブール値。

--------------------

この DataLabelFormat オブジェクトの親が DataLabelCollection（データラベルのコレクション）の場合、このプロパティは DataLabelCollection 内の新しいデータラベルに対する ShowValue プロパティの既定値を取得または設定します。値を設定すると、その値は DataLabelCollection 内のすべてのデータラベルの ShowValue プロパティにも設定されます（例：`DataLabels.getDefaultDataLabelFormat().setShowValue(val);` により、すべての `DataLabels.get_Item(i).getShowValue()` が val と同じになります）。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |
### getShowCategoryName() {#getShowCategoryName--}
```
public abstract boolean getShowCategoryName()
```

特定のチャートのデータラベルのカテゴリ名の表示動作を表します。true の場合はカテゴリ名を表示し、false の場合は非表示にします。読み書き可能なブール値。

--------------------

この DataLabelFormat オブジェクトの親が DataLabelCollection（データラベルのコレクション）の場合、このプロパティは DataLabelCollection 内の新しいデータラベルに対する ShowCategoryName プロパティの既定値を取得または設定します。値を設定すると、その値は DataLabelCollection 内のすべてのデータラベルの ShowCategoryName プロパティにも設定されます（例：`DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);` により、すべての `DataLabels.get_Item(i).getShowCategoryName()` が val と同じになります）。

**戻り値:**  
boolean
### setShowCategoryName(boolean value) {#setShowCategoryName-boolean-}
```
public abstract void setShowCategoryName(boolean value)
```

特定のチャートのデータラベルのカテゴリ名の表示動作を表します。true の場合はカテゴリ名を表示し、false の場合は非表示にします。読み書き可能なブール値。

--------------------
If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowCategoryName property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowCategoryName property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" cause to all DataLabels.get\_Item(i).getShowCategoryName() is equal to val).

この DataLabelFormat オブジェクトの親が DataLabelCollection（データ ラベルのコレクション）である場合、このプロパティは DataLabelCollection 内の新しいデータ ラベルに対する ShowCategoryName プロパティのデフォルト値を取得または設定します。値を設定すると、この値は DataLabelCollection 内のすべてのデータ ラベルの ShowCategoryName プロパティにも設定されます（例: "DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);" により、すべての DataLabels.get\_Item(i).getShowCategoryName() が val と等しくなります）。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getShowSeriesName() {#getShowSeriesName--}
```
public abstract boolean getShowSeriesName()
```

チャート上のデータ ラベルの系列名表示動作を示す Boolean を取得または設定します。True で系列名を表示し、False で非表示にします。読み書き可能な boolean。

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowSeriesName property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowSeriesName property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" cause to all DataLabels.get\_Item(i).getShowSeriesName() is equal to val).

この DataLabelFormat オブジェクトの親が DataLabelCollection（データ ラベルのコレクション）である場合、このプロパティは DataLabelCollection 内の新しいデータ ラベルに対する ShowSeriesName プロパティのデフォルト値を取得または設定します。値を設定すると、この値は DataLabelCollection 内のすべてのデータ ラベルの ShowSeriesName プロパティにも設定されます（例: "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" により、すべての DataLabels.get\_Item(i).getShowSeriesName() が val と等しくなります）。

**戻り値:**
boolean
### setShowSeriesName(boolean value) {#setShowSeriesName-boolean-}
```
public abstract void setShowSeriesName(boolean value)
```

チャート上のデータ ラベルの系列名表示動作を示す Boolean を取得または設定します。True で系列名を表示し、False で非表示にします。読み書き可能な boolean。

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowSeriesName property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowSeriesName property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" cause to all DataLabels.get\_Item(i).getShowSeriesName() is equal to val).

この DataLabelFormat オブジェクトの親が DataLabelCollection（データ ラベルのコレクション）である場合、このプロパティは DataLabelCollection 内の新しいデータ ラベルに対する ShowSeriesName プロパティのデフォルト値を取得または設定します。値を設定すると、この値は DataLabelCollection 内のすべてのデータ ラベルの ShowSeriesName プロパティにも設定されます（例: "DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);" により、すべての DataLabels.get\_Item(i).getShowSeriesName() が val と等しくなります）。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getShowPercentage() {#getShowPercentage--}
```
public abstract boolean getShowPercentage()
```

指定されたチャートのデータ ラベルのパーセンテージ値表示動作を表します。True でパーセンテージ値を表示し、False で非表示にします。読み書き可能な boolean。

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowPercentage property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowPercentage property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" cause to all DataLabels.get\_Item(i).getShowPercentage() is equal to val).

この DataLabelFormat オブジェクトの親が DataLabelCollection（データ ラベルのコレクション）である場合、このプロパティは DataLabelCollection 内の新しいデータ ラベルに対する ShowPercentage プロパティのデフォルト値を取得または設定します。値を設定すると、この値は DataLabelCollection 内のすべてのデータ ラベルの ShowPercentage プロパティにも設定されます（例: "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" により、すべての DataLabels.get\_Item(i).getShowPercentage() が val と等しくなります）。

**戻り値:**
boolean
### setShowPercentage(boolean value) {#setShowPercentage-boolean-}
```
public abstract void setShowPercentage(boolean value)
```

指定されたチャートのデータ ラベルのパーセンテージ値表示動作を表します。True でパーセンテージ値を表示し、False で非表示にします。読み書き可能な boolean。

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowPercentage property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowPercentage property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" cause to all DataLabels.get\_Item(i).getShowPercentage() is equal to val).

この DataLabelFormat オブジェクトの親が DataLabelCollection（データ ラベルのコレクション）である場合、このプロパティは DataLabelCollection 内の新しいデータ ラベルに対する ShowPercentage プロパティのデフォルト値を取得または設定します。値を設定すると、この値は DataLabelCollection 内のすべてのデータ ラベルの ShowPercentage プロパティにも設定されます（例: "DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);" により、すべての DataLabels.get\_Item(i).getShowPercentage() が val と等しくなります）。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getShowBubbleSize() {#getShowBubbleSize--}
```
public abstract boolean getShowBubbleSize()
```

指定されたチャートのデータ ラベルのバブルサイズ値表示動作を表します。True でバブルサイズ値を表示し、False で非表示にします。読み書き可能な boolean。

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowBubbleSize property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowBubbleSize property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" cause to all DataLabels.get\_Item(i).getShowBubbleSize() is equal to val).

この DataLabelFormat オブジェクトの親が DataLabelCollection（データ ラベルのコレクション）である場合、このプロパティは DataLabelCollection 内の新しいデータ ラベルに対する ShowBubbleSize プロパティのデフォルト値を取得または設定します。値を設定すると、この値は DataLabelCollection 内のすべてのデータ ラベルの ShowBubbleSize プロパティにも設定されます（例: "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" により、すべての DataLabels.get\_Item(i).getShowBubbleSize() が val と等しくなります）。

**戻り値:**
boolean
### setShowBubbleSize(boolean value) {#setShowBubbleSize-boolean-}
```
public abstract void setShowBubbleSize(boolean value)
```

指定されたチャートのデータ ラベルのバブルサイズ値表示動作を表します。True でバブルサイズ値を表示し、False で非表示にします。読み書き可能な boolean。

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowBubbleSize property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowBubbleSize property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" cause to all DataLabels.get\_Item(i).getShowBubbleSize() is equal to val).

この DataLabelFormat オブジェクトの親が DataLabelCollection（データ ラベルのコレクション）である場合、このプロパティは DataLabelCollection 内の新しいデータ ラベルに対する ShowBubbleSize プロパティのデフォルト値を取得または設定します。値を設定すると、この値は DataLabelCollection 内のすべてのデータ ラベルの ShowBubbleSize プロパティにも設定されます（例: "DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);" により、すべての DataLabels.get\_Item(i).getShowBubbleSize() が val と等しくなります）。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getShowLeaderLines() {#getShowLeaderLines--}
```
public abstract boolean getShowLeaderLines()
```

指定されたチャートのデータ ラベルのリーダー線表示動作を表します。True でリーダー線を表示し、False で非表示にします。読み書き可能な boolean。

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowLeaderLines property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowLeaderLines property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" cause to all DataLabels.get\_Item(i).getShowLeaderLines() is equal to val).

この DataLabelFormat オブジェクトの親が DataLabelCollection（データ ラベルのコレクション）である場合、このプロパティは DataLabelCollection 内の新しいデータ ラベルに対する ShowLeaderLines プロパティのデフォルト値を取得または設定します。値を設定すると、この値は DataLabelCollection 内のすべてのデータ ラベルの ShowLeaderLines プロパティにも設定されます（例: "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" により、すべての DataLabels.get\_Item(i).getShowLeaderLines() が val と等しくなります）。

**戻り値:**
boolean
### setShowLeaderLines(boolean value) {#setShowLeaderLines-boolean-}
```
public abstract void setShowLeaderLines(boolean value)
```

指定されたチャートのデータ ラベルのリーダー線表示動作を表します。True でリーダー線を表示し、False で非表示にします。読み書き可能な boolean。

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowLeaderLines property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowLeaderLines property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" cause to all DataLabels.get\_Item(i).getShowLeaderLines() is equal to val).

この DataLabelFormat オブジェクトの親が DataLabelCollection（データ ラベルのコレクション）である場合、このプロパティは DataLabelCollection 内の新しいデータ ラベルに対する ShowLeaderLines プロパティのデフォルト値を取得または設定します。値を設定すると、この値は DataLabelCollection 内のすべてのデータ ラベルの ShowLeaderLines プロパティにも設定されます（例: "DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);" により、すべての DataLabels.get\_Item(i).getShowLeaderLines() が val と等しくなります）。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelAsDataCallout() {#getShowLabelAsDataCallout--}
```
public abstract boolean getShowLabelAsDataCallout()
```

指定されたチャートのデータ ラベルがデータ コールアウトとして表示されるか、データ ラベルとして表示されるかを決定します。

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowLabelAsDataCallout property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowLabelAsDataCallout property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" cause to all DataLabels.get\_Item(i).getShowLabelAsDataCallout() is equal to val).

この DataLabelFormat オブジェクトの親が DataLabelCollection（データ ラベルのコレクション）である場合、このプロパティは DataLabelCollection 内の新しいデータ ラベルに対する ShowLabelAsDataCallout プロパティのデフォルト値を取得または設定します。値を設定すると、この値は DataLabelCollection 内のすべてのデータ ラベルの ShowLabelAsDataCallout プロパティにも設定されます（例: "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" により、すべての DataLabels.get\_Item(i).getShowLabelAsDataCallout() が val と等しくなります）。

**戻り値:**
boolean
### setShowLabelAsDataCallout(boolean value) {#setShowLabelAsDataCallout-boolean-}
```
public abstract void setShowLabelAsDataCallout(boolean value)
```

指定されたチャートのデータ ラベルがデータ コールアウトとして表示されるか、データ ラベルとして表示されるかを決定します。

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowLabelAsDataCallout property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowLabelAsDataCallout property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" cause to all DataLabels.get\_Item(i).getShowLabelAsDataCallout() is equal to val).

この DataLabelFormat オブジェクトの親が DataLabelCollection（データ ラベルのコレクション）である場合、このプロパティは DataLabelCollection 内の新しいデータ ラベルに対する ShowLabelAsDataCallout プロパティのデフォルト値を取得または設定します。値を設定すると、この値は DataLabelCollection 内のすべてのデータ ラベルの ShowLabelAsDataCallout プロパティにも設定されます（例: "DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);" により、すべての DataLabels.get\_Item(i).getShowLabelAsDataCallout() が val と等しくなります）。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getShowLabelValueFromCell() {#getShowLabelValueFromCell--}
```
public abstract boolean getShowLabelValueFromCell()
```

指定されたチャートのデータ ラベルのセル値表示動作を表します。True でセル値を表示し、False で非表示にします。読み書き可能な boolean。

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowLabelValueFromCell property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowLabelValueFromCell property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" cause to all DataLabels.get\_Item(i).getShowLabelValueFromCell() is equal to val).

この DataLabelFormat オブジェクトの親が DataLabelCollection（データ ラベルのコレクション）である場合、このプロパティは DataLabelCollection 内の新しいデータ ラベルに対する ShowLabelValueFromCell プロパティのデフォルト値を取得または設定します。値を設定すると、この値は DataLabelCollection 内のすべてのデータ ラベルの ShowLabelValueFromCell プロパティにも設定されます（例: "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" により、すべての DataLabels.get\_Item(i).getShowLabelValueFromCell() が val と等しくなります）。

**戻り値:**
boolean
### setShowLabelValueFromCell(boolean value) {#setShowLabelValueFromCell-boolean-}
```
public abstract void setShowLabelValueFromCell(boolean value)
```

指定されたチャートのデータ ラベルのセル値表示動作を表します。True でセル値を表示し、False で非表示にします。読み書き可能な boolean。

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the ShowLabelValueFromCell property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the ShowLabelValueFromCell property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" cause to all DataLabels.get\_Item(i).getShowLabelValueFromCell() is equal to val).

この DataLabelFormat オブジェクトの親が DataLabelCollection（データ ラベルのコレクション）である場合、このプロパティは DataLabelCollection 内の新しいデータ ラベルに対する ShowLabelValueFromCell プロパティのデフォルト値を取得または設定します。値を設定すると、この値は DataLabelCollection 内のすべてのデータ ラベルの ShowLabelValueFromCell プロパティにも設定されます（例: "DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);" により、すべての DataLabels.get\_Item(i).getShowLabelValueFromCell() が val と等しくなります）。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getSeparator() {#getSeparator--}
```
public abstract String getSeparator()
```

チャート上のデータ ラベルで使用される区切り文字を表す Variant を取得または設定します。読み書き可能な String。

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the Separator property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the Separator property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" cause to all DataLabels.get\_Item(i).getSeparator() is equal to val).

この DataLabelFormat オブジェクトの親が DataLabelCollection（データ ラベルのコレクション）である場合、このプロパティは DataLabelCollection 内の新しいデータ ラベルに対する Separator プロパティのデフォルト値を取得または設定します。値を設定すると、この値は DataLabelCollection 内のすべてのデータ ラベルの Separator プロパティにも設定されます（例: "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" により、すべての DataLabels.get\_Item(i).getSeparator() が val と等しくなります）。

**戻り値:**
java.lang.String
### setSeparator(String value) {#setSeparator-java.lang.String-}
```
public abstract void setSeparator(String value)
```

チャート上のデータ ラベルで使用される区切り文字を表す Variant を取得または設定します。読み書き可能な String。

--------------------

If parent of this DataLabelFormat object is a DataLabelCollection collection of data labels then this property gets or sets the default value of the Separator property for the new data labels in the DataLabelCollection collection. Set this property with value also sets this value to the Separator property for all data labels in the DataLabelCollection collection (i.e. "DataLabels.getDefaultDataLabelFormat().setSeparator(val);" cause to all DataLabels.get\_Item(i).getSeparator() is equal to val).
**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |