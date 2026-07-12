---
title: Axis
second_title: Aspose.Slides for Android Java API-re vonatkozó hivatkozás
description: Összevonja azt az objektumot, amely egy diagram tengelyét reprezentálja.
type: docs
url: /hu/com.aspose.slides/axis/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.IAxis](../../com.aspose.slides/iaxis)
```
public class Axis extends DomObject<AxesManager> implements IAxis
```

Összevonja azt az objektumot, amely egy chart tengelyét képviseli.

## Metódusok

| Method | Description |
| --- | --- |
| [getChart()](#getChart--) | Visszaadja a szülő chart-ot. |
| [getAxisBetweenCategories()](#getAxisBetweenCategories--) | Jeli, hogy az értéktengely áthalad-e a kategóriatengelyen a kategóriák között. |
| [setAxisBetweenCategories(boolean value)](#setAxisBetweenCategories-boolean-) | Jeli, hogy az értéktengely áthalad-e a kategóriatengelyen a kategóriák között. |
| [getCategoryAxisType()](#getCategoryAxisType--) | Megadja a kategóriatengely típusát. |
| [setCategoryAxisType(int value)](#setCategoryAxisType-int-) | Megadja a kategóriatengely típusát. |
| [setCategoryAxisTypeAutomatically()](#setCategoryAxisTypeAutomatically--) | Beállítja az IAxis.CategoryAxisType tulajdonságot egy olyan értékkel, amely automatikusan kerül meghatározásra a tengely adatai alapján. |
| [getCrossAt()](#getCrossAt--) | Jeli azt a pontot a tengelyen, ahol a merőleges tengely áthalad rajta. |
| [setCrossAt(float value)](#setCrossAt-float-) | Jeli azt a pontot a tengelyen, ahol a merőleges tengely áthalad rajta. |
| [getDisplayUnit()](#getDisplayUnit--) | Megadja a megjelenítő egységek méretezési értékét az értéktengelyhez. |
| [setDisplayUnit(int value)](#setDisplayUnit-int-) | Megadja a megjelenítő egységek méretezési értékét az értéktengelyhez. |
| [getActualMaxValue()](#getActualMaxValue--) | Megadja a tengely tényleges maximális értékét. |
| [getActualMinValue()](#getActualMinValue--) | Megadja a tengely tényleges minimális értékét. |
| [getActualMajorUnit()](#getActualMajorUnit--) | Megadja a tengely tényleges fő egységét. |
| [getActualMinorUnit()](#getActualMinorUnit--) | Megadja a tengely tényleges alsegységét. |
| [getActualMajorUnitScale()](#getActualMajorUnitScale--) | Megadja a tengely tényleges fő egység skáláját. |
| [getActualMinorUnitScale()](#getActualMinorUnitScale--) | Megadja a tengely tényleges alsegység skáláját. |
| [isAutomaticMaxValue()](#isAutomaticMaxValue--) | Jeli, hogy a maximális érték automatikusan van-e hozzárendelve. |
| [setAutomaticMaxValue(boolean value)](#setAutomaticMaxValue-boolean-) | Jeli, hogy a maximális érték automatikusan van-e hozzárendelve. |
| [getMaxValue()](#getMaxValue--) | Jeli a maximális értéket az értéktengelyen. |
| [setMaxValue(double value)](#setMaxValue-double-) | Jeli a maximális értéket az értéktengelyen. |
| [getMinorUnit()](#getMinorUnit--) | Jeli a kisebb egységeket a dátum vagy értéktengelyhez. |
| [setMinorUnit(double value)](#setMinorUnit-double-) | Jeli a kisebb egységeket a dátum vagy értéktengelyhez. |
| [isAutomaticMinorUnit()](#isAutomaticMinorUnit--) | Jeli, hogy a tengely kisebb egysége automatikusan van-e hozzárendelve. |
| [setAutomaticMinorUnit(boolean value)](#setAutomaticMinorUnit-boolean-) | Jeli, hogy a tengely kisebb egysége automatikusan van-e hozzárendelve. |
| [getMajorUnit()](#getMajorUnit--) | Jeli a fő egységeket a dátum vagy értéktengelyhez. |
| [setMajorUnit(double value)](#setMajorUnit-double-) | Jeli a fő egységeket a dátum vagy értéktengelyhez. |
| [isAutomaticMajorUnit()](#isAutomaticMajorUnit--) | Jeli, hogy a tengely fő egysége automatikusan van-e hozzárendelve. |
| [setAutomaticMajorUnit(boolean value)](#setAutomaticMajorUnit-boolean-) | Jeli, hogy a tengely fő egysége automatikusan van-e hozzárendelve. |
| [isAutomaticMinValue()](#isAutomaticMinValue--) | Jeli, hogy a minimális érték automatikusan van-e hozzárendelve. |
| [setAutomaticMinValue(boolean value)](#setAutomaticMinValue-boolean-) | Jeli, hogy a minimális érték automatikusan van-e hozzárendelve. |
| [getMinValue()](#getMinValue--) | Jeli a minimális értéket az értéktengelyen. |
| [setMinValue(double value)](#setMinValue-double-) | Jeli a minimális értéket az értéktengelyen. |
| [isLogarithmic()](#isLogarithmic--) | Jeli, hogy az értéktengely skálatípusa logaritmikus-e vagy sem. |
| [setLogarithmic(boolean value)](#setLogarithmic-boolean-) | Jeli, hogy az értéktengely skálatípusa logaritmikus-e vagy sem. |
| [getLogBase()](#getLogBase--) | Jeli a logaritmikus alapot. |
| [setLogBase(double value)](#setLogBase-double-) | Jeli a logaritmikus alapot. |
| [isPlotOrderReversed()](#isPlotOrderReversed--) | Jeli, hogy a MS PowerPoint az adatpontokat az utolsótól az elsőig ábrázolja-e. |
| [setPlotOrderReversed(boolean value)](#setPlotOrderReversed-boolean-) | Jeli, hogy a MS PowerPoint az adatpontokat az utolsótól az elsőig ábrázolja-e. |
| [isVisible()](#isVisible--) | Jeli, hogy a tengely látható-e. |
| [setVisible(boolean value)](#setVisible-boolean-) | Jeli, hogy a tengely látható-e. |
| [getMajorTickMark()](#getMajorTickMark--) | Jeli a fő jelölőpont típusát a megadott tengelyen. |
| [setMajorTickMark(int value)](#setMajorTickMark-int-) | Jeli a fő jelölőpont típusát a megadott tengelyen. |
| [getMinorTickMark()](#getMinorTickMark--) | Jeli a kisebb jelölőpont típusát a megadott tengelyen. |
| [setMinorTickMark(int value)](#setMinorTickMark-int-) | Jeli a kisebb jelölőpont típusát a megadott tengelyen. |
| [getTickLabelPosition()](#getTickLabelPosition--) | Jeli a jelölőcímkék pozícióját a megadott tengelyen. |
| [setTickLabelPosition(int value)](#setTickLabelPosition-int-) | Jeli a jelölőcímkék pozícióját a megadott tengelyen. |
| [getMajorUnitScale()](#getMajorUnitScale--) | Jeli a fő egység skáláját a dátumtengelyen. |
| [setMajorUnitScale(int value)](#setMajorUnitScale-int-) | Jeli a fő egység skáláját a dátumtengelyen. |
| [getMinorUnitScale()](#getMinorUnitScale--) | Jeli a fő egység skáláját a dátumtengelyen. |
| [setMinorUnitScale(int value)](#setMinorUnitScale-int-) | Jeli a fő egység skáláját a dátumtengelyen. |
| [getBaseUnitScale()](#getBaseUnitScale--) | Megadja a legkisebb időegységet, amely a dátumtengelyen megjelenik. |
| [setBaseUnitScale(int value)](#setBaseUnitScale-int-) | Megadja a legkisebb időegységet, amely a dátumtengelyen megjelenik. |
| [getMinorGridLinesFormat()](#getMinorGridLinesFormat--) | Jeli a kisebb rácsvonalak formátumát egy chart tengelyen. |
| [getMajorGridLinesFormat()](#getMajorGridLinesFormat--) | Jeli a nagyobb rácsvonalak formátumát egy chart tengelyen. |
| [getShowMinorGridLines()](#getShowMinorGridLines--) | A kisebb rácsvonal elrejtéséhez állítsa a MinorGridLinesFormat.Line.FillFormat.FillType értékét FillType.NoFill-re. |
| [getShowMajorGridLines()](#getShowMajorGridLines--) | A nagyobb rácsvonal elrejtéséhez állítsa a MajorGridLinesFormat.Line.FillFormat.FillType értékét FillType.NoFill-re. |
| [getFormat()](#getFormat--) | Jeli a tengely formátumát. |
| [getTextFormat()](#getTextFormat--) | Jeli a szöveg formátumát. |
| [getTitle()](#getTitle--) | Lekéri a tengely címét. |
| [getCrossType()](#getCrossType--) | Jeli a CrossType-ot a megadott tengelyen, ahol a másik tengely kereszteződik. |
| [setCrossType(int value)](#setCrossType-int-) | Jeli a CrossType-ot a megadott tengelyen, ahol a másik tengely kereszteződik. |
| [getPosition()](#getPosition--) | Jeli a tengely pozícióját. |
| [setPosition(int value)](#setPosition-int-) | Jeli a tengely pozícióját. |
| [hasTitle()](#hasTitle--) | Megállapítja, hogy egy tengelynek látható címe van-e. |
| [setTitle(boolean value)](#setTitle-boolean-) | Megállapítja, hogy egy tengelynek látható címe van-e. |
| [getNumberFormat()](#getNumberFormat--) | Jeli a formátum karakterláncot az Axis Labels-hez. |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | Jeli a formátum karakterláncot az Axis Labels-hez. |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | Jeli, hogy a formátum a forrás adatokra hivatkozik. |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | Jeli, hogy a formátum a forrás adatokra hivatkozik. |
| [getTickLabelRotationAngle()](#getTickLabelRotationAngle--) | Jeli a jelölőcímkék forgatási szögét. |
| [setTickLabelRotationAngle(float value)](#setTickLabelRotationAngle-float-) | Jeli a jelölőcímkék forgatási szögét. |
| [getTickLabelSpacing()](#getTickLabelSpacing--) | Megadja, hány jelölőcímkét kell kihagyni a kirajzolandó címkék között. |
| [setTickLabelSpacing(long value)](#setTickLabelSpacing-long-) | Megadja, hány jelölőcímkét kell kihagyni a kirajzolandó címkék között. |
| [isAutomaticTickLabelSpacing()](#isAutomaticTickLabelSpacing--) | Megadja a automatikus jelölőcímke távolság értékét. |
| [setAutomaticTickLabelSpacing(boolean value)](#setAutomaticTickLabelSpacing-boolean-) | Megadja a automatikus jelölőcímke távolság értékét. |
| [getTickMarksSpacing()](#getTickMarksSpacing--) | Megadja, hány jelölőpontot kell kihagyni, mielőtt a következőt kirajzolná. |
| [setTickMarksSpacing(long value)](#setTickMarksSpacing-long-) | Megadja, hány jelölőpontot kell kihagyni, mielőtt a következőt kirajzolná. |
| [isAutomaticTickMarksSpacing()](#isAutomaticTickMarksSpacing--) | Megadja a automatikus jelölőpontok távolság értékét. |
| [setAutomaticTickMarksSpacing(boolean value)](#setAutomaticTickMarksSpacing-boolean-) | Megadja a automatikus jelölőpontok távolság értékét. |
| [getLabelOffset()](#getLabelOffset--) | Megadja a címkék távolságát a tengelytől. |
| [setLabelOffset(int value)](#setLabelOffset-int-) | Megadja a címkék távolságát a tengelytől. |
| [getAggregationType()](#getAggregationType--) | Jeli a kategóriatengely aggregációs típusát (csoportosítás). |
| [setAggregationType(int value)](#setAggregationType-int-) | Jeli a kategóriatengely aggregációs típusát (csoportosítás). |
| [getBinWidth()](#getBinWidth--) | Megadja a bin szélességet, amikor az AggregationType tulajdonság értéke AxisAggregationType.ByBinWidth. |
| [setBinWidth(double value)](#setBinWidth-double-) | Megadja a bin szélességet, amikor az AggregationType tulajdonság értéke AxisAggregationType.ByBinWidth. |
| [getNumberOfBins()](#getNumberOfBins--) | Megadja a binok számát, amikor az AggregationType tulajdonság értéke AxisAggregationType.ByNumberOfBins. |
| [setNumberOfBins(long value)](#setNumberOfBins-long-) | Megadja a binok számát, amikor az AggregationType tulajdonság értéke AxisAggregationType.ByNumberOfBins. |
| [isOverflowBin()](#isOverflowBin--) | Megadja, hogy az overflow bin alkalmazva van-e. |
| [setOverflowBin(boolean value)](#setOverflowBin-boolean-) | Megadja, hogy az overflow bin alkalmazva van-e. |
| [isAutomaticOverflowBin()](#isAutomaticOverflowBin--) | Megadja az automatikus overflow bin értékét. |
| [setAutomaticOverflowBin(boolean value)](#setAutomaticOverflowBin-boolean-) | Megadja az automatikus overflow bin értékét. |
| [getOverflowBin()](#getOverflowBin--) | Megadja az overflow bin egyéni értékét. |
| [setOverflowBin(double value)](#setOverflowBin-double-) | Megadja az overflow bin egyéni értékét. |
| [isUnderflowBin()](#isUnderflowBin--) | Megadja, hogy az underflow bin alkalmazva van-e. |
| [setUnderflowBin(boolean value)](#setUnderflowBin-boolean-) | Megadja, hogy az underflow bin alkalmazva van-e. |
| [isAutomaticUnderflowBin()](#isAutomaticUnderflowBin--) | Megadja az automatikus underflow bin értékét. |
| [setAutomaticUnderflowBin(boolean value)](#setAutomaticUnderflowBin-boolean-) | Megadja az automatikus underflow bin értékét. |
| [getUnderflowBin()](#getUnderflowBin--) | Megadja az underflow bin egyéni értékét. |
| [setUnderflowBin(double value)](#setUnderflowBin-double-) | Megadja az underflow bin egyéni értékét. |
| [getSlide()](#getSlide--) | Visszaadja a FillFormat szülő slide-át. |
| [getPresentation()](#getPresentation--) | Visszaadja a FillFormat szülő prezentációját. |

### getChart() {#getChart--}
```
public final IChart getChart()
```

Visszaadja a szülő chart-ot. Csak olvasható [IChart](../../com.aspose.slides/ichart).

**Visszatér:**
[IChart](../../com.aspose.slides/ichart)

### getAxisBetweenCategories() {#getAxisBetweenCategories--}
```
public final boolean getAxisBetweenCategories()
```

Jeli, hogy az értéktengely áthalad-e a kategóriatengelyen a kategóriák között. Ez a tulajdonság csak a kategóriatengelyekre vonatkozik, és nem alkalmazható 3-D chartokra. Olvasás/írás boolean.

**Visszatér:**
boolean

### setAxisBetweenCategories(boolean value) {#setAxisBetweenCategories-boolean-}
```
public final void setAxisBetweenCategories(boolean value)
```

Jeli, hogy az értéktengely áthalad-e a kategóriatengelyen a kategóriák között. Ez a tulajdonság csak a kategóriatengelyekre vonatkozik, és nem alkalmazható 3-D chartokra. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getCategoryAxisType() {#getCategoryAxisType--}
```
public final int getCategoryAxisType()
```

Megadja a kategóriatengely típusát. Olvasás/írás [CategoryAxisType](../../com.aspose.slides/categoryaxistype).

**Visszatér:**
int

### setCategoryAxisType(int value) {#setCategoryAxisType-int-}
```
public final void setCategoryAxisType(int value)
```

Megadja a kategóriatengely típusát. Olvasás/írás [CategoryAxisType](../../com.aspose.slides/categoryaxistype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### setCategoryAxisTypeAutomatically() {#setCategoryAxisTypeAutomatically--}
```
public final void setCategoryAxisTypeAutomatically()
```

Beállítja az IAxis.CategoryAxisType tulajdonságot egy olyan értékkel, amely automatikusan kerül meghatározásra a tengely adatai alapján.

### getCrossAt() {#getCrossAt--}
```
public final float getCrossAt()
```

Jeli a pontot a tengelyen, ahol a merőleges tengely áthalad rajta. Olvasás/írás float.

**Visszatér:**
float

### setCrossAt(float value) {#setCrossAt-float-}
```
public final void setCrossAt(float value)
```

Jeli a pontot a tengelyen, ahol a merőleges tengely áthalad rajta. Olvasás/írás float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getDisplayUnit() {#getDisplayUnit--}
```
public final int getDisplayUnit()
```

Megadja a megjelenítő egységek méretezési értékét az értéktengelyhez. Olvasás/írás [DisplayUnitType](../../com.aspose.slides/displayunittype).

**Visszatér:**
int

### setDisplayUnit(int value) {#setDisplayUnit-int-}
```
public final void setDisplayUnit(int value)
```

Megadja a megjelenítő egységek méretezési értékét az értéktengelyhez. Olvasás/írás [DisplayUnitType](../../com.aspose.slides/displayunittype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getActualMaxValue() {#getActualMaxValue--}
```
public final double getActualMaxValue()
```

Megadja a tengely tényleges maximális értékét. Hívja meg az IChart.ValidateChartLayout() metódust előzőleg a tényleges érték lekéréséhez.

**Visszatér:**
double

### getActualMinValue() {#getActualMinValue--}
```
public final double getActualMinValue()
```

Megadja a tengely tényleges minimális értékét. Hívja meg az IChart.ValidateChartLayout() metódust előzőleg a tényleges érték lekéréséhez.

**Visszatér:**
double

### getActualMajorUnit() {#getActualMajorUnit--}
```
public final double getActualMajorUnit()
```

Megadja a tengely tényleges fő egységét. Hívja meg az IChart.ValidateChartLayout() metódust előzőleg a tényleges érték lekéréséhez.

**Visszatér:**
double

### getActualMinorUnit() {#getActualMinorUnit--}
```
public final double getActualMinorUnit()
```

Megadja a tengely tényleges alsegységét. Hívja meg az IChart.ValidateChartLayout() metódust előzőleg a tényleges érték lekéréséhez.

**Visszatér:**
double

### getActualMajorUnitScale() {#getActualMajorUnitScale--}
```
public final int getActualMajorUnitScale()
```

Megadja a tengely tényleges fő egység skáláját. Hívja meg az IChart.ValidateChartLayout() metódust előzőleg a tényleges érték lekéréséhez.

**Visszatér:**
int

### getActualMinorUnitScale() {#getActualMinorUnitScale--}
```
public final int getActualMinorUnitScale()
```

Megadja a tengely tényleges alsegység skáláját. Hívja meg az IChart.ValidateChartLayout() metódust előzőleg a tényleges érték lekéréséhez.

**Visszatér:**
int

### isAutomaticMaxValue() {#isAutomaticMaxValue--}
```
public final boolean isAutomaticMaxValue()
```

Jeli, hogy a maximális érték automatikusan van-e hozzárendelve. Olvasás/írás boolean.

**Visszatér:**
boolean

### setAutomaticMaxValue(boolean value) {#setAutomaticMaxValue-boolean-}
```
public final void setAutomaticMaxValue(boolean value)
```

Jeli, hogy a maximális érték automatikusan van-e hozzárendelve. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getMaxValue() {#getMaxValue--}
```
public final double getMaxValue()
```

Jeli a maximális értéket az értéktengelyen. Olvasás/írás double.

**Visszatér:**
double

### setMaxValue(double value) {#setMaxValue-double-}
```
public final void setMaxValue(double value)
```

Jeli a maximális értéket az értéktengelyen. Olvasás/írás double.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |

### getMinorUnit() {#getMinorUnit--}
```
public final double getMinorUnit()
```

Jeli a kisebb egységeket a dátum vagy értéktengelyhez. Olvasás/írás double.

**Visszatér:**
double

### setMinorUnit(double value) {#setMinorUnit-double-}
```
public final void setMinorUnit(double value)
```

Jeli a kisebb egységeket a dátum vagy értéktengelyhez. Olvasás/írás double.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |

### isAutomaticMinorUnit() {#isAutomaticMinorUnit--}
```
public final boolean isAutomaticMinorUnit()
```

Jeli, hogy a tengely kisebb egysége automatikusan van-e hozzárendelve. Olvasás/írás boolean.

**Visszatér:**
boolean

### setAutomaticMinorUnit(boolean value) {#setAutomaticMinorUnit-boolean-}
```
public final void setAutomaticMinorUnit(boolean value)
```

Jeli, hogy a tengely kisebb egysége automatikusan van-e hozzárendelve. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getMajorUnit() {#getMajorUnit--}
```
public final double getMajorUnit()
```

Jeli a fő egységeket a dátum vagy értéktengelyhez. Olvasás/írás double.

**Visszatér:**
double

### setMajorUnit(double value) {#setMajorUnit-double-}
```
public final void setMajorUnit(double value)
```

Jeli a fő egységeket a dátum vagy értéktengelyhez. Olvasás/írás double.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |

### isAutomaticMajorUnit() {#isAutomaticMajorUnit--}
```
public final boolean isAutomaticMajorUnit()
```

Jeli, hogy a tengely fő egysége automatikusan van-e hozzárendelve. Olvasás/írás boolean.

**Visszatér:**
boolean

### setAutomaticMajorUnit(boolean value) {#setAutomaticMajorUnit-boolean-}
```
public final void setAutomaticMajorUnit(boolean value)
```

Jeli, hogy a tengely fő egysége automatikusan van-e hozzárendelve. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticMinValue() {#isAutomaticMinValue--}
```
public final boolean isAutomaticMinValue()
```

Jeli, hogy a minimális érték automatikusan van-e hozzárendelve. Olvasás/írás boolean.

**Visszatér:**
boolean

### setAutomaticMinValue(boolean value) {#setAutomaticMinValue-boolean-}
```
public final void setAutomaticMinValue(boolean value)
```

Jeli, hogy a minimális érték automatikusan van-e hozzárendelve. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getMinValue() {#getMinValue--}
```
public final double getMinValue()
```

Jeli a minimális értéket az értéktengelyen. Olvasás/írás double.

**Visszatér:**
double

### setMinValue(double value) {#setMinValue-double-}
```
public final void setMinValue(double value)
```

Jeli a minimális értéket az értéktengelyen. Olvasás/írás double.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |

### isLogarithmic() {#isLogarithmic--}
```
public final boolean isLogarithmic()
```

Jeli, hogy az értéktengely skálatípusa logaritmikus-e vagy sem. Olvasás/írás boolean.

**Visszatér:**
boolean

### setLogarithmic(boolean value) {#setLogarithmic-boolean-}
```
public final void setLogarithmic(boolean value)
```

Jeli, hogy az értéktengely skálatípusa logaritmikus-e vagy sem. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getLogBase() {#getLogBase--}
```
public final double getLogBase()
```

Jeli a logaritmikus alapot. Alapértelmezett érték 10. Olvasás/írás double.

**Visszatér:**
double

### setLogBase(double value) {#setLogBase-double-}
```
public final void setLogBase(double value)
```

Jeli a logaritmikus alapot. Alapértelmezett érték 10. Olvasás/írás double.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |

### isPlotOrderReversed() {#isPlotOrderReversed--}
```
public final boolean isPlotOrderReversed()
```

Jeli, hogy a MS PowerPoint az adatpontokat az utolsótól az elsőig ábrázolja-e. Olvasás/írás boolean.

**Visszatér:**
boolean

### setPlotOrderReversed(boolean value) {#setPlotOrderReversed-boolean-}
```
public final void setPlotOrderReversed(boolean value)
```

Jeli, hogy a MS PowerPoint az adatpontokat az utolsótól az elsőig ábrázolja-e. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

Jeli, hogy a tengely látható-e. Olvasás/írás boolean.

**Visszatér:**
boolean

### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```

Jeli, hogy a tengely látható-e. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getMajorTickMark() {#getMajorTickMark--}
```
public final int getMajorTickMark()
```

Jeli a fő jelölőpont típusát a megadott tengelyen. Olvasás/írás [TickMarkType](../../com.aspose.slides/tickmarktype).

**Visszatér:**
int

### setMajorTickMark(int value) {#setMajorTickMark-int-}
```
public final void setMajorTickMark(int value)
```

Jeli a fő jelölőpont típusát a megadott tengelyen. Olvasás/írás [TickMarkType](../../com.aspose.slides/tickmarktype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getMinorTickMark() {#getMinorTickMark--}
```
public final int getMinorTickMark()
```

Jeli a kisebb jelölőpont típusát a megadott tengelyen. Olvasás/írás [TickMarkType](../../com.aspose.slides/tickmarktype).

**Visszatér:**
int

### setMinorTickMark(int value) {#setMinorTickMark-int-}
```
public final void setMinorTickMark(int value)
```

Jeli a kisebb jelölőpont típusát a megadott tengelyen. Olvasás/írás [TickMarkType](../../com.aspose.slides/tickmarktype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getTickLabelPosition() {#getTickLabelPosition--}
```
public final int getTickLabelPosition()
```

Jeli a jelölőcímkék pozícióját a megadott tengelyen. Olvasás/írás [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**Visszatér:**
int

### setTickLabelPosition(int value) {#setTickLabelPosition-int-}
```
public final void setTickLabelPosition(int value)
```

Jeli a jelölőcímkék pozícióját a megadott tengelyen. Olvasás/írás [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getMajorUnitScale() {#getMajorUnitScale--}
```
public final int getMajorUnitScale()
```

Jeli a fő egység skáláját a dátumtengelyen. Olvasás/írás [TimeUnitType](../../com.aspose.slides/timeunittype).

**Visszatér:**
int

### setMajorUnitScale(int value) {#setMajorUnitScale-int-}
```
public final void setMajorUnitScale(int value)
```

Jeli a fő egység skáláját a dátumtengelyen. Olvasás/írás [TimeUnitType](../../com.aspose.slides/timeunittype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getMinorUnitScale() {#getMinorUnitScale--}
```
public final int getMinorUnitScale()
```

Jeli a fő egység skáláját a dátumtengelyen. Olvasás/írás [TimeUnitType](../../com.aspose.slides/timeunittype).

**Visszatér:**
int

### setMinorUnitScale(int value) {#setMinorUnitScale-int-}
```
public final void setMinorUnitScale(int value)
```

Jeli a fő egység skáláját a dátumtengelyen. Olvasás/írás [TimeUnitType](../../com.aspose.slides/timeunittype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getBaseUnitScale() {#getBaseUnitScale--}
```
public final int getBaseUnitScale()
```

Megadja a legkisebb időegységet, amely a dátumtengelyen megjelenik. Olvasás/írás [TimeUnitType](../../com.aspose.slides/timeunittype).

**Visszatér:**
int

### setBaseUnitScale(int value) {#setBaseUnitScale-int-}
```
public final void setBaseUnitScale(int value)
```

Megadja a legkisebb időegységet, amely a dátumtengelyen megjelenik. Olvasás/írás [TimeUnitType](../../com.aspose.slides/timeunittype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getMinorGridLinesFormat() {#getMinorGridLinesFormat--}
```
public final IChartLinesFormat getMinorGridLinesFormat()
```

Jeli a kisebb rácsvonalak formátumát egy chart tengelyen. Csak olvasható [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**Visszatér:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getMajorGridLinesFormat() {#getMajorGridLinesFormat--}
```
public final IChartLinesFormat getMajorGridLinesFormat()
```

Jeli a nagyobb rácsvonalak formátumát egy chart tengelyen. Csak olvasható [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**Visszatér:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getShowMinorGridLines() {#getShowMinorGridLines--}
```
public final boolean getShowMinorGridLines()
```

A kisebb rácsvonal elrejtéséhez állítsa a MinorGridLinesFormat.Line.FillFormat.FillType értékét FillType.NoFill-re. Csak olvasható boolean.

**Visszatér:**
boolean

### getShowMajorGridLines() {#getShowMajorGridLines--}
```
public.  

```

A nagyobb rácsvonal elrejtéséhez állítsa a MajorGridLinesFormat.Line.FillFormat.FillType értékét FillType.NoFill-re. Csak olvasható boolean.

**Visszatér:**
boolean

### getFormat() {#getFormat--}
```
public final IAxisFormat getFormat()
```

Jeli a tengely formátumát. Csak olvasható [IAxisFormat](../../com.aspose.slides/iaxisformat).

**Visszatér:**
[IAxisFormat](../../com.aspose.slides/iaxisformat)

### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

Jeli a szöveg formátumát. Csak olvasható [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Visszatér:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)

### getTitle() {#getTitle--}
```
public final IChartTitle getTitle()
```

Lekéri a tengely címét. Csak olvasható [IChartTitle](../../com.aspose.slides/icharttitle).

**Visszatér:**
[IChartTitle](../../com.aspose.slides/icharttitle)

### getCrossType() {#getCrossType--}
```
public final int getCrossType()
```

Jeli a CrossType-ot a megadott tengelyen, ahol a másik tengely kereszteződik. Olvasás/írás [CrossesType](../../com.aspose.slides/crossestype).

**Visszatér:**
int

### setCrossType(int value) {#setCrossType-int-}
```
public final void setCrossType(int value)
```

Jeli a CrossType-ot a megadott tengelyen, ahol a másik tengely kereszteződik. Olvasás/írás [CrossesType](../../com.aspose.slides/crossestype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getPosition() {#getPosition--}
```
public final int getPosition()
```

Jeli a tengely pozícióját. Olvasás/írás [AxisPositionType](../../com.aspose.slides/axispositiontype).

**Visszatér:**
int

### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```

Jeli a tengely pozícióját. Olvasás/írás [AxisPositionType](../../com.aspose.slides/axispositiontype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### hasTitle() {#hasTitle--}
```
public final boolean hasTitle()
```

Megállapítja, hogy egy tengelynek látható címe van-e. Olvasás/írás boolean.

**Visszatér:**
boolean

### setTitle(boolean value) {#setTitle-boolean-}
```
public final void setTitle(boolean value)
```

Megállapítja, hogy egy tengelynek látható címe van-e. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public final String getNumberFormat()
```

Jeli a formátum karakterláncot az Axis Labels-hez. Olvasás/írás String.

**Visszatér:**
java.lang.String

### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public final void setNumberFormat(String value)
```

Jeli a formátum karakterláncot az Axis Labels-hez. Olvasás/írás String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public final boolean isNumberFormatLinkedToSource()
```

Jeli, hogy a formátum a forrás adatokra hivatkozik. Olvasás/írás boolean.

**Visszatér:**
boolean

### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public final void setNumberFormatLinkedToSource(boolean value)
```

Jeli, hogy a formátum a forrás adatokra hivatkozik. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getTickLabelRotationAngle() {#getTickLabelRotationAngle--}
```
public final float getTickLabelRotationAngle()
```

Jeli a jelölőcímkék forgatási szögét. Olvasás/írás float.

**Visszatér:**
float

### setTickLabelRotationAngle(float value) {#setTickLabelRotationAngle-float-}
```
public final void setTickLabelRotationAngle(float value)
```

Jeli a jelölőcímkék forgatási szögét. Olvasás/írás float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getTickLabelSpacing() {#getTickLabelSpacing--}
```
public final long getTickLabelSpacing()
```

Megadja, hány jelölőcímkét kell kihagyni a kirajzolandó címkék között. Alkalmazva a kategória vagy sorozat tengelyen. Olvasás/írás long.

**Visszatér:**
long

### setTickLabelSpacing(long value) {#setTickLabelSpacing-long-}
```
public final void setTickLabelSpacing(long value)
```

Megadja, hány jelölőcímkét kell kihagyni a kirajzolandó címkék között. Alkalmazva a kategória vagy sorozat tengelyen. Olvasás/írás long.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickLabelSpacing() {#isAutomaticTickLabelSpacing--}
```
public final boolean isAutomaticTickLabelSpacing()
```

Megadja a automatikus jelölőcímke távolság értékét. Ha false: használja a TickLabelSpacing tulajdonságot. Olvasás/írás boolean.

**Visszatér:**
boolean

### setAutomaticTickLabelSpacing(boolean value) {#setAutomaticTickLabelSpacing-boolean-}
```
public final void setAutomaticTickLabelSpacing(boolean value)
```

Megadja a automatikus jelölőcímke távolság értékét. Ha false: használja a TickLabelSpacing tulajdonságot. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getTickMarksSpacing() {#getTickMarksSpacing--}
```
public final long getTickMarksSpacing()
```

Megadja, hány jelölőpontot kell kihagyni, mielőtt a következőt kirajzolná. Alkalmazva a kategória vagy sorozat tengelyen. Olvasás/írás int.

**Visszatér:**
long

### setTickMarksSpacing(long value) {#setTickMarksSpacing-long-}
```
public final void setTickMarksSpacing(long value)
```

Megadja, hány jelölőpontot kell kihagyni, mielőtt a következőt kirajzolná. Alkalmazva a kategória vagy sorozat tengelyen. Olvasás/írás int.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickMarksSpacing() {#isAutomaticTickMarksSpacing--}
```
public final boolean isAutomaticTickMarksSpacing()
```

Megadja a automatikus jelölőpontok távolság értékét. Ha false: használja a TickMarksSpacing tulajdonságot. Olvasás/írás boolean.

**Visszatér:**
boolean

### setAutomaticTickMarksSpacing(boolean value) {#setAutomaticTickMarksSpacing-boolean-}
```
public final void setAutomaticTickMarksSpacing(boolean value)
```

Megadja a automatikus jelölőpontok távolság értékét. Ha false: használja a TickMarksSpacing tulajdonságot. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getLabelOffset() {#getLabelOffset--}
```
public final int getLabelOffset()
```

Megadja a címkék távolságát a tengelytől. Alkalmazva a kategória vagy dátum tengelyen. Az értéknek 0 % és 1000 % között kell lennie. Olvasás/írás int.

**Visszatér:**
int

### setLabelOffset(int value) {#setLabelOffset-int-}
```
public final void setLabelOffset(int value)
```

Megadja a címkék távolságát a tengelytől. Alkalmazva a kategória vagy dátum tengelyen. Az értéknek 0 % és 1000 % között kell lennie. Olvasás/írás int.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getAggregationType() {#getAggregationType--}
```
public final int getAggregationType()
```

Jeli a kategóriatengely aggregációs típusát (csoportosítás). Alkalmazva a kategórián. Csak Histograma vagy HistogramPareto sorozatok esetén használható.

**Visszatér:**
int

### setAggregationType(int value) {#setAggregationType-int-}
```
public final void setAggregationType(int value)
```

Jeli a kategóriatengely aggregációs típusát (csoportosítás). Alkalmazva a kategórián. Csak Histograma vagy HistogramPareto sorozatok esetén használható.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getBinWidth() {#getBinWidth--}
```
public final double getBinWidth()
```

Megadja a bin szélességet, amikor az AggregationType tulajdonság értéke AxisAggregationType.ByBinWidth. Alkalmazva a kategóriatengelyen. Csak Histograma vagy HistogramPareto sorozatok esetén használható.

**Visszatér:**
double

### setBinWidth(double value) {#setBinWidth-double-}
```
public final void setBinWidth(double value)
```

Megadja a bin szélességet, amikor az AggregationType tulajdonság értéke AxisAggregationType.ByBinWidth. Alkalmazva a kategóriatengelyen. Csak Histograma vagy HistogramPareto sorozatok esetén használható.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |

### getNumberOfBins() {#getNumberOfBins--}
```
public final long getNumberOfBins()
```

Megadja a binok számát, amikor az AggregationType tulajdonság értéke AxisAggregationType.ByNumberOfBins. Alkalmazva a kategóriatengelyen. Csak Histograma vagy HistogramPareto sorozatok esetén használható.

**Visszatér:**
long

### setNumberOfBins(long value) {#setNumberOfBins-long-}
```
public final void setNumberOfBins(long value)
```

Megadja a binok számát, amikor az AggregationType tulajdonság értéke AxisAggregationType.ByNumberOfBins. Alkalmazva a kategóriatengelyen. Csak Histograma vagy HistogramPareto sorozatok esetén használható.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | long |  |

### isOverflowBin() {#isOverflowBin--}
```
public final boolean isOverflowBin()
```

Megadja, hogy az overflow bin alkalmazva van-e. Használja az IsAutomaticOverflowBin és az OverflowBin tulajdonságokat az overflow bin értékének beállításához.

**Visszatér:**
boolean

### setOverflowBin(boolean value) {#setOverflowBin-boolean-}
```
public final void setOverflowBin(boolean value)
```

Megadja, hogy az overflow bin alkalmazva van-e. Használja az IsAutomaticOverflowBin és az OverflowBin tulajdonságokat az overflow bin értékének beállításához.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticOverflowBin() {#isAutomaticOverflowBin--}
```
public final boolean isAutomaticOverflowBin()
```

Megadja az automatikus overflow bin értékét. Ha false: használja az OverflowBin tulajdonságot.

**Visszatér:**
boolean

### setAutomaticOverflowBin(boolean value) {#setAutomaticOverflowBin-boolean-}
```
public final void setAutomaticOverflowBin(boolean value)
```

Megadja az automatikus overflow bin értékét. Ha false: használja az OverflowBin tulajdonságot.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getOverflowBin() {#getOverflowBin--}
```
public final double getOverflowBin()
```

Megadja az overflow bin egyéni értékét. Alkalmazva, amikor az IsAutomaticOverflowBin tulajdonság false, és az IsOverflowBin tulajdonság true.

**Visszatér:**
double

### setOverflowBin(double value) {#setOverflowBin-double-}
```
public final void setOverflowBin(double value)
```

Megadja az overflow bin egyéni értékét. Alkalmazva, amikor az IsAutomaticOverflowBin tulajdonság false, és az IsOverflowBin tulajdonság true.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |

### isUnderflowBin() {#isUnderflowBin--}
```
public final boolean isUnderflowBin()
```

Megadja, hogy az underflow bin alkalmazva van-e. Használja az IsAutomaticUnderflowBin és az UnderflowBin tulajdonságokat az underflow bin értékének beállításához.

**Visszatér:**
boolean

### setUnderflowBin(boolean value) {#setUnderflowBin-boolean-}
```
public final void setUnderflowBin(boolean value)
```

Megadja, hogy az underflow bin alkalmazva van-e. Használja az IsAutomaticUnderflowBin és az UnderflowBin tulajdonságokat az underflow bin értékének beállításához.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticUnderflowBin() {#isAutomaticUnderflowBin--}
```
public final boolean isAutomaticUnderflowBin()
```

Megadja az automatikus underflow bin értékét. Ha false: használja az UnderflowBin tulajdonságot.

**Visszatér:**
boolean

### setAutomaticUnderflowBin(boolean value) {#setAutomaticUnderflowBin-boolean-}
```
public final void setAutomaticUnderflowBin(boolean value)
```

Megadja az automatikus underflow bin értékét. Ha false: használja az UnderflowBin tulajdonságot.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getUnderflowBin() {#getUnderflowBin--}
```
public final double getUnderflowBin()
```

Megadja az underflow bin egyéni értékét. Alkalmazva, amikor az IsAutomaticUnderflowBin tulajdonság false, és az IsUnderflowBin tulajdonság true.

**Visszatér:**
double

### setUnderflowBin(double value) {#setUnderflowBin-double-}
```
public final void setUnderflowBin(double value)
```

Megadja az underflow bin egyéni értékét. Alkalmazva, amikor az IsAutomaticUnderflowBin tulajdonság false, és az IsUnderflowBin tulajdonság true.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Visszaadja a FillFormat szülő slide-át. Csak olvasható [BaseSlide](../../com.aspose.slides/baseslide).

**Visszatér:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Visszaadja a FillFormat szülő prezentációját. Csak olvasható [IPresentation](../../com.aspose.slides/ipresentation).

**Visszatér:**
[IPresentation](../../com.aspose.slides/ipresentation)