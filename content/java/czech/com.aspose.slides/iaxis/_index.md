---
title: IAxis
second_title: Aspose.Slides pro Java API referenční příručka
description: Zapouzdřuje objekt, který představuje osu grafu.
type: docs
url: /cs/com.aspose.slides/iaxis/
---
**All Implemented Interfaces:**
[com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer)
```
public interface IAxis extends IFormattedTextContainer
```

Encapsulates the object that represents a chart's axis.
## Metody

| Metoda | Popis |
| --- | --- |
| [getAxisBetweenCategories()](#getAxisBetweenCategories--) | Určuje, zda osa hodnot protíná osu kategorií mezi kategoriemi. |
| [setAxisBetweenCategories(boolean value)](#setAxisBetweenCategories-boolean-) | Určuje, zda osa hodnot protíná osu kategorií mezi kategoriemi. |
| [getCrossAt()](#getCrossAt--) | Zobrazuje bod na ose, kde ji protichůdná osa protíná. |
| [setCrossAt(float value)](#setCrossAt-float-) | Zobrazuje bod na ose, kde ji protichůdná osa protíná. |
| [getDisplayUnit()](#getDisplayUnit--) | Určuje měřítkovou hodnotu zobrazovacích jednotek pro osu hodnot. |
| [setDisplayUnit(int value)](#setDisplayUnit-int-) | Určuje měřítkovou hodnotu zobrazovacích jednotek pro osu hodnot. |
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
| [getMinorUnit()](#getMinorUnit--) | Zobrazuje vedlejší jednotky pro datumovou nebo hodnotovou osu. |
| [setMinorUnit(double value)](#setMinorUnit-double-) | Zobrazuje vedlejší jednotky pro datumovou nebo hodnotovou osu. |
| [isAutomaticMinorUnit()](#isAutomaticMinorUnit--) | Indikuje, zda je vedlejší jednotka osy přiřazena automaticky. |
| [setAutomaticMinorUnit(boolean value)](#setAutomaticMinorUnit-boolean-) | Indikuje, že je vedlejší jednotka osy přiřazena automaticky. |
| [getMajorUnit()](#getMajorUnit--) | Zobrazuje hlavní jednotky pro datumovou nebo hodnotovou osu. |
| [setMajorUnit(double value)](#setMajorUnit-double-) | Zobrazuje hlavní jednotky pro datumovou nebo hodnotovou osu. |
| [isAutomaticMajorUnit()](#isAutomaticMajorUnit--) | Indikuje, zda je hlavní jednotka osy přiřazena automaticky. |
| [setAutomaticMajorUnit(boolean value)](#setAutomaticMajorUnit-boolean-) | Indikuje, že je hlavní jednotka osy přiřazena automaticky. |
| [isAutomaticMinValue()](#isAutomaticMinValue--) | Indikuje, zda je minimální hodnota přiřazena automaticky. |
| [setAutomaticMinValue(boolean value)](#setAutomaticMinValue-boolean-) | Indikuje, že je minimální hodnota přiřazena automaticky. |
| [getMinValue()](#getMinValue--) | Zobrazuje minimální hodnotu na ose hodnot. |
| [setMinValue(double value)](#setMinValue-double-) | Zobrazuje minimální hodnotu na ose hodnot. |
| [isLogarithmic()](#isLogarithmic--) | Určuje, zda je typ měřítka osy hodnot logaritmický nebo ne. |
| [setLogarithmic(boolean value)](#setLogarithmic-boolean-) | Určuje, že je typ měřítka osy hodnot logaritmický nebo ne. |
| [getLogBase()](#getLogBase--) | Zobrazuje logaritmický základ. |
| [setLogBase(double value)](#setLogBase-double-) | Zobrazuje logaritmický základ. |
| [isPlotOrderReversed()](#isPlotOrderReversed--) | Určuje, zda MS PowerPoint vykresluje datové body od posledního k prvnímu. |
| [setPlotOrderReversed(boolean value)](#setPlotOrderReversed-boolean-) | Určuje, že MS PowerPoint vykresluje datové body od posledního k prvnímu. |
| [isVisible()](#isVisible--) | Určuje, zda je osa viditelná. |
| [setVisible(boolean value)](#setVisible-boolean-) | Určuje, že je osa viditelná. |
| [getMajorTickMark()](#getMajorTickMark--) | Zobrazuje typ hlavního značkovacího tahu pro zadanou osu. |
| [setMajorTickMark(int value)](#setMajorTickMark-int-) | Zobrazuje typ hlavního značkovacího tahu pro zadanou osu. |
| [getMinorTickMark()](#getMinorTickMark--) | Zobrazuje typ vedlejšího značkovacího tahu pro zadanou osu. |
| [setMinorTickMark(int value)](#setMinorTickMark-int-) | Zobrazuje typ vedlejšího značkovacího tahu pro zadanou osu. |
| [getTickLabelPosition()](#getTickLabelPosition--) | Zobrazuje polohu popisků značek na zadané ose. |
| [setTickLabelPosition(int value)](#setTickLabelPosition-int-) | Zobrazuje polohu popisků značek na zadané ose. |
| [getMajorUnitScale()](#getMajorUnitScale--) | Zobrazuje měřítko hlavní jednotky pro datumovou osu. |
| [setMajorUnitScale(int value)](#setMajorUnitScale-int-) | Zobrazuje měřítko hlavní jednotky pro datumovou osu. |
| [getMinorUnitScale()](#getMinorUnitScale--) | Zobrazuje měřítko hlavní jednotky pro datumovou osu. |
| [setMinorUnitScale(int value)](#setMinorUnitScale-int-) | Zobrazuje měřítko hlavní jednotky pro datumovou osu. |
| [getBaseUnitScale()](#getBaseUnitScale--) | Určuje nejmenší časovou jednotku, která je na datumové ose reprezentována. |
| [setBaseUnitScale(int value)](#setBaseUnitScale-int-) | Určuje nejmenší časovou jednotku, která je na datumové ose reprezentována. |
| [getMinorGridLinesFormat()](#getMinorGridLinesFormat--) | Zobrazuje formát vedlejších mřížkových čar na ose diagramu. |
| [getMajorGridLinesFormat()](#getMajorGridLinesFormat--) | Zobrazuje formát hlavních mřížkových čar na ose diagramu. |
| [getShowMinorGridLines()](#getShowMinorGridLines--) | Určuje, zda jsou zobrazeny vedlejší mřížkové čáry. |
| [getShowMajorGridLines()](#getShowMajorGridLines--) | Určuje, zda jsou zobrazeny hlavní mřížkové čáry. |
| [getFormat()](#getFormat--) | Zobrazuje formát osy. |
| [getTitle()](#getTitle--) | Získá název osy. |
| [getCrossType()](#getCrossType--) | Zobrazuje typ průniku na zadané ose, kde se kříží druhá osa. |
| [setCrossType(int value)](#setCrossType-int-) | Zobrazuje typ průniku na zadané ose, kde se kříží druhá osa. |
| [getPosition()](#getPosition--) | Zobrazuje polohu osy. |
| [setPosition(int value)](#setPosition-int-) | Zobrazuje polohu osy. |
| [hasTitle()](#hasTitle--) | Určuje, zda má osa viditelný název. |
| [setTitle(boolean value)](#setTitle-boolean-) | Určuje, že má osa viditelný název. |
| [getNumberFormat()](#getNumberFormat--) | Zobrazuje řetězec formátu pro popisky osy. |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | Zobrazuje řetězec formátu pro popisky osy. |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | Indikuje, zda je formát propojený se zdrojovými daty. |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | Indikuje, že je formát propojený se zdrojovými daty. |
| [getTickLabelRotationAngle()](#getTickLabelRotationAngle--) | Zobrazuje úhel otočení popisků značek Čtení/zápis float. |
| [setTickLabelRotationAngle(float value)](#setTickLabelRotationAngle-float-) | Zobrazuje úhel otočení popisků značek Čtení/zápis float. |
| [getTickLabelSpacing()](#getTickLabelSpacing--) | Určuje, kolik popisků značek přeskočit mezi zobrazenými popisky. |
| [setTickLabelSpacing(long value)](#setTickLabelSpacing-long-) | Určuje, kolik popisků značek přeskočit mezi zobrazenými popisky. |
| [isAutomaticTickLabelSpacing()](#isAutomaticTickLabelSpacing--) | Určuje automatickou hodnotu rozestupu popisků značek. |
| [setAutomaticTickLabelSpacing(boolean value)](#setAutomaticTickLabelSpacing-boolean-) | Určuje automatickou hodnotu rozestupu popisků značek. |
| [getTickMarksSpacing()](#getTickMarksSpacing--) | Určuje, kolik značek má být přeskočeno před vykreslením další. |
| [setTickMarksSpacing(long value)](#setTickMarksSpacing-long-) | Určuje, kolik značek má být přeskočeno před vykreslením další. |
| [isAutomaticTickMarksSpacing()](#isAutomaticTickMarksSpacing--) | Určuje automatickou hodnotu rozestupu značek. |
| [setAutomaticTickMarksSpacing(boolean value)](#setAutomaticTickMarksSpacing-boolean-) | Určuje automatickou hodnotu rozestupu značek. |
| [getLabelOffset()](#getLabelOffset--) | Určuje vzdálenost popisků od osy. |
| [setLabelOffset(int value)](#setLabelOffset-int-) | Určuje vzdálenost popisků od osy. |
| [getCategoryAxisType()](#getCategoryAxisType--) | Určuje typ osy kategorií. |
| [setCategoryAxisType(int value)](#setCategoryAxisType-int-) | Určuje typ osy kategorií. |
| [setCategoryAxisTypeAutomatically()](#setCategoryAxisTypeAutomatically--) | Nastavuje vlastnost IAxis.CategoryAxisType na hodnotu, která je automaticky určena na základě dat osy. |
| [getAggregationType()](#getAggregationType--) | Zobrazuje typ agregace osy kategorií (skupinování). |
| [setAggregationType(int value)](#setAggregationType-int-) | Zobrazuje typ agregace osy kategorií (skupinování). |
| [getBinWidth()](#getBinWidth--) | Určuje šířku binu, když je hodnota vlastnosti AggregationType nastavena na AxisAggregationType.ByBinWidth. |
| [setBinWidth(double value)](#setBinWidth-double-) | Určuje šířku binu, když je hodnota vlastnosti AggregationType nastavena na AxisAggregationType.ByBinWidth. |
| [getNumberOfBins()](#getNumberOfBins--) | Určuje počet binů, když je hodnota vlastnosti AggregationType nastavena na AxisAggregationType.ByNumberOfBins. |
| [setNumberOfBins(long value)](#setNumberOfBins-long-) | Určuje počet binů, když je hodnota vlastnosti AggregationType nastavena na AxisAggregationType.ByNumberOfBins. |
| [isOverflowBin()](#isOverflowBin--) | Určuje, zda je použita přetékací bin. |
| [setOverflowBin(boolean value)](#setOverflowBin-boolean-) | Určuje, že je použita přetékací bin. |
| [isAutomaticOverflowBin()](#isAutomaticOverflowBin--) | Určuje automatickou hodnotu přetékacího binu. |
| [setAutomaticOverflowBin(boolean value)](#setAutomaticOverflowBin-boolean-) | Určuje automatickou hodnotu přetékacího binu. |
| [getOverflowBin()](#getOverflowBin--) | Určuje vlastní hodnotu přetékacího binu. |
| [setOverflowBin(double value)](#setOverflowBin-double-) | Určuje vlastní hodnotu přetékacího binu. |
| [isUnderflowBin()](#isUnderflowBin--) | Určuje, zda je použita podtečná bin. |
| [setUnderflowBin(boolean value)](#setUnderflowBin-boolean-) | Určuje, že je použita podtečná bin. |
| [isAutomaticUnderflowBin()](#isAutomaticUnderflowBin--) | Určuje automatickou hodnotu podtečné bin. |
| [setAutomaticUnderflowBin(boolean value)](#setAutomaticUnderflowBin-boolean-) | Určuje automatickou hodnotu podtečné bin. |
| [getUnderflowBin()](#getUnderflowBin--) | Určuje vlastní hodnotu podtečné bin. |
| [setUnderflowBin(double value)](#setUnderflowBin-double-) | Určuje vlastní hodnotu podtečné bin. |

### getAxisBetweenCategories() {#getAxisBetweenCategories--}
```
public abstract boolean getAxisBetweenCategories()
```

Určuje, zda osa hodnot protíná osu kategorií mezi kategoriemi. Tato vlastnost platí jen pro osy kategorií a neplatí pro 3-D diagramy. Čtení/zápis boolean.

**Vrací:**
boolean

### setAxisBetweenCategories(boolean value) {#setAxisBetweenCategories-boolean-}
```
public abstract void setAxisBetweenCategories(boolean value)
```

Určuje, zda osa hodnot protíná osu kategorií mezi kategoriemi. Tato vlastnost platí jen pro osy kategorií a neplatí pro 3-D diagramy. Čtení/zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getCrossAt() {#getCrossAt--}
```
public abstract float getCrossAt()
```

Zobrazuje bod na ose, kde ji protichůdná osa protíná. Čtení/zápis float.

**Vrací:**
float

### setCrossAt(float value) {#setCrossAt-float-}
```
public abstract void setCrossAt(float value)
```

Zobrazuje bod na ose, kde ji protichůdná osa protíná. Čtení/zápis float.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |

### getDisplayUnit() {#getDisplayUnit--}
```
public abstract int getDisplayUnit()
```

Určuje měřítkovou hodnotu zobrazovacích jednotek pro osu hodnot. Čtení/zápis [DisplayUnitType](../../com.aspose.slides/displayunittype).

**Vrací:**
int

### setDisplayUnit(int value) {#setDisplayUnit-int-}
```
public abstract void setDisplayUnit(int value)
```

Určuje měřítkovou hodnotu zobrazovacích jednotek pro osu hodnot. Čtení/zápis [DisplayUnitType](../../com.aspose.slides/displayunittype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getActualMaxValue() {#getActualMaxValue--}
```
public abstract double getActualMaxValue()
```

Určuje skutečnou maximální hodnotu na ose. Nejprve zavolejte metodu IChart.ValidateChartLayout() pro získání skutečné hodnoty.

**Vrací:**
double

### getActualMinValue() {#getActualMinValue--}
```
public abstract double getActualMinValue()
```

Určuje skutečnou minimální hodnotu na ose. Nejprve zavolejte metodu IChart.ValidateChartLayout() pro získání skutečné hodnoty.

**Vrací:**
double

### getActualMajorUnit() {#getActualMajorUnit--}
```
public abstract double getActualMajorUnit()
```

Určuje skutečnou hlavní jednotku osy. Nejprve zavolejte metodu IChart.ValidateChartLayout() pro získání skutečné hodnoty.

**Vrací:**
double

### getActualMinorUnit() {#getActualMinorUnit--}
```
public abstract double getActualMinorUnit()
```

Určuje skutečnou vedlejší jednotku osy. Nejprve zavolejte metodu IChart.ValidateChartLayout() pro získání skutečné hodnoty.

**Vrací:**
double

### getActualMajorUnitScale() {#getActualMajorUnitScale--}
```
public abstract int getActualMajorUnitScale()
```

Určuje skutečné měřítko hlavní jednotky osy. Nejprve zavolejte metodu IChart.ValidateChartLayout() pro získání skutečné hodnoty.

**Vrací:**
int

### getActualMinorUnitScale() {#getActualMinorUnitScale--}
```
public abstract int getActualMinorUnitScale()
```

Určuje skutečné měřítko vedlejší jednotky osy. Nejprve zavolejte metodu IChart.ValidateChartLayout() pro získání skutečné hodnoty.

**Vrací:**
int

### isAutomaticMaxValue() {#isAutomaticMaxValue--}
```
public abstract boolean isAutomaticMaxValue()
```

Indikuje, zda je maximální hodnota přiřazena automaticky. Čtení/zápis boolean.

**Vrací:**
boolean

### setAutomaticMaxValue(boolean value) {#setAutomaticMaxValue-boolean-}
```
public abstract void setAutomaticMaxValue(boolean value)
```

Indikuje, že je maximální hodnota přiřazena automaticky. Čtení/zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getMaxValue() {#getMaxValue--}
```
public abstract double getMaxValue()
```

Zobrazuje maximální hodnotu na ose hodnot. Čtení/zápis double.

**Vrací:**
double

### setMaxValue(double value) {#setMaxValue-double-}
```
public abstract void setMaxValue(double value)
```

Zobrazuje maximální hodnotu na ose hodnot. Čtení/zápis double.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |

### getMinorUnit() {#getMinorUnit--}
```
public abstract double getMinorUnit()
```

Zobrazuje vedlejší jednotky pro datumovou nebo hodnotovou osu. Čtení/zápis double.

**Vrací:**
double

### setMinorUnit(double value) {#setMinorUnit-double-}
```
public abstract void setMinorUnit(double value)
```

Zobrazuje vedlejší jednotky pro datumovou nebo hodnotovou osu. Čtení/zápis double.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |

### isAutomaticMinorUnit() {#isAutomaticMinorUnit--}
```
public abstract boolean isAutomaticMinorUnit()
```

Indikuje, zda je vedlejší jednotka osy přiřazena automaticky. Čtení/zápis boolean.

**Vrací:**
boolean

### setAutomaticMinorUnit(boolean value) {#setAutomaticMinorUnit-boolean-}
```
public abstract void setAutomaticMinorUnit(boolean value)
```

Indikuje, že je vedlejší jednotka osy přiřazena automaticky. Čtení/zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getMajorUnit() {#getMajorUnit--}
```
public abstract double getMajorUnit()
```

Zobrazuje hlavní jednotky pro datumovou nebo hodnotovou osu. Čtení/zápis double.

**Vrací:**
double

### setMajorUnit(double value) {#setMajorUnit-double-}
```
public abstract void setMajorUnit(double value)
```

Zobrazuje hlavní jednotky pro datumovou nebo hodnotovou osu. Čtení/zápis double.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |

### isAutomaticMajorUnit() {#isAutomaticMajorUnit--}
```
public abstract boolean isAutomaticMajorUnit()
```

Indikuje, zda je hlavní jednotka osy přiřazena automaticky. Čtení/zápis boolean.

**Vrací:**
boolean
### setAutomaticMajorUnit(boolean value) {#setAutomaticMajorUnit-boolean-}
```
public abstract void setAutomaticMajorUnit(boolean value)
```

Indikuje, zda je hlavní jednotka osy přiřazena automaticky. Čtení/zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticMinValue() {#isAutomaticMinValue--}
```
public abstract boolean isAutomaticMinValue()
```

Indikuje, zda je minimální hodnota přiřazena automaticky. Čtení/zápis boolean.

**Návratová hodnota:**
boolean
### setAutomaticMinValue(boolean value) {#setAutomaticMinValue-boolean-}
```
public abstract void setAutomaticMinValue(boolean value)
```

Indikuje, zda je minimální hodnota přiřazena automaticky. Čtení/zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getMinValue() {#getMinValue--}
```
public abstract double getMinValue()
```

Reprezentuje minimální hodnotu na hodnotové ose. Čtení/zápis double.

**Návratová hodnota:**
double
### setMinValue(double value) {#setMinValue-double-}
```
public abstract void setMinValue(double value)
```

Reprezentuje minimální hodnotu na hodnotové ose. Čtení/zápis double.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |

### isLogarithmic() {#isLogarithmic--}
```
public abstract boolean isLogarithmic()
```

Reprezentuje, zda je typ měřítka hodnotové osy logaritmický nebo ne. Čtení/zápis boolean.

**Návratová hodnota:**
boolean
### setLogarithmic(boolean value) {#setLogarithmic-boolean-}
```
public abstract void setLogarithmic(boolean value)
```

Reprezentuje, zda je typ měřítka hodnotové osy logaritmický nebo ne. Čtení/zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getLogBase() {#getLogBase--}
```
public abstract double getLogBase()
```

Reprezentuje logaritmickou základnu. Výchozí hodnota je 10. Čtení/zápis double.

**Návratová hodnota:**
double
### setLogBase(double value) {#setLogBase-double-}
```
public abstract void setLogBase(double value)
```

Reprezentuje logaritmickou základnu. Výchozí hodnota je 10. Čtení/zápis double.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |

### isPlotOrderReversed() {#isPlotOrderReversed--}
```
public abstract boolean isPlotOrderReversed()
```

Reprezentuje, zda MS PowerPoint vykresluje datové body od posledního k prvnímu. Čtení/zápis boolean.

**Návratová hodnota:**
boolean
### setPlotOrderReversed(boolean value) {#setPlotOrderReversed-boolean-}
```
public abstract void setPlotOrderReversed(boolean value)
```

Reprezentuje, zda MS PowerPoint vykresluje datové body od posledního k prvnímu. Čtení/zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

Reprezentuje, zda je osa viditelná. Čtení/zápis boolean.

**Návratová hodnota:**
boolean
### setVisible(boolean value) {#setVisible-boolean-}
```
public abstract void setVisible(boolean value)
```

Reprezentuje, zda je osa viditelná. Čtení/zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getMajorTickMark() {#getMajorTickMark--}
```
public abstract int getMajorTickMark()
```

Reprezentuje typ hlavního značkovacího čáry pro zadanou osu. Čtení/zápis [TickMarkType](../../com.aspose.slides/tickmarktype).

**Návratová hodnota:**
int
### setMajorTickMark(int value) {#setMajorTickMark-int-}
```
public abstract void setMajorTickMark(int value)
```

Reprezentuje typ hlavního značkovacího čáry pro zadanou osu. Čtení/zápis [TickMarkType](../../com.aspose.slides/tickmarktype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getMinorTickMark() {#getMinorTickMark--}
```
public abstract int getMinorTickMark()
```

Reprezentuje typ menšího značkovacího čáry pro zadanou osu. Čtení/zápis [TickMarkType](../../com.aspose.slides/tickmarktype).

**Návratová hodnota:**
int
### setMinorTickMark(int value) {#setMinorTickMark-int-}
```
public abstract void setMinorTickMark(int value)
```

Reprezentuje typ menšího značkovacího čáry pro zadanou osu. Čtení/zápis [TickMarkType](../../com.aspose.slides/tickmarktype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getTickLabelPosition() {#getTickLabelPosition--}
```
public abstract int getTickLabelPosition()
```

Reprezentuje polohu popisků značek na zadané ose. Čtení/zápis [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**Návratová hodnota:**
int
### setTickLabelPosition(int value) {#setTickLabelPosition-int-}
```
public abstract void setTickLabelPosition(int value)
```

Reprezentuje polohu popisků značek na zadané ose. Čtení/zápis [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getMajorUnitScale() {#getMajorUnitScale--}
```
public abstract int getMajorUnitScale()
```

Reprezentuje hlavní jednotkovou škálu pro datumovou osu. Čtení/zápis [TimeUnitType](../../com.aspose.slides/timeunittype).

**Návratová hodnota:**
int
### setMajorUnitScale(int value) {#setMajorUnitScale-int-}
```
public abstract void setMajorUnitScale(int value)
```

Reprezentuje hlavní jednotkovou škálu pro datumovou osu. Čtení/zápis [TimeUnitType](../../com.aspose.slides/timeunittype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getMinorUnitScale() {#getMinorUnitScale--}
```
public abstract int getMinorUnitScale()
```

Reprezentuje hlavní jednotkovou škálu pro datumovou osu. Čtení/zápis [TimeUnitType](../../com.aspose.slides/timeunittype).

**Návratová hodnota:**
int
### setMinorUnitScale(int value) {#setMinorUnitScale-int-}
```
public abstract void setMinorUnitScale(int value)
```

Reprezentuje hlavní jednotkovou škálu pro datumovou osu. Čtení/zápis [TimeUnitType](../../com.aspose.slides/timeunittype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getBaseUnitScale() {#getBaseUnitScale--}
```
public abstract int getBaseUnitScale()
```

Určuje nejmenší časovou jednotku, která je reprezentována na datumové ose. Čtení/zápis [TimeUnitType](../../com.aspose.slides/timeunittype).

**Návratová hodnota:**
int
### setBaseUnitScale(int value) {#setBaseUnitScale-int-}
```
public abstract void setBaseUnitScale(int value)
```

Určuje nejmenší časovou jednotku, která je reprezentována na datumové ose. Čtení/zápis [TimeUnitType](../../com.aspose.slides/timeunittype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getMinorGridLinesFormat() {#getMinorGridLinesFormat--}
```
public abstract IChartLinesFormat getMinorGridLinesFormat()
```

Reprezentuje formát menších mřížkových čar na ose grafu. Pouze ke čtení [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**Návratová hodnota:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### getMajorGridLinesFormat() {#getMajorGridLinesFormat--}
```
public abstract IChartLinesFormat getMajorGridLinesFormat()
```

Reprezentuje formát hlavních mřížkových čar na ose grafu. Pouze ke čtení [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**Návratová hodnota:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### getShowMinorGridLines() {#getShowMinorGridLines--}
```
public abstract boolean getShowMinorGridLines()
```

Reprezentuje, zda jsou menší mřížkové čáry zobrazeny. Pouze ke čtení boolean.

**Návratová hodnota:**
boolean
### getShowMajorGridLines() {#getShowMajorGridLines--}
```
public abstract boolean getShowMajorGridLines()
```

Reprezentuje, zda jsou hlavní mřížkové čáry zobrazeny. Pouze ke čtení boolean.

**Návratová hodnota:**
boolean
### getFormat() {#getFormat--}
```
public abstract IAxisFormat getFormat()
```

Reprezentuje formát osy. Pouze ke čtení [IAxisFormat](../../com.aspose.slides/iaxisformat).

**Návratová hodnota:**
[IAxisFormat](../../com.aspose.slides/iaxisformat)
### getTitle() {#getTitle--}
```
public abstract IChartTitle getTitle()
```

Získá název osy. Pouze ke čtení [IChartTitle](../../com.aspose.slides/icharttitle).

**Návratová hodnota:**
[IChartTitle](../../com.aspose.slides/icharttitle)
### getCrossType() {#getCrossType--}
```
public abstract int getCrossType()
```

Reprezentuje CrossType na zadané ose, kde se protíná druhá osa. Čtení/zápis [CrossesType](../../com.aspose.slides/crossestype).

**Návratová hodnota:**
int
### setCrossType(int value) {#setCrossType-int-}
```
public abstract void setCrossType(int value)
```

Reprezentuje CrossType na zadané ose, kde se protíná druhá osa. Čtení/zápis [CrossesType](../../com.aspose.slides/crossestype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

Reprezentuje pozici osy. Čtení/zápis [AxisPositionType](../../com.aspose.slides/axispositiontype).

**Návratová hodnota:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

Reprezentuje pozici osy. Čtení/zápis [AxisPositionType](../../com.aspose.slides/axispositiontype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### hasTitle() {#hasTitle--}
```
public abstract boolean hasTitle()
```

Určuje, zda osa má viditelný název. Čtení/zápis boolean.

**Návratová hodnota:**
boolean
### setTitle(boolean value) {#setTitle-boolean-}
```
public abstract void setTitle(boolean value)
```

Určuje, zda osa má viditelný název. Čtení/zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public abstract String getNumberFormat()
```

Reprezentuje řetězec formátu pro popisky osy. Čtení/zápis String.

**Návratová hodnota:**
java.lang.String
### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public abstract void setNumberFormat(String value)
```

Reprezentuje řetězec formátu pro popisky osy. Čtení/zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public abstract boolean isNumberFormatLinkedToSource()
```

Indikuje, zda je formát propojen se zdrojovými daty. Čtení/zápis boolean.

**Návratová hodnota:**
boolean
### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public abstract void setNumberFormatLinkedToSource(boolean value)
```

Indikuje, zda je formát propojen se zdrojovými daty. Čtení/zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getTickLabelRotationAngle() {#getTickLabelRotationAngle--}
```
public abstract float getTickLabelRotationAngle()
```

Reprezentuje úhel otočení popisků značek. Čtení/zápis float.

**Návratová hodnota:**
float
### setTickLabelRotationAngle(float value) {#setTickLabelRotationAngle-float-}
```
public abstract void setTickLabelRotationAngle(float value)
```

Reprezentuje úhel otočení popisků značek. Čtení/zápis float.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |

### getTickLabelSpacing() {#getTickLabelSpacing--}
```
public abstract long getTickLabelSpacing()
```

Určuje, kolik popisků značek se má přeskočit mezi zobrazenými popisky. Čtení/zápis long.

**Návratová hodnota:**
long
### setTickLabelSpacing(long value) {#setTickLabelSpacing-long-}
```
public abstract void setTickLabelSpacing(long value)
```

Určuje, kolik popisků značek se má přeskočit mezi zobrazenými popisky. Čtení/zápis long.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickLabelSpacing() {#isAutomaticTickLabelSpacing--}
```
public abstract boolean isAutomaticTickLabelSpacing()
```

Určuje automatickou hodnotu mezery mezi popisky značek. Pokud je false: použije se vlastnost TickLabelSpacing. Čtení/zápis boolean.

**Návratová hodnota:**
boolean
### setAutomaticTickLabelSpacing(boolean value) {#setAutomaticTickLabelSpacing-boolean-}
```
public abstract void setAutomaticTickLabelSpacing(boolean value)
```

Určuje automatickou hodnotu mezery mezi popisky značek. Pokud je false: použije se vlastnost TickLabelSpacing. Čtení/zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getTickMarksSpacing() {#getTickMarksSpacing--}
```
public abstract long getTickMarksSpacing()
```

Určuje, kolik značkovacích čar se má přeskočit před vykreslením další. Používá se pro osu kategorií nebo řad. Čtení/zápis int.

**Návratová hodnota:**
long
### setTickMarksSpacing(long value) {#setTickMarksSpacing-long-}
```
public abstract void setTickMarksSpacing(long value)
```

Určuje, kolik značkovacích čar se má přeskočit před vykreslením další. Používá se pro osu kategorií nebo řad. Čtení/zápis int.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickMarksSpacing() {#isAutomaticTickMarksSpacing--}
```
public abstract boolean isAutomaticTickMarksSpacing()
```

Určuje automatickou hodnotu mezery mezi značkovacími čarami. Pokud je false: použije se vlastnost TickMarksSpacing. Čtení/zápis boolean.

**Návratová hodnota:**
boolean
### setAutomaticTickMarksSpacing(boolean value) {#setAutomaticTickMarksSpacing-boolean-}
```
public abstract void setAutomaticTickMarksSpacing(boolean value)
```

Určuje automatickou hodnotu mezery mezi značkovacími čarami. Pokud je false: použije se vlastnost TickMarksSpacing. Čtení/zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getLabelOffset() {#getLabelOffset--}
```
public abstract int getLabelOffset()
```

Určuje vzdálenost popisků od osy. Používá se pro osu kategorií nebo datumovou osu. Hodnota musí být mezi 0 % a 1000 %. Čtení/zápis int.

**Návratová hodnota:**
int
### setLabelOffset(int value) {#setLabelOffset-int-}
```
public abstract void setLabelOffset(int value)
```

Určuje vzdálenost popisků od osy. Používá se pro osu kategorií nebo datumovou osu. Hodnota musí být mezi 0 % a 1000 %. Čtení/zápis int.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getCategoryAxisType() {#getCategoryAxisType--}
```
public abstract int getCategoryAxisType()
```

Určuje typ osy kategorií. Čtení/zápis [CategoryAxisType](../../com.aspose.slides/categoryaxistype)(\#getCategoryAxisType.getCategoryAxisType/\#setCategoryAxisType(int).setCategoryAxisType(int)).

**Návratová hodnota:**
int
### setCategoryAxisType(int value) {#setCategoryAxisType-int-}
```
public abstract void setCategoryAxisType(int value)
```

Určuje typ osy kategorií. Čtení/zápis [CategoryAxisType](../../com.aspose.slides/categoryaxistype)(\#getCategoryAxisType.getCategoryAxisType/\#setCategoryAxisType(int).setCategoryAxisType(int)).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### setCategoryAxisTypeAutomatically() {#setCategoryAxisTypeAutomatically--}
```
public abstract void setCategoryAxisTypeAutomatically()
```

Nastaví vlastnost IAxis.CategoryAxisType na hodnotu, která je automaticky určena na základě dat osy.

### getAggregationType() {#getAggregationType--}
```
public abstract int getAggregationType()
```

Reprezentuje typ agregace osy kategorií (seskupování). Používá se pro kategorii. Používá se pouze se sériemi Histogram nebo HistogramPareto.

**Návratová hodnota:**
int
### setAggregationType(int value) {#setAggregationType-int-}
```
public abstract void setAggregationType(int value)
```

Reprezentuje typ agregace osy kategorií (seskupování). Používá se pro kategorii. Používá se pouze se sériemi Histogram nebo HistogramPareto.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |
### getBinWidth() {#getBinWidth--}
```
public abstract double getBinWidth()
```

Určuje šířku koše, když je hodnota vlastnosti AggregationType nastavena na AxisAggregationType.ByBinWidth. Používá se pro kategoriové osy. Používá se pouze se sériemi Histogram nebo HistogramPareto.

**Vrací:**
double
### setBinWidth(double value) {#setBinWidth-double-}
```
public abstract void setBinWidth(double value)
```

Určuje šířku koše, když je hodnota vlastnosti AggregationType nastavena na AxisAggregationType.ByBinWidth. Používá se pro kategoriové osy. Používá se pouze se sériemi Histogram nebo HistogramPareto.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |

### getNumberOfBins() {#getNumberOfBins--}
```
public abstract long getNumberOfBins()
```

Určuje počet košů, když je hodnota vlastnosti AggregationType nastavena na AxisAggregationType.ByNumberOfBins. Používá se pro kategoriové osy. Používá se pouze se sériemi Histogram nebo HistogramPareto.

**Vrací:**
long
### setNumberOfBins(long value) {#setNumberOfBins-long-}
```
public abstract void setNumberOfBins(long value)
```

Určuje počet košů, když je hodnota vlastnosti AggregationType nastavena na AxisAggregationType.ByNumberOfBins. Používá se pro kategoriové osy. Používá se pouze se sériemi Histogram nebo HistogramPareto.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | long |  |

### isOverflowBin() {#isOverflowBin--}
```
public abstract boolean isOverflowBin()
```

Určuje, zda je použita přetečná koš. K úpravě hodnoty přetečného koše použijte IsAutomaticOverflowBin a OverflowBin.

**Vrací:**
boolean
### setOverflowBin(boolean value) {#setOverflowBin-boolean-}
```
public abstract void setOverflowBin(boolean value)
```

Určuje, zda je použita přetečná koš. K úpravě hodnoty přetečného koše použijte IsAutomaticOverflowBin a OverflowBin.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticOverflowBin() {#isAutomaticOverflowBin--}
```
public abstract boolean isAutomaticOverflowBin()
```

Určuje automatickou hodnotu přetečného koše. Pokud je false: použijte vlastnost OverflowBin.

**Vrací:**
boolean
### setAutomaticOverflowBin(boolean value) {#setAutomaticOverflowBin-boolean-}
```
public abstract void setAutomaticOverflowBin(boolean value)
```

Určuje automatickou hodnotu přetečného koše. Pokud je false: použijte vlastnost OverflowBin.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getOverflowBin() {#getOverflowBin--}
```
public abstract double getOverflowBin()
```

Určuje vlastní hodnotu přetečného koše. Používá se, když je vlastnost IsAutomaticOverflowBin nastavena na false a vlastnost IsOverflowBin je true.

**Vrací:**
double
### setOverflowBin(double value) {#setOverflowBin-double-}
```
public abstract void setOverflowBin(double value)
```

Určuje vlastní hodnotu přetečného koše. Používá se, když je vlastnost IsAutomaticOverflowBin nastavena na false a vlastnost IsOverflowBin je true.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |

### isUnderflowBin() {#isUnderflowBin--}
```
public abstract boolean isUnderflowBin()
```

Určuje, zda je použita podtečná koš. K úpravě hodnoty podtečného koše použijte IsAutomaticUnderflowBin a UnderflowBin.

**Vrací:**
boolean
### setUnderflowBin(boolean value) {#setUnderflowBin-boolean-}
```
public abstract void setUnderflowBin(boolean value)
```

Určuje, zda je použita podtečná koš. K úpravě hodnoty podtečného koše použijte IsAutomaticUnderflowBin a UnderflowBin.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticUnderflowBin() {#isAutomaticUnderflowBin--}
```
public abstract boolean isAutomaticUnderflowBin()
```

Určuje automatickou hodnotu podtečného koše. Pokud je false: použijte vlastnost UnderflowBin.

**Vrací:**
boolean
### setAutomaticUnderflowBin(boolean value) {#setAutomaticUnderflowBin-boolean-}
```
public abstract void setAutomaticUnderflowBin(boolean value)
```

Určuje automatickou hodnotu podtečného koše. Pokud je false: použijte vlastnost UnderflowBin.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getUnderflowBin() {#getUnderflowBin--}
```
public abstract double getUnderflowBin()
```

Určuje vlastní hodnotu podtečného koše. Používá se, když je vlastnost IsAutomaticUnderflowBin nastavena na false a vlastnost IsUnderflowBin je true.

**Vrací:**
double
### setUnderflowBin(double value) {#setUnderflowBin-double-}
```
public abstract void setUnderflowBin(double value)
```

Určuje vlastní hodnotu podtečného koše. Používá se, když je vlastnost IsAutomaticUnderflowBin nastavena na false a vlastnost IsUnderflowBin je true.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |