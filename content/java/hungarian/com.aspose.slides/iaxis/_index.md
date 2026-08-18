---
title: IAxis
second_title: Aspose.Slides Java API hivatkozás
description: Lefedi azt az objektumot, amely egy diagram tengelyt képvisel.
type: docs
url: /hu/com.aspose.slides/iaxis/
---
**Minden megvalósított interfész:**
[com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer)
```
public interface IAxis extends IFormattedTextContainer
```

Elkapsolja azt az objektumot, amely egy diagram tengelyét képviseli.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getAxisBetweenCategories()](#getAxisBetweenCategories--) | Jelzi, hogy az értéktengely átszeli-e a kategóriatengelyt a kategóriák között. |
| [setAxisBetweenCategories(boolean value)](#setAxisBetweenCategories-boolean-) | Jelzi, hogy az értéktengely átszeli-e a kategóriatengelyt a kategóriák között. |
| [getCrossAt()](#getCrossAt--) | Jelzi a pontot a tengelyen, ahol a merőleges tengely áthalad. |
| [setCrossAt(float value)](#setCrossAt-float-) | Jelzi a pontot a tengelyen, ahol a merőleges tengely áthalad. |
| [getDisplayUnit()](#getDisplayUnit--) | Megadja a megjelenítési egységek léptékváltozó értékét az értéktengelyhez. |
| [setDisplayUnit(int value)](#setDisplayUnit-int-) | Megadja a megjelenítési egységek léptékváltozó értékét az értéktengelyhez. |
| [getActualMaxValue()](#getActualMaxValue--) | Megadja a tengely tényleges legnagyobb értékét. |
| [getActualMinValue()](#getActualMinValue--) | Megadja a tengely tényleges legkisebb értékét. |
| [getActualMajorUnit()](#getActualMajorUnit--) | Megadja a tengely tényleges főegységét. |
| [getActualMinorUnit()](#getActualMinorUnit--) | Megadja a tengely tényleges alsegységét. |
| [getActualMajorUnitScale()](#getActualMajorUnitScale--) | Megadja a tengely tényleges főegység léptékét. |
| [getActualMinorUnitScale()](#getActualMinorUnitScale--) | Megadja a tengely tényleges alsegység léptékét. |
| [isAutomaticMaxValue()](#isAutomaticMaxValue--) | Jelzi, hogy a maximális érték automatikusan van-e hozzárendelve. |
| [setAutomaticMaxValue(boolean value)](#setAutomaticMaxValue-boolean-) | Jelzi, hogy a maximális érték automatikusan van-e hozzárendelve. |
| [getMaxValue()](#getMaxValue--) | Jelzi a maximális értéket az értéktengelyen. |
| [setMaxValue(double value)](#setMaxValue-double-) | Jelzi a maximális értéket az értéktengelyen. |
| [getMinorUnit()](#getMinorUnit--) | Jelzi a kisebb egységeket a dátum- vagy értéktengelyhez. |
| [setMinorUnit(double value)](#setMinorUnit-double-) | Jelzi a kisebb egységeket a dátum- vagy értéktengelyhez. |
| [isAutomaticMinorUnit()](#isAutomaticMinorUnit--) | Jelzi, hogy a tengely alegysége automatikusan van-e hozzárendelve. |
| [setAutomaticMinorUnit(boolean value)](#setAutomaticMinorUnit-boolean-) | Jelzi, hogy a tengely alegysége automatikusan van-e hozzárendelve. |
| [getMajorUnit()](#getMajorUnit--) | Jelzi a főegységeket a dátum- vagy értéktengelyhez. |
| [setMajorUnit(double value)](#setMajorUnit-double-) | Jelzi a főegységeket a dátum- vagy értéktengelyhez. |
| [isAutomaticMajorUnit()](#isAutomaticMajorUnit--) | Jelzi, hogy a tengely főegysége automatikusan van-e hozzárendelve. |
| [setAutomaticMajorUnit(boolean value)](#setAutomaticMajorUnit-boolean-) | Jelzi, hogy a tengely főegysége automatikusan van-e hozzárendelve. |
| [isAutomaticMinValue()](#isAutomaticMinValue--) | Jelzi, hogy a minimális érték automatikusan van-e hozzárendelve. |
| [setAutomaticMinValue(boolean value)](#setAutomaticMinValue-boolean-) | Jelzi, hogy a minimális érték automatikusan van-e hozzárendelve. |
| [getMinValue()](#getMinValue--) | Jelzi a minimális értéket az értéktengelyen. |
| [setMinValue(double value)](#setMinValue-double-) | Jelzi a minimális értéket az értéktengelyen. |
| [isLogarithmic()](#isLogarithmic--) | Jelzi, hogy az értéktengely skálatípusa logaritmikus-e vagy sem. |
| [setLogarithmic(boolean value)](#setLogarithmic-boolean-) | Jelzi, hogy az értéktengely skálatípusa logaritmikus-e vagy sem. |
| [getLogBase()](#getLogBase--) | Jelzi a logaritmikus alapot. |
| [setLogBase(double value)](#setLogBase-double-) | Jelzi a logaritmikus alapot. |
| [isPlotOrderReversed()](#isPlotOrderReversed--) | Jelzi, hogy a MS PowerPoint az adatpontokat az utolsótól az elsőig ábrázolja. |
| [setPlotOrderReversed(boolean value)](#setPlotOrderReversed-boolean-) | Jelzi, hogy a MS PowerPoint az adatpontokat az utolsótól az elsőig ábrázolja. |
| [isVisible()](#isVisible--) | Jelzi, hogy a tengely látható-e. |
| [setVisible(boolean value)](#setVisible-boolean-) | Jelzi, hogy a tengely látható-e. |
| [getMajorTickMark()](#getMajorTickMark--) | Jelzi a megadott tengely fő jelölőjelet típusát. |
| [setMajorTickMark(int value)](#setMajorTickMark-int-) | Jelzi a megadott tengely fő jelölőjelet típusát. |
| [getMinorTickMark()](#getMinorTickMark--) | Jelzi a megadott tengely al jelölőjelet típusát. |
| [setMinorTickMark(int value)](#setMinorTickMark-int-) | Jelzi a megadott tengely al jelölőjelet típusát. |
| [getTickLabelPosition()](#getTickLabelPosition--) | Jelzi a jelölőjel címkéinek pozícióját a megadott tengelyen. |
| [setTickLabelPosition(int value)](#setTickLabelPosition-int-) | Jelzi a jelölőjel címkéinek pozícióját a megadott tengelyen. |
| [getMajorUnitScale()](#getMajorUnitScale--) | Jelzi a főegység léptékét a dátumtengelyen. |
| [setMajorUnitScale(int value)](#setMajorUnitScale-int-) | Jelzi a főegység léptékét a dátumtengelyen. |
| [getMinorUnitScale()](#getMinorUnitScale--) | Jelzi a főegység léptékét a dátumtengelyen. |
| [setMinorUnitScale(int value)](#setMinorUnitScale-int-) | Jelzi a főegység léptékét a dátumtengelyen. |
| [getBaseUnitScale()](#getBaseUnitScale--) | Megadja a legkisebb időegységet, amely a dátumtengelyen megjelenik. |
| [setBaseUnitScale(int value)](#setBaseUnitScale-int-) | Megadja a legkisebb időegységet, amely a dátumtengelyen megjelenik. |
| [getMinorGridLinesFormat()](#getMinorGridLinesFormat--) | Jelzi a kisebb rácsvonalak formátumát egy diagramtengelyen. |
| [getMajorGridLinesFormat()](#getMajorGridLinesFormat--) | Jelzi a fő rácsvonalak formátumát egy diagramtengelyen. |
| [getShowMinorGridLines()](#getShowMinorGridLines--) | Jelzi, hogy a kisebb rácsvonalak megjelennek-e. |
| [getShowMajorGridLines()](#getShowMajorGridLines--) | Jelzi, hogy a fő rácsvonalak megjelennek-e. |
| [getFormat()](#getFormat--) | Jelzi a tengely formátumát. |
| [getTitle()](#getTitle--) | Lekéri a tengely címét. |
| [getCrossType()](#getCrossType--) | Jelzi a CrossType-ot a megadott tengelyen, ahol a másik tengely keresztezi. |
| [setCrossType(int value)](#setCrossType-int-) | Jelzi a CrossType-ot a megadott tengelyen, ahol a másik tengely keresztezi. |
| [getPosition()](#getPosition--) | Jelzi a tengely pozícióját. |
| [setPosition(int value)](#setPosition-int-) | Jelzi a tengely pozícióját. |
| [hasTitle()](#hasTitle--) | Megállapítja, hogy a tengelynek látható címe van-e. |
| [setTitle(boolean value)](#setTitle-boolean-) | Megállapítja, hogy a tengelynek látható címe van-e. |
| [getNumberFormat()](#getNumberFormat--) | Jelzi a formátum karakterláncot a tengelycímkékhez. |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | Jelzi a formátum karakterláncot a tengelycímkékhez. |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | Jelzi, hogy a formátum összekapcsolt forrásadatokból származik-e. |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | Jelzi, hogy a formátum összekapcsolt forrásadatokból származik-e. |
| [getTickLabelRotationAngle()](#getTickLabelRotationAngle--) | Jelzi a jelölőcímkék forgatási szögét. Olvasás/írás float. |
| [setTickLabelRotationAngle(float value)](#setTickLabelRotationAngle-float-) | Jelzi a jelölőcímkék forgatási szögét. Olvasás/írás float. |
| [getTickLabelSpacing()](#getTickLabelSpacing--) | Megadja, hány jelölőcímkét kell kihagyni a megjelenő címke között. |
| [setTickLabelSpacing(long value)](#setTickLabelSpacing-long-) | Megadja, hány jelölőcímkét kell kihagyni a megjelenő címke között. |
| [isAutomaticTickLabelSpacing()](#isAutomaticTickLabelSpacing--) | Megadja az automatikus jelölőcímke távolságértéket. |
| [setAutomaticTickLabelSpacing(boolean value)](#setAutomaticTickLabelSpacing-boolean-) | Megadja az automatikus jelölőcímke távolságértéket. |
| [getTickMarksSpacing()](#getTickMarksSpacing--) | Megadja, hány jelölőjel kerül kihagyásra, mielőtt a következő megjelenik. |
| [setTickMarksSpacing(long value)](#setTickMarksSpacing-long-) | Megadja, hány jelölőjel kerül kihagyásra, mielőtt a következő megjelenik. |
| [isAutomaticTickMarksSpacing()](#isAutomaticTickMarksSpacing--) | Megadja az automatikus jelölőjelek távolságértékét. |
| [setAutomaticTickMarksSpacing(boolean value)](#setAutomaticTickMarksSpacing-boolean-) | Megadja az automatikus jelölőjelek távolságértékét. |
| [getLabelOffset()](#getLabelOffset--) | Megadja a címkék távolságát a tengelytől. |
| [setLabelOffset(int value)](#setLabelOffset-int-) | Megadja a címkék távolságát a tengelytől. |
| [getCategoryAxisType()](#getCategoryAxisType--) | Megadja a kategóriatengely típusát. |
| [setCategoryAxisType(int value)](#setCategoryAxisType-int-) | Megadja a kategóriatengely típusát. |
| [setCategoryAxisTypeAutomatically()](#setCategoryAxisTypeAutomatically--) | Beállítja az IAxis.CategoryAxisType tulajdonságot egy értékkel, amely a tengelyadatok alapján automatikusan kerül meghatározásra. |
| [getAggregationType()](#getAggregationType--) | Jelzi a kategóriatengely aggregációs típusát (csoportosítás). |
| [setAggregationType(int value)](#setAggregationType-int-) | Jelzi a kategóriatengely aggregációs típusát (csoportosítás). |
| [getBinWidth()](#getBinWidth--) | Megadja a bin szélességét, amikor az AggregationType tulajdonság értéke AxisAggregationType.ByBinWidth. |
| [setBinWidth(double value)](#setBinWidth-double-) | Megadja a bin szélességét, amikor az AggregationType tulajdonság értéke AxisAggregationType.ByBinWidth. |
| [getNumberOfBins()](#getNumberOfBins--) | Megadja a binok számát, amikor az AggregationType tulajdonság értéke AxisAggregationType.ByNumberOfBins. |
| [setNumberOfBins(long value)](#setNumberOfBins-long-) | Megadja a binok számát, amikor az AggregationType tulajdonság értéke AxisAggregationType.ByNumberOfBins. |
| [isOverflowBin()](#isOverflowBin--) | Jelzi, hogy alkalmazásra került-e a túlcsordulási bin. |
| [setOverflowBin(boolean value)](#setOverflowBin-boolean-) | Jelzi, hogy alkalmazásra került-e a túlcsordulási bin. |
| [isAutomaticOverflowBin()](#isAutomaticOverflowBin--) | Megadja az automatikus túlcsordulási bin értékét. |
| [setAutomaticOverflowBin(boolean value)](#setAutomaticOverflowBin-boolean-) | Megadja az automatikus túlcsordulási bin értékét. |
| [getOverflowBin()](#getOverflowBin--) | Megadja a túlcsordulási bin egyéni értékét. |
| [setOverflowBin(double value)](#setOverflowBin-double-) | Megadja a túlcsordulási bin egyéni értékét. |
| [isUnderflowBin()](#isUnderflowBin--) | Jelzi, hogy alkalmazásra került-e az alcsordulási bin. |
| [setUnderflowBin(boolean value)](#setUnderflowBin-boolean-) | Jelzi, hogy alkalmazásra került-e az alcsordulási bin. |
| [isAutomaticUnderflowBin()](#isAutomaticUnderflowBin--) | Megadja az automatikus alcsordulási bin értékét. |
| [setAutomaticUnderflowBin(boolean value)](#setAutomaticUnderflowBin-boolean-) | Megadja az automatikus alcsordulási bin értékét. |
| [getUnderflowBin()](#getUnderflowBin--) | Megadja az alcsordulási bin egyéni értékét. |
| [setUnderflowBin(double value)](#setUnderflowBin-double-) | Megadja az alcsordulási bin egyéni értékét. |

### getAxisBetweenCategories() {#getAxisBetweenCategories--}
```
public abstract boolean getAxisBetweenCategories()
```

Jelzi, hogy az értéktengely átszeli-e a kategóriatengelyt a kategóriák között. Ez a tulajdonság csak kategóriatengelyekre vonatkozik, és nem érvényes 3D diagramokra. Olvasás/írás boolean.

**Visszatér:**
boolean

### setAxisBetweenCategories(boolean value) {#setAxisBetweenCategories-boolean-}
```
public abstract void setAxisBetweenCategories(boolean value)
```

Jelzi, hogy az értéktengely átszeli-e a kategóriatengelyt a kategóriák között. Ez a tulajdonság csak kategóriatengelyekre vonatkozik, és nem érvényes 3D diagramokra. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getCrossAt() {#getCrossAt--}
```
public abstract float getCrossAt()
```

Jelzi a pontot a tengelyen, ahol a merőleges tengely áthalad. Olvasás/írás float.

**Visszatér:**
float

### setCrossAt(float value) {#setCrossAt-float-}
```
public abstract void setCrossAt(float value)
```

Jelzi a pontot a tengelyen, ahol a merőleges tengely áthalad. Olvasás/írás float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getDisplayUnit() {#getDisplayUnit--}
```
public abstract int getDisplayUnit()
```

Megadja a megjelenítési egységek léptékértékét az értéktengelyhez. Olvasás/írás [DisplayUnitType](../../com.aspose.slides/displayunittype).

**Visszatér:**
int

### setDisplayUnit(int value) {#setDisplayUnit-int-}
```
public abstract void setDisplayUnit(int value)
```

Megadja a megjelenítési egységek léptékértékét az értéktengelyhez. Olvasás/írás [DisplayUnitType](../../com.aspose.slides/displayunittype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getActualMaxValue() {#getActualMaxValue--}
```
public abstract double getActualMaxValue()
```

Megadja a tengely tényleges legnagyobb értékét. Hívja meg előzőleg az IChart.ValidateChartLayout() metódust a tényleges érték lekéréséhez.

**Visszatér:**
double

### getActualMinValue() {#getActualMinValue--}
```
public abstract double getActualMinValue()
```

Megadja a tengely tényleges legkisebb értékét. Hívja meg előzőleg az IChart.ValidateChartLayout() metódust a tényleges érték lekéréséhez.

**Visszatér:**
double

### getActualMajorUnit() {#getActualMajorUnit--}
```
public abstract double getActualMajorUnit()
```

Megadja a tengely tényleges főegységét. Hívja meg előzőleg az IChart.ValidateChartLayout() metódust a tényleges érték lekéréséhez.

**Visszatér:**
double

### getActualMinorUnit() {#getActualMinorUnit--}
```
public abstract double getActualMinorUnit()
```

Megadja a tengely tényleges alsegységét. Hívja meg előzőleg az IChart.ValidateChartLayout() metódust a tényleges érték lekéréséhez.

**Visszatér:**
double

### getActualMajorUnitScale() {#getActualMajorUnitScale--}
```
public abstract int getActualMajorUnitScale()
```

Megadja a tengely tényleges főegység léptékét. Hívja meg előzőleg az IChart.ValidateChartLayout() metódust a tényleges érték lekéréséhez.

**Visszatér:**
int

### getActualMinorUnitScale() {#getActualMinorUnitScale--}
```
public abstract int getActualMinorUnitScale()
```

Megadja a tengely tényleges alsegység léptékét. Hívja meg előzőleg az IChart.ValidateChartLayout() metódust a tényleges érték lekéréséhez.

**Visszatér:**
int

### isAutomaticMaxValue() {#isAutomaticMaxValue--}
```
public abstract boolean isAutomaticMaxValue()
```

Jelzi, hogy a maximális érték automatikusan van-e hozzárendelve. Olvasás/írás boolean.

**Visszatér:**
boolean

### setAutomaticMaxValue(boolean value) {#setAutomaticMaxValue-boolean-}
```
public abstract void setAutomaticMaxValue(boolean value)
```

Jelzi, hogy a maximális érték automatikusan van-e hozzárendelve. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getMaxValue() {#getMaxValue--}
```
public abstract double getMaxValue()
```

Jelzi a maximális értéket az értéktengelyen. Olvasás/írás double.

**Visszatér:**
double

### setMaxValue(double value) {#setMaxValue-double-}
```
public abstract void setMaxValue(double value)
```

Jelzi a maximális értéket az értéktengelyen. Olvasás/írás double.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |

### getMinorUnit() {#getMinorUnit--}
```
public abstract double getMinorUnit()
```

Jelzi a kisebb egységeket a dátum- vagy értéktengelyen. Olvasás/írás double.

**Visszatér:**
double

### setMinorUnit(double value) {#setMinorUnit-double-}
```
public abstract void setMinorUnit(double value)
```

Jelzi a kisebb egységeket a dátum- vagy értéktengelyen. Olvasás/írás double.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |

### isAutomaticMinorUnit() {#isAutomaticMinorUnit--}
```
public abstract boolean isAutomaticMinorUnit()
```

Jelzi, hogy a tengely alegysége automatikusan van-e hozzárendelve. Olvasás/írás boolean.

**Visszatér:**
boolean

### setAutomaticMinorUnit(boolean value) {#setAutomaticMinorUnit-boolean-}
```
public abstract void setAutomaticMinorUnit(boolean value)
```

Jelzi, hogy a tengely alegysége automatikusan van-e hozzárendelve. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getMajorUnit() {#getMajorUnit--}
```
public abstract double getMajorUnit()
```

Jelzi a főegységeket a dátum- vagy értéktengelyen. Olvasás/írás double.

**Visszatér:**
double

### setMajorUnit(double value) {#setMajorUnit-double-}
```
public abstract void setMajorUnit(double value)
```

Jelzi a főegységeket a dátum- vagy értéktengelyen. Olvasás/írás double.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |

### isAutomaticMajorUnit() {#isAutomaticMajorUnit--}
```
public abstract boolean isAutomaticMajorUnit()
```

Jelzi, hogy a tengely főegysége automatikusan van-e hozzárendelve. Olvasás/írás boolean.

**Visszatér:**
boolean
### setAutomaticMajorUnit(boolean value) {#setAutomaticMajorUnit-boolean-}
```
public abstract void setAutomaticMajorUnit(boolean value)
```

Azt jelzi, hogy a tengely főegységét automatikusan osztják be. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticMinValue() {#isAutomaticMinValue--}
```
public abstract boolean isAutomaticMinValue()
```

Azt jelzi, hogy a minimumértéket automatikusan állítják be. Olvasás/írás boolean.

**Visszatérési érték:**
boolean
### setAutomaticMinValue(boolean value) {#setAutomaticMinValue-boolean-}
```
public abstract void setAutomaticMinValue(boolean value)
```

Azt jelzi, hogy a minimumértéket automatikusan állítják be. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getMinValue() {#getMinValue--}
```
public abstract double getMinValue()
```

A value tengely minimális értékét reprezentálja. Olvasás/írás double.

**Visszatérési érték:**
double
### setMinValue(double value) {#setMinValue-double-}
```
public abstract void setMinValue(double value)
```

A value tengely minimális értékét reprezentálja. Olvasás/írás double.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |

### isLogarithmic() {#isLogarithmic--}
```
public abstract boolean isLogarithmic()
```

Azt jelzi, hogy a value tengely skálatípusa logaritmikus-e. Olvasás/írás boolean.

**Visszatérési érték:**
boolean
### setLogarithmic(boolean value) {#setLogarithmic-boolean-}
```
public abstract void setLogarithmic(boolean value)
```

Azt jelzi, hogy a value tengely skálatípusa logaritmikus-e. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getLogBase() {#getLogBase--}
```
public abstract double getLogBase()
```

A logaritmikus alapot reprezentálja. Alapértelmezett érték 10. Olvasás/írás double.

**Visszatérési érték:**
double
### setLogBase(double value) {#setLogBase-double-}
```
public abstract void setLogBase(double value)
```

A logaritmikus alapot reprezentálja. Alapértelmezett érték 10. Olvasás/írás double.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |

### isPlotOrderReversed() {#isPlotOrderReversed--}
```
public abstract boolean isPlotOrderReversed()
```

Azt jelzi, hogy a MS PowerPoint az adatpontokat az utolsótól az elsőig rajzolja. Olvasás/írás boolean.

**Visszatérési érték:**
boolean
### setPlotOrderReversed(boolean value) {#setPlotOrderReversed-boolean-}
```
public abstract void setPlotOrderReversed(boolean value)
```

Azt jelzi, hogy a MS PowerPoint az adatpontokat az utolsótól az elsőig rajzolja. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

Azt jelzi, hogy a tengely látható-e. Olvasás/írás boolean.

**Visszatérési érték:**
boolean
### setVisible(boolean value) {#setVisible-boolean-}
```
public abstract void setVisible(boolean value)
```

Azt jelzi, hogy a tengely látható-e. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getMajorTickMark() {#getMajorTickMark--}
```
public abstract int getMajorTickMark()
```

A megadott tengely fő jelölőjének típusát reprezentálja. Olvasás/írás [TickMarkType](../../com.aspose.slides/tickmarktype).

**Visszatérési érték:**
int
### setMajorTickMark(int value) {#setMajorTickMark-int-}
```
public abstract void setMajorTickMark(int value)
```

A megadott tengely fő jelölőjének típusát reprezentálja. Olvasás/írás [TickMarkType](../../com.aspose.slides/tickmarktype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getMinorTickMark() {#getMinorTickMark--}
```
public abstract int getMinorTickMark()
```

A megadott tengely másodlagos jelölőjének típusát reprezentálja. Olvasás/írás [TickMarkType](../../com.aspose.slides/tickmarktype).

**Visszatérési érték:**
int
### setMinorTickMark(int value) {#setMinorTickMark-int-}
```
public abstract void setMinorTickMark(int value)
```

A megadott tengely másodlagos jelölőjének típusát reprezentálja. Olvasás/írás [TickMarkType](../../com.aspose.slides/tickmarktype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getTickLabelPosition() {#getTickLabelPosition--}
```
public abstract int getTickLabelPosition()
```

A jelölőcímkék pozícióját a megadott tengelyen reprezentálja. Olvasás/írás [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**Visszatérési érték:**
int
### setTickLabelPosition(int value) {#setTickLabelPosition-int-}
```
public abstract void setTickLabelPosition(int value)
```

A jelölőcímkék pozícióját a megadott tengelyen reprezentálja. Olvasás/írás [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getMajorUnitScale() {#getMajorUnitScale--}
```
public abstract int getMajorUnitScale()
```

A dátumtengely fő egység skáláját reprezentálja. Olvasás/írás [TimeUnitType](../../com.aspose.slides/timeunittype).

**Visszatérési érték:**
int
### setMajorUnitScale(int value) {#setMajorUnitScale-int-}
```
public abstract void setMajorUnitScale(int value)
```

A dátumtengely fő egység skáláját reprezentálja. Olvasás/írás [TimeUnitType](../../com.aspose.slides/timeunittype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getMinorUnitScale() {#getMinorUnitScale--}
```
public abstract int getMinorUnitScale()
```

A dátumtengely fő egység skáláját reprezentálja. Olvasás/írás [TimeUnitType](../../com.aspose.slides/timeunittype).

**Visszatérési érték:**
int
### setMinorUnitScale(int value) {#setMinorUnitScale-int-}
```
public abstract void setMinorUnitScale(int value)
```

A dátumtengely fő egység skáláját reprezentálja. Olvasás/írás [TimeUnitType](../../com.aspose.slides/timeunittype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getBaseUnitScale() {#getBaseUnitScale--}
```
public abstract int getBaseUnitScale()
```

A legkisebb időegységet adja meg, amely a dátumtengelyen megjelenik. Olvasás/írás [TimeUnitType](../../com.aspose.slides/timeunittype).

**Visszatérési érték:**
int
### setBaseUnitScale(int value) {#setBaseUnitScale-int-}
```
public abstract void setBaseUnitScale(int value)
```

A legkisebb időegységet adja meg, amely a dátumtengelyen megjelenik. Olvasás/írás [TimeUnitType](../../com.aspose.slides/timeunittype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getMinorGridLinesFormat() {#getMinorGridLinesFormat--}
```
public abstract IChartLinesFormat getMinorGridLinesFormat()
```

A diagram tengelyen lévő kisebb rácsvonalak formátumát reprezentálja. Csak olvasható [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**Visszatérési érték:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### getMajorGridLinesFormat() {#getMajorGridLinesFormat--}
```
public abstract IChartLinesFormat getMajorGridLinesFormat()
```

A diagram tengelyen lévő nagyobb rácsvonalak formátumát reprezentálja. Csak olvasható [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**Visszatérési érték:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### getShowMinorGridLines() {#getShowMinorGridLines--}
```
public abstract boolean getShowMinorGridLines()
```

A kisebb rácsvonalak megjelenését jelzi. Csak olvasható boolean.

**Visszatérési érték:**
boolean
### getShowMajorGridLines() {#getShowMajorGridLines--}
```
public abstract boolean getShowMajorGridLines()
```

A nagyobb rácsvonalak megjelenését jelzi. Csak olvasható boolean.

**Visszatérési érték:**
boolean
### getFormat() {#getFormat--}
```
public abstract IAxisFormat getFormat()
```

A tengely formátumát reprezentálja. Csak olvasható [IAxisFormat](../../com.aspose.slides/iaxisformat).

**Visszatérési érték:**
[IAxisFormat](../../com.aspose.slides/iaxisformat)
### getTitle() {#getTitle--}
```
public abstract IChartTitle getTitle()
```

A tengely címét adja vissza. Csak olvasható [IChartTitle](../../com.aspose.slides/icharttitle).

**Visszatérési érték:**
[IChartTitle](../../com.aspose.slides/icharttitle)
### getCrossType() {#getCrossType--}
```
public abstract int getCrossType()
```

A megadott tengelyen, ahol a másik tengely metszi, a CrossType-ot reprezentálja. Olvasás/írás [CrossesType](../../com.aspose.slides/crossestype).

**Visszatérési érték:**
int
### setCrossType(int value) {#setCrossType-int-}
```
public abstract void setCrossType(int value)
```

A megadott tengelyen, ahol a másik tengely metszi, a CrossType-ot reprezentálja. Olvasás/írás [CrossesType](../../com.aspose.slides/crossestype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

A tengely pozícióját reprezentálja. Olvasás/írás [AxisPositionType](../../com.aspose.slides/axispositiontype).

**Visszatérési érték:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

A tengely pozícióját reprezentálja. Olvasás/írás [AxisPositionType](../../com.aspose.slides/axispositiontype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### hasTitle() {#hasTitle--}
```
public abstract boolean hasTitle()
```

Megállapítja, hogy a tengelynek látható címe van-e. Olvasás/írás boolean.

**Visszatérési érték:**
boolean
### setTitle(boolean value) {#setTitle-boolean-}
```
public abstract void setTitle(boolean value)
```

Megállapítja, hogy a tengelynek látható címe van-e. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public abstract String getNumberFormat()
```

A tengely feliratainak formátumkarakterláncát reprezentálja. Olvasás/írás String.

**Visszatérési érték:**
java.lang.String
### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public abstract void setNumberFormat(String value)
```

A tengely feliratainak formátumkarakterláncát reprezentálja. Olvasás/írás String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public abstract boolean isNumberFormatLinkedToSource()
```

Jelzi, hogy a formátum a forrásadatokhoz van-e kapcsolva. Olvasás/írás boolean.

**Visszatérési érték:**
boolean
### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public abstract void setNumberFormatLinkedToSource(boolean value)
```

Jelzi, hogy a formátum a forrásadatokhoz van-e kapcsolva. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getTickLabelRotationAngle() {#getTickLabelRotationAngle--}
```
public abstract float getTickLabelRotationAngle()
```

A jelölőcímkék forgatási szögét reprezentálja. Olvasás/írás float.

**Visszatérési érték:**
float
### setTickLabelRotationAngle(float value) {#setTickLabelRotationAngle-float-}
```
public abstract void setTickLabelRotationAngle(float value)
```

A jelölőcímkék forgatási szögét reprezentálja. Olvasás/írás float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getTickLabelSpacing() {#getTickLabelSpacing--}
```
public abstract long getTickLabelSpacing()
```

Megadja, hogy hány jelölőcímkét kell kihagyni a rajzolt címke között. Olvasás/írás long.

**Visszatérési érték:**
long
### setTickLabelSpacing(long value) {#setTickLabelSpacing-long-}
```
public abstract void setTickLabelSpacing(long value)
```

Megadja, hogy hány jelölőcímkét kell kihagyni a rajzolt címke között. Olvasás/írás long.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickLabelSpacing() {#isAutomaticTickLabelSpacing--}
```
public abstract boolean isAutomaticTickLabelSpacing()
```

Megadja az automatikus jelölőcímke-távolság értékét. Ha false: a TickLabelSpacing tulajdonságot használja. Olvasás/írás boolean.

**Visszatérési érték:**
boolean
### setAutomaticTickLabelSpacing(boolean value) {#setAutomaticTickLabelSpacing-boolean-}
```
public abstract void setAutomaticTickLabelSpacing(boolean value)
```

Megadja az automatikus jelölőcímke-távolság értékét. Ha false: a TickLabelSpacing tulajdonságot használja. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getTickMarksSpacing() {#getTickMarksSpacing--}
```
public abstract long getTickMarksSpacing()
```

Megadja, hogy hány jelölővonalat kell kihagyni a következő rajzolásáig. Kategória vagy sor tengelyre alkalmazható. Olvasás/írás int.

**Visszatérési érték:**
long
### setTickMarksSpacing(long value) {#setTickMarksSpacing-long-}
```
public abstract void setTickMarksSpacing(long value)
```

Megadja, hogy hány jelölővonalat kell kihagyni a következő rajzolásáig. Kategória vagy sor tengelyre alkalmazható. Olvasás/írás int.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickMarksSpacing() {#isAutomaticTickMarksSpacing--}
```
public abstract boolean isAutomaticTickMarksSpacing()
```

Megadja az automatikus jelölővonal-távolság értékét. Ha false: a TickMarksSpacing tulajdonságot használja. Olvasás/írás boolean.

**Visszatérési érték:**
boolean
### setAutomaticTickMarksSpacing(boolean value) {#setAutomaticTickMarksSpacing-boolean-}
```
public abstract void setAutomaticTickMarksSpacing(boolean value)
```

Megadja az automatikus jelölővonal-távolság értékét. Ha false: a TickMarksSpacing tulajdonságot használja. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getLabelOffset() {#getLabelOffset--}
```
public abstract int getLabelOffset()
```

Meghatározza a címkék távolságát a tengelytől. Kategória vagy dátum tengelyre alkalmazható. Az érték 0 % és 1000 % között kell legyen. Olvasás/írás int.

**Visszatérési érték:**
int
### setLabelOffset(int value) {#setLabelOffset-int-}
```
public abstract void setLabelOffset(int value)
```

Meghatározza a címkék távolságát a tengelytől. Kategória vagy dátum tengelyre alkalmazható. Az érték 0 % és 1000 % között kell legyen. Olvasás/írás int.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getCategoryAxisType() {#getCategoryAxisType--}
```
public abstract int getCategoryAxisType()
```

Meghatározza a kategória tengely típusát. Olvasás/írás [CategoryAxisType](../../com.aspose.slides/categoryaxistype)(\#getCategoryAxisType.getCategoryAxisType/\#setCategoryAxisType(int).setCategoryAxisType(int)).

**Visszatérési érték:**
int
### setCategoryAxisType(int value) {#setCategoryAxisType-int-}
```
public abstract void setCategoryAxisType(int value)
```

Meghatározza a kategória tengely típusát. Olvasás/írás [CategoryAxisType](../../com.aspose.slides/categoryaxistype)(\#getCategoryAxisType.getCategoryAxisType/\#setCategoryAxisType(int).setCategoryAxisType(int)).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### setCategoryAxisTypeAutomatically() {#setCategoryAxisTypeAutomatically--}
```
public abstract void setCategoryAxisTypeAutomatically()
```

Beállítja az IAxis.CategoryAxisType tulajdonságot egy automatikusan meghatározott értékkel, amely a tengelyadata alapján kerül kiszámításra.

### getAggregationType() {#getAggregationType--}
```
public abstract int getAggregationType()
```

A kategória tengely aggregációs típusát (binning) reprezentálja. Kategóriára vonatkozik. Csak histogram vagy histogramPareto sorokkal használható.

**Visszatérési érték:**
int
### setAggregationType(int value) {#setAggregationType-int-}
```
public abstract void setAggregationType(int value)
```

A kategória tengely aggregációs típusát (binning) reprezentálja. Kategóriára vonatkozik. Csak histogram vagy histogramPareto sorokkal használható.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### getBinWidth() {#getBinWidth--}
```
public abstract double getBinWidth()
```


Megadja a bin szélességét, amikor az AggregationType property értéke AxisAggregationType.ByBinWidth. Alkalmazva kategória tengelyekre. Csak Histogram vagy HistogramPareto sorozatokkal használható.

**Visszatér:**
double
### setBinWidth(double value) {#setBinWidth-double-}
```
public abstract void setBinWidth(double value)
```


Megadja a bin szélességét, amikor az AggregationType property értéke AxisAggregationType.ByBinWidth. Alkalmazva kategória tengelyekre. Csak Histogram vagy HistogramPareto sorozatokkal használható.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |

### getNumberOfBins() {#getNumberOfBins--}
```
public abstract long getNumberOfBins()
```


Megadja a bin-ek számát, amikor az AggregationType property értéke AxisAggregationType.ByNumberOfBins. Alkalmazva kategória tengelyekre. Csak Histogram vagy HistogramPareto sorozatokkal használható.

**Visszatér:**
long
### setNumberOfBins(long value) {#setNumberOfBins-long-}
```
public abstract void setNumberOfBins(long value)
```


Megadja a bin-ek számát, amikor az AggregationType property értéke AxisAggregationType.ByNumberOfBins. Alkalmazva kategória tengelyekre. Csak Histogram vagy HistogramPareto sorozatokkal használható.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | long |  |

### isOverflowBin() {#isOverflowBin--}
```
public abstract boolean isOverflowBin()
```


Megadja, hogy alkalmaz-e overflow bin-t. Az IsAutomaticOverflowBin és az OverflowBin használatával állítható be az overflow bin értéke.

**Visszatér:**
boolean
### setOverflowBin(boolean value) {#setOverflowBin-boolean-}
```
public abstract void setOverflowBin(boolean value)
```


Megadja, hogy alkalmaz-e overflow bin-t. Az IsAutomaticOverflowBin és az OverflowBin használatával állítható be az overflow bin értéke.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticOverflowBin() {#isAutomaticOverflowBin--}
```
public abstract boolean isAutomaticOverflowBin()
```


Megadja az automatikus overflow bin értékét. Ha hamis: használja az OverflowBin tulajdonságot.

**Visszatér:**
boolean
### setAutomaticOverflowBin(boolean value) {#setAutomaticOverflowBin-boolean-}
```
public abstract void setAutomaticOverflowBin(boolean value)
```


Megadja az automatikus overflow bin értékét. Ha hamis: használja az OverflowBin tulajdonságot.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getOverflowBin() {#getOverflowBin--}
```
public abstract double getOverflowBin()
```


Megadja az overflow bin egyéni értékét. Alkalmazva, amikor az IsAutomaticOverflowBin tulajdonság hamisra van állítva, és az IsOverflowBin tulajdonság igaz.

**Visszatér:**
double
### setOverflowBin(double value) {#setOverflowBin-double-}
```
public abstract void setOverflowBin(double value)
```


Megadja az overflow bin egyéni értékét. Alkalmazva, amikor az IsAutomaticOverflowBin tulajdonság hamisra van állítva, és az IsOverflowBin tulajdonság igaz.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |

### isUnderflowBin() {#isUnderflowBin--}
```
public abstract boolean isUnderflowBin()
```


Megadja, hogy alkalmaz-e underflow bin-t. Az IsAutomaticUnderflowBin és az UnderflowBin használatával állítható be az underflow bin értéke.

**Visszatér:**
boolean
### setUnderflowBin(boolean value) {#setUnderflowBin-boolean-}
```
public abstract void setUnderflowBin(boolean value)
```


Megadja, hogy alkalmaz-e underflow bin-t. Az IsAutomaticUnderflowBin és az UnderflowBin használatával állítható be az underflow bin értéke.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticUnderflowBin() {#isAutomaticUnderflowBin--}
```
public abstract boolean isAutomaticUnderflowBin()
```


Megadja az automatikus underflow bin értékét. Ha hamis: használja az UnderflowBin tulajdonságot.

**Visszatér:**
boolean
### setAutomaticUnderflowBin(boolean value) {#setAutomaticUnderflowBin-boolean-}
```
public abstract void setAutomaticUnderflowBin(boolean value)
```


Megadja az automatikus underflow bin értékét. Ha hamis: használja az UnderflowBin tulajdonságot.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getUnderflowBin() {#getUnderflowBin--}
```
public abstract double getUnderflowBin()
```


Megadja az underflow bin egyéni értékét. Alkalmazva, amikor az IsAutomaticUnderflowBin tulajdonság hamisra van állítva, és az IsUnderflowBin tulajdonság igaz.

**Visszatér:**
double
### setUnderflowBin(double value) {#setUnderflowBin-double-}
```
public abstract void setUnderflowBin(double value)
```


Megadja az underflow bin egyéni értékét. Alkalmazva, amikor az IsAutomaticUnderflowBin tulajdonság hamisra van állítva, és az IsUnderflowBin tulajdonság igaz.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |