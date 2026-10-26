---
title: Axis
second_title: Aspose.Slides pro Android přes Java API Reference
description: Zapouzdřuje objekt, který představuje osu diagramu.
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

Zapouzdřuje objekt, který představuje osu diagramu.
## Metody

| Metoda | Popis |
| --- | --- |
| [getChart()](#getChart--) | Vrací nadřazený diagram. |
| [getAxisBetweenCategories()](#getAxisBetweenCategories--) | Udává, zda osa hodnot protíná osu kategorií mezi kategoriemi. |
| [setAxisBetweenCategories(boolean value)](#setAxisBetweenCategories-boolean-) | Udává, zda osa hodnot protíná osu kategorií mezi kategoriemi. |
| [getCategoryAxisType()](#getCategoryAxisType--) | Určuje typ osy kategorií. |
| [setCategoryAxisType(int value)](#setCategoryAxisType-int-) | Určuje typ osy kategorií. |
| [setCategoryAxisTypeAutomatically()](#setCategoryAxisTypeAutomatically--) | Nastavuje vlastnost IAxis.CategoryAxisType na hodnotu, která je automaticky určena na základě dat osy. |
| [getCrossAt()](#getCrossAt--) | Udává bod na ose, kde ji protichůdná osa protíná. |
| [setCrossAt(float value)](#setCrossAt-float-) | Udává bod na ose, kde ji protichůdná osa protíná. |
| [getDisplayUnit()](#getDisplayUnit--) | Určuje měřítko zobrazovacích jednotek pro osu hodnot. |
| [setDisplayUnit(int value)](#setDisplayUnit-int-) | Určuje měřítko zobrazovacích jednotek pro osu hodnot. |
| [getActualMaxValue()](#getActualMaxValue--) | Určuje skutečnou maximální hodnotu na ose. |
| [getActualMinValue()](#getActualMinValue--) | Určuje skutečnou minimální hodnotu na ose. |
| [getActualMajorUnit()](#getActualMajorUnit--) | Určuje skutečnou hlavní jednotku osy. |
| [getActualMinorUnit()](#getActualMinorUnit--) | Určuje skutečnou vedlejší jednotku osy. |
| [getActualMajorUnitScale()](#getActualMajorUnitScale--) | Určuje skutečné měřítko hlavní jednotky osy. |
| [getActualMinorUnitScale()](#getActualMinorUnitScale--) | Určuje skutečné měřítko vedlejší jednotky osy. |
| [isAutomaticMaxValue()](#isAutomaticMaxValue--) | Udává, zda je maximální hodnota přiřazena automaticky. |
| [setAutomaticMaxValue(boolean value)](#setAutomaticMaxValue-boolean-) | Udává, zda je maximální hodnota přiřazena automaticky. |
| [getMaxValue()](#getMaxValue--) | Udává maximální hodnotu na ose hodnot. |
| [setMaxValue(double value)](#setMaxValue-double-) | Udává maximální hodnotu na ose hodnot. |
| [getMinorUnit()](#getMinorUnit--) | Udává vedlejší jednotky pro datumovou nebo hodnotovou osu. |
| [setMinorUnit(double value)](#setMinorUnit-double-) | Udává vedlejší jednotky pro datumovou nebo hodnotovou osu. |
| [isAutomaticMinorUnit()](#isAutomaticMinorUnit--) | Udává, zda je vedlejší jednotka osy přiřazena automaticky. |
| [setAutomaticMinorUnit(boolean value)](#setAutomaticMinorUnit-boolean-) | Udává, zda je vedlejší jednotka osy přiřazena automaticky. |
| [getMajorUnit()](#getMajorUnit--) | Udává hlavní jednotky pro datumovou nebo hodnotovou osu. |
| [setMajorUnit(double value)](#setMajorUnit-double-) | Udává hlavní jednotky pro datumovou nebo hodnotovou osu. |
| [isAutomaticMajorUnit()](#isAutomaticMajorUnit--) | Udává, zda je hlavní jednotka osy přiřazena automaticky. |
| [setAutomaticMajorUnit(boolean value)](#setAutomaticMajorUnit-boolean-) | Udává, zda je hlavní jednotka osy přiřazena automaticky. |
| [isAutomaticMinValue()](#isAutomaticMinValue--) | Udává, zda je minimální hodnota přiřazena automaticky. |
| [setAutomaticMinValue(boolean value)](#setAutomaticMinValue-boolean-) | Udává, zda je minimální hodnota přiřazena automaticky. |
| [getMinValue()](#getMinValue--) | Udává minimální hodnotu na ose hodnot. |
| [setMinValue(double value)](#setMinValue-double-) | Udává minimální hodnotu na ose hodnot. |
| [isLogarithmic()](#isLogarithmic--) | Udává, zda je typ měřítka osy hodnot logaritmický. |
| [setLogarithmic(boolean value)](#setLogarithmic-boolean-) | Udává, zda je typ měřítka osy hodnot logaritmický. |
| [getLogBase()](#getLogBase--) | Udává logaritmickou základnu. |
| [setLogBase(double value)](#setLogBase-double-) | Udává logaritmickou základnu. |
| [isPlotOrderReversed()](#isPlotOrderReversed--) | Udává, zda MS PowerPoint vykresluje datové body od posledního po první. |
| [setPlotOrderReversed(boolean value)](#setPlotOrderReversed-boolean-) | Udává, zda MS PowerPoint vykresluje datové body od posledního po první. |
| [isVisible()](#isVisible--) | Udává, zda je osa viditelná. |
| [setVisible(boolean value)](#setVisible-boolean-) | Udává, zda je osa viditelná. |
| [getMajorTickMark()](#getMajorTickMark--) | Udává typ hlavního značkovacího znaku pro zadanou osu. |
| [setMajorTickMark(int value)](#setMajorTickMark-int-) | Udává typ hlavního značkovacího znaku pro zadanou osu. |
| [getMinorTickMark()](#getMinorTickMark--) | Udává typ vedlejšího značkovacího znaku pro zadanou osu. |
| [setMinorTickMark(int value)](#setMinorTickMark-int-) | Udává typ vedlejšího značkovacího znaku pro zadanou osu. |
| [getTickLabelPosition()](#getTickLabelPosition--) | Udává polohu popisků značek na zadané ose. |
| [setTickLabelPosition(int value)](#setTickLabelPosition-int-) | Udává polohu popisků značek na zadané ose. |
| [getMajorUnitScale()](#getMajorUnitScale--) | Udává hlavní měřítko jednotky pro datumovou osu. |
| [setMajorUnitScale(int value)](#setMajorUnitScale-int-) | Udává hlavní měřítko jednotky pro datumovou osu. |
| [getMinorUnitScale()](#getMinorUnitScale--) | Udává hlavní měřítko jednotky pro datumovou osu. |
| [setMinorUnitScale(int value)](#setMinorUnitScale-int-) | Udává hlavní měřítko jednotky pro datumovou osu. |
| [getBaseUnitScale()](#getBaseUnitScale--) | Určuje nejmenší časovou jednotku zobrazenou na datumové ose. |
| [setBaseUnitScale(int value)](#setBaseUnitScale-int-) | Určuje nejmenší časovou jednotku zobrazenou na datumové ose. |
| [getMinorGridLinesFormat()](#getMinorGridLinesFormat--) | Udává formát vedlejších mřížek na ose diagramu. |
| [getMajorGridLinesFormat()](#getMajorGridLinesFormat--) | Udává formát hlavních mřížek na ose diagramu. |
| [getShowMinorGridLines()](#getShowMinorGridLines--) | Pro skrytí vedlejší mřížky nastavte MinorGridLinesFormat.Line.FillFormat.FillType na FillType.NoFill. |
| [getShowMajorGridLines()](#getShowMajorGridLines--) | Pro skrytí hlavní mřížky nastavte MajorGridLinesFormat.Line.FillFormat.FillType na FillType.NoFill. |
| [getFormat()](#getFormat--) | Udává formát osy. |
| [getTextFormat()](#getTextFormat--) | Udává formát textu. |
| [getTitle()](#getTitle--) | Získává název osy. |
| [getCrossType()](#getCrossType--) | Udává typ průniku (CrossType) na zadané ose, kde se kříží s další osou. |
| [setCrossType(int value)](#setCrossType-int-) | Udává typ průniku (CrossType) na zadané ose, kde se kříží s další osou. |
| [getPosition()](#getPosition--) | Udává polohu osy. |
| [setPosition(int value)](#setPosition-int-) | Udává polohu osy. |
| [hasTitle()](#hasTitle--) | Určuje, zda má osa viditelný název. |
| [setTitle(boolean value)](#setTitle-boolean-) | Určuje, zda má osa viditelný název. |
| [getNumberFormat()](#getNumberFormat--) | Udává formátovací řetězec pro popisky osy. |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | Udává formátovací řetězec pro popisky osy. |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | Udává, zda je formát propojen se zdrojovými daty. |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | Udává, zda je formát propojen se zdrojovými daty. |
| [getTickLabelRotationAngle()](#getTickLabelRotationAngle--) | Udává úhel otáčení popisků značek. |
| [setTickLabelRotationAngle(float value)](#setTickLabelRotationAngle-float-) | Udává úhel otáčení popisků značek. |
| [getTickLabelSpacing()](#getTickLabelSpacing--) | Určuje, kolik popisků značek přeskočit mezi vykreslenými popisky. |
| [setTickLabelSpacing(long value)](#setTickLabelSpacing-long-) | Určuje, kolik popisků značek přeskočit mezi vykreslenými popisky. |
| [isAutomaticTickLabelSpacing()](#isAutomaticTickLabelSpacing--) | Určuje automatickou hodnotu rozestupu popisků značek. |
| [setAutomaticTickLabelSpacing(boolean value)](#setAutomaticTickLabelSpacing-boolean-) | Určuje automatickou hodnotu rozestupu popisků značek. |
| [getTickMarksSpacing()](#getTickMarksSpacing--) | Určuje, kolik značek má být přeskočeno před vykreslením další. |
| [setTickMarksSpacing(long value)](#setTickMarksSpacing-long-) | Určuje, kolik značek má být přeskočeno před vykreslením další. |
| [isAutomaticTickMarksSpacing()](#isAutomaticTickMarksSpacing--) | Určuje automatickou hodnotu rozestupu značek. |
| [setAutomaticTickMarksSpacing(boolean value)](#setAutomaticTickMarksSpacing-boolean-) | Určuje automatickou hodnotu rozestupu značek. |
| [getLabelOffset()](#getLabelOffset--) | Určuje vzdálenost popisků od osy. |
| [setLabelOffset(int value)](#setLabelOffset-int-) | Určuje vzdálenost popisků od osy. |
| [getAggregationType()](#getAggregationType--) | Udává typ agregace osy kategorií (skupinování). |
| [setAggregationType(int value)](#setAggregationType-int-) | Udává typ agregace osy kategorií (skupinování). |
| [getBinWidth()](#getBinWidth--) | Určuje šířku binu, když je vlastnost AggregationType nastavena na AxisAggregationType.ByBinWidth. |
| [setBinWidth(double value)](#setBinWidth-double-) | Určuje šířku binu, když je vlastnost AggregationType nastavena na AxisAggregationType.ByBinWidth. |
| [getNumberOfBins()](#getNumberOfBins--) | Určuje počet binů, když je vlastnost AggregationType nastavena na AxisAggregationType.ByNumberOfBins. |
| [setNumberOfBins(long value)](#setNumberOfBins-long-) | Určuje počet binů, když je vlastnost AggregationType nastavena na AxisAggregationType.ByNumberOfBins. |
| [isOverflowBin()](#isOverflowBin--) | Udává, zda je použit overflow bin. |
| [setOverflowBin(boolean value)](#setOverflowBin-boolean-) | Udává, zda je použit overflow bin. |
| [isAutomaticOverflowBin()](#isAutomaticOverflowBin--) | Určuje automatickou hodnotu overflow binu. |
| [setAutomaticOverflowBin(boolean value)](#setAutomaticOverflowBin-boolean-) | Určuje automatickou hodnotu overflow binu. |
| [getOverflowBin()](#getOverflowBin--) | Udává vlastní hodnotu overflow binu. |
| [setOverflowBin(double value)](#setOverflowBin-double-) | Udává vlastní hodnotu overflow binu. |
| [isUnderflowBin()](#isUnderflowBin--) | Udává, zda je použit underflow bin. |
| [setUnderflowBin(boolean value)](#setUnderflowBin-boolean-) | Udává, zda je použit underflow bin. |
| [isAutomaticUnderflowBin()](#isAutomaticUnderflowBin--) | Určuje automatickou hodnotu underflow binu. |
| [setAutomaticUnderflowBin(boolean value)](#setAutomaticUnderflowBin-boolean-) | Určuje automatickou hodnotu underflow binu. |
| [getUnderflowBin()](#getUnderflowBin--) | Udává vlastní hodnotu underflow binu. |
| [setUnderflowBin(double value)](#setUnderflowBin-double-) | Udává vlastní hodnotu underflow binu. |
| [getSlide()](#getSlide--) | Vrací nadřazený snímek objektu FillFormat. |
| [getPresentation()](#getPresentation--) | Vrací nadřazenou prezentaci objektu FillFormat. |

### getChart() {#getChart--}
```
public final IChart getChart()
```

Vrací nadřazený diagram. Pouze pro čtení [IChart](../../com.aspose.slides/ichart).

**Vrací:**
[IChart](../../com.aspose.slides/ichart)

### getAxisBetweenCategories() {#getAxisBetweenCategories--}
```
public final boolean getAxisBetweenCategories()
```

Udává, zda osa hodnot protíná osu kategorií mezi kategoriemi. Tato vlastnost platí jen pro osy kategorií a nepoužívá se u 3-D diagramů. Čtení/zápis boolean.

**Vrací:**
boolean

### setAxisBetweenCategories(boolean value) {#setAxisBetweenCategories-boolean-}
```
public final void setAxisBetweenCategories(boolean value)
```

Udává, zda osa hodnot protíná osu kategorií mezi kategoriemi. Tato vlastnost platí jen pro osy kategorií a nepoužívá se u 3-D diagramů. Čtení/zápis boolean.

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

Nastavuje vlastnost IAxis.CategoryAxisType na hodnotu, která je automaticky určena na základě dat osy.

### getCrossAt() {#getCrossAt--}
```
public final float getCrossAt()
```

Udává bod na ose, kde ji protichůdná osa protíná. Čtení/zápis float.

**Vrací:**
float

### setCrossAt(float value) {#setCrossAt-float-}
```
public final void setCrossAt(float value)
```

Udává bod na ose, kde ji protichůdná osa protíná. Čtení/zápis float.

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

Určuje skutečnou maximální hodnotu na ose. Před voláním zavolejte metodu IChart.ValidateChartLayout(). 

**Vrací:**
double

### getActualMinValue() {#getActualMinValue--}
```
public final double getActualMinValue()
```

Určuje skutečnou minimální hodnotu na ose. Před voláním zavolejte metodu IChart.ValidateChartLayout(). 

**Vrací:**
double

### getActualMajorUnit() {#getActualMajorUnit--}
```
public final double getActualMajorUnit()
```

Určuje skutečnou hlavní jednotku osy. Před voláním zavolejte metodu IChart.ValidateChartLayout(). 

**Vrací:**
double

### getActualMinorUnit() {#getActualMinorUnit--}
```
public final double getActualMinorUnit()
```

Určuje skutečnou vedlejší jednotku osy. Před voláním zavolejte metodu IChart.ValidateChartLayout(). 

**Vrací:**
double

### getActualMajorUnitScale() {#getActualMajorUnitScale--}
```
public final int getActualMajorUnitScale()
```

Určuje skutečné měřítko hlavní jednotky osy. Před voláním zavolejte metodu IChart.ValidateChartLayout(). 

**Vrací:**
int

### getActualMinorUnitScale() {#getActualMinorUnitScale--}
```
public final int getActualMinorUnitScale()
```

Určuje skutečné měřítko vedlejší jednotky osy. Před voláním zavolejte metodu IChart.ValidateChartLayout(). 

**Vrací:**
int

### isAutomaticMaxValue() {#isAutomaticMaxValue--}
```
public final boolean isAutomaticMaxValue()
```

Udává, zda je maximální hodnota přiřazena automaticky. Čtení/zápis boolean.

**Vrací:**
boolean

### setAutomaticMaxValue(boolean value) {#setAutomaticMaxValue-boolean-}
```
public final void setAutomaticMaxValue(boolean value)
```

Udává, zda je maximální hodnota přiřazena automaticky. Čtení/zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getMaxValue() {#getMaxValue--}
```
public final double getMaxValue()
```

Udává maximální hodnotu na ose hodnot. Čtení/zápis double.

**Vrací:**
double

### setMaxValue(double value) {#setMaxValue-double-}
```
public final void setMaxValue(double value)
```

Udává maximální hodnotu na ose hodnot. Čtení/zápis double.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |

### getMinorUnit() {#getMinorUnit--}
```
public final double getMinorUnit()
```

Udává vedlejší jednotky pro datumovou nebo hodnotovou osu. Čtení/zápis double.

**Vrací:**
double

### setMinorUnit(double value) {#setMinorUnit-double-}
```
public final void setMinorUnit(double value)
```

Udává vedlejší jednotky pro datumovou nebo hodnotovou osu. Čtení/zápis double.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |

### isAutomaticMinorUnit() {#isAutomaticMinorUnit--}
```
public final boolean isAutomaticMinorUnit()
```

Udává, zda je vedlejší jednotka osy přiřazena automaticky. Čtení/zápis boolean.

**Vrací:**
boolean

### setAutomaticMinorUnit(boolean value) {#setAutomaticMinorUnit-boolean-}
```
public final void setAutomaticMinorUnit(boolean value)
```

Udává, zda je vedlejší jednotka osy přiřazena automaticky. Čtení/zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getMajorUnit() {#getMajorUnit--}
```
public final double getMajorUnit()
```

Udává hlavní jednotky pro datumovou nebo hodnotovou osu. Čtení/zápis double.

**Vrací:**
double

### setMajorUnit(double value) {#setMajorUnit-double-}
```
public final void setMajorUnit(double value)
```

Udává hlavní jednotky pro datumovou nebo hodnotovou osu. Čtení/zápis double.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |

### isAutomaticMajorUnit() {#isAutomaticMajorUnit--}
```
public final boolean isAutomaticMajorUnit()
```

Udává, zda je hlavní jednotka osy přiřazena automaticky. Čtení/zápis boolean.

**Vrací:**
boolean

### setAutomaticMajorUnit(boolean value) {#setAutomaticMajorUnit-boolean-}
```
public final void setAutomaticMajorUnit(boolean value)
```

Udává, zda je hlavní jednotka osy přiřazena automaticky. Čtení/zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticMinValue() {#isAutomaticMinValue--}
```
public final boolean isAutomaticMinValue()
```

Udává, zda je minimální hodnota přiřazena automaticky. Čtení/zápis boolean.

**Vrací:**
boolean

### setAutomaticMinValue(boolean value) {#setAutomaticMinValue-boolean-}
```
public final void setAutomaticMinValue(boolean value)
```

Udává, zda je minimální hodnota přiřazena automaticky. Čtení/zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getMinValue() {#getMinValue--}
```
public final double getMinValue()
```

Udává minimální hodnotu na ose hodnot. Čtení/zápis double.

**Vrací:**
double

### setMinValue(double value) {#setMinValue-double-}
```
public final void setMinValue(double value)
```

Udává minimální hodnotu na ose hodnot. Čtení/zápis double.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |

### isLogarithmic() {#isLogarithmic--}
```
public final boolean isLogarithmic()
```

Udává, zda je typ měřítka osy hodnot logaritmický. Čtení/zápis boolean.

**Vrací:**
boolean

### setLogarithmic(boolean value) {#setLogarithmic-boolean-}
```
public final void setLogarithmic(boolean value)
```

Udává, zda je typ měřítka osy hodnot logaritmický. Čtení/zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getLogBase() {#getLogBase--}
```
public final double getLogBase()
```

Udává logaritmickou základnu. Výchozí hodnota je 10. Čtení/zápis double.

**Vrací:**
double

### setLogBase(double value) {#setLogBase-double-}
```
public final void setLogBase(double value)
```

Udává logaritmickou základnu. Výchozí hodnota je 10. Čtení/zápis double.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |

### isPlotOrderReversed() {#isPlotOrderReversed--}
```
public final boolean isPlotOrderReversed()
```

Udává, zda MS PowerPoint vykresluje datové body od posledního po první. Čtení/zápis boolean.

**Vrací:**
boolean

### setPlotOrderReversed(boolean value) {#setPlotOrderReversed-boolean-}
```
public final void setPlotOrderReversed(boolean value)
```

Udává, zda MS PowerPoint vykresluje datové body od posledního po první. Čtení/zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

Udává, zda je osa viditelná. Čtení/zápis boolean.

**Vrací:**
boolean

### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```

Udává, zda je osa viditelná. Čtení/zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getMajorTickMark() {#getMajorTickMark--}
```
public final int getMajorTickMark()
```

Udává typ hlavního značkovacího znaku pro zadanou osu. Čtení/zápis [TickMarkType](../../com.aspose.slides/tickmarktype).

**Vrací:**
int

### setMajorTickMark(int value) {#setMajorTickMark-int-}
```
public final void setMajorTickMark(int value)
```

Udává typ hlavního značkovacího znaku pro zadanou osu. Čtení/zápis [TickMarkType](../../com.aspose.slides/tickmarktype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getMinorTickMark() {#getMinorTickMark--}
```
public final int getMinorTickMark()
```

Udává typ vedlejšího značkovacího znaku pro zadanou osu. Čtení/zápis [TickMarkType](../../com.aspose.slides/tickmarktype).

**Vrací:**
int

### setMinorTickMark(int value) {#setMinorTickMark-int-}
```
public final void setMinorTickMark(int value)
```

Udává typ vedlejšího značkovacího znaku pro zadanou osu. Čtení/zápis [TickMarkType](../../com.aspose.slides/tickmarktype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getTickLabelPosition() {#getTickLabelPosition--}
```
public final int getTickLabelPosition()
```

Udává polohu popisků značek na zadané ose. Čtení/zápis [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**Vrací:**
int

### setTickLabelPosition(int value) {#setTickLabelPosition-int-}
```
public final void setTickLabelPosition(int value)
```

Udává polohu popisků značek na zadané ose. Čtení/zápis [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getMajorUnitScale() {#getMajorUnitScale--}
```
public final int getMajorUnitScale()
```

Udává hlavní měřítko jednotky pro datumovou osu. Čtení/zápis [TimeUnitType](../../com.aspose.slides/timeunittype).

**Vrací:**
int

### setMajorUnitScale(int value) {#setMajorUnitScale-int-}
```
public final void setMajorUnitScale(int value)
```

Udává hlavní měřítko jednotky pro datumovou osu. Čtení/zápis [TimeUnitType](../../com.aspose.slides/timeunittype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getMinorUnitScale() {#getMinorUnitScale--}
```
public final int getMinorUnitScale()
```

Udává hlavní měřítko jednotky pro datumovou osu. Čtení/zápis [TimeUnitType](../../com.aspose.slides/timeunittype).

**Vrací:**
int

### setMinorUnitScale(int value) {#setMinorUnitScale-int-}
```
public final void setMinorUnitScale(int value)
```

Udává hlavní měřítko jednotky pro datumovou osu. Čtení/zápis [TimeUnitType](../../com.aspose.slides/timeunittype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getBaseUnitScale() {#getBaseUnitScale--}
```
public final int getBaseUnitScale()
```

Určuje nejmenší časovou jednotku zobrazenou na datumové ose. Čtení/zápis [TimeUnitType](../../com.aspose.slides/timeunittype).

**Vrací:**
int

### setBaseUnitScale(int value) {#setBaseUnitScale-int-}
```
public final void setBaseUnitScale(int value)
```

Určuje nejmenší časovou jednotku zobrazenou na datumové ose. Čtení/zápis [TimeUnitType](../../com.aspose.slides/timeunittype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getMinorGridLinesFormat() {#getMinorGridLinesFormat--}
```
public final IChartLinesFormat getMinorGridLinesFormat()
```

Udává formát vedlejších mřížek na ose diagramu. Pouze pro čtení [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**Vrací:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getMajorGridLinesFormat() {#getMajorGridLinesFormat--}
```
public final IChartLinesFormat getMajorGridLinesFormat()
```

Udává formát hlavních mřížek na ose diagramu. Pouze pro čtení [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**Vrací:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getShowMinorGridLines() {#getShowMinorGridLines--}
```
public final boolean getShowMinorGridLines()
```

Pro skrytí vedlejší mřížky nastavte MinorGridLinesFormat.Line.FillFormat.FillType na FillType.NoFill. Pouze pro čtení boolean.

**Vrací:**
boolean

### getShowMajorGridLines() {#getShowMajorGridLines--}
```
public final boolean getShowMajorGridLines()
```

Pro skrytí hlavní mřížky nastavte MajorGridLinesFormat.Line.FillFormat.FillType na FillType.NoFill. Pouze pro čtení boolean.

**Vrací:**
boolean

### getFormat() {#getFormat--}
```
public final IAxisFormat getFormat()
```

Udává formát osy. Pouze pro čtení [IAxisFormat](../../com.aspose.slides/iaxisformat).

**Vrací:**
[IAxisFormat](../../com.aspose.slides/iaxisformat)

### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

Udává formát textu. Pouze pro čtení [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Vrací:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)

### getTitle() {#getTitle--}
```
public final IChartTitle getTitle()
```

Získává název osy. Pouze pro čtení [IChartTitle](../../com.aspose.slides/icharttitle).

**Vrací:**
[IChartTitle](../../com.aspose.slides/icharttitle)

### getCrossType() {#getCrossType--}
```
public final int getCrossType()
```

Udává typ průniku (CrossType) na zadané ose, kde se kříží s další osou. Čtení/zápis [CrossesType](../../com.aspose.slides/crossestype).

**Vrací:**
int

### setCrossType(int value) {#setCrossType-int-}
```
public final void setCrossType(int value)
```

Udává typ průniku (CrossType) na zadané ose, kde se kříží s další osou. Čtení/zápis [CrossesType](../../com.aspose.slides/crossestype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getPosition() {#getPosition--}
```
public final int getPosition()
```

Udává polohu osy. Čtení/zápis [AxisPositionType](../../com.aspose.slides/axispositiontype).

**Vrací:**
int

### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```

Udává polohu osy. Čtení/zápis [AxisPositionType](../../com.aspose.slides/axispositiontype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### hasTitle() {#hasTitle--}
```
public final boolean hasTitle()
```

Určuje, zda má osa viditelný název. Čtení/zápis boolean.

**Vrací:**
boolean

### setTitle(boolean value) {#setTitle-boolean-}
```
public final void setTitle(boolean value)
```

Určuje, zda má osa viditelný název. Čtení/zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public final String getNumberFormat()
```

Udává formátovací řetězec pro popisky osy. Čtení/zápis String.

**Vrací:**
java.lang.String

### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public final void setNumberFormat(String value)
```

Udává formátovací řetězec pro popisky osy. Čtení/zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public final boolean isNumberFormatLinkedToSource()
```

Udává, zda je formát propojen se zdrojovými daty. Čtení/zápis boolean.

**Vrací:**
boolean

### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public final void setNumberFormatLinkedToSource(boolean value)
```

Udává, zda je formát propojen se zdrojovými daty. Čtení/zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getTickLabelRotationAngle() {#getTickLabelRotationAngle--}
```
public final float getTickLabelRotationAngle()
```

Udává úhel otáčení popisků značek. Čtení/zápis float.

**Vrací:**
float

### setTickLabelRotationAngle(float value) {#setTickLabelRotationAngle-float-}
```
public final void setTickLabelRotationAngle(float value)
```

Udává úhel otáčení popisků značek. Čtení/zápis float.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |

### getTickLabelSpacing() {#getTickLabelSpacing--}
```
public final long getTickLabelSpacing()
```

Určuje, kolik popisků značek přeskočit mezi vykreslenými popisky. Použitelné pro osu kategorií nebo sérií. Čtení/zápis long.

**Vrací:**
long

### setTickLabelSpacing(long value) {#setTickLabelSpacing-long-}
```
public final void setTickLabelSpacing(long value)
```

Určuje, kolik popisků značek přeskočit mezi vykreslenými popisky. Použitelné pro osu kategorií nebo sérií. Čtení/zápis long.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickLabelSpacing() {#isAutomaticTickLabelSpacing--}
```
public final boolean isAutomaticTickLabelSpacing()
```

Určuje automatickou hodnotu rozestupu popisků značek. Pokud false: použijte vlastnost TickLabelSpacing. Čtení/zápis boolean.

**Vrací:**
boolean

### setAutomaticTickLabelSpacing(boolean value) {#setAutomaticTickLabelSpacing-boolean-}
```
public final void setAutomaticTickLabelSpacing(boolean value)
```

Určuje automatickou hodnotu rozestupu popisků značek. Pokud false: použijte vlastnost TickLabelSpacing. Čtení/zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getTickMarksSpacing() {#getTickMarksSpacing--}
```
public final long getTickMarksSpacing()
```

Určuje, kolik značek má být přeskočeno před vykreslením další. Použitelné pro osu kategorií nebo sérií. Čtení/zápis int.

**Vrací:**
long

### setTickMarksSpacing(long value) {#setTickMarksSpacing-long-}
```
public final void setTickMarksSpacing(long value)
```

Určuje, kolik značek má být přeskočeno před vykreslením další. Použitelné pro osu kategorií nebo sérií. Čtení/zápis int.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickMarksSpacing() {#isAutomaticTickMarksSpacing--}
```
public final boolean isAutomaticTickMarksSpacing()
```

Určuje automatickou hodnotu rozestupu značek. Pokud false: použijte vlastnost TickMarksSpacing. Čtení/zápis boolean.

**Vrací:**
boolean

### setAutomaticTickMarksSpacing(boolean value) {#setAutomaticTickMarksSpacing-boolean-}
```
public final void setAutomaticTickMarksSpacing(boolean value)
```

Určuje automatickou hodnotu rozestupu značek. Pokud false: použijte vlastnost TickMarksSpacing. Čtení/zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getLabelOffset() {#getLabelOffset--}
```
public final int getLabelOffset()
```

Určuje vzdálenost popisků od osy. Použitelné pro osu kategorií nebo datumovou. Hodnota musí být mezi 0 % a 1000 %. Čtení/zápis int.

**Vrací:**
int

### setLabelOffset(int value) {#setLabelOffset-int-}
```
public final void setLabelOffset(int value)
```

Určuje vzdálenost popisků od osy. Použitelné pro osu kategorií nebo datumovou. Hodnota musí být mezi 0 % a 1000 %. Čtení/zápis int.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getAggregationType() {#getAggregationType--}
```
public final int getAggregationType()
```

Udává typ agregace osy kategorií (skupinování). Použitelné pro osu kategorií. Používá se jen se sériemi Histogram nebo HistogramPareto.

**Vrací:**
int

### setAggregationType(int value) {#setAggregationType-int-}
```
public final void setAggregationType(int value)
```

Udává typ agregace osy kategorií (skupinování). Použitelné pro osu kategorií. Používá se jen se sériemi Histogram nebo HistogramPareto.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getBinWidth() {#getBinWidth--}
```
public final double getBinWidth()
```

Určuje šířku binu, když je vlastnost AggregationType nastavena na AxisAggregationType.ByBinWidth. Použitelné pro osy kategorií. Používá se jen se sériemi Histogram nebo HistogramPareto.

**Vrací:**
double

### setBinWidth(double value) {#setBinWidth-double-}
```
public final void setBinWidth(double value)
```

Určuje šířku binu, když je vlastnost AggregationType nastavena na AxisAggregationType.ByBinWidth. Použitelné pro osy kategorií. Používá se jen se sériemi Histogram nebo HistogramPareto.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |

### getNumberOfBins() {#getNumberOfBins--}
```
public final long getNumberOfBins()
```

Určuje počet binů, když je vlastnost AggregationType nastavena na AxisAggregationType.ByNumberOfBins. Použitelné pro osy kategorií. Používá se jen se sériemi Histogram nebo HistogramPareto.

**Vrací:**
long

### setNumberOfBins(long value) {#setNumberOfBins-long-}
```
public final void setNumberOfBins(long value)
```

Určuje počet binů, když je vlastnost AggregationType nastavena na AxisAggregationType.ByNumberOfBins. Použitelné pro osy kategorií. Používá se jen se sériemi Histogram nebo HistogramPareto.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | long |  |

### isOverflowBin() {#isOverflowBin--}
```
public final boolean isOverflowBin()
```

Udává, zda je použit overflow bin. Použijte IsAutomaticOverflowBin a OverflowBin k úpravě hodnoty overflow binu.

**Vrací:**
boolean

### setOverflowBin(boolean value) {#setOverflowBin-boolean-}
```
public final void setOverflowBin(boolean value)
```

Udává, zda je použit overflow bin. Použijte IsAutomaticOverflowBin a OverflowBin k úpravě hodnoty overflow binu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticOverflowBin() {#isAutomaticOverflowBin--}
```
public final boolean isAutomaticOverflowBin()
```

Určuje automatickou hodnotu overflow binu. Pokud false: použijte vlastnost OverflowBin.

**Vrací:**
boolean

### setAutomaticOverflowBin(boolean value) {#setAutomaticOverflowBin-boolean-}
```
public final void setAutomaticOverflowBin(boolean value)
```

Určuje automatickou hodnotu overflow binu. Pokud false: použijte vlastnost OverflowBin.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getOverflowBin() {#getOverflowBin--}
```
public final double getOverflowBin()
```

Udává vlastní hodnotu overflow binu. Používá se, když je IsAutomaticOverflowBin nastaveno na false a IsOverflowBin je true.

**Vrací:**
double

### setOverflowBin(double value) {#setOverflowBin-double-}
```
public final void setOverflowBin(double value)
```

Udává vlastní hodnotu overflow binu. Používá se, když je IsAutomaticOverflowBin nastaveno na false a IsOverflowBin je true.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |

### isUnderflowBin() {#isUnderflowBin--}
```
public final boolean isUnderflowBin()
```

Udává, zda je použit underflow bin. Použijte IsAutomaticUnderflowBin a UnderflowBin k úpravě hodnoty underflow binu.

**Vrací:**
boolean

### setUnderflowBin(boolean value) {#setUnderflowBin-boolean-}
```
public final void setUnderflowBin(boolean value)
```

Udává, zda je použit underflow bin. Použijte IsAutomaticUnderflowBin a UnderflowBin k úpravě hodnoty underflow binu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticUnderflowBin() {#isAutomaticUnderflowBin--}
```
public final boolean isAutomaticUnderflowBin()
```

Určuje automatickou hodnotu underflow binu. Pokud false: použijte vlastnost UnderflowBin.

**Vrací:**
boolean

### setAutomaticUnderflowBin(boolean value) {#setAutomaticUnderflowBin-boolean-}
```
public final void setAutomaticUnderflowBin(boolean value)
```

Určuje automatickou hodnotu underflow binu. Pokud false: použijte vlastnost UnderflowBin.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getUnderflowBin() {#getUnderflowBin--}
```
public final double getUnderflowBin()
```

Udává vlastní hodnotu underflow binu. Používá se, když je IsAutomaticUnderflowBin nastaveno na false a IsUnderflowBin je true.

**Vrací:**
double

### setUnderflowBin(double value) {#setUnderflowBin-double-}
```
public final void setUnderflowBin(double value)
```

Udává vlastní hodnotu underflow binu. Používá se, když je IsAutomaticUnderflowBin nastaveno na false a IsUnderflowBin je true.

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