---
title: Axis
second_title: Aspose.Slides for Java – referenční příručka API
description: Zapouzdřuje objekt, který představuje osu grafu.
type: docs
url: /cs/com.aspose.slides/axis/
---
**Dědičnost:**
java.lang.Object, com.aspose.slides.DomObject

**Všechny implementované rozhraní:**
[com.aspose.slides.IAxis](../../com.aspose.slides/iaxis)
```
public class Axis extends DomObject<AxesManager> implements IAxis
```

Zapouzdřuje objekt, který představuje osu grafu.
## Metody

| Metoda | Popis |
| --- | --- |
| [getChart()](#getChart--) | Vrací nadřazený graf. |
| [getAxisBetweenCategories()](#getAxisBetweenCategories--) | Určuje, zda osa hodnot protíná osu kategorií mezi kategoriemi. |
| [setAxisBetweenCategories(boolean value)](#setAxisBetweenCategories-boolean-) | Určuje, zda osa hodnot protíná osu kategorií mezi kategoriemi. |
| [getCategoryAxisType()](#getCategoryAxisType--) | Určuje typ osy kategorií. |
| [setCategoryAxisType(int value)](#setCategoryAxisType-int-) | Určuje typ osy kategorií. |
| [setCategoryAxisTypeAutomatically()](#setCategoryAxisTypeAutomatically--) | Nastavuje vlastnost IAxis.CategoryAxisType s hodnotou, která je automaticky určena na základě dat osy. |
| [getCrossAt()](#getCrossAt--) | Zobrazuje bod na ose, kde ji protíná kolmá osa. |
| [setCrossAt(float value)](#setCrossAt-float-) | Zobrazuje bod na ose, kde ji protíná kolmá osa. |
| [getDisplayUnit()](#getDisplayUnit--) | Určuje měřítko zobrazovacích jednotek pro osu hodnot. |
| [setDisplayUnit(int value)](#setDisplayUnit-int-) | Určuje měřítko zobrazovacích jednotek pro osu hodnot. |
| [getActualMaxValue()](#getActualMaxValue--) | Určuje skutečnou maximální hodnotu na ose. |
| [getActualMinValue()](#getActualMinValue--) | Určuje skutečnou minimální hodnotu na ose. |
| [getActualMajorUnit()](#getActualMajorUnit--) | Určuje skutečnou hlavní jednotku osy. |
| [getActualMinorUnit()](#getActualMinorUnit--) | Určuje skutečnou vedlejší jednotku osy. |
| [getActualMajorUnitScale()](#getActualMajorUnitScale--) | Určuje skutečné měřítko hlavní jednotky osy. |
| [getActualMinorUnitScale()](#getActualMinorUnitScale--) | Určuje skutečné měřítko vedlejší jednotky osy. |
| [isAutomaticMaxValue()](#isAutomaticMaxValue--) | Indikuje, zda je maximální hodnota přiřazena automaticky. |
| [setAutomaticMaxValue(boolean value)](#setAutomaticMaxValue-boolean-) | Indikuje, zda je maximální hodnota přiřazena automaticky. |
| [getMaxValue()](#getMaxValue--) | Zobrazuje maximální hodnotu na ose hodnot. |
| [setMaxValue(double value)](#setMaxValue-double-) | Zobrazuje maximální hodnotu na ose hodnot. |
| [getMinorUnit()](#getMinorUnit--) | Zobrazuje vedlejší jednotky pro datum nebo osu hodnot. |
| [setMinorUnit(double value)](#setMinorUnit-double-) | Zobrazuje vedlejší jednotky pro datum nebo osu hodnot. |
| [isAutomaticMinorUnit()](#isAutomaticMinorUnit--) | Indikuje, zda je vedlejší jednotka osy přiřazena automaticky. |
| [setAutomaticMinorUnit(boolean value)](#setAutomaticMinorUnit-boolean-) | Indikuje, zda je vedlejší jednotka osy přiřazena automaticky. |
| [getMajorUnit()](#getMajorUnit--) | Zobrazuje hlavní jednotky pro datum nebo osu hodnot. |
| [setMajorUnit(double value)](#setMajorUnit-double-) | Zobrazuje hlavní jednotky pro datum nebo osu hodnot. |
| [isAutomaticMajorUnit()](#isAutomaticMajorUnit--) | Indikuje, zda je hlavní jednotka osy přiřazena automaticky. |
| [setAutomaticMajorUnit(boolean value)](#setAutomaticMajorUnit-boolean-) | Indikuje, zda je hlavní jednotka osy přiřazena automaticky. |
| [isAutomaticMinValue()](#isAutomaticMinValue--) | Indikuje, zda je minimální hodnota přiřazena automaticky. |
| [setAutomaticMinValue(boolean value)](#setAutomaticMinValue-boolean-) | Indikuje, zda je minimální hodnota přiřazena automaticky. |
| [getMinValue()](#getMinValue--) | Zobrazuje minimální hodnotu na ose hodnot. |
| [setMinValue(double value)](#setMinValue-double-) | Zobrazuje minimální hodnotu na ose hodnot. |
| [isLogarithmic()](#isLogarithmic--) | Určuje, zda je typ měřítka osy hodnot logaritmický nebo ne. |
| [setLogarithmic(boolean value)](#setLogarithmic-boolean-) | Určuje, zda je typ měřítka osy hodnot logaritmický nebo ne. |
| [getLogBase()](#getLogBase--) | Zobrazuje logaritmický základ. |
| [setLogBase(double value)](#setLogBase-double-) | Zobrazuje logaritmický základ. |
| [isPlotOrderReversed()](#isPlotOrderReversed--) | Určuje, zda MS PowerPoint vykresluje datové body od posledního k prvnímu. |
| [setPlotOrderReversed(boolean value)](#setPlotOrderReversed-boolean-) | Určuje, zda MS PowerPoint vykresluje datové body od posledního k prvnímu. |
| [isVisible()](#isVisible--) | Určuje, zda je osa viditelná. |
| [setVisible(boolean value)](#setVisible-boolean-) | Určuje, zda je osa viditelná. |
| [getMajorTickMark()](#getMajorTickMark--) | Zobrazuje typ hlavního značky (tiku) pro zadanou osu. |
| [setMajorTickMark(int value)](#setMajorTickMark-int-) | Zobrazuje typ hlavního značky (tiku) pro zadanou osu. |
| [getMinorTickMark()](#getMinorTickMark--) | Zobrazuje typ vedlejší značky (tiku) pro zadanou osu. |
| [setMinorTickMark(int value)](#setMinorTickMark-int-) | Zobrazuje typ vedlejší značky (tiku) pro zadanou osu. |
| [getTickLabelPosition()](#getTickLabelPosition--) | Zobrazuje pozici popisků značek na zadané ose. |
| [setTickLabelPosition(int value)](#setTickLabelPosition-int-) | Zobrazuje pozici popisků značek na zadané ose. |
| [getMajorUnitScale()](#getMajorUnitScale--) | Zobrazuje měřítko hlavní jednotky pro osu dat. |
| [setMajorUnitScale(int value)](#setMajorUnitScale-int-) | Zobrazuje měřítko hlavní jednotky pro osu dat. |
| [getMinorUnitScale()](#getMinorUnitScale--) | Zobrazuje měřítko hlavní jednotky pro osu dat. |
| [setMinorUnitScale(int value)](#setMinorUnitScale-int-) | Zobrazuje měřítko hlavní jednotky pro osu dat. |
| [getBaseUnitScale()](#getBaseUnitScale--) | Určuje nejmenší časovou jednotku, která je zobrazena na ose dat. |
| [setBaseUnitScale(int value)](#setBaseUnitScale-int-) | Určuje nejmenší časovou jednotku, která je zobrazena na ose dat. |
| [getMinorGridLinesFormat()](#getMinorGridLinesFormat--) | Zobrazuje formát vedlejších mřížkových čar na ose grafu. |
| [getMajorGridLinesFormat()](#getMajorGridLinesFormat--) | Zobrazuje formát hlavních mřížkových čar na ose grafu. |
| [getShowMinorGridLines()](#getShowMinorGridLines--) | Pro skrytí vedlejší mřížky nastavte MinorGridLinesFormat.Line.FillFormat.FillType na FillType.NoFill. |
| [getShowMajorGridLines()](#getShowMajorGridLines--) | Pro skrytí hlavní mřížky nastavte MajorGridLinesFormat.Line.FillFormat.FillType na FillType.NoFill. |
| [getFormat()](#getFormat--) | Zobrazuje formát osy. |
| [getTextFormat()](#getTextFormat--) | Zobrazuje formát textu. |
| [getTitle()](#getTitle--) | Získává název osy. |
| [getCrossType()](#getCrossType--) | Zobrazuje typ průseku (CrossType) na zadané ose, kde se protíná druhá osa. |
| [setCrossType(int value)](#setCrossType-int-) | Zobrazuje typ průseku (CrossType) na zadané ose, kde se protíná druhá osa. |
| [getPosition()](#getPosition--) | Zobrazuje pozici osy. |
| [setPosition(int value)](#setPosition-int-) | Zobrazuje pozici osy. |
| [hasTitle()](#hasTitle--) | Určuje, zda má osa viditelný název. |
| [setTitle(boolean value)](#setTitle-boolean-) | Určuje, zda má osa viditelný název. |
| [getNumberFormat()](#getNumberFormat--) | Zobrazuje formátovací řetězec pro popisky osy. |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | Zobrazuje formátovací řetězec pro popisky osy. |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | Indikuje, zda je formát propojen se zdrojovými daty. |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | Indikuje, zda je formát propojen se zdrojovými daty. |
| [getTickLabelRotationAngle()](#getTickLabelRotationAngle--) | Zobrazuje úhel otočení popisků značek. |
| [setTickLabelRotationAngle(float value)](#setTickLabelRotationAngle-float-) | Zobrazuje úhel otočení popisků značek. |
| [getTickLabelSpacing()](#getTickLabelSpacing--) | Určuje, kolik popisků značek se má přeskočit mezi vykreslenými popisky. |
| [setTickLabelSpacing(long value)](#setTickLabelSpacing-long-) | Určuje, kolik popisků značek se má přeskočit mezi vykreslenými popisky. |
| [isAutomaticTickLabelSpacing()](#isAutomaticTickLabelSpacing--) | Určuje automatickou hodnotu rozestupu popisků značek. |
| [setAutomaticTickLabelSpacing(boolean value)](#setAutomaticTickLabelSpacing-boolean-) | Určuje automatickou hodnotu rozestupu popisků značek. |
| [getTickMarksSpacing()](#getTickMarksSpacing--) | Určuje, kolik značek (tíků) se má přeskočit před vykreslením další značky. |
| [setTickMarksSpacing(long value)](#setTickMarksSpacing-long-) | Určuje, kolik značek (tíků) se má přeskočit před vykreslením další značky. |
| [isAutomaticTickMarksSpacing()](#isAutomaticTickMarksSpacing--) | Určuje automatickou hodnotu rozestupu značek. |
| [setAutomaticTickMarksSpacing(boolean value)](#setAutomaticTickMarksSpacing-boolean-) | Určuje automatickou hodnotu rozestupu značek. |
| [getLabelOffset()](#getLabelOffset--) | Určuje vzdálenost popisků od osy. |
| [setLabelOffset(int value)](#setLabelOffset-int-) | Určuje vzdálenost popisků od osy. |
| [getAggregationType()](#getAggregationType--) | Zobrazuje typ agregace osy kategorií (skupinování). |
| [setAggregationType(int value)](#setAggregationType-int-) | Zobrazuje typ agregace osy kategorií (skupinování). |
| [getBinWidth()](#getBinWidth--) | Určuje šířku binu, když je hodnota vlastnosti AggregationType nastavena na AxisAggregationType.ByBinWidth. |
| [setBinWidth(double value)](#setBinWidth-double-) | Určuje šířku binu, když je hodnota vlastnosti AggregationType nastavena na AxisAggregationType.ByBinWidth. |
| [getNumberOfBins()](#getNumberOfBins--) | Určuje počet binů, když je hodnota vlastnosti AggregationType nastavena na AxisAggregationType.ByNumberOfBins. |
| [setNumberOfBins(long value)](#setNumberOfBins-long-) | Určuje počet binů, když je hodnota vlastnosti AggregationType nastavena na AxisAggregationType.ByNumberOfBins. |
| [isOverflowBin()](#isOverflowBin--) | Určuje, zda je použit overflow bin. |
| [setOverflowBin(boolean value)](#setOverflowBin-boolean-) | Určuje, zda je použit overflow bin. |
| [isAutomaticOverflowBin()](#isAutomaticOverflowBin--) | Určuje automatickou hodnotu overflow binu. |
| [setAutomaticOverflowBin(boolean value)](#setAutomaticOverflowBin-boolean-) | Určuje automatickou hodnotu overflow binu. |
| [getOverflowBin()](#getOverflowBin--) | Určuje vlastní hodnotu overflow binu. |
| [setOverflowBin(double value)](#setOverflowBin-double-) | Určuje vlastní hodnotu overflow binu. |
| [isUnderflowBin()](#isUnderflowBin--) | Určuje, zda je použit underflow bin. |
| [setUnderflowBin(boolean value)](#setUnderflowBin-boolean-) | Určuje, zda je použit underflow bin. |
| [isAutomaticUnderflowBin()](#isAutomaticUnderflowBin--) | Určuje automatickou hodnotu underflow binu. |
| [setAutomaticUnderflowBin(boolean value)](#setAutomaticUnderflowBin-boolean-) | Určuje automatickou hodnotu podřízeného binu. |
| [getUnderflowBin()](#getUnderflowBin--) | Určuje vlastní hodnotu underflow binu. |
| [setUnderflowBin(double value)](#setUnderflowBin-double-) | Určuje vlastní hodnotu underflow binu. |
| [getSlide()](#getSlide--) | Vrací nadřazený snímek objektu FillFormat. |
| [getPresentation()](#getPresentation--) | Vrací nadřazenou prezentaci objektu FillFormat. |

### getChart() {#getChart--}
```
public final IChart getChart()
```

Vrací nadřazený graf. Pouze pro čtení [IChart](../../com.aspose.slides/ichart).

**Vrací:**
[IChart](../../com.aspose.slides/ichart)
### getAxisBetweenCategories() {#getAxisBetweenCategories--}
```
public final boolean getAxisBetweenCategories()
```

Určuje, zda osa hodnot protíná osu kategorií mezi kategoriemi. Tato vlastnost platí pouze pro osy kategorií a neplatí pro 3-D grafy. Čtení/zápis boolean.

**Vrací:**
boolean
### setAxisBetweenCategories(boolean value) {#setAxisBetweenCategories-boolean-}
```
public final void setAxisBetweenCategories(boolean value)
```

Určuje, zda osa hodnot protíná osu kategorií mezi kategoriemi. Tato vlastnost platí pouze pro osy kategorií a neplatí pro 3-D grafy. Čtení/zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |
### getCategoryAxisType() {#getCategoryAxisType--}
```
public final int getCategoryAxisType()
```

Určuje typ osy kategorií. Čtení/zápis [CategoryAxisType](../../com.aspose.slides/categoryaxistype).

**Vrací:**
int
### setCategoryAxisType(int value) {#setCategoryAxisType-int-}
```
public final void setCategoryAxisType(int value)
```

Určuje typ osy kategorií. Čtení/zápis [CategoryAxisType](../../com.aspose.slides/categoryaxistype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |
### setCategoryAxisTypeAutomatically() {#setCategoryAxisTypeAutomatically--}
```
public final void setCategoryAxisTypeAutomatically()
```

Nastavuje vlastnost IAxis.CategoryAxisType s hodnotou, která je automaticky určena na základě dat osy.
### getCrossAt() {#getCrossAt--}
```
public final float getCrossAt()
```

Zobrazuje bod na ose, kde ji protíná kolmá osa. Čtení/zápis float.

**Vrací:**
float
### setCrossAt(float value) {#setCrossAt-float-}
```
public final void setCrossAt(float value)
```

Zobrazuje bod na ose, kde ji protíná kolmá osa. Čtení/zápis float.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |
### getDisplayUnit() {#getDisplayUnit--}
```
public final int getDisplayUnit()
```

Určuje měřítko zobrazovacích jednotek pro osu hodnot. Čtení/zápis [DisplayUnitType](../../com.aspose.slides/displayunittype).

**Vrací:**
int
### setDisplayUnit(int value) {#setDisplayUnit-int-}
```
public final void setDisplayUnit(int value)
```

Určuje měřítko zobrazovacích jednotek pro osu hodnot. Čtení/zápis [DisplayUnitType](../../com.aspose.slides/displayunittype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |
### getActualMaxValue() {#getActualMaxValue--}
```
public final double getActualMaxValue()
```

Určuje skutečnou maximální hodnotu na ose. Předtím zavolejte metodu IChart.ValidateChartLayout(), abyste získali skutečnou hodnotu.

**Vrací:**
double
### getActualMinValue() {#getActualMinValue--}
```
public final double getActualMinValue()
```

Určuje skutečnou minimální hodnotu na ose. Předtím zavolejte metodu IChart.ValidateChartLayout(), abyste získali skutečnou hodnotu.

**Vrací:**
double
### getActualMajorUnit() {#getActualMajorUnit--}
```
public final double getActualMajorUnit()
```

Určuje skutečnou hlavní jednotku osy. Předtím zavolejte metodu IChart.ValidateChartLayout(), abyste získali skutečnou hodnotu.

**Vrací:**
double
### getActualMinorUnit() {#getActualMinorUnit--}
```
public final double getActualMinorUnit()
```

Určuje skutečnou vedlejší jednotku osy. Předtím zavolejte metodu IChart.ValidateChartLayout(), abyste získali skutečnou hodnotu.

**Vrací:**
double
### getActualMajorUnitScale() {#getActualMajorUnitScale--}
```
public final int getActualMajorUnitScale()
```

Určuje skutečné měřítko hlavní jednotky osy. Předtím zavolejte metodu IChart.ValidateChartLayout(), abyste získali skutečnou hodnotu.

**Vrací:**
int
### getActualMinorUnitScale() {#getActualMinorUnitScale--}
```
public final int getActualMinorUnitScale()
```

Určuje skutečné měřítko vedlejší jednotky osy. Předtím zavolejte metodu IChart.ValidateChartLayout(), abyste získali skutečnou hodnotu.

**Vrací:**
int
### isAutomaticMaxValue() {#isAutomaticMaxValue--}
```
public final boolean isAutomaticMaxValue()
```

Indikuje, zda je maximální hodnota přiřazena automaticky. Čtení/zápis boolean.

**Vrací:**
boolean
### setAutomaticMaxValue(boolean value) {#setAutomaticMaxValue-boolean-}
```
public final void setAutomaticMaxValue(boolean value)
```

Indikuje, zda je maximální hodnota přiřazena automaticky. Čtení/zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |
### getMaxValue() {#getMaxValue--}
```
public final double getMaxValue()
```

Zobrazuje maximální hodnotu na ose hodnot. Čtení/zápis double.

**Vrací:**
double
### setMaxValue(double value) {#setMaxValue-double-}
```
public final void setMaxValue(double value)
```

Zobrazuje maximální hodnotu na ose hodnot. Čtení/zápis double.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |
### getMinorUnit() {#getMinorUnit--}
```
public final double getMinorUnit()
```

Zobrazuje vedlejší jednotky pro datum nebo osu hodnot. Čtení/zápis double.

**Vrací:**
double
### setMinorUnit(double value) {#setMinorUnit-double-}
```
public final void setMinorUnit(double value)
```

Zobrazuje vedlejší jednotky pro datum nebo osu hodnot. Čtení/zápis double.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |
### isAutomaticMinorUnit() {#isAutomaticMinorUnit--}
```
public final boolean isAutomaticMinorUnit()
```
Indicates whether the minor unit of the axis is automatically assigned. Čtení/zápis boolean.

**Návratová hodnota:**
boolean
### setAutomaticMinorUnit(boolean value) {#setAutomaticMinorUnit-boolean-}
```
public final void setAutomaticMinorUnit(boolean value)
```


Indicates whether the minor unit of the axis is automatically assigned. Čtení/zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getMajorUnit() {#getMajorUnit--}
```
public final double getMajorUnit()
```


Represents the major units for the date or value axis. Čtení/zápis double.

**Návratová hodnota:**
double
### setMajorUnit(double value) {#setMajorUnit-double-}
```
public final void setMajorUnit(double value)
```


Represents the major units for the date or value axis. Čtení/zápis double.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |

### isAutomaticMajorUnit() {#isAutomaticMajorUnit--}
```
public final boolean isAutomaticMajorUnit()
```


Indicates whether the major unit of the axis is automatically assigned. Čtení/zápis boolean.

**Návratová hodnota:**
boolean
### setAutomaticMajorUnit(boolean value) {#setAutomaticMajorUnit-boolean-}
```
public final void setAutomaticMajorUnit(boolean value)
```


Indicates whether the major unit of the axis is automatically assigned. Čtení/zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticMinValue() {#isAutomaticMinValue--}
```
public final boolean isAutomaticMinValue()
```


Indicates whether the min value is automatically assigned. Čtení/zápis boolean.

**Návratová hodnota:**
boolean
### setAutomaticMinValue(boolean value) {#setAutomaticMinValue-boolean-}
```
public final void setAutomaticMinValue(boolean value)
```


Indicates whether the min value is automatically assigned. Čtení/zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getMinValue() {#getMinValue--}
```
public final double getMinValue()
```


Represents the minimum value on the value axis. Čtení/zápis double.

**Návratová hodnota:**
double
### setMinValue(double value) {#setMinValue-double-}
```
public final void setMinValue(double value)
```


Represents the minimum value on the value axis. Čtení/zápis double.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |

### isLogarithmic() {#isLogarithmic--}
```
public final boolean isLogarithmic()
```


Represents if the value axis scale type is logarithmic or not. Čtení/zápis boolean.

**Návratová hodnota:**
boolean
### setLogarithmic(boolean value) {#setLogarithmic-boolean-}
```
public final void setLogarithmic(boolean value)
```


Represents if the value axis scale type is logarithmic or not. Čtení/zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getLogBase() {#getLogBase--}
```
public final double getLogBase()
```


Represents the logarithmic base. Default value is 10. Čtení/zápis double.

**Návratová hodnota:**
double
### setLogBase(double value) {#setLogBase-double-}
```
public final void setLogBase(double value)
```


Represents the logarithmic base. Default value is 10. Čtení/zápis double.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |

### isPlotOrderReversed() {#isPlotOrderReversed--}
```
public final boolean isPlotOrderReversed()
```


Represents if MS PowerPoint plots data points from last to first. Čtení/zápis boolean.

**Návratová hodnota:**
boolean
### setPlotOrderReversed(boolean value) {#setPlotOrderReversed-boolean-}
```
public final void setPlotOrderReversed(boolean value)
```


Represents if MS PowerPoint plots data points from last to first. Čtení/zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### isVisible() {#isVisible--}
```
public final boolean isVisible()
```


Represents if the axis is visible. Čtení/zápis boolean.

**Návratová hodnota:**
boolean
### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```


Represents if the axis is visible. Čtení/zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getMajorTickMark() {#getMajorTickMark--}
```
public final int getMajorTickMark()
```


Represents the type of major tick mark for the specified axis. Čtení/zápis [TickMarkType](../../com.aspose.slides/tickmarktype).

**Návratová hodnota:**
int
### setMajorTickMark(int value) {#setMajorTickMark-int-}
```
public final void setMajorTickMark(int value)
```


Represents the type of major tick mark for the specified axis. Čtení/zápis [TickMarkType](../../com.aspose.slides/tickmarktype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getMinorTickMark() {#getMinorTickMark--}
```
public final int getMinorTickMark()
```


Represents the type of minor tick mark for the specified axis. Čtení/zápis [TickMarkType](../../com.aspose.slides/tickmarktype).

**Návratová hodnota:**
int
### setMinorTickMark(int value) {#setMinorTickMark-int-}
```
public final void setMinorTickMark(int value)
```


Represents the type of minor tick mark for the specified axis. Čtení/zápis [TickMarkType](../../com.aspose.slides/tickmarktype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getTickLabelPosition() {#getTickLabelPosition--}
```
public final int getTickLabelPosition()
```


Represents the position of tick-mark labels on the specified axis. Čtení/zápis [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**Návratová hodnota:**
int
### setTickLabelPosition(int value) {#setTickLabelPosition-int-}
```
public final void setTickLabelPosition(int value)
```


Represents the position of tick-mark labels on the specified axis. Čtení/zápis [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getMajorUnitScale() {#getMajorUnitScale--}
```
public final int getMajorUnitScale()
```


Represents the major unit scale for the date axis. Čtení/zápis [TimeUnitType](../../com.aspose.slides/timeunittype).

**Návratová hodnota:**
int
### setMajorUnitScale(int value) {#setMajorUnitScale-int-}
```
public final void setMajorUnitScale(int value)
```


Represents the major unit scale for the date axis. Čtení/zápis [TimeUnitType](../../com.aspose.slides/timeunittype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getMinorUnitScale() {#getMinorUnitScale--}
```
public final int getMinorUnitScale()
```


Represents the major unit scale for the date axis. Čtení/zápis [TimeUnitType](../../com.aspose.slides/timeunittype).

**Návratová hodnota:**
int
### setMinorUnitScale(int value) {#setMinorUnitScale-int-}
```
public final void setMinorUnitScale(int value)
```


Represents the major unit scale for the date axis. Čtení/zápis [TimeUnitType](../../com.aspose.slides/timeunittype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getBaseUnitScale() {#getBaseUnitScale--}
```
public final int getBaseUnitScale()
```


Specifies the smallest time unit that is represented on the date axis. Čtení/zápis [TimeUnitType](../../com.aspose.slides/timeunittype).

**Návratová hodnota:**
int
### setBaseUnitScale(int value) {#setBaseUnitScale-int-}
```
public final void setBaseUnitScale(int value)
```


Specifies the smallest time unit that is represented on the date axis. Čtení/zápis [TimeUnitType](../../com.aspose.slides/timeunittype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getMinorGridLinesFormat() {#getMinorGridLinesFormat--}
```
public final IChartLinesFormat getMinorGridLinesFormat()
```


Represents minor gridlines format on a chart axis. Pouze ke čtení [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**Návratová hodnota:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### getMajorGridLinesFormat() {#getMajorGridLinesFormat--}
```
public final IChartLinesFormat getMinorGridLinesFormat()
```


Represents major gridlines format on a chart axis. Pouze ke čtení [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**Návratová hodnota:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### getShowMinorGridLines() {#getShowMinorGridLines--}
```
public final boolean getShowMinorGridLines()
```


To hide minor gridline set MinorGridLinesFormat.Line.FillFormat.FillType to FillType.NoFill. Pouze ke čtení boolean.

**Návratová hodnota:**
boolean
### getShowMajorGridLines() {#getShowMajorGridLines--}
```
public final boolean getShowMajorGridLines()
```


To hide major gridline set MajorGridLinesFormat.Line.FillFormat.FillType to FillType.NoFill. Pouze ke čtení boolean.

**Návratová hodnota:**
boolean
### getFormat() {#getFormat--}
```
public final IAxisFormat getFormat()
```


Represents format of axis. Pouze ke čtení [IAxisFormat](../../com.aspose.slides/iaxisformat).

**Návratová hodnota:**
[IAxisFormat](../../com.aspose.slides/iaxisformat)
### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```


Represents format of text. Pouze ke čtení [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Návratová hodnota:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### getTitle() {#getTitle--}
```
public final IChartTitle getTitle()
```


Gets the axis' title. Pouze ke čtení [IChartTitle](../../com.aspose.slides/icharttitle).

**Návratová hodnota:**
[IChartTitle](../../com.aspose.slides/icharttitle)
### getCrossType() {#getCrossType--}
```
public final int getCrossType()
```


Represents the CrossType on the specified axis where the other axis crosses. Čtení/zápis [CrossesType](../../com.aspose.slides/crossestype).

**Návratová hodnota:**
int
### setCrossType(int value) {#setCrossType-int-}
```
public final void setCrossType(int value)
```


Represents the CrossType on the specified axis where the other axis crosses. Čtení/zápis [CrossesType](../../com.aspose.slides/crossestype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getPosition() {#getPosition--}
```
public final int getPosition()
```


Represents position of axis. Čtení/zápis [AxisPositionType](../../com.aspose.slides/axispositiontype).

**Návratová hodnota:**
int
### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```


Represents position of axis. Čtení/zápis [AxisPositionType](../../com.aspose.slides/axispositiontype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### hasTitle() {#hasTitle--}
```
public final boolean hasTitle()
```


Determines whether a axis has a visible title. Čtení/zápis boolean.

**Návratová hodnota:**
boolean
### setTitle(boolean value) {#setTitle-boolean-}
```
public final void setTitle(boolean value)
```


Determines whether a axis has a visible title. Čtení/zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public final String getNumberFormat()
```


Represents the format string for the Axis Labels. Čtení/zápis String.

**Návratová hodnota:**
java.lang.String
### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public final String getNumberFormat()
```


Represents the format string for the Axis Labels. Čtení/zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public final boolean isNumberFormatLinkedToSource()
```


Indicates whether the format is linked source data. Čtení/zápis boolean.

**Návratová hodnota:**
boolean
### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public final void setNumberFormatLinkedToSource(boolean value)
```


Indicates whether the format is linked source data. Čtení/zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getTickLabelRotationAngle() {#getTickLabelRotationAngle--}
```
public final float getTickLabelRotationAngle()
```


Represents the rotation angle of tick labels. Čtení/zápis float.

**Návratová hodnota:**
float
### setTickLabelRotationAngle(float value) {#setTickLabelRotationAngle-float-}
```
public final void setTickLabelRotationAngle(float value)
```


Represents the rotation angle of tick labels. Čtení/zápis float.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |

### getTickLabelSpacing() {#getTickLabelSpacing--}
```
public final long getTickLabelSpacing()
```


Specifies how many tick labels to skip between label that is drawn. Applied to category or series axis. Čtení/zápis long.

**Návratová hodnota:**
long
### setTickLabelSpacing(long value) {#setTickLabelSpacing-long-}
```
public final void setTickLabelSpacing(long value)
```


Specifies how many tick labels to skip between label that is drawn. Applied to category or series axis. Čtení/zápis long.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickLabelSpacing() {#isAutomaticTickLabelSpacing--}
```
public final boolean isAutomaticTickLabelSpacing()
```


Specifies automatic tick label spacing value. If false: use TickLabelSpacing property. Čtení/zápis boolean.

**Návratová hodnota:**
boolean
### setAutomaticTickLabelSpacing(boolean value) {#setAutomaticTickLabelSpacing-boolean-}
```
public final void setAutomaticTickLabelSpacing(boolean value)
```


Specifies automatic tick label spacing value. If false: use TickLabelSpacing property. Čtení/zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getTickMarksSpacing() {#getTickMarksSpacing--}
```
public final long getTickMarksSpacing()
```


Specifies how many tick marks shall be skipped before the next one shall be drawn. Applied to category or series axis. Čtení/zápis int.

**Návratová hodnota:**
long
### setTickMarksSpacing(long value) {#setTickMarksSpacing-long-}
```
public final void setTickMarksSpacing(long value)
```


Specifies how many tick marks shall be skipped before the next one shall be drawn. Applied to category or series axis. Čtení/zápis int.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickMarksSpacing() {#isAutomaticTickMarksSpacing--}
```
public final boolean isAutomaticTickMarksSpacing()
```


Specifies automatic tick marks spacing value. If false: use TickMarksSpacing property. Čtení/zápis boolean.

**Návratová hodnota:**
boolean
### setAutomaticTickMarksSpacing(boolean value) {#setAutomaticTickMarksSpacing-boolean-}
```
public final void setAutomaticTickMarksSpacing(boolean value)
```


Specifies automatic tick marks spacing value. If false: use TickMarksSpacing property. Čtení/zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getLabelOffset() {#getLabelOffset--}
```
public final int getLabelOffset()
```


Specifies the distance of labels from the axis. Applied to category or date axis. Value must be between 0% and 1000%. Čtení/zápis int.

**Návratová hodnota:**
int
### setLabelOffset(int value) {#setLabelOffset-int-}
```
public final void setLabelOffset(int value)
```


Specifies the distance of labels from the axis. Applied to category or date axis. Value must be between 0% and 1000%. Čtení/zápis int.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |
### getAggregationType() {#getAggregationType--}
```
public final int getAggregationType()
```

Představuje typ agregace osy kategorie (seskupování). Použito pro kategorii. Použito pouze se sériemi Histogram nebo HistogramPareto.

**Vrací:**
int
### setAggregationType(int value) {#setAggregationType-int-}
```
public final void setAggregationType(int value)
```

Představuje typ agregace osy kategorie (seskupování). Použito pro kategorii. Použito pouze se sériemi Histogram nebo HistogramPareto.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |
### getBinWidth() {#getBinWidth--}
```
public final double getBinWidth()
```

Určuje šířku koše, když je hodnota vlastnosti AggregationType nastavena na AxisAggregationType.ByBinWidth. Použito pro osy kategorií. Použito pouze se sériemi Histogram nebo HistogramPareto.

**Vrací:**
double
### setBinWidth(double value) {#setBinWidth-double-}
```
public final void setBinWidth(double value)
```

Určuje šířku koše, když je hodnota vlastnosti AggregationType nastavena na AxisAggregationType.ByBinWidth. Použito pro osy kategorií. Použito pouze se sériemi Histogram nebo HistogramPareto.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |
### getNumberOfBins() {#getNumberOfBins--}
```
public final long getNumberOfBins()
```

Určuje počet košů, když je hodnota vlastnosti AggregationType nastavena na AxisAggregationType.ByNumberOfBins. Použito pro osy kategorií. Použito pouze se sériemi Histogram nebo HistogramPareto.

**Vrací:**
long
### setNumberOfBins(long value) {#setNumberOfBins-long-}
```
public final void setNumberOfBins(long value)
```

Určuje počet košů, když je hodnota vlastnosti AggregationType nastavena na AxisAggregationType.ByNumberOfBins. Použito pro osy kategorií. Použito pouze se sériemi Histogram nebo HistogramPareto.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | long |  |
### isOverflowBin() {#isOverflowBin--}
```
public final boolean isOverflowBin()
```

Určuje, zda je použita přeplňovací koš. Použijte IsAutomaticOverflowBin a OverflowBin k úpravě hodnoty přeplňovacího koše.

**Vrací:**
boolean
### setOverflowBin(boolean value) {#setOverflowBin-boolean-}
```
public final void setOverflowBin(boolean value)
```

Určuje, zda je použita přeplňovací koš. Použijte IsAutomaticOverflowBin a OverflowBin k úpravě hodnoty přeplňovacího koše.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |
### isAutomaticOverflowBin() {#isAutomaticOverflowBin--}
```
public final boolean isAutomaticOverflowBin()
```

Určuje automatickou hodnotu přeplňovacího koše. Pokud je false: použijte vlastnost OverflowBin.

**Vrací:**
boolean
### setAutomaticOverflowBin(boolean value) {#setAutomaticOverflowBin-boolean-}
```
public final void setAutomaticOverflowBin(boolean value)
```

Určuje automatickou hodnotu přeplňovacího koše. Pokud je false: použijte vlastnost OverflowBin.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |
### getOverflowBin() {#getOverflowBin--}
```
public final double getOverflowBin()
```

Určuje vlastní hodnotu přeplňovacího koše. Použito, když je vlastnost IsAutomaticOverflowBin nastavena na false a vlastnost IsOverflowBin je true.

**Vrací:**
double
### setOverflowBin(double value) {#setOverflowBin-double-}
```
public final void setOverflowBin(double value)
```

Určuje vlastní hodnotu přeplňovacího koše. Použito, když je vlastnost IsAutomaticOverflowBin nastavena na false a vlastnost IsOverflowBin je true.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |
### isUnderflowBin() {#isUnderflowBin--}
```
public final boolean isUnderflowBin()
```

Určuje, zda je použita podplňovací koš. Použijte IsAutomaticUnderflowBin a UnderflowBin k úpravě hodnoty podplňovacího koše.

**Vrací:**
boolean
### setUnderflowBin(boolean value) {#setUnderflowBin-boolean-}
```
public final void setUnderflowBin(boolean value)
```

Určuje, zda je použita podplňovací koš. Použijte IsAutomaticUnderflowBin a UnderflowBin k úpravě hodnoty podplňovacího koše.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |
### isAutomaticUnderflowBin() {#isAutomaticUnderflowBin--}
```
public final boolean isAutomaticUnderflowBin()
```

Určuje automatickou hodnotu podplňovacího koše. Pokud je false: použijte vlastnost UnderflowBin.

**Vrací:**
boolean
### setAutomaticUnderflowBin(boolean value) {#setAutomaticUnderflowBin-boolean-}
```
public final void setAutomaticUnderflowBin(boolean value)
```

Určuje automatickou hodnotu podplňovacího koše. Pokud je false: použijte vlastnost UnderflowBin.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |
### getUnderflowBin() {#getUnderflowBin--}
```
public final double getUnderflowBin()
```

Určuje vlastní hodnotu podplňovacího koše. Použito, když je vlastnost IsAutomaticUnderflowBin nastavena na false a vlastnost IsUnderflowBin je true.

**Vrací:**
double
### setUnderflowBin(double value) {#setUnderflowBin-double-}
```
public final void setUnderflowBin(double value)
```

Určuje vlastní hodnotu podplňovacího koše. Použito, když je vlastnost IsAutomaticUnderflowBin nastavena na false a vlastnost IsUnderflowBin je true.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Vrací nadřazený snímek objektu FillFormat. Pouze pro čtení [BaseSlide](../../com.aspose.slides/baseslide).

**Vrací:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Vrací nadřazenou prezentaci objektu FillFormat. Pouze pro čtení [IPresentation](../../com.aspose.slides/ipresentation).

**Vrací:**
[IPresentation](../../com.aspose.slides/ipresentation)