---  
title: IAxis  
second_title: Aspose.Slides pro Android prostřednictvím referenční příručky Java API  
description: Zapouzdřuje objekt, který představuje osu grafu.  
type: docs  
url: /cs/com.aspose.slides/iaxis/  
---
**Všechna implementovaná rozhraní:**
[com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer)
```
public interface IAxis extends IFormattedTextContainer
```

Zapouzdřuje objekt, který představuje osu grafu.
## Metody

| Metoda | Popis |
| --- | --- |
| [getAxisBetweenCategories()](#getAxisBetweenCategories--) | Představuje, zda osa hodnot protíná osu kategorií mezi kategoriemi. |
| [setAxisBetweenCategories(boolean value)](#setAxisBetweenCategories-boolean-) | Představuje, zda osa hodnot protíná osu kategorií mezi kategoriemi. |
| [getCrossAt()](#getCrossAt--) | Představuje bod na ose, kde ji protilehlá osa protíná. |
| [setCrossAt(float value)](#setCrossAt-float-) | Představuje bod na ose, kde ji protilehlá osa protíná. |
| [getDisplayUnit()](#getDisplayUnit--) | Určuje škálovací hodnotu zobrazovacích jednotek pro osu hodnot. |
| [setDisplayUnit(int value)](#setDisplayUnit-int-) | Určuje škálovací hodnotu zobrazovacích jednotek pro osu hodnot. |
| [getActualMaxValue()](#getActualMaxValue--) | Určuje skutečnou maximální hodnotu na ose. |
| [getActualMinValue()](#getActualMinValue--) | Určuje skutečnou minimální hodnotu na ose. |
| [getActualMajorUnit()](#getActualMajorUnit--) | Určuje skutečnou hlavní jednotku osy. |
| [getActualMinorUnit()](#getActualMinorUnit--) | Určuje skutečnou vedlejší jednotku osy. |
| [getActualMajorUnitScale()](#getActualMajorUnitScale--) | Určuje skutečnou škálu hlavní jednotky osy. |
| [getActualMinorUnitScale()](#getActualMinorUnitScale--) | Určuje skutečnou škálu vedlejší jednotky osy. |
| [isAutomaticMaxValue()](#isAutomaticMaxValue--) | Indikuje, zda je maximální hodnota přiřazena automaticky. |
| [setAutomaticMaxValue(boolean value)](#setAutomaticMaxValue-boolean-) | Indikuje, zda je maximální hodnota přiřazena automaticky. |
| [getMaxValue()](#getMaxValue--) | Představuje maximální hodnotu na ose hodnot. |
| [setMaxValue(double value)](#setMaxValue-double-) | Představuje maximální hodnotu na ose hodnot. |
| [getMinorUnit()](#getMinorUnit--) | Představuje vedlejší jednotky pro datum nebo osu hodnot. |
| [setMinorUnit(double value)](#setMinorUnit-double-) | Představuje vedlejší jednotky pro datum nebo osu hodnot. |
| [isAutomaticMinorUnit()](#isAutomaticMinorUnit--) | Indikuje, zda je vedlejší jednotka osy přiřazena automaticky. |
| [setAutomaticMinorUnit(boolean value)](#setAutomaticMinorUnit-boolean-) | Indikuje, zda je vedlejší jednotka osy přiřazena automaticky. |
| [getMajorUnit()](#getMajorUnit--) | Představuje hlavní jednotky pro datum nebo osu hodnot. |
| [setMajorUnit(double value)](#setMajorUnit-double-) | Představuje hlavní jednotky pro datum nebo osu hodnot. |
| [isAutomaticMajorUnit()](#isAutomaticMajorUnit--) | Indikuje, zda je hlavní jednotka osy přiřazena automaticky. |
| [setAutomaticMajorUnit(boolean value)](#setAutomaticMajorUnit-boolean-) | Indikuje, zda je hlavní jednotka osy přiřazena automaticky. |
| [isAutomaticMinValue()](#isAutomaticMinValue--) | Indikuje, zda je minimální hodnota přiřazena automaticky. |
| [setAutomaticMinValue(boolean value)](#setAutomaticMinValue-boolean-) | Indikuje, zda je minimální hodnota přiřazena automaticky. |
| [getMinValue()](#getMinValue--) | Představuje minimální hodnotu na ose hodnot. |
| [setMinValue(double value)](#setMinValue-double-) | Představuje minimální hodnotu na ose hodnot. |
| [isLogarithmic()](#isLogarithmic--) | Představuje, zda je typ měřítka osy hodnot logaritmický nebo ne. |
| [setLogarithmic(boolean value)](#setLogarithmic-boolean-) | Představuje, zda je typ měřítka osy hodnot logaritmický nebo ne. |
| [getLogBase()](#getLogBase--) | Představuje logaritmický základ. |
| [setLogBase(double value)](#setLogBase-double-) | Představuje logaritmický základ. |
| [isPlotOrderReversed()](#isPlotOrderReversed--) | Představuje, zda MS PowerPoint vykresluje datové body od posledního k prvnímu. |
| [setPlotOrderReversed(boolean value)](#setPlotOrderReversed-boolean-) | Představuje, zda MS PowerPoint vykresluje datové body od posledního k prvnímu. |
| [isVisible()](#isVisible--) | Představuje, zda je osa viditelná. |
| [setVisible(boolean value)](#setVisible-boolean-) | Představuje, zda je osa viditelná. |
| [getMajorTickMark()](#getMajorTickMark--) | Představuje typ hlavního značkovacího pruhu pro zadanou osu. |
| [setMajorTickMark(int value)](#setMajorTickMark-int-) | Představuje typ hlavního značkovacího pruhu pro zadanou osu. |
| [getMinorTickMark()](#getMinorTickMark--) | Představuje typ vedlejšího značkovacího pruhu pro zadanou osu. |
| [setMinorTickMark(int value)](#setMinorTickMark-int-) | Představuje typ vedlejšího značkovacího pruhu pro zadanou osu. |
| [getTickLabelPosition()](#getTickLabelPosition--) | Představuje polohu štítků značek na zadané ose. |
| [setTickLabelPosition(int value)](#setTickLabelPosition-int-) | Představuje polohu štítků značek na zadané ose. |
| [getMajorUnitScale()](#getMajorUnitScale--) | Představuje škálu hlavní jednotky pro osu data. |
| [setMajorUnitScale(int value)](#setMajorUnitScale-int-) | Představuje škálu hlavní jednotky pro osu data. |
| [getMinorUnitScale()](#getMinorUnitScale--) | Představuje škálu hlavní jednotky pro osu data. |
| [setMinorUnitScale(int value)](#setMinorUnitScale-int-) | Představuje škálu hlavní jednotky pro osu data. |
| [getBaseUnitScale()](#getBaseUnitScale--) | Určuje nejmenší časovou jednotku, která je reprezentována na ose data. |
| [setBaseUnitScale(int value)](#setBaseUnitScale-int-) | Určuje nejmenší časovou jednotku, která je reprezentována na ose data. |
| [getMinorGridLinesFormat()](#getMinorGridLinesFormat--) | Představuje formát vedlejších mřížkových čar na ose grafu. |
| [getMajorGridLinesFormat()](#getMajorGridLinesFormat--) | Představuje formát hlavních mřížkových čar na ose grafu. |
| [getShowMinorGridLines()](#getShowMinorGridLines--) | Představuje, zda jsou vedlejší mřížkové čáry zobrazeny. |
| [getShowMajorGridLines()](#getShowMajorGridLines--) | Představuje, zda jsou hlavní mřížkové čáry zobrazeny. |
| [getFormat()](#getFormat--) | Představuje formát osy. |
| [getTitle()](#getTitle--) | Získá název osy. |
| [getCrossType()](#getCrossType--) | Představuje typ průniku (CrossType) na dané ose, kde se protíná druhá osa. |
| [setCrossType(int value)](#setCrossType-int-) | Představuje typ průniku (CrossType) na dané ose, kde se protíná druhá osa. |
| [getPosition()](#getPosition--) | Představuje pozici osy. |
| [setPosition(int value)](#setPosition-int-) | Představuje pozici osy. |
| [hasTitle()](#hasTitle--) | Určuje, zda má osa viditelný název. |
| [setTitle(boolean value)](#setTitle-boolean-) | Určuje, zda má osa viditelný název. |
| [getNumberFormat()](#getNumberFormat--) | Představuje formátovací řetězec pro popisky osy. |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | Představuje formátovací řetězec pro popisky osy. |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | Indikuje, zda je formát propojen se zdrojovými daty. |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | Indikuje, zda je formát propojen se zdrojovými daty. |
| [getTickLabelRotationAngle()](#getTickLabelRotationAngle--) | Představuje úhel otočení štítků značek. Číst/zapisovat float. |
| [setTickLabelRotationAngle(float value)](#setTickLabelRotationAngle-float-) | Představuje úhel otočení štítků značek. Číst/zapisovat float. |
| [getTickLabelSpacing()](#getTickLabelSpacing--) | Určuje, kolik štítků značek se má přeskočit mezi vykreslenými štítky. |
| [setTickLabelSpacing(long value)](#setTickLabelSpacing-long-) | Určuje, kolik štítků značek se má přeskočit mezi vykreslenými štítky. |
| [isAutomaticTickLabelSpacing()](#isAutomaticTickLabelSpacing--) | Určuje automatickou hodnotu mezery mezi štítky značek. |
| [setAutomaticTickLabelSpacing(boolean value)](#setAutomaticTickLabelSpacing-boolean-) | Určuje automatickou hodnotu mezery mezi štítky značek. |
| [getTickMarksSpacing()](#getTickMarksSpacing--) | Určuje, kolik značek se má přeskočit před dalším vykreslením. |
| [setTickMarksSpacing(long value)](#setTickMarksSpacing-long-) | Určuje, kolik značek se má přeskočit před dalším vykreslením. |
| [isAutomaticTickMarksSpacing()](#isAutomaticTickMarksSpacing--) | Určuje automatickou hodnotu mezery mezi značkami. |
| [setAutomaticTickMarksSpacing(boolean value)](#setAutomaticTickMarksSpacing-boolean-) | Určuje automatickou hodnotu mezery mezi značkami. |
| [getLabelOffset()](#getLabelOffset--) | Určuje vzdálenost štítků od osy. |
| [setLabelOffset(int value)](#setLabelOffset-int-) | Určuje vzdálenost štítků od osy. |
| [getCategoryAxisType()](#getCategoryAxisType--) | Určuje typ osy kategorií. |
| [setCategoryAxisType(int value)](#setCategoryAxisType-int-) | Určuje typ osy kategorií. |
| [setCategoryAxisTypeAutomatically()](#setCategoryAxisTypeAutomatically--) | Nastavuje vlastnost IAxis.CategoryAxisType na hodnotu, která je automaticky určena na základě dat osy. |
| [getAggregationType()](#getAggregationType--) | Představuje typ agregace osy kategorií (seskupování). |
| [setAggregationType(int value)](#setAggregationType-int-) | Představuje typ agregace osy kategorií (seskupování). |
| [getBinWidth()](#getBinWidth--) | Určuje šířku koše, když je vlastnost AggregationType nastavena na AxisAggregationType.ByBinWidth. |
| [setBinWidth(double value)](#setBinWidth-double-) | Určuje šířku koše, když je vlastnost AggregationType nastavena na AxisAggregationType.ByBinWidth. |
| [getNumberOfBins()](#getNumberOfBins--) | Určuje počet košů, když je vlastnost AggregationType nastavena na AxisAggregationType.ByNumberOfBins. |
| [setNumberOfBins(long value)](#setNumberOfBins-long-) | Určuje počet košů, když je vlastnost AggregationType nastavena na AxisAggregationType.ByNumberOfBins. |
| [isOverflowBin()](#isOverflowBin--) | Určuje, zda je použit přetečný koš. |
| [setOverflowBin(boolean value)](#setOverflowBin-boolean-) | Určuje, zda je použit přetečný koš. |
| [isAutomaticOverflowBin()](#isAutomaticOverflowBin--) | Určuje automatickou hodnotu přetečného koše. |
| [setAutomaticOverflowBin(boolean value)](#setAutomaticOverflowBin-boolean-) | Určuje automatickou hodnotu přetečného koše. |
| [getOverflowBin()](#getOverflowBin--) | Určuje vlastní hodnotu přetečného koše. |
| [setOverflowBin(double value)](#setOverflowBin-double-) | Určuje vlastní hodnotu přetečného koše. |
| [isUnderflowBin()](#isUnderflowBin--) | Určuje, zda je použit podtečný koš. |
| [setUnderflowBin(boolean value)](#setUnderflowBin-boolean-) | Určuje, zda je použit podtečný koš. |
| [isAutomaticUnderflowBin()](#isAutomaticUnderflowBin--) | Určuje automatickou hodnotu podtečného koše. |
| [setAutomaticUnderflowBin(boolean value)](#setAutomaticUnderflowBin-boolean-) | Určuje automatickou hodnotu podtečného koše. |
| [getUnderflowBin()](#getUnderflowBin--) | Určuje vlastní hodnotu podtečného koše. |
| [setUnderflowBin(double value)](#setUnderflowBin-double-) | Určuje vlastní hodnotu podtečného koše. |

### getAxisBetweenCategories() {#getAxisBetweenCategories--}
```
public abstract boolean getAxisBetweenCategories()
```

Představuje, zda osa hodnot protíná osu kategorií mezi kategoriemi. Tato vlastnost se vztahuje pouze na osy kategorií a nepoužívá se u 3D grafů. Číst/zapisovat boolean.

**Vrací:**
boolean

### setAxisBetweenCategories(boolean value) {#setAxisBetweenCategories-boolean-}
```
public abstract void setAxisBetweenCategories(boolean value)
```

Představuje, zda osa hodnot protíná osu kategorií mezi kategoriemi. Tato vlastnost se vztahuje pouze na osy kategorií a nepoužívá se u 3D grafů. Číst/zapisovat boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getCrossAt() {#getCrossAt--}
```
public abstract float getCrossAt()
```

Představuje bod na ose, kde ji protilehlá osa protíná. Číst/zapisovat float.

**Vrací:**
float

### setCrossAt(float value) {#setCrossAt-float-}
```
public abstract void setCrossAt(float value)
```

Představuje bod na ose, kde ji protilehlá osa protíná. Číst/zapisovat float.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |

### getDisplayUnit() {#getDisplayUnit--}
```
public abstract int getDisplayUnit()
```

Určuje škálovací hodnotu zobrazovacích jednotek pro osu hodnot. Číst/zapisovat [DisplayUnitType](../../com.aspose.slides/displayunittype).

**Vrací:**
int

### setDisplayUnit(int value) {#setDisplayUnit-int-}
```
public abstract void setDisplayUnit(int value)
```

Určuje škálovací hodnotu zobrazovacích jednotek pro osu hodnot. Číst/zapisovat [DisplayUnitType](../../com.aspose.slides/displayunittype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getActualMaxValue() {#getActualMaxValue--}
```
public abstract double getActualMaxValue()
```

Určuje skutečnou maximální hodnotu na ose. Předtím zavolejte metodu IChart.ValidateChartLayout(), abyste získali skutečnou hodnotu.

**Vrací:**
double

### getActualMinValue() {#getActualMinValue--}
```
public abstract double getActualMinValue()
```

Určuje skutečnou minimální hodnotu na ose. Předtím zavolejte metodu IChart.ValidateChartLayout(), abyste získali skutečnou hodnotu.

**Vrací:**
double

### getActualMajorUnit() {#getActualMajorUnit--}
```
public abstract double getActualMajorUnit()
```

Určuje skutečnou hlavní jednotku osy. Předtím zavolejte metodu IChart.ValidateChartLayout(), abyste získali skutečnou hodnotu.

**Vrací:**
double

### getActualMinorUnit() {#getActualMinorUnit--}
```
public abstract double getActualMinorUnit()
```

Určuje skutečnou vedlejší jednotku osy. Předtím zavolejte metodu IChart.ValidateChartLayout(), abyste získali skutečnou hodnotu.

**Vrací:**
double

### getActualMajorUnitScale() {#getActualMajorUnitScale--}
```
public abstract int getActualMajorUnitScale()
```

Určuje skutečnou škálu hlavní jednotky osy. Předtím zavolejte metodu IChart.ValidateChartLayout(), abyste získali skutečnou hodnotu.

**Vrací:**
int

### getActualMinorUnitScale() {#getActualMinorUnitScale--}
```
public abstract int getActualMinorUnitScale()
```

Určuje skutečnou škálu vedlejší jednotky osy. Předtím zavolejte metodu IChart.ValidateChartLayout(), abyste získali skutečnou hodnotu.

**Vrací:**
int

### isAutomaticMaxValue() {#isAutomaticMaxValue--}
```
public abstract boolean isAutomaticMaxValue()
```

Indikuje, zda je maximální hodnota přiřazena automaticky. Číst/zapisovat boolean.

**Vrací:**
boolean

### setAutomaticMaxValue(boolean value) {#setAutomaticMaxValue-boolean-}
```
public abstract void setAutomaticMaxValue(boolean value)
```

Indikuje, zda je maximální hodnota přiřazena automaticky. Číst/zapisovat boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getMaxValue() {#getMaxValue--}
```
public abstract double getMaxValue()
```

Představuje maximální hodnotu na ose hodnot. Číst/zapisovat double.

**Vrací:**
double

### setMaxValue(double value) {#setMaxValue-double-}
```
public abstract void setMaxValue(double value)
```

Představuje maximální hodnotu na ose hodnot. Číst/zapisovat double.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |

### getMinorUnit() {#getMinorUnit--}
```
public abstract double getMinorUnit()
```

Představuje vedlejší jednotky pro datum nebo osu hodnot. Číst/zapisovat double.

**Vrací:**
double

### setMinorUnit(double value) {#setMinorUnit-double-}
```
public abstract void setMinorUnit(double value)
```

Představuje vedlejší jednotky pro datum nebo osu hodnot. Číst/zapisovat double.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |

### isAutomaticMinorUnit() {#isAutomaticMinorUnit--}
```
public abstract boolean isAutomaticMinorUnit()
```

Indikuje, zda je vedlejší jednotka osy přiřazena automaticky. Číst/zapisovat boolean.

**Vrací:**
boolean

### setAutomaticMinorUnit(boolean value) {#setAutomaticMinorUnit-boolean-}
```
public abstract void setAutomaticMinorUnit(boolean value)
```

Indikuje, že vedlejší jednotka osy je přiřazena automaticky. Číst/zapisovat boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getMajorUnit() {#getMajorUnit--}
```
public abstract double getMajorUnit()
```

Představuje hlavní jednotky pro datum nebo osu hodnot. Číst/zapisovat double.

**Vrací:**
double

### setMajorUnit(double value) {#setMajorUnit-double-}
```
public abstract void setMajorUnit(double value)
```

Představuje hlavní jednotky pro datum nebo osu hodnot. Číst/zapisovat double.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |

### isAutomaticMajorUnit() {#isAutomaticMajorUnit--}
```
public abstract boolean isAutomaticMajorUnit()
```

Indikuje, zda je hlavní jednotka osy přiřazena automaticky. Číst/zapisovat boolean.

**Vrací:**
boolean

### setAutomaticMajorUnit(boolean value) {#setAutomaticMajorUnit-boolean-}
```
public abstract void setAutomaticMajorUnit(boolean value)
```

Indikuje, že hlavní jednotka osy je přiřazena automaticky. Číst/zapisovat boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticMinValue() {#isAutomaticMinValue--}
```
public abstract boolean isAutomaticMinValue()
```

Indikuje, zda je minimální hodnota přiřazena automaticky. Číst/zapisovat boolean.

**Vrací:**
boolean

### setAutomaticMinValue(boolean value) {#setAutomaticMinValue-boolean-}
```
public abstract void setAutomaticMinValue(boolean value)
```

Indikuje, že minimální hodnota je přiřazena automaticky. Číst/zapisovat boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getMinValue() {#getMinValue--}
```
public abstract double getMinValue()
```

Představuje minimální hodnotu na ose hodnot. Číst/zapisovat double.

**Vrací:**
double

### setMinValue(double value) {#setMinValue-double-}
```
public abstract void setMinValue(double value)
```

Představuje minimální hodnotu na ose hodnot. Číst/zapisovat double.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |

### isLogarithmic() {#isLogarithmic--}
```
public abstract boolean isLogarithmic()
```

Představuje, zda je typ měřítka osy hodnot logaritmický nebo ne. Číst/zapisovat boolean.

**Vrací:**
boolean

### setLogarithmic(boolean value) {#setLogarithmic-boolean-}
```
public abstract void setLogarithmic(boolean value)
```

Představuje, zda je typ měřítka osy hodnot logaritmický nebo ne. Číst/zapisovat boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getLogBase() {#getLogBase--}
```
public abstract double getLogBase()
```

Představuje logaritmický základ. Výchozí hodnota je 10. Číst/zapisovat double.

**Vrací:**
double

### setLogBase(double value) {#setLogBase-double-}
```
public abstract void setLogBase(double value)
```

Představuje logaritmický základ. Výchozí hodnota je 10. Číst/zapisovat double.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |

### isPlotOrderReversed() {#isPlotOrderReversed--}
```
public abstract boolean isPlotOrderReversed()
```

Představuje, zda MS PowerPoint vykresluje datové body od posledního k prvnímu. Číst/zapisovat boolean.

**Vrací:**
boolean

### setPlotOrderReversed(boolean value) {#setPlotOrderReversed-boolean-}
```
public abstract void setPlotOrderReversed(boolean value)
```

Představuje, zda MS PowerPoint vykresluje datové body od posledního k prvnímu. Číst/zapisovat boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

Představuje, zda je osa viditelná. Číst/zapisovat boolean.

**Vrací:**
boolean

### setVisible(boolean value) {#setVisible-boolean-}
```
public abstract void setVisible(boolean value)
```

Představuje, zda je osa viditelná. Číst/zapisovat boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getMajorTickMark() {#getMajorTickMark--}
```
public abstract int getMajorTickMark()
```

Představuje typ hlavního značkovacího pruhu pro zadanou osu. Číst/zapisovat [TickMarkType](../../com.aspose.slides/tickmarktype).

**Vrací:**
int

### setMajorTickMark(int value) {#setMajorTickMark-int-}
```
public abstract void setMajorTickMark(int value)
```

Představuje typ hlavního značkovacího pruhu pro zadanou osu. Číst/zapisovat [TickMarkType](../../com.aspose.slides/tickmarktype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getMinorTickMark() {#getMinorTickMark--}
```
public abstract int getMinorTickMark()
```

Představuje typ vedlejšího značkovacího pruhu pro zadanou osu. Číst/zapisovat [TickMarkType](../../com.aspose.slides/tickmarktype).

**Vrací:**
int

### setMinorTickMark(int value) {#setMinorTickMark-int-}
```
public abstract void setMinorTickMark(int value)
```

Představuje typ vedlejšího značkovacího pruhu pro zadanou osu. Číst/zapisovat [TickMarkType](../../com.aspose.slides/tickmarktype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getTickLabelPosition() {#getTickLabelPosition--}
```
public abstract int getTickLabelPosition()
```

Představuje polohu štítků značek na zadané ose. Číst/zapisovat [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**Vrací:**
int

### setTickLabelPosition(int value) {#setTickLabelPosition-int-}
```
public abstract void setTickLabelPosition(int value)
```

Představuje polohu štítků značek na zadané ose. Číst/zapisovat [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getMajorUnitScale() {#getMajorUnitScale--}
```
public abstract int getMinor…? (???) …? 

the...?

```

Představuje škálu hlavní jednotky pro osu data. Číst/zapisovat [TimeUnitType](../../com.aspose.slides/timeunittype).

**Vrací:**
int

### setMajorUnitScale(int value) {#setMajorUnitScale-int-}
```
public abstract void setMajorUnitScale(int value)
```

Představuje škálu hlavní jednotky pro osu data. Číst/zapisovat [TimeUnitType](../../com.aspose.slides/timeunittype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getMinorUnitScale() {#getMinorUnitScale--}
```
public abstract int getMinorUnitScale()
```

Představuje škálu hlavní jednotky pro osu data. Číst/zapisovat [TimeUnitType](../../com.aspose.slides/timeunittype).

**Vrací:**
int

### setMinorUnitScale(int value) {#setMinorUnitScale-int-}
```
public abstract void setMinorUnitScale(int value)
```

Představuje škálu hlavní jednotky pro osu data. Číst/zapisovat [TimeUnitType](../../com.aspose.slides/timeunittype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getBaseUnitScale() {#getBaseUnitScale--}
```
public abstract int getBaseUnitScale()
```

Určuje nejmenší časovou jednotku, která je reprezentována na ose data. Číst/zapisovat [TimeUnitType](../../com.aspose.slides/timeunittype).

**Vrací:**
int

### setBaseUnitScale(int value) {#setBaseUnitScale-int-}
```
public abstract void setBaseUnitScale(int value)
```

Určuje nejmenší časovou jednotku, která je reprezentována na ose data. Číst/zapisovat [TimeUnitType](../../com.aspose.slides/timeunittype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getMinorGridLinesFormat() {#getMinorGridLinesFormat--}
```
public abstract IChartLinesFormat getMinorGridLinesFormat()
```

Představuje formát vedlejších mřížkových čar na ose grafu. Pouze pro čtení [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**Vrací:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getMajorGridLinesFormat() {#getMajorGridLinesFormat--}
```
public abstract IChartLinesFormat getMajorGridLinesFormat()
```

Představuje formát hlavních mřížkových čar na ose grafu. Pouze pro čtení [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**Vrací:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getShowMinorGridLines() {#getShowMinorGridLines--}
```
public abstract boolean getShowMinorGridLines()
```

Představuje, zda jsou vedlejší mřížkové čáry zobrazeny. Pouze pro čtení boolean.

**Vrací:**
boolean

### getShowMajorGridLines() {#getShowMajorGridLines--}
```
public abstract boolean getShowMajorGridLines()
```

Představuje, zda jsou hlavní mřížkové čáry zobrazeny. Pouze pro čtení boolean.

**Vrací:**
boolean

### getFormat() {#getFormat--}
```
public abstract IAxisFormat getFormat()
```

Představuje formát osy. Pouze pro čtení [IAxisFormat](../../com.aspose.slides/iaxisformat).

**Vrací:**
[IAxisFormat](../../com.aspose.slides/iaxisformat)

### getTitle() {#getTitle--}
```




```

Získá název osy. Pouze pro čtení [IChartTitle](../../com.aspose.slides/icharttitle).

**Vrací:**
[IChartTitle](../../com.aspose.slides/icharttitle)

### getCrossType() {#getCrossType--}
```
public abstract int getCrossType()
```

Představuje typ průniku (CrossType) na dané ose, kde se protíná druhá osa. Číst/zapisovat [CrossesType](../../com.aspose.slides/crossestype).

**Vrací:**
int

### setCrossType(int value) {#setCrossType-int-}
```
public abstract void setCrossType(int value)
```

Představuje typ průniku (CrossType) na dané ose, kde se protíná druhá osa. Číst/zapisovat [CrossesType](../../com.aspose.slides/crossestype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

Představuje pozici osy. Číst/zapisovat [AxisPositionType](../../com.aspose.slides/axispositiontype).

**Vrací:**
int

### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

Představuje pozici osy. Číst/zapisovat [AxisPositionType](../../com.aspose.slides/axispositiontype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### hasTitle() {#hasTitle--}
```
public abstract boolean hasTitle()
```

Určuje, zda má osa viditelný název. Číst/zapisovat boolean.

**Vrací:**
boolean

### setTitle(boolean value) {#setTitle-boolean-}
```
public abstract void setTitle(boolean value)
```

Určuje, zda má osa viditelný název. Číst/zapisovat boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public abstract String getNumberFormat()
```

Představuje formátovací řetězec pro popisky osy. Číst/zapisovat String.

**Vrací:**
java.lang.String

### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public abstract void setNumberFormat(String value)
```

Představuje formátovací řetězec pro popisky osy. Číst/zapisovat String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public abstract boolean isNumberFormatLinkedToSource()
```

Indikuje, zda je formát propojen se zdrojovými daty. Číst/zapisovat boolean.

**Vrací:**
boolean

### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public abstract void setNumberFormatLinkedToSource(boolean value)
```

Indikuje, zda je formát propojen se zdrojovými daty. Číst/zapisovat boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getTickLabelRotationAngle() {#getTickLabelRotationAngle--}
```
public abstract float getTickLabelRotationAngle()
```

Představuje úhel otočení štítků značek. Číst/zapisovat float.

**Vrací:**
float

### setTickLabelRotationAngle(float value) {#setTickLabelRotationAngle-float-}
```
public abstract void setTickLabelRotationAngle(float value)
```

Představuje úhel otočení štítků značek. Číst/zapisovat float.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |

### getTickLabelSpacing() {#getTickLabelSpacing--}
```
public abstract long getTickLabelSpacing()
```

Určuje, kolik štítků značek se má přeskočit mezi vykreslenými štítky. Číst/zapisovat long.

**Vrací:**
long

### setTickLabelSpacing(long value) {#setTickLabelSpacing-long-}
```
public abstract void setTickLabelSpacing(long value)
```

Určuje, kolik štítků značek se má přeskočit mezi vykreslenými štítky. Číst/zapisovat long.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickLabelSpacing() {#isAutomaticTickLabelSpacing--}
```
public abstract boolean isAutomaticTickLabelSpacing()
```

Určuje automatickou hodnotu mezery mezi štítky značek. Pokud false: použijte vlastnost TickLabelSpacing. Číst/zapisovat boolean.

**Vrací:**
boolean

### setAutomaticTickLabelSpacing(boolean value) {#setAutomaticTickLabelSpacing-boolean-}
```
public abstract void setAutomaticTickLabelSpacing(boolean value)
```

Určuje automatickou hodnotu mezery mezi štítky značek. Pokud false: použijte vlastnost TickLabelSpacing. Číst/zapisovat boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getTickMarksSpacing() {#getTickMarksSpacing--}
```
public abstract long getTickMarksSpacing()
```

Určuje, kolik značek se má přeskočit před dalším vykreslením. Používá se pro osu kategorií nebo sérií. Číst/zapisovat int.

**Vrací:**
long

### setTickMarksSpacing(long value) {#setTickMarksSpacing-long-}
```
public abstract void setTickMarksSpacing(long value)
```

Určuje, kolik značek se má přeskočit před dalším vykreslením. Používá se pro osu kategorií nebo sérií. Číst/zapisovat int.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickMarksSpacing() {#isAutomaticTickMarksSpacing--}
```
public abstract boolean isAutomaticTickMarksSpacing()
```

Určuje automatickou hodnotu mezery mezi značkami. Pokud false: použijte vlastnost TickMarksSpacing. Číst/zapisovat boolean.

**Vrací:**
boolean

### setAutomaticTickMarksSpacing(boolean value) {#setAutomaticTickMarksSpacing-boolean-}
```
public abstract void setAutomaticTickMarksSpacing(boolean value)
```

Určuje automatickou hodnotu mezery mezi značkami. Pokud false: použijte vlastnost TickMarksSpacing. Číst/zapisovat boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getLabelOffset() {#getLabelOffset--}
```
public abstract int getLabelOffset()
```

Určuje vzdálenost štítků od osy. Používá se pro osu kategorií nebo datum. Hodnota musí být mezi 0 % a 1000 %. Číst/zapisovat int.

**Vrací:**
int

### setLabelOffset(int value) {#setLabelOffset-int-}
```
public abstract void setLabelOffset(int value)
```

Určuje vzdálenost štítků od osy. Používá se pro osu kategorií nebo datum. Hodnota musí být mezi 0 % a 1000 %. Číst/zapisovat int.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getCategoryAxisType() {#getCategoryAxisType--}
```
public abstract int getCategoryAxisType()
```

Určuje typ osy kategorií. Číst/zapisovat [CategoryAxisType](../../com.aspose.slides/categoryaxistype)(\#getCategoryAxisType.getCategoryAxisType/\#setCategoryAxisType(int).setCategoryAxisType(int)).

**Vrací:**
int

### setCategoryAxisType(int value) {#setCategoryAxisType-int-}
```


``` 

The ... 



We 







This 







...

`…`.

Určuje typ osy kategorií. Číst/zapisovat [CategoryAxisType](../../com.aspose.slides/categoryaxistype)(\#getCategoryAxisType.getCategoryAxisType/\#setCategoryAxisType(int).setCategoryAxisType(int)).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### setCategoryAxisTypeAutomatically() {#setCategoryAxisTypeAutomatically--}
```
public abstract void setCategoryAxisTypeAutomatically()
```

Nastavuje vlastnost IAxis.CategoryAxisType na hodnotu, která je automaticky určena na základě dat osy.

### getAggregationType() {#getAggregationType--}
```
public abstract int getAggregationType()
```

Představuje typ agregace osy kategorií (seskupování). Používá se pro osu kategorií. Použitelné jen s řadami Histogram nebo HistogramPareto.

**Vrací:**
int

### setAggregationType(int value) {#setAggregationType-int-}
```
public abstract void setAggregationType(int value)
```

Představuje typ agregace osy kategorií (seskupování). Používá se pro osu kategorií. Použitelné jen s řadami Histogram nebo HistogramPareto.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getBinWidth() {#getBinWidth--}
```
public abstract double getBinWidth()
```

Určuje šířku koše, když je vlastnost AggregationType nastavena na AxisAggregationType.ByBinWidth. Používá se pro osy kategorií. Použitelné jen s řadami Histogram nebo HistogramPareto.

**Vrací:**
double

### setBinWidth(double value) {#setBinWidth-double-}
```
public abstract void setBinWidth(double value)
```

Určuje šířku koše, když je vlastnost AggregationType nastavena na AxisAggregationType.ByBinWidth. Používá se pro osy kategorií. Použitelné jen s řadami Histogram nebo HistogramPareto.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |

### getNumberOfBins() {#getNumberOfBins--}
```
public abstract long getNumberOfBins()
```

Určuje počet košů, když je vlastnost AggregationType nastavena na AxisAggregationType.ByNumberOfBins. Používá se pro osy kategorií. Použitelné jen s řadami Histogram nebo HistogramPareto.

**Vrací:**
long

### setNumberOfBins(long value) {#setNumberOfBins-long-}
```
public abstract void setNumberOfBins(long value)
```

Určuje počet košů, když je vlastnost AggregationType nastavena na AxisAggregationType.ByNumberOfBins. Používá se pro osy kategorií. Použitelné jen s řadami Histogram nebo HistogramPareto.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | long |  |

### isOverflowBin() {#isOverflowBin--}
```
public abstract boolean isOverflowBin()
```

Určuje, zda je použit přetečný koš. Použijte IsAutomaticOverflowBin a OverflowBin pro úpravu hodnoty přetečného koše.

**Vrací:**
boolean

### setOverflowBin(boolean value) {#setOverflowBin-boolean-}
```
public abstract void setOverflowBin(boolean value)
```

Určuje, zda je použit přetečný koš. Použijte IsAutomaticOverflowBin a OverflowBin pro úpravu hodnoty přetečného koše.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticOverflowBin() {#isAutomaticOverflowBin--}
```
public abstract boolean isAutomaticOverflowBin()
```

Určuje automatickou hodnotu přetečného koše. Pokud false: použijte vlastnost OverflowBin.

**Vrací:**
boolean

### setAutomaticOverflowBin(boolean value) {#setAutomaticOverflowBin-boolean-}
```
public abstract void setAutomaticOverflowBin(boolean value)
```

Určuje automatickou hodnotu přetečného koše. Pokud false: použijte vlastnost OverflowBin.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getOverflowBin() {#getOverflowBin--}
```
public abstract double getOverflowBin()
```

Určuje vlastní hodnotu přetečného koše. Používá se, když je vlastnost IsAutomaticOverflowBin nastavena na false a IsOverflowBin je true.

**Vrací:**
double

### setOverflowBin(double value) {#setOverflowBin-double-}
```
public abstract void setOverflowBin(double value)
```

Určuje vlastní hodnotu přetečného koše. Používá se, když je vlastnost IsAutomaticOverflowBin nastavena na false a IsOverflowBin je true.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |

### isUnderflowBin() {#isUnderflowBin--}
```
public abstract boolean isUnderflowBin()
```

Určuje, zda je použit podtečný koš. Použijte IsAutomaticUnderflowBin a UnderflowBin pro úpravu hodnoty podtečného koše.

**Vrací:**
boolean

### setUnderflowBin(boolean value) {#setUnderflowBin-boolean-}
```
public abstract void setUnderflowBin(boolean value)
```

Určuje, zda je použit podtečný koš. Použijte IsAutomaticUnderflowBin a UnderflowBin pro úpravu hodnoty podtečného koše.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticUnderflowBin() {#isAutomaticUnderflowBin--}
```
public abstract boolean isAutomaticUnderflowBin()
```

Určuje automatickou hodnotu podtečného koše. Pokud false: použijte vlastnost UnderflowBin.

**Vrací:**
boolean

### setAutomaticUnderflowBin(boolean value) {#setAutomaticUnderflowBin-boolean-}
```
public abstract void setAutomaticUnderflowBin(boolean value)
```

Určuje automatickou hodnotu podtečného koše. Pokud false: použijte vlastnost UnderflowBin.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getUnderflowBin() {#getUnderflowBin--}
```
public abstract double getUnderflowBin()
```

Určuje vlastní hodnotu podtečného koše. Používá se, když je vlastnost IsAutomaticUnderflowBin nastavena na false a IsUnderflowBin je true.

**Vrací:**
double

### setUnderflowBin(double value) {#setUnderflowBin-double-}
```
public abstract void setUnderflowBin(double value)
```

Určuje vlastní hodnotu podtečného koše. Používá se, když je vlastnost IsAutomaticUnderflowBin nastavena na false a IsUnderflowBin je true.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |