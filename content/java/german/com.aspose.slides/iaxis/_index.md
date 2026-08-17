---
title: IAxis
second_title: Aspose.Slides für Java API-Referenz
description: Kapselt das Objekt, das die Achse eines Diagramms darstellt.
type: docs
url: /de/com.aspose.slides/iaxis/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer)
```
public interface IAxis extends IFormattedTextContainer
```

Kapselt das Objekt, das eine Diagrammachse darstellt.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getAxisBetweenCategories()](#getAxisBetweenCategories--) | Gibt an, ob die Werteachse die Kategorienachse zwischen den Kategorien schneidet. |
| [setAxisBetweenCategories(boolean value)](#setAxisBetweenCategories-boolean-) | Gibt an, ob die Werteachse die Kategorienachse zwischen den Kategorien schneidet. |
| [getCrossAt()](#getCrossAt--) | Gibt den Punkt auf der Achse an, an dem die senkrechte Achse sie schneidet. |
| [setCrossAt(float value)](#setCrossAt-float-) | Gibt den Punkt auf der Achse an, an dem die senkrechte Achse sie schneidet. |
| [getDisplayUnit()](#getDisplayUnit--) | Gibt den Skalierungswert der Anzeigeeinheiten für die Werteachse an. |
| [setDisplayUnit(int value)](#setDisplayUnit-int-) | Gibt den Skalierungswert der Anzeigeeinheiten für die Werteachse an. |
| [getActualMaxValue()](#getActualMaxValue--) | Gibt den tatsächlichen Maximalwert der Achse an. |
| [getActualMinValue()](#getActualMinValue--) | Gibt den tatsächlichen Minimalwert der Achse an. |
| [getActualMajorUnit()](#getActualMajorUnit--) | Gibt die tatsächliche Haupteinheit der Achse an. |
| [getActualMinorUnit()](#getActualMinorUnit--) | Gibt die tatsächliche Nebeneinheit der Achse an. |
| [getActualMajorUnitScale()](#getActualMajorUnitScale--) | Gibt den tatsächlichen Maßstab der Haupteinheit der Achse an. |
| [getActualMinorUnitScale()](#getActualMinorUnitScale--) | Gibt den tatsächlichen Maßstab der Nebeneinheit der Achse an. |
| [isAutomaticMaxValue()](#isAutomaticMaxValue--) | Gibt an, ob der Maximalwert automatisch zugewiesen wird. |
| [setAutomaticMaxValue(boolean value)](#setAutomaticMaxValue-boolean-) | Gibt an, ob der Maximalwert automatisch zugewiesen wird. |
| [getMaxValue()](#getMaxValue--) | Gibt den Maximalwert auf der Werteachse an. |
| [setMaxValue(double value)](#setMaxValue-double-) | Gibt den Maximalwert auf der Werteachse an. |
| [getMinorUnit()](#getMinorUnit--) | Gibt die Nebeneinheiten für die Datums- oder Werteachse an. |
| [setMinorUnit(double value)](#setMinorUnit-double-) | Gibt die Nebeneinheiten für die Datums- oder Werteachse an. |
| [isAutomaticMinorUnit()](#isAutomaticMinorUnit--) | Gibt an, ob die Nebeneinheit der Achse automatisch zugewiesen wird. |
| [setAutomaticMinorUnit(boolean value)](#setAutomaticMinorUnit-boolean-) | Gibt an, ob die Nebeneinheit der Achse automatisch zugewiesen wird. |
| [getMajorUnit()](#getMajorUnit--) | Gibt die Haupteinheiten für die Datums- oder Werteachse an. |
| [setMajorUnit(double value)](#setMajorUnit-double-) | Gibt die Haupteinheiten für die Datums- oder Werteachse an. |
| [isAutomaticMajorUnit()](#isAutomaticMajorUnit--) | Gibt an, ob die Haupteinheit der Achse automatisch zugewiesen wird. |
| [setAutomaticMajorUnit(boolean value)](#setAutomaticMajorUnit-boolean-) | Gibt an, ob die Haupteinheit der Achse automatisch zugewiesen wird. |
| [isAutomaticMinValue()](#isAutomaticMinValue--) | Gibt an, ob der Minimalwert automatisch zugewiesen wird. |
| [setAutomaticMinValue(boolean value)](#setAutomaticMinValue-boolean-) | Gibt an, ob der Minimalwert automatisch zugewiesen wird. |
| [getMinValue()](#getMinValue--) | Gibt den Minimalwert auf der Werteachse an. |
| [setMinValue(double value)](#setMinValue-double-) | Gibt den Minimalwert auf der Werteachse an. |
| [isLogarithmic()](#isLogarithmic--) | Gibt an, ob der Skalierungstyp der Werteachse logarithmisch ist oder nicht. |
| [setLogarithmic(boolean value)](#setLogarithmic-boolean-) | Gibt an, ob der Skalierungstyp der Werteachse logarithmisch ist oder nicht. |
| [getLogBase()](#getLogBase--) | Gibt die logarithmische Basis an. |
| [setLogBase(double value)](#setLogBase-double-) | Gibt die logarithmische Basis an. |
| [isPlotOrderReversed()](#isPlotOrderReversed--) | Gibt an, ob MS PowerPoint Datenpunkte von zuletzt zu zuerst plottet. |
| [setPlotOrderReversed(boolean value)](#setPlotOrderReversed-boolean-) | Gibt an, ob MS PowerPoint Datenpunkte von zuletzt zu zuerst plottet. |
| [isVisible()](#isVisible--) | Gibt an, ob die Achse sichtbar ist. |
| [setVisible(boolean value)](#setVisible-boolean-) | Gibt an, ob die Achse sichtbar ist. |
| [getMajorTickMark()](#getMajorTickMark--) | Gibt den Typ des Hauptabschnittszeichens für die angegebene Achse an. |
| [setMajorTickMark(int value)](#setMajorTickMark-int-) | Gibt den Typ des Hauptabschnittszeichens für die angegebene Achse an. |
| [getMinorTickMark()](#getMinorTickMark--) | Gibt den Typ des Nebenabschnittszeichens für die angegebene Achse an. |
| [setMinorTickMark(int value)](#setMinorTickMark-int-) | Gibt den Typ des Nebenabschnittszeichens für die angegebene Achse an. |
| [getTickLabelPosition()](#getTickLabelPosition--) | Gibt die Position der Beschriftungen der Abschnittsmarken auf der angegebenen Achse an. |
| [setTickLabelPosition(int value)](#setTickLabelPosition-int-) | Gibt die Position der Beschriftungen der Abschnittsmarken auf der angegebenen Achse an. |
| [getMajorUnitScale()](#getMajorUnitScale--) | Gibt den Maßstab der Haupteinheit für die Datumsachse an. |
| [setMajorUnitScale(int value)](#setMajorUnitScale-int-) | Gibt den Maßstab der Haupteinheit für die Datumsachse an. |
| [getMinorUnitScale()](#getMinorUnitScale--) | Gibt den Maßstab der Haupteinheit für die Datumsachse an. |
| [setMinorUnitScale(int value)](#setMinorUnitScale-int-) | Gibt den Maßstab der Haupteinheit für die Datumsachse an. |
| [getBaseUnitScale()](#getBaseUnitScale--) | Gibt die kleinste Zeiteinheit an, die auf der Datumsachse dargestellt wird. |
| [setBaseUnitScale(int value)](#setBaseUnitScale-int-) | Gibt die kleinste Zeiteinheit an, die auf der Datumsachse dargestellt wird. |
| [getMinorGridLinesFormat()](#getMinorGridLinesFormat--) | Gibt das Format der Hilfslinien für die Achse eines Diagramms an. |
| [getMajorGridLinesFormat()](#getMajorGridLinesFormat--) | Gibt das Format der Hauptgitternetzlinien für die Achse eines Diagramms an. |
| [getShowMinorGridLines()](#getShowMinorGridLines--) | Gibt an, ob die Hilfslinien angezeigt werden. |
| [getShowMajorGridLines()](#getShowMajorGridLines--) | Gibt an, ob die Hauptgitternetzlinien angezeigt werden. |
| [getFormat()](#getFormat--) | Gibt das Format der Achse an. |
| [getTitle()](#getTitle--) | Liefert den Achsentitel. |
| [getCrossType()](#getCrossType--) | Gibt den Kreuzungstyp auf der angegebenen Achse an, an dem die andere Achse kreuzt. |
| [setCrossType(int value)](#setCrossType-int-) | Gibt den Kreuzungstyp auf der angegebenen Achse an, an dem die andere Achse kreuzt. |
| [getPosition()](#getPosition--) | Gibt die Position der Achse an. |
| [setPosition(int value)](#setPosition-int-) | Gibt die Position der Achse an. |
| [hasTitle()](#hasTitle--) | Bestimmt, ob eine Achse einen sichtbaren Titel hat. |
| [setTitle(boolean value)](#setTitle-boolean-) | Bestimmt, ob eine Achse einen sichtbaren Titel hat. |
| [getNumberFormat()](#getNumberFormat--) | Gibt die Formatzeichenfolge für die Achsenbeschriftungen an. |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | Gibt die Formatzeichenfolge für die Achsenbeschriftungen an. |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | Gibt an, ob das Format mit Quelldaten verknüpft ist. |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | Gibt an, ob das Format mit Quelldaten verknüpft ist. |
| [getTickLabelRotationAngle()](#getTickLabelRotationAngle--) | Gibt den Rotationswinkel der Achsenbeschriftungen an Lesen/Schreiben float. |
| [setTickLabelRotationAngle(float value)](#setTickLabelRotationAngle-float-) | Gibt den Rotationswinkel der Achsenbeschriftungen an Lesen/Schreiben float. |
| [getTickLabelSpacing()](#getTickLabelSpacing--) | Gibt an, wie viele Achsenbeschriftungen übersprungen werden sollen zwischen den dargestellten Beschriftungen. |
| [setTickLabelSpacing(long value)](#setTickLabelSpacing-long-) | Gibt an, wie viele Achsenbeschriftungen übersprungen werden sollen zwischen den dargestellten Beschriftungen. |
| [isAutomaticTickLabelSpacing()](#isAutomaticTickLabelSpacing--) | Gibt den automatischen Abstandswert für Achsenbeschriftungen an. |
| [setAutomaticTickLabelSpacing(boolean value)](#setAutomaticTickLabelSpacing-boolean-) | Gibt den automatischen Abstandswert für Achsenbeschriftungen an. |
| [getTickMarksSpacing()](#getTickMarksSpacing--) | Gibt an, wie viele Achsenmarken übersprungen werden sollen, bevor die nächste gezeichnet wird. |
| [setTickMarksSpacing(long value)](#setTickMarksSpacing-long-) | Gibt an, wie viele Achsenmarken übersprungen werden sollen, bevor die nächste gezeichnet wird. |
| [isAutomaticTickMarksSpacing()](#isAutomaticTickMarksSpacing--) | Gibt den automatischen Abstandswert für Achsenmarken an. |
| [setAutomaticTickMarksSpacing(boolean value)](#setAutomaticTickMarksSpacing-boolean-) | Gibt den automatischen Abstandswert für Achsenmarken an. |
| [getLabelOffset()](#getLabelOffset--) | Gibt den Abstand der Beschriftungen von der Achse an. |
| [setLabelOffset(int value)](#setLabelOffset-int-) | Gibt den Abstand der Beschriftungen von der Achse an. |
| [getCategoryAxisType()](#getCategoryAxisType--) | Gibt den Typ der Kategorienachse an. |
| [setCategoryAxisType(int value)](#setCategoryAxisType-int-) | Gibt den Typ der Kategorienachse an. |
| [setCategoryAxisTypeAutomatically()](#setCategoryAxisTypeAutomatically--) | Setzt die Eigenschaft IAxis.CategoryAxisType auf einen Wert, der basierend auf den Achsendaten automatisch ermittelt wird. |
| [getAggregationType()](#getAggregationType--) | Gibt den Aggregationstyp der Kategorienachse (Binning) an. |
| [setAggregationType(int value)](#setAggregationType-int-) | Gibt den Aggregationstyp der Kategorienachse (Binning) an. |
| [getBinWidth()](#getBinWidth--) | Gibt die Bin-Breite an, wenn der Wert der Eigenschaft AggregationType auf AxisAggregationType.ByBinWidth gesetzt ist. |
| [setBinWidth(double value)](#setBinWidth-double-) | Gibt die Bin-Breite an, wenn der Wert der Eigenschaft AggregationType auf AxisAggregationType.ByBinWidth gesetzt ist. |
| [getNumberOfBins()](#getNumberOfBins--) | Gibt die Anzahl der Bins an, wenn der Wert der Eigenschaft AggregationType auf AxisAggregationType.ByNumberOfBins gesetzt ist. |
| [setNumberOfBins(long value)](#setNumberOfBins-long-) | Gibt die Anzahl der Bins an, wenn der Wert der Eigenschaft AggregationType auf AxisAggregationType.ByNumberOfBins gesetzt ist. |
| [isOverflowBin()](#isOverflowBin--) | Gibt an, ob ein Überlauf-Bin angewendet wird. |
| [setOverflowBin(boolean value)](#setOverflowBin-boolean-) | Gibt an, ob ein Überlauf-Bin angewendet wird. |
| [isAutomaticOverflowBin()](#isAutomaticOverflowBin--) | Gibt den automatischen Überlauf-Bin-Wert an. |
| [setAutomaticOverflowBin(boolean value)](#setAutomaticOverflowBin-boolean-) | Gibt den automatischen Überlauf-Bin-Wert an. |
| [getOverflowBin()](#getOverflowBin--) | Gibt den benutzerdefinierten Überlauf-Bin-Wert an. |
| [setOverflowBin(double value)](#setOverflowBin-double-) | Gibt den benutzerdefinierten Überlauf-Bin-Wert an. |
| [isUnderflowBin()](#isUnderflowBin--) | Gibt an, ob ein Unterlauf-Bin angewendet wird. |
| [setUnderflowBin(boolean value)](#setUnderflowBin-boolean-) | Gibt an, ob ein Unterlauf-Bin angewendet wird. |
| [isAutomaticUnderflowBin()](#isAutomaticUnderflowBin--) | Gibt den automatischen Unterlauf-Bin-Wert an. |
| [setAutomaticUnderflowBin(boolean value)](#setAutomaticUnderflowBin-boolean-) | Gibt den automatischen Unterlauf-Bin-Wert an. |
| [getUnderflowBin()](#getUnderflowBin--) | Gibt den benutzerdefinierten Unterlauf-Bin-Wert an. |
| [setUnderflowBin(double value)](#setUnderflowBin-double-) | Gibt den benutzerdefinierten Unterlauf-Bin-Wert an. |

### getAxisBetweenCategories() {#getAxisBetweenCategories--}
```
public abstract boolean getAxisBetweenCategories()
```

Gibt an, ob die Werteachse die Kategorienachse zwischen den Kategorien schneidet. Diese Eigenschaft gilt nur für Kategorienachsen und nicht für 3-D-Diagramme. Lesen/Schreiben boolesch.

**Rückgabewert:**
boolean

### setAxisBetweenCategories(boolean value) {#setAxisBetweenCategories-boolean-}
```
public abstract void setAxisBetweenCategories(boolean value)
```

Gibt an, ob die Werteachse die Kategorienachse zwischen den Kategorien schneidet. Diese Eigenschaft gilt nur für Kategorienachsen und nicht für 3-D-Diagramme. Lesen/Schreiben boolesch.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getCrossAt() {#getCrossAt--}
```
public abstract float getCrossAt()
```

Gibt den Punkt auf der Achse an, an dem die senkrechte Achse sie schneidet. Lesen/Schreiben float.

**Rückgabewert:**
float

### setCrossAt(float value) {#setCrossAt-float-}
```
public abstract void setCrossAt(float value)
```

Gibt den Punkt auf der Achse an, an dem die senkrechte Achse sie schneidet. Lesen/Schreiben float.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |

### getDisplayUnit() {#getDisplayUnit--}
```
public abstract int getDisplayUnit()
```

Gibt den Skalierungswert der Anzeigeeinheiten für die Werteachse an. Lesen/Schreiben [DisplayUnitType](../../com.aspose.slides/displayunittype).

**Rückgabewert:**
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

Gibt den tatsächlichen Maximalwert der Achse an. Rufen Sie zuvor die Methode IChart.ValidateChartLayout() auf, um den tatsächlichen Wert zu erhalten.

**Rückgabewert:**
double

### getActualMinValue() {#getActualMinValue--}
```
public abstract double getActualMinValue()
```

Gibt den tatsächlichen Minimalwert der Achse an. Rufen Sie zuvor die Methode IChart.ValidateChartLayout() auf, um den tatsächlichen Wert zu erhalten.

**Rückgabewert:**
double

### getActualMajorUnit() {#getActualMajorUnit--}
```
public abstract double getActualMajorUnit()
```

Gibt die tatsächliche Haupteinheit der Achse an. Rufen Sie zuvor die Methode IChart.ValidateChartLayout() auf, um den tatsächlichen Wert zu erhalten.

**Rückgabewert:**
double

### getActualMinorUnit() {#getActualMinorUnit--}
```
public abstract double getActualMinorUnit()
```

Gibt die tatsächliche Nebeneinheit der Achse an. Rufen Sie zuvor die Methode IChart.ValidateChartLayout() auf, um den tatsächlichen Wert zu erhalten.

**Rückgabewert:**
double

### getActualMajorUnitScale() {#getActualMajorUnitScale--}
```
public abstract int getActualMajorUnitScale()
```

Gibt den tatsächlichen Maßstab der Haupteinheit der Achse an. Rufen Sie zuvor die Methode IChart.ValidateChartLayout() auf, um den tatsächlichen Wert zu erhalten.

**Rückgabewert:**
int

### getActualMinorUnitScale() {#getActualMinorUnitScale--}
```
public abstract int getActualMinorUnitScale()
```

Gibt den tatsächlichen Maßstab der Nebeneinheit der Achse an. Rufen Sie zuvor die Methode IChart.ValidateChartLayout() auf, um den tatsächlichen Wert zu erhalten.

**Rückgabewert:**
int

### isAutomaticMaxValue() {#isAutomaticMaxValue--}
```
public abstract boolean isAutomaticMaxValue()
```

Gibt an, ob der Maximalwert automatisch zugewiesen wird. Lesen/Schreiben boolesch.

**Rückgabewert:**
boolean

### setAutomaticMaxValue(boolean value) {#setAutomaticMaxValue-boolean-}
```
public abstract void setAutomaticMaxValue(boolean value)
```

Gibt an, ob der Maximalwert automatisch zugewiesen wird. Lesen/Schreiben boolesch.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getMaxValue() {#getMaxValue--}
```
public abstract double getMaxValue()
```

Gibt den Maximalwert auf der Werteachse an. Lesen/Schreiben double.

**Rückgabewert:**
double

### setMaxValue(double value) {#setMaxValue-double-}
```
public abstract void setMaxValue(double value)
```

Gibt den Maximalwert auf der Werteachse an. Lesen/Schreiben double.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |

### getMinorUnit() {#getMinorUnit--}
```
public abstract double getMinorUnit()
```

Gibt die Nebeneinheiten für die Datums- oder Werteachse an. Lesen/Schreiben double.

**Rückgabewert:**
double

### setMinorUnit(double value) {#setMinorUnit-double-}
```
public abstract void setMinorUnit(double value)
```

Gibt die Nebeneinheiten für die Datums- oder Werteachse an. Lesen/Schreiben double.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |

### isAutomaticMinorUnit() {#isAutomaticMinorUnit--}
```
public abstract boolean isAutomaticMinorUnit()
```

Gibt an, ob die Nebeneinheit der Achse automatisch zugewiesen wird. Lesen/Schreiben boolesch.

**Rückgabewert:**
boolean

### setAutomaticMinorUnit(boolean value) {#setAutomaticMinorUnit-boolean-}
```
public abstract void setAutomaticMinorUnit(boolean value)
```

Gibt an, ob die Nebeneinheit der Achse automatisch zugewiesen wird. Lesen/Schreiben boolesch.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getMajorUnit() {#getMajorUnit--}
```
public abstract double getMajorUnit()
```

Gibt die Haupteinheiten für die Datums- oder Werteachse an. Lesen/Schreiben double.

**Rückgabewert:**
double

### setMajorUnit(double value) {#setMajorUnit-double-}
```
public abstract void setMajorUnit(double value)
```

Gibt die Haupteinheiten für die Datums- oder Werteachse an. Lesen/Schreiben double.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |

### isAutomaticMajorUnit() {#isAutomaticMajorUnit--}
```
public abstract boolean isAutomaticMajorUnit()
```

Gibt an, ob die Haupteinheit der Achse automatisch zugewiesen wird. Lesen/Schreiben boolesch.

**Rückgabewert:**
boolean
### setAutomaticMajorUnit(boolean value) {#setAutomaticMajorUnit-boolean-}
```
public abstract void setAutomaticMajorUnit(boolean value)
```

Gibt an, ob die Haupteinheit der Achse automatisch zugewiesen wird. Lese/Schreib boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticMinValue() {#isAutomaticMinValue--}
```
public abstract boolean isAutomaticMinValue()
```

Gibt an, ob der Minimalwert automatisch zugewiesen wird. Lese/Schreib boolean.

**Rückgabewert:**
boolean
### setAutomaticMinValue(boolean value) {#setAutomaticMinValue-boolean-}
```
public abstract void setAutomaticMinValue(boolean value)
```

Gibt an, ob der Minimalwert automatisch zugewiesen wird. Lese/Schreib boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getMinValue() {#getMinValue--}
```
public abstract double getMinValue()
```

Stellt den Minimalwert auf der Werteachse dar. Lese/Schreib double.

**Rückgabewert:**
double
### setMinValue(double value) {#setMinValue-double-}
```
public abstract void setMinValue(double value)
```

Stellt den Minimalwert auf der Werteachse dar. Lese/Schreib double.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |

### isLogarithmic() {#isLogarithmic--}
```
public abstract boolean isLogarithmic()
```

Stellt dar, ob der Skalierungstyp der Werteachse logarithmisch ist oder nicht. Lese/Schreib boolean.

**Rückgabewert:**
boolean
### setLogarithmic(boolean value) {#setLogarithmic-boolean-}
```
public abstract void setLogarithmic(boolean value)
```

Stellt dar, ob der Skalierungstyp der Werteachse logarithmisch ist oder nicht. Lese/Schreib boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getLogBase() {#getLogBase--}
```
public abstract double getLogBase()
```

Stellt die logarithmische Basis dar. Standardwert ist 10. Lese/Schreib double.

**Rückgabewert:**
double
### setLogBase(double value) {#setLogBase-double-}
```
public abstract void setLogBase(double value)
```

Stellt die logarithmische Basis dar. Standardwert ist 10. Lese/Schreib double.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |

### isPlotOrderReversed() {#isPlotOrderReversed--}
```
public abstract boolean isPlotOrderReversed()
```

Stellt dar, ob MS PowerPoint Datenpunkte von zuletzt nach zuerst darstellt. Lese/Schreib boolean.

**Rückgabewert:**
boolean
### setPlotOrderReversed(boolean value) {#setPlotOrderReversed-boolean-}
```
public abstract void setPlotOrderReversed(boolean value)
```

Stellt dar, ob MS PowerPoint Datenpunkte von zuletzt nach zuerst darstellt. Lese/Schreib boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

Stellt dar, ob die Achse sichtbar ist. Lese/Schreib boolean.

**Rückgabewert:**
boolean
### setVisible(boolean value) {#setVisible-boolean-}
```
public abstract void setVisible(boolean value)
```

Stellt dar, ob die Achse sichtbar ist. Lese/Schreib boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getMajorTickMark() {#getMajorTickMark--}
```
public abstract int getMajorTickMark()
```

Stellt den Typ des Haupttickmarks für die angegebene Achse dar. Lese/Schreib [TickMarkType](../../com.aspose.slides/tickmarktype).

**Rückgabewert:**
int
### setMajorTickMark(int value) {#setMajorTickMark-int-}
```
public abstract void setMajorTickMark(int value)
```

Stellt den Typ des Haupttickmarks für die angegebene Achse dar. Lese/Schreib [TickMarkType](../../com.aspose.slides/tickmarktype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getMinorTickMark() {#getMinorTickMark--}
```
public abstract int getMinorTickMark()
```

Stellt den Typ des Nebentickmarks für die angegebene Achse dar. Lese/Schreib [TickMarkType](../../com.aspose.slides/tickmarktype).

**Rückgabewert:**
int
### setMinorTickMark(int value) {#setMinorTickMark-int-}
```
public abstract void setMinorTickMark(int value)
```

Stellt den Typ des Nebentickmarks für die angegebene Achse dar. Lese/Schreib [TickMarkType](../../com.aspose.slides/tickmarktype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getTickLabelPosition() {#getTickLabelPosition--}
```
public abstract int getTickLabelPosition()
```

Stellt die Position der Tick-Beschriftungslabels auf der angegebenen Achse dar. Lese/Schreib [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**Rückgabewert:**
int
### setTickLabelPosition(int value) {#setTickLabelPosition-int-}
```
public abstract void setTickLabelPosition(int value)
```

Stellt die Position der Tick-Beschriftungslabels auf der angegebenen Achse dar. Lese/Schreib [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getMajorUnitScale() {#getMajorUnitScale--}
```
public abstract int getMajorUnitScale()
```

Stellt die Hauptschnellsskala für die Datumsachse dar. Lese/Schreib [TimeUnitType](../../com.aspose.slides/timeunittype).

**Rückgabewert:**
int
### setMajorUnitScale(int value) {#setMajorUnitScale-int-}
```
public abstract void setMajorUnitScale(int value)
```

Stellt die Hauptschnellsskala für die Datumsachse dar. Lese/Schreib [TimeUnitType](../../com.aspose.slides/timeunittype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getMinorUnitScale() {#getMinorUnitScale--}
```
public abstract int getMinorUnitScale()
```

Stellt die Hauptschnellsskala für die Datumsachse dar. Lese/Schreib [TimeUnitType](../../com.aspose.slides/timeunittype).

**Rückgabewert:**
int
### setMinorUnitScale(int value) {#setMinorUnitScale-int-}
```
public abstract void setMinorUnitScale(int value)
```

Stellt die Hauptschnellsskala für die Datumsachse dar. Lese/Schreib [TimeUnitType](../../com.aspose.slides/timeunittype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getBaseUnitScale() {#getBaseUnitScale--}
```
public abstract int getBaseUnitScale()
```

Gibt die kleinste Zeiteinheit an, die auf der Datumsachse dargestellt wird. Lese/Schreib [TimeUnitType](../../com.aspose.slides/timeunittype).

**Rückgabewert:**
int
### setBaseUnitScale(int value) {#setBaseUnitScale-int-}
```
public abstract void setBaseUnitScale(int value)
```

Gibt die kleinste Zeiteinheit an, die auf der Datumsachse dargestellt wird. Lese/Schreib [TimeUnitType](../../com.aspose.slides/timeunittype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getMinorGridLinesFormat() {#getMinorGridLinesFormat--}
```
public abstract IChartLinesFormat getMinorGridLinesFormat()
```

Stellt das Format der sekundären Gitternetzlinien einer Diagrammachse dar. Nur lesbar [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**Rückgabewert:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### getMajorGridLinesFormat() {#getMajorGridLinesFormat--}
```
public abstract IChartLinesFormat getMajorGridLinesFormat()
```

Stellt das Format der primären Gitternetzlinien einer Diagrammachse dar. Nur lesbar [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**Rückgabewert:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### getShowMinorGridLines() {#getShowMinorGridLines--}
```
public abstract boolean getShowMinorGridLines()
```

Gibt an, ob die sekundären Gitternetzlinien angezeigt werden. Nur lesbar boolean.

**Rückgabewert:**
boolean
### getShowMajorGridLines() {#getShowMajorGridLines--}
```
public abstract boolean getShowMajorGridLines()
```

Gibt an, ob die primären Gitternetzlinien angezeigt werden. Nur lesbar boolean.

**Rückgabewert:**
boolean
### getFormat() {#getFormat--}
```
public abstract IAxisFormat getFormat()
```

Stellt das Format der Achse dar. Nur lesbar [IAxisFormat](../../com.aspose.slides/iaxisformat).

**Rückgabewert:**
[IAxisFormat](../../com.aspose.slides/iaxisformat)
### getTitle() {#getTitle--}
```
public abstract IChartTitle getTitle()
```

Liefert den Titel der Achse. Nur lesbar [IChartTitle](../../com.aspose.slides/icharttitle).

**Rückgabewert:**
[IChartTitle](../../com.aspose.slides/icharttitle)
### getCrossType() {#getCrossType--}
```
public abstract int getCrossType()
```

Stellt den CrossType auf der angegebenen Achse dar, an dem die andere Achse kreuzt. Lese/Schreib [CrossesType](../../com.aspose.slides/crossestype).

**Rückgabewert:**
int
### setCrossType(int value) {#setCrossType-int-}
```
public abstract void setCrossType(int value)
```

Stellt den CrossType auf der angegebenen Achse dar, an dem die andere Achse kreuzt. Lese/Schreib [CrossesType](../../com.aspose.slides/crossestype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

Stellt die Position der Achse dar. Lese/Schreib [AxisPositionType](../../com.aspose.slides/axispositiontype).

**Rückgabewert:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

Stellt die Position der Achse dar. Lese/Schreib [AxisPositionType](../../com.aspose.slides/axispositiontype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### hasTitle() {#hasTitle--}
```
public abstract boolean hasTitle()
```

Bestimmt, ob eine Achse einen sichtbaren Titel hat. Lese/Schreib boolean.

**Rückgabewert:**
boolean
### setTitle(boolean value) {#setTitle-boolean-}
```
public abstract void setTitle(boolean value)
```

Bestimmt, ob eine Achse einen sichtbaren Titel hat. Lese/Schreib boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public abstract String getNumberFormat()
```

Stellt die Formatzeichenfolge für die Achsenbeschriftungen dar. Lese/Schreib String.

**Rückgabewert:**
java.lang.String
### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public abstract void setNumberFormat(String value)
```

Stellt die Formatzeichenfolge für die Achsenbeschriftungen dar. Lese/Schreib String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public abstract boolean isNumberFormatLinkedToSource()
```

Gibt an, ob das Format mit den Quelldaten verknüpft ist. Lese/Schreib boolean.

**Rückgabewert:**
boolean
### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public abstract void setNumberFormatLinkedToSource(boolean value)
```

Gibt an, ob das Format mit den Quelldaten verknüpft ist. Lese/Schreib boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getTickLabelRotationAngle() {#getTickLabelRotationAngle--}
```
public abstract float getTickLabelRotationAngle()
```

Stellt den Rotationswinkel der Tick-Beschriftungen dar. Lese/Schreib float.

**Rückgabewert:**
float
### setTickLabelRotationAngle(float value) {#setTickLabelRotationAngle-float-}
```
public abstract void setTickLabelRotationAngle(float value)
```

Stellt den Rotationswinkel der Tick-Beschriftungen dar. Lese/Schreib float.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |

### getTickLabelSpacing() {#getTickLabelSpacing--}
```
public abstract long getTickLabelSpacing()
```

Gibt an, wie viele Tick-Beschriftungen zwischen einer gezeichneten Beschriftung übersprungen werden sollen. Lese/Schreib long.

**Rückgabewert:**
long
### setTickLabelSpacing(long value) {#setTickLabelSpacing-long-}
```
public abstract void setTickLabelSpacing(long value)
```

Gibt an, wie viele Tick-Beschriftungen zwischen einer gezeichneten Beschriftung übersprungen werden sollen. Lese/Schreib long.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickLabelSpacing() {#isAutomaticTickLabelSpacing--}
```
public abstract boolean isAutomaticTickLabelSpacing()
```

Gibt den automatischen Abstand der Tick-Beschriftungen an. Wenn false: wird die Eigenschaft TickLabelSpacing verwendet. Lese/Schreib boolean.

**Rückgabewert:**
boolean
### setAutomaticTickLabelSpacing(boolean value) {#setAutomaticTickLabelSpacing-boolean-}
```
public abstract void setAutomaticTickLabelSpacing(boolean value)
```

Gibt den automatischen Abstand der Tick-Beschriftungen an. Wenn false: wird die Eigenschaft TickLabelSpacing verwendet. Lese/Schreib boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getTickMarksSpacing() {#getTickMarksSpacing--}
```
public abstract long getTickMarksSpacing()
```

Gibt an, wie viele Tick-Markierungen übersprungen werden sollen, bevor die nächste gezeichnet wird. Gilt für Kategorien- oder Reihenachse. Lese/Schreib int.

**Rückgabewert:**
long
### setTickMarksSpacing(long value) {#setTickMarksSpacing-long-}
```
public abstract void setTickMarksSpacing(long value)
```

Gibt an, wie viele Tick-Markierungen übersprungen werden sollen, bevor die nächste gezeichnet wird. Gilt für Kategorien- oder Reihenachse. Lese/Schreib int.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickMarksSpacing() {#isAutomaticTickMarksSpacing--}
```
public abstract boolean isAutomaticTickMarksSpacing()
```

Gibt den automatischen Abstand der Tick-Markierungen an. Wenn false: wird die Eigenschaft TickMarksSpacing verwendet. Lese/Schreib boolean.

**Rückgabewert:**
boolean
### setAutomaticTickMarksSpacing(boolean value) {#setAutomaticTickMarksSpacing-boolean-}
```
public abstract void setAutomaticTickMarksSpacing(boolean value)
```

Gibt den automatischen Abstand der Tick-Markierungen an. Wenn false: wird die Eigenschaft TickMarksSpacing verwendet. Lese/Schreib boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getLabelOffset() {#getLabelOffset--}
```
public abstract int getLabelOffset()
```

Gibt den Abstand der Beschriftungen von der Achse an. Gilt für Kategorien- oder Datumsachse. Der Wert muss zwischen 0 % und 1000 % liegen. Lese/Schreib int.

**Rückgabewert:**
int
### setLabelOffset(int value) {#setLabelOffset-int-}
```
public abstract void setLabelOffset(int value)
```

Gibt den Abstand der Beschriftungen von der Achse an. Gilt für Kategorien- oder Datumsachse. Der Wert muss zwischen 0 % und 1000 % liegen. Lese/Schreib int.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getCategoryAxisType() {#getCategoryAxisType--}
```
public abstract int getCategoryAxisType()
```

Gibt den Typ der Kategorienachse an. Lese/Schreib [CategoryAxisType](../../com.aspose.slides/categoryaxistype)(\#getCategoryAxisType.getCategoryAxisType/\#setCategoryAxisType(int).setCategoryAxisType(int)).

**Rückgabewert:**
int
### setCategoryAxisType(int value) {#setCategoryAxisType-int-}
```
public abstract void setCategoryAxisType(int value)
```

Gibt den Typ der Kategorienachse an. Lese/Schreib [CategoryAxisType](../../com.aspose.slides/categoryaxistype)(\#getCategoryAxisType.getCategoryAxisType/\#setCategoryAxisType(int).setCategoryAxisType(int)).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### setCategoryAxisTypeAutomatically() {#setCategoryAxisTypeAutomatically--}
```
public abstract void setCategoryAxisTypeAutomatically()
```

Setzt die Eigenschaft IAxis.CategoryAxisType mit einem Wert, der automatisch basierend auf den Achsendaten bestimmt wird.

### getAggregationType() {#getAggregationType--}
```
public abstract int getAggregationType()
```

Stellt den Aggregationstyp der Kategorienachse (Binning) dar. Gilt für Kategorien. Wird nur mit Histogramm- oder HistogrammPareto-Serien verwendet.

**Rückgabewert:**
int
### setAggregationType(int value) {#setAggregationType-int-}
```
public abstract void setAggregationType(int value)
```

Stellt den Aggregationstyp der Kategorienachse (Binning) dar. Gilt für Kategorien. Wird nur mit Histogramm- oder HistogrammPareto-Serien verwendet.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### getBinWidth() {#getBinWidth--}
```
public abstract double getBinWidth()
```

Gibt die Bin-Breite an, wenn der Wert der AggregationType-Eigenschaft auf AxisAggregationType.ByBinWidth gesetzt ist. Gilt für Kategorienachsen. Wird nur mit Histogram oder HistogramPareto Serien verwendet.

**Rückgabewert:**
double
### setBinWidth(double value) {#setBinWidth-double-}
```
public abstract void setBinWidth(double value)
```

Gibt die Bin-Breite an, wenn der Wert der AggregationType-Eigenschaft auf AxisAggregationType.ByBinWidth gesetzt ist. Gilt für Kategorienachsen. Wird nur mit Histogram oder HistogramPareto Serien verwendet.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |
### getNumberOfBins() {#getNumberOfBins--}
```
public abstract long getNumberOfBins()
```

Gibt die Anzahl der Bins an, wenn der Wert der AggregationType-Eigenschaft auf AxisAggregationType.ByNumberOfBins gesetzt ist. Gilt für Kategorienachsen. Wird nur mit Histogram oder HistogramPareto Serien verwendet.

**Rückgabewert:**
long
### setNumberOfBins(long value) {#setNumberOfBins-long-}
```
public abstract void setNumberOfBins(long value)
```

Gibt die Anzahl der Bins an, wenn der Wert der AggregationType-Eigenschaft auf AxisAggregationType.ByNumberOfBins gesetzt ist. Gilt für Kategorienachsen. Wird nur mit Histogram oder HistogramPareto Serien verwendet.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |
### isOverflowBin() {#isOverflowBin--}
```
public abstract boolean isOverflowBin()
```

Gibt an, ob ein Überlauf-Bin angewendet wird. Verwenden Sie IsAutomaticOverflowBin und OverflowBin, um den Wert des Überlauf-Bins anzupassen.

**Rückgabewert:**
boolean
### setOverflowBin(boolean value) {#setOverflowBin-boolean-}
```
public abstract void setOverflowBin(boolean value)
```

Gibt an, ob ein Überlauf-Bin angewendet wird. Verwenden Sie IsAutomaticOverflowBin und OverflowBin, um den Wert des Überlauf-Bins anzupassen.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### isAutomaticOverflowBin() {#isAutomaticOverflowBin--}
```
public abstract boolean isAutomaticOverflowBin()
```

Gibt den automatischen Überlauf-Bin-Wert an. Wenn false: Verwenden Sie die OverflowBin-Eigenschaft.

**Rückgabewert:**
boolean
### setAutomaticOverflowBin(boolean value) {#setAutomaticOverflowBin-boolean-}
```
public abstract void setAutomaticOverflowBin(boolean value)
```

Gibt den automatischen Überlauf-Bin-Wert an. Wenn false: Verwenden Sie die OverflowBin-Eigenschaft.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getOverflowBin() {#getOverflowBin--}
```
public abstract double getOverflowBin()
```

Gibt den benutzerdefinierten Wert des Überlauf-Bins an. Wird angewendet, wenn IsAutomaticOverflowBin-Eigenschaft auf false gesetzt ist und IsOverflowBin-Eigenschaft true ist.

**Rückgabewert:**
double
### setOverflowBin(double value) {#setOverflowBin-double-}
```
public abstract void setOverflowBin(double value)
```

Gibt den benutzerdefinierten Wert des Überlauf-Bins an. Wird angewendet, wenn IsAutomaticOverflowBin-Eigenschaft auf false gesetzt ist und IsOverflowBin-Eigenschaft true ist.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |
### isUnderflowBin() {#isUnderflowBin--}
```
public abstract boolean isUnderflowBin()
```

Gibt an, ob ein Unterlauf-Bin angewendet wird. Verwenden Sie IsAutomaticUnderflowBin und UnderflowBin, um den Wert des Unterlauf-Bins anzupassen.

**Rückgabewert:**
boolean
### setUnderflowBin(boolean value) {#setUnderflowBin-boolean-}
```
public abstract void setUnderflowBin(boolean value)
```

Gibt an, ob ein Unterlauf-Bin angewendet wird. Verwenden Sie IsAutomaticUnderflowBin und UnderflowBin, um den Wert des Unterlauf-Bins anzupassen.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### isAutomaticUnderflowBin() {#isAutomaticUnderflowBin--}
```
public abstract boolean isAutomaticUnderflowBin()
```

Gibt den automatischen Unterlauf-Bin-Wert an. Wenn false: Verwenden Sie die UnderflowBin-Eigenschaft.

**Rückgabewert:**
boolean
### setAutomaticUnderflowBin(boolean value) {#setAutomaticUnderflowBin-boolean-}
```
public abstract void setAutomaticUnderflowBin(boolean value)
```

Gibt den automatischen Unterlauf-Bin-Wert an. Wenn false: Verwenden Sie die UnderflowBin-Eigenschaft.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getUnderflowBin() {#getUnderflowBin--}
```
public abstract double getUnderflowBin()
```

Gibt den benutzerdefinierten Wert des Unterlauf-Bins an. Wird angewendet, wenn IsAutomaticUnderflowBin-Eigenschaft auf false gesetzt ist und IsUnderflowBin-Eigenschaft true ist.

**Rückgabewert:**
double
### setUnderflowBin(double value) {#setUnderflowBin-double-}
```
public abstract void setUnderflowBin(double value)
```

Gibt den benutzerdefinierten Wert des Unterlauf-Bins an. Wird angewendet, wenn IsAutomaticUnderflowBin-Eigenschaft auf false gesetzt ist und IsUnderflowBin-Eigenschaft true ist.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |