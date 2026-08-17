---
title: IChartSeries
second_title: Aspose.Slides für Java API Referenz
description: Stellt eine Diagrammserie dar.
type: docs
url: /de/com.aspose.slides/ichartseries/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IChartSeries extends IChartComponent
```

Stellt eine Diagrammserie dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getExplosion()](#getExplosion--) | Der Abstand eines offenen Kuchenscheibens vom Mittelpunkt des Kreisdiagramms wird als Prozentsatz des Durchmessers des Kreises angegeben. |
| [setExplosion(int value)](#setExplosion-int-) | Der Abstand eines offenen Kuchenscheibens vom Mittelpunkt des Kreisdiagramms wird als Prozentsatz des Durchmessers des Kreises angegeben. |
| [getSmooth()](#getSmooth--) | Stellt Kurvenglättung dar. |
| [setSmooth(boolean value)](#setSmooth-boolean-) | Stellt Kurvenglättung dar. |
| [getMarker()](#getMarker--) | Gibt den Serienmarker zurück. |
| [getBar3DShape()](#getBar3DShape--) | Gibt die Form einer Serie eines 3-D-Balkendiagramms an. |
| [setBar3DShape(int value)](#setBar3DShape-int-) | Gibt die Form einer Serie eines 3-D-Balkendiagramms an. |
| [getName()](#getName--) | Gibt den Seriennamen zurück. |
| [getDataPoints()](#getDataPoints--) | Gibt die Sammlung von Datenpunkten dieser Serie zurück. |
| [getType()](#getType--) | Gibt einen Typ dieser Serie zurück. |
| [setType(int value)](#setType-int-) | Gibt einen Typ dieser Serie zurück. |
| [getParentSeriesGroup()](#getParentSeriesGroup--) | Gibt die übergeordnete Seriengruppe zurück. |
| [getFormat()](#getFormat--) | Gibt das Format einer Serie zurück. |
| [getOrder()](#getOrder--) | Gibt die Reihenfolge einer Serie zurück. |
| [setOrder(int value)](#setOrder-int-) | Gibt die Reihenfolge einer Serie zurück. |
| [getLabels()](#getLabels--) | Gibt die Beschriftungen einer Serie zurück. |
| [getTrendLines()](#getTrendLines--) | Sammlung von Serien-Trendlinien Nur lesen [ITrendlineCollection](../../com.aspose.slides/itrendlinecollection). |
| [getErrorBarsXFormat()](#getErrorBarsXFormat--) | Stellt ErrorBars einer Serie mit Richtung X dar. |
| [getErrorBarsYFormat()](#getErrorBarsYFormat--) | Stellt ErrorBars einer Serie mit Richtung Y dar. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Gibt an, ob diese Serie auf der sekundären Werteachse dargestellt wird. |
| [setPlotOnSecondAxis(boolean value)](#setPlotOnSecondAxis-boolean-) | Gibt an, ob diese Serie auf der sekundären Werteachse dargestellt wird. |
| [getNumberFormatOfValues()](#getNumberFormatOfValues--) | Gibt das Zahlenformat für Serienwerte zurück oder legt es fest. |
| [setNumberFormatOfValues(String value)](#setNumberFormatOfValues-java.lang.String-) | Gibt das Zahlenformat für Serienwerte zurück oder legt es fest. |
| [getNumberFormatOfXValues()](#getNumberFormatOfXValues--) | Gibt das Zahlenformat für Serien-X-Werte zurück oder legt es fest. |
| [setNumberFormatOfXValues(String value)](#setNumberFormatOfXValues-java.lang.String-) | Gibt das Zahlenformat für Serien-X-Werte zurück oder legt es fest. |
| [getNumberFormatOfYValues()](#getNumberFormatOfYValues--) | Gibt das Zahlenformat für Serien-Y-Werte zurück oder legt es fest. |
| [setNumberFormatOfYValues(String value)](#setNumberFormatOfYValues-java.lang.String-) | Gibt das Zahlenformat für Serien-Y-Werte zurück oder legt es fest. |
| [getNumberFormatOfBubbleSizes()](#getNumberFormatOfBubbleSizes--) | Gibt das Zahlenformat für Serien-Blasengrößen zurück oder legt es fest. |
| [setNumberFormatOfBubbleSizes(String value)](#setNumberFormatOfBubbleSizes-java.lang.String-) | Gibt das Zahlenformat für Serien-Blasengrößen zurück oder legt es fest. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Gibt an, dass die Balken-, Säulen- oder Blasensereie ihre Farben invertieren soll, wenn der Wert negativ ist. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Gibt an, dass die Balken-, Säulen- oder Blasensereie ihre Farben invertieren soll, wenn der Wert negativ ist. |
| [getInvertedSolidFillColor()](#getInvertedSolidFillColor--) | Gibt die invertierte Vollfarbe für die Serie an. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Stellt einen Legendeneintrag dar, der mit dieser Serie verknüpft ist Nur lesen [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |
| [getAutomaticSeriesColor()](#getAutomaticSeriesColor--) | Gibt eine automatische Farbe einer Serie zurück, basierend auf dem Serienindex und dem Diagrammstil. |
| [getShowInnerPoints()](#getShowInnerPoints--) | Stellt innere Punkte dar. |
| [setShowInnerPoints(boolean value)](#setShowInnerPoints-boolean-) | Stellt innere Punkte dar. |
| [getShowOutlierPoints()](#getShowOutlierPoints--) | Stellt Ausreißerpunkte dar. |
| [setShowOutlierPoints(boolean value)](#setShowOutlierPoints-boolean-) | Stellt Ausreißerpunkte dar. |
| [getShowMeanMarkers()](#getShowMeanMarkers--) | Stellt Mittelwertmarker dar. |
| [setShowMeanMarkers(boolean value)](#setShowMeanMarkers-boolean-) | Stellt Mittelwertmarker dar. |
| [getShowMeanLine()](#getShowMeanLine--) | Stellt Mittelwertmarker dar. |
| [setShowMeanLine(boolean value)](#setShowMeanLine-boolean-) | Stellt Mittelwertmarker dar. |
| [getQuartileMethod()](#getQuartileMethod--) | Stellt Quartilmethode dar. |
| [setQuartileMethod(int value)](#setQuartileMethod-int-) | Stellt Quartilmethode dar. |
| [getShowConnectorLines()](#getShowConnectorLines--) | Stellt Verbindungslinien dar. |
| [setShowConnectorLines(boolean value)](#setShowConnectorLines-boolean-) | Stellt Verbindungslinien dar. |
| [getParentLabelLayout()](#getParentLabelLayout--) | Stellt das Layout der übergeordneten Kategoriebeschriftungen dar. |
| [setParentLabelLayout(int value)](#setParentLabelLayout-int-) | Stellt das Layout der übergeordneten Kategoriebeschriftungen dar. |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Gibt den Skalierungsfaktor für das Blasendiagramm an (kann zwischen 0 und 300 % der Standardgröße liegen). |
| [hasUpDownBars()](#hasUpDownBars--) | Bestimmt, ob ein Linien- oder Kursdiagramm Auf/Ab-Balken hat. |
| [getGapWidth()](#getGapWidth--) | Gibt den Abstand zwischen Balken- oder Säulenklustern an, als Prozentsatz der Balken- oder Säulenbreite. |
| [getGapDepth()](#getGapDepth--) | Gibt den Abstand zurück oder legt ihn fest, als Prozentsatz der Markierungsbreite, zwischen den Datenserien in einem 3D-Diagramm. |
| [isColorVaried()](#isColorVaried--) | Gibt an, dass jeder Datenmarker in der Serie eine andere Farbe hat. |
| [hasSeriesLines()](#hasSeriesLines--) | Bestimmt, ob es Serienlinien für diese Serie und verwandte Serien gibt. |
| [getOverlap()](#getOverlap--) | Gibt an, wie stark Balken und Säulen in 2-D-Diagrammen überlappen, als Prozentsatz (von -100 % bis 100 %). |
| [getSecondPieSize()](#getSecondPieSize--) | Gibt die Größe des zweiten Kreises oder Balkens eines Pie-of-Pie-Diagramms bzw. Bar-of-Pie-Diagramms an, als Prozentsatz der Größe des ersten Kreises (kann zwischen 5 % und 200 % liegen). |
| [getPieSplitPosition()](#getPieSplitPosition--) | Gibt einen Wert an, der verwendet wird, um zu bestimmen, welche Datenpunkte im zweiten Kreis oder Balken eines Pie-of-Pie- oder Bar-of-Pie-Diagramms liegen. |
| [getPieSplitBy()](#getPieSplitBy--) | Gibt an, wie zu bestimmen ist, welche Datenpunkte im zweiten Kreis oder Balken eines Pie-of-Pie- oder Bar-of-Pie-Diagramms liegen. |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Gibt die Größe des Lochs in einem Donut-Diagramm an (kann zwischen 10 % und 90 % der Plot-Flächengröße liegen). |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | Gibt den Winkel des ersten Kuchen- oder Donut-Diagrammscheibchens in Grad an (im Uhrzeigersinn von oben, von 0 bis 360 Grad). |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | Die benutzerdefinierten Aufteilungsinformationen für ein Pie-of-Pie- oder Bar-of-Pie-Diagramm mit benutzerdefinierter Aufteilung. |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Gibt an, wie die Blasengrößenwerte im Blasendiagramm dargestellt werden. |

### getExplosion() {#getExplosion--}
```
public abstract int getExplosion()
```

Der Abstand eines offenen Kuchenscheibens vom Mittelpunkt des Kreisdiagramms wird als Prozentsatz des Durchmessers des Kreises angegeben. Lesen/Schreiben int.

**Rückgabe:**
int

### setExplosion(int value) {#setExplosion-int-}
```
public abstract void setExplosion(int value)
```

Der Abstand eines offenen Kuchenscheibens vom Mittelpunkt des Kreisdiagramms wird als Prozentsatz des Durchmessers des Kreises angegeben. Lesen/Schreiben int.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getSmooth() {#getSmooth--}
```
public abstract boolean getSmooth()
```

Stellt Kurvenglättung dar. True, wenn die Kurvenglättung für das Liniendiagramm oder Streudiagramm aktiviert ist. Gilt nur für Liniendiagramme und Streudiagramme, die durch Linien verbunden sind. Lesen/Schreiben boolean.

**Rückgabe:**
boolean

### setSmooth(boolean value) {#setSmooth-boolean-}
```
public abstract void setSmooth(boolean value)
```

Stellt Kurvenglättung dar. True, wenn die Kurvenglättung für das Liniendiagramm oder Streudiagramm aktiviert ist. Gilt nur für Liniendiagramme und Streudiagramme, die durch Linien verbunden sind. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getMarker() {#getMarker--}
```
public abstract IMarker getMarker()
```

Gibt den Serienmarker zurück. Nur lesen [IMarker](../../com.aspose.slides/imarker).

**Rückgabe:**
[IMarker](../../com.aspose.slides/imarker)

### getBar3DShape() {#getBar3DShape--}
```
public abstract int getBar3DShape()
```

Gibt die Form einer Serie eines 3-D-Balkendiagramms an. Eine Änderung des Werts dieser Eigenschaft kann zu einer automatischen Änderung des Typs der Serie führen. Lesen/Schreiben [ChartShapeType](../../com.aspose.slides/chartshapetype).

**Rückgabe:**
int

### setBar3DShape(int value) {#setBar3DShape-int-}
```
public abstract void setBar3DShape(int value)
```

Gibt die Form einer Serie eines 3-D-Balkendiagramms an. Eine Änderung des Werts dieser Eigenschaft kann zu einer automatischen Änderung des Typs der Serie führen. Lesen/Schreiben [ChartShapeType](../../com.aspose.slides/chartshapetype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getName() {#getName--}
```
public abstract IStringChartValue getName()
```

Gibt den Seriennamen zurück. Nur lesen [IStringChartValue](../../com.aspose.slides/istringchartvalue).

**Rückgabe:**
[IStringChartValue](../../com.aspose.slides/istringchartvalue)

### getDataPoints() {#getDataPoints--}
```
public abstract IChartDataPointCollection getDataPoints()
```

Gibt die Sammlung von Datenpunkten dieser Serie zurück. Nur lesen [IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection).

**Rückgabe:**
[IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection)

### getType() {#getType--}
```
public abstract int getType()
```

Gibt einen Typ dieser Serie zurück. Lesen/Schreiben [ChartType](../../com.aspose.slides/charttype).

**Rückgabe:**
int

### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

Gibt einen Typ dieser Serie zurück. Lesen/Schreiben [ChartType](../../com.aspose.slides/charttype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getParentSeriesGroup() {#getParentSeriesGroup--}
```
public abstract IChartSeriesGroup getParentSeriesGroup()
```

Gibt die übergeordnete Seriengruppe zurück. Nur lesen [IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup).

**Rückgabe:**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Gibt das Format einer Serie zurück. Nur lesen [IFormat](../../com.aspose.slides/iformat).

**Rückgabe:**
[IFormat](../../com.aspose.slides/iformat)

### getOrder() {#getOrder--}
```
public abstract int getOrder()
```

Gibt die Reihenfolge einer Serie zurück. Lesen/Schreiben int.

**Rückgabe:**
int

### setOrder(int value) {#setOrder-int-}
```
public abstract void setOrder(int value)
```

Gibt die Reihenfolge einer Serie zurück. Lesen/Schreiben int.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getLabels() {#getLabels--}
```
public abstract IDataLabelCollection getLabels()
```

Gibt die Beschriftungen einer Serie zurück. Nur lesen [IDataLabelCollection](../../com.aspose.slides/idatalabelcollection).

**Rückgabe:**
[IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)

### getTrendLines() {#getTrendLines--}
```
public abstract ITrendlineCollection getTrendLines()
```

Sammlung von Serien-Trendlinien Nur lesen [ITrendlineCollection](../../com.aspose.slides/itrendlinecollection).

**Rückgabe:**
[ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)

### getErrorBarsXFormat() {#getErrorBarsXFormat--}
```
public abstract IErrorBarsFormat getErrorBarsXFormat()
```

Stellt ErrorBars einer Serie mit Richtung X dar. Nur lesen [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

ErrorBars mit X-Richtung sind für Serien vom Typ area, bar, scatter und bubble verfügbar. Für alle anderen Diagrammtypen gibt diese Eigenschaft null zurück (einschließlich 3D-Diagrammen). Im Falle benutzerdefinierter Werte verwenden Sie die DataPoints-Sammlung, um den Wert anzugeben (mit der ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) Eigenschaft).

**Rückgabe:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)

### getErrorBarsYFormat() {#getErrorBarsYFormat--}
```
public abstract IErrorBarsFormat getErrorBarsYFormat()
```

Stellt ErrorBars einer Serie mit Richtung Y dar. Nur lesen [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

ErrorBars mit Y-Richtung sind für Serien vom Typ area, bar, line, scatter und bubble verfügbar. Für alle anderen Diagrammtypen gibt diese Eigenschaft null zurück (einschließlich 3D-Diagrammen). Im Falle benutzerdefinierter Werte verwenden Sie die DataPoints-Sammlung, um den Wert anzugeben (mit der ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) Eigenschaft).

**Rückgabe:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public abstract boolean getPlotOnSecondAxis()
```

Gibt an, ob diese Serie auf der sekundären Werteachse dargestellt wird. Lesen/Schreiben boolean.

**Rückgabe:**
boolean

### setPlotOnSecondAxis(boolean value) {#setPlotOnSecondAxis-boolean-}
```
public abstract void setPlotOnSecondAxis(boolean value)
```

Gibt an, ob diese Serie auf der sekundären Werteachse dargestellt wird. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getNumberFormatOfValues() {#getNumberFormatOfValues--}
```
public abstract String getNumberFormatOfValues()
```

Gibt das Zahlenformat für Serienwerte zurück oder legt es fest. Lesen/Schreiben String.

**Rückgabe:**
java.lang.String

### setNumberFormatOfValues(String value) {#setNumberFormatOfValues-java.lang.String-}
```
public abstract void setNumberFormatOfValues(String value)
```

Gibt das Zahlenformat für Serienwerte zurück oder legt es fest. Lesen/Schreiben String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfXValues() {#getNumberFormatOfXValues--}
```
public abstract String getNumberFormatOfXValues()
```

Gibt das Zahlenformat für Serien-X-Werte zurück oder legt es fest. Lesen/Schreiben String.

**Rückgabe:**
java.lang.String

### setNumberFormatOfXValues(String value) {#setNumberFormatOfXValues-java.lang.String-}
```
public abstract void setNumberFormatOfXValues(String value)
```

Gibt das Zahlenformat für Serien-X-Werte zurück oder legt es fest. Lesen/Schreiben String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfYValues() {#getNumberFormatOfYValues--}
```
public abstract String getNumberFormatOfYValues()
```

Gibt das Zahlenformat für Serien-Y-Werte zurück oder legt es fest. Lesen/Schreiben String.

**Rückgabe:**
java.lang.String

### setNumberFormatOfYValues(String value) {#setNumberFormatOfYValues-java.lang.String-}
```
public abstract void setNumberFormatOfYValues(String value)
```

Gibt das Zahlenformat für Serien-Y-Werte zurück oder legt es fest. Lesen/Schreiben String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |

### getNumberFormatOfBubbleSizes() {#getNumberFormatOfBubbleSizes--}
```
public abstract String getNumberFormatOfBubbleSizes()
```

Gibt das Zahlenformat für Serien-Blasengrößen zurück oder legt es fest. Lesen/Schreiben String.

**Rückgabe:**
java.lang.String

### setNumberFormatOfBubbleSizes(String value) {#setNumberFormatOfBubbleSizes-java.lang.String-}
```
public abstract void setNumberFormatOfBubbleSizes(String value)
```

Gibt das Zahlenformat für Serien-Blasengrößen zurück oder legt es fest. Lesen/Schreiben String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |

### getInvertIfNegative() {#getInvertIfNegative--}
```
public abstract boolean getInvertIfNegative()
```

Gibt an, dass die Balken-, Säulen- oder Blasensereie ihre Farben invertieren soll, wenn der Wert negativ ist. Lesen/Schreiben boolean.

**Rückgabe:**
boolean

### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public abstract void setInvertIfNegative(boolean value)
```

Gibt an, dass die Balken-, Säulen- oder Blasensereie ihre Farben invertieren soll, wenn der Wert negativ ist. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getInvertedSolidFillColor() {#getInvertedSolidFillColor--}
```
public abstract IColorFormat getInvertedSolidFillColor()
```

Gibt invertierte Vollfarbe für die Serie an. Um die Farbe anzuwenden, setzen Sie den Serienformat-FillType auf FillType.Solid. Lesen/Schreiben [IColorFormat](../../com.aspose.slides/icolorformat).

**Rückgabe:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```

Stellt einen Legendeneintrag dar, der mit dieser Serie verknüpft ist Nur lesen [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Rückgabe:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)

### getAutomaticSeriesColor() {#getAutomaticSeriesColor--}
```
public abstract Color getAutomaticSeriesColor()
```
Returns an automatic color of series based on series index and chart style. This color is used by default if FillType equals NotDefined.

**Rückgabewert:**
java.awt.Color - Automatische Farbe der Serie java.awt.Color
### getShowInnerPoints() {#getShowInnerPoints--}
```
public abstract boolean getShowInnerPoints()
```

Stellt innere Punkte dar. True, wenn innere Punkte im BoxAndWhisker-Diagramm angezeigt werden. Gilt nur für BoxAndWhisker-Diagramme. Lesen/Schreiben boolesch.

**Rückgabewert:**
boolean
### setShowInnerPoints(boolean value) {#setShowInnerPoints-boolean-}
```
public abstract void setShowInnerPoints(boolean value)
```

Stellt innere Punkte dar. True, wenn innere Punkte im BoxAndWhisker-Diagramm angezeigt werden. Gilt nur für BoxAndWhisker-Diagramme. Lesen/Schreiben boolesch.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getShowOutlierPoints() {#getShowOutlierPoints--}
```
public abstract boolean getShowOutlierPoints()
```

Stellt Ausreißerpunkte dar. True, wenn Ausreißerpunkte im BoxAndWhisker-Diagramm angezeigt werden. Gilt nur für BoxAndWhisker-Diagramme. Lesen/Schreiben boolesch.

**Rückgabewert:**
boolean
### setShowOutlierPoints(boolean value) {#setShowOutlierPoints-boolean-}
```
public abstract void setShowOutlierPoints(boolean value)
```

Stellt Ausreißerpunkte dar. True, wenn Ausreißerpunkte im BoxAndWhisker-Diagramm angezeigt werden. Gilt nur für BoxAndWhisker-Diagramme. Lesen/Schreiben boolesch.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getShowMeanMarkers() {#getShowMeanMarkers--}
```
public abstract boolean getShowMeanMarkers()
```

Stellt Mittelwertmarker dar. True, wenn Mittelwertmarker im BoxAndWhisker-Diagramm angezeigt werden. Gilt nur für BoxAndWhisker-Diagramme. Lesen/Schreiben boolesch.

**Rückgabewert:**
boolean
### setShowMeanMarkers(boolean value) {#setShowMeanMarkers-boolean-}
```
public abstract void setShowMeanMarkers(boolean value)
```

Stellt Mittelwertmarker dar. True, wenn Mittelwertmarker im BoxAndWhisker-Diagramm angezeigt werden. Gilt nur für BoxAndWhisker-Diagramme. Lesen/Schreiben boolesch.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getShowMeanLine() {#getShowMeanLine--}
```
public abstract boolean getShowMeanLine()
```

Stellt Mittelwertmarker dar. True, wenn Mittelwertlinie im BoxAndWhisker-Diagramm angezeigt wird. Gilt nur für BoxAndWhisker-Diagramme. Lesen/Schreiben boolesch.

**Rückgabewert:**
boolean
### setShowMeanLine(boolean value) {#setShowMeanLine-boolean-}
```
public abstract void setShowMeanLine(boolean value)
```

Stellt Mittelwertmarker dar. True, wenn Mittelwertlinie im BoxAndWhisker-Diagramm angezeigt wird. Gilt nur für BoxAndWhisker-Diagramme. Lesen/Schreiben boolesch.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getQuartileMethod() {#getQuartileMethod--}
```
public abstract int getQuartileMethod()
```

Stellt Quartils-Methode dar. Gilt nur für BoxAndWhisker-Diagramme.

**Rückgabewert:**
int
### setQuartileMethod(int value) {#setQuartileMethod-int-}
```
public abstract void setQuartileMethod(int value)
```

Stellt Quartils-Methode dar. Gilt nur für BoxAndWhisker-Diagramme.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### getShowConnectorLines() {#getShowConnectorLines--}
```
public abstract boolean getShowConnectorLines()
```

Stellt Verbindungslinien dar. Gilt nur für Waterfall-Diagramme.

**Rückgabewert:**
boolean
### setShowConnectorLines(boolean value) {#setShowConnectorLines-boolean-}
```
public abstract void setShowConnectorLines(boolean value)
```

Stellt Verbindungslinien dar. Gilt nur für Waterfall-Diagramme.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getParentLabelLayout() {#getParentLabelLayout--}
```
public abstract int getParentLabelLayout()
```

Stellt Layout der übergeordneten Kategorielabels dar. Gilt nur für Treemap-Diagramme.

**Rückgabewert:**
int
### setParentLabelLayout(int value) {#setParentLabelLayout-int-}
```
public abstract void setParentLabelLayout(int value)
```

Stellt Layout der übergeordneten Kategorielabels dar. Gilt nur für Treemap-Diagramme.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public abstract int getBubbleSizeScale()
```

Gibt den Skalierungsfaktor für das Blasendiagramm an (kann zwischen 0 und 300 Prozent der Standardgröße liegen). Dies ist die Eigenschaft nicht nur dieser Serie, sondern aller Serien der übergeordneten Seriengruppe – dies ist eine Projektion der entsprechenden Gruppeneigenschaft. Daher ist diese Eigenschaft schreibgeschützt. Verwenden Sie die ParentSeriesGroup-Eigenschaft, um auf die übergeordnete Seriengruppe zuzugreifen. Verwenden Sie die ParentSeriesGroup.BubbleSizeScale-Lese/Schreib-Eigenschaft, um den Wert zu ändern.

--------------------

Dies ist die Projektion der Eigenschaft ParentSeriesGroup.BubbleSizeScale.

**Rückgabewert:**
int
### hasUpDownBars() {#hasUpDownBars--}
```
public abstract boolean hasUpDownBars()
```

Bestimmt, ob ein Linien- oder Kursdiagramm Aufwärts-/Abwärts-Balken hat. Dies ist die Eigenschaft nicht nur dieser Serie, sondern aller Serien der übergeordneten Seriengruppe – dies ist eine Projektion der entsprechenden Gruppeneigenschaft. Daher ist diese Eigenschaft schreibgeschützt. Verwenden Sie die ParentSeriesGroup-Eigenschaft, um auf die übergeordnete Seriengruppe zuzugreifen. Verwenden Sie die ParentSeriesGroup.UpDownBars.HasUpDownBars-Lese/Schreib-Eigenschaft, um den Wert zu ändern. Verwenden Sie die ParentSeriesGroup.UpDownBars-Eigenschaft, um Aufwärts-/Abwärts-Balken zu formatieren. Schreibgeschützt boolesch.

--------------------

Dies ist die Projektion der Eigenschaft ParentSeriesGroup.UpDownBars.HasUpDownBars.

**Rückgabewert:**
boolean
### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```

Gibt den Abstand zwischen Balken- oder Säulenclustern als Prozentsatz der Balken- bzw. Säulenbreite an. Dies ist die Eigenschaft nicht nur dieser Serie, sondern aller Serien der übergeordneten Seriengruppe – dies ist eine Projektion der entsprechenden Gruppeneigenschaft. Daher ist diese Eigenschaft schreibgeschützt. Verwenden Sie die ParentSeriesGroup-Eigenschaft, um auf die übergeordnete Seriengruppe zuzugreifen. Verwenden Sie die ParentSeriesGroup.GapWidth-Lese/Schreib-Eigenschaft, um den Wert zu ändern. Schreibgeschützt int.

--------------------

Dies ist die Projektion der Eigenschaft ParentSeriesGroup.GapWidth.

**Rückgabewert:**
int
### getGapDepth() {#getGapDepth--}
```
public abstract int getGapDepth()
```

Gibt den Abstand als Prozentsatz der Markierungsbreite zwischen den Datenserien in einem 3D-Diagramm zurück oder setzt ihn. Dies ist die Eigenschaft nicht nur dieser Serie, sondern aller Serien der übergeordneten Seriengruppe – dies ist eine Projektion der entsprechenden Gruppeneigenschaft. Daher ist diese Eigenschaft schreibgeschützt. Verwenden Sie die ParentSeriesGroup-Eigenschaft, um auf die übergeordnete Seriengruppe zuzugreifen. Verwenden Sie die ParentSeriesGroup.GapDepth-Lese/Schreib-Eigenschaft, um den Wert zu ändern. Schreibgeschützt int.

--------------------

Dies ist die Projektion der Eigenschaft ParentSeriesGroup.GapDepth.

**Rückgabewert:**
int
### isColorVaried() {#isColorVaried--}
```
public abstract boolean isColorVaried()
```

Gibt an, dass jeder Datenmarker in der Serie eine andere Farbe hat. Dies ist die Eigenschaft nicht nur dieser Serie, sondern aller Serien der übergeordneten Seriengruppe – dies ist eine Projektion der entsprechenden Gruppeneigenschaft. Daher ist diese Eigenschaft schreibgeschützt. Verwenden Sie die ParentSeriesGroup-Eigenschaft, um auf die übergeordnete Seriengruppe zuzugreifen. Verwenden Sie die ParentSeriesGroup.IsColorVaried-Lese/Schreib-Eigenschaft, um den Wert zu ändern. Schreibgeschützt boolesch.

--------------------

Dies ist die Projektion der Eigenschaft ParentSeriesGroup.IsColorVaried.

**Rückgabewert:**
boolean
### hasSeriesLines() {#hasSeriesLines--}
```
public abstract boolean hasSeriesLines()
```

Bestimmt, ob für diese Serie und verwandte Serien Serienlinien vorhanden sind. Dies ist die Eigenschaft nicht nur dieser Serie, sondern aller Serien der übergeordneten Seriengruppe – dies ist eine Projektion der entsprechenden Gruppeneigenschaft. Daher ist diese Eigenschaft schreibgeschützt. Verwenden Sie die ParentSeriesGroup-Eigenschaft, um auf die übergeordnete Seriengruppe zuzugreifen. Verwenden Sie die ParentSeriesGroup.HasSeriesLines-Lese/Schreib-Eigenschaft, um den Wert zu ändern. Verwenden Sie die ParentSeriesGroup.SeriesLinesFormat-Eigenschaft, um Serienlinien zu formatieren. Schreibgeschützt boolesch.

--------------------

Dies ist die Projektion der Eigenschaft ParentSeriesGroup.HasSeriesLines.

**Rückgabewert:**
boolean
### getOverlap() {#getOverlap--}
```
public abstract byte getOverlap()
```

Gibt an, wie stark Balken und Säulen in 2-D-Diagrammen überlappen, als Prozentsatz (von -100 % bis 100 %). Dies ist die Eigenschaft nicht nur dieser Serie, sondern aller Serien der übergeordneten Seriengruppe. Sie ist eine Projektion der entsprechenden Eigenschaft in der übergeordneten Seriengruppe und daher schreibgeschützt. Um den Wert zu ändern, verwenden Sie die ParentSeriesGroup.Overlap-Lese/Schreib-Eigenschaft. Schreibgeschützt byte.

--------------------

Overlap gibt den Grad der Überlappung bzw. des Abstands zwischen Balken und Säulen als Prozentsatz ihrer Breite an: - -100 %: Maximale Lücke (Balken sind vollständig getrennt). - 0 %: Balken werden nebeneinander ohne Überlappung oder Abstand platziert. - 100 %: Maximale Überlappung (Balken überlappen vollständig). Dies ist eine Projektion der Eigenschaft ParentSeriesGroup.Overlap.

**Rückgabewert:**
byte
### getSecondPieSize() {#getSecondPieSize--}
```
public abstract int getSecondPieSize()
```

Gibt die Größe des zweiten Kuchens oder Balkens eines Kuchen-zu-Kuchen- bzw. Balken-zu-Kuchen-Diagramms als Prozentsatz der Größe des ersten Kuchens an (kann zwischen 5 und 200 Prozent liegen). Dies ist die Eigenschaft nicht nur dieser Serie, sondern aller Serien der übergeordneten Seriengruppe – dies ist eine Projektion der entsprechenden Gruppeneigenschaft. Daher ist diese Eigenschaft schreibgeschützt. Verwenden Sie die ParentSeriesGroup-Eigenschaft, um auf die übergeordnete Seriengruppe zuzugreifen. Verwenden Sie die ParentSeriesGroup.SecondPieSize-Lese/Schreib-Eigenschaft, um den Wert zu ändern. Schreibgeschützt int.

--------------------

Dies ist die Projektion der Eigenschaft ParentSeriesGroup.SecondPieSize.

**Rückgabewert:**
int
### getPieSplitPosition() {#getPieSplitPosition--}
```
public abstract double getPieSplitPosition()
```

Gibt einen Wert an, der verwendet wird, um zu bestimmen, welche Datenpunkte im zweiten Kuchen oder Balken eines Kuchen-zu-Kuchen- bzw. Balken-zu-Kuchen-Diagramms liegen. Wird zusammen mit der PieSplitBy-Eigenschaft verwendet. Dies ist die Eigenschaft nicht nur dieser Serie, sondern aller Serien der übergeordneten Seriengruppe – dies ist eine Projektion der entsprechenden Gruppeneigenschaft. Daher ist diese Eigenschaft schreibgeschützt. Verwenden Sie die ParentSeriesGroup-Eigenschaft, um auf die übergeordnete Seriengruppe zuzugreifen. Verwenden Sie die ParentSeriesGroup.PieSplitPosition-Lese/Schreib-Eigenschaft, um den Wert zu ändern. Schreibgeschützt double.

--------------------

Dies ist die Projektion der Eigenschaft ParentSeriesGroup.PieSplitPosition.

**Rückgabewert:**
double
### getPieSplitBy() {#getPieSplitBy--}
```
public abstract int getPieSplitBy()
```

Gibt an, wie bestimmt wird, welche Datenpunkte im zweiten Kuchen oder Balken eines Kuchen-zu-Kuchen- bzw. Balken-zu-Kuchen-Diagramms liegen. Dies ist die Eigenschaft nicht nur dieser Serie, sondern aller Serien der übergeordneten Seriengruppe – dies ist eine Projektion der entsprechenden Gruppeneigenschaft. Daher ist diese Eigenschaft schreibgeschützt. Verwenden Sie die ParentSeriesGroup-Eigenschaft, um auf die übergeordnete Seriengruppe zuzugreifen. Verwenden Sie die ParentSeriesGroup.PieSplitBy-Lese/Schreib-Eigenschaft, um den Wert zu ändern. Schreibgeschützt [PieSplitType](../../com.aspose.slides/piesplittype).

--------------------

1) Dies ist die Projektion der Eigenschaft ParentSeriesGroup.PieSplitBy. 2) Wenn der Eigenschaftswert PieSplitType.Custom ist, können Sie benutzerdefinierte Split-Informationen mit der ParentSeriesGroup.PieSplitCustomPoints-Eigenschaft definieren.

**Rückgabewert:**
int
### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public abstract byte getDoughnutHoleSize()
```

Gibt die Größe des Lochs in einem Donut-Diagramm an (kann zwischen 10 und 90 Prozent der Plot-Flächengröße liegen). Dies ist die Eigenschaft nicht nur dieser Serie, sondern aller Serien der übergeordneten Seriengruppe – dies ist eine Projektion der entsprechenden Gruppeneigenschaft. Daher ist diese Eigenschaft schreibgeschützt. Verwenden Sie die ParentSeriesGroup-Eigenschaft, um auf die übergeordnete Seriengruppe zuzugreifen. Verwenden Sie die ParentSeriesGroup.DoughnutHoleSize-Lese/Schreib-Eigenschaft, um den Wert zu ändern. Schreibgeschützt byte.

--------------------

Dies ist die Projektion der Eigenschaft ParentSeriesGroup.DoughnutHoleSize.

**Rückgabewert:**
byte
### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public abstract int getFirstSliceAngle()
```

Gibt den Winkel des ersten Kuchen- oder Donut-Diagrammsegments in Grad an (im Uhrzeigersinn von oben, von 0 bis 360 Grad). Dies ist die Eigenschaft nicht nur dieser Serie, sondern aller Serien der übergeordneten Seriengruppe – dies ist eine Projektion der entsprechenden Gruppeneigenschaft. Daher ist diese Eigenschaft schreibgeschützt. Verwenden Sie die ParentSeriesGroup-Eigenschaft, um auf die übergeordnete Seriengruppe zuzugreifen. Verwenden Sie die ParentSeriesGroup.FirstSliceAngle-Lese/Schreib-Eigenschaft, um den Wert zu ändern. Schreibgeschützt int.

--------------------

Dies ist die Projektion der Eigenschaft ParentSeriesGroup.FirstSliceAngle.

**Rückgabewert:**
int
### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public abstract IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

Die benutzerdefinierten Split-Informationen für ein Kuchen-zu-Kuchen- oder Balken-zu-Kuchen-Diagramm mit benutzerdefiniertem Split. Enthält Datenpunkte, die im zweiten Kuchen oder Balken eines solchen Diagramms gezeichnet werden sollen. Dies ist die Eigenschaft nicht nur dieser Serie, sondern aller Serien der übergeordneten Seriengruppe – dies ist eine Projektion der entsprechenden Gruppeneigenschaft. Schreibgeschützt [IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection).

--------------------

Dies ist die Projektion der Eigenschaft ParentSeriesGroup.PieSplitCustomPoints.

**Rückgabewert:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)
### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public abstract int getBubbleSizeRepresentation()
```
Gibt an, wie die Werte der Blasengröße im Blasendiagramm dargestellt werden. Dies ist die Eigenschaft nicht nur dieser Serie, sondern aller Serien der übergeordneten Seriengruppe - dies ist die Projektion der entsprechenden Gruppeneigenschaft. Daher ist diese Eigenschaft schreibgeschützt. Verwenden Sie die ParentSeriesGroup-Eigenschaft, um auf die übergeordnete Seriengruppe zuzugreifen. Verwenden Sie die ParentSeriesGroup.BubbleSizeRepresentation Lese/Schreib-Eigenschaft, um den Wert zu ändern.

--------------------

Dies ist die Projektion der Eigenschaft ParentSeriesGroup.BubbleSizeRepresentation.

**Rückgabewert:**
int