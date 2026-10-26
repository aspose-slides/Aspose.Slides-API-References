---
title: IDataLabelFormat
second_title: Java API リファレンスによる Aspose.Slides for Android
description: DataLabel の書式設定オプションを表します。
type: docs
url: /ja/com.aspose.slides/idatalabelformat/
---
**実装されているすべてのインターフェイス:**
[com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer)
```
public interface IDataLabelFormat extends IFormattedTextContainer
```

DataLabel の書式設定オプションを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | 読み書き可能な boolean。 |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | 読み書き可能な boolean。 |
| [getNumberFormat()](#getNumberFormat--) | DataLabels オブジェクトの書式文字列を表します。 |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | DataLabels オブジェクトの書式文字列を表します。 |
| [getFormat()](#getFormat--) | データラベルの書式を表します。 |
| [getPosition()](#getPosition--) | データラベルの位置を表します。 |
| [setPosition(int value)](#setPosition-int-) | データラベルの位置を表します。 |
| [getShowLegendKey()](#getShowLegendKey--) | 指定されたチャートのデータラベルの凡例キー表示動作を表します。 |
| [setShowLegendKey(boolean value)](#setShowLegendKey-boolean-) | 指定されたチャートのデータラベルの凡例キー表示動作を表します。 |
| [getShowValue()](#getShowValue--) | 指定されたチャートのデータラベルのパーセンテージ値表示動作を表します。 |
| [setShowValue(boolean value)](#setShowValue-boolean-) | 指定されたチャートのデータラベルのパーセンテージ値表示動作を表します。 |
| [getShowCategoryName()](#getShowCategoryName--) | 指定されたチャートのデータラベルのカテゴリ名表示動作を表します。 |
| [setShowCategoryName(boolean value)](#setShowCategoryName-boolean-) | 指定されたチャートのデータラベルのカテゴリ名表示動作を表します。 |
| [getShowSeriesName()](#getShowSeriesName--) | チャート上のデータラベルのシリーズ名表示動作を示す Boolean を取得または設定します。 |
| [setShowSeriesName(boolean value)](#setShowSeriesName-boolean-) | チャート上のデータラベルのシリーズ名表示動作を示す Boolean を取得または設定します。 |
| [getShowPercentage()](#getShowPercentage--) | 指定されたチャートのデータラベルのパーセンテージ値表示動作を表します。 |
| [setShowPercentage(boolean value)](#setShowPercentage-boolean-) | 指定されたチャートのデータラベルのパーセンテージ値表示動作を表します。 |
| [getShowBubbleSize()](#getShowBubbleSize--) | 指定されたチャートのデータラベルのバブルサイズ値表示動作を表します。 |
| [setShowBubbleSize(boolean value)](#setShowBubbleSize-boolean-) | 指定されたチャートのデータラベルのバブルサイズ値表示動作を表します。 |
| [getShowLeaderLines()](#getShowLeaderLines--) | 指定されたチャートのデータラベルのリーダーライン表示動作を表します。 |
| [setShowLeaderLines(boolean value)](#setShowLeaderLines-boolean-) | 指定されたチャートのデータラベルのリーダーライン表示動作を表します。 |
| [getShowLabelAsDataCallout()](#getShowLabelAsDataCallout--) | 指定されたチャートのデータラベルがデータコールアウトとして表示されるかデータラベルとして表示されるかを決定します。 |
| [setShowLabelAsDataCallout(boolean value)](#setShowLabelAsDataCallout-boolean-) | 指定されたチャートのデータラベルがデータコールアウトとして表示されるかデータラベルとして表示されるかを決定します。 |
| [getShowLabelValueFromCell()](#getShowLabelValueFromCell--) | 指定されたチャートのデータラベルのセル値表示動作を表します。 |
| [setShowLabelValueFromCell(boolean value)](#setShowLabelValueFromCell-boolean-) | 指定されたチャートのデータラベルのセル値表示動作を表します。 |
| [getSeparator()](#getSeparator--) | チャート上のデータラベルで使用される区切り文字を表す Variant を設定または取得します。 |
| [setSeparator(String value)](#setSeparator-java.lang.String-) | チャート上のデータラベルで使用される区切り文字を表す Variant を設定または取得します。 |
### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public abstract boolean isNumberFormatLinkedToSource()
```


読み書き可能な boolean。

--------------------

DataLabelFormat オブジェクトの親が DataLabelCollection コレクションの場合、このプロパティは新しいデータラベルの IsNumberFormatLinkedToSource プロパティのデフォルト値を取得または設定します。値を設定すると、DataLabelCollection 内のすべてのデータラベルの IsNumberFormatLinkedToSource プロパティにも同じ値が設定されます (例: `"DataLabels.getDefaultDataLabelFormat().setNumberFormatLinkedToSource(val);"` によりすべての `DataLabels.get_Item(i).isNumberFormatLinkedToSource()` が `val` と等しくなります)。

**戻り値:**
boolean
### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public abstract void setNumberFormatLinkedToSource(boolean value)
```


読み書き可能な boolean。

--------------------

DataLabelFormat オブジェクトの親が DataLabelCollection コレクションの場合、このプロパティは新しいデータラベルの IsNumberFormatLinkedToSource プロパティのデフォルト値を取得または設定します。値を設定すると、DataLabelCollection 内のすべてのデータラベルの IsNumberFormatLinkedToSource プロパティにも同じ値が設定されます (例: `"DataLabels.getDefaultDataLabelFormat().setNumberFormatLinkedToSource(val);"` によりすべての `DataLabels.get_Item(i).isNumberFormatLinkedToSource()` が `val` と等しくなります)。

**パラメータ:**
| パラメータ | 型 | 説明 |
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

DataLabelFormat オブジェクトの親が DataLabelCollection コレクションの場合、このプロパティは新しいデータラベルの NumberFormat プロパティのデフォルト値を取得または設定します。値を設定すると、DataLabelCollection 内のすべてのデータラベルの NumberFormat プロパティにも同じ値が設定されます (例: `"DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);"` によりすべての `DataLabels.get_Item(i).getNumberFormat()` が `val` と等しくなります)。

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

DataLabelFormat オブジェクトの親が DataLabelCollection コレクションの場合、このプロパティは新しいデータラベルの NumberFormat プロパティのデフォルト値を取得または設定します。値を設定すると、DataLabelCollection 内のすべてのデータラベルの NumberFormat プロパティにも同じ値が設定されます (例: `"DataLabels.getDefaultDataLabelFormat().setNumberFormat(val);"` によりすべての `DataLabels.get_Item(i).getNumberFormat()` が `val` と等しくなります)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```


データラベルの書式を表します。読み取り専用 [IFormat](../../com.aspose.slides/iformat)。

--------------------

DataLabelFormat オブジェクトの親が DataLabelCollection コレクションの場合、このプロパティは新しいデータラベルのデフォルト書式を表します。

**戻り値:**
[IFormat](../../com.aspose.slides/iformat)
### getPosition() {#getPosition--}
```
public abstract int getPosition()
```


データラベルの位置を表します。読み書き可能な [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition)。

--------------------

DataLabelFormat オブジェクトの親が DataLabelCollection コレクションの場合、このプロパティは新しいデータラベルの Position プロパティのデフォルト値を取得または設定します。DataLabel オブジェクトの位置を表します。値を設定すると、DataLabelCollection 内のすべてのデータラベルの Position プロパティにも同じ値が設定されます (例: `"DataLabels.getDefaultDataLabelFormat().setPosition(val)"` によりすべての `DataLabels.get_Item(i).getPosition()` が `val` と等しくなります)。

**戻り値:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```


データラベルの位置を表します。読み書き可能な [LegendDataLabelPosition](../../com.aspose.slides/legenddatalabelposition)。

--------------------

DataLabelFormat オブジェクトの親が DataLabelCollection コレクションの場合、このプロパティは新しいデータラベルの Position プロパティのデフォルト値を取得または設定します。DataLabel オブジェクトの位置を表します。値を設定すると、DataLabelCollection 内のすべてのデータラベルの Position プロパティにも同じ値が設定されます (例: `"DataLabels.getDefaultDataLabelFormat().setPosition(val)"` によりすべての `DataLabels.get_Item(i).getPosition()` が `val` と等しくなります)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |
### getShowLegendKey() {#getShowLegendKey--}
```
public abstract boolean getShowLegendKey()
```


指定されたチャートのデータラベルの凡例キー表示動作を表します。凡例キーが表示されている場合は true。読み書き可能な boolean。

--------------------

DataLabelFormat オブジェクトの親が DataLabelCollection コレクションの場合、このプロパティは新しいデータラベルの ShowLegendKey プロパティのデフォルト値を取得または設定します。値を設定すると、DataLabelCollection 内のすべてのデータラベルの ShowLegendKey プロパティにも同じ値が設定されます (例: `"DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);"` によりすべての `DataLabels.get_Item(i).getShowLegendKey()` が `val` と等しくなります)。

**戻り値:**
boolean
### setShowLegendKey(boolean value) {#setShowLegendKey-boolean-}
```
public abstract void setShowLegendKey(boolean value)
```


指定されたチャートのデータラベルの凡例キー表示動作を表します。凡例キーが表示されている場合は true。読み書き可能な boolean。

--------------------

DataLabelFormat オブジェクトの親が DataLabelCollection コレクションの場合、このプロパティは新しいデータラベルの ShowLegendKey プロパティのデフォルト値を取得または設定します。値を設定すると、DataLabelCollection 内のすべてのデータラベルの ShowLegendKey プロパティにも同じ値が設定されます (例: `"DataLabels.getDefaultDataLabelFormat().setShowLegendKey(val);"` によりすべての `DataLabels.get_Item(i).getShowLegendKey()` が `val` と等しくなります)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |
### getShowValue() {#getShowValue--}
```
public abstract boolean getShowValue()
```


指定されたチャートのデータラベルのパーセンテージ値表示動作を表します。true の場合はパーセンテージ値を表示し、false の場合は非表示にします。読み書き可能な boolean。

--------------------

DataLabelFormat オブジェクトの親が DataLabelCollection コレクションの場合、このプロパティは新しいデータラベルの ShowValue プロパティのデフォルト値を取得または設定します。値を設定すると、DataLabelCollection 内のすべてのデータラベルの ShowValue プロパティにも同じ値が設定されます (例: `"DataLabels.getDefaultDataLabelFormat().setShowValue(val);"` によりすべての `DataLabels.get_Item(i).getShowValue()` が `val` と等しくなります)。

**戻り値:**
boolean
### setShowValue(boolean value) {#setShowValue-boolean-}
```
public abstract void setShowValue(boolean value)
```


指定されたチャートのデータラベルのパーセンテージ値表示動作を表します。true の場合はパーセンテージ値を表示し、false の場合は非表示にします。読み書き可能な boolean。

--------------------

DataLabelFormat オブジェクトの親が DataLabelCollection コレクションの場合、このプロパティは新しいデータラベルの ShowValue プロパティのデフォルト値を取得または設定します。値を設定すると、DataLabelCollection 内のすべてのデータラベルの ShowValue プロパティにも同じ値が設定されます (例: `"DataLabels.getDefaultDataLabelFormat().setShowValue(val);"` によりすべての `DataLabels.get_Item(i).getShowValue()` が `val` と等しくなります)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |
### getShowCategoryName() {#getShowCategoryName--}
```
public abstract boolean getShowCategoryName()
```


指定されたチャートのデータラベルのカテゴリ名表示動作を表します。true の場合はカテゴリ名を表示し、false の場合は非表示にします。読み書き可能な boolean。

--------------------

DataLabelFormat オブジェクトの親が DataLabelCollection コレクションの場合、このプロパティは新しいデータラベルの ShowCategoryName プロパティのデフォルト値を取得または設定します。値を設定すると、DataLabelCollection 内のすべてのデータラベルの ShowCategoryName プロパティにも同じ値が設定されます (例: `"DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);"` によりすべての `DataLabels.get_Item(i).getShowCategoryName()` が `val` と等しくなります)。

**戻り値:**
boolean
### setShowCategoryName(boolean value) {#setShowCategoryName-boolean-}
```
public abstract void setShowCategoryName(boolean value)
```


指定されたチャートのデータラベルのカテゴリ名表示動作を表します。true の場合はカテゴリ名を表示し、false の場合は非表示にします。読み書き可能な boolean。

--------------------

DataLabelFormat オブジェクトの親が DataLabelCollection コレクションの場合、このプロパティは新しいデータラベルの ShowCategoryName プロパティのデフォルト値を取得または設定します。値を設定すると、DataLabelCollection 内のすべてのデータラベルの ShowCategoryName プロパティにも同じ値が設定されます (例: `"DataLabels.getDefaultDataLabelFormat().setShowCategoryName(val);"` によりすべての `DataLabels.get_Item(i).getShowCategoryName()` が `val` と等しくなります)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |
### getShowSeriesName() {#getShowSeriesName--}
```
public abstract boolean getShowSeriesName()
```


チャート上のデータラベルのシリーズ名表示動作を示す Boolean を取得または設定します。true の場合はシリーズ名を表示し、false の場合は非表示にします。読み書き可能な boolean。

--------------------

DataLabelFormat オブジェクトの親が DataLabelCollection コレクションの場合、このプロパティは新しいデータラベルの ShowSeriesName プロパティのデフォルト値を取得または設定します。値を設定すると、DataLabelCollection 内のすべてのデータラベルの ShowSeriesName プロパティにも同じ値が設定されます (例: `"DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);"` によりすべての `DataLabels.get_Item(i).getShowSeriesName()` が `val` と等しくなります)。

**戻り値:**
boolean
### setShowSeriesName(boolean value) {#setShowSeriesName-boolean-}
```
public abstract void setShowSeriesName(boolean value)
```


チャート上のデータラベルのシリーズ名表示動作を示す Boolean を取得または設定します。true の場合はシリーズ名を表示し、false の場合は非表示にします。読み書き可能な boolean。

--------------------

DataLabelFormat オブジェクトの親が DataLabelCollection コレクションの場合、このプロパティは新しいデータラベルの ShowSeriesName プロパティのデフォルト値を取得または設定します。値を設定すると、DataLabelCollection 内のすべてのデータラベルの ShowSeriesName プロパティにも同じ値が設定されます (例: `"DataLabels.getDefaultDataLabelFormat().setShowSeriesName(val);"` によりすべての `DataLabels.get_Item(i).getShowSeriesName()` が `val` と等しくなります)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |
### getShowPercentage() {#getShowPercentage--}
```
public abstract boolean getShowPercentage()
```


指定されたチャートのデータラベルのパーセンテージ値表示動作を表します。true の場合はパーセンテージ値を表示し、false の場合は非表示にします。読み書き可能な boolean。

--------------------

DataLabelFormat オブジェクトの親が DataLabelCollection コレクションの場合、このプロパティは新しいデータラベルの ShowPercentage プロパティのデフォルト値を取得または設定します。値を設定すると、DataLabelCollection 内のすべてのデータラベルの ShowPercentage プロパティにも同じ値が設定されます (例: `"DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);"` によりすべての `DataLabels.get_Item(i).getShowPercentage()` が `val` と等しくなります)。

**戻り値:**
boolean
### setShowPercentage(boolean value) {#setShowPercentage-boolean-}
```
public abstract void setShowPercentage(boolean value)
```


指定されたチャートのデータラベルのパーセンテージ値表示動作を表します。true の場合はパーセンテージ値を表示し、false の場合は非表示にします。読み書き可能な boolean。

--------------------

DataLabelFormat オブジェクトの親が DataLabelCollection コレクションの場合、このプロパティは新しいデータラベルの ShowPercentage プロパティのデフォルト値を取得または設定します。値を設定すると、DataLabelCollection 内のすべてのデータラベルの ShowPercentage プロパティにも同じ値が設定されます (例: `"DataLabels.getDefaultDataLabelFormat().setShowPercentage(val);"` によりすべての `DataLabels.get_Item(i).getShowPercentage()` が `val` と等しくなります)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |
### getShowBubbleSize() {#getShowBubbleSize--}
```
public abstract boolean getShowBubbleSize()
```


指定されたチャートのデータラベルのバブルサイズ値表示動作を表します。true の場合はバブルサイズ値を表示し、false の場合は非表示にします。読み書き可能な boolean。

--------------------

DataLabelFormat オブジェクトの親が DataLabelCollection コレクションの場合、このプロパティは新しいデータラベルの ShowBubbleSize プロパティのデフォルト値を取得または設定します。値を設定すると、DataLabelCollection 内のすべてのデータラベルの ShowBubbleSize プロパティにも同じ値が設定されます (例: `"DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);"` によりすべての `DataLabels.get_Item(i).getShowBubbleSize()` が `val` と等しくなります)。

**戻り値:**
boolean
### setShowBubbleSize(boolean value) {#setShowBubbleSize-boolean-}
```
public abstract void setShowBubbleSize(boolean value)
```


指定されたチャートのデータラベルのバブルサイズ値表示動作を表します。true の場合はバブルサイズ値を表示し、false の場合は非表示にします。読み書き可能な boolean。

--------------------

DataLabelFormat オブジェクトの親が DataLabelCollection コレクションの場合、このプロパティは新しいデータラベルの ShowBubbleSize プロパティのデフォルト値を取得または設定します。値を設定すると、DataLabelCollection 内のすべてのデータラベルの ShowBubbleSize プロパティにも同じ値が設定されます (例: `"DataLabels.getDefaultDataLabelFormat().setShowBubbleSize(val);"` によりすべての `DataLabels.get_Item(i).getShowBubbleSize()` が `val` と等しくなります)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |
### getShowLeaderLines() {#getShowLeaderLines--}
```
public abstract boolean getShowLeaderLines()
```


指定されたチャートのデータラベルのリーダーライン表示動作を表します。true の場合はリーダーラインを表示し、false の場合は非表示にします。読み書き可能な boolean。

--------------------

DataLabelFormat オブジェクトの親が DataLabelCollection コレクションの場合、このプロパティは新しいデータラベルの ShowLeaderLines プロパティのデフォルト値を取得または設定します。値を設定すると、DataLabelCollection 内のすべてのデータラベルの ShowLeaderLines プロパティにも同じ値が設定されます (例: `"DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);"` によりすべての `DataLabels.get_Item(i).getShowLeaderLines()` が `val` と等しくなります)。

**戻り値:**
boolean
### setShowLeaderLines(boolean value) {#setShowLeaderLines-boolean-}
```
public abstract void setShowLeaderLines(boolean value)
```


指定されたチャートのデータラベルのリーダーライン表示動作を表します。true の場合はリーダーラインを表示し、false の場合は非表示にします。読み書き可能な boolean。

--------------------

DataLabelFormat オブジェクトの親が DataLabelCollection コレクションの場合、このプロパティは新しいデータラベルの ShowLeaderLines プロパティのデフォルト値を取得または設定します。値を設定すると、DataLabelCollection 内のすべてのデータラベルの ShowLeaderLines プロパティにも同じ値が設定されます (例: `"DataLabels.getDefaultDataLabelFormat().setShowLeaderLines(val);"` によりすべての `DataLabels.get_Item(i).getShowLeaderLines()` が `val` と等しくなります)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |
### getShowLabelAsDataCallout() {#getShowLabelAsDataCallout--}
```
public abstract boolean getShowLabelAsDataCallout()
```


指定されたチャートのデータラベルがデータコールアウトとして表示されるかデータラベルとして表示されるかを決定します。

--------------------

DataLabelFormat オブジェクトの親が DataLabelCollection コレクションの場合、このプロパティは新しいデータラベルの ShowLabelAsDataCallout プロパティのデフォルト値を取得または設定します。値を設定すると、DataLabelCollection 内のすべてのデータラベルの ShowLabelAsDataCallout プロパティにも同じ値が設定されます (例: `"DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);"` によりすべての `DataLabels.get_Item(i).getShowLabelAsDataCallout()` が `val` と等しくなります)。

**戻り値:**
boolean
### setShowLabelAsDataCallout(boolean value) {#setShowLabelAsDataCallout-boolean-}
```
public abstract void setShowLabelAsDataCallout(boolean value)
```


指定されたチャートのデータラベルがデータコールアウトとして表示されるかデータラベルとして表示されるかを決定します。

--------------------

DataLabelFormat オブジェクトの親が DataLabelCollection コレクションの場合、このプロパティは新しいデータラベルの ShowLabelAsDataCallout プロパティのデフォルト値を取得または設定します。値を設定すると、DataLabelCollection 内のすべてのデータラベルの ShowLabelAsDataCallout プロパティにも同じ値が設定されます (例: `"DataLabels.getDefaultDataLabelFormat().setShowLabelAsDataCallout(val);"` によりすべての `DataLabels.get_Item(i).getShowLabelAsDataCallout()` が `val` と等しくなります)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |
### getShowLabelValueFromCell() {#getShowLabelValueFromCell--}
```
public abstract boolean getShowLabelValueFromCell()
```


指定されたチャートのデータラベルのセル値表示動作を表します。true の場合はセル値を表示し、false の場合は非表示にします。読み書き可能な boolean。

--------------------

DataLabelFormat オブジェクトの親が DataLabelCollection コレクションの場合、このプロパティは新しいデータラベルの ShowLabelValueFromCell プロパティのデフォルト値を取得または設定します。値を設定すると、DataLabelCollection 内のすべてのデータラベルの ShowLabelValueFromCell プロパティにも同じ値が設定されます (例: `"DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);"` によりすべての `DataLabels.get_Item(i).getShowLabelValueFromCell()` が `val` と等しくなります)。

**戻り値:**
boolean
### setShowLabelValueFromCell(boolean value) {#setShowLabelValueFromCell-boolean-}
```
public abstract void setShowLabelValueFromCell(boolean value)
```


指定されたチャートのデータラベルのセル値表示動作を表します。true の場合はセル値を表示し、false の場合は非表示にします。読み書き可能な boolean。

--------------------

DataLabelFormat オブジェクトの親が DataLabelCollection コレクションの場合、このプロパティは新しいデータラベルの ShowLabelValueFromCell プロパティのデフォルト値を取得または設定します。値を設定すると、DataLabelCollection 内のすべてのデータラベルの ShowLabelValueFromCell プロパティにも同じ値が設定されます (例: `"DataLabels.getDefaultDataLabelFormat().setShowLabelValueFromCell(val);"` によりすべての `DataLabels.get_Item(i).getShowLabelValueFromCell()` が `val` と等しくなります)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |
### getSeparator() {#getSeparator--}
```
public abstract String getSeparator()
```


チャート上のデータラベルで使用される区切り文字を表す Variant を設定または取得します。読み書き可能な String。

--------------------

DataLabelFormat オブジェクトの親が DataLabelCollection コレクションの場合、このプロパティは新しいデータラベルの Separator プロパティのデフォルト値を取得または設定します。値を設定すると、DataLabelCollection 内のすべてのデータラベルの Separator プロパティにも同じ値が設定されます (例: `"DataLabels.getDefaultDataLabelFormat().setSeparator(val);"` によりすべての `DataLabels.get_Item(i).getSeparator()` が `val` と等しくなります)。

**戻り値:**
java.lang.String
### setSeparator(String value) {#setSeparator-java.lang.String-}
```
public abstract void setSeparator(String value)
```


チャート上のデータラベルで使用される区切り文字を表す Variant を設定または取得します。読み書き可能な String。

--------------------

DataLabelFormat オブジェクトの親が DataLabelCollection コレクションの場合、このプロパティは新しいデータラベルの Separator プロパティのデフォルト値を取得または設定します。値を設定すると、DataLabelCollection 内のすべてのデータラベルの Separator プロパティにも同じ値が設定されます (例: `"DataLabels.getDefaultDataLabelFormat().setSeparator(val);"` によりすべての `DataLabels.get_Item(i).getSeparator()` が `val` と等しくなります)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |