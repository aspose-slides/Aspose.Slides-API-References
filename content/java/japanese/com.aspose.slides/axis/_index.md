---
title: Axis
second_title: Aspose.Slides for Java API リファレンス
description: チャートの軸を表すオブジェクトをカプセル化します。
type: docs
url: /ja/com.aspose.slides/axis/
---
**継承:**  
java.lang.Object, com.aspose.slides.DomObject

**実装されているすべてのインターフェイス:**  
[com.aspose.slides.IAxis](../../com.aspose.slides/iaxis)  
```
public class Axis extends DomObject<AxesManager> implements IAxis
```

チャートの軸を表すオブジェクトをカプセル化します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getChart()](#getChart--) | 親チャートを返します。 |
| [getAxisBetweenCategories()](#getAxisBetweenCategories--) | 値軸がカテゴリ軸をカテゴリ間で交差するかどうかを表します。 |
| [setAxisBetweenCategories(boolean value)](#setAxisBetweenCategories-boolean-) | 値軸がカテゴリ軸をカテゴリ間で交差するかどうかを表します。 |
| [getCategoryAxisType()](#getCategoryAxisType--) | カテゴリ軸のタイプを指定します。 |
| [setCategoryAxisType(int value)](#setCategoryAxisType-int-) | カテゴリ軸のタイプを指定します。 |
| [setCategoryAxisTypeAutomatically()](#setCategoryAxisTypeAutomatically--) | 軸データに基づいて自動的に決定される値で IAxis.CategoryAxisType プロパティを設定します。 |
| [getCrossAt()](#getCrossAt--) | 垂直軸が交差する軸上の点を表します。 |
| [setCrossAt(float value)](#setCrossAt-float-) | 垂直軸が交差する軸上の点を表します。 |
| [getDisplayUnit()](#getDisplayUnit--) | 値軸の表示単位のスケーリング値を指定します。 |
| [setDisplayUnit(int value)](#setDisplayUnit-int-) | 値軸の表示単位のスケーリング値を指定します。 |
| [getActualMaxValue()](#getActualMaxValue--) | 軸上の実際の最大値を指定します。 |
| [getActualMinValue()](#getActualMinValue--) | 軸上の実際の最小値を指定します。 |
| [getActualMajorUnit()](#getActualMajorUnit--) | 軸の実際の主要単位を指定します。 |
| [getActualMinorUnit()](#getActualMinorUnit--) | 軸の実際の副単位を指定します。 |
| [getActualMajorUnitScale()](#getActualMajorUnitScale--) | 軸の実際の主要単位スケールを指定します。 |
| [getActualMinorUnitScale()](#getActualMinorUnitScale--) | 軸の実際の副単位スケールを指定します。 |
| [isAutomaticMaxValue()](#isAutomaticMaxValue--) | 最大値が自動的に割り当てられるかどうかを示します。 |
| [setAutomaticMaxValue(boolean value)](#setAutomaticMaxValue-boolean-) | 最大値が自動的に割り当てられるかどうかを示します。 |
| [getMaxValue()](#getMaxValue--) | 値軸の最大値を表します。 |
| [setMaxValue(double value)](#setMaxValue-double-) | 値軸の最大値を表します。 |
| [getMinorUnit()](#getMinorUnit--) | 日付軸または値軸の副単位を表します。 |
| [setMinorUnit(double value)](#setMinorUnit-double-) | 日付軸または値軸の副単位を表します。 |
| [isAutomaticMinorUnit()](#isAutomaticMinorUnit--) | 軸の副単位が自動的に割り当てられるかどうかを示します。 |
| [setAutomaticMinorUnit(boolean value)](#setAutomaticMinorUnit-boolean-) | 軸の副単位が自動的に割り当てられるかどうかを示します。 |
| [getMajorUnit()](#getMajorUnit--) | 日付軸または値軸の主要単位を表します。 |
| [setMajorUnit(double value)](#setMajorUnit-double-) | 日付軸または値軸の主要単位を表します。 |
| [isAutomaticMajorUnit()](#isAutomaticMajorUnit--) | 軸の主要単位が自動的に割り当てられるかどうかを示します。 |
| [setAutomaticMajorUnit(boolean value)](#setAutomaticMajorUnit-boolean-) | 軸の主要単位が自動的に割り当てられるかどうかを示します。 |
| [isAutomaticMinValue()](#isAutomaticMinValue--) | 最小値が自動的に割り当てられるかどうかを示します。 |
| [setAutomaticMinValue(boolean value)](#setAutomaticMinValue-boolean-) | 最小値が自動的に割り当てられるかどうかを示します。 |
| [getMinValue()](#getMinValue--) | 値軸の最小値を表します。 |
| [setMinValue(double value)](#setMinValue-double-) | 値軸の最小値を表します。 |
| [isLogarithmic()](#isLogarithmic--) | 値軸のスケールタイプが対数かどうかを表します。 |
| [setLogarithmic(boolean value)](#setLogarithmic-boolean-) | 値軸のスケールタイプが対数かどうかを表します。 |
| [getLogBase()](#getLogBase--) | 対数の底を表します。 |
| [setLogBase(double value)](#setLogBase-double-) | 対数の底を表します。 |
| [isPlotOrderReversed()](#isPlotOrderReversed--) | MS PowerPoint がデータポイントを最後から最初へプロットするかどうかを表します。 |
| [setPlotOrderReversed(boolean value)](#setPlotOrderReversed-boolean-) | MS PowerPoint がデータポイントを最後から最初へプロットするかどうかを表します。 |
| [isVisible()](#isVisible--) | 軸が表示されているかどうかを表します。 |
| [setVisible(boolean value)](#setVisible-boolean-) | 軸が表示されているかどうかを表します。 |
| [getMajorTickMark()](#getMajorTickMark--) | 指定された軸の主要目盛りのタイプを表します。 |
| [setMajorTickMark(int value)](#setMajorTickMark-int-) | 指定された軸の主要目盛りのタイプを表します。 |
| [getMinorTickMark()](#getMinorTickMark--) | 指定された軸の副目盛りのタイプを表します。 |
| [setMinorTickMark(int value)](#setMinorTickMark-int-) | 指定された軸の副目盛りのタイプを表します。 |
| [getTickLabelPosition()](#getTickLabelPosition--) | 指定された軸上の目盛りラベルの位置を表します。 |
| [setTickLabelPosition(int value)](#setTickLabelPosition-int-) | 指定された軸上の目盛りラベルの位置を表します。 |
| [getMajorUnitScale()](#getMajorUnitScale--) | 日付軸の主要単位スケールを表します。 |
| [setMajorUnitScale(int value)](#setMajorUnitScale-int-) | 日付軸の主要単位スケールを表します。 |
| [getMinorUnitScale()](#getMinorUnitScale--) | 日付軸の主要単位スケールを表します。 |
| [setMinorUnitScale(int value)](#setMinorUnitScale-int-) | 日付軸の主要単位スケールを表します。 |
| [getBaseUnitScale()](#getBaseUnitScale--) | 日付軸で表される最小の時間単位を指定します。 |
| [setBaseUnitScale(int value)](#setBaseUnitScale-int-) | 日付軸で表される最小の時間単位を指定します。 |
| [getMinorGridLinesFormat()](#getMinorGridLinesFormat--) | チャート軸上の副目盛線の書式を表します。 |
| [getMajorGridLinesFormat()](#getMajorGridLinesFormat--) | チャート軸上の主要目盛線の書式を表します。 |
| [getShowMinorGridLines()](#getShowMinorGridLines--) | 副目盛線を非表示にするには、MinorGridLinesFormat.Line.FillFormat.FillType を FillType.NoFill に設定します。 |
| [getShowMajorGridLines()](#getShowMajorGridLines--) | 主要目盛線を非表示にするには、MajorGridLinesFormat.Line.FillFormat.FillType を FillType.NoFill に設定します。 |
| [getFormat()](#getFormat--) | 軸の書式を表します。 |
| [getTextFormat()](#getTextFormat--) | テキストの書式を表します。 |
| [getTitle()](#getTitle--) | 軸のタイトルを取得します。 |
| [getCrossType()](#getCrossType--) | 他の軸が交差する指定軸上の CrossType を表します。 |
| [setCrossType(int value)](#setCrossType-int-) | 他の軸が交差する指定軸上の CrossType を表します。 |
| [getPosition()](#getPosition--) | 軸の位置を表します。 |
| [setPosition(int value)](#setPosition-int-) | 軸の位置を表します。 |
| [hasTitle()](#hasTitle--) | 軸に表示可能なタイトルがあるかどうかを決定します。 |
| [setTitle(boolean value)](#setTitle-boolean-) | 軸に表示可能なタイトルがあるかどうかを決定します。 |
| [getNumberFormat()](#getNumberFormat--) | 軸ラベルの書式文字列を表します。 |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | 軸ラベルの書式文字列を表します。 |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | 書式がリンクされた元データかどうかを示します。 |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | 書式がリンクされた元データかどうかを示します。 |
| [getTickLabelRotationAngle()](#getTickLabelRotationAngle--) | 目盛ラベルの回転角度を表します。 |
| [setTickLabelRotationAngle(float value)](#setTickLabelRotationAngle-float-) | 目盛ラベルの回転角度を表します。 |
| [getTickLabelSpacing()](#getTickLabelSpacing--) | 描画されるラベル間でスキップする目盛ラベルの数を指定します。 |
| [setTickLabelSpacing(long value)](#setTickLabelSpacing-long-) | 描画されるラベル間でスキップする目盛ラベルの数を指定します。 |
| [isAutomaticTickLabelSpacing()](#isAutomaticTickLabelSpacing--) | 目盛ラベル間の自動間隔値を指定します。 |
| [setAutomaticTickLabelSpacing(boolean value)](#setAutomaticTickLabelSpacing-boolean-) | 目盛ラベル間の自動間隔値を指定します。 |
| [getTickMarksSpacing()](#getTickMarksSpacing--) | 次の目盛りが描画されるまでにスキップする目盛りの数を指定します。 |
| [setTickMarksSpacing(long value)](#setTickMarksSpacing-long-) | 次の目盛りが描画されるまでにスキップする目盛りの数を指定します。 |
| [isAutomaticTickMarksSpacing()](#isAutomaticTickMarksSpacing--) | 目盛り間の自動間隔値を指定します。 |
| [setAutomaticTickMarksSpacing(boolean value)](#setAutomaticTickMarksSpacing-boolean-) | 目盛り間の自動間隔値を指定します。 |
| [getLabelOffset()](#getLabelOffset--) | ラベルと軸の距離を指定します。 |
| [setLabelOffset(int value)](#setLabelOffset-int-) | ラベルと軸の距離を指定します。 |
| [getAggregationType()](#getAggregationType--) | カテゴリ軸（ビニング）の集計タイプを表します。 |
| [setAggregationType(int value)](#setAggregationType-int-) | カテゴリ軸（ビニング）の集計タイプを表します。 |
| [getBinWidth()](#getBinWidth--) | AggregationType プロパティの値が AxisAggregationType.ByBinWidth に設定されている場合のビン幅を指定します。 |
| [setBinWidth(double value)](#setBinWidth-double-) | AggregationType プロパティの値が AxisAggregationType.ByBinWidth に設定されている場合のビン幅を指定します。 |
| [getNumberOfBins()](#getNumberOfBins--) | AggregationType プロパティの値が AxisAggregationType.ByNumberOfBins に設定されている場合のビン数を指定します。 |
| [setNumberOfBins(long value)](#setNumberOfBins-long-) | AggregationType プロパティの値が AxisAggregationType.ByNumberOfBins に設定されている場合のビン数を指定します。 |
| [isOverflowBin()](#isOverflowBin--) | オーバーフロービンが適用されるかどうかを指定します。 |
| [setOverflowBin(boolean value)](#setOverflowBin-boolean-) | オーバーフロービンが適用されるかどうかを指定します。 |
| [isAutomaticOverflowBin()](#isAutomaticOverflowBin--) | オーバーフロービンの自動値を指定します。 |
| [setAutomaticOverflowBin(boolean value)](#setAutomaticOverflowBin-boolean-) | オーバーフロービンの自動値を指定します。 |
| [getOverflowBin()](#getOverflowBin--) | オーバーフロービンのカスタム値を指定します。 |
| [setOverflowBin(double value)](#setOverflowBin-double-) | オーバーフロービンのカスタム値を指定します。 |
| [isUnderflowBin()](#isUnderflowBin--) | アンダーフロービンが適用されるかどうかを指定します。 |
| [setUnderflowBin(boolean value)](#setUnderflowBin-boolean-) | アンダーフロービンが適用されるかどうかを指定します。 |
| [isAutomaticUnderflowBin()](#isAutomaticUnderflowBin--) | アンダーフロービンの自動値を指定します。 |
| [setAutomaticUnderflowBin(boolean value)](#setAutomaticUnderflowBin-boolean-) | アンダーフロービンの自動値を指定します。 |
| [getUnderflowBin()](#getUnderflowBin--) | アンダーフロービンのカスタム値を指定します。 |
| [setUnderflowBin(double value)](#setUnderflowBin-double-) | アンダーフロービンのカスタム値を指定します。 |
| [getSlide()](#getSlide--) | FillFormat の親スライドを返します。 |
| [getPresentation()](#getPresentation--) | FillFormat の親プレゼンテーションを返します。 |

### getChart() {#getChart--}
```
public final IChart getChart()
```

親チャートを返します。 読み取り専用 [IChart](../../com.aspose.slides/ichart).

**戻り値:**
[IChart](../../com.aspose.slides/ichart)

### getAxisBetweenCategories() {#getAxisBetweenCategories--}
```
public final boolean getAxisBetweenCategories()
```

値軸がカテゴリ軸をカテゴリ間で交差するかどうかを表します。このプロパティはカテゴリ軸にのみ適用され、3-D チャートには適用されません。 読み書き boolean.

**戻り値:**
boolean

### setAxisBetweenCategories(boolean value) {#setAxisBetweenCategories-boolean-}
```
public final void setAxisBetweenCategories(boolean value)
```

値軸がカテゴリ軸をカテゴリ間で交差するかどうかを表します。このプロパティはカテゴリ軸にのみ適用され、3-D チャートには適用されません。 読み書き boolean.

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getCategoryAxisType() {#getCategoryAxisType--}
```
public final int getCategoryAxisType()
```

カテゴリ軸のタイプを指定します。 読み書き [CategoryAxisType](../../com.aspose.slides/categoryaxistype).

**戻り値:**
int

### setCategoryAxisType(int value) {#setCategoryAxisType-int-}
```
public final void setCategoryAxisType(int value)
```

カテゴリ軸のタイプを指定します。 読み書き [CategoryAxisType](../../com.aspose.slides/categoryaxistype).

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### setCategoryAxisTypeAutomatically() {#setCategoryAxisTypeAutomatically--}
```
public final void setCategoryAxisTypeAutomatically()
```

IAxis.CategoryAxisType プロパティを軸データに基づいて自動的に決定される値で設定します。

### getCrossAt() {#getCrossAt--}
```
public final float getCrossAt()
```

垂直軸が交差する軸上の点を表します。 読み書き float.

**戻り値:**
float

### setCrossAt(float value) {#setCrossAt-float-}
```
public final void setCrossAt(float value)
```

垂直軸が交差する軸上の点を表します。 読み書き float.

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getDisplayUnit() {#getDisplayUnit--}
```
public final int getDisplayUnit()
```

値軸の表示単位のスケーリング値を指定します。 読み書き [DisplayUnitType](../../com.aspose.slides/displayunittype).

**戻り値:**
int

### setDisplayUnit(int value) {#setDisplayUnit-int-}
```
public final void setDisplayUnit(int value)
```

値軸の表示単位のスケーリング値を指定します。 読み書き [DisplayUnitType](../../com.aspose.slides/displayunittype).

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getActualMaxValue() {#getActualMaxValue--}
```
public final double getActualMaxValue()
```

軸上の実際の最大値を指定します。実際の値を取得するには、事前に IChart.ValidateChartLayout() メソッドを呼び出してください。

**戻り値:**
double

### getActualMinValue() {#getActualMinValue--}
```
public final double getActualMinValue()
```

軸上の実際の最小値を指定します。実際の値を取得するには、事前に IChart.ValidateChartLayout() メソッドを呼び出してください。

**戻り値:**
double

### getActualMajorUnit() {#getActualMajorUnit--}
```
public final double getActualMajorUnit()
```

軸の実際の主要単位を指定します。実際の値を取得するには、事前に IChart.ValidateChartLayout() メソッドを呼び出してください。

**戻り値:**
double

### getActualMinorUnit() {#getActualMinorUnit--}
```
public final double getActualMinorUnit()
```

軸の実際の副単位を指定します。実際の値を取得するには、事前に IChart.ValidateChartLayout() メソッドを呼び出してください。

**戻り値:**
double

### getActualMajorUnitScale() {#getActualMajorUnitScale--}
```
public final int getActualMajorUnitScale()
```

軸の実際の主要単位スケールを指定します。実際の値を取得するには、事前に IChart.ValidateChartLayout() メソッドを呼び出してください。

**戻り値:**
int

### getActualMinorUnitScale() {#getActualMinorUnitScale--}
```
public final int getActualMinorUnitScale()
```

軸の実際の副単位スケールを指定します。実際の値を取得するには、事前に IChart.ValidateChartLayout() メソッドを呼び出してください。

**戻り値:**
int

### isAutomaticMaxValue() {#isAutomaticMaxValue--}
```
public final boolean isAutomaticMaxValue()
```

最大値が自動的に割り当てられるかどうかを示します。 読み書き boolean.

**戻り値:**
boolean

### setAutomaticMaxValue(boolean value) {#setAutomaticMaxValue-boolean-}
```
public final void setAutomaticMaxValue(boolean value)
```

最大値が自動的に割り当てられるかどうかを示します。 読み書き boolean.

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getMaxValue() {#getMaxValue--}
```
public final double getMaxValue()
```

値軸の最大値を表します。 読み書き double.

**戻り値:**
double

### setMaxValue(double value) {#setMaxValue-double-}
```
public final void setMaxValue(double value)
```

値軸の最大値を表します。 読み書き double.

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | double |  |

### getMinorUnit() {#getMinorUnit--}
```
public final double getMinorUnit()
```

日付軸または値軸の副単位を表します。 読み書き double.

**戻り値:**
double

### setMinorUnit(double value) {#setMinorUnit-double-}
```
public final void setMinorUnit(double value)
```

日付軸または値軸の副単位を表します。 読み書き double.

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | double |  |

### isAutomaticMinorUnit() {#isAutomaticMinorUnit--}
```
public final boolean isAutomaticMinorUnit()
```
軸のマイナーユニットが自動的に割り当てられるかどうかを示します。読み取り/書き込み boolean。

**戻り値:**
boolean
### setAutomaticMinorUnit(boolean value) {#setAutomaticMinorUnit-boolean-}
```
public final void setAutomaticMinorUnit(boolean value)
```


軸のマイナーユニットが自動的に割り当てられるかどうかを示します。読み取り/書き込み boolean。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getMajorUnit() {#getMajorUnit--}
```
public final double getMajorUnit()
```


日付軸または値軸の主要ユニットを表します。読み取り/書き込み double。

**戻り値:**
double
### setMajorUnit(double value) {#setMajorUnit-double-}
```
public final void setMajorUnit(double value)
```


日付軸または値軸の主要ユニットを表します。読み取り/書き込み double。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | double |  |

### isAutomaticMajorUnit() {#isAutomaticMajorUnit--}
```
public final boolean isAutomaticMajorUnit()
```


軸の主要ユニットが自動的に割り当てられるかどうかを示します。読み取り/書き込み boolean。

**戻り値:**
boolean
### setAutomaticMajorUnit(boolean value) {#setAutomaticMajorUnit-boolean-}
```
public final void setAutomaticMajorUnit(boolean value)
```


軸の主要ユニットが自動的に割り当てられるかどうかを示します。読み取り/書き込み boolean。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticMinValue() {#isAutomaticMinValue--}
```
public final boolean isAutomaticMinValue()
```


最小値が自動的に割り当てられるかどうかを示します。読み取り/書き込み boolean。

**戻り値:**
boolean
### setAutomaticMinValue(boolean value) {#setAutomaticMinValue-boolean-}
```
public final void setAutomaticMinValue(boolean value)
```


最小値が自動的に割り当てられるかどうかを示します。読み取り/書き込み boolean。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getMinValue() {#getMinValue--}
```
public final double getMinValue()
```


値軸上の最小値を表します。読み取り/書き込み double。

**戻り値:**
double
### setMinValue(double value) {#setMinValue-double-}
```
public final void setMinValue(double value)
```


値軸上の最小値を表します。読み取り/書き込み double。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | double |  |

### isLogarithmic() {#isLogarithmic--}
```
public final boolean isLogarithmic()
```


値軸のスケールタイプが対数かどうかを表します。読み取り/書き込み boolean。

**戻り値:**
boolean
### setLogarithmic(boolean value) {#setLogarithmic-boolean-}
```
public final void setLogarithmic(boolean value)
```


値軸のスケールタイプが対数かどうかを表します。読み取り/書き込み boolean。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getLogBase() {#getLogBase--}
```
public final double getLogBase()
```


対数の底を表します。デフォルト値は 10 です。読み取り/書き込み double。

**戻り値:**
double
### setLogBase(double value) {#setLogBase-double-}
```
public final void setLogBase(double value)
```


対数の底を表します。デフォルト値は 10 です。読み取り/書き込み double。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | double |  |

### isPlotOrderReversed() {#isPlotOrderReversed--}
```
public final boolean isPlotOrderReversed()
```


MS PowerPoint がデータポイントを最後から最初へプロットするかどうかを表します。読み取り/書き込み boolean。

**戻り値:**
boolean
### setPlotOrderReversed(boolean value) {#setPlotOrderReversed-boolean-}
```
public final void setPlotOrderReversed(boolean value)
```


MS PowerPoint がデータポイントを最後から最初へプロットするかどうかを表します。読み取り/書き込み boolean。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### isVisible() {#isVisible--}
```
public final boolean isVisible()
```


軸が表示されているかどうかを表します。読み取り/書き込み boolean。

**戻り値:**
boolean
### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```


軸が表示されているかどうかを表します。読み取り/書き込み boolean。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getMajorTickMark() {#getMajorTickMark--}
```
public final int getMajorTickMark()
```


指定された軸の主要目盛りの種類を表します。読み取り/書き込み [TickMarkType](../../com.aspose.slides/tickmarktype)。

**戻り値:**
int
### setMajorTickMark(int value) {#setMajorTickMark-int-}
```
public final void setMajorTickMark(int value)
```


指定された軸の主要目盛りの種類を表します。読み取り/書き込み [TickMarkType](../../com.aspose.slides/tickmarktype)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getMinorTickMark() {#getMinorTickMark--}
```
public final int getMinorTickMark()
```


指定された軸の副目盛りの種類を表します。読み取り/書き込み [TickMarkType](../../com.aspose.slides/tickmarktype)。

**戻り値:**
int
### setMinorTickMark(int value) {#setMinorTickMark-int-}
```
public final void setMinorTickMark(int value)
```


指定された軸の副目盛りの種類を表します。読み取り/書き込み [TickMarkType](../../com.aspose.slides/tickmarktype)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getTickLabelPosition() {#getTickLabelPosition--}
```
public final int getTickLabelPosition()
```


指定された軸の目盛ラベルの位置を表します。読み取り/書き込み [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype)。

**戻り値:**
int
### setTickLabelPosition(int value) {#setTickLabelPosition-int-}
```
public final void setTickLabelPosition(int value)
```


指定された軸の目盛ラベルの位置を表します。読み取り/書き込み [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getMajorUnitScale() {#getMajorUnitScale--}
```
public final int getMajorUnitScale()
```


日付軸の主要ユニットスケールを表します。読み取り/書き込み [TimeUnitType](../../com.aspose.slides/timeunittype)。

**戻り値:**
int
### setMajorUnitScale(int value) {#setMajorUnitScale-int-}
```
public final void setMajorUnitScale(int value)
```


日付軸の主要ユニットスケールを表します。読み取り/書き込み [TimeUnitType](../../com.aspose.slides/timeunittype)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getMinorUnitScale() {#getMinorUnitScale--}
```
public final int getMinorUnitScale()
```


日付軸の主要ユニットスケールを表します。読み取り/書き込み [TimeUnitType](../../com.aspose.slides/timeunittype)。

**戻り値:**
int
### setMinorUnitScale(int value) {#setMinorUnitScale-int-}
```
public final void setMinorUnitScale(int value)
```


日付軸の主要ユニットスケールを表します。読み取り/書き込み [TimeUnitType](../../com.aspose.slides/timeunittype)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getBaseUnitScale() {#getBaseUnitScale--}
```
public final int getBaseUnitScale()
```


日付軸で表される最小の時間単位を指定します。読み取り/書き込み [TimeUnitType](../../com.aspose.slides/timeunittype)。

**戻り値:**
int
### setBaseUnitScale(int value) {#setBaseUnitScale-int-}
```
public final void setBaseUnitScale(int value)
```


日付軸で表される最小の時間単位を指定します。読み取り/書き込み [TimeUnitType](../../com.aspose.slides/timeunittype)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getMinorGridLinesFormat() {#getMinorGridLinesFormat--}
```
public final IChartLinesFormat getMinorGridLinesFormat()
```


チャート軸上の小さなグリッドラインの形式を表します。読み取り専用 [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)。

**戻り値:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### getMajorGridLinesFormat() {#getMajorGridLinesFormat--}
```
public final IChartLinesFormat getMajorGridLinesFormat()
```


チャート軸上の大きなグリッドラインの形式を表します。読み取り専用 [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)。

**戻り値:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### getShowMinorGridLines() {#getShowMinorGridLines--}
```
public final boolean getShowMinorGridLines()
```


小さなグリッドラインを非表示にするには MinorGridLinesFormat.Line.FillFormat.FillType を FillType.NoFill に設定します。読み取り専用 boolean。

**戻り値:**
boolean
### getShowMajorGridLines() {#getShowMajorGridLines--}
```
public final boolean getShowMajorGridLines()
```


大きなグリッドラインを非表示にするには MajorGridLinesFormat.Line.FillFormat.FillType を FillType.NoFill に設定します。読み取り専用 boolean。

**戻り値:**
boolean
### getFormat() {#getFormat--}
```
public final IAxisFormat getFormat()
```


軸の形式を表します。読み取り専用 [IAxisFormat](../../com.aspose.slides/iaxisformat)。

**戻り値:**
[IAxisFormat](../../com.aspose.slides/iaxisformat)
### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```


テキストの形式を表します。読み取り専用 [IChartTextFormat](../../com.aspose.slides/icharttextformat)。

**戻り値:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### getTitle() {#getTitle--}
```
public final IChartTitle getTitle()
```


軸のタイトルを取得します。読み取り専用 [IChartTitle](../../com.aspose.slides/icharttitle)。

**戻り値:**
[IChartTitle](../../com.aspose.slides/icharttitle)
### getCrossType() {#getCrossType--}
```
public final int getCrossType()
```


他の軸が交差する位置の CrossType を表します。読み取り/書き込み [CrossesType](../../com.aspose.slides/crossestype)。

**戻り値:**
int
### setCrossType(int value) {#setCrossType-int-}
```
public final void setCrossType(int value)
```


他の軸が交差する位置の CrossType を表します。読み取り/書き込み [CrossesType](../../com.aspose.slides/crossestype)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getPosition() {#getPosition--}
```
public final int getPosition()
```


軸の位置を表します。読み取り/書き込み [AxisPositionType](../../com.aspose.slides/axispositiontype)。

**戻り値:**
int
### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```


軸の位置を表します。読み取り/書き込み [AxisPositionType](../../com.aspose.slides/axispositiontype)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### hasTitle() {#hasTitle--}
```
public final boolean hasTitle()
```


軸に表示可能なタイトルがあるかどうかを判定します。読み取り/書き込み boolean。

**戻り値:**
boolean
### setTitle(boolean value) {#setTitle-boolean-}
```
public final void setTitle(boolean value)
```


軸に表示可能なタイトルがあるかどうかを判定します。読み取り/書き込み boolean。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public final String getNumberFormat()
```


軸ラベルの書式文字列を表します。読み取り/書き込み String。

**戻り値:**
java.lang.String
### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public final void setNumberFormat(String value)
```


軸ラベルの書式文字列を表します。読み取り/書き込み String。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public final boolean isNumberFormatLinkedToSource()
```


書式がソースデータにリンクされているかどうかを示します。読み取り/書き込み boolean。

**戻り値:**
boolean
### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public final void setNumberFormatLinkedToSource(boolean value)
```


書式がソースデータにリンクされているかどうかを示します。読み取り/書き込み boolean。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getTickLabelRotationAngle() {#getTickLabelRotationAngle--}
```
public final float getTickLabelRotationAngle()
```


目盛ラベルの回転角度を表します。読み取り/書き込み float。

**戻り値:**
float
### setTickLabelRotationAngle(float value) {#setTickLabelRotationAngle-float-}
```
public final void setTickLabelRotationAngle(float value)
```


目盛ラベルの回転角度を表します。読み取り/書き込み float。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | float |  |

### getTickLabelSpacing() {#getTickLabelSpacing--}
```
public final long getTickLabelSpacing()
```


描画されるラベル間でスキップする目盛ラベルの数を指定します。カテゴリ軸または系列軸に適用されます。読み取り/書き込み long。

**戻り値:**
long
### setTickLabelSpacing(long value) {#setTickLabelSpacing-long-}
```
public final void setTickLabelSpacing(long value)
```


描画されるラベル間でスキップする目盛ラベルの数を指定します。カテゴリ軸または系列軸に適用されます。読み取り/書き込み long。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickLabelSpacing() {#isAutomaticTickLabelSpacing--}
```
public final boolean isAutomaticTickLabelSpacing()
```


自動目盛ラベル間隔の値を指定します。false の場合は TickLabelSpacing プロパティを使用します。読み取り/書き込み boolean。

**戻り値:**
boolean
### setAutomaticTickLabelSpacing(boolean value) {#setAutomaticTickLabelSpacing-boolean-}
```
public final void setAutomaticTickLabelSpacing(boolean value)
```


自動目盛ラベル間隔の値を指定します。false の場合は TickLabelSpacing プロパティを使用します。読み取り/書き込み boolean。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getTickMarksSpacing() {#getTickMarksSpacing--}
```
public final long getTickMarksSpacing()
```


次の目盛りが描画されるまでにスキップする目盛りの数を指定します。カテゴリ軸または系列軸に適用されます。読み取り/書き込み int。

**戻り値:**
long
### setTickMarksSpacing(long value) {#setTickMarksSpacing-long-}
```
public final void setTickMarksSpacing(long value)
```


次の目盛りが描画されるまでにスキップする目盛りの数を指定します。カテゴリ軸または系列軸に適用されます。読み取り/書き込み int。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickMarksSpacing() {#isAutomaticTickMarksSpacing--}
```
public final boolean isAutomaticTickMarksSpacing()
```


自動目盛り間隔の値を指定します。false の場合は TickMarksSpacing プロパティを使用します。読み取り/書き込み boolean。

**戻り値:**
boolean
### setAutomaticTickMarksSpacing(boolean value) {#setAutomaticTickMarksSpacing-boolean-}
```
public final void setAutomaticTickMarksSpacing(boolean value)
```


自動目盛り間隔の値を指定します。false の場合は TickMarksSpacing プロパティを使用します。読み取り/書き込み boolean。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getLabelOffset() {#getLabelOffset--}
```
public final int getLabelOffset()
```


ラベルと軸との距離を指定します。カテゴリ軸または日付軸に適用されます。値は 0% から 1000% の間でなければなりません。読み取り/書き込み int。

**戻り値:**
int
### setLabelOffset(int value) {#setLabelOffset-int-}
```
public final void setLabelOffset(int value)
```


ラベルと軸との距離を指定します。カテゴリ軸または日付軸に適用されます。値は 0% から 1000% の間でなければなりません。読み取り/書き込み int。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |
### getAggregationType() {#getAggregationType--}
```
public final int getAggregationType()
```

カテゴリ軸（ビニング）の集計タイプを表します。カテゴリに適用されます。Histogram または HistogramPareto 系列でのみ使用できます。

**戻り値:**
int
### setAggregationType(int value) {#setAggregationType-int-}
```
public final void setAggregationType(int value)
```

カテゴリ軸（ビニング）の集計タイプを表します。カテゴリに適用されます。Histogram または HistogramPareto 系列でのみ使用できます。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getBinWidth() {#getBinWidth--}
```
public final double getBinWidth()
```

AggregationType プロパティの値が AxisAggregationType.ByBinWidth に設定されている場合のビン幅を指定します。カテゴリ軸に適用されます。Histogram または HistogramPareto 系列でのみ使用できます。

**戻り値:**
double
### setBinWidth(double value) {#setBinWidth-double-}
```
public final void setBinWidth(double value)
```

AggregationType プロパティの値が AxisAggregationType.ByBinWidth に設定されている場合のビン幅を指定します。カテゴリ軸に適用されます。Histogram または HistogramPareto 系列でのみ使用できます。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | double |  |

### getNumberOfBins() {#getNumberOfBins--}
```
public final long getNumberOfBins()
```

AggregationType プロパティの値が AxisAggregationType.ByNumberOfBins に設定されている場合のビン数を指定します。カテゴリ軸に適用されます。Histogram または HistogramPareto 系列でのみ使用できます。

**戻り値:**
long
### setNumberOfBins(long value) {#setNumberOfBins-long-}
```
public final void setNumberOfBins(long value)
```

AggregationType プロパティの値が AxisAggregationType.ByNumberOfBins に設定されている場合のビン数を指定します。カテゴリ軸に適用されます。Histogram または HistogramPareto 系列でのみ使用できます。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | long |  |

### isOverflowBin() {#isOverflowBin--}
```
public final boolean isOverflowBin()
```

オーバーフロービンが適用されるかどうかを指定します。オーバーフロービンの値を調整するには IsAutomaticOverflowBin と OverflowBin を使用してください。

**戻り値:**
boolean
### setOverflowBin(boolean value) {#setOverflowBin-boolean-}
```
public final void setOverflowBin(boolean value)
```

オーバーフロービンが適用されるかどうかを指定します。オーバーフロービンの値を調整するには IsAutomaticOverflowBin と OverflowBin を使用してください。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticOverflowBin() {#isAutomaticOverflowBin--}
```
public final boolean isAutomaticOverflowBin()
```

自動オーバーフロービンの値を指定します。false の場合は OverflowBin プロパティを使用します。

**戻り値:**
boolean
### setAutomaticOverflowBin(boolean value) {#setAutomaticOverflowBin-boolean-}
```
public final void setAutomaticOverflowBin(boolean value)
```

自動オーバーフロービンの値を指定します。false の場合は OverflowBin プロパティを使用します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getOverflowBin() {#getOverflowBin--}
```
public final double getOverflowBin()
```

オーバーフロービンのカスタム値を指定します。IsAutomaticOverflowBin プロパティが false に設定され、IsOverflowBin プロパティが true のときに適用されます。

**戻り値:**
double
### setOverflowBin(double value) {#setOverflowBin-double-}
```
public final void setOverflowBin(double value)
```

オーバーフロービンのカスタム値を指定します。IsAutomaticOverflowBin プロパティが false に設定され、IsOverflowBin プロパティが true のときに適用されます。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | double |  |

### isUnderflowBin() {#isUnderflowBin--}
```
public final boolean isUnderflowBin()
```

アンダーフロービンが適用されるかどうかを指定します。アンダーフロービンの値を調整するには IsAutomaticUnderflowBin と UnderflowBin を使用してください。

**戻り値:**
boolean
### setUnderflowBin(boolean value) {#setUnderflowBin-boolean-}
```
public final void setUnderflowBin(boolean value)
```

アンダーフロービンが適用されるかどうかを指定します。アンダーフロービンの値を調整するには IsAutomaticUnderflowBin と UnderflowBin を使用してください。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticUnderflowBin() {#isAutomaticUnderflowBin--}
```
public final boolean isAutomaticUnderflowBin()
```

自動アンダーフロービンの値を指定します。false の場合は UnderflowBin プロパティを使用します。

**戻り値:**
boolean
### setAutomaticUnderflowBin(boolean value) {#setAutomaticUnderflowBin-boolean-}
```
public final void setAutomaticUnderflowBin(boolean value)
```

自動アンダーフロービンの値を指定します。false の場合は UnderflowBin プロパティを使用します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getUnderflowBin() {#getUnderflowBin--}
```
public final double getUnderflowBin()
```

アンダーフロービンのカスタム値を指定します。IsAutomaticUnderflowBin プロパティが false に設定され、IsUnderflowBin プロパティが true のときに適用されます。

**戻り値:**
double
### setUnderflowBin(double value) {#setUnderflowBin-double-}
```
public final void setUnderflowBin(double value)
```

アンダーフロービンのカスタム値を指定します。IsAutomaticUnderflowBin プロパティが false に設定され、IsUnderflowBin プロパティが true のときに適用されます。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | double |  |

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

FillFormat の親スライドを返します。読み取り専用 [BaseSlide](../../com.aspose.slides/baseslide)。

**戻り値:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

FillFormat の親プレゼンテーションを返します。読み取り専用 [IPresentation](../../com.aspose.slides/ipresentation)。

**戻り値:**
[IPresentation](../../com.aspose.slides/ipresentation)