---
title: IAxis
second_title: Aspose.Slides für Android über die Java API Referenz
description: Kapselt das Objekt, das die Achse eines Diagramms darstellt.
type: docs
url: /de/com.aspose.slides/iaxis/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer)
```
public interface IAxis extends IFormattedTextContainer
```

Kapselt das Objekt, das die Achse eines Diagramms darstellt.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getAxisBetweenCategories()](#getAxisBetweenCategories--) | Stellt dar, ob die Werteachse die Kategorienachse zwischen Kategorien kreuzt. |
| [setAxisBetweenCategories(boolean value)](#setAxisBetweenCategories-boolean-) | Stellt dar, ob die Werteachse die Kategorienachse zwischen Kategorien kreuzt. |
| [getCrossAt()](#getCrossAt--) | Stellt den Punkt auf der Achse dar, an dem die senkrechte Achse sie schneidet. |
| [setCrossAt(float value)](#setCrossAt-float-) | Stellt den Punkt auf der Achse dar, an dem die senkrechte Achse sie schneidet. |
| [getDisplayUnit()](#getDisplayUnit--) | Gibt den Skalierungswert der Anzeigeeinheiten für die Werteachse an. |
| [setDisplayUnit(int value)](#setDisplayUnit-int-) | Gibt den Skalierungswert der Anzeigeeinheiten für die Werteachse an. |
| [getActualMaxValue()](#getActualMaxValue--) | Gibt den tatsächlichen Maximalwert auf der Achse an. |
| [getActualMinValue()](#getActualMinValue--) | Gibt den tatsächlichen Minimalwert auf der Achse an. |
| [getActualMajorUnit()](#getActualMajorUnit--) | Gibt die tatsächliche Haupteinheit der Achse an. |
| [getActualMinorUnit()](#getActualMinorUnit--) | Gibt die tatsächliche Nebeneinheit der Achse an. |
| [getActualMajorUnitScale()](#getActualMajorUnitScale--) | Gibt die tatsächliche Skalierung der Haupteinheit der Achse an. |
| [getActualMinorUnitScale()](#getActualMinorUnitScale--) | Gibt die tatsächliche Skalierung der Nebeneinheit der Achse an. |
| [isAutomaticMaxValue()](#isAutomaticMaxValue--) | Gibt an, ob der Maximalwert automatisch zugewiesen wird. |
| [setAutomaticMaxValue(boolean value)](#setAutomaticMaxValue-boolean-) | Gibt an, ob der Maximalwert automatisch zugewiesen wird. |
| [getMaxValue()](#getMaxValue--) | Stellt den Maximalwert auf der Werteachse dar. |
| [setMaxValue(double value)](#setMaxValue-double-) | Stellt den Maximalwert auf der Werteachse dar. |
| [getMinorUnit()](#getMinorUnit--) | Stellt die Nebeneinheiten für die Datums- oder Werteachse dar. |
| [setMinorUnit(double value)](#setMinorUnit-double-) | Stellt die Nebeneinheiten für die Datums- oder Werteachse dar. |
| [isAutomaticMinorUnit()](#isAutomaticMinorUnit--) | Gibt an, ob die Nebeneinheit der Achse automatisch zugewiesen wird. |
| [setAutomaticMinorUnit(boolean value)](#setAutomaticMinorUnit-boolean-) | Gibt an, ob die Nebeneinheit der Achse automatisch zugewiesen wird. |
| [getMajorUnit()](#getMajorUnit--) | Stellt die Haupteinheiten für die Datums- oder Werteachse dar. |
| [setMajorUnit(double value)](#setMajorUnit-double-) | Stellt die Haupteinheiten für die Datums- oder Werteachse dar. |
| [isAutomaticMajorUnit()](#isAutomaticMajorUnit--) | Gibt an, ob die Haupteinheit der Achse automatisch zugewiesen wird. |
| [setAutomaticMajorUnit(boolean value)](#setAutomaticMajorUnit-boolean-) | Gibt an, ob die Haupteinheit der Achse automatisch zugewiesen wird. |
| [isAutomaticMinValue()](#isAutomaticMinValue--) | Gibt an, ob der Minimalwert automatisch zugewiesen wird. |
| [setAutomaticMinValue(boolean value)](#setAutomaticMinValue-boolean-) | Gibt an, ob der Minimalwert automatisch zugewiesen wird. |
| [getMinValue()](#getMinValue--) | Stellt den Minimalwert auf der Werteachse dar. |
| [setMinValue(double value)](#setMinValue-double-) | Stellt den Minimalwert auf der Werteachse dar. |
| [isLogarithmic()](#isLogarithmic--) | Stellt dar, ob der Skalierungstyp der Werteachse logarithmisch ist oder nicht. |
| [setLogarithmic(boolean value)](#setLogarithmic-boolean-) | Stellt dar, ob der Skalierungstyp der Werteachse logarithmisch ist oder nicht. |
| [getLogBase()](#getLogBase--) | Stellt die logarithmische Basis dar. |
| [setLogBase(double value)](#setLogBase-double-) | Stellt die logarithmische Basis dar. |
| [isPlotOrderReversed()](#isPlotOrderReversed--) | Stellt dar, ob MS PowerPoint Datenpunkte von zuletzt nach zuerst plottet. |
| [setPlotOrderReversed(boolean value)](#setPlotOrderReversed-boolean-) | Stellt dar, ob MS PowerPoint Datenpunkte von zuletzt nach zuerst plottet. |
| [isVisible()](#isVisible--) | Stellt dar, ob die Achse sichtbar ist. |
| [setVisible(boolean value)](#setVisible-boolean-) | Stellt dar, ob die Achse sichtbar ist. |
| [getMajorTickMark()](#getMajorTickMark--) | Stellt den Typ der Hauptteilungsmarke für die angegebene Achse dar. |
| [setMajorTickMark(int value)](#setMajorTickMark-int-) | Stellt den Typ der Hauptteilungsmarke für die angegebene Achse dar. |
| [getMinorTickMark()](#getMinorTickMark--) | Stellt den Typ der Nebenteilungsmarke für die angegebene Achse dar. |
| [setMinorTickMark(int value)](#setMinorTickMark-int-) | Stellt den Typ der Nebenteilungsmarke für die angegebene Achse dar. |
| [getTickLabelPosition()](#getTickLabelPosition--) | Stellt die Position der Teilungsbeschriftungen auf der angegebenen Achse dar. |
| [setTickLabelPosition(int value)](#setTickLabelPosition-int-) | Stellt die Position der Teilungsbeschriftungen auf der angegebenen Achse dar. |
| [getMajorUnitScale()](#getMajorUnitScale--) | Stellt die Skalierung der Haupteinheit für die Datumsachse dar. |
| [setMajorUnitScale(int value)](#setMajorUnitScale-int-) | Stellt die Skalierung der Haupteinheit für die Datumsachse dar. |
| [getMinorUnitScale()](#getMinorUnitScale--) | Stellt die Skalierung der Haupteinheit für die Datumsachse dar. |
| [setMinorUnitScale(int value)](#setMinorUnitScale-int-) | Stellt die Skalierung der Haupteinheit für die Datumsachse dar. |
| [getBaseUnitScale()](#getBaseUnitScale--) | Gibt die kleinste Zeiteinheit an, die auf der Datumsachse dargestellt wird. |
| [setBaseUnitScale(int value)](#setBaseUnitScale-int-) | Gibt die kleinste Zeiteinheit an, die auf der Datumsachse dargestellt wird. |
| [getMinorGridLinesFormat()](#getMinorGridLinesFormat--) | Stellt das Format der Nebenrastern auf einer Diagrammachse dar. |
| [getMajorGridLinesFormat()](#getMajorGridLinesFormat--) | Stellt das Format der Hauptrastern auf einer Diagrammachse dar. |
| [getShowMinorGridLines()](#getShowMinorGridLines--) | Stellt dar, ob die Nebenrastern angezeigt werden. |
| [getShowMajorGridLines()](#getShowMajorGridLines--) | Stellt dar, ob die Hauptrastern angezeigt werden. |
| [getFormat()](#getFormat--) | Stellt das Format der Achse dar. |
| [getTitle()](#getTitle--) | Liest den Titel der Achse. |
| [getCrossType()](#getCrossType--) | Stellt den CrossType auf der angegebenen Achse dar, an dem die andere Achse kreuzt. |
| [setCrossType(int value)](#setCrossType-int-) | Stellt den CrossType auf der angegebenen Achse dar, an dem die andere Achse kreuzt. |
| [getPosition()](#getPosition--) | Stellt die Position der Achse dar. |
| [setPosition(int value)](#setPosition-int-) | Stellt die Position der Achse dar. |
| [hasTitle()](#hasTitle--) | Bestimmt, ob eine Achse einen sichtbaren Titel hat. |
| [setTitle(boolean value)](#setTitle-boolean-) | Bestimmt, ob eine Achse einen sichtbaren Titel hat. |
| [getNumberFormat()](#getNumberFormat--) | Stellt die Formatzeichenkette für die Achsenbeschriftungen dar. |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | Stellt die Formatzeichenkette für die Achsenbeschriftungen dar. |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | Gibt an, ob das Format mit Quell-Daten verknüpft ist. |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | Gibt an, ob das Format mit Quell-Daten verknüpft ist. |
| [getTickLabelRotationAngle()](#getTickLabelRotationAngle--) | Stellt den Rotationswinkel der Teilungsbeschriftungen dar Lesen/Schreiben float. |
| [setTickLabelRotationAngle(float value)](#setTickLabelRotationAngle-float-) | Stellt den Rotationswinkel der Teilungsbeschriftungen dar Lesen/Schreiben float. |
| [getTickLabelSpacing()](#getTickLabelSpacing--) | Gibt an, wie viele Teilungsbeschriftungen zwischen den gezeichneten Beschriftungen übersprungen werden. |
| [setTickLabelSpacing(long value)](#setTickLabelSpacing-long-) | Gibt an, wie viele Teilungsbeschriftungen zwischen den gezeichneten Beschriftungen übersprungen werden. |
| [isAutomaticTickLabelSpacing()](#isAutomaticTickLabelSpacing--) | Gibt den automatischen Abstandswert für Teilungsbeschriftungen an. |
| [setAutomaticTickLabelSpacing(boolean value)](#setAutomaticTickLabelSpacing-boolean-) | Gibt den automatischen Abstandswert für Teilungsbeschriftungen an. |
| [getTickMarksSpacing()](#getTickMarksSpacing--) | Gibt an, wie viele Teilungsstriche übersprungen werden sollen, bevor der nächste gezeichnet wird. |
| [setTickMarksSpacing(long value)](#setTickMarksSpacing-long-) | Gibt an, wie viele Teilungsstriche übersprungen werden sollen, bevor der nächste gezeichnet wird. |
| [isAutomaticTickMarksSpacing()](#isAutomaticTickMarksSpacing--) | Gibt den automatischen Abstandswert für Teilungsstriche an. |
| [setAutomaticTickMarksSpacing(boolean value)](#setAutomaticTickMarksSpacing-boolean-) | Gibt den automatischen Abstandswert für Teilungsstriche an. |
| [getLabelOffset()](#getLabelOffset--) | Gibt den Abstand der Beschriftungen von der Achse an. |
| [setLabelOffset(int value)](#setLabelOffset-int-) | Gibt den Abstand der Beschriftungen von der Achse an. |
| [getCategoryAxisType()](#getCategoryAxisType--) | Gibt den Typ der Kategorienachse an. |
| [setCategoryAxisType(int value)](#setCategoryAxisType-int-) | Gibt den Typ der Kategorienachse an. |
| [setCategoryAxisTypeAutomatically()](#setCategoryAxisTypeAutomatically--) | Setzt die Eigenschaft IAxis.CategoryAxisType mit einem Wert, der basierend auf den Achsendaten automatisch bestimmt wird. |
| [getAggregationType()](#getAggregationType--) | Stellt den Aggregationstyp der Kategorienachse (Binning) dar. |
| [setAggregationType(int value)](#setAggregationType-int-) | Stellt den Aggregationstyp der Kategorienachse (Binning) dar. |
| [getBinWidth()](#getBinWidth--) | Gibt die Bin-Breite an, wenn der AggregationType-Wert auf AxisAggregationType.ByBinWidth gesetzt ist. |
| [setBinWidth(double value)](#setBinWidth-double-) | Gibt die Bin-Breite an, wenn der AggregationType-Wert auf AxisAggregationType.ByBinWidth gesetzt ist. |
| [getNumberOfBins()](#getNumberOfBins--) | Gibt die Anzahl der Bins an, wenn der AggregationType-Wert auf AxisAggregationType.ByNumberOfBins gesetzt ist. |
| [setNumberOfBins(long value)](#setNumberOfBins-long-) | Gibt die Anzahl der Bins an, wenn der AggregationType-Wert auf AxisAggregationType.ByNumberOfBins gesetzt ist. |
| [isOverflowBin()](#isOverflowBin--) | Gibt an, ob ein Overflow-Bin angewendet wird. |
| [setOverflowBin(boolean value)](#setOverflowBin-boolean-) | Gibt an, ob ein Overflow-Bin angewendet wird. |
| [isAutomaticOverflowBin()](#isAutomaticOverflowBin--) | Gibt den automatischen Overflow-Bin-Wert an. |
| [setAutomaticOverflowBin(boolean value)](#setAutomaticOverflowBin-boolean-) | Gibt den automatischen Overflow-Bin-Wert an. |
| [getOverflowBin()](#getOverflowBin--) | Gibt den benutzerdefinierten Wert des Overflow-Bins an. |
| [setOverflowBin(double value)](#setOverflowBin-double-) | Gibt den benutzerdefinierten Wert des Overflow-Bins an. |
| [isUnderflowBin()](#isUnderflowBin--) | Gibt an, ob ein Underflow-Bin angewendet wird. |
| [setUnderflowBin(boolean value)](#setUnderflowBin-boolean-) | Gibt an, ob ein Underflow-Bin angewendet wird. |
| [isAutomaticUnderflowBin()](#isAutomaticUnderflowBin--) | Gibt den automatischen Underflow-Bin-Wert an. |
| [setAutomaticUnderflowBin(boolean value)](#setAutomaticUnderflowBin-boolean-) | Gibt den automatischen Underflow-Bin-Wert an. |
| [getUnderflowBin()](#getUnderflowBin--) | Gibt den benutzerdefinierten Wert des Underflow-Bins an. |
| [setUnderflowBin(double value)](#setUnderflowBin-double-) | Gibt den benutzerdefinierten Wert des Underflow-Bins an. |

### getAxisBetweenCategories() {#getAxisBetweenCategories--}
```
public abstract boolean getAxisBetweenCategories()
```

Stellt dar, ob die Werteachse die Kategorienachse zwischen Kategorien kreuzt. Diese Eigenschaft gilt nur für Kategorienachsen und nicht für 3-D-Diagramme. Lesen/Schreiben boolean.

**Rückgabe:**
boolean

### setAxisBetweenCategories(boolean value) {#setAxisBetweenCategories-boolean-}
```
public abstract void setAxisBetweenCategories(boolean value)
```

Stellt dar, ob die Werteachse die Kategorienachse zwischen Kategorien kreuzt. Diese Eigenschaft gilt nur für Kategorienachsen und nicht für 3-D-Diagramme. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getCrossAt() {#getCrossAt--}
```
public abstract float getCrossAt()
```

Stellt den Punkt auf der Achse dar, an dem die senkrechte Achse sie schneidet. Lesen/Schreiben float.

**Rückgabe:**
float

### setCrossAt(float value) {#setCrossAt-float-}
```
public abstract void setCrossAt(float value)
```

Stellt den Punkt auf der Achse dar, an dem die senkrechte Achse sie schneidet. Lesen/Schreiben float.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |

### getDisplayUnit() {#getDisplayUnit--}
```
public abstract int getDisplayUnit()
```

Gibt den Skalierungswert der Anzeigeeinheiten für die Werteachse an. Lesen/Schreiben [DisplayUnitType](../../com.aspose.slides/displayunittype).

**Rückgabe:**
int

### setDisplayUnit(int value) {#setDisplayUnit-int-}
```
public abstract void setDisplayUnit(int value)
```

Gibt den Skalierungswert der Anzeigeeinheiten für die Werteachse an. Lesen/Schreiben [DisplayUnitType](../../com.aspose.slides/displayunittype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getActualMaxValue() {#getActualMaxValue--}
```
public abstract double getActualMaxValue()
```

Gibt den tatsächlichen Maximalwert auf der Achse an. Rufen Sie vorher die Methode IChart.ValidateChartLayout() auf, um den tatsächlichen Wert zu erhalten.

**Rückgabe:**
double

### getActualMinValue() {#getActualMinValue--}
```
public abstract double getActualMinValue()
```

Gibt den tatsächlichen Minimalwert auf der Achse an. Rufen Sie vorher die Methode IChart.ValidateChartLayout() auf, um den tatsächlichen Wert zu erhalten.

**Rückgabe:**
double

### getActualMajorUnit() {#getActualMajorUnit--}
```
public abstract double getActualMajorUnit()
```

Gibt die tatsächliche Haupteinheit der Achse an. Rufen Sie vorher die Methode IChart.ValidateChartLayout() auf, um den tatsächlichen Wert zu erhalten.

**Rückgabe:**
double

### getActualMinorUnit() {#getActualMinorUnit--}
```
public abstract double getActualMinorUnit()
```

Gibt die tatsächliche Nebeneinheit der Achse an. Rufen Sie vorher die Methode IChart.ValidateChartLayout() auf, um den tatsächlichen Wert zu erhalten.

**Rückgabe:**
double

### getActualMajorUnitScale() {#getActualMajorUnitScale--}
```
public abstract int getActualMajorUnitScale()
```

Gibt die tatsächliche Skalierung der Haupteinheit der Achse an. Rufen Sie vorher die Methode IChart.ValidateChartLayout() auf, um den tatsächlichen Wert zu erhalten.

**Rückgabe:**
int

### getActualMinorUnitScale() {#getActualMinorUnitScale--}
```
public abstract int getActualMinorUnitScale()
```

Gibt die tatsächliche Skalierung der Nebeneinheit der Achse an. Rufen Sie vorher die Methode IChart.ValidateChartLayout() auf, um den tatsächlichen Wert zu erhalten.

**Rückgabe:**
int

### isAutomaticMaxValue() {#isAutomaticMaxValue--}
```
public abstract boolean isAutomaticMaxValue()
```

Gibt an, ob der Maximalwert automatisch zugewiesen wird. Lesen/Schreiben boolean.

**Rückgabe:**
boolean

### setAutomaticMaxValue(boolean value) {#setAutomaticMaxValue-boolean-}
```
public abstract void setAutomaticMaxValue(boolean value)
```

Gibt an, ob der Maximalwert automatisch zugewiesen wird. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getMaxValue() {#getMaxValue--}
```
public abstract double getMaxValue()
```

Stellt den Maximalwert auf der Werteachse dar. Lesen/Schreiben double.

**Rückgabe:**
double

### setMaxValue(double value) {#setMaxValue-double-}
```
public abstract void setMaxValue(double value)
```

Stellt den Maximalwert auf der Werteachse dar. Lesen/Schreiben double.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |

### getMinorUnit() {#getMinorUnit--}
```
public abstract double getMinorUnit()
```

Stellt die Nebeneinheiten für die Datums- oder Werteachse dar. Lesen/Schreiben double.

**Rückgabe:**
double

### setMinorUnit(double value) {#setMinorUnit-double-}
```
public abstract void setMinorUnit(double value)
```

Stellt die Nebeneinheiten für die Datums- oder Werteachse dar. Lesen/Schreiben double.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |

### isAutomaticMinorUnit() {#isAutomaticMinorUnit--}
```
public abstract boolean isAutomaticMinorUnit()
```

Gibt an, ob die Nebeneinheit der Achse automatisch zugewiesen wird. Lesen/Schreiben boolean.

**Rückgabe:**
boolean

### setAutomaticMinorUnit(boolean value) {#setAutomaticMinorUnit-boolean-}
```
public abstract void setAutomaticMinorUnit(boolean value)
```

Gibt an, ob die Nebeneinheit der Achse automatisch zugewiesen wird. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getMajorUnit() {#getMajorUnit--}
```
public abstract double getMajorUnit()
```

Stellt die Haupteinheiten für die Datums- oder Werteachse dar. Lesen/Schreiben double.

**Rückgabe:**
double

### setMajorUnit(double value) {#setMajorUnit-double-}
```
public abstract void setMajorUnit(double value)
```

Stellt die Haupteinheiten für die Datums- oder Werteachse dar. Lesen/Schreiben double.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |

### isAutomaticMajorUnit() {#isAutomaticMajorUnit--}
```
public abstract boolean isAutomaticMajorUnit()
```

Gibt an, ob die Haupteinheit der Achse automatisch zugewiesen wird. Lesen/Schreiben boolean.

**Rückgabe:**
boolean

### setAutomaticMajorUnit(boolean value) {#setAutomaticMajorUnit-boolean-}
```
public abstract void setAutomaticMajorUnit(boolean value)
```

Gibt an, ob die Haupteinheit der Achse automatisch zugewiesen wird. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticMinValue() {#isAutomaticMinValue--}
```
public abstract boolean isAutomaticMinValue()
```

Gibt an, ob der Minimalwert automatisch zugewiesen wird. Lesen/Schreiben boolean.

**Rückgabe:**
boolean

### setAutomaticMinValue(boolean value) {#setAutomaticMinValue-boolean-}
```
public abstract void setAutomaticMinValue(boolean value)
```

Gibt an, ob der Minimalwert automatisch zugewiesen wird. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getMinValue() {#getMinValue--}
```
public abstract double getMinValue()
```

Stellt den Minimalwert auf der Werteachse dar. Lesen/Schreiben double.

**Rückgabe:**
double

### setMinValue(double value) {#setMinValue-double-}
```
public abstract void setMinValue(double value)
```

Stellt den Minimalwert auf der Werteachse dar. Lesen/Schreiben double.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |

### isLogarithmic() {#isLogarithmic--}
```
public abstract boolean isLogarithmic()
```

Stellt dar, ob der Skalierungstyp der Werteachse logarithmisch ist oder nicht. Lesen/Schreiben boolean.

**Rückgabe:**
boolean

### setLogarithmic(boolean value) {#setLogarithmic-boolean-}
```
public abstract void setLogarithmic(boolean value)
```

Stellt dar, ob der Skalierungstyp der Werteachse logarithmisch ist oder nicht. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getLogBase() {#getLogBase--}
```
public abstract double getLogBase()
```

Stellt die logarithmische Basis dar. Der Standardwert ist 10. Lesen/Schreiben double.

**Rückgabe:**
double

### setLogBase(double value) {#setLogBase-double-}
```
public abstract void setLogBase(double value)
```

Stellt die logarithmische Basis dar. Der Standardwert ist 10. Lesen/Schreiben double.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |

### isPlotOrderReversed() {#isPlotOrderReversed--}
```
public abstract boolean isPlotOrderReversed()
```

Stellt dar, ob MS PowerPoint Datenpunkte von zuletzt nach zuerst plottet. Lesen/Schreiben boolean.

**Rückgabe:**
boolean

### setPlotOrderReversed(boolean value) {#setPlotOrderReversed-boolean-}
```
public abstract void setPlotOrderReversed(boolean value)
```

Stellt dar, ob MS PowerPoint Datenpunkte von zuletzt nach zuerst plottet. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

Stellt dar, ob die Achse sichtbar ist. Lesen/Schreiben boolean.

**Rückgabe:**
boolean

### setVisible(boolean value) {#setVisible-boolean-}
```
public abstract void setVisible(boolean value)
```

Stellt dar, ob die Achse sichtbar ist. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getMajorTickMark() {#getMajorTickMark--}
```
public abstract int getMajorTickMark()
```

Stellt den Typ der Hauptteilungsmarke für die angegebene Achse dar. Lesen/Schreiben [TickMarkType](../../com.aspose.slides/tickmarktype).

**Rückgabe:**
int

### setMajorTickMark(int value) {#setMajorTickMark-int-}
```
public abstract void setMajorTickMark(int value)
```

Stellt den Typ der Hauptteilungsmarke für die angegebene Achse dar. Lesen/Schreiben [TickMarkType](../../com.aspose.slides/tickmarktype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getMinorTickMark() {#getMinorTickMark--}
```
public abstract int getMinorTickMark()
```

Stellt den Typ der Nebenteilungsmarke für die angegebene Achse dar. Lesen/Schreiben [TickMarkType](../../com.aspose.slides/tickmarktype).

**Rückgabe:**
int

### setMinorTickMark(int value) {#setMinorTickMark-int-}
```
public abstract void setMinorTickMark(int value)
```

Stellt den Typ der Nebenteilungsmarke für die angegebene Achse dar. Lesen/Schreiben [TickMarkType](../../com.aspose.slides/tickmarktype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getTickLabelPosition() {#getTickLabelPosition--}
```
public abstract int getTickLabelPosition()
```

Stellt die Position der Teilungsbeschriftungen auf der angegebenen Achse dar. Lesen/Schreiben [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**Rückgabe:**
int

### setTickLabelPosition(int value) {#setTickLabelPosition-int-}
```
public abstract void setTickLabelPosition(int value)
```

Stellt die Position der Teilungsbeschriftungen auf der angegebenen Achse dar. Lesen/Schreiben [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getMajorUnitScale() {#getMajorUnitScale--}
```
public abstract int getMajorUnitScale()
```

Stellt die Skalierung der Haupteinheit für die Datumsachse dar. Lesen/Schreiben [TimeUnitType](../../com.aspose.slides/timeunittype).

**Rückgabe:**
int

### setMajorUnitScale(int value) {#setMajorUnitScale-int-}
```
public abstract void setMajorUnitScale(int value)
```

Stellt die Skalierung der Haupteinheit für die Datumsachse dar. Lesen/Schreiben [TimeUnitType](../../com.aspose.slides/timeunittype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getMinorUnitScale() {#getMinorUnitScale--}
```
public abstract int getMinorUnitScale()
```

Stellt die Skalierung der Haupteinheit für die Datumsachse dar. Lesen/Schreiben [TimeUnitType](../../com.aspose.slides/timeunittype).

**Rückgabe:**
int

### setMinorUnitScale(int value) {#setMinorUnitScale-int-}
```
public abstract void setMinorUnitScale(int value)
```

Stellt die Skalierung der Haupteinheit für die Datumsachse dar. Lesen/Schreiben [TimeUnitType](../../com.aspose.slides/timeunittype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getBaseUnitScale() {#getBaseUnitScale--}
```
public abstract int getBaseUnit 
```

Gibt die kleinste Zeiteinheit an, die auf der Datumsachse dargestellt wird. Lesen/Schreiben [TimeUnitType](../../com.aspose.slides/timeunittype).

**Rückgabe:**
int

### setBaseUnitScale(int value) {#setBaseUnitScale-int-}
```
public abstract void setBaseUnitScale(int value)
```

Gibt die kleinste Zeiteinheit an, die auf der Datumsachse dargestellt wird. Lesen/Schreiben [TimeUnitType](../../com.aspose.slides/timeunittype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getMinorGridLinesFormat() {#getMinorGridLinesFormat--}
```
public abstract IChartLinesFormat getMinorGridLinesFormat()
```

Stellt das Format der Nebenrastern auf einer Diagrammachse dar. Nur lesen [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**Rückgabe:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getMajorGridLinesFormat() {#getMajorGridLinesFormat--}
```
public abstract IChartLinesFormat getMajorGridLinesFormat()
```

Stellt das Format der Hauptrastern auf einer Diagrammachse dar. Nur lesen [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**Rückgabe:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getShowMinorGridLines() {#getShowMinorGridLines--}
```
public abstract boolean getShowMinorGridLines()
```

Stellt dar, ob die Nebenrastern angezeigt werden. Nur lesen boolean.

**Rückgabe:**
boolean

### getShowMajorGridLines() {#getShowMajorGridLines--}
```
public abstract boolean getShowMajorGridLines()
```

Stellt dar, ob die Hauptrastern angezeigt werden. Nur lesen boolean.

**Rückgabe:**
boolean

### getFormat() {#getFormat--}
```
public abstract IAxisFormat getFormat()
```

Stellt das Format der Achse dar. Nur lesen [IAxisFormat](../../com.aspose.slides/iaxisformat).

**Rückgabe:**
[IAxisFormat](../../com.aspose.slides/iaxisformat)

### getTitle() {#getTitle--}
```
public abstract IChartTitle getTitle()
```

Liest den Titel der Achse. Nur lesen [IChartTitle](../../com.aspose.slides/icharttitle).

**Rückgabe:**
[IChartTitle](../../com.aspose.slides/icharttitle)

### getCrossType() {#getCrossType--}
```
public abstract int getCrossType()
```

Stellt den CrossType auf der angegebenen Achse dar, an dem die andere Achse kreuzt. Lesen/Schreiben [CrossesType](../../com.aspose.slides/crossestype).

**Rückgabe:**
int

### setCrossType(int value) {#setCrossType-int-}
```
public abstract void setCrossType(int value)
```

Stellt den CrossType auf der angegebenen Achse dar, an dem die andere Achse kreuzt. Lesen/Schreiben [CrossesType](../../com.aspose.slides/crossestype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

Stellt die Position der Achse dar. Lesen/Schreiben [AxisPositionType](../../com.aspose.slides/axispositiontype).

**Rückgabe:**
int

### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

Stellt die Position der Achse dar. Lesen/Schreiben [AxisPositionType](../../com.aspose.slides/axispositiontype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### hasTitle() {#hasTitle--}
```
public abstract boolean hasTitle()
```

Bestimmt, ob eine Achse einen sichtbaren Titel hat. Lesen/Schreiben boolean.

**Rückgabe:**
boolean

### setTitle(boolean value) {#setTitle-boolean-}
```
public abstract void setTitle(boolean value)
```

Bestimmt, ob eine Achse einen sichtbaren Titel hat. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public abstract String getNumberFormat()
```

Stellt die Formatzeichenkette für die Achsenbeschriftungen dar. Lesen/Schreiben String.

**Rückgabe:**
java.lang.String

### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public abstract void setNumberFormat(String value)
```

Stellt die Formatzeichenkette für die Achsenbeschriftungen dar. Lesen/Schreiben String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public abstract boolean isNumberFormatLinkedToSource()
```

Gibt an, ob das Format mit Quell-Daten verknüpft ist. Lesen/Schreiben boolean.

**Rückgabe:**
boolean

### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public abstract void setNumberFormatLinkedToSource(boolean value)
```

Gibt an, ob das Format mit Quell-Daten verknüpft ist. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getTickLabelRotationAngle() {#getTickLabelRotationAngle--}
```
public abstract float getTickLabelRotationAngle()
```

Stellt den Rotationswinkel der Teilungsbeschriftungen dar. Lesen/Schreiben float.

**Rückgabe:**
float

### setTickLabelRotationAngle(float value) {#setTickLabelRotationAngle-float-}
```
public abstract void setTickLabelRotationAngle(float value)
```

Stellt den Rotationswinkel der Teilungsbeschriftungen dar. Lesen/Schreiben float.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |

### getTickLabelSpacing() {#getTickLabelSpacing--}
```
public abstract long getTickLabelSpacing()
```

Gibt an, wie viele Teilungsbeschriftungen zwischen den gezeichneten Beschriftungen übersprungen werden. Lesen/Schreiben long.

**Rückgabe:**
long

### setTickLabelSpacing(long value) {#setTickLabelSpacing-long-}
```
public abstract void setTickLabelSpacing(long value)
```

Gibt an, wie viele Teilungsbeschriftungen zwischen den gezeichneten Beschriftungen übersprungen werden. Lesen/Schreiben long.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickLabelSpacing() {#isAutomaticTickLabelSpacing--}
```
public abstract boolean isAutomaticTickLabelSpacing()
```

Gibt den automatischen Abstandswert für Teilungsbeschriftungen an. Wenn false: Verwendung der Eigenschaft TickLabelSpacing. Lesen/Schreiben boolean.

**Rückgabe:**
boolean

### setAutomaticTickLabelSpacing(boolean value) {#setAutomaticTickLabelSpacing-boolean-}
```
public abstract void setAutomaticTickLabelSpacing(boolean value)
```

Gibt den automatischen Abstandswert für Teilungsbeschriftungen an. Wenn false: Verwendung der Eigenschaft TickLabelSpacing. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getTickMarksSpacing() {#getTickMarksSpacing--}
```
public abstract long getTickMarksSpacing()
```

Gibt an, wie viele Teilungsstriche übersprungen werden sollen, bevor der nächste gezeichnet wird. Anwendung auf Kategorien- oder Serienachse. Lesen/Schreiben int.

**Rückgabe:**
long

### setTickMarksSpacing(long value) {#setTickMarksSpacing-long-}
```
public abstract void setTickMarksSpacing(long value)
```

Gibt an, wie viele Teilungsstriche übersprungen werden sollen, bevor der nächste gezeichnet wird. Anwendung auf Kategorien- oder Serienachse. Lesen/Schreiben int.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickMarksSpacing() {#isAutomaticTickMarksSpacing--}
```
public abstract boolean isAutomaticTickMarksSpacing()
```

Gibt den automatischen Abstandswert für Teilungsstriche an. Wenn false: Verwendung der Eigenschaft TickMarksSpacing. Lesen/Schreiben boolean.

**Rückgabe:**
boolean

### setAutomaticTickMarksSpacing(boolean value) {#setAutomaticTickMarksSpacing-boolean-}
```
public abstract void setAutomaticTickMarksSpacing(boolean value)
```

Gibt den automatischen Abstandswert für Teilungsstriche an. Wenn false: Verwendung der Eigenschaft TickMarksSpacing. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getLabelOffset() {#getLabelOffset--}
```
public abstract int getLabelOffset()
```

Gibt den Abstand der Beschriftungen von der Achse an. Anwendung auf Kategorien- oder Datumsachse. Der Wert muss zwischen 0 % und 1000 % liegen. Lesen/Schreiben int.

**Rückgabe:**
int

### setLabelOffset(int value) {#setLabelOffset-int-}
```




```

Gibt den Abstand der Beschriftungen von der Achse an. Anwendung auf Kategorien- oder Datumsachse. Der Wert muss zwischen 0 % und 1000 % liegen. Lesen/Schreiben int.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getCategoryAxisType() {#getCategoryAxisType--}
```
public abstract int getCategoryAxisType()
```

Gibt den Typ der Kategorienachse an. Lesen/Schreiben [CategoryAxisType](../../com.aspose.slides/categoryaxistype)(\#getCategoryAxisType.getCategoryAxisType/\#setCategoryAxisType(int).setCategoryAxisType(int)).

**Rückgabe:**
int

### setCategoryAxisType(int value) {#setCategoryAxisType-int-}
```
public abstract int getCategoryAxisType()
```

Gibt den Typ der Kategorienachse an. Lesen/Schreiben [CategoryAxisType](../../com.aspose.slides/categoryaxistype)(\#getCategoryAxisType.getCategoryAxisType/\#setCategoryAxisType(int).setCategoryAxisType(int)).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### setCategoryAxisTypeAutomatically() {#setCategoryAxisTypeAutomatically--}
```
public abstract void setCategoryAxisTypeAutomatically()
```

Setzt die Eigenschaft IAxis.CategoryAxisType mit einem Wert, der basierend auf den Achsendaten automatisch bestimmt wird.

### getAggregationType() {#getAggregationType--}
```
public abstract int getAggregationType()
```

Stellt den Aggregationstyp der Kategorienachse (Binning) dar. Anwendung auf Kategorien. Nur mit Histogram- oder HistogramPareto-Serien verwendet.

**Rückgabe:**
int

### setAggregationType(int value) {#setAggregationType-int-}
```
public abstract void setAggregationType(int value)
```

Stellt den Aggregationstyp der Kategorienachse (Binning) dar. Anwendung auf Kategorien. Nur mit Histogram- oder HistogramPareto-Serien verwendet.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getBinWidth() {#getBinWidth--}
```
public abstract double getBinWidth()
```

Gibt die Bin-Breite an, wenn der AggregationType-Wert auf AxisAggregationType.ByBinWidth gesetzt ist. Anwendung auf Kategorienachsen. Nur mit Histogram- oder HistogramPareto-Serien verwendet.

**Rückgabe:**
double

### setBinWidth(double value) {#setBinWidth-double-}
```
public abstract void setBinWidth(double value)
```

Gibt die Bin-Breite an, wenn der AggregationType-Wert auf AxisAggregationType.ByBinWidth gesetzt ist. Anwendung auf Kategorienachsen. Nur mit Histogram- oder HistogramPareto-Serien verwendet.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |

### getNumberOfBins() {#getNumberOfBins--}
```
public abstract long getNumberOfBins()
```

Gibt die Anzahl der Bins an, wenn der AggregationType-Wert auf AxisAggregationType.ByNumberOfBins gesetzt ist. Anwendung auf Kategorienachsen. Nur mit Histogram- oder HistogramPareto-Serien verwendet.

**Rückgabe:**
long

### setNumberOfBins(long value) {#setNumberOfBins-long-}
```

```

Gibt die Anzahl der Bins an, wenn der AggregationType-Wert auf AxisAggregationType.ByNumberOfBins gesetzt ist. Anwendung auf Kategorienachsen. Nur mit Histogram- oder HistogramPareto-Serien verwendet.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | long |  |

### isOverflowBin() {#isOverflowBin--}
```
public abstract boolean isOverflowBin()
```

Gibt an, ob ein Overflow-Bin angewendet wird. Verwenden Sie IsAutomaticOverflowBin und OverflowBin, um den Overflow-Bin-Wert anzupassen.

**Rückgabe:**
boolean

### setOverflowBin(boolean value) {#setOverflowBin-boolean-}
```
public abstract void setOverflowBin(boolean value)
```

Gibt an, ob ein Overflow-Bin angewendet wird. Verwenden Sie IsAutomaticOverflowBin und OverflowBin, um den Overflow-Bin-Wert anzupassen.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticOverflowBin() {#isAutomaticOverflowBin--}
```
public abstract boolean isAutomaticOverflowBin()
```

Gibt den automatischen Overflow-Bin-Wert an. Wenn false: Verwendung der Eigenschaft OverflowBin.

**Rückgabe:**
boolean

### setAutomaticOverflowBin(boolean value) {#setAutomaticOverflowBin-boolean-}
```
public abstract void setAutomaticOverflowBin(boolean value)
```

Gibt den automatischen Overflow-Bin-Wert an. Wenn false: Verwendung der Eigenschaft OverflowBin.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getOverflowBin() {#getOverflowBin--}
```
public abstract double getOverflowBin()
```

Gibt den benutzerdefinierten Wert des Overflow-Bins an. Anwendung, wenn IsAutomaticOverflowBin auf false gesetzt ist und IsOverflowBin true ist.

**Rückgabe:**
double

### setOverflowBin(double value) {#setOverflowBin-double-}
```
public abstract void setOverflowBin(double value)
```

Gibt den benutzerdefinierten Wert des Overflow-Bins an. Anwendung, wenn IsAutomaticOverflowBin auf false gesetzt ist und IsOverflowBin true ist.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |

### isUnderflowBin() {#isUnderflowBin--}
```
public abstract boolean isUnderflowBin()
```

Gibt an, ob ein Underflow-Bin angewendet wird. Verwenden Sie IsAutomaticUnderflowBin und UnderflowBin, um den Underflow-Bin-Wert anzupassen.

**Rückgabe:**
boolean

### setUnderflowBin(boolean value) {#setUnderflowBin-boolean-}
```
public abstract void setUnderflowBin(boolean value)
```

Gibt an, ob ein Underflow-Bin angewendet wird. Verwenden Sie IsAutomaticUnderflowBin und UnderflowBin, um den Underflow-Bin-Wert anzupassen.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticUnderflowBin() {#isAutomaticUnderflowBin--}
```
public abstract boolean isAutomaticUnderflowBin()
```

Gibt den automatischen Underflow-Bin-Wert an. Wenn false: Verwendung der Eigenschaft UnderflowBin.

**Rückgabe:**
boolean

### setAutomaticUnderflowBin(boolean value) {#setAutomaticUnderflowBin-boolean-}
```
public abstract void setAutomaticUnderflowBin(boolean value)
```

Gibt den automatischen Underflow-Bin-Wert an. Wenn false: Verwendung der Eigenschaft UnderflowBin.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getUnderflowBin() {#getUnderflowBin--}
```
public abstract double getUnderflowBin()
```

Gibt den benutzerdefinierten Wert des Underflow-Bins an. Anwendung, wenn IsAutomaticUnderflowBin auf false gesetzt ist und IsUnderflowBin true ist.

**Rückgabe:**
double

### setUnderflowBin(double value) {#setUnderflowBin-double-}
```
public abstract void setUnderflowBin(double value)
```

Gibt den benutzerdefinierten Wert des Underflow-Bins an. Anwendung, wenn IsAutomaticUnderflowBin auf false gesetzt ist und IsUnderflowBin true ist.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |