---
title: IAxis
second_title: Aspose.Slides Androidra a Java API hivatkozás
description: Tömöríti azt az objektumot, amely egy diagram tengelyét képviseli.
type: docs
url: /hu/com.aspose.slides/iaxis/
---
**Az összes megvalósított interfész:**
[com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer)
```
public interface IAxis extends IFormattedTextContainer
```

Az objektumot tartalmazza, amely egy diagram tengelyét képviseli.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getAxisBetweenCategories()](#getAxisBetweenCategories--) | Azt jelzi, hogy az érték tengely a kategória tengelyt a kategóriák között keresztezi-e. |
| [setAxisBetweenCategories(boolean value)](#setAxisBetweenCategories-boolean-) | Azt jelzi, hogy az érték tengely a kategória tengelyt a kategóriák között keresztezi-e. |
| [getCrossAt()](#getCrossAt--) | A tengely azon pontját jelöli, ahol a merőleges tengely keresztezi azt. |
| [setCrossAt(float value)](#setCrossAt-float-) | A tengely azon pontját jelöli, ahol a merőleges tengely keresztezi azt. |
| [getDisplayUnit()](#getDisplayUnit--) | A megjelenítési egységek méretezési értékét határozza meg az érték tengelyhez. |
| [setDisplayUnit(int value)](#setDisplayUnit-int-) | A megjelenítési egységek méretezési értékét határozza meg az érték tengelyhez. |
| [getActualMaxValue()](#getActualMaxValue--) | A tengely tényleges maximális értékét adja meg. |
| [getActualMinValue()](#getActualMinValue--) | A tengely tényleges minimális értékét adja meg. |
| [getActualMajorUnit()](#getActualMajorUnit--) | A tengely tényleges fő egységét adja meg. |
| [getActualMinorUnit()](#getActualMinorUnit--) | A tengely tényleges másodlagos egységét adja meg. |
| [getActualMajorUnitScale()](#getActualMajorUnitScale--) | A tengely tényleges fő egység skáláját adja meg. |
| [getActualMinorUnitScale()](#getActualMinorUnitScale--) | A tengely tényleges másodlagos egység skáláját adja meg. |
| [isAutomaticMaxValue()](#isAutomaticMaxValue--) | Jelzi, hogy a maximális érték automatikusan van-e hozzárendelve. |
| [setAutomaticMaxValue(boolean value)](#setAutomaticMaxValue-boolean-) | Jelzi, hogy a maximális érték automatikusan van-e hozzárendelve. |
| [getMaxValue()](#getMaxValue--) | Az érték tengely maximális értékét jelöli. |
| [setMaxValue(double value)](#setMaxValue-double-) | Az érték tengely maximális értékét jelöli. |
| [getMinorUnit()](#getMinorUnit--) | A dátum vagy érték tengely kisebb egységeit jelöli. |
| [setMinorUnit(double value)](#setMinorUnit-double-) | A dátum vagy érték tengely kisebb egységeit jelöli. |
| [isAutomaticMinorUnit()](#isAutomaticMinorUnit--) | Jelzi, hogy a tengely kisebb egysége automatikusan van-e hozzárendelve. |
| [setAutomaticMinorUnit(boolean value)](#setAutomaticMinorUnit-boolean-) | Jelzi, hogy a tengely kisebb egysége automatikusan van-e hozzárendelve. |
| [getMajorUnit()](#getMajorUnit--) | A dátum vagy érték tengely fő egységeit jelöli. |
| [setMajorUnit(double value)](#setMajorUnit-double-) | A dátum vagy érték tengely fő egységeit jelöli. |
| [isAutomaticMajorUnit()](#isAutomaticMajorUnit--) | Jelzi, hogy a tengely fő egysége automatikusan van-e hozzárendelve. |
| [setAutomaticMajorUnit(boolean value)](#setAutomaticMajorUnit-boolean-) | Jelzi, hogy a tengely fő egysége automatikusan van-e hozzárendelve. |
| [isAutomaticMinValue()](#isAutomaticMinValue--) | Jelzi, hogy a minimális érték automatikusan van-e hozzárendelve. |
| [setAutomaticMinValue(boolean value)](#setAutomaticMinValue-boolean-) | Jelzi, hogy a minimális érték automatikusan van-e hozzárendelve. |
| [getMinValue()](#getMinValue--) | Az érték tengely minimális értékét jelöli. |
| [setMinValue(double value)](#setMinValue-double-) | Az érték tengely minimális értékét jelöli. |
| [isLogarithmic()](#isLogarithmic--) | Azt jelzi, hogy az érték tengely skálatípusa logaritmikus-e vagy sem. |
| [setLogarithmic(boolean value)](#setLogarithmic-boolean-) | Azt jelzi, hogy az érték tengely skálatípusa logaritmikus-e vagy sem. |
| [getLogBase()](#getLogBase--) | A logaritmikus alapot jelöli. |
| [setLogBase(double value)](#setLogBase-double-) | A logaritmikus alapot jelöli. |
| [isPlotOrderReversed()](#isPlotOrderReversed--) | Azt jelzi, hogy a MS PowerPoint az adatpontokat az utolsótól az elsőig ábrázolja-e. |
| [setPlotOrderReversed(boolean value)](#setPlotOrderReversed-boolean-) | Azt jelzi, hogy a MS PowerPoint az adatpontokat az utolsótól az elsőig ábrázolja-e. |
| [isVisible()](#isVisible--) | Azt jelzi, hogy a tengely látható-e. |
| [setVisible(boolean value)](#setVisible-boolean-) | Azt jelzi, hogy a tengely látható-e. |
| [getMajorTickMark()](#getMajorTickMark--) | A megadott tengely fő jelölővonalának típusát jelöli. |
| [setMajorTickMark(int value)](#setMajorTickMark-int-) | A megadott tengely fő jelölővonalának típusát jelöli. |
| [getMinorTickMark()](#getMinorTickMark--) | A megadott tengely kisebb jelölővonalának típusát jelöli. |
| [setMinorTickMark(int value)](#setMinorTickMark-int-) | A megadott tengely kisebb jelölővonalának típusát jelöli. |
| [getTickLabelPosition()](#getTickLabelPosition--) | A megadott tengelyen a jelölő címkék pozícióját jelöli. |
| [setTickLabelPosition(int value)](#setTickLabelPosition-int-) | A megadott tengelyen a jelölő címkék pozícióját jelöli. |
| [getMajorUnitScale()](#getMajorUnitScale--) | A dátum tengely fő egység skáláját jelöli. |
| [setMajorUnitScale(int value)](#setMajorUnitScale-int-) | A dátum tengely fő egység skáláját jelöli. |
| [getMinorUnitScale()](#getMinorUnitScale--) | A dátum tengely fő egység skáláját jelöli. |
| [setMinorUnitScale(int value)](#setMinorUnitScale-int-) | A dátum tengely fő egység skáláját jelöli. |
| [getBaseUnitScale()](#getBaseUnitScale--) | Megadja a legkisebb időegységet, amely a dátum tengelyen megjelenik. |
| [setBaseUnitScale(int value)](#setBaseUnitScale-int-) | Megadja a legkisebb időegységet, amely a dátum tengelyen megjelenik. |
| [getMinorGridLinesFormat()](#getMinorGridLinesFormat--) | A diagram tengelyének kisebb rácsvonalak formátumát jelöli. |
| [getMajorGridLinesFormat()](#getMajorGridLinesFormat--) | A diagram tengelyének fő rácsvonalak formátumát jelöli. |
| [getShowMinorGridLines()](#getShowMinorGridLines--) | Azt jelzi, hogy a kisebb rácsvonalak megjelennek-e. |
| [getShowMajorGridLines()](#getShowMajorGridLines--) | Azt jelzi, hogy a fő rácsvonalak megjelennek-e. |
| [getFormat()](#getFormat--) | A tengely formátumát jelöli. |
| [getTitle()](#getTitle--) | A tengely címét adja vissza. |
| [getCrossType()](#getCrossType--) | A megadott tengelyen a másik tengely által áthaladó CrossType-ot jelöli. |
| [setCrossType(int value)](#setCrossType-int-) | A megadott tengelyen a másik tengely által áthaladó CrossType-ot jelöli. |
| [getPosition()](#getPosition--) | A tengely pozícióját jelöli. |
| [setPosition(int value)](#setPosition-int-) | A tengely pozícióját jelöli. |
| [hasTitle()](#hasTitle--) | Megállapítja, hogy a tengelynek van-e látható címe. |
| [setTitle(boolean value)](#setTitle-boolean-) | Megállapítja, hogy a tengelynek van-e látható címe. |
| [getNumberFormat()](#getNumberFormat--) | Az Axis Labels formátumkarakterláncát jelöli. |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | Az Axis Labels formátumkarakterláncát jelöli. |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | Jelzi, hogy a formátum kapcsolódik-e a forrásadatokhoz. |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | Jelzi, hogy a formátum kapcsolódik-e a forrásadatokhoz. |
| [getTickLabelRotationAngle()](#getTickLabelRotationAngle--) | A jelölőcímkék forgástényszögét jelöli. Olvasás/írás float. |
| [setTickLabelRotationAngle(float value)](#setTickLabelRotationAngle-float-) | A jelölőcímkék forgástényszögét jelöli. Olvasás/írás float. |
| [getTickLabelSpacing()](#getTickLabelSpacing--) | Megadja, hány jelölőcímkét kell kihagyni a megjelenített címke között. |
| [setTickLabelSpacing(long value)](#setTickLabelSpacing-long-) | Megadja, hány jelölőcímkét kell kihagyni a megjelenített címke között. |
| [isAutomaticTickLabelSpacing()](#isAutomaticTickLabelSpacing--) | Megadja az automatikus jelölőcímke távolság értékét. |
| [setAutomaticTickLabelSpacing(boolean value)](#setAutomaticTickLabelSpacing-boolean-) | Megadja az automatikus jelölőcímke távolság értékét. |
| [getTickMarksSpacing()](#getTickMarksSpacing--) | Megadja, hány jelölővonalat kell kihagyni, mielőtt a következő megjelenik. |
| [setTickMarksSpacing(long value)](#setTickMarksSpacing-long-) | Megadja, hány jelölővonalat kell kihagyni, mielőtt a következő megjelenik. |
| [isAutomaticTickMarksSpacing()](#isAutomaticTickMarksSpacing--) | Megadja az automatikus jelölővonalak távolság értékét. |
| [setAutomaticTickMarksSpacing(boolean value)](#setAutomaticTickMarksSpacing-boolean-) | Megadja az automatikus jelölővonalak távolság értékét. |
| [getLabelOffset()](#getLabelOffset--) | Megadja a címkék távolságát a tengelytől. |
| [setLabelOffset(int value)](#setLabelOffset-int-) | Megadja a címkék távolságát a tengelytől. |
| [getCategoryAxisType()](#getCategoryAxisType--) | A kategória tengely típusát jelöli. |
| [setCategoryAxisType(int value)](#setCategoryAxisType-int-) | A kategória tengely típusát jelöli. |
| [setCategoryAxisTypeAutomatically()](#setCategoryAxisTypeAutomatically--) | Beállítja az IAxis.CategoryAxisType tulajdonságot egy, a tengely adatai alapján automatikusan meghatározott értékkel. |
| [getAggregationType()](#getAggregationType--) | A kategória tengely aggregációs típusát (csoportosítás) jelöli. |
| [setAggregationType(int value)](#setAggregationType-int-) | A kategória tengely aggregációs típusát (csoportosítás) jelöli. |
| [getBinWidth()](#getBinWidth--) | Megadja a bin szélességet, ha az AggregationType tulajdonság értéke AxisAggregationType.ByBinWidth. |
| [setBinWidth(double value)](#setBinWidth-double-) | Megadja a bin szélességet, ha az AggregationType tulajdonság értéke AxisAggregationType.ByBinWidth. |
| [getNumberOfBins()](#getNumberOfBins--) | Megadja a bin-ek számát, ha az AggregationType tulajdonság értéke AxisAggregationType.ByNumberOfBins. |
| [setNumberOfBins(long value)](#setNumberOfBins-long-) | Megadja a bin-ek számát, ha az AggregationType tulajdonság értéke AxisAggregationType.ByNumberOfBins. |
| [isOverflowBin()](#isOverflowBin--) | Megadja, hogy túlcsorduló bin alkalmazásra került-e. |
| [setOverflowBin(boolean value)](#setOverflowBin-boolean-) | Megadja, hogy túlcsorduló bin alkalmazásra került-e. |
| [isAutomaticOverflowBin()](#isAutomaticOverflowBin--) | Megadja az automatikus túlcsorduló bin értékét. |
| [setAutomaticOverflowBin(boolean value)](#setAutomaticOverflowBin-boolean-) | Megadja az automatikus túlcsorduló bin értékét. |
| [getOverflowBin()](#getOverflowBin--) | Megadja a túlcsorduló bin egyéni értékét. |
| [setOverflowBin(double value)](#setOverflowBin-double-) | Megadja a túlcsorduló bin egyéni értékét. |
| [isUnderflowBin()](#isUnderflowBin--) | Megadja, hogy alulcsorduló bin alkalmazásra került-e. |
| [setUnderflowBin(boolean value)](#setUnderflowBin-boolean-) | Megadja, hogy alulcsorduló bin alkalmazásra került-e. |
| [isAutomaticUnderflowBin()](#isAutomaticUnderflowBin--) | Megadja az automatikus alulcsorduló bin értékét. |
| [setAutomaticUnderflowBin(boolean value)](#setAutomaticUnderflowBin-boolean-) | Megadja az automatikus alulcsorduló bin értékét. |
| [getUnderflowBin()](#getUnderflowBin--) | Megadja az alulcsorduló bin egyéni értékét. |
| [setUnderflowBin(double value)](#setUnderflowBin-double-) | Megadja az alulcsorduló bin egyéni értékét. |

### getAxisBetweenCategories() {#getAxisBetweenCategories--}
```
public abstract boolean getAxisBetweenCategories()
```

Azt jelzi, hogy az érték tengely a kategória tengelyt a kategóriák között keresztezi-e. Ez a tulajdonság csak kategória tengelyekre vonatkozik, és 3-D diagramokra nem érvényes. Olvasás/írás boolean.

**Visszatérési érték:**
boolean
### setAxisBetweenCategories(boolean value) {#setAxisBetweenCategories-boolean-}
```
public abstract void setAxisBetweenCategories(boolean value)
```

Azt jelzi, hogy az érték tengely a kategória tengelyt a kategóriák között keresztezi-e. Ez a tulajdonság csak kategória tengelyekre vonatkozik, és 3-D diagramokra nem érvényes. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getCrossAt() {#getCrossAt--}
```
public abstract float getCrossAt()
```

A tengely azon pontját jelöli, ahol a merőleges tengely keresztezi azt. Olvasás/írás float.

**Visszatérési érték:**
float
### setCrossAt(float value) {#setCrossAt-float-}
```
public abstract void setCrossAt(float value)
```

A tengely azon pontját jelöli, ahol a merőleges tengely keresztezi azt. Olvasás/írás float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getDisplayUnit() {#getDisplayUnit--}
```
public abstract int getDisplayUnit()
```

A megjelenítési egységek méretezési értékét határozza meg az érték tengelyhez. Olvasás/írás [DisplayUnitType](../../com.aspose.slides/displayunittype).

**Visszatérési érték:**
int
### setDisplayUnit(int value) {#setDisplayUnit-int-}
```
public abstract void setDisplayUnit(int value)
```

A megjelenítési egységek méretezési értékét határozza meg az érték tengelyhez. Olvasás/írás [DisplayUnitType](../../com.aspose.slides/displayunittype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getActualMaxValue() {#getActualMaxValue--}
```
public abstract double getActualMaxValue()
```

A tengely tényleges maximális értékét adja meg. A tényleges érték megszerzéséhez előtte hívja meg az IChart.ValidateChartLayout() metódust.

**Visszatérési érték:**
double
### getActualMinValue() {#getActualMinValue--}
```
public abstract double getActualMinValue()
```

A tengely tényleges minimális értékét adja meg. A tényleges érték megszerzéséhez előtte hívja meg az IChart.ValidateChartLayout() metódust.

**Visszatérési érték:**
double
### getActualMajorUnit() {#getActualMajorUnit--}
```
public abstract double getActualMajorUnit()
```

A tengely tényleges fő egységét adja meg. A tényleges érték megszerzéséhez előtte hívja meg az IChart.ValidateChartLayout() metódust.

**Visszatérési érték:**
double
### getActualMinorUnit() {#getActualMinorUnit--}
```
public abstract double getActualMinorUnit()
```

A tengely tényleges másodlagos egységét adja meg. A tényleges érték megszerzéséhez előtte hívja meg az IChart.ValidateChartLayout() metódust.

**Visszatérési érték:**
double
### getActualMajorUnitScale() {#getActualMajorUnitScale--}
```
public abstract int getActualMajorUnitScale()
```

A tengely tényleges fő egység skáláját adja meg. A tényleges érték megszerzéséhez előtte hívja meg az IChart.ValidateChartLayout() metódust.

**Visszatérési érték:**
int
### getActualMinorUnitScale() {#getActualMinorUnitScale--}
```
public abstract int getActualMinorUnitScale()
```

A tengely tényleges másodlagos egység skáláját adja meg. A tényleges érték megszerzéséhez előtte hívja meg az IChart.ValidateChartLayout() metódust.

**Visszatérési érték:**
int
### isAutomaticMaxValue() {#isAutomaticMaxValue--}
```
public abstract boolean isAutomaticMaxValue()
```

Jelzi, hogy a maximális érték automatikusan van-e hozzárendelve. Olvasás/írás boolean.

**Visszatérési érték:**
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

Az érték tengely maximális értékét jelöli. Olvasás/írás double.

**Visszatérési érték:**
double
### setMaxValue(double value) {#setMaxValue-double-}
```
public abstract void setMaxValue(double value)
```

Az érték tengely maximális értékét jelöli. Olvasás/írás double.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |

### getMinorUnit() {#getMinorUnit--}
```
public abstract double getMinorUnit()
```

A dátum vagy érték tengely kisebb egységeit jelöli. Olvasás/írás double.

**Visszatérési érték:**
double
### setMinorUnit(double value) {#setMinorUnit-double-}
```
public abstract void setMinorUnit(double value)
```

A dátum vagy érték tengely kisebb egységeit jelöli. Olvasás/írás double.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |

### isAutomaticMinorUnit() {#isAutomaticMinorUnit--}
```
public abstract boolean isAutomaticMinorUnit()
```

Jelzi, hogy a tengely kisebb egysége automatikusan van-e hozzárendelve. Olvasás/írás boolean.

**Visszatérési érték:**
boolean
### setAutomaticMinorUnit(boolean value) {#setAutomaticMinorUnit-boolean-}
```
public abstract void setAutomaticMinorUnit(boolean value)
```

Jelzi, hogy a tengely kisebb egysége automatikusan van-e hozzárendelve. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getMajorUnit() {#getMajorUnit--}
```
public abstract double getMajorUnit()
```

A dátum vagy érték tengely fő egységeit jelöli. Olvasás/írás double.

**Visszatérési érték:**
double
### setMajorUnit(double value) {#setMajorUnit-double-}
```
public abstract void setMajorUnit(double value)
```

A dátum vagy érték tengely fő egységeit jelöli. Olvasás/írás double.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |

### isAutomaticMajorUnit() {#isAutomaticMajorUnit--}
```
public abstract boolean isAutomaticMajorUnit()
```

Jelzi, hogy a tengely fő egysége automatikusan van-e hozzárendelve. Olvasás/írás boolean.

**Visszatérési érték:**
boolean
### setAutomaticMajorUnit(boolean value) {#setAutomaticMajorUnit-boolean-}
```
public abstract void setAutomaticMajorUnit(boolean value)
```

Jelzi, hogy a tengely fő egysége automatikusan van-e hozzárendelve. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticMinValue() {#isAutomaticMinValue--}
```
public abstract boolean isAutomaticMinValue()
```

Jelzi, hogy a minimális érték automatikusan van-e hozzárendelve. Olvasás/írás boolean.

**Visszatérési érték:**
boolean
### setAutomaticMinValue(boolean value) {#setAutomaticMinValue-boolean-}
```
public abstract void setAutomaticMinValue(boolean value)
```

Jelzi, hogy a minimális érték automatikusan van-e hozzárendelve. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getMinValue() {#getMinValue--}
```
public abstract double getMinValue()
```

Az érték tengely minimális értékét jelöli. Olvasás/írás double.

**Visszatérési érték:**
double
### setMinValue(double value) {#setMinValue-double-}
```
...... ... ...........
```

Az érték tengely minimális értékét jelöli. Olvasás/írás double.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |

### isLogarithmic() {#isLogarithmic--}
```
public abstract boolean isLogarithmic()
```

Azt jelzi, hogy az érték tengely skálatípusa logaritmikus-e vagy sem. Olvasás/írás boolean.

**Visszatérési érték:**
boolean
### setLogarithmic(boolean value) {#setLogarithmic-boolean-}
```
public abstract void setLogarithmic(boolean value)
```

Azt jelzi, hogy az érték tengely skálatípusa logaritmikus-e vagy sem. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getLogBase() {#getLogBase--}
```
public abstract double getLogBase()
```

A logaritmikus alapot jelöli. Alapértelmezett érték 10. Olvasás/írás double.

**Visszatérési érték:**
double
### setLogBase(double value) {#setLogBase-double-}
```
public abstract void setLogBase(double value)
```

A logaritmikus alapot jelöli. Alapértelmezett érték 10. Olvasás/írás double.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |

### isPlotOrderReversed() {#isPlotOrderReversed--}
```
public abstract boolean isPlotOrderReversed()
```

Azt jelzi, hogy a MS PowerPoint az adatpontokat az utolsótól az elsőig ábrázolja-e. Olvasás/írás boolean.

**Visszatérési érték:**
boolean
### setPlotOrderReversed(boolean value) {#setPlotOrderReversed-boolean-}
```
public abstract void setPlotOrderReversed(boolean value)
```

Azt jelzi, hogy a MS PowerPoint az adatpontokat az utolsótól az elsőig ábrázolja-e. Olvasás/írás boolean.

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

A megadott tengely fő jelölővonalának típusát jelöli. Olvasás/írás [TickMarkType](../../com.aspose.slides/tickmarktype).

**Visszatérési érték:**
int
### setMajorTickMark(int value) {#setMajorTickMark-int-}
```
public abstract void setMajorTickMark(int value)
```

A megadott tengely fő jelölővonalának típusát jelöli. Olvasás/írás [TickMarkType](../../com.aspose.slides/tickmarktype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getMinorTickMark() {#getMinorTickMark--}
```
public abstract int getMinorTickMark()
```

A megadott tengely kisebb jelölővonalának típusát jelöli. Olvasás/írás [TickMarkType](../../com.aspose.slides/tickmarktype).

**Visszatérési érték:**
int
### setMinorTickMark(int value) {#setMinorTickMark-int-}
```
public abstract void setMinorTickMark(int value)
```

A megadott tengely kisebb jelölővonalának típusát jelöli. Olvasás/írás [TickMarkType](../../com.aspose.slides/tickmarktype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getTickLabelPosition() {#getTickLabelPosition--}
```
public abstract int getTickLabelPosition()
```

A megadott tengelyen a jelölő címkék pozícióját jelöli. Olvasás/írás [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**Visszatérési érték:**
int
### setTickLabelPosition(int value) {#setTickLabelPosition-int-}
```
public abstract void setTickLabelPosition(int value)
```

A megadott tengelyen a jelölő címkék pozícióját jelöli. Olvasás/írás [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getMajorUnitScale() {#getMajorUnitScale--}
```
public abstract int getMajorUnitScale()
```

A dátum tengely fő egység skáláját jelöli. Olvasás/írás [TimeUnitType](../../com.aspose.slides/timeunittype).

**Visszatérési érték:**
int
### setMajorUnitScale(int value) {#setMajorUnitScale-int-}
```
public abstract void setMajorUnitScale(int value)
```

A dátum tengely fő egység skáláját jelöli. Olvasás/írás [TimeUnitType](../../com.aspose.slides/timeunittype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getMinorUnitScale() {#getMinorUnitScale--}
```
public abstract int getMinorUnitScale()
```

A dátum tengely fő egység skáláját jelöli. Olvasás/írás [TimeUnitType](../../com.aspose.slides/timeunittype).

**Visszatérési érték:**
int
### setMinorUnitScale(int value) {#setMinorUnitScale-int-}
```
public abstract void setMinorUnitScale(int value)
```

A dátum tengely fő egység skáláját jelöli. Olvasás/írás [TimeUnitType](../../com.aspose.slides/timeunittype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getBaseUnitScale() {#getBaseUnitScale--}
```
public abstract int getBaseUnitScale()
```

Megadja a legkisebb időegységet, amely a dátum tengelyen megjelenik. Olvasás/írás [TimeUnitType](../../com.aspose.slides/timeunittype).

**Visszatérési érték:**
int
### setBaseUnitScale(int value) {#setBaseUnitScale-int-}
```
public abstract void setBaseUnitScale(int value)
```

Megadja a legkisebb időegységet, amely a dátum tengelyen megjelenik. Olvasás/írás [TimeUnitType](../../com.aspose.slides/timeunittype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getMinorGridLinesFormat() {#getMinorGridLinesFormat--}
```
public abstract IChartLinesFormat getMinorGridLinesFormat()
```

A diagram tengelyének kisebb rácsvonalak formátumát jelöli. Csak olvasható [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**Visszatérési érték:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### getMajorGridLinesFormat() {#getMajorGridLinesFormat--}
```
public abstract IChartLinesFormat getMajorGridLinesFormat()
```

A diagram tengelyének fő rácsvonalak formátumát jelöli. Csak olvasható [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**Visszatérési érték:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### getShowMinorGridLines() {#getShowMinorGridLines--}
```
public abstract boolean getShowMinorGridLines()
```

Azt jelzi, hogy a kisebb rácsvonalak megjelennek-e. Csak olvasható boolean.

**Visszatérési érték:**
boolean
### getShowMajorGridLines() {#getShowMajorGridLines--}
```
public abstract boolean getShowMajorGridLines()
```

Azt jelzi, hogy a fő rácsvonalak megjelennek-e. Csak olvasható boolean.

**Visszatérési érték:**
boolean
### getFormat() {#getFormat--}
```
public abstract IAxisFormat getFormat()
```

A tengely formátumát jelöli. Csak olvasható [IAxisFormat](../../com.aspose.slides/iaxisformat).

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
public      …  …  …
```

A megadott tengelyen a másik tengely által áthaladó CrossType-ot jelöli. Olvasás/írás [CrossesType](../../com.aspose.slides/crossestype).

**Visszatérési érték:**
int
### setCrossType(int value) {#setCrossType-int-}
```
public abstract void setCrossType(int value)
```

A megadott tengelyen a másik tengely által áthaladó CrossType-ot jelöli. Olvasás/írás [CrossesType](../../com.aspose.slides/crossestype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

A tengely pozícióját jelöli. Olvasás/írás [AxisPositionType](../../com.aspose.slides/axispositiontype).

**Visszatérési érték:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

A tengely pozícióját jelöli. Olvasás/írás [AxisPositionType](../../com.aspose.slides/axispositiontype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### hasTitle() {#hasTitle--}
```
public abstract boolean hasTitle()
```

Megállapítja, hogy a tengelynek van-e látható címe. Olvasás/írás boolean.

**Visszatérési érték:**
boolean
### setTitle(boolean value) {#setTitle-boolean-}
```
public abstract void setTitle(boolean value)
```

Megállapítja, hogy a tengelynek van-e látható címe. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public abstract String getNumberFormat()
```

Az Axis Labels formátumkarakterláncát jelöli. Olvasás/írás String.

**Visszatérési érték:**
java.lang.String
### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public abstract void setNumberFormat(String value)
```

Az Axis Labels formátumkarakterláncát jelöli. Olvasás/írás String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public abstract boolean isNumberFormatLinkedToSource()
```

Jelzi, hogy a formátum kapcsolódik-e a forrásadatokhoz. Olvasás/írás boolean.

**Visszatérési érték:**
boolean
### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public abstract void setNumberFormatLinkedToSource(boolean value)
```

Jelzi, hogy a formátum kapcsolódik-e a forrásadatokhoz. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getTickLabelRotationAngle() {#getTickLabelRotationAngle--}
```
public abstract float getTickLabelRotationAngle()
```

A jelölőcímkék forgástényszögét jelöli. Olvasás/írás float.

**Visszatérési érték:**
float
### setTickLabelRotationAngle(float value) {#setTickLabelRotationAngle-float-}
```
public abstract void setTickLabelRotationAngle(float value)
```

A jelölőcímkék forgástényszögét jelöli. Olvasás/írás float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getTickLabelSpacing() {#getTickLabelSpacing--}
```
public abstract long getTickLabelSpacing()
```

Megadja, hány jelölőcímkét kell kihagyni a megjelenített címke között. Olvasás/írás long.

**Visszatérési érték:**
long
### setTickLabelSpacing(long value) {#setTickLabelSpacing-long-}
```
public abstract void setTickLabelSpacing(long value)
```

Megadja, hány jelölőcímkét kell kihagyni a megjelenített címke között. Olvasás/írás long.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickLabelSpacing() {#isAutomaticTickLabelSpacing--}
```
public abstract boolean isAutomaticTickLabelSpacing()
```

Megadja az automatikus jelölőcímke távolság értékét. Ha false: a TickLabelSpacing tulajdonságot használja. Olvasás/írás boolean.

**Visszatérési érték:**
boolean
### setAutomaticTickLabelSpacing(boolean value) {#setAutomaticTickLabelSpacing-boolean-}
```
public abstract void setAutomaticTickLabelSpacing(boolean value)
```

Megadja az automatikus jelölőcímke távolság értékét. Ha false: a TickLabelSpacing tulajdonságot használja. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getTickMarksSpacing() {#getTickMarksSpacing--}
```
public abstract long getTickMarksSpacing()
```

Megadja, hány jelölővonalat kell kihagyni, mielőtt a következő megjelenik. Kategória vagy sorozat tengelyen alkalmazható. Olvasás/írás int.

**Visszatérési érték:**
long
### setTickMarksSpacing(long value) {#setTickMarksSpacing-long-}
```
public abstract void setTickMarksSpacing(long value)
```

Megadja, hány jelölővonalat kell kihagyni, mielőtt a következő megjelenik. Kategória vagy sorozat tengelyen alkalmazható. Olvasás/írás int.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickMarksSpacing() {#isAutomaticTickMarksSpacing--}
```
public abstract boolean isAutomaticTickMarksSpacing()
```

Megadja az automatikus jelölővonalak távolság értékét. Ha false: a TickMarksSpacing tulajdonságot használja. Olvasás/írás boolean.

**Visszatérési érték:**
boolean
### setAutomaticTickMarksSpacing(boolean value) {#setAutomaticTickMarksSpacing-boolean-}
```
public abstract void setAutomaticTickMarksSpacing(boolean value)
```

Megadja az automatikus jelölővonalak távolság értékét. Ha false: a TickMarksSpacing tulajdonságot használja. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getLabelOffset() {#getLabelOffset--}
```
public abstract int getLabelOffset()
```

Megadja a címkék távolságát a tengelytől. Kategória vagy dátum tengelyen alkalmazható. Az értéknek 0 % és 1000 % között kell lennie. Olvasás/írás int.

**Visszatérési érték:**
int
### setLabelOffset(int value) {#setLabelOffset-int-}
```
public  ... ... ......
```

Megadja a címkék távolságát a tengelytől. Kategória vagy dátum tengelyen alkalmazható. Az értéknek 0 % és 1000 % között kell lennie. Olvasás/írás int.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getCategoryAxisType() {#getCategoryAxisType--}
```
public abstract int getCategoryAxisType()
```

A kategória tengely típusát jelöli. Olvasás/írás [CategoryAxisType](../../com.aspose.slides/categoryaxistype)(\#getCategoryAxisType.getCategoryAxisType/\#setCategoryAxisType(int).setCategoryAxisType(int)).

**Visszatérési érték:**
int
### setCategoryAxisType(int value) {#setCategoryAxisType-int-}
```
public abstract void setCategoryAxisType(int value)
```

A kategória tengely típusát jelöli. Olvasás/írás [CategoryAxisType](../../com.aspose.slides/categoryaxistype)(\#getCategoryAxisType.getCategoryAxisType/\#setCategoryAxisType(int).setCategoryAxisType(int)).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### setCategoryAxisTypeAutomatically() {#setCategoryAxisTypeAutomatically--}
```
public abstract void setCategoryAxisTypeAutomatically()
```

Beállítja az IAxis.CategoryAxisType tulajdonságot egy, a tengely adatai alapján automatikusan meghatározott értékkel.

### getAggregationType() {#getAggregationType--}
```
public abstract int getAggregationType()
```

A kategória tengely aggregációs típusát (csoportosítás) jelöli. Kategóriára vonatkozik. Csak Histogram vagy HistogramPareto sorozatoknál használható.

**Visszatérési érték:**
int
### setAggregationType(int value) {#setAggregationType-int-}
```
public abstract void setAggregationType(int value)
```

A kategória tengely aggregációs típusát (csoportosítás) jelöli. Kategóriára vonatkozik. Csak Histogram vagy HistogramPareto sorozatoknál használható.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getBinWidth() {#getBinWidth--}
```
public abstract double getBinWidth()
```

Megadja a bin szélességet, ha az AggregationType tulajdonság értéke AxisAggregationType.ByBinWidth. Kategória tengelyeken alkalmazható. Csak Histogram vagy HistogramPareto sorozatoknál használható.

**Visszatérési érték:**
double
### setBinWidth(double value) {#setBinWidth-double-}
```
public abstract void setBinWidth(double value)
```

Megadja a bin szélességet, ha az AggregationType tulajdonság értéke AxisAggregationType.ByBinWidth. Kategória tengelyeken alkalmazható. Csak Histogram vagy HistogramPareto sorozatoknál használható.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |

### getNumberOfBins() {#getNumberOfBins--}
```
public abstract long getNumberOfBins()
```

Megadja a bin-ek számát, ha az AggregationType tulajdonság értéke AxisAggregationType.ByNumberOfBins. Kategória tengelyeken alkalmazható. Csak Histogram vagy HistogramPareto sorozatoknál használható.

**Visszatérési érték:**
long
### setNumberOfBins(long value) {#setNumberOfBins-long-}
```
public abstract void setNumberOfBins(long value)
```

Megadja a bin-ek számát, ha az AggregationType tulajdonság értéke AxisAggregationType.ByNumberOfBins. Kategória tengelyeken alkalmazható. Csak Histogram vagy HistogramPareto sorozatoknál használható.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | long |  |

### isOverflowBin() {#isOverflowBin--}
```
public abstract boolean isOverflowBin()
```

Megadja, hogy túlcsorduló bin alkalmazásra került-e. Használja az IsAutomaticOverflowBin és az OverflowBin beállításokat az érték módosításához.

**Visszatérési érték:**
boolean
### setOverflowBin(boolean value) {#setOverflowBin-boolean-}
```
public abstract void setOverflowBin(boolean value)
```

Megadja, hogy túlcsorduló bin alkalmazásra került-e. Használja az IsAutomaticOverflowBin és az OverflowBin beállításokat az érték módosításához.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticOverflowBin() {#isAutomaticOverflowBin--}
```
public abstract boolean isAutomaticOverflowBin()
```

Megadja az automatikus túlcsorduló bin értékét. Ha false: az OverflowBin tulajdonságot használja.

**Visszatérési érték:**
boolean
### setAutomaticOverflowBin(boolean value) {#setAutomaticOverflowBin-boolean-}
```
public abstract void setAutomaticOverflowBin(boolean value)
```

Megadja az automatikus túlcsorduló bin értékét. Ha false: az OverflowBin tulajdonságot használja.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getOverflowBin() {#getOverflowBin--}
```
public abstract double getOverflowBin()
```

Megadja a túlcsorduló bin egyéni értékét. Akkor alkalmazható, ha az IsAutomaticOverflowBin tulajdonság false, és az IsOverflowBin igaz.

**Visszatérési érték:**
double
### setOverflowBin(double value) {#setOverflowBin-double-}
```
public abstract void setOverflowBin(double value)
```

Megadja a túlcsorduló bin egyéni értékét. Akkor alkalmazható, ha az IsAutomaticOverflowBin tulajdonság false, és az IsOverflowBin igaz.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |

### isUnderflowBin() {#isUnderflowBin--}
```
public abstract boolean isUnderflowBin()
```

Megadja, hogy alulcsorduló bin alkalmazásra került-e. Használja az IsAutomaticUnderflowBin és az UnderflowBin beállításokat az érték módosításához.

**Visszatérési érték:**
boolean
### setUnderflowBin(boolean value) {#setUnderflowBin-boolean-}
```
public abstract void setUnderflowBin(boolean value)
```

Megadja, hogy alulcsorduló bin alkalmazásra került-e. Használja az IsAutomaticUnderflowBin és az UnderflowBin beállításokat az érték módosításához.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticUnderflowBin() {#isAutomaticUnderflowBin--}
```
public abstract boolean isAutomaticUnderflowBin()
```

Megadja az automatikus alulcsorduló bin értékét. Ha false: az UnderflowBin tulajdonságot használja.

**Visszatérési érték:**
boolean
### setAutomaticUnderflowBin(boolean value) {#setAutomaticUnderflowBin-boolean-}
```
public abstract void setAutomaticUnderflowBin(boolean value)
```

Megadja az automatikus alulcsorduló bin értékét. Ha false: az UnderflowBin tulajdonságot használja.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getUnderflowBin() {#getUnderflowBin--}
```
public abstract double getUnderflowBin()
```

Megadja az alulcsorduló bin egyéni értékét. Akkor alkalmazható, ha az IsAutomaticUnderflowBin tulajdonság false, és az IsUnderflowBin igaz.

**Visszatérési érték:**
double
### setUnderflowBin(double value) {#setUnderflowBin-double-}
```
public abstract void setUnderflowBin(double value)
```

Megadja az alulcsorduló bin egyéni értékét. Akkor alkalmazható, ha az IsAutomaticUnderflowBin tulajdonság false, és az IsUnderflowBin igaz.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |