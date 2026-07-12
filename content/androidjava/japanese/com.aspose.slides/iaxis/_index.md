---
title: IAxis
second_title: Aspose.Slides for Android の Java API リファレンス
description: チャートの軸を表すオブジェクトをカプセル化します。
type: docs
url: /ja/com.aspose.slides/iaxis/
---
**実装されているすべてのインターフェイス:**
[com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer)
```
public interface IAxis extends IFormattedTextContainer
```

チャートの軸を表すオブジェクトをカプセル化します。

## メソッド

| Method | Description |
| --- | --- |
| [getAxisBetweenCategories()](#getAxisBetweenCategories--) | 値軸がカテゴリ軸をカテゴリ間で交差するかどうかを表します。 |
| [setAxisBetweenCategories(boolean value)](#setAxisBetweenCategories-boolean-) | 値軸がカテゴリ軸をカテゴリ間で交差するかどうかを表します。 |
| [getCrossAt()](#getCrossAt--) | 軸上で直交軸が交差する点を表します。 |
| [setCrossAt(float value)](#setCrossAt-float-) | 軸上で直交軸が交差する点を表します。 |
| [getDisplayUnit()](#getDisplayUnit--) | 値軸の表示単位のスケーリング値を指定します。 |
| [setDisplayUnit(int value)](#setDisplayUnit-int-) | 値軸の表示単位のスケーリング値を指定します。 |
| [getActualMaxValue()](#getActualMaxValue--) | 軸上の実際の最大値を指定します。 |
| [getActualMinValue()](#getActualMinValue--) | 軸上の実際の最小値を指定します。 |
| [getActualMajorUnit()](#getActualMajorUnit--) | 軸の実際の主単位を指定します。 |
| [getActualMinorUnit()](#getActualMinorUnit--) | 軸の実際の副単位を指定します。 |
| [getActualMajorUnitScale()](#getActualMajorUnitScale--) | 軸の実際の主単位スケールを指定します。 |
| [getActualMinorUnitScale()](#getActualMinorUnitScale--) | 軸の実際の副単位スケールを指定します。 |
| [isAutomaticMaxValue()](#isAutomaticMaxValue--) | 最大値が自動的に割り当てられるかどうかを示します。 |
| [setAutomaticMaxValue(boolean value)](#setAutomaticMaxValue-boolean-) | 最大値が自動的に割り当てられるかどうかを示します。 |
| [getMaxValue()](#getMaxValue--) | 値軸上の最大値を表します。 |
| [setMaxValue(double value)](#setMaxValue-double-) | 値軸上の最大値を表します。 |
| [getMinorUnit()](#getMinorUnit--) | 日付軸または値軸の副単位を表します。 |
| [setMinorUnit(double value)](#setMinorUnit-double-) | 日付軸または値軸の副単位を表します。 |
| [isAutomaticMinorUnit()](#isAutomaticMinorUnit--) | 軸の副単位が自動的に割り当てられるかどうかを示します。 |
| [setAutomaticMinorUnit(boolean value)](#setAutomaticMinorUnit-boolean-) | 軸の副単位が自動的に割り当てられるかどうかを示します。 |
| [getMajorUnit()](#getMajorUnit--) | 日付軸または値軸の主単位を表します。 |
| [setMajorUnit(double value)](#setMajorUnit-double-) | 日付軸または値軸の主単位を表します。 |
| [isAutomaticMajorUnit()](#isAutomaticMajorUnit--) | 軸の主単位が自動的に割り当てられるかどうかを示します。 |
| [setAutomaticMajorUnit(boolean value)](#setAutomaticMajorUnit-boolean-) | 軸の主単位が自動的に割り当てられるかどうかを示します。 |
| [isAutomaticMinValue()](#isAutomaticMinValue--) | 最小値が自動的に割り当てられるかどうかを示します。 |
| [setAutomaticMinValue(boolean value)](#setAutomaticMinValue-boolean-) | 最小値が自動的に割り当てられるかどうかを示します。 |
| [getMinValue()](#getMinValue--) | 値軸上の最小値を表します。 |
| [setMinValue(double value)](#setMinValue-double-) | 値軸上の最小値を表します。 |
| [isLogarithmic()](#isLogarithmic--) | 値軸のスケールタイプが対数かどうかを表します。 |
| [setLogarithmic(boolean value)](#setLogarithmic-boolean-) | 値軸のスケールタイプが対数かどうかを表します。 |
| [getLogBase()](#getLogBase--) | 対数の基数を表します。 |
| [setLogBase(double value)](#setLogBase-double-) | 対数の基数を表します。 |
| [isPlotOrderReversed()](#isPlotOrderReversed--) | MS PowerPoint がデータポイントを最後から最初へプロットするかどうかを表します。 |
| [setPlotOrderReversed(boolean value)](#setPlotOrderReversed-boolean-) | MS PowerPoint がデータポイントを最後から最初へプロットするかどうかを表します。 |
| [isVisible()](#isVisible--) | 軸が表示されているかどうかを表します。 |
| [setVisible(boolean value)](#setVisible-boolean-) | 軸が表示されているかどうかを表します。 |
| [getMajorTickMark()](#getMajorTickMark--) | 指定された軸の主目盛りの種類を表します。 |
| [setMajorTickMark(int value)](#setMajorTickMark-int-) | 指定された軸の主目盛りの種類を表します。 |
| [getMinorTickMark()](#getMinorTickMark--) | 指定された軸の副目盛りの種類を表します。 |
| [setMinorTickMark(int value)](#setMinorTickMark-int-) | 指定された軸の副目盛りの種類を表します。 |
| [getTickLabelPosition()](#getTickLabelPosition--) | 指定された軸上の目盛りラベルの位置を表します。 |
| [setTickLabelPosition(int value)](#setTickLabelPosition-int-) | 指定された軸上の目盛りラベルの位置を表します。 |
| [getMajorUnitScale()](#getMajorUnitScale--) | 日付軸の主単位スケールを表します。 |
| [setMajorUnitScale(int value)](#setMajorUnitScale-int-) | 日付軸の主単位スケールを表します。 |
| [getMinorUnitScale()](#getMinorUnitScale--) | 日付軸の主単位スケールを表します。 |
| [setMinorUnitScale(int value)](#setMinorUnitScale-int-) | 日付軸の主単位スケールを表します。 |
| [getBaseUnitScale()](#getBaseUnitScale--) | 日付軸で表される最小の時間単位を指定します。 |
| [setBaseUnitScale(int value)](#setBaseUnitScale-int-) | 日付軸で表される最小の時間単位を指定します。 |
| [getMinorGridLinesFormat()](#getMinorGridLinesFormat--) | チャート軸の副グリッド線の書式を表します。 |
| [getMajorGridLinesFormat()](#getMajorGridLinesFormat--) | チャート軸の主グリッド線の書式を表します。 |
| [getShowMinorGridLines()](#getShowMinorGridLines--) | 副グリッド線が表示されるかどうかを表します。 |
| [getShowMajorGridLines()](#getShowMajorGridLines--) | 主グリッド線が表示されるかどうかを表します。 |
| [getFormat()](#getFormat--) | 軸の書式を表します。 |
| [getTitle()](#getTitle--) | 軸のタイトルを取得します。 |
| [getCrossType()](#getCrossType--) | 他の軸が交差する指定軸上の CrossType を表します。 |
| [setCrossType(int value)](#setCrossType-int-) | 他の軸が交差する指定軸上の CrossType を表します。 |
| [getPosition()](#getPosition--) | 軸の位置を表します。 |
| [setPosition(int value)](#setPosition-int-) | 軸の位置を表します。 |
| [hasTitle()](#hasTitle--) | 軸に表示可能なタイトルがあるかどうかを決定します。 |
| [setTitle(boolean value)](#setTitle-boolean-) | 軸に表示可能なタイトルがあるかどうかを決定します。 |
| [getNumberFormat()](#getNumberFormat--) | 軸ラベルの書式文字列を表します。 |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | 軸ラベルの書式文字列を表します。 |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | 書式がソースデータにリンクされているかどうかを示します。 |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | 書式がソースデータにリンクされているかどうかを示します。 |
| [getTickLabelRotationAngle()](#getTickLabelRotationAngle--) | 目盛ラベルの回転角度を表します。読み取り/書き込み float。 |
| [setTickLabelRotationAngle(float value)](#setTickLabelRotationAngle-float-) | 目盛ラベルの回転角度を表します。読み取り/書き込み float。 |
| [getTickLabelSpacing()](#getTickLabelSpacing--) | 描画されるラベル間でスキップする目盛ラベルの数を指定します。 |
| [setTickLabelSpacing(long value)](#setTickLabelSpacing-long-) | 描画されるラベル間でスキップする目盛ラベルの数を指定します。 |
| [isAutomaticTickLabelSpacing()](#isAutomaticTickLabelSpacing--) | 自動目盛ラベル間隔の値を指定します。 |
| [setAutomaticTickLabelSpacing(boolean value)](#setAutomaticTickLabelSpacing-boolean-) | 自動目盛ラベル間隔の値を指定します。 |
| [getTickMarksSpacing()](#getTickMarksSpacing--) | 次の目盛りが描画される前にスキップすべき目盛りの数を指定します。 |
| [setTickMarksSpacing(long value)](#setTickMarksSpacing-long-) | 次の目盛りが描画される前にスキップすべき目盛りの数を指定します。 |
| [isAutomaticTickMarksSpacing()](#isAutomaticTickMarksSpacing--) | 自動目盛間隔の値を指定します。 |
| [setAutomaticTickMarksSpacing(boolean value)](#setAutomaticTickMarksSpacing-boolean-) | 自動目盛間隔の値を指定します。 |
| [getLabelOffset()](#getLabelOffset--) | ラベルと軸との距離を指定します。 |
| [setLabelOffset(int value)](#setLabelOffset-int-) | ラベルと軸との距離を指定します。 |
| [getCategoryAxisType()](#getCategoryAxisType--) | カテゴリ軸のタイプを指定します。 |
| [setCategoryAxisType(int value)](#setCategoryAxisType-int-) | カテゴリ軸のタイプを指定します。 |
| [setCategoryAxisTypeAutomatically()](#setCategoryAxisTypeAutomatically--) | 軸データに基づいて自動的に決定される値で IAxis.CategoryAxisType プロパティを設定します。 |
| [getAggregationType()](#getAggregationType--) | カテゴリ軸（ビニング）の集計タイプを表します。 |
| [setAggregationType(int value)](#setAggregationType-int-) | カテゴリ軸（ビニング）の集計タイプを表します。 |
| [getBinWidth()](#getBinWidth--) | AggregationType プロパティが AxisAggregationType.ByBinWidth に設定されている場合のビン幅を指定します。 |
| [setBinWidth(double value)](#setBinWidth-double-) | AggregationType プロパティが AxisAggregationType.ByBinWidth に設定されている場合のビン幅を指定します。 |
| [getNumberOfBins()](#getNumberOfBins--) | AggregationType プロパティが AxisAggregationType.ByNumberOfBins に設定されている場合のビン数を指定します。 |
| [setNumberOfBins(long value)](#setNumberOfBins-long-) | AggregationType プロパティが AxisAggregationType.ByNumberOfBins に設定されている場合のビン数を指定します。 |
| [isOverflowBin()](#isOverflowBin--) | オーバーフロービンが適用されるかどうかを指定します。 |
| [setOverflowBin(boolean value)](#setOverflowBin-boolean-) | オーバーフロービンが適用されるかどうかを指定します。 |
| [isAutomaticOverflowBin()](#isAutomaticOverflowBin--) | 自動オーバーフロービンの値を指定します。 |
| [setAutomaticOverflowBin(boolean value)](#setAutomaticOverflowBin-boolean-) | 自動オーバーフロービンの値を指定します。 |
| [getOverflowBin()](#getOverflowBin--) | オーバーフロービンのカスタム値を指定します。 |
| [setOverflowBin(double value)](#setOverflowBin-double-) | オーバーフロービンのカスタム値を指定します。 |
| [isUnderflowBin()](#isUnderflowBin--) | アンダーフロービンが適用されるかどうかを指定します。 |
| [setUnderflowBin(boolean value)](#setUnderflowBin-boolean-) | アンダーフロービンが適用されるかどうかを指定します。 |
| [isAutomaticUnderflowBin()](#isAutomaticUnderflowBin--) | 自動アンダーフロービンの値を指定します。 |
| [setAutomaticUnderflowBin(boolean value)](#setAutomaticUnderflowBin-boolean-) | 自動アンダーフロービンの値を指定します。 |
| [getUnderflowBin()](#getUnderflowBin--) | アンダーフロービンのカスタム値を指定します。 |
| [setUnderflowBin(double value)](#setUnderflowBin-double-) | アンダーフロービンのカスタム値を指定します。 |

### getAxisBetweenCategories() {#getAxisBetweenCategories--}
```
public abstract boolean getAxisBetweenCategories()
```

値軸がカテゴリ軸をカテゴリ間で交差するかどうかを表します。このプロパティはカテゴリ軸にのみ適用され、3-D チャートには適用されません。読み取り/書き込み boolean。

**戻り値:**
boolean

### setAxisBetweenCategories(boolean value) {#setAxisBetweenCategories-boolean-}
```
public abstract void setAxisBetweenCategories(boolean value)
```

値軸がカテゴリ軸をカテゴリ間で交差するかどうかを表します。このプロパティはカテゴリ軸にのみ適用され、3-D チャートには適用されません。読み取り/書き込み boolean。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getCrossAt() {#getCrossAt--}
```
public abstract float getCrossAt()
```

軸上で直交軸が交差する点を表します。読み取り/書き込み float。

**戻り値:**
float

### setCrossAt(float value) {#setCrossAt-float-}
```
public abstract void setCrossAt(float value)
```

軸上で直交軸が交差する点を表します。読み取り/書き込み float。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getDisplayUnit() {#getDisplayUnit--}
```
public abstract int getDisplayUnit()
```

値軸の表示単位のスケーリング値を指定します。読み取り/書き込み [DisplayUnitType](../../com.aspose.slides/displayunittype)。

**戻り値:**
int

### setDisplayUnit(int value) {#setDisplayUnit-int-}
```
public abstract void setDisplayUnit(int value)
```

値軸の表示単位のスケーリング値を指定します。読み取り/書き込み [DisplayUnitType](../../com.aspose.slides/displayunittype)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getActualMaxValue() {#getActualMaxValue--}
```
public abstract double getActualMaxValue()
```

軸上の実際の最大値を指定します。事前に IChart.ValidateChartLayout() メソッドを呼び出して実際の値を取得してください。

**戻り値:**
double

### getActualMinValue() {#getActualMinValue--}
```
public abstract double getActualMinValue()
```

軸上の実際の最小値を指定します。事前に IChart.ValidateChartLayout() メソッドを呼び出して実際の値を取得してください。

**戻り値:**
double

### getActualMajorUnit() {#getActualMajorUnit--}
```
public abstract double getActualMajorUnit()
```

軸の実際の主単位を指定します。事前に IChart.ValidateChartLayout() メソッドを呼び出して実際の値を取得してください。

**戻り値:**
double

### getActualMinorUnit() {#getActualMinorUnit--}
```
public abstract double getActualMinorUnit()
```

軸の実際の副単位を指定します。事前に IChart.ValidateChartLayout() メソッドを呼び出して実際の値を取得してください。

**戻り値:**
double

### getActualMajorUnitScale() {#getActualMajorUnitScale--}
```
public abstract int getActualMajorUnitScale()
```

軸の実際の主単位スケールを指定します。事前に IChart.ValidateChartLayout() メソッドを呼び出して実際の値を取得してください。

**戻り値:**
int

### getActualMinorUnitScale() {#getActualMinorUnitScale--}
```
public abstract int getActualMinorUnitScale()
```

軸の実際の副単位スケールを指定します。事前に IChart.ValidateChartLayout() メソッドを呼び出して実際の値を取得してください。

**戻り値:**
int

### isAutomaticMaxValue() {#isAutomaticMaxValue--}
```
public abstract boolean isAutomaticMaxValue()
```

最大値が自動的に割り当てられるかどうかを示します。読み取り/書き込み boolean。

**戻り値:**
boolean

### setAutomaticMaxValue(boolean value) {#setAutomaticMaxValue-boolean-}
```
public abstract void setAutomaticMaxValue(boolean value)
```

最大値が自動的に割り当てられるかどうかを示します。読み取り/書き込み boolean。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getMaxValue() {#getMaxValue--}
```
public abstract double getMaxValue()
```

値軸上の最大値を表します。読み取り/書き込み double。

**戻り値:**
double

### setMaxValue(double value) {#setMaxValue-double-}
```
public abstract void setMaxValue(double value)
```

値軸上の最大値を表します。読み取り/書き込み double。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | double |  |

### getMinorUnit() {#getMinorUnit--}
```
public abstract double getMinorUnit()
```

日付軸または値軸の副単位を表します。読み取り/書き込み double。

**戻り値:**
double

### setMinorUnit(double value) {#setMinorUnit-double-}
```
public abstract void setMinorUnit(double value)
```

日付軸または値軸の副単位を表します。読み取り/書き込み double。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | double |  |

### isAutomaticMinorUnit() {#isAutomaticMinorUnit--}
```
public abstract boolean isAutomaticMinorUnit()
```

軸の副単位が自動的に割り当てられるかどうかを示します。読み取り/書き込み boolean。

**戻り値:**
boolean

### setAutomaticMinorUnit(boolean value) {#setAutomaticMinorUnit-boolean-}
```
public abstract void setAutomaticMinorUnit(boolean value)
```

軸の副単位が自動的に割り当てられるかどうかを示します。読み取り/書き込み boolean。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getMajorUnit() {#getMajorUnit--}
```
public abstract double getMajorUnit()
```

日付軸または値軸の主単位を表します。読み取り/書き込み double。

**戻り値:**
double

### setMajorUnit(double value) {#setMajorUnit-double-}
```
public abstract void setMajorUnit(double value)
```

日付軸または値軸の主単位を表します。読み取り/書き込み double。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | double |  |

### isAutomaticMajorUnit() {#isAutomaticMajorUnit--}
```
public abstract boolean isAutomaticMajorUnit()
```

軸の主単位が自動的に割り当てられるかどうかを示します。読み取り/書き込み boolean。

**戻り値:**
boolean

### setAutomaticMajorUnit(boolean value) {#setAutomaticMajorUnit-boolean-}
```
public abstract void setAutomaticMajorUnit(boolean value)
```

軸の主単位が自動的に割り当てられるかどうかを示します。読み取り/書き込み boolean。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticMinValue() {#isAutomaticMinValue--}
```
public abstract boolean isAutomaticMinValue()
```

最小値が自動的に割り当てられるかどうかを示します。読み取り/書き込み boolean。

**戻り値:**
boolean

### setAutomaticMinValue(boolean value) {#setAutomaticMinValue-boolean-}
```
public abstract void setAutomaticMinValue(boolean value)
```

最小値が自動的に割り当てられるかどうかを示します。読み取り/書き込み boolean。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getMinValue() {#getMinValue--}
```
public abstract double getMinValue()
```

値軸上の最小値を表します。読み取り/書き込み double。

**戻り値:**
double

### setMinValue(double value) {#setMinValue-double-}
```
public abstract void setMinValue(double value)
```

値軸上の最小値を表します。読み取り/書き込み double。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | double |  |

### isLogarithmic() {#isLogarithmic--}
```
public abstract boolean isLogarithmic()
```

値軸のスケールタイプが対数かどうかを表します。読み取り/書き込み boolean。

**戻り値:**
boolean

### setLogarithmic(boolean value) {#setLogarithmic-boolean-}
```
public abstract void setLogarithmic(boolean value)
```

値軸のスケールタイプが対数かどうかを表します。読み取り/書き込み boolean。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getLogBase() {#getLogBase--}
```
public abstract double getLogBase()
```

対数の基数を表します。既定値は 10 です。読み取り/書き込み double。

**戻り値:**
double

### setLogBase(double value) {#setLogBase-double-}
```
public abstract void setLogBase(double value)
```

対数の基数を表します。既定値は 10 です。読み取り/書き込み double。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | double |  |

### isPlotOrderReversed() {#isPlotOrderReversed--}
```
public abstract boolean isPlotVisible
```

MS PowerPoint がデータポイントを最後から最初へプロットするかどうかを表します。読み取り/書き込み boolean。

**戻り値:**
boolean

### setPlotOrderReversed(boolean value) {#setPlotOrderReversed-boolean-}
```
public abstract void setPlotOrderReversed(boolean value)
```

MS PowerPoint がデータポイントを最後から最初へプロットするかどうかを表します。読み取り/書き込み boolean。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

軸が表示されているかどうかを表します。読み取り/書き込み boolean。

**戻り値:**
boolean

### setVisible(boolean value) {#setVisible-boolean-}
```
public abstract void setVisible(boolean value)
```

軸が表示されているかどうかを表します。読み取り/書き込み boolean。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getMajorTickMark() {#getMajorTickMark--}
```
public abstract int getMajorTickMark()
```

指定された軸の主目盛りの種類を表します。読み取り/書き込み [TickMarkType](../../com.aspose.slides/tickmarktype)。

**戻り値:**
int

### setMajorTickMark(int value) {#setMajorTickMark-int-}
```
public abstract void setMajorTickMark(int value)
```

指定された軸の主目盛りの種類を表します。読み取り/書き込み [TickMarkType](../../com.aspose.slides/tickmarktype)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getMinorTickMark() {#getMinorTickMark--}
```
public abstract int getMinorTickMark()
```

指定された軸の副目盛りの種類を表します。読み取り/書き込み [TickMarkType](../../com.aspose.slides/tickmarktype)。

**戻り値:**
int

### setMinorTickMark(int value) {#setMinorTickMark-int-}
```
public abstract void setMinorTickMark(int value)
```

指定された軸の副目盛りの種類を表します。読み取り/書き込み [TickMarkType](../../com.aspose.slides/tickmarktype)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getTickLabelPosition() {#getTickLabelPosition--}
```
public abstract int getTickLabelPosition()
```

指定された軸上の目盛りラベルの位置を表します。読み取り/書き込み [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype)。

**戻り値:**
int

### setTickLabelPosition(int value) {#setTickLabelPosition-int-}
```
public abstract void setTickLabelPosition(int value)
```

指定された軸上の目盛りラベルの位置を表します。読み取り/書き込み [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getMajorUnitScale() {#getMajorUnitScale--}
```
public abstract int getMajorUnitScale()
```

日付軸の主単位スケールを表します。読み取り/書き込み [TimeUnitType](../../com.aspose.slides/timeunittype)。

**戻り値:**
int

### setMajorUnitScale(int value) {#setMajorUnitScale-int-}
```
public abstract void setMajorUnitScale(int value)
```

日付軸の主単位スケールを表します。読み取り/書き込み [TimeUnitType](../../com.aspose.slides/timeunittype)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getMinorUnitScale() {#getMinorUnitScale--}
```
public abstract int getMinorUnitScale()
```

日付軸の主単位スケールを表します。読み取り/書き込み [TimeUnitType](../../com.aspose.slides/timeunittype)。

**戻り値:**
int

### setMinorUnitScale(int value) {#setMinorUnitScale-int-}
```
public abstract void setMinorUnitScale(int value)
```

日付軸の主単位スケールを表します。読み取り/書き込み [TimeUnitType](../../com.aspose.slides/timeunittype)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getBaseUnitScale() {#getBaseUnitScale--}
```
public abstract int getBaseUnitScale()
```

日付軸で表される最小の時間単位を指定します。読み取り/書き込み [TimeUnitType](../../com.aspose.slides/timeunittype)。

**戻り値:**
int

### setBaseUnitScale(int value) {#setBaseUnitScale-int-}
```
public abstract void setBaseUnitScale(int value)
```

日付軸で表される最小の時間単位を指定します。読み取り/書き込み [TimeUnitType](../../com.aspose.slides/timeunittype)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getMinorGridLinesFormat() {#getMinorGridLinesFormat--}
```
public abstract IChartLinesFormat getMinorGridLinesFormat()
```

チャート軸の副グリッド線の書式を表します。読み取り専用 [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)。

**戻り値:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getMajorGridLinesFormat() {#getMajorGridLinesFormat--}
```
public abstract IChartLinesFormat getMinorGridLinesFormat()
```

チャート軸の主グリッド線の書式を表します。読み取り専用 [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)。

**戻り値:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getShowMinorGridLines() {#getShowMinorGridLines--}
```
public abstract boolean getShowMinorGridLines()
```

副グリッド線が表示されるかどうかを表します。読み取り専用 boolean。

**戻り値:**
boolean

### getShowMajorGridLines() {#getShowMajorGridLines--}
```
public abstract boolean getShowMajorGridLines()
```

主グリッド線が表示されるかどうかを表します。読み取り専用 boolean。

**戻り値:**
boolean

### getFormat() {#getFormat--}
```
public abstract IAxisFormat getFormat()
```

軸の書式を表します。読み取り専用 [IAxisFormat](../../com.aspose.slides/iaxisformat)。

**戻り値:**
[IAxisFormat](../../com.aspose.slides/iaxisformat)

### getTitle() {#getTitle--}
```
public abstract IChartTitle getTitle()
```

軸のタイトルを取得します。読み取り専用 [IChartTitle](../../com.aspose.slides/icharttitle)。

**戻り値:**
[IChartTitle](../../com.aspose.slides/icharttitle)

### getCrossType() {#getCrossType--}
```
public abstract int getCrossType()
```

他の軸が交差する指定軸上の CrossType を表します。読み取り/書き込み [CrossesType](../../com.aspose.slides/crossestype)。

**戻り値:**
int

### setCrossType(int value) {#setCrossType-int-}
```
public abstract void setCrossType(int value)
```

他の軸が交差する指定軸上の CrossType を表します。読み取り/書き込み [CrossesType](../../com.aspose.slides/crossestype)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getPosition() {#getPosition--}
```
public abstract int



जे



```

軸の位置を表します。読み取り/書き込み [AxisPositionType](../../com.aspose.slides/axispositiontype)。

**戻り値:**
int

### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

軸の位置を表します。読み取り/書き込み [AxisPositionType](../../com.aspose.slides/axispositiontype)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### hasTitle() {#hasTitle--}
```
public abstract boolean hasTitle()
```

軸に表示可能なタイトルがあるかどうかを決定します。読み取り/書き込み boolean。

**戻り値:**
boolean

### setTitle(boolean value) {#setTitle-boolean-}
```
public abstract void setTitle(boolean value)
```

軸に表示可能なタイトルがあるかどうかを決定します。読み取り/書き込み boolean。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public abstract String getNumberFormat()
```

軸ラベルの書式文字列を表します。読み取り/書き込み String。

**戻り値:**
java.lang.String

### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public abstract void setNumberFormat(String value)
```

軸ラベルの書式文字列を表します。読み取り/書き込み String。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public abstract boolean isNumberFormatLinkedToSource()
```

書式がソースデータにリンクされているかどうかを示します。読み取り/書き込み boolean。

**戻り値:**
boolean

### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public abstract void setNumberFormatLinkedToSource(boolean value)
```

書式がソースデータにリンクされているかどうかを示します。読み取り/書き込み boolean。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getTickLabelRotationAngle() {#getTickLabelRotationAngle--}
```
public abstract float getTickLabelRotationAngle()
```

目盛ラベルの回転角度を表します。読み取り/書き込み float。

**戻り値:**
float

### setTickLabelRotationAngle(float value) {#setTickLabelRotationAngle-float-}
```
public abstract void setTickLabelRotationAngle(float value)
```

目盛ラベルの回転角度を表します。読み取り/書き込み float。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getTickLabelSpacing() {#getTickLabelSpacing--}
```
public abstract long getTickLabelSpacing()
```

描画されるラベル間でスキップする目盛ラベルの数を指定します。読み取り/書き込み long。

**戻り値:**
long

### setTickLabelSpacing(long value) {#setTickLabelSpacing-long-}
```
public abstract void setTickLabelSpacing(long value)
```

描画されるラベル間でスキップする目盛ラベルの数を指定します。読み取り/書き込み long。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickLabelSpacing() {#isAutomaticTickLabelSpacing--}
```
public abstract boolean isAutomaticTickLabelSpacing()
```

自動目盛ラベル間隔の値を指定します。false の場合は TickLabelSpacing プロパティを使用します。読み取り/書き込み boolean。

**戻り値:**
boolean

### setAutomaticTickLabelSpacing(boolean value) {#setAutomaticTickLabelSpacing-boolean-}
```
public abstract void setAutomaticTickLabelSpacing(boolean value)
```

自動目盛ラベル間隔の値を指定します。false の場合は TickLabelSpacing プロパティを使用します。読み取り/書き込み boolean。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getTickMarksSpacing() {#getTickMarksSpacing--}
```
public abstract long getTickMarksSpacing()
```

次の目盛りが描画される前にスキップすべき目盛りの数を指定します。カテゴリ軸または系列軸に適用されます。読み取り/書き込み int。

**戻り値:**
long

### setTickMarksSpacing(long value) {#setTickMarksSpacing-long-}
```
public abstract void setTickMarksSpacing(long value)
```

次の目盛りが描画される前にスキップすべき目盛りの数を指定します。カテゴリ軸または系列軸に適用されます。読み取り/書き込み int。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickMarksSpacing() {#isAutomaticTickMarksSpacing--}
```
public abstract



```

自動目盛間隔の値を指定します。false の場合は TickMarksSpacing プロパティを使用します。読み取り/書き込み boolean。

**戻り値:**
boolean

### setAutomaticTickMarksSpacing(boolean value) {#setAutomaticTickMarksSpacing-boolean-}
```
public abstract void setAutomaticTickMarksSpacing(boolean value)
```

自動目盛間隔の値を指定します。false の場合は TickMarksSpacing プロパティを使用します。読み取り/書き込み boolean。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getLabelOffset() {#getLabelOffset--}
```
public abstract int getLabelOffset()
```

ラベルと軸との距離を指定します。カテゴリ軸または日付軸に適用されます。値は 0% から 1000% の間でなければなりません。読み取り/書き込み int。

**戻り値:**
int

### setLabelOffset(int value) {#setLabelOffset-int-}
```
public abstract void setLabelOffset(int value)
```

ラベルと軸との距離を指定します。カテゴリ軸または日付軸に適用されます。値は 0% から 1000% の間でなければなりません。読み取り/書き込み int。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getCategoryAxisType() {#getCategoryAxisType--}
```
public abstract int getCategoryAxisType()
```

カテゴリ軸のタイプを指定します。読み取り/書き込み [CategoryAxisType](../../com.aspose.slides/categoryaxistype)(\#getCategoryAxisType.getCategoryAxisType/\#setCategoryAxisType(int).setCategoryAxisType(int))。

**戻り値:**
int

### setCategoryAxisType(int value) {#setCategoryAxisType-int-}
```
public abstract void setCategoryAxisType(int value)
```

カテゴリ軸のタイプを指定します。読み取り/書き込み [CategoryAxisType](../../com.aspose.slides/categoryaxistype)(\#getCategoryAxisType.getCategoryAxisType/\#setCategoryAxisType(int).setCategoryAxisType(int))。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### setCategoryAxisTypeAutomatically() {#setCategoryAxisTypeAutomatically--}
```
public abstract void setCategoryAxisTypeAutomatically()
```

軸データに基づいて自動的に決定される値で IAxis.CategoryAxisType プロパティを設定します。

### getAggregationType() {#getAggregationType--}
```
public abstract int getAggregationType()
```

カテゴリ軸（ビニング）の集計タイプを表します。カテゴリに適用されます。Histogram または HistogramPareto 系列でのみ使用できます。

**戻り値:**
int

### setAggregationType(int value) {#setAggregationType-int-}
```
public abstract void setAggregationType(int value)
```

カテゴリ軸（ビニング）の集計タイプを表します。カテゴリに適用されます。Histogram または HistogramPareto 系列でのみ使用できます。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getBinWidth() {#getBinWidth--}
```
public abstract double getBinWidth()
```

AggregationType プロパティが AxisAggregationType.ByBinWidth に設定されている場合のビン幅を指定します。カテゴリ軸に適用されます。Histogram または HistogramPareto 系列でのみ使用できます。

**戻り値:**
double

### setBinWidth(double value) {#setBinWidth-double-}
```
public abstract void setBinWidth(double value)
```

AggregationType プロパティが AxisAggregationType.ByBinWidth に設定されている場合のビン幅を指定します。カテゴリ軸に適用されます。Histogram または HistogramPareto 系列でのみ使用できます。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | double |  |

### getNumberOfBins() {#getNumberOfBins--}
```
public abstract long getNumberOfBins()
```

AggregationType プロパティが AxisAggregationType.ByNumberOfBins に設定されている場合のビン数を指定します。カテゴリ軸に適用されます。Histogram または HistogramPareto 系列でのみ使用できます。

**戻り値:**
long

### setNumberOfBins(long value) {#setNumberOfBins-long-}
```
public abstract void setNumberOfBins(long value)
```

AggregationType プロパティが AxisAggregationType.ByNumberOfBins に設定されている場合のビン数を指定します。カテゴリ軸に適用されます。Histogram または HistogramPareto 系列でのみ使用できます。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | long |  |

### isOverflowBin() {#isOverflowBin--}
```
public abstract boolean isOverflowBin()
```

オーバーフロービンが適用されるかどうかを指定します。IsAutomaticOverflowBin と OverflowBin を使用してオーバーフロービンの値を調整します。

**戻り値:**
boolean

### setOverflowBin(boolean value) {#setOverflowBin-boolean-}
```
public abstract void setOverflowBin(boolean value)
```

オーバーフロービンが適用されるかどうかを指定します。IsAutomaticOverflowBin と OverflowBin を使用してオーバーフロービンの値を調整します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticOverflowBin() {#isAutomaticOverflowBin--}
```
public abstract boolean isAutomaticOverflowBin()
```

自動オーバーフロービンの値を指定します。false の場合は OverflowBin プロパティを使用します。

**戻り値:**
boolean

### setAutomaticOverflowBin(boolean value) {#setAutomaticOverflowBin-boolean-}
```
public abstract void setAutomaticOverflowBin(boolean value)
```

自動オーバーフロービンの値を指定します。false の場合は OverflowBin プロパティを使用します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getOverflowBin() {#getOverflowBin--}
```
public abstract double getOverflowBin()
```

オーバーフロービンのカスタム値を指定します。IsAutomaticOverflowBin プロパティが false に設定され、IsOverflowBin プロパティが true の場合に適用されます。

**戻り値:**
double

### setOverflowBin(double value) {#setOverflowBin-double-}
```
public abstract void setOverflowBin(double value)
```

オーバーフロービンのカスタム値を指定します。IsAutomaticOverflowBin プロパティが false に設定され、IsOverflowBin プロパティが true の場合に適用されます。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | double |  |

### isUnderflowBin() {#isUnderflowBin--}
```
public abstract boolean isUnderflowBin()
```

アンダーフロービンが適用されるかどうかを指定します。IsAutomaticUnderflowBin と UnderflowBin を使用してアンダーフロービンの値を調整します。

**戻り値:**
boolean

### setUnderflowBin(boolean value) {#setUnderflowBin-boolean-}
```
public abstract void setUnderflowBin(boolean value)
```

アンダーフロービンが適用されるかどうかを指定します。IsAutomaticUnderflowBin と UnderflowBin を使用してアンダーフロービンの値を調整します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticUnderflowBin() {#isAutomaticUnderflowBin--}
```
public abstract



```

自動アンダーフロービンの値を指定します。false の場合は UnderflowBin プロパティを使用します。

**戻り値:**
boolean

### setAutomaticUnderflowBin(boolean value) {#setAutomaticUnderflowBin-boolean-}
```
public abstract void setAutomaticUnderflowBin(boolean value)
```

自動アンダーフロービンの値を指定します。false の場合は UnderflowBin プロパティを使用します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getUnderflowBin() {#getUnderflowBin--}
```
public abstract double getUnderflowBin()
```

アンダーフロービンのカスタム値を指定します。IsAutomaticUnderflowBin プロパティが false に設定され、IsUnderflowBin プロパティが true の場合に適用されます。

**戻り値:**
double

### setUnderflowBin(double value) {#setUnderflowBin-double-}
```
public abstract void setUnderflowBin(double value)
```

アンダーフロービンのカスタム値を指定します。IsAutomaticUnderflowBin プロパティが false に設定され、IsUnderflowBin プロパティが true の場合に適用されます。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | double |  |