---
title: Axis
second_title: Aspose.Slides Java API Referencia
description: Egy objektumot kapszuláz, amely a diagram tengelyét képviseli.
type: docs
url: /hu/com.aspose.slides/axis/
---
**Öröklődés:**
java.lang.Object, com.aspose.slides.DomObject

**Minden megvalósított interfész:**
[com.aspose.slides.IAxis](../../com.aspose.slides/iaxis)
```
public class Axis extends DomObject<AxesManager> implements IAxis
```

Tömöríti azt az objektumot, amely egy diagram tengelyét reprezentálja.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getChart()](#getChart--) | Visszaadja a szülődiagramot. |
| [getAxisBetweenCategories()](#getAxisBetweenCategories--) | Megadja, hogy az értéktengely keresztezi-e a kategóriatengelyt a kategóriák között. |
| [setAxisBetweenCategories(boolean value)](#setAxisBetweenCategories-boolean-) | Megadja, hogy az értéktengely keresztezi-e a kategóriatengelyt a kategóriák között. |
| [getCategoryAxisType()](#getCategoryAxisType--) | Meghatározza a kategóriatengely típusát. |
| [setCategoryAxisType(int value)](#setCategoryAxisType-int-) | Meghatározza a kategóriatengely típusát. |
| [setCategoryAxisTypeAutomatically()](#setCategoryAxisTypeAutomatically--) | Beállítja az IAxis.CategoryAxisType tulajdonságot egy értékkel, amely automatikusan kerül meghatározásra a tengely adatai alapján. |
| [getCrossAt()](#getCrossAt--) | Megadja a pontot a tengelyen, ahol a merőleges tengely kereszteződik vele. |
| [setCrossAt(float value)](#setCrossAt-float-) | Megadja a pontot a tengelyen, ahol a merőleges tengely kereszteződik vele. |
| [getDisplayUnit()](#getDisplayUnit--) | Meghatározza a megjelenítési egységek méretezési értékét az értéktengelyhez. |
| [setDisplayUnit(int value)](#setDisplayUnit-int-) | Meghatározza a megjelenítési egységek méretezési értékét az értéktengelyhez. |
| [getActualMaxValue()](#getActualMaxValue--) | Meghatározza a tényleges legnagyobb értéket a tengelyen. |
| [getActualMinValue()](#getActualMinValue--) | Meghatározza a tényleges legkisebb értéket a tengelyen. |
| [getActualMajorUnit()](#getActualMajorUnit--) | Meghatározza a tényleges főegységet a tengelyen. |
| [getActualMinorUnit()](#getActualMinorUnit--) | Meghatározza a tényleges alregységet a tengelyen. |
| [getActualMajorUnitScale()](#getActualMajorUnitScale--) | Meghatározza a tényleges főegység skáláját a tengelyen. |
| [getActualMinorUnitScale()](#getActualMinorUnitScale--) | Meghatározza a tényleges alregység skáláját a tengelyen. |
| [isAutomaticMaxValue()](#isAutomaticMaxValue--) | Jelzi, hogy a legnagyobb érték automatikusan van-e hozzárendelve. |
| [setAutomaticMaxValue(boolean value)](#setAutomaticMaxValue-boolean-) | Jelzi, hogy a legnagyobb érték automatikusan van-e hozzárendelve. |
| [getMaxValue()](#getMaxValue--) | Megjeleníti a legnagyobb értéket az értéktengelyen. |
| [setMaxValue(double value)](#setMaxValue-double-) | Megjeleníti a legnagyobb értéket az értéktengelyen. |
| [getMinorUnit()](#getMinorUnit--) | Megjeleníti a kisebb egységeket a dátum vagy értéktengelyen. |
| [setMinorUnit(double value)](#setMinorUnit-double-) | Megjeleníti a kisebb egységeket a dátum vagy értéktengelyen. |
| [isAutomaticMinorUnit()](#isAutomaticMinorUnit--) | Jelzi, hogy a tengely kisebb egysége automatikusan legyen-e hozzárendelve. |
| [setAutomaticMinorUnit(boolean value)](#setAutomaticMinorUnit-boolean-) | Jelzi, hogy a tengely kisebb egysége automatikusan legyen-e hozzárendelve. |
| [getMajorUnit()](#getMajorUnit--) | Megjeleníti a fő egységeket a dátum vagy értéktengelyen. |
| [setMajorUnit(double value)](#setMajorUnit-double-) | Megjeleníti a fő egységeket a dátum vagy értéktengelyen. |
| [isAutomaticMajorUnit()](#isAutomaticMajorUnit--) | Jelzi, hogy a tengely fő egysége automatikusan legyen-e hozzárendelve. |
| [setAutomaticMajorUnit(boolean value)](#setAutomaticMajorUnit-boolean-) | Jelzi, hogy a tengely fő egysége automatikusan legyen-e hozzárendelve. |
| [isAutomaticMinValue()](#isAutomaticMinValue--) | Jelzi, hogy a legkisebb érték automatikusan van-e hozzárendelve. |
| [setAutomaticMinValue(boolean value)](#setAutomaticMinValue-boolean-) | Jelzi, hogy a legkisebb érték automatikusan van-e hozzárendelve. |
| [getMinValue()](#getMinValue--) | Megjeleníti a legkisebb értéket az értéktengelyen. |
| [setMinValue(double value)](#setMinValue-double-) | Megjeleníti a legkisebb értéket az értéktengelyen. |
| [isLogarithmic()](#isLogarithmic--) | Megjeleníti, hogy az értéktengely skálatípusa logaritmikus-e vagy sem. |
| [setLogarithmic(boolean value)](#setLogarithmic-boolean-) | Megjeleníti, hogy az értéktengely skálatípusa logaritmikus-e vagy sem. |
| [getLogBase()](#getLogBase--) | Megjeleníti a logaritmikus alapot. |
| [setLogBase(double value)](#setLogBase-double-) | Megjeleníti a logaritmikus alapot. |
| [isPlotOrderReversed()](#isPlotOrderReversed--) | Megjeleníti, hogy a MS PowerPoint az adatpontokat az utolsótól az elsőig ábrázolja-e. |
| [setPlotOrderReversed(boolean value)](#setPlotOrderReversed-boolean-) | Megjeleníti, hogy a MS PowerPoint az adatpontokat az utolsótól az elsőig ábrázolja-e. |
| [isVisible()](#isVisible--) | Megjeleníti, hogy a tengely látható-e. |
| [setVisible(boolean value)](#setVisible-boolean-) | Megjeleníti, hogy a tengely látható-e. |
| [getMajorTickMark()](#getMajorTickMark--) | Megjeleníti a fő jelölő típusát a megadott tengelyen. |
| [setMajorTickMark(int value)](#setMajorTickMark-int-) | Megjeleníti a fő jelölő típusát a megadott tengelyen. |
| [getMinorTickMark()](#getMinorTickMark--) | Megjeleníti a kisebb jelölő típusát a megadott tengelyen. |
| [setMinorTickMark(int value)](#setMinorTickMark-int-) | Megjeleníti a kisebb jelölő típusát a megadott tengelyen. |
| [getTickLabelPosition()](#getTickLabelPosition--) | Megjeleníti a jelölőcímkék pozícióját a megadott tengelyen. |
| [setTickLabelPosition(int value)](#setTickLabelPosition-int-) | Megjeleníti a jelölőcímkék pozícióját a megadott tengelyen. |
| [getMajorUnitScale()](#getMajorUnitScale--) | Megjeleníti a fő egység skáláját a dátumtengelyen. |
| [setMajorUnitScale(int value)](#setMajorUnitScale-int-) | Megjeleníti a fő egység skáláját a dátumtengelyen. |
| [getMinorUnitScale()](#getMinorUnitScale--) | Megjeleníti a fő egység skáláját a dátumtengelyen. |
| [setMinorUnitScale(int value)](#setMinorUnitScale-int-) | Megjeleníti a fő egység skáláját a dátumtengelyen. |
| [getBaseUnitScale()](#getBaseUnitScale--) | Meghatározza a legkisebb időegységet, amely a dátumtengelyen megjelenik. |
| [setBaseUnitScale(int value)](#setBaseUnitScale-int-) | Meghatározza a legkisebb időegységet, amely a dátumtengelyen megjelenik. |
| [getMinorGridLinesFormat()](#getMinorGridLinesFormat--) | Megjeleníti a kisebb rácsvonalak formátumát egy diagramtengelyen. |
| [getMajorGridLinesFormat()](#getMajorGridLinesFormat--) | Megjeleníti a fő rácsvonalak formátumát egy diagramtengelyen. |
| [getShowMinorGridLines()](#getShowMinorGridLines--) | A kisebb rácsvonal elrejtéséhez állítsa a MinorGridLinesFormat.Line.FillFormat.FillType értékét FillType.NoFill-re. |
| [getShowMajorGridLines()](#getShowMajorGridLines--) | A nagyobb rácsvonal elrejtéséhez állítsa a MajorGridLinesFormat.Line.FillFormat.FillType értékét FillType.NoFill-re. |
| [getFormat()](#getFormat--) | Megjeleníti a tengely formátumát. |
| [getTextFormat()](#getTextFormat--) | Megjeleníti a szöveg formátumát. |
| [getTitle()](#getTitle--) | Lekéri a tengely címét. |
| [getCrossType()](#getCrossType--) | Megjeleníti a CrossType-ot a megadott tengelyen, ahol a másik tengely kereszteződik. |
| [setCrossType(int value)](#setCrossType-int-) | Megjeleníti a CrossType-ot a megadott tengelyen, ahol a másik tengely kereszteződik. |
| [getPosition()](#getPosition--) | Megjeleníti a tengely pozícióját. |
| [setPosition(int value)](#setPosition-int-) | Megjeleníti a tengely pozícióját. |
| [hasTitle()](#hasTitle--) | Megállapítja, hogy a tengelynek van-e látható címe. |
| [setTitle(boolean value)](#setTitle-boolean-) | Megállapítja, hogy a tengelynek van-e látható címe. |
| [getNumberFormat()](#getNumberFormat--) | Megjeleníti a formátum karakterláncot a tengelycímkékhez. |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | Megjeleníti a formátum karakterláncot a tengelycímkékhez. |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | Jelzi, hogy a formátum a forrásadatokhoz van-e kapcsolva. |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | Jelzi, hogy a formátum a forrásadatokhoz van-e kapcsolva. |
| [getTickLabelRotationAngle()](#getTickLabelRotationAngle--) | Megjeleníti a jelölőcímkék forgásszögét. |
| [setTickLabelRotationAngle(float value)](#setTickLabelRotationAngle-float-) | Megjeleníti a jelölőcímkék forgásszögét. |
| [getTickLabelSpacing()](#getTickLabelSpacing--) | Megadja, hány jelölőcímkét kell kihagyni a megjelenített címkék között. |
| [setTickLabelSpacing(long value)](#setTickLabelSpacing-long-) | Megadja, hány jelölőcímkét kell kihagyni a megjelenített címkék között. |
| [isAutomaticTickLabelSpacing()](#isAutomaticTickLabelSpacing--) | Megadja az automatikus jelölőcímke távolságértékét. |
| [setAutomaticTickLabelSpacing(boolean value)](#setAutomaticTickLabelSpacing-boolean-) | Megadja az automatikus jelölőcímke távolságértékét. |
| [getTickMarksSpacing()](#getTickMarksSpacing--) | Megadja, hány jelölőt kell kihagyni, mielőtt a következő megjelenik. |
| [setTickMarksSpacing(long value)](#setTickMarksSpacing-long-) | Megadja, hány jelölőt kell kihagyni, mielőtt a következő megjelenik. |
| [isAutomaticTickMarksSpacing()](#isAutomaticTickMarksSpacing--) | Megadja az automatikus jelölő távolságértékét. |
| [setAutomaticTickMarksSpacing(boolean value)](#setAutomaticTickMarksSpacing-boolean-) | Megadja az automatikus jelölő távolságértékét. |
| [getLabelOffset()](#getLabelOffset--) | Megadja a címkék távolságát a tengelytől. |
| [setLabelOffset(int value)](#setLabelOffset-int-) | Megadja a címkék távolságát a tengelytől. |
| [getAggregationType()](#getAggregationType--) | Megjeleníti a kategóriatengely aggregációs típusát (binning). |
| [setAggregationType(int value)](#setAggregationType-int-) | Megjeleníti a kategóriatengely aggregációs típusát (binning). |
| [getBinWidth()](#getBinWidth--) | Megadja a bin szélességét, amikor az AggregationType tulajdonság értéke AxisAggregationType.ByBinWidth. |
| [setBinWidth(double value)](#setBinWidth-double-) | Megadja a bin szélességét, amikor az AggregationType tulajdonság értéke AxisAggregationType.ByBinWidth. |
| [getNumberOfBins()](#getNumberOfBins--) | Megadja a bin-ek számát, amikor az AggregationType tulajdonság értéke AxisAggregationType.ByNumberOfBins. |
| [setNumberOfBins(long value)](#setNumberOfBins-long-) | Megadja a bin-ek számát, amikor az AggregationType tulajdonság értéke AxisAggregationType.ByNumberOfBins. |
| [isOverflowBin()](#isOverflowBin--) | Megadja, hogy túlcsorduló bin alkalmazásra kerül-e. |
| [setOverflowBin(boolean value)](#setOverflowBin-boolean-) | Megadja, hogy túlcsorduló bin alkalmazásra kerül-e. |
| [isAutomaticOverflowBin()](#isAutomaticOverflowBin--) | Megadja az automatikus túlcsorduló bin értékét. |
| [setAutomaticOverflowBin(boolean value)](#setAutomaticOverflowBin-boolean-) | Megadja az automatikus túlcsorduló bin értékét. |
| [getOverflowBin()](#getOverflowBin--) | Megadja a túlcsorduló bin egyéni értékét. |
| [setOverflowBin(double value)](#setOverflowBin-double-) | Megadja a túlcsorduló bin egyéni értékét. |
| [isUnderflowBin()](#isUnderflowBin--) | Megadja, hogy alulcsorduló bin alkalmazásra kerül-e. |
| [setUnderflowBin(boolean value)](#setUnderflowBin-boolean-) | Megadja, hogy alulcsorduló bin alkalmazásra kerül-e. |
| [isAutomaticUnderflowBin()](#isAutomaticUnderflowBin--) | Megadja az automatikus alulcsorduló bin értékét. |
| [setAutomaticUnderflowBin(boolean value)](#setAutomaticUnderflowBin-boolean-) | Megadja az automatikus alulcsorduló bin értékét. |
| [getUnderflowBin()](#getUnderflowBin--) | Megadja az alulcsorduló bin egyéni értékét. |
| [setUnderflowBin(double value)](#setUnderflowBin-double-) | Megadja az alulcsorduló bin egyéni értékét. |
| [getSlide()](#getSlide--) | Visszaadja a FillFormat szülő-diapozitívját. |
| [getPresentation()](#getPresentation--) | Visszaadja a FillFormat szülő-prezentációját. |
### getChart() {#getChart--}
```
public final IChart getChart()
```

Visszaadja a szülődiagramot. Csak olvasható [IChart](../../com.aspose.slides/ichart).

**Visszaadja:**
[IChart](../../com.aspose.slides/ichart)
### getAxisBetweenCategories() {#getAxisBetweenCategories--}
```
public final boolean getAxisBetweenCategories()
```

Megadja, hogy az értéktengely keresztezi-e a kategóriatengelyt a kategóriák között. Ez a tulajdonság csak kategória tengelyekre vonatkozik, és nem alkalmazható 3D-diagramokra. Olvasás/írás boolean.

**Visszaadja:**
boolean
### setAxisBetweenCategories(boolean value) {#setAxisBetweenCategories-boolean-}
```
public final void setAxisBetweenCategories(boolean value)
```

Megadja, hogy az értéktengely keresztezi-e a kategóriatengelyt a kategóriák között. Ez a tulajdonság csak kategória tengelyekre vonatkozik, és nem alkalmazható 3D-diagramokra. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |
### getCategoryAxisType() {#getCategoryAxisType--}
```
public final int getCategoryAxisType()
```

Meghatározza a kategóriatengely típusát. Olvasás/írás [CategoryAxisType](../../com.aspose.slides/categoryaxistype).

**Visszaadja:**
int
### setCategoryAxisType(int value) {#setCategoryAxisType-int-}
```
public final void setCategoryAxisType(int value)
```

Meghatározza a kategóriatengely típusát. Olvasás/írás [CategoryAxisType](../../com.aspose.slides/categoryaxistype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### setCategoryAxisTypeAutomatically() {#setCategoryAxisTypeAutomatically--}
```
public final void setCategoryAxisTypeAutomatically()
```

Beállítja az IAxis.CategoryAxisType tulajdonságot egy értékkel, amely automatikusan kerül meghatározásra a tengely adatai alapján.
### getCrossAt() {#getCrossAt--}
```
public final float getCrossAt()
```

Megadja a pontot a tengelyen, ahol a merőleges tengely kereszteződik vele. Olvasás/írás float.

**Visszaadja:**
float
### setCrossAt(float value) {#setCrossAt-float-}
```
public final void setCrossAt(float value)
```

Megadja a pontot a tengelyen, ahol a merőleges tengely kereszteződik vele. Olvasás/írás float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |
### getDisplayUnit() {#getDisplayUnit--}
```
public final int getDisplayUnit()
```

Meghatározza a megjelenítési egységek méretezési értékét az értéktengelyhez. Olvasás/írás [DisplayUnitType](../../com.aspose.slides/displayunittype).

**Visszaadja:**
int
### setDisplayUnit(int value) {#setDisplayUnit-int-}
```
public final void setDisplayUnit(int value)
```

Meghatározza a megjelenítési egységek méretezési értékét az értéktengelyhez. Olvasás/írás [DisplayUnitType](../../com.aspose.slides/displayunittype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### getActualMaxValue() {#getActualMaxValue--}
```
public final double getActualMaxValue()
```

Meghatározza a tényleges legnagyobb értéket a tengelyen. Call method IChart.ValidateChartLayout() previously to get actual value.

**Visszaadja:**
double
### getActualMinValue() {#getActualMinValue--}
```
public final double getActualMinValue()
```

Meghatározza a tényleges legkisebb értéket a tengelyen. Call method IChart.ValidateChartLayout() previously to get actual value.

**Visszaadja:**
double
### getActualMajorUnit() {#getActualMajorUnit--}
```
public final double getActualMajorUnit()
```

Meghatározza a tényleges főegységet a tengelyen. Call method IChart.ValidateChartLayout() previously to get actual value.

**Visszaadja:**
double
### getActualMinorUnit() {#getActualMinorUnit--}
```
public final double getActualMinorUnit()
```

Meghatározza a tényleges alregységet a tengelyen. Call method IChart.ValidateChartLayout() previously to get actual value.

**Visszaadja:**
double
### getActualMajorUnitScale() {#getActualMajorUnitScale--}
```
public final int getActualMajorUnitScale()
```

Meghatározza a tényleges főegység skáláját a tengelyen. Call method IChart.ValidateChartLayout() previously to get actual value.

**Visszaadja:**
int
### getActualMinorUnitScale() {#getActualMinorUnitScale--}
```
public final int getActualMinorUnitScale()
```

Meghatározza a tényleges alregység skáláját a tengelyen. Call method IChart.ValidateChartLayout() previously to get actual value.

**Visszaadja:**
int
### isAutomaticMaxValue() {#isAutomaticMaxValue--}
```
public final boolean isAutomaticMaxValue()
```

Jelzi, hogy a legnagyobb érték automatikusan van-e hozzárendelve. Olvasás/írás boolean.

**Visszaadja:**
boolean
### setAutomaticMaxValue(boolean value) {#setAutomaticMaxValue-boolean-}
```
public final void setAutomaticMaxValue(boolean value)
```

Jelzi, hogy a legnagyobb érték automatikusan van-e hozzárendelve. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |
### getMaxValue() {#getMaxValue--}
```
public final double getMaxValue()
```

Megjeleníti a legnagyobb értéket az értéktengelyen. Olvasás/írás double.

**Visszaadja:**
double
### setMaxValue(double value) {#setMaxValue-double-}
```
public final void setMaxValue(double value)
```

Megjeleníti a legnagyobb értéket az értéktengelyen. Olvasás/írás double.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |
### getMinorUnit() {#getMinorUnit--}
```
public final double getMinorUnit()
```

Megjeleníti a kisebb egységeket a dátum vagy értéktengelyen. Olvasás/írás double.

**Visszaadja:**
double
### setMinorUnit(double value) {#setMinorUnit-double-}
```
public final void setMinorUnit(double value)
```

Megjeleníti a kisebb egységeket a dátum vagy értéktengelyen. Olvasás/írás double.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |
### isAutomaticMinorUnit() {#isAutomaticMinorUnit--}
```
public final boolean isAutomaticMinorUnit()
```
Azt jelzi, hogy a tengely alárendelt egysége automatikusan van-e hozzárendelve. Olvasás/írás boolean.

**Visszatérési érték:**
boolean
### setAutomaticMinorUnit(boolean value) {#setAutomaticMinorUnit-boolean-}
```
public final void setAutomaticMinorUnit(boolean value)
```


Azt jelzi, hogy a tengely alárendelt egysége automatikusan van-e hozzárendelve. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getMajorUnit() {#getMajorUnit--}
```
public final double getMajorUnit()
```


A dátum vagy érték tengely fő egységeit képviseli. Olvasás/írás double.

**Visszatérési érték:**
double
### setMajorUnit(double value) {#setMajorUnit-double-}
```
public final void setMajorUnit(double value)
```


A dátum vagy érték tengely fő egységeit képviseli. Olvasás/írás double.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |

### isAutomaticMajorUnit() {#isAutomaticMajorUnit--}
```
public final boolean isAutomaticMajorUnit()
```


Azt jelzi, hogy a tengely fő egysége automatikusan van-e hozzárendelve. Olvasás/írás boolean.

**Visszatérési érték:**
boolean
### setAutomaticMajorUnit(boolean value) {#setAutomaticMajorUnit-boolean-}
```
public final void setAutomaticMajorUnit(boolean value)
```


Azt jelzi, hogy a tengely fő egysége automatikusan van-e hozzárendelve. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticMinValue() {#isAutomaticMinValue--}
```
public final boolean isAutomaticMinValue()
```


Azt jelzi, hogy a minimumérték automatikusan van-e meghatározva. Olvasás/írás boolean.

**Visszatérési érték:**
boolean
### setAutomaticMinValue(boolean value) {#setAutomaticMinValue-boolean-}
```
public final void setAutomaticMinValue(boolean value)
```


Azt jelzi, hogy a minimumérték automatikusan van-e meghatározva. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getMinValue() {#getMinValue--}
```
public final double getMinValue()
```


A minimumértéket képviseli az értéktengelyen. Olvasás/írás double.

**Visszatérési érték:**
double
### setMinValue(double value) {#setMinValue-double-}
```
public final void setMinValue(double value)
```


A minimumértéket képviseli az értéktengelyen. Olvasás/írás double.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |

### isLogarithmic() {#isLogarithmic--}
```
public final boolean isLogarithmic()
```


Azt jelzi, hogy az értéktengely skálája logaritmikus-e. Olvasás/írás boolean.

**Visszatérési érték:**
boolean
### setLogarithmic(boolean value) {#setLogarithmic-boolean-}
```
public final void setLogarithmic(boolean value)
```


Azt jelzi, hogy az értéktengely skálája logaritmikus-e. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getLogBase() {#getLogBase--}
```
public final double getLogBase()
```


A logaritmus alapját képviseli. Alapértelmezett érték 10. Olvasás/írás double.

**Visszatérési érték:**
double
### setLogBase(double value) {#setLogBase-double-}
```
public final void setLogBase(double value)
```


A logaritmus alapját képviseli. Alapértelmezett érték 10. Olvasás/írás double.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |

### isPlotOrderReversed() {#isPlotOrderReversed--}
```
public final boolean isPlotOrderReversed()
```


Azt jelzi, hogy a MS PowerPoint az adatpontokat az utolsótól az elsőig ábrázolja. Olvasás/írás boolean.

**Visszatérési érték:**
boolean
### setPlotOrderReversed(boolean value) {#setPlotOrderReversed-boolean-}
```
public final void setPlotOrderReversed(boolean value)
```


Azt jelzi, hogy a MS PowerPoint az adatpontokat az utolsótól az elsőig ábrázolja. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### isVisible() {#isVisible--}
```
public final boolean isVisible()
```


Azt jelzi, hogy a tengely látható-e. Olvasás/írás boolean.

**Visszatérési érték:**
boolean
### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```


Azt jelzi, hogy a tengely látható-e. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getMajorTickMark() {#getMajorTickMark--}
```
public final int getMajorTickMark()
```


A megadott tengely fő jelölőjének típusát képviseli. Olvasás/írás [TickMarkType](../../com.aspose.slides/tickmarktype).

**Visszatérési érték:**
int
### setMajorTickMark(int value) {#setMajorTickMark-int-}
```
public final void setMajorTickMark(int value)
```


A megadott tengely fő jelölőjének típusát képviseli. Olvasás/írás [TickMarkType](../../com.aspose.slides/tickmarktype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getMinorTickMark() {#getMinorTickMark--}
```
public final int getMinorTickMark()
```


A megadott tengely alárendelt jelölőjének típusát képviseli. Olvasás/írás [TickMarkType](../../com.aspose.slides/tickmarktype).

**Visszatérési érték:**
int
### setMinorTickMark(int value) {#setMinorTickMark-int-}
```
public final void setMinorTickMark(int value)
```


A megadott tengely alárendelt jelölőjének típusát képviseli. Olvasás/írás [TickMarkType](../../com.aspose.slides/tickmarktype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getTickLabelPosition() {#getTickLabelPosition--}
```
public final int getTickLabelPosition()
```


A megadott tengelyen a jelölőcímkék pozícióját képviseli. Olvasás/írás [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**Visszatérési érték:**
int
### setTickLabelPosition(int value) {#setTickLabelPosition-int-}
```
public final void setTickLabelPosition(int value)
```


A megadott tengelyen a jelölőcímkék pozícióját képviseli. Olvasás/írás [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getMajorUnitScale() {#getMajorUnitScale--}
```
public final int getMajorUnitScale()
```


A dátum tengely fő egységskáláját képviseli. Olvasás/írás [TimeUnitType](../../com.aspose.slides/timeunittype).

**Visszatérési érték:**
int
### setMajorUnitScale(int value) {#setMajorUnitScale-int-}
```
public final void setMajorUnitScale(int value)
```


A dátum tengely fő egységskáláját képviseli. Olvasás/írás [TimeUnitType](../../com.aspose.slides/timeunittype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getMinorUnitScale() {#getMinorUnitScale--}
```
public final int getMinorUnitScale()
```


A dátum tengely alárendelt egységskáláját képviseli. Olvasás/írás [TimeUnitType](../../com.aspose.slides/timeunittype).

**Visszatérési érték:**
int
### setMinorUnitScale(int value) {#setMinorUnitScale-int-}
```
public final void setMinorUnitScale(int value)
```


A dátum tengely alárendelt egységskáláját képviseli. Olvasás/írás [TimeUnitType](../../com.aspose.slides/timeunittype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getBaseUnitScale() {#getBaseUnitScale--}
```
public final int getBaseUnitScale()
```


A legkisebb időegységet határozza meg, amely a dátum tengelyen megjelenik. Olvasás/írás [TimeUnitType](../../com.aspose.slides/timeunittype).

**Visszatérési érték:**
int
### setBaseUnitScale(int value) {#setBaseUnitScale-int-}
```
public final void setBaseUnitScale(int value)
```


A legkisebb időegységet határozza meg, amely a dátum tengelyen megjelenik. Olvasás/írás [TimeUnitType](../../com.aspose.slides/timeunittype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getMinorGridLinesFormat() {#getMinorGridLinesFormat--}
```
public final IChartLinesFormat getMinorGridLinesFormat()
```


A kisebb rácsvonalak formátumát képviseli egy diagram tengelyen. Csak olvasható [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**Visszatérési érték:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### getMajorGridLinesFormat() {#getMajorGridLinesFormat--}
```
public final IChartLinesFormat getMajorGridLinesFormat()
```


A nagyobb rácsvonalak formátumát képviseli egy diagram tengelyen. Csak olvasható [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**Visszatérési érték:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### getShowMinorGridLines() {#getShowMinorGridLines--}
```
public final boolean getShowMinorGridLines()
```


A kisebb rácsvonal elrejtéséhez állítsa a MinorGridLinesFormat.Line.FillFormat.FillType értékét FillType.NoFill-re. Csak olvasható boolean.

**Visszatérési érték:**
boolean
### getShowMajorGridLines() {#getShowMajorGridLines--}
```
public final boolean getShowMajorGridLines()
```


A nagyobb rácsvonal elrejtéséhez állítsa a MajorGridLinesFormat.Line.FillFormat.FillType értékét FillType.NoFill-re. Csak olvasható boolean.

**Visszatérési érték:**
boolean
### getFormat() {#getFormat--}
```
public final IAxisFormat getFormat()
```


A tengely formátumát képviseli. Csak olvasható [IAxisFormat](../../com.aspose.slides/iaxisformat).

**Visszatérési érték:**
[IAxisFormat](../../com.aspose.slides/iaxisformat)
### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```


A szöveg formátumát képviseli. Csak olvasható [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Visszatérési érték:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### getTitle() {#getTitle--}
```
public final IChartTitle getTitle()
```


A tengely címét adja vissza. Csak olvasható [IChartTitle](../../com.aspose.slides/icharttitle).

**Visszatérési érték:**
[IChartTitle](../../com.aspose.slides/icharttitle)
### getCrossType() {#getCrossType--}
```
public final int getCrossType()
```


A megadott tengelyen a másik tengely metszéspontjában lévő CrossType-ot képviseli. Olvasás/írás [CrossesType](../../com.aspose.slides/crossestype).

**Visszatérési érték:**
int
### setCrossType(int value) {#setCrossType-int-}
```
public final void setCrossType(int value)
```


A megadott tengelyen a másik tengely metszéspontjában lévő CrossType-ot képviseli. Olvasás/írás [CrossesType](../../com.aspose.slides/crossestype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getPosition() {#getPosition--}
```
public final int getPosition()
```


A tengely helyzetét képviseli. Olvasás/írás [AxisPositionType](../../com.aspose.slides/axispositiontype).

**Visszatérési érték:**
int
### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```


A tengely helyzetét képviseli. Olvasás/írás [AxisPositionType](../../com.aspose.slides/axispositiontype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### hasTitle() {#hasTitle--}
```
public final boolean hasTitle()
```


Meghatározza, hogy a tengelynek van-e látható címe. Olvasás/írás boolean.

**Visszatérési érték:**
boolean
### setTitle(boolean value) {#setTitle-boolean-}
```
public final void setTitle(boolean value)
```


Meghatározza, hogy a tengelynek van-e látható címe. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public final String getNumberFormat()
```


A tengelycímkék formátumstringjét képviseli. Olvasás/írás String.

**Visszatérési érték:**
java.lang.String
### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public final void setNumberFormat(String value)
```


A tengelycímkék formátumstringjét képviseli. Olvasás/írás String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public final boolean isNumberFormatLinkedToSource()
```


Azt jelzi, hogy a formátum a forrásadatokhoz van-e kapcsolva. Olvasás/írás boolean.

**Visszatérési érték:**
boolean
### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public final void setNumberFormatLinkedToSource(boolean value)
```


Azt jelzi, hogy a formátum a forrásadatokhoz van-e kapcsolva. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getTickLabelRotationAngle() {#getTickLabelRotationAngle--}
```
public final float getTickLabelRotationAngle()
```


A jelölőcímkék forgatási szögét képviseli. Olvasás/írás float.

**Visszatérési érték:**
float
### setTickLabelRotationAngle(float value) {#setTickLabelRotationAngle-float-}
```
public final void setTickLabelRotationAngle(float value)
```


A jelölőcímkék forgatási szögét képviseli. Olvasás/írás float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getTickLabelSpacing() {#getTickLabelSpacing--}
```
public final long getTickLabelSpacing()
```


Megadja, hány jelölőcímkét kell kihagyni a megjelenített címke között. Kategória- vagy sorozat-tengelyen alkalmazható. Olvasás/írás long.

**Visszatérési érték:**
long
### setTickLabelSpacing(long value) {#setTickLabelSpacing-long-}
```
public final void setTickLabelSpacing(long value)
```


Megadja, hány jelölőcímkét kell kihagyni a megjelenített címke között. Kategória- vagy sorozat-tengelyen alkalmazható. Olvasás/írás long.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickLabelSpacing() {#isAutomaticTickLabelSpacing--}
```
public final boolean isAutomaticTickLabelSpacing()
```


Az automatikus jelölőcímke-távolság értékét adja meg. Ha hamis, a TickLabelSpacing tulajdonságot használja. Olvasás/írás boolean.

**Visszatérési érték:**
boolean
### setAutomaticTickLabelSpacing(boolean value) {#setAutomaticTickLabelSpacing-boolean-}
```
public final void setAutomaticTickLabelSpacing(boolean value)
```


Az automatikus jelölőcímke-távolság értékét adja meg. Ha hamis, a TickLabelSpacing tulajdonságot használja. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getTickMarksSpacing() {#getTickMarksSpacing--}
```
public final long getTickMarksSpacing()
```


Megadja, hány jelölővonalat kell kihagyni a következő megjelenítés előtt. Kategória- vagy sorozat-tengelyen alkalmazható. Olvasás/írás int.

**Visszatérési érték:**
long
### setTickMarksSpacing(long value) {#setTickMarksSpacing-long-}
```
public final void setTickMarksSpacing(long value)
```


Megadja, hány jelölővonalat kell kihagyni a következő megjelenítés előtt. Kategória- vagy sorozat-tengelyen alkalmazható. Olvasás/írás int.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickMarksSpacing() {#isAutomaticTickMarksSpacing--}
```
public final boolean isAutomaticTickMarksSpacing()
```


Az automatikus jelölővonal-távolság értékét adja meg. Ha hamis, a TickMarksSpacing tulajdonságot használja. Olvasás/írás boolean.

**Visszatérési érték:**
boolean
### setAutomaticTickMarksSpacing(boolean value) {#setAutomaticTickMarksSpacing-boolean-}
```
public final void setAutomaticTickMarksSpacing(boolean value)
```


Az automatikus jelölővonal-távolság értékét adja meg. Ha hamis, a TickMarksSpacing tulajdonságot használja. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getLabelOffset() {#getLabelOffset--}
```
public final int getLabelOffset()
```


Megadja a címkék távolságát a tengelytől. Kategória- vagy dátumtengelyen alkalmazható. Az érték 0 % és 1000 % között kell legyen. Olvasás/írás int.

**Visszatérési érték:**
int
### setLabelOffset(int value) {#setLabelOffset-int-}
```
public final void setLabelOffset(int value)
```


Megadja a címkék távolságát a tengelytől. Kategória- vagy dátumtengelyen alkalmazható. Az érték 0 % és 1000 % között kell legyen. Olvasás/írás int.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### getAggregationType() {#getAggregationType--}
```
public final int getAggregationType()
```

Képviseli a kategória tengely (binning) aggregációs típusát. Alkalmazott a kategóriára. Csak Histogram vagy HistogramPareto sorozatokkal használható.

**Visszatérési érték:**
int

### setAggregationType(int value) {#setAggregationType-int-}
```
public final void setAggregationType(int value)
```

Képviseli a kategória tengely (binning) aggregációs típusát. Alkalmazott a kategóriára. Csak Histogram vagy HistogramPareto sorozatokkal használható.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getBinWidth() {#getBinWidth--}
```
public final double getBinWidth()
```

Megadja a bin szélességet, amikor az AggregationType tulajdonság értéke AxisAggregationType.ByBinWidth-ra van beállítva. Alkalmazott kategória tengelyekre. Csak Histogram vagy HistogramPareto sorozatokkal használható.

**Visszatérési érték:**
double

### setBinWidth(double value) {#setBinWidth-double-}
```
public final void setBinWidth(double value)
```

Megadja a bin szélességet, amikor az AggregationType tulajdonság értéke AxisAggregationType.ByBinWidth-ra van beállítva. Alkalmazott kategória tengelyekre. Csak Histogram vagy HistogramPareto sorozatokkal használható.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |

### getNumberOfBins() {#getNumberOfBins--}
```
public final long getNumberOfBins()
```

Megadja a binok számát, amikor az AggregationType tulajdonság értéke AxisAggregationType.ByNumberOfBins-ra van beállítva. Alkalmazott kategória tengelyekre. Csak Histogram vagy HistogramPareto sorozatokkal használható.

**Visszatérési érték:**
long

### setNumberOfBins(long value) {#setNumberOfBins-long-}
```
public final void setNumberOfBins(long value)
```

Megadja a binok számát, amikor az AggregationType tulajdonság értéke AxisAggregationType.ByNumberOfBins-ra van beállítva. Alkalmazott kategória tengelyekre. Csak Histogram vagy HistogramPareto sorozatokkal használható.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | long |  |

### isOverflowBin() {#isOverflowBin--}
```
public final boolean isOverflowBin()
```

Megadja, hogy alkalmaz-e overflow bin-t. Használja az IsAutomaticOverflowBin és az OverflowBin értékeket az overflow bin értékének beállításához.

**Visszatérési érték:**
boolean

### setOverflowBin(boolean value) {#setOverflowBin-boolean-}
```
public final void setOverflowBin(boolean value)
```

Megadja, hogy alkalmaz-e overflow bin-t. Használja az IsAutomaticOverflowBin és az OverflowBin értékeket az overflow bin értékének beállításához.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticOverflowBin() {#isAutomaticOverflowBin--}
```
public final boolean isAutomaticOverflowBin()
```

Megadja az automatikus overflow bin értékét. Ha hamis, akkor használja az OverflowBin tulajdonságot.

**Visszatérési érték:**
boolean

### setAutomaticOverflowBin(boolean value) {#setAutomaticOverflowBin-boolean-}
```
public final void setAutomaticOverflowBin(boolean value)
```

Megadja az automatikus overflow bin értékét. Ha hamis, akkor használja az OverflowBin tulajdonságot.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getOverflowBin() {#getOverflowBin--}
```
public final double getOverflowBin()
```

Megadja az overflow bin egyéni értékét. Alkalmazott, amikor az IsAutomaticOverflowBin tulajdonság hamisra van állítva, és az IsOverflowBin tulajdonság igaz.

**Visszatérési érték:**
double

### setOverflowBin(double value) {#setOverflowBin-double-}
```
public final void setOverflowBin(double value)
```

Megadja az overflow bin egyéni értékét. Alkalmazott, amikor az IsAutomaticOverflowBin tulajdonság hamisra van állítva, és az IsOverflowBin tulajdonság igaz.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |

### isUnderflowBin() {#isUnderflowBin--}
```
public final boolean isUnderflowBin()
```

Megadja, hogy alkalmaz-e underflow bin-t. Használja az IsAutomaticUnderflowBin és az UnderflowBin értékeket az underflow bin értékének beállításához.

**Visszatérési érték:**
boolean

### setUnderflowBin(boolean value) {#setUnderflowBin-boolean-}
```
public final void setUnderflowBin(boolean value)
```

Megadja, hogy alkalmaz-e underflow bin-t. Használja az IsAutomaticUnderflowBin és az UnderflowBin értékeket az underflow bin értékének beállításához.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticUnderflowBin() {#isAutomaticUnderflowBin--}
```
public final boolean isAutomaticUnderflowBin()
```

Megadja az automatikus underflow bin értékét. Ha hamis, akkor használja az UnderflowBin tulajdonságot.

**Visszatérési érték:**
boolean

### setAutomaticUnderflowBin(boolean value) {#setAutomaticUnderflowBin-boolean-}
```
public final void setAutomaticUnderflowBin(boolean value)
```

Megadja az automatikus underflow bin értékét. Ha hamis, akkor használja az UnderflowBin tulajdonságot.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getUnderflowBin() {#getUnderflowBin--}
```
public final double getUnderflowBin()
```

Megadja az underflow bin egyéni értékét. Alkalmazott, amikor az IsAutomaticUnderflowBin tulajdonság hamisra van állítva, és az IsUnderflowBin tulajdonság igaz.

**Visszatérési érték:**
double

### setUnderflowBin(double value) {#setUnderflowBin-double-}
```
public final void setUnderflowBin(double value)
```

Megadja az underflow bin egyéni értékét. Alkalmazott, amikor az IsAutomaticUnderflowBin tulajdonság hamisra van állítva, és az IsUnderflowBin tulajdonság igaz.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Visszaadja a FillFormat szülő diaját. Csak olvasható [BaseSlide](../../com.aspose.slides/baseslide).

**Visszatérési érték:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Visszaadja a FillFormat szülő prezentációját. Csak olvasható [IPresentation](../../com.aspose.slides/ipresentation).

**Visszatérési érték:**
[IPresentation](../../com.aspose.slides/ipresentation)