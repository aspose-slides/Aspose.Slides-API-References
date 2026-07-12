---
title: Axis
second_title: Aspose.Slides für Android über Java API-Referenz
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

Kapselt das Objekt, das eine Diagrammachse darstellt.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getChart()](#getChart--) | Gibt das übergeordnete Diagramm zurück. |
| [getAxisBetweenCategories()](#getAxisBetweenCategories--) | Stellt dar, ob die Werteachse die Kategorienachse zwischen den Kategorien schneidet. |
| [setAxisBetweenCategories(boolean value)](#setAxisBetweenCategories-boolean-) | Stellt dar, ob die Werteachse die Kategorienachse zwischen den Kategorien schneidet. |
| [getCategoryAxisType()](#getCategoryAxisType--) | Gibt den Typ der Kategorienachse an. |
| [setCategoryAxisType(int value)](#setCategoryAxisType-int-) | Gibt den Typ der Kategorienachse an. |
| [setCategoryAxisTypeAutomatically()](#setCategoryAxisTypeAutomatically--) | Setzt die Eigenschaft IAxis.CategoryAxisType auf einen automatisch anhand der Achsendaten ermittelten Wert. |
| [getCrossAt()](#getCrossAt--) | Stellt den Punkt auf der Achse dar, an dem die senkrechte Achse sie kreuzt. |
| [setCrossAt(float value)](#setCrossAt-float-) | Stellt den Punkt auf der Achse dar, an dem die senkrechte Achse sie kreuzt. |
| [getDisplayUnit()](#getDisplayUnit--) | Gibt den Skalierungswert der Anzeigeeinheiten für die Werteachse an. |
| [setDisplayUnit(int value)](#setDisplayUnit-int-) | Gibt den Skalierungswert der Anzeigeeinheiten für die Werteachse an. |
| [getActualMaxValue()](#getActualMaxValue--) | Gibt den tatsächlichen Maximalwert auf der Achse an. |
| [getActualMinValue()](#getActualMinValue--) | Gibt den tatsächlichen Minimalwert auf der Achse an. |
| [getActualMajorUnit()](#getActualMajorUnit--) | Gibt die tatsächliche Haupteinheit der Achse an. |
| [getActualMinorUnit()](#getActualMinorUnit--) | Gibt die tatsächliche Nebeneinheit der Achse an. |
| [getActualMajorUnitScale()](#getActualMajorUnitScale--) | Gibt die tatsächliche Skalierung der Haupteinheit der Achse an. |
| [getActualMinorUnitScale()](#getActualMinorUnitScale--) | Gibt die tatsächliche Skalierung der Nebeneinheit der Achse an. |
| [isAutomaticMaxValue()](#isAutomaticMaxValue--) | Zeigt an, ob der Maximalwert automatisch zugewiesen wird. |
| [setAutomaticMaxValue(boolean value)](#setAutomaticMaxValue-boolean-) | Zeigt an, ob der Maximalwert automatisch zugewiesen wird. |
| [getMaxValue()](#getMaxValue--) | Stellt den Maximalwert auf der Werteachse dar. |
| [setMaxValue(double value)](#setMaxValue-double-) | Stellt den Maximalwert auf der Werteachse dar. |
| [getMinorUnit()](#getMinorUnit--) | Stellt die Nebeneinheiten für die Datums- oder Werteachse dar. |
| [setMinorUnit(double value)](#setMinorUnit-double-) | Stellt die Nebeneinheiten für die Datums- oder Werteachse dar. |
| [isAutomaticMinorUnit()](#isAutomaticMinorUnit--) | Zeigt an, ob die Nebeneinheit der Achse automatisch zugewiesen wird. |
| [setAutomaticMinorUnit(boolean value)](#setAutomaticMinorUnit-boolean-) | Zeigt an, ob die Nebeneinheit der Achse automatisch zugewiesen wird. |
| [getMajorUnit()](#getMajorUnit--) | Stellt die Haupteinheiten für die Datums- oder Werteachse dar. |
| [setMajorUnit(double value)](#setMajorUnit-double-) | Stellt die Haupteinheiten für die Datums- oder Werteachse dar. |
| [isAutomaticMajorUnit()](#isAutomaticMajorUnit--) | Zeigt an, ob die Haupteinheit der Achse automatisch zugewiesen wird. |
| [setAutomaticMajorUnit(boolean value)](#setAutomaticMajorUnit-boolean-) | Zeigt an, ob die Haupteinheit der Achse automatisch zugewiesen wird. |
| [isAutomaticMinValue()](#isAutomaticMinValue--) | Zeigt an, ob der Minimalwert automatisch zugewiesen wird. |
| [setAutomaticMinValue(boolean value)](#setAutomaticMinValue-boolean-) | Zeigt an, ob der Minimalwert automatisch zugewiesen wird. |
| [getMinValue()](#getMinValue--) | Stellt den Minimalwert auf der Werteachse dar. |
| [setMinValue(double value)](#setMinValue-double-) | Stellt den Minimalwert auf der Werteachse dar. |
| [isLogarithmic()](#isLogarithmic--) | Stellt dar, ob der Skalierungstyp der Werteachse logarithmisch ist oder nicht. |
| [setLogarithmic(boolean value)](#setLogarithmic-boolean-) | Stellt dar, ob der Skalierungstyp der Werteachse logarithmisch ist oder nicht. |
| [getLogBase()](#getLogBase--) | Stellt die logarithmische Basis dar. |
| [setLogBase(double value)](#setLogBase-double-) | Stellt die logarithmische Basis dar. |
| [isPlotOrderReversed()](#isPlotOrderReversed--) | Stellt dar, ob MS PowerPoint Datenpunkte von zuletzt nach zuerst darstellt. |
| [setPlotOrderReversed(boolean value)](#setPlotOrderReversed-boolean-) | Stellt dar, ob MS PowerPoint Datenpunkte von zuletzt nach zuerst darstellt. |
| [isVisible()](#isVisible--) | Stellt dar, ob die Achse sichtbar ist. |
| [setVisible(boolean value)](#setVisible-boolean-) | Stellt dar, ob die Achse sichtbar ist. |
| [getMajorTickMark()](#getMajorTickMark--) | Stellt den Typ der Haupt-Markierung für die angegebene Achse dar. |
| [setMajorTickMark(int value)](#setMajorTickMark-int-) | Stellt den Typ der Haupt-Markierung für die angegebene Achse dar. |
| [getMinorTickMark()](#getMinorTickMark--) | Stellt den Typ der Neben-Markierung für die angegebene Achse dar. |
| [setMinorTickMark(int value)](#setMinorTickMark-int-) | Stellt den Typ der Neben-Markierung für die angegebene Achse dar. |
| [getTickLabelPosition()](#getTickLabelPosition--) | Stellt die Position der Beschriftungen der Markierungen auf der angegebenen Achse dar. |
| [setTickLabelPosition(int value)](#setTickLabelPosition-int-) | Stellt die Position der Beschriftungen der Markierungen auf der angegebenen Achse dar. |
| [getMajorUnitScale()](#getMajorUnitScale--) | Stellt die Skalierung der Haupteinheit für die Datumsachse dar. |
| [setMajorUnitScale(int value)](#setMajorUnitScale-int-) | Stellt die Skalierung der Haupteinheit für die Datumsachse dar. |
| [getMinorUnitScale()](#getMinorUnitScale--) | Stellt die Skalierung der Haupteinheit für die Datumsachse dar. |
| [setMinorUnitScale(int value)](#setMinorUnitScale-int-) | Stellt die Skalierung der Haupteinheit für die Datumsachse dar. |
| [getBaseUnitScale()](#getBaseUnitScale--) | Gibt die kleinste Zeiteinheit an, die auf der Datumsachse dargestellt wird. |
| [setBaseUnitScale(int value)](#setBaseUnitScale-int-) | Gibt die kleinste Zeiteinheit an, die auf der Datumsachse dargestellt wird. |
| [getMinorGridLinesFormat()](#getMinorGridLinesFormat--) | Stellt das Format der Hilfsgitterlinien auf einer Diagrammachse dar. |
| [getMajorGridLinesFormat()](#getMajorGridLinesFormat--) | Stellt das Format der Hauptgitterlinien auf einer Diagrammachse dar. |
| [getShowMinorGridLines()](#getShowMinorGridLines--) | Um die Hilfsgitterlinie auszublenden, setzen Sie MinorGridLinesFormat.Line.FillFormat.FillType auf FillType.NoFill. |
| [getShowMajorGridLines()](#getShowMajorGridLines--) | Um die Hauptgitterlinie auszublenden, setzen Sie MajorGridLinesFormat.Line.FillFormat.FillType auf FillType.NoFill. |
| [getFormat()](#getFormat--) | Stellt das Format der Achse dar. |
| [getTextFormat()](#getTextFormat--) | Stellt das Textformat dar. |
| [getTitle()](#getTitle--) | Ruft den Titel der Achse ab. |
| [getCrossType()](#getCrossType--) | Stellt den CrossType auf der angegebenen Achse dar, an dem die andere Achse sie schneidet. |
| [setCrossType(int value)](#setCrossType-int-) | Stellt den CrossType auf der angegebenen Achse dar, an dem die andere Achse sie schneidet. |
| [getPosition()](#getPosition--) | Stellt die Position der Achse dar. |
| [setPosition(int value)](#setPosition-int-) | Stellt die Position der Achse dar. |
| [hasTitle()](#hasTitle--) | Bestimmt, ob eine Achse einen sichtbaren Titel hat. |
| [setTitle(boolean value)](#setTitle-boolean-) | Bestimmt, ob eine Achse einen sichtbaren Titel hat. |
| [getNumberFormat()](#getNumberFormat--) | Stellt die Formatzeichenfolge für die Achsenbeschriftungen dar. |
| [setNumberFormat(String value)](#setNumberFormat-java.lang.String-) | Stellt die Formatzeichenfolge für die Achsenbeschriftungen dar. |
| [isNumberFormatLinkedToSource()](#isNumberFormatLinkedToSource--) | Zeigt an, ob das Format mit Quelldaten verknüpft ist. |
| [setNumberFormatLinkedToSource(boolean value)](#setNumberFormatLinkedToSource-boolean-) | Zeigt an, ob das Format mit Quelldaten verknüpft ist. |
| [getTickLabelRotationAngle()](#getTickLabelRotationAngle--) | Stellt den Drehwinkel der Markierungsbeschriftungen dar. |
| [setTickLabelRotationAngle(float value)](#setTickLabelRotationAngle-float-) | Stellt den Drehwinkel der Markierungsbeschriftungen dar. |
| [getTickLabelSpacing()](#getTickLabelSpacing--) | Gibt an, wie viele Markierungsbeschriftungen zwischen den gezeichneten Beschriftungen übersprungen werden. |
| [setTickLabelSpacing(long value)](#setTickLabelSpacing-long-) | Gibt an, wie viele Markierungsbeschriftungen zwischen den gezeichneten Beschriftungen übersprungen werden. |
| [isAutomaticTickLabelSpacing()](#isAutomaticTickLabelSpacing--) | Gibt den automatischen Abstand zwischen Markierungsbeschriftungen an. |
| [setAutomaticTickLabelSpacing(boolean value)](#setAutomaticTickLabelSpacing-boolean-) | Gibt den automatischen Abstand zwischen Markierungsbeschriftungen an. |
| [getTickMarksSpacing()](#getTickMarksSpacing--) | Gibt an, wie viele Markierungen übersprungen werden sollen, bevor die nächste gezeichnet wird. |
| [setTickMarksSpacing(long value)](#setTickMarksSpacing-long-) | Gibt an, wie viele Markierungen übersprungen werden sollen, bevor die nächste gezeichnet wird. |
| [isAutomaticTickMarksSpacing()](#isAutomaticTickMarksSpacing--) | Gibt den automatischen Abstand zwischen Markierungen an. |
| [setAutomaticTickMarksSpacing(boolean value)](#setAutomaticTickMarksSpacing-boolean-) | Gibt den automatischen Abstand zwischen Markierungen an. |
| [getLabelOffset()](#getLabelOffset--) | Gibt den Abstand der Beschriftungen von der Achse an. |
| [setLabelOffset(int value)](#setLabelOffset-int-) | Gibt den Abstand der Beschriftungen von der Achse an. |
| [getAggregationType()](#getAggregationType--) | Stellt den Aggregationstyp der Kategorienachse (Binning) dar. |
| [setAggregationType(int value)](#setAggregationType-int-) | Stellt den Aggregationstyp der Kategorienachse (Binning) dar. |
| [getBinWidth()](#getBinWidth--) | Gibt die Bin-Breite an, wenn die Eigenschaft AggregationType auf AxisAggregationType.ByBinWidth gesetzt ist. |
| [setBinWidth(double value)](#setBinWidth-double-) | Gibt die Bin-Breite an, wenn die Eigenschaft AggregationType auf AxisAggregationType.ByBinWidth gesetzt ist. |
| [getNumberOfBins()](#getNumberOfBins--) | Gibt die Anzahl der Bins an, wenn die Eigenschaft AggregationType auf AxisAggregationType.ByNumberOfBins gesetzt ist. |
| [setNumberOfBins(long value)](#setNumberOfBins-long-) | Gibt die Anzahl der Bins an, wenn die Eigenschaft AggregationType auf AxisAggregationType.ByNumberOfBins gesetzt ist. |
| [isOverflowBin()](#isOverflowBin--) | Gibt an, ob ein Overflow-Bin angewendet wird. |
| [setOverflowBin(boolean value)](#setOverflowBin-boolean-) | Gibt an, ob ein Overflow-Bin angewendet wird. |
| [isAutomaticOverflowBin()](#isAutomaticOverflowBin--) | Gibt den automatischen Wert für das Overflow-Bin an. |
| [setAutomaticOverflowBin(boolean value)](#setAutomaticOverflowBin-boolean-) | Gibt den automatischen Wert für das Overflow-Bin an. |
| [getOverflowBin()](#getOverflowBin--) | Gibt den benutzerdefinierten Wert für das Overflow-Bin an. |
| [setOverflowBin(double value)](#setOverflowBin-double-) | Gibt den benutzerdefinierten Wert für das Overflow-Bin an. |
| [isUnderflowBin()](#isUnderflowBin--) | Gibt an, ob ein Underflow-Bin angewendet wird. |
| [setUnderflowBin(boolean value)](#setUnderflowBin-boolean-) | Gibt an, ob ein Underflow-Bin angewendet wird. |
| [isAutomaticUnderflowBin()](#isAutomaticUnderflowBin--) | Gibt den automatischen Wert für das Underflow-Bin an. |
| [setAutomaticUnderflowBin(boolean value)](#setAutomaticUnderflowBin-boolean-) | Gibt den automatischen Wert für das Underflow-Bin an. |
| [getUnderflowBin()](#getUnderflowBin--) | Gibt den benutzerdefinierten Wert für das Underflow-Bin an. |
| [setUnderflowBin(double value)](#setUnderflowBin-double-) | Gibt den benutzerdefinierten Wert für das Underflow-Bin an. |
| [getSlide()](#getSlide--) | Gibt die übergeordnete Folie eines FillFormat zurück. |
| [getPresentation()](#getPresentation--) | Gibt die übergeordnete Präsentation eines FillFormat zurück. |

### getChart() {#getChart--}
```
public final IChart getChart()
```

Gibt das übergeordnete Diagramm zurück. Nur lesbar [IChart](../../com.aspose.slides/ichart).

**Rückgabe:**
[IChart](../../com.aspose.slides/ichart)

### getAxisBetweenCategories() {#getAxisBetweenCategories--}
```
public final boolean getAxisBetweenCategories()
```

Stellt dar, ob die Werteachse die Kategorienachse zwischen den Kategorien schneidet. Diese Eigenschaft gilt nur für Kategorienachsen und nicht für 3-D-Diagramme. Lesen/Schreiben boolean.

**Rückgabe:**
boolean

### setAxisBetweenCategories(boolean value) {#setAxisBetweenCategories-boolean-}
```
public final void setAxisBetweenCategories(boolean value)
```

Stellt dar, ob die Werteachse die Kategorienachse zwischen den Kategorien schneidet. Diese Eigenschaft gilt nur für Kategorienachsen und nicht für 3-D-Diagramme. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getCategoryAxisType() {#getCategoryAxisType--}
```
public final int getCategoryAxisType()
```

Gibt den Typ der Kategorienachse an. Lesen/Schreiben [CategoryAxisType](../../com.aspose.slides/categoryaxistype).

**Rückgabe:**
int

### setCategoryAxisType(int value) {#setCategoryAxisType-int-}
```
public final void setCategoryAxisType(int value)
```

Gibt den Typ der Kategorienachse an. Lesen/Schreiben [CategoryAxisType](../../com.aspose.slides/categoryaxistype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### setCategoryAxisTypeAutomatically() {#setCategoryAxisTypeAutomatically--}
```
public final void setCategoryAxisTypeAutomatically()
```

Setzt die Eigenschaft IAxis.CategoryAxisType auf einen automatisch anhand der Achsendaten ermittelten Wert.

### getCrossAt() {#getCrossAt--}
```
public final float getCrossAt()
```

Stellt den Punkt auf der Achse dar, an dem die senkrechte Achse sie kreuzt. Lesen/Schreiben float.

**Rückgabe:**
float

### setCrossAt(float value) {#setCrossAt-float-}
```
public final void setCrossAt(float value)
```

Stellt den Punkt auf der Achse dar, an dem die senkrechte Achse sie kreuzt. Lesen/Schreiben float.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |

### getDisplayUnit() {#getDisplayUnit--}
```
public final int getDisplayUnit()
```

Gibt den Skalierungswert der Anzeigeeinheiten für die Werteachse an. Lesen/Schreiben [DisplayUnitType](../../com.aspose.slides/displayunittype).

**Rückgabe:**
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

Gibt den tatsächlichen Maximalwert auf der Achse an. Rufen Sie vorher IChart.ValidateChartLayout() auf, um den tatsächlichen Wert zu erhalten.

**Rückgabe:**
double

### getActualMinValue() {#getActualMinValue--}
```
public final double getActualMinValue()
```

Gibt den tatsächlichen Minimalwert auf der Achse an. Rufen Sie vorher IChart.ValidateChartLayout() auf, um den tatsächlichen Wert zu erhalten.

**Rückgabe:**
double

### getActualMajorUnit() {#getActualMajorUnit--}
```
public final double getActualMajorUnit()
```

Gibt die tatsächliche Haupteinheit der Achse an. Rufen Sie vorher IChart.ValidateChartLayout() auf, um den tatsächlichen Wert zu erhalten.

**Rückgabe:**
double

### getActualMinorUnit() {#getActualMinorUnit--}
```
public final double getActualMinorUnit()
```

Gibt die tatsächliche Nebeneinheit der Achse an. Rufen Sie vorher IChart.ValidateChartLayout() auf, um den tatsächlichen Wert zu erhalten.

**Rückgabe:**
double

### getActualMajorUnitScale() {#getActualMajorUnitScale--}
```
public final int getActualMajorUnitScale()
```

Gibt die tatsächliche Skalierung der Haupteinheit der Achse an. Rufen Sie vorher IChart.ValidateChartLayout() auf, um den tatsächlichen Wert zu erhalten.

**Rückgabe:**
int

### getActualMinorUnitScale() {#getActualMinorUnitScale--}
```
public final int getActualMinorUnitScale()
```

Gibt die tatsächliche Skalierung der Nebeneinheit der Achse an. Rufen Sie vorher IChart.ValidateChartLayout() auf, um den tatsächlichen Wert zu erhalten.

**Rückgabe:**
int

### isAutomaticMaxValue() {#isAutomaticMaxValue--}
```
public final boolean isAutomaticMaxValue()
```

Zeigt an, ob der Maximalwert automatisch zugewiesen wird. Lesen/Schreiben boolean.

**Rückgabe:**
boolean

### setAutomaticMaxValue(boolean value) {#setAutomaticMaxValue-boolean-}
```
public final void setAutomaticMaxValue(boolean value)
```

Zeigt an, ob der Maximalwert automatisch zugewiesen wird. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getMaxValue() {#getMaxValue--}
```
public final double getMaxValue()
```

Stellt den Maximalwert auf der Werteachse dar. Lesen/Schreiben double.

**Rückgabe:**
double

### setMaxValue(double value) {#setMaxValue-double-}
```
public final void setMaxValue(double value)
```

Stellt den Maximalwert auf der Werteachse dar. Lesen/Schreiben double.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |

### getMinorUnit() {#getMinorUnit--}
```
public final double getMinorUnit()
```

Stellt die Nebeneinheiten für die Datums- oder Werteachse dar. Lesen/Schreiben double.

**Rückgabe:**
double

### setMinorUnit(double value) {#setMinorUnit-double-}
```
public final void setMinorUnit(double value)
```

Stellt die Nebeneinheiten für die Datums- oder Werteachse dar. Lesen/Schreiben double.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |

### isAutomaticMinorUnit() {#isAutomaticMinorUnit--}
```
public final boolean isAutomaticMinorUnit()
```

Zeigt an, ob die Nebeneinheit der Achse automatisch zugewiesen wird. Lesen/Schreiben boolean.

**Rückgabe:**
boolean

### setAutomaticMinorUnit(boolean value) {#setAutomaticMinorUnit-boolean-}
```
public final void setAutomaticMinorUnit(boolean value)
```

Zeigt an, ob die Nebeneinheit der Achse automatisch zugewiesen wird. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getMajorUnit() {#getMajorUnit--}
```
public final double getMajorUnit()
```

Stellt die Haupteinheiten für die Datums- oder Werteachse dar. Lesen/Schreiben double.

**Rückgabe:**
double

### setMajorUnit(double value) {#setMajorUnit-double-}
```
public final void setMajorUnit(double value)
```

Stellt die Haupteinheiten für die Datums- oder Werteachse dar. Lesen/Schreiben double.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |

### isAutomaticMajorUnit() {#isAutomaticMajorUnit--}
```
public final boolean isAutomaticMajorUnit()
```

Zeigt an, ob die Haupteinheit der Achse automatisch zugewiesen wird. Lesen/Schreiben boolean.

**Rückgabe:**
boolean

### setAutomaticMajorUnit(boolean value) {#setAutomaticMajorUnit-boolean-}
```
public final void setAutomaticMajorUnit(boolean value)
```

Zeigt an, ob die Haupteinheit der Achse automatisch zugewiesen wird. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticMinValue() {#isAutomaticMinValue--}
```
public final boolean isAutomaticMinValue()
```

Zeigt an, ob der Minimalwert automatisch zugewiesen wird. Lesen/Schreiben boolean.

**Rückgabe:**
boolean

### setAutomaticMinValue(boolean value) {#setAutomaticMinValue-boolean-}
```
public final void setAutomaticMinValue(boolean value)
```

Zeigt an, ob der Minimalwert automatisch zugewiesen wird. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getMinValue() {#getMinValue--}
```
public final double getMinValue()
```

Stellt den Minimalwert auf der Werteachse dar. Lesen/Schreiben double.

**Rückgabe:**
double

### setMinValue(double value) {#setMinValue-double-}
```
public final void setMinValue(double value)
```

Stellt den Minimalwert auf der Werteachse dar. Lesen/Schreiben double.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |

### isLogarithmic() {#isLogarithmic--}
```
public final boolean isLogarithmic()
```

Stellt dar, ob der Skalierungstyp der Werteachse logarithmisch ist oder nicht. Lesen/Schreiben boolean.

**Rückgabe:**
boolean

### setLogarithmic(boolean value) {#setLogarithmic-boolean-}
```
public final void setLogarithmic(boolean value)
```

Stellt dar, ob der Skalierungstyp der Werteachse logarithmisch ist oder nicht. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getLogBase() {#getLogBase--}
```
public final double getLogBase()
```

Stellt die logarithmische Basis dar. Der Standardwert ist 10. Lesen/Schreiben double.

**Rückgabe:**
double

### setLogBase(double value) {#setLogBase-double-}
```
public final void setLogBase(double value)
```

Stellt die logarithmische Basis dar. Der Standardwert ist 10. Lesen/Schreiben double.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |

### isPlotOrderReversed() {#isPlotOrderReversed--}
```
public final boolean isPlotOrderReversed()
```

Stellt dar, ob MS PowerPoint Datenpunkte von zuletzt nach zuerst darstellt. Lesen/Schreiben boolean.

**Rückgabe:**
boolean

### setPlotOrderReversed(boolean value) {#setPlotOrderReversed-boolean-}
```
public final void setPlotOrderReversed(boolean value)
```

Stellt dar, ob MS PowerPoint Datenpunkte von zuletzt nach zuerst darstellt. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

Stellt dar, ob die Achse sichtbar ist. Lesen/Schreiben boolean.

**Rückgabe:**
boolean

### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```

Stellt dar, ob die Achse sichtbar ist. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getMajorTickMark() {#getMajorTickMark--}
```
public final int getMajorTickMark()
```

Stellt den Typ der Haupt-Markierung für die angegebene Achse dar. Lesen/Schreiben [TickMarkType](../../com.aspose.slides/tickmarktype).

**Rückgabe:**
int

### setMajorTickMark(int value) {#setMajorTickMark-int-}
```
public final void setMajorTickMark(int value)
```

Stellt den Typ der Haupt-Markierung für die angegebene Achse dar. Lesen/Schreiben [TickMarkType](../../com.aspose.slides/tickmarktype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getMinorTickMark() {#getMinorTickMark--}
```
public final int getMinorTickMark()
```

Stellt den Typ der Neben-Markierung für die angegebene Achse dar. Lesen/Schreiben [TickMarkType](../../com.aspose.slides/tickmarktype).

**Rückgabe:**
int

### setMinorTickMark(int value) {#setMinorTickMark-int-}
```
public final void setMinorTickMark(int value)
```

Stellt den Typ der Neben-Markierung für die angegebene Achse dar. Lesen/Schreiben [TickMarkType](../../com.aspose.slides/tickmarktype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getTickLabelPosition() {#getTickLabelPosition--}
```
public final int getTickLabelPosition()
```

Stellt die Position der Beschriftungen der Markierungen auf der angegebenen Achse dar. Lesen/Schreiben [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**Rückgabe:**
int

### setTickLabelPosition(int value) {#setTickLabelPosition-int-}
```
public final void setTickLabelPosition(int value)
```

Stellt die Position der Beschriftungen der Markierungen auf der angegebenen Achse dar. Lesen/Schreiben [TickLabelPositionType](../../com.aspose.slides/ticklabelpositiontype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getMajorUnitScale() {#getMajorUnitScale--}
```
public final int getMajorUnitScale()
```

Stellt die Skalierung der Haupteinheit für die Datumsachse dar. Lesen/Schreiben [TimeUnitType](../../com.aspose.slides/timeunittype).

**Rückgabe:**
int

### setMajorUnitScale(int value) {#setMajorUnitScale-int-}
```
public final void setMajorUnitScale(int value)
```

Stellt die Skalierung der Haupteinheit für die Datumsachse dar. Lesen/Schreiben [TimeUnitType](../../com.aspose.slides/timeunittype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getMinorUnitScale() {#getMinorUnitScale--}
```
public final int getMinorUnitScale()
```

Stellt die Skalierung der Haupteinheit für die Datumsachse dar. Lesen/Schreiben [TimeUnitType](../../com.aspose.slides/timeunittype).

**Rückgabe:**
int

### setMinorUnitScale(int value) {#setMinorUnitScale-int-}
```
public final void setMinorUnitScale(int value)
```

Stellt die Skalierung der Haupteinheit für die Datumsachse dar. Lesen/Schreiben [TimeUnitType](../../com.aspose.slides/timeunittype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getBaseUnitScale() {#getBaseUnitScale--}
```
public final int getBaseUnitScale()
```

Gibt die kleinste Zeiteinheit an, die auf der Datumsachse dargestellt wird. Lesen/Schreiben [TimeUnitType](../../com.aspose.slides/timeunittype).

**Rückgabe:**
int

### setBaseUnitScale(int value) {#setBaseUnitScale-int-}
```
public final void setBaseUnitScale(int value)
```

Gibt die kleinste Zeiteinheit an, die auf der Datumsachse dargestellt wird. Lesen/Schreiben [TimeUnitType](../../com.aspose.slides/timeunittype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getMinorGridLinesFormat() {#getMinorGridLinesFormat--}
```
public final IChartLinesFormat getMinorGridLinesFormat()
```

Stellt das Format der Hilfsgitterlinien auf einer Diagrammachse dar. Nur lesbar [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**Rückgabe:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getMajorGridLinesFormat() {#getMajorGridLinesFormat--}
```
public final IChartLinesFormat getMajorGridLinesFormat()
```

Stellt das Format der Hauptgitterlinien auf einer Diagrammachse dar. Nur lesbar [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

**Rückgabe:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getShowMinorGridLines() {#getShowMinorGridLines--}
```
public final boolean getShowMinorGridLines()
```

Um die Hilfsgitterlinie auszublenden, setzen Sie MinorGridLinesFormat.Line.FillFormat.FillType auf FillType.NoFill. Nur lesbar boolean.

**Rückgabe:**
boolean

### getShowMajorGridLines() {#getShowMajorGridLines--}
```
public final boolean getShowMajorGridLines()
```

Um die Hauptgitterlinie auszublenden, setzen Sie MajorGridLinesFormat.Line.FillFormat.FillType auf FillType.NoFill. Nur lesbar boolean.

**Rückgabe:**
boolean

### getFormat() {#getFormat--}
```
public final IAxisFormat getFormat()
```

Stellt das Format der Achse dar. Nur lesbar [IAxisFormat](../../com.aspose.slides/iaxisformat).

**Rückgabe:**
[IAxisFormat](../../com.aspose.slides/iaxisformat)

### getTextFormat() {#getTextFormat--}
```
public final IChartTextFormat getTextFormat()
```

Stellt das Textformat dar. Nur lesbar [IChartTextFormat](../../com.aspose.slides/icharttextformat).

**Rückgabe:**
[IChartTextFormat](../../com.aspose.slides/icharttextformat)

### getTitle() {#getTitle--}
```
public final IChartTitle getTitle()
```

Liest den Titel der Achse. Nur lesbar [IChartTitle](../../com.aspose.slides/icharttitle).

**Rückgabe:**
[IChartTitle](../../com.aspose.slides/icharttitle)

### getCrossType() {#getCrossType--}
```
public final int getCrossType()
```

Stellt den CrossType auf der angegebenen Achse dar, an dem die andere Achse sie schneidet. Lesen/Schreiben [CrossesType](../../com.aspose.slides/crossestype).

**Rückgabe:**
int

### setCrossType(int value) {#setCrossType-int-}
```
public final void setCrossType(int value)
```

Stellt den CrossType auf der angegebenen Achse dar, an dem die andere Achse sie schneidet. Lesen/Schreiben [CrossesType](../../com.aspose.slides/crossestype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getPosition() {#getPosition--}
```
public final int getPosition()
```

Stellt die Position der Achse dar. Lesen/Schreiben [AxisPositionType](../../com.aspose.slides/axispositiontype).

**Rückgabe:**
int

### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```

Stellt die Position der Achse dar. Lesen/Schreiben [AxisPositionType](../../com.aspose.slides/axispositiontype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### hasTitle() {#hasTitle--}
```
public final boolean hasTitle()
```

Bestimmt, ob eine Achse einen sichtbaren Titel hat. Lesen/Schreiben boolean.

**Rückgabe:**
boolean

### setTitle(boolean value) {#setTitle-boolean-}
```
public final void setTitle(boolean value)
```

Bestimmt, ob eine Achse einen sichtbaren Titel hat. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormat() {#getNumberFormat--}
```
public final String getNumberFormat()
```

Stellt die Formatzeichenfolge für die Achsenbeschriftungen dar. Lesen/Schreiben String.

**Rückgabe:**
java.lang.String

### setNumberFormat(String value) {#setNumberFormat-java.lang.String-}
```
public final void setNumberFormat(String value)
```

Stellt die Formatzeichenfolge für die Achsenbeschriftungen dar. Lesen/Schreiben String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |

### isNumberFormatLinkedToSource() {#isNumberFormatLinkedToSource--}
```
public final boolean isNumberFormatLinkedToSource()
```

Zeigt an, ob das Format mit Quelldaten verknüpft ist. Lesen/Schreiben boolean.

**Rückgabe:**
boolean

### setNumberFormatLinkedToSource(boolean value) {#setNumberFormatLinkedToSource-boolean-}
```
public final void setNumberFormatLinkedToSource(boolean value)
```

Zeigt an, ob das Format mit Quelldaten verknüpft ist. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getTickLabelRotationAngle() {#getTickLabelRotationAngle--}
```
public final float getTickLabelRotationAngle()
```

Stellt den Drehwinkel der Markierungsbeschriftungen dar. Lesen/Schreiben float.

**Rückgabe:**
float

### setTickLabelRotationAngle(float value) {#setTickLabelRotationAngle-float-}
```
public final void setTickLabelRotationAngle(float value)
```

Stellt den Drehwinkel der Markierungsbeschriftungen dar. Lesen/Schreiben float.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |

### getTickLabelSpacing() {#getTickLabelSpacing--}
```
public final long getTickLabelSpacing()
```

Gibt an, wie viele Markierungsbeschriftungen zwischen den gezeichneten Beschriftungen übersprungen werden. Gilt für Kategorien- oder Serienachse. Lesen/Schreiben long.

**Rückgabe:**
long

### setTickLabelSpacing(long value) {#setTickLabelSpacing-long-}
```
public final void setTickLabelSpacing(long value)
```

Gibt an, wie viele Markierungsbeschriftungen zwischen den gezeichneten Beschriftungen übersprungen werden. Gilt für Kategorien- oder Serienachse. Lesen/Schreiben long.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickLabelSpacing() {#isAutomaticTickLabelSpacing--}
```
public final boolean isAutomaticTickLabelSpacing()
```

Gibt den automatischen Abstand zwischen Markierungsbeschriftungen an. Wenn false: wird TickLabelSpacing verwendet. Lesen/Schreiben boolean.

**Rückgabe:**
boolean

### setAutomaticTickLabelSpacing(boolean value) {#setAutomaticTickLabelSpacing-boolean-}
```
public final void setAutomaticTickLabelSpacing(boolean value)
```

Gibt den automatischen Abstand zwischen Markierungsbeschriftungen an. Wenn false: wird TickLabelSpacing verwendet. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getTickMarksSpacing() {#getTickMarksSpacing--}
```
public final long getTickMarksSpacing()
```

Gibt an, wie viele Markierungen übersprungen werden sollen, bevor die nächste gezeichnet wird. Gilt für Kategorien- oder Serienachse. Lesen/Schreiben int.

**Rückgabe:**
long

### setTickMarksSpacing(long value) {#setTickMarksSpacing-long-}
```
public final void setTickMarksSpacing(long value)
```

Gibt an, wie viele Markierungen übersprungen werden sollen, bevor die nächste gezeichnet wird. Gilt für Kategorien- oder Serienachse. Lesen/Schreiben int.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | long |  |

### isAutomaticTickMarksSpacing() {#isAutomaticTickMarksSpacing--}
```
public final boolean isAutomaticTickMarksSpacing()
```

Gibt den automatischen Abstand zwischen Markierungen an. Wenn false: wird TickMarksSpacing verwendet. Lesen/Schreiben boolean.

**Rückgabe:**
boolean

### setAutomaticTickMarksSpacing(boolean value) {#setAutomaticTickMarksSpacing-boolean-}
```
public final void setAutomaticTickMarksSpacing(boolean value)
```

Gibt den automatischen Abstand zwischen Markierungen an. Wenn false: wird TickMarksSpacing verwendet. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getLabelOffset() {#getLabelOffset--}
```
public final int getLabelOffset()
```

Gibt den Abstand der Beschriftungen von der Achse an. Gilt für Kategorien- oder Datumsachse. Der Wert muss zwischen 0 % und 1000 % liegen. Lesen/Schreiben int.

**Rückgabe:**
int

### setLabelOffset(int value) {#setLabelOffset-int-}
```
public final void setLabelOffset(int value)
```

Gibt den Abstand der Beschriftungen von der Achse an. Gilt für Kategorien- oder Datumsachse. Der Wert muss zwischen 0 % und 1000 % liegen. Lesen/Schreiben int.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getAggregationType() {#getAggregationType--}
```
public final int getAggregationType()
```

Stellt den Aggregationstyp der Kategorienachse (Binning) dar. Gilt für Kategorien. Nur mit Histogram- oder HistogramPareto-Serien verwendet.

**Rückgabe:**
int

### setAggregationType(int value) {#setAggregationType-int-}
```
public final void setAggregationType(int value)
```

Stellt den Aggregationstyp der Kategorienachse (Binning) dar. Gilt für Kategorien. Nur mit Histogram- oder HistogramPareto-Serien verwendet.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getBinWidth() {#getBinWidth--}
```
public final double getBinWidth()
```

Gibt die Bin-Breite an, wenn die Eigenschaft AggregationType auf AxisAggregationType.ByBinWidth gesetzt ist. Gilt für Kategorienachsen. Nur mit Histogram- oder HistogramPareto-Serien verwendet.

**Rückgabe:**
double

### setBinWidth(double value) {#setBinWidth-double-}
```
public final double getBinWidth()
```

Gibt die Bin-Breite an, wenn die Eigenschaft AggregationType auf AxisAggregationType.ByBinWidth gesetzt ist. Gilt für Kategorienachsen. Nur mit Histogram- oder HistogramPareto-Serien verwendet.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |

### getNumberOfBins() {#getNumberOfBins--}
```
public final long getNumberOfBins()
```

Gibt die Anzahl der Bins an, wenn die Eigenschaft AggregationType auf AxisAggregationType.ByNumberOfBins gesetzt ist. Gilt für Kategorienachsen. Nur mit Histogram- oder HistogramPareto-Serien verwendet.

**Rückgabe:**
long

### setNumberOfBins(long value) {#setNumberOfBins-long-}
```
public final void setNumberOfBins(long value)
```

Gibt die Anzahl der Bins an, wenn die Eigenschaft AggregationType auf AxisAggregationType.ByNumberOfBins gesetzt ist. Gilt für Kategorienachsen. Nur mit Histogram- oder HistogramPareto-Serien verwendet.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | long |  |

### isOverflowBin() {#isOverflowBin--}
```
public final boolean isOverflowBin()
```

Gibt an, ob ein Overflow-Bin angewendet wird. Verwenden Sie IsAutomaticOverflowBin und OverflowBin, um den Wert anzupassen.

**Rückgabe:**
boolean

### setOverflowBin(boolean value) {#setOverflowBin-boolean-}
```
public final void setOverflowBin(boolean value)
```

Gibt an, ob ein Overflow-Bin angewendet wird. Verwenden Sie IsAutomaticOverflowBin und OverflowBin, um den Wert anzupassen.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticOverflowBin() {#isAutomaticOverflowBin--}
```
public final boolean isAutomaticOverflowBin()
```

Gibt den automatischen Wert für das Overflow-Bin an. Wenn false: wird OverflowBin verwendet.

**Rückgabe:**
boolean

### setAutomaticOverflowBin(boolean value) {#setAutomaticOverflowBin-boolean-}
```
public final void setAutomaticOverflowBin(boolean value)
```

Gibt den automatischen Wert für das Overflow-Bin an. Wenn false: wird OverflowBin verwendet.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getOverflowBin() {#getOverflowBin--}
```
public final double getOverflowBin()
```

Gibt den benutzerdefinierten Wert für das Overflow-Bin an. Wird angewendet, wenn IsAutomaticOverflowBin auf false gesetzt ist und IsOverflowBin true ist.

**Rückgabe:**
double

### setOverflowBin(double value) {#setOverflowBin-double-}
```
public final void setOverflowBin(double value)
```

Gibt den benutzerdefinierten Wert für das Overflow-Bin an. Wird angewendet, wenn IsAutomaticOverflowBin auf false gesetzt ist und IsOverflowBin true ist.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |

### isUnderflowBin() {#isUnderflowBin--}
```
public final boolean isUnderflowBin()
```

Gibt an, ob ein Underflow-Bin angewendet wird. Verwenden Sie IsAutomaticUnderflowBin und UnderflowBin, um den Wert anzupassen.

**Rückgabe:**
boolean

### setUnderflowBin(boolean value) {#setUnderflowBin-boolean-}
```
public final void setUnderflowBin(boolean value)
```

Gibt an, ob ein Underflow-Bin angewendet wird. Verwenden Sie IsAutomaticUnderflowBin und UnderflowBin, um den Wert anzupassen.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### isAutomaticUnderflowBin() {#isAutomaticUnderflowBin--}
```
public final boolean isAutomaticUnderflowBin()
```

Gibt den automatischen Wert für das Underflow-Bin an. Wenn false: wird UnderflowBin verwendet.

**Rückgabe:**
boolean

### setAutomaticUnderflowBin(boolean value) {#setAutomaticUnderflowBin-boolean-}
```
public final void setAutomaticUnderflowBin(boolean value)
```

Gibt den automatischen Wert für das Underflow-Bin an. Wenn false: wird UnderflowBin verwendet.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getUnderflowBin() {#getUnderflowBin--}
```
public final double getUnderflowBin()
```

Gibt den benutzerdefinierten Wert für das Underflow-Bin an. Wird angewendet, wenn IsAutomaticUnderflowBin auf false gesetzt ist und IsUnderflowBin true ist.

**Rückgabe:**
double

### setUnderflowBin(double value) {#setUnderflowBin-double-}
```
public final void setUnderflowBin(double value)
```

Gibt den benutzerdefinierten Wert für das Underflow-Bin an. Wird angewendet, wenn IsAutomaticUnderflowBin auf false gesetzt ist und IsUnderflowBin true ist.

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