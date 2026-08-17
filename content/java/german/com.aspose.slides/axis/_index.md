---
title: Axis
second_title: Aspose.Slides für Java API-Referenz
description: Kapselt das Objekt, das eine Diagrammachse darstellt.
type: docs
url: /de/com.aspose.slides/axis/
---
**Vererbung:**
java.lang.Object, com.aspose.slides.DomObject

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IAxis](../../com.aspose.slides/iaxis)
```
public class Axis extends DomObject<AxesManager> implements IAxis
```

Kapselt das Objekt, das eine Diagrammachse repräsentiert.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getChart()](#getChart--) | Gibt das übergeordnete Diagramm zurück. |
| [getAxisBetweenCategories()](#getAxisBetweenCategories--) | Gibt an, ob die Werteachse die Kategorieachse zwischen Kategorien schneidet. |
| [setAxisBetweenCategories(boolean value)](#setAxisBetweenCategories-boolean-) | Gibt an, ob die Werteachse die Kategorieachse zwischen Kategorien schneidet. |
| [getCategoryAxisType()](#getCategoryAxisType--) | Gibt den Typ der Kategorieachse an. |
| [setCategoryAxisType(int value)](#setCategoryAxisType-int-) | Gibt den Typ der Kategorieachse an. |
| [setCategoryAxisTypeAutomatically()](#setCategoryAxisTypeAutomatically--) | Setzt die IAxis.CategoryAxisType Eigenschaft mit einem Wert, der basierend auf den Achsendaten automatisch bestimmt wird. |
| [getCrossAt()](#getCrossAt--) | Gibt den Punkt auf der Achse an, an dem die senkrechte Achse sie schneidet. |
| [setCrossAt(float value)](#setCrossAt-float-) | Gibt den Punkt auf der Achse an, an dem die senkrechte Achse sie schneidet. |
| [getDisplayUnit()](#getDisplayUnit--) | Gibt den Skalierungswert der Anzeigeeinheiten für die Werteachse an. |
| [setDisplayUnit(int value)](#setDisplayUnit-int-) | Gibt den Skalierungswert der Anzeigeeinheiten für die Werteachse an. |
| [getActualMaxValue()](#getActualMaxValue--) | Gibt den tatsächlichen Maximalwert auf der Achse an. |
| [getActualMinValue()](#getActualMinValue--) | Gibt den tatsächlichen Minimalwert auf der Achse an. |
| [getActualMajorUnit()](#getActualMajorUnit--) | Gibt die tatsächliche Haupteinheit der Achse an. |
| [getActualMinorUnit()](#getActualMinorUnit--) | Gibt die tatsächliche Nebenheit der Achse an. |
| [getActualMajorUnitScale()](#getActualMajorUnitScale--) | Gibt die tatsächliche Skalierung der Haupteinheit der Achse an. |
| [getActualMinorUnitScale()](#getActualMinorUnitScale--) | Gibt die tatsächliche Skalierung der Nebenheit der Achse an. |
| [isAutomaticMaxValue()](#isAutomaticMaxValue--) | Gibt an, ob der Maximalwert automatisch zugewiesen wird. |
| [setAutomaticMaxValue(boolean value)](#setAutomaticMaxValue-boolean-) | Gibt an, ob der Maximalwert automatisch zugewiesen wird. |
| [getMaxValue()](#getMaxValue--) | Gibt den Maximalwert auf der Werteachse an. |
| [setMaxValue(double value)](#setMaxValue-double-) | Gibt den Maximalwert auf der Werteachse an. |
| [getMinorUnit()](#getMinorUnit--) | Gibt die Nebenheiten für die Datums- oder Werteachse an. |
| [setMinorUnit(double value)](#setMinorUnit-double-) | Gibt die Nebenheiten für die Datums- oder Werteachse an. |
| [isAutomaticMinorUnit()](#isAutomaticMinorUnit--) | Gibt an, ob die Nebenheit der Achse automatisch zugewiesen wird. |
| [setAutomaticMinorUnit(boolean value)](#setAutomaticMinorUnit-boolean-) | Gibt an, ob die Nebenheit der Achse automatisch zugewiesen wird. |
| [getMajorUnit()](#getMajorUnit--) | Gibt die Haupteinheiten für die Datums- oder Werteachse an. |
| [setMajorUnit(double value)](#setMajorUnit-double-) | Gibt die Haupteinheiten für die Datums- oder Werteachse an. |
| [isAutomaticMajorUnit()](#isAutomaticMajorUnit--) | Gibt an, ob die Haupteinheit der Achse automatisch zugewiesen wird. |
| [setAutomaticMajorUnit(boolean value)](#setAutomaticMajorUnit-boolean-) | Gibt an, ob die Haupteinheit der Achse automatisch zugewiesen wird. |
| [isAutomaticMinValue()](#isAutomaticMinValue--) | Gibt an, ob der Minimalwert automatisch zugewiesen wird. |
| [setAutomaticMinValue(boolean value)](#setAutomaticMinValue-boolean-) | Gibt an, ob der Minimalwert automatisch zugewiesen wird. |
| [getMinValue()](#getMinValue--) | Gibt den Minimalwert auf der Werteachse an. |
| [setMinValue(double value)](#setMinValue-double-) | Gibt den Minimalwert auf der Werteachse an. |
| [isLogarithmic()](#isLogarithmic--) | Gibt an, ob der Skalierungstyp der Werteachse logarithmisch ist. |
| [setLogarithmic(boolean value)](#setLogarithmic-boolean-) | Gibt an, ob der Skalierungstyp der Werteachse logarithmisch ist. |
| [getLogBase()](#getLogBase--) | Gibt die logarithmische Basis an. |
| [setLogBase(double value)](#setLogBase-double-) | Gibt die logarithmische Basis an. |
| [isPlotOrderReversed()](#isPlotOrderReversed--) | Gibt an, ob MS PowerPoint die Datenpunkte von zuletzt nach zuerst darstellt. |
| [setPlotOrderReversed(boolean value)](#setPlotOrderReversed-boolean-) | Gibt an, ob MS PowerPoint die Datenpunkte von zuletzt nach zuerst darstellt. |
| [isVisible()](#isVisible--) | Gibt an, ob die Achse sichtbar ist. |
| [setVisible(boolean value)](#setVisible-boolean-) | Gibt an, ob die Achse sichtbar ist. |
| [getMajorTickMark()](#getMajorTickMark--) | Gibt den Typ der Haupthäkchen für die angegebene Achse an. |
| [setMajorTickMark(int value)](#setMajorTickMark-int-) | Gibt den Typ der Haupthäkchen für die angegebene Achse an. |
| [getMinorTickMark()](#getMinorTickMark--) | Gibt den Typ der Nebenhäkchen für die angegebene Achse an. |
| [setMinorTickMark(int value)](#setMinorTickMark-int-) | Gibt den Typ der Nebenhäkchen für die angegebene Achse an. |
| [getTickLabelPosition()](#getTickLabelPosition--) | Gibt die Position der Tick-Mark-Beschriftungen auf der angegebenen Achse an. |
| [setTickLabelPosition(int value)](#setTickLabelPosition-int-) | Gibt die Position der Tick-Mark-Beschriftungen auf der angegebenen Achse an. |
| [getMajorUnitScale()](#getMajorUnitScale--) | Gibt die Skalierung der Haupteinheit für die Datumsachse an. |
| [setMajorUnitScale(int value)](#setMajorUnitScale-int-) | Gibt die Skalierung der Haupteinheit für die Datumsachse an. |
| [getMinorUnitScale()](#getMinorUnitScale--) | Gibt die Skalierung der Haupteinheit für die Datumsachse an. |
| [setMinorUnitScale(int value)](#setMinorUnitScale-int-) | Gibt die Skalierung der Haupteinheit für die Datumsachse an. |
| [getBaseUnitScale()](#getBaseUnitScale--) | Gibt die kleinste Zeiteinheit an, die auf der Datumsachse dargestellt wird. |
| [setBaseUnitScale(int value)](#setBaseUnitScale-int-) | Gibt die kleinste Zeiteinheit an, die auf der Datumsachse dargestellt wird. |
| [getMinorGridLinesFormat()](#getMinorGridLinesFormat--) | Gibt das Format der Nebenrasterlinien einer Diagrammachse an. |
| [getMajorGridLinesFormat()](#getMajorGridLinesFormat--) | Gibt das Format der Hauptrasterlinien einer Diagrammachse an. |
| [getShowMinorGridLines()](#getShowMinorGridLines--) | Um Nebenrasterlinien zu verbergen, setze MinorGridLinesFormat.Line.FillFormat.FillType auf FillType.NoFill. |
| [getShowMajorGridLines()](#getShowMajorGridLines--) | Um Hauptrasterlinien zu verbergen, setze MajorGridLinesFormat.Line.FillFormat.FillType auf FillType.NoFill. |
| [getFormat()](#getFormat--) | Gibt das Format der Achse an. |
| [getTextFormat()](#getTextFormat--) | Gibt das Textformat an. |
| [getTitle()](#getTitle--) | Liefert den Titel der Achse. |
| [getCrossType()](#getCrossType--) | Gibt den Kreuzungstyp auf der angegebenen Achse an, an dem die andere Achse sie schneidet. |
| [setCrossType(int value)](#setCrossType-int-) | Gibt den Kreuzungstyp auf der angegebenen Achse an, an dem die andere Achse sie schneidet. |
| [getPosition()](#getPosition--) | Gibt die Position der Achse an. |
| [setPosition(int value)](#setPosition-int-) | Gibt die Position der Achse an. |
| [hasTitle()](#hasTitle--) | Bestimmt, ob eine Achse einen sichtbaren Titel hat. |
| [setTitle(boolean value)](#setTitle-boolean-) | Bestimmt, ob eine Achse einen sichtbaren Titel hat. |
| [getNumberFormat()](#getNumberFormat--) | Gibt die Formatzeichenfolge für die Achsenbeschriftungen an. |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | Gibt die Formatzeichenfolge für die Achsenbeschriftungen an. |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | Gibt an, ob das Format mit Quelldaten verknüpft ist. |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | Gibt an, ob das Format mit Quelldaten verknüpft ist. |
| [getTickLabelRotationAngle()](#getTickLabelRotationAngle--) | Gibt den Rotationswinkel der Tick-Beschriftungen an. |
| [setTickLabelRotationAngle(float value)](#setTickLabelRotationAngle-float-) | Gibt den Rotationswinkel der Tick-Beschriftungen an. |
| [getTickLabelSpacing()](#getTickLabelSpacing--) | Gibt an, wie viele Tick-Beschriftungen zwischen den angezeigten Labels übersprungen werden. |
| [setTickLabelSpacing(long value)](#setTickLabelSpacing-long-) | Gibt an, wie viele Tick-Beschriftungen zwischen den angezeigten Labels übersprungen werden. |
| [isAutomaticTickLabelSpacing()](#isAutomaticTickLabelSpacing--) | Gibt den automatischen Abstandswert für Tick-Labels an. |
| [setAutomaticTickLabelSpacing(boolean value)](#setAutomaticTickLabelSpacing-boolean-) | Gibt den automatischen Abstandswert für Tick-Labels an. |
| [getTickMarksSpacing()](#getTickMarksSpacing--) | Gibt an, wie viele Tick-Marken übersprungen werden, bevor die nächste gezeichnet wird. |
| [setTickMarksSpacing(long value)](#setTickMarksSpacing-long-) | Gibt an, wie viele Tick-Marken übersprungen werden, bevor die nächste gezeichnet wird. |
| [isAutomaticTickMarksSpacing()](#isAutomaticTickMarksSpacing--) | Gibt den automatischen Abstandswert für Tick-Marken an. |
| [setAutomaticTickMarksSpacing(boolean value)](#setAutomaticTickMarksSpacing-boolean-) | Gibt den automatischen Abstandswert für Tick-Marken an. |
| [getLabelOffset()](#getLabelOffset--) | Gibt den Abstand der Labels von der Achse an. |
| [setLabelOffset(int value)](#setLabelOffset-int-) | Gibt den Abstand der Labels von der Achse an. |
| [getAggregationType()](#getAggregationType--) | Gibt den Aggregationstyp der Kategorieachse (Binning) an. |
| [setAggregationType(int value)](#setAggregationType-int-) | Gibt den Aggregationstyp der Kategorieachse (Binning) an. |
| [getBinWidth()](#getBinWidth--) | Gibt die Bin-Breite an, wenn der AggregationType-Eigenschaftswert auf AxisAggregationType.ByBinWidth gesetzt ist. |
| [setBinWidth(double value)](#setBinWidth-double-) | Gibt die Bin-Breite an, wenn der AggregationType-Eigenschaftswert auf AxisAggregationType.ByBinWidth gesetzt ist. |
| [getNumberOfBins()](#getNumberOfBins--) | Gibt die Anzahl der Bins an, wenn der AggregationType-Eigenschaftswert auf AxisAggregationType.ByNumberOfBins gesetzt ist. |
| [setNumberOfBins(long value)](#setNumberOfBins-long-) | Gibt die Anzahl der Bins an, wenn der AggregationType-Eigenschaftswert auf AxisAggregationType.ByNumberOfBins gesetzt ist. |
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
| [getSlide()](#getSlide--) | Gibt die übergeordnete Folie eines FillFormat zurück. |
| [getPresentation()](#getPresentation--) | Gibt die übergeordnete Präsentation eines FillFormat zurück. |

### getChart() {#getChart--}
```
public final IChart getChart()
```

Gibt das übergeordnete Diagramm zurück. Nur-Lesen [IChart](../../com.aspose.slides/ichart).

**Rückgabewert:**
[IChart](../../com.aspose.slides/ichart)

### getAxisBetweenCategories() {#getAxisBetweenCategories--}
```
public final boolean getAxisBetweenCategories()
```

Gibt an, ob die Werteachse die Kategorieachse zwischen Kategorien schneidet. Diese Eigenschaft gilt nur für Kategorieachsen und nicht für 3-D-Diagramme. Lesen/Schreiben boolean.

**Rückgabewert:**
boolean

### setAxisBetweenCategories(boolean value) {#setAxisBetweenCategories-boolean-}
```
public final void setAxisBetweenCategories(boolean value)
```

Gibt an, ob die Werteachse die Kategorieachse zwischen Kategorien schneidet. Diese Eigenschaft gilt nur für Kategorieachsen und nicht für 3-D-Diagramme. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getCategoryAxisType() {#getCategoryAxisType--}
```
public final int getCategoryAxisType()
```

Gibt den Typ der Kategorieachse an. Lesen/Schreiben [CategoryAxisType](../../com.aspose.slides/categoryaxistype).

**Rückgabewert:**
int

### setCategoryAxisType(int value) {#setCategoryAxisType-int-}
```
public final void setCategoryAxisType(int value)
```

Gibt den Typ der Kategorieachse an. Lesen/Schreiben [CategoryAxisType](../../com.aspose.slides/categoryaxistype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### setCategoryAxisTypeAutomatically() {#setCategoryAxisTypeAutomatically--}
```
public final void setCategoryAxisTypeAutomatically()
```

Setzt die IAxis.CategoryAxisType Eigenschaft mit einem Wert, der basierend auf den Achsendaten automatisch bestimmt wird.

### getCrossAt() {#getCrossAt--}
```
public final float getCrossAt()
```

Gibt den Punkt auf der Achse an, an dem die senkrechte Achse sie schneidet. Lesen/Schreiben float.

**Rückgabewert:**
float

### setCrossAt(float value) {#setCrossAt-float-}
```
public final void setCrossAt(float value)
```

Gibt den Punkt auf der Achse an, an dem die senkrechte Achse sie schneidet. Lesen/Schreiben float.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |

### getDisplayUnit() {#getDisplayUnit--}
```
public final int getDisplayUnit()
```

Gibt den Skalierungswert der Anzeigeeinheiten für die Werteachse an. Lesen/Schreiben [DisplayUnitType](../../com.aspose.slides/displayunittype).

**Rückgabewert:**
int

### setDisplayUnit(int value) {#setDisplayUnit-int-}
```
public final void setDisplayUnit(int value)
```

Gibt den Skalierungswert der Anzeigeeinheiten für die Werteachse an. Lesen/Schreiben [DisplayUnitType](../../com.aspose.slides/displayunittype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getActualMaxValue() {#getActualMaxValue--}
```
public final double getActualMaxValue()
```

Gibt den tatsächlichen Maximalwert auf der Achse an. Rufen Sie zuvor die Methode IChart.ValidateChartLayout() auf, um den tatsächlichen Wert zu erhalten.

**Rückgabewert:**
double

### getActualMinValue() {#getActualMinValue--}
```
public final double getActualMinValue()
```

Gibt den tatsächlichen Minimalwert auf der Achse an. Rufen Sie zuvor die Methode IChart.ValidateChartLayout() auf, um den tatsächlichen Wert zu erhalten.

**Rückgabewert:**
double

### getActualMajorUnit() {#getActualMajorUnit--}
```
public final double getActualMajorUnit()
```

Gibt die tatsächliche Haupteinheit der Achse an. Rufen Sie zuvor die Methode IChart.ValidateChartLayout() auf, um den tatsächlichen Wert zu erhalten.

**Rückgabewert:**
double

### getActualMinorUnit() {#getActualMinorUnit--}
```
public final double getActualMinorUnit()
```

Gibt die tatsächliche Nebenheit der Achse an. Rufen Sie zuvor die Methode IChart.ValidateChartLayout() auf, um den tatsächlichen Wert zu erhalten.

**Rückgabewert:**
double

### getActualMajorUnitScale() {#getActualMajorUnitScale--}
```
public final int getActualMajorUnitScale()
```

Gibt die tatsächliche Skalierung der Haupteinheit der Achse an. Rufen Sie zuvor die Methode IChart.ValidateChartLayout() auf, um den tatsächlichen Wert zu erhalten.

**Rückgabewert:**
int

### getActualMinorUnitScale() {#getActualMinorUnitScale--}
```
public final int getActualMinorUnitScale()
```

Gibt die tatsächliche Skalierung der Nebenheit der Achse an. Rufen Sie zuvor die Methode IChart.ValidateChartLayout() auf, um den tatsächlichen Wert zu erhalten.

**Rückgabewert:**
int

### isAutomaticMaxValue() {#isAutomaticMaxValue--}
```
public final boolean isAutomaticMaxValue()
```

Gibt an, ob der Maximalwert automatisch zugewiesen wird. Lesen/Schreiben boolean.

**Rückgabewert:**
boolean

### setAutomaticMaxValue(boolean value) {#setAutomaticMaxValue-boolean-}
```
public final void setAutomaticMaxValue(boolean value)
```

Gibt an, ob der Maximalwert automatisch zugewiesen wird. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getMaxValue() {#getMaxValue--}
```
public final double getMaxValue()
```

Gibt den Maximalwert auf der Werteachse an. Lesen/Schreiben double.

**Rückgabewert:**
double

### setMaxValue(double value) {#setMaxValue-double-}
```
public final void setMaxValue(double value)
```

Gibt den Maximalwert auf der Werteachse an. Lesen/Schreiben double.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |

### getMinorUnit() {#getMinorUnit--}
```
public final double getMinorUnit()
```

Gibt die Nebenheiten für die Datums- oder Werteachse an. Lesen/Schreiben double.

**Rückgabewert:**
double

### setMinorUnit(double value) {#setMinorUnit-double-}
```
public final void setMinorUnit(double value)
```

Gibt die Nebenheiten für die Datums- oder Werteachse an. Lesen/Schreiben double.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |

### isAutomaticMinorUnit() {#isAutomaticMinorUnit--}
```
public final boolean isAutomaticMinorUnit()
```
Indicates whether the minor unit of the axis is automatically assigned. Lesen/Schreiben boolean.

**Rückgabe:**
boolean
### setAutomaticMinorUnit(boolean value) {#setAutomaticMinorUnit-boolean-}
```
public final void setAutomaticMinorUnit(boolean value)
```


Indicates whether the minor unit of the axis is automatically assigned. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getMajorUnit() {#getMajorUnit--}
```
public final double getMajorUnit()
```


Represents the major units for the date or value axis. Lesen/Schreiben double.

**Rückgabe:**
double
### setMajorUnit(double value) {#setMajorUnit-double-}
```
public final void setMajorUnit(double value)
```


Represents the major units for the date or value axis. Lesen/Schreiben double.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |

### isAutomaticMajorUnit() {#isAutomaticMajorUnit--}
```
public final boolean isAutomaticMajorUnit()
```


Indicates whether the major unit of the axis is automatically assigned. Lesen/Schreiben boolean.

**Rückgabe:**
boolean
### setAutomaticMajorUnit(boolean value) {#setAutomaticMajorUnit-boolean-}
```
public final void setAutomaticMajorUnit(boolean value)
```


Indicates whether the major unit of the axis is automatically assigned. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticMinValue() {#isAutomaticMinValue--}
```
public final boolean isAutomaticMinValue()
```


Indicates whether the min value is automatically assigned. Lesen/Schreiben boolean.

**Rückgabe:**
boolean
### setAutomaticMinValue(boolean value) {#setAutomaticMinValue-boolean-}
```
public final void setAutomaticMinValue(boolean value)
```


Indicates whether the min value is automatically assigned. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getMinValue() {#getMinValue--}
```
public final double getMinValue()
```


Represents the minimum value on the value axis. Lesen/Schreiben double.

**Rückgabe:**
double
### setMinValue(double value) {#setMinValue-double-}
```
public final void setMinValue(double value)
```


Represents the minimum value on the value axis. Lesen/Schreiben double.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |

### isLogarithmic() {#isLogarithmic--}
```
public final boolean isLogarithmic()
```


Represents if the value axis scale type is logarithmic or not. Lesen/Schreiben boolean.

**Rückgabe:**
boolean
### setLogarithmic(boolean value) {#setLogarithmic-boolean-}
```
public final void setLogarithmic(boolean value)
```


Represents if the value axis scale type is logarithmic or not. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getLogBase() {#getLogBase--}
```
public final double getLogBase()
```


Represents the logarithmic base. Default value is 10. Lesen/Schreiben double.

**Rückgabe:**
double
### setLogBase(double value) {#setLogBase-double-}
```
public final void setLogBase(double value)
```


Represents the logarithmic base. Default value is 10. Lesen/Schreiben double.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |

### isPlotOrderReversed() {#isPlotOrderReversed--}
```
public final boolean isPlotOrderReversed()
```


Represents if MS PowerPoint plots data points from last to first. Lesen/Schreiben boolean.

**Rückgabe:**
boolean
### setPlotOrderReversed(boolean value) {#setPlotOrderReversed-boolean-}
```
public final void setPlotOrderReversed(boolean value)
```


Represents if MS PowerPoint plots data points from last to first. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### isVisible() {#isVisible--}
```
public final boolean isVisible()
```


Represents if the axis is visible. Lesen/Schreiben boolean.

**Rückgabe:**
boolean
### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```


Represents if the axis is visible. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getMajorTickMark() {#getMajorTickMark--}
```
public final int getMajorTickMark()
```


Represents the type of major tick mark for the specified axis. Lesen/Schreiben [TickMarkType](../../com.aspose.slides/tickmarktype).

**Rückgabe:**
int
### setMajorTickMark(int value) {#setMajorTickMark-int-}
```
public final void setMajorTickMark(int value)
```


Represents the type of major tick mark for the specified axis. Lesen/Schreiben [TickMarkType](../../com.aspose.slides/tickmarktype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getMinorTickMark() {#getMinorTickMark--}
```
public final int getMinorTickMark()
```


Represents the type of minor tick mark for the specified axis. Lesen/Schreiben [TickMarkType](../../com.aspose.slides/tickmarktype).

**Rückgabe:**
int
### setMinorTickMark(int value) {#setMinorTickMark-int-}
```
public final void setMinorTickMark(int value)
```


Represents the type of minor tick mark for the specified axis. Lesen/Schreiben [TickMarkType](../../com.aspose.slides/tickmarktype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getTickLabelPosition() {#getTickLabelPosition--}
```
public final int getTickLabelPosition()
```


Represents the position of tick-mark labels on the specified axis. Lesen/Schreiben [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**Rückgabe:**
int
### setTickLabelPosition(int value) {#setTickLabelPosition-int-}
```
public final void setTickLabelPosition(int value)
```


Represents the position of tick-mark labels on the specified axis. Lesen/Schreiben [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getMajorUnitScale() {#getMajorUnitScale--}
```
public final int getMajorUnitScale()
```


Represents the major unit scale for the date axis. Lesen/Schreiben [TimeUnitType](../../com.aspose.slides/timeunittype).

**Rückgabe:**
int
### setMajorUnitScale(int value) {#setMajorUnitScale-int-}
```
public final void setMajorUnitScale(int value)
```


Represents the major unit scale for the date axis. Lesen/Schreiben [TimeUnitType](../../com.aspose.slides/timeunittype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getMinorUnitScale() {#getMinorUnitScale--}
```
public final int getMinorUnitScale()
```


Represents the major unit scale for the date axis. Lesen/Schreiben [TimeUnitType](../../com.aspose.slides/timeunittype).

**Rückgabe:**
int
### setMinorUnitScale(int value) {#setMinorUnitScale-int-}
```
public final void setMinorUnitScale(int value)
```


Represents the major unit scale for the date axis. Lesen/Schreiben [TimeUnitType](../../com.aspose.slides/timeunittype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getBaseUnitScale() {#getBaseUnitScale--}
```
public final int getBaseUnitScale()
```


Specifies the smallest time unit that is represented on the date axis. Lesen/Schreiben [TimeUnitType](../../com.aspose.slides/timeunittype).

**Rückgabe:**
int
### setBaseUnitScale(int value) {#setBaseUnitScale-int-}
```
public final void setBaseUnitScale(int value)
```


Specifies the smallest time unit that is represented on the date axis. Lesen/Schreiben [TimeUnitType](../../com.aspose.slides/timeunittype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getMinorGridLinesFormat() {#getMinorGridLinesFormat--}
```
public final IChartLinesFormat getMinorGridLinesFormat()
```


Represents minor gridlines format on a chart axis. Nur-Lesen [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**Rückgabe:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### getMajorGridLinesFormat() {#getMajorGridLinesFormat--}
```
public final IChartLinesFormat getMajorGridLinesFormat()
```


Represents major gridlines format on a chart axis. Nur-Lesen [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**Rückgabe:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### getShowMinorGridLines() {#getShowMinorGridLines--}
```
public final boolean getShowMinorGridLines()
```


To hide minor gridline set MinorGridLinesFormat.Line.FillFormat.FillType to FillType.NoFill. Nur-Lesen boolean.

**Rückgabe:**
boolean
### getShowMajorGridLines() {#getShowMajorGridLines--}
```
public final boolean getShowMajorGridLines()
```


To hide major gridline set MajorGridLinesFormat.Line.FillFormat.FillType to FillType.NoFill. Nur-Lesen boolean.

**Rückgabe:**
boolean
### getFormat() {#getFormat--}
```
public final IAxisFormat getFormat()
```


Represents format of axis. Nur-Lesen [IAxisFormat](../../com.aspose.slides/iaxisformat).

**Rückgabe:**
[IAxisFormat](../../com.aspose.slides/iaxisformat)
### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```


Represents format of text. Nur-Lesen [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Rückgabe:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)
### getTitle() {#getTitle--}
```
public final IChartTitle getTitle()
```


Gets the axis' title. Nur-Lesen [IChartTitle](../../com.aspose.slides/icharttitle).

**Rückgabe:**
[IChartTitle](../../com.aspose.slides/icharttitle)
### getCrossType() {#getCrossType--}
```
public final int getCrossType()
```


Represents the CrossType on the specified axis where the other axis crosses. Lesen/Schreiben [CrossesType](../../com.aspose.slides/crossestype).

**Rückgabe:**
int
### setCrossType(int value) {#setCrossType-int-}
```
public final void setCrossType(int value)
```


Represents the CrossType on the specified axis where the other axis crosses. Lesen/Schreiben [CrossesType](../../com.aspose.slides/crossestype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getPosition() {#getPosition--}
```
public final int getPosition()
```


Represents position of axis. Lesen/Schreiben [AxisPositionType](../../com.aspose.slides/axispositiontype).

**Rückgabe:**
int
### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```


Represents position of axis. Lesen/Schreiben [AxisPositionType](../../com.aspose.slides/axispositiontype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### hasTitle() {#hasTitle--}
```
public final boolean hasTitle()
```


Determines whether a axis has a visible title. Lesen/Schreiben boolean.

**Rückgabe:**
boolean
### setTitle(boolean value) {#setTitle-boolean-}
```
public final void setTitle(boolean value)
```


Determines whether a axis has a visible title. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public final String getNumberFormat()
```


Represents the format string for the Axis Labels. Lesen/Schreiben String.

**Rückgabe:**
java.lang.String
### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public final void setNumberFormat(String value)
```


Represents the format string for the Axis Labels. Lesen/Schreiben String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public final boolean isNumberFormatLinkedToSource()
```


Indicates whether the format is linked source data. Lesen/Schreiben boolean.

**Rückgabe:**
boolean
### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public final void setNumberFormatLinkedToSource(boolean value)
```


Indicates whether the format is linked source data. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getTickLabelRotationAngle() {#getTickLabelRotationAngle--}
```
public final float getTickLabelRotationAngle()
```


Represents the rotation angle of tick labels. Lesen/Schreiben float.

**Rückgabe:**
float
### setTickLabelRotationAngle(float value) {#setTickLabelRotationAngle-float-}
```
public final void setTickLabelRotationAngle(float value)
```


Represents the rotation angle of tick labels. Lesen/Schreiben float.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |

### getTickLabelSpacing() {#getTickLabelSpacing--}
```
public final long getTickLabelSpacing()
```


Specifies how many tick labels to skip between label that is drawn. Applied to category or series axis. Lesen/Schreiben long.

**Rückgabe:**
long
### setTickLabelSpacing(long value) {#setTickLabelSpacing-long-}
```
public final void setTickLabelSpacing(long value)
```


Specifies how many tick labels to skip between label that is drawn. Applied to category or series axis. Lesen/Schreiben long.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickLabelSpacing() {#isAutomaticTickLabelSpacing--}
```
public final boolean isAutomaticTickLabelSpacing()
```


Specifies automatic tick label spacing value. If false: use TickLabelSpacing property. Lesen/Schreiben boolean.

**Rückgabe:**
boolean
### setAutomaticTickLabelSpacing(boolean value) {#setAutomaticTickLabelSpacing-boolean-}
```
public final void setAutomaticTickLabelSpacing(boolean value)
```


Specifies automatic tick label spacing value. If false: use TickLabelSpacing property. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getTickMarksSpacing() {#getTickMarksSpacing--}
```
public final long getTickMarksSpacing()
```


Specifies how many tick marks shall be skipped before the next one shall be drawn. Applied to category or series axis. Lesen/Schreiben int.

**Rückgabe:**
long
### setTickMarksSpacing(long value) {#setTickMarksSpacing-long-}
```
public final void setTickMarksSpacing(long value)
```


Specifies how many tick marks shall be skipped before the next one shall be drawn. Applied to category or series axis. Lesen/Schreiben int.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickMarksSpacing() {#isAutomaticTickMarksSpacing--}
```
public final boolean isAutomaticTickMarksSpacing()
```


Specifies automatic tick marks spacing value. If false: use TickMarksSpacing property. Lesen/Schreiben boolean.

**Rückgabe:**
boolean
### setAutomaticTickMarksSpacing(boolean value) {#setAutomaticTickMarksSpacing-boolean-}
```
public final void setAutomaticTickMarksSpacing(boolean value)
```


Specifies automatic tick marks spacing value. If false: use TickMarksSpacing property. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getLabelOffset() {#getLabelOffset--}
```
public final int getLabelOffset()
```


Specifies the distance of labels from the axis. Applied to category or date axis. Value must be between 0% and 1000%. Lesen/Schreiben int.

**Rückgabe:**
int
### setLabelOffset(int value) {#setLabelOffset-int-}
```
public final void setLabelOffset(int value)
```


Specifies the distance of labels from the axis. Applied to category or date axis. Value must be between 0% and 1000%. Lesen/Schreiben int.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### getAggregationType() {#getAggregationType--}
```
public final int getAggregationType()
```

Stellt den Aggregationstyp der Kategorienachse (Binning) dar. Auf die Kategorie angewendet. Wird nur mit Histogramm- oder HistogrammPareto-Serien verwendet.

**Rückgabe:**
int
### setAggregationType(int value) {#setAggregationType-int-}
```
public final void setAggregationType(int value)
```

Stellt den Aggregationstyp der Kategorienachse (Binning) dar. Auf die Kategorie angewendet. Wird nur mit Histogramm- oder HistogrammPareto-Serien verwendet.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getBinWidth() {#getBinWidth--}
```
public final double getBinWidth()
```

Gibt die Bin-Breite an, wenn der Wert der Eigenschaft AggregationType auf AxisAggregationType.ByBinWidth gesetzt ist. Auf Kategorienachsen angewendet. Wird nur mit Histogramm- oder HistogrammPareto-Serien verwendet.

**Rückgabe:**
double
### setBinWidth(double value) {#setBinWidth-double-}
```
public final void setBinWidth(double value)
```

Gibt die Bin-Breite an, wenn der Wert der Eigenschaft AggregationType auf AxisAggregationType.ByBinWidth gesetzt ist. Auf Kategorienachsen angewendet. Wird nur mit Histogramm- oder HistogrammPareto-Serien verwendet.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |

### getNumberOfBins() {#getNumberOfBins--}
```
public final long getNumberOfBins()
```

Gibt die Anzahl der Bins an, wenn der Wert der Eigenschaft AggregationType auf AxisAggregationType.ByNumberOfBins gesetzt ist. Auf Kategorienachsen angewendet. Wird nur mit Histogramm- oder HistogrammPareto-Serien verwendet.

**Rückgabe:**
long
### setNumberOfBins(long value) {#setNumberOfBins-long-}
```
public final void setNumberOfBins(long value)
```

Gibt die Anzahl der Bins an, wenn der Wert der Eigenschaft AggregationType auf AxisAggregationType.ByNumberOfBins gesetzt ist. Auf Kategorienachsen angewendet. Wird nur mit Histogramm- oder HistogrammPareto-Serien verwendet.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | long |  |

### isOverflowBin() {#isOverflowBin--}
```
public final boolean isOverflowBin()
```

Gibt an, ob ein Überlauf-Bin angewendet wird. Verwenden Sie IsAutomaticOverflowBin und OverflowBin, um den Wert des Überlauf-Bins anzupassen.

**Rückgabe:**
boolean
### setOverflowBin(boolean value) {#setOverflowBin-boolean-}
```
public final void setOverflowBin(boolean value)
```

Gibt an, ob ein Überlauf-Bin angewendet wird. Verwenden Sie IsAutomaticOverflowBin und OverflowBin, um den Wert des Überlauf-Bins anzupassen.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticOverflowBin() {#isAutomaticOverflowBin--}
```
public final boolean isAutomaticOverflowBin()
```

Gibt den automatischen Wert des Überlauf-Bins an. Wenn false: Verwenden Sie die Eigenschaft OverflowBin.

**Rückgabe:**
boolean
### setAutomaticOverflowBin(boolean value) {#setAutomaticOverflowBin-boolean-}
```
public final void setAutomaticOverflowBin(boolean value)
```

Gibt den automatischen Wert des Überlauf-Bins an. Wenn false: Verwenden Sie die Eigenschaft OverflowBin.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getOverflowBin() {#getOverflowBin--}
```
public final double getOverflowBin()
```

Gibt den benutzerdefinierten Wert des Überlauf-Bins an. Wird angewendet, wenn die Eigenschaft IsAutomaticOverflowBin auf false gesetzt ist und die Eigenschaft IsOverflowBin true ist.

**Rückgabe:**
double
### setOverflowBin(double value) {#setOverflowBin-double-}
```
public final void setOverflowBin(double value)
```

Gibt den benutzerdefinierten Wert des Überlauf-Bins an. Wird angewendet, wenn die Eigenschaft IsAutomaticOverflowBin auf false gesetzt ist und die Eigenschaft IsOverflowBin true ist.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |

### isUnderflowBin() {#isUnderflowBin--}
```
public final boolean isUnderflowBin()
```

Gibt an, ob ein Unterlauf-Bin angewendet wird. Verwenden Sie IsAutomaticUnderflowBin und UnderflowBin, um den Wert des Unterlauf-Bins anzupassen.

**Rückgabe:**
boolean
### setUnderflowBin(boolean value) {#setUnderflowBin-boolean-}
```
public final void setUnderflowBin(boolean value)
```

Gibt an, ob ein Unterlauf-Bin angewendet wird. Verwenden Sie IsAutomaticUnderflowBin und UnderflowBin, um den Wert des Unterlauf-Bins anzupassen.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticUnderflowBin() {#isAutomaticUnderflowBin--}
```
public final boolean isAutomaticUnderflowBin()
```

Gibt den automatischen Wert des Unterlauf-Bins an. Wenn false: Verwenden Sie die Eigenschaft UnderflowBin.

**Rückgabe:**
boolean
### setAutomaticUnderflowBin(boolean value) {#setAutomaticUnderflowBin-boolean-}
```
public final void setAutomaticUnderflowBin(boolean value)
```

Gibt den automatischen Wert des Unterlauf-Bins an. Wenn false: Verwenden Sie die Eigenschaft UnderflowBin.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getUnderflowBin() {#getUnderflowBin--}
```
public final double getUnderflowBin()
```

Gibt den benutzerdefinierten Wert des Unterlauf-Bins an. Wird angewendet, wenn die Eigenschaft IsAutomaticUnderflowBin auf false gesetzt ist und die Eigenschaft IsUnderflowBin true ist.

**Rückgabe:**
double
### setUnderflowBin(double value) {#setUnderflowBin-double-}
```
public final void setUnderflowBin(double value)
```

Gibt den benutzerdefinierten Wert des Unterlauf-Bins an. Wird angewendet, wenn die Eigenschaft IsAutomaticUnderflowBin auf false gesetzt ist und die Eigenschaft IsUnderflowBin true ist.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Gibt die übergeordnete Folie eines FillFormat zurück. Nur lesbar [BaseSlide](../../com.aspose.slides/baseslide).

**Rückgabe:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Gibt die übergeordnete Präsentation eines FillFormat zurück. Nur lesbar [IPresentation](../../com.aspose.slides/ipresentation).

**Rückgabe:**
[IPresentation](../../com.aspose.slides/ipresentation)