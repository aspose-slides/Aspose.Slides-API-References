---
title: IChartSeries
second_title: Aspose.Slides für Android über die Java-API-Referenz
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
| [getExplosion()](#getExplosion--) | Der Abstand eines offenen Kuchenscheibchens vom Zentrum des Kreisdiagramms wird als Prozentsatz des Kreisdurchmessers angegeben. |
| [setExplosion(int value)](#setExplosion-int-) | Der Abstand eines offenen Kuchenscheibchens vom Zentrum des Kreisdiagramms wird als Prozentsatz des Kreisdurchmessers angegeben. |
| [getSmooth()](#getSmooth--) | Stellt Kurvenglättung dar. |
| [setSmooth(boolean value)](#setSmooth-boolean-) | Stellt Kurvenglättung dar. |
| [getMarker()](#getMarker--) | Gibt Serienmarker zurück. |
| [getBar3DShape()](#getBar3DShape--) | Gibt die Form einer Serie eines 3-D-Balkendiagramms an. |
| [setBar3DShape(int value)](#setBar3DShape-int-) | Gibt die Form einer Serie eines 3-D-Balkendiagramms an. |
| [getName()](#getName--) | Gibt Seriennamen zurück. |
| [getDataPoints()](#getDataPoints--) | Gibt die Sammlung von Datenpunkten dieser Serie zurück. |
| [getType()](#getType--) | Gibt einen Typ dieser Serie zurück. |
| [setType(int value)](#setType-int-) | Gibt einen Typ dieser Serie zurück. |
| [getParentSeriesGroup()](#getParentSeriesGroup--) | Gibt die übergeordnete Seriengruppe zurück. |
| [getFormat()](#getFormat--) | Gibt das Format einer Serie zurück. |
| [getOrder()](#getOrder--) | Gibt die Reihenfolge einer Serie zurück. |
| [setOrder(int value)](#setOrder-int-) | Gibt die Reihenfolge einer Serie zurück. |
| [getLabels()](#getLabels--) | Gibt die Bezeichnungen einer Serie zurück. |
| [getTrendLines()](#getTrendLines--) | Sammlung von Trendlinien der Serie Nur lesbar [ITrendlineCollection](../../com.aspose.slides/itrendlinecollection). |
| [getErrorBarsXFormat()](#getErrorBarsXFormat--) | Stellt ErrorBars der Serie mit Richtung X dar. |
| [getErrorBarsYFormat()](#getErrorBarsYFormat--) | Stellt ErrorBars der Serie mit Richtung Y dar. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Gibt an, ob diese Serie auf der zweiten Werteachse dargestellt wird. |
| [setPlotOnSecondAxis(boolean value)](#setPlotOnSecondAxis-boolean-) | Gibt an, ob diese Serie auf der zweiten Werteachse dargestellt wird. |
| [getNumberFormatOfValues()](#getNumberFormatOfValues--) | Gibt das Zahlenformat für Serienwerte zurück oder legt es fest. |
| [setNumberFormatOfValues(String value)](#setNumberFormatOfValues-java.lang.String-) | Gibt das Zahlenformat für Serienwerte zurück oder legt es fest. |
| [getNumberFormatOfXValues()](#getNumberFormatOfXValues--) | Gibt das Zahlenformat für Serien-x-Werte zurück oder legt es fest. |
| [setNumberFormatOfXValues(String value)](#setNumberFormatOfXValues-java.lang.String-) | Gibt das Zahlenformat für Serien-x-Werte zurück oder legt es fest. |
| [getNumberFormatOfYValues()](#getNumberFormatOfYValues--) | Gibt das Zahlenformat für Serien-y-Werte zurück oder legt es fest. |
| [setNumberFormatOfYValues(String value)](#setNumberFormatOfYValues-java.lang.String-) | Gibt das Zahlenformat für Serien-y-Werte zurück oder legt es fest. |
| [getNumberFormatOfBubbleSizes()](#getNumberFormatOfBubbleSizes--) | Gibt das Zahlenformat für Serien-Blasengrößen zurück oder legt es fest. |
| [setNumberFormatOfBubbleSizes(String value)](#setNumberFormatOfBubbleSizes-java.lang.String-) | Gibt das Zahlenformat für Serien-Blasengrößen zurück oder legt es fest. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Gibt an, dass die Balken-, Spalten- oder Blasensereien ihre Farben invertieren sollen, wenn der Wert negativ ist. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Gibt an, dass die Balken-, Spalten- oder Blasensereien ihre Farben invertieren sollen, wenn der Wert negativ ist. |
| [getInvertedSolidFillColor()](#getInvertedSolidFillColor--) | Gibt die invertierte Vollfarbe für die Serie an. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Stellt die Legendeneintragung dar, die mit dieser Serie verbunden ist Nur lesbar [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |
| [getAutomaticSeriesColor()](#getAutomaticSeriesColor--) | Gibt eine automatische Farbe der Serie basierend auf dem Serienindex und dem Diagrammstil zurück. |
| [getShowInnerPoints()](#getShowInnerPoints--) | Stellt innere Punkte dar. |
| [setShowInnerPoints(boolean value)](#setShowInnerPoints-boolean-) | Stellt innere Punkte dar. |
| [getShowOutlierPoints()](#getShowOutlierPoints--) | Stellt Ausreißerpunkte dar. |
| [setShowOutlierPoints(boolean value)](#setShowOutlierPoints-boolean-) | Stellt Ausreißerpunkte dar. |
| [getShowMeanMarkers()](#getShowMeanMarkers--) | Stellt Mittelwertsymbole dar. |
| [setShowMeanMarkers(boolean value)](#setShowMeanMarkers-boolean-) | Stellt Mittelwertsymbole dar. |
| [getShowMeanLine()](#getShowMeanLine--) | Stellt Mittelwertsymbole dar. |
| [setShowMeanLine(boolean value)](#setShowMeanLine-boolean-) | Stellt Mittelwertsymbole dar. |
| [getQuartileMethod()](#getQuartileMethod--) | Stellt Quartilsmethode dar. |
| [setQuartileMethod(int value)](#setQuartileMethod-int-) | Stellt Quartilsmethode dar. |
| [getShowConnectorLines()](#getShowConnectorLines--) | Stellt Verbindungslinien dar. |
| [setShowConnectorLines(boolean value)](#setShowConnectorLines-boolean-) | Stellt Verbindungslinien dar. |
| [getParentLabelLayout()](#getParentLabelLayout--) | Stellt das Layout der übergeordneten Kategorielabels dar. |
| [setParentLabelLayout(int value)](#setParentLabelLayout-int-) | Stellt das Layout der übergeordneten Kategorielabels dar. |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Gibt den Skalierungsfaktor für das Blasendiagramm an (kann zwischen 0 % und 300 % der Standardgröße liegen). |
| [hasUpDownBars()](#hasUpDownBars--) | Bestimmt, ob ein Linien- oder Kursdiagramm Auf-/Ab-Balken hat. |
| [getGapWidth()](#getGapWidth--) | Gibt den Abstand zwischen Balken- oder Spaltenclustern als Prozentsatz der Balken- oder Spaltenbreite an. |
| [getGapDepth()](#getGapDepth--) | Gibt den Abstand als Prozentsatz der Markerbreite zwischen den Datenserien in einem 3D-Diagramm zurück oder legt ihn fest. |
| [isColorVaried()](#isColorVaried--) | Gibt an, dass jeder Datenmarker in der Serie eine andere Farbe hat. |
| [hasSeriesLines()](#hasSeriesLines--) | Bestimmt, ob für diese Serie und verwandte Serien Serienlinien vorhanden sind. |
| [getOverlap()](#getOverlap--) | Gibt an, wie stark Balken und Spalten in 2-D-Diagrammen überlappen, als Prozentsatz (von –100 % bis 100 %). |
| [getSecondPieSize()](#getSecondPieSize--) | Gibt die Größe des zweiten Kreises oder Balkens eines Kreis-in-Kreis-Diagramms oder Balken-in-Kreis-Diagramms als Prozentsatz der Größe des ersten Kreises an (kann zwischen 5 % und 200 % liegen). |
| [getPieSplitPosition()](#getPieSplitPosition--) | Gibt einen Wert an, der zur Bestimmung verwendet wird, welche Datenpunkte im zweiten Kreis oder Balken eines Kreis-in-Kreis- oder Balken-in-Kreis-Diagramms liegen. |
| [getPieSplitBy()](#getPieSplitBy--) | Gibt an, wie bestimmt wird, welche Datenpunkte im zweiten Kreis oder Balken eines Kreis-in-Kreis- oder Balken-in-Kreis-Diagramms liegen. |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Gibt die Größe des Lochs in einem Donut-Diagramm an (kann zwischen 10 % und 90 % der Plotbereichsgröße liegen). |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | Gibt den Winkel des ersten Kreis- oder Donut-Diagrammscheibchens in Grad an (im Uhrzeigersinn von oben, von 0 bis 360 Grad). |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | Die benutzerdefinierten Trenninformationen für ein Kreis-in-Kreis- oder Balken-in-Kreis-Diagramm mit benutzerdefinierter Trennung. |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Gibt an, wie die Blasengrößenwerte im Blasendiagramm dargestellt werden. |
### getExplosion() {#getExplosion--}
```
public abstract int getExplosion()
```

Der Abstand eines offenen Kuchenscheibchens vom Zentrum des Kreisdiagramms wird als Prozentsatz des Kreisdurchmessers angegeben. Lesen/Schreiben int.

**Rückgabe:**
int
### setExplosion(int value) {#setExplosion-int-}
```
public abstract void setExplosion(int value)
```

Der Abstand eines offenen Kuchenscheibchens vom Zentrum des Kreisdiagramms wird als Prozentsatz des Kreisdurchmessers angegeben. Lesen/Schreiben int.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### getSmooth() {#getSmooth--}
```
public abstract boolean getSmooth()
```

Stellt Kurvenglättung dar. true, wenn Kurvenglättung für das Liniendiagramm oder Streudiagramm aktiviert ist. Gilt nur für Diagramme, bei denen Linien und Streuungen durch Linien verbunden sind. Lesen/Schreiben boolean.

**Rückgabe:**
boolean
### setSmooth(boolean value) {#setSmooth-boolean-}
```
public abstract void setSmooth(boolean value)
```

Stellt Kurvenglättung dar. true, wenn Kurvenglättung für das Liniendiagramm oder Streudiagramm aktiviert ist. Gilt nur für Diagramme, bei denen Linien und Streuungen durch Linien verbunden sind. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getMarker() {#getMarker--}
```
public abstract IMarker getMarker()
```

Gibt Serienmarker zurück. Nur lesbar [IMarker](../../com.aspose.slides/imarker).

**Rückgabe:**
[IMarker](../../com.aspose.slides/imarker)
### getBar3DShape() {#getBar3DShape--}
```
public abstract int getBar3DShape()
```

Gibt die Form einer Serie eines 3-D-Balkendiagramms an. Das Ändern dieses Werts kann automatisch den Typ der Serie ändern. Lesen/Schreiben [ChartShapeType](../../com.aspose.slides/chartshapetype).

**Rückgabe:**
int
### setBar3DShape(int value) {#setBar3DShape-int-}
```
public abstract void setBar3DShape(int value)
```

Gibt die Form einer Serie eines 3-D-Balkendiagramms an. Das Ändern dieses Werts kann automatisch den Typ der Serie ändern. Lesen/Schreiben [ChartShapeType](../../com.aspose.slides/chartshapetype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### getName() {#getName--}
```
public abstract IStringChartValue getName()
```

Gibt Seriennamen zurück. Nur lesbar [IStringChartValue](../../com.aspose.slides/istringchartvalue).

**Rückgabe:**
[IStringChartValue](../../com.aspose.slides/istringchartvalue)
### getDataPoints() {#getDataPoints--}
```
public abstract IChartDataPointCollection getDataPoints()
```

Gibt die Sammlung von Datenpunkten dieser Serie zurück. Nur lesbar [IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection).

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

Gibt die übergeordnete Seriengruppe zurück. Nur lesbar [IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup).

**Rückgabe:**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Gibt das Format einer Serie zurück. Nur lesbar [IFormat](../../com.aspose.slides/iformat).

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

Gibt die Bezeichnungen einer Serie zurück. Nur lesbar [IDataLabelCollection](../../com.aspose.slides/idatalabelcollection).

**Rückgabe:**
[IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)
### getTrendLines() {#getTrendLines--}
```
public abstract ITrendlineCollection getTrendLines()
```

Sammlung von Trendlinien der Serie Nur lesbar [ITrendlineCollection](../../com.aspose.slides/itrendlinecollection).

**Rückgabe:**
[ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)
### getErrorBarsXFormat() {#getErrorBarsXFormat--}
```
public abstract IErrorBarsFormat getErrorBarsXFormat()
```

Stellt ErrorBars der Serie mit Richtung X dar. Nur lesbar [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

ErrorBars mit X-Richtung sind für Serien vom Typ area, bar, scatter und bubble verfügbar. Für alle anderen Diagrammtypen gibt diese Eigenschaft null zurück (einschließlich 3D-Diagramme). Bei benutzerdefinierten Werten verwenden Sie die DataPoints-Sammlung, um den Wert festzulegen (mit der Eigenschaft ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues))).

**Rückgabe:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)
### getErrorBarsYFormat() {#getErrorBarsYFormat--}
```
public abstract IErrorBarsFormat getErrorBarsYFormat()
```

Stellt ErrorBars der Serie mit Richtung Y dar. Nur lesbar [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

ErrorBars mit Y-Richtung sind für Serien vom Typ area, bar, line, scatter und bubble verfügbar. Für alle anderen Diagrammtypen gibt diese Eigenschaft null zurück (einschließlich 3D-Diagramme). Bei benutzerdefinierten Werten verwenden Sie die DataPoints-Sammlung, um den Wert festzulegen (mit der Eigenschaft ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues))).

**Rückgabe:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)
### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public abstract boolean getPlotOnSecondAxis()
```

Gibt an, ob diese Serie auf der zweiten Werteachse dargestellt wird. Lesen/Schreiben boolean.

**Rückgabe:**
boolean
### setPlotOnSecondAxis(boolean value) {#setPlotOnSecondAxis-boolean-}
```
public abstract void setPlotOnSecondAxis(boolean value)
```

Gibt an, ob diese Serie auf der zweiten Werteachse dargestellt wird. Lesen/Schreiben boolean.

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

Gibt das Zahlenformat für Serien-x-Werte zurück oder legt es fest. Lesen/Schreiben String.

**Rückgabe:**
java.lang.String
### setNumberFormatOfXValues(String value) {#setNumberFormatOfXValues-java.lang.String-}
```
public abstract void setNumberFormatOfXValues(String value)
```

Gibt das Zahlenformat für Serien-x-Werte zurück oder legt es fest. Lesen/Schreiben String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |
### getNumberFormatOfYValues() {#getNumberFormatOfYValues--}
```
public abstract String getNumberFormatOfYValues()
```

Gibt das Zahlenformat für Serien-y-Werte zurück oder legt es fest. Lesen/Schreiben String.

**Rückgabe:**
java.lang.String
### setNumberFormatOfYValues(String value) {#setNumberFormatOfYValues-java.lang.String-}
```
public abstract void setNumberFormatOfYValues(String value)
```

Gibt das Zahlenformat für Serien-y-Werte zurück oder legt es fest. Lesen/Schreiben String.

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

Gibt an, dass die Balken-, Spalten- oder Blasensereien ihre Farben invertieren sollen, wenn der Wert negativ ist. Lesen/Schreiben boolean.

**Rückgabe:**
boolean
### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public abstract void setInvertIfNegative(boolean value)
```

Gibt an, dass die Balken-, Spalten- oder Blasensereien ihre Farben invertieren sollen, wenn der Wert negativ ist. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getInvertedSolidFillColor() {#getInvertedSolidFillColor--}
```
public abstract IColorFormat getInvertedSolidFillColor()
```

Gibt die invertierte Vollfarbe für die Serie an. Um die Farbe anzuwenden, setzen Sie den Serienformat-FillType auf FillType.Solid. Lesen/Schreiben [IColorFormat](../../com.aspose.slides/icolorformat).

**Rückgabe:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```

Stellt die Legendeneintragung dar, die mit dieser Serie verbunden ist Nur lesbar [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Rückgabe:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### getAutomaticSeriesColor() {#getAutomaticSeriesColor--}
```
public abstract Integer getAutomaticSeriesColor()
```

Gibt eine automatische Farbe der Serie basierend auf dem Serienindex und dem Diagrammstil zurück. Diese Farbe wird standardmäßig verwendet, wenn FillType gleich NotDefined ist.

**Rückgabe:**
java.lang.Integer - Automatische Farbe der Serie java.lang.Integer
### getShowInnerPoints() {#getShowInnerPoints--}
```
public abstract boolean getShowInnerPoints()
```

Stellt innere Punkte dar. true, wenn innere Punkte im BoxAndWhisker-Diagramm angezeigt werden. Gilt nur für BoxAndWhisker-Diagramme. Lesen/Schreiben boolean.

**Rückgabe:**
boolean
### setShowInnerPoints(boolean value) {#setShowInnerPoints-boolean-}
```
public abstract void setShowInnerPoints(boolean value)
```

Stellt innere Punkte dar. true, wenn innere Punkte im BoxAndWhisker-Diagramm angezeigt werden. Gilt nur für BoxAndWhisker-Diagramme. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getShowOutlierPoints() {#getShowOutlierPoints--}
```
public abstract boolean getShowOutlierPoints()
```

Stellt Ausreißerpunkte dar. true, wenn Ausreißerpunkte im BoxAndWhisker-Diagramm angezeigt werden. Gilt nur für BoxAndWhisker-Diagramme. Lesen/Schreiben boolean.

**Rückgabe:**
boolean
### setShowOutlierPoints(boolean value) {#setShowOutlierPoints-boolean-}
```
public abstract void setShowOutlierPoints(boolean value)
```

Stellt Ausreißerpunkte dar. true, wenn Ausreißerpunkte im BoxAndWhisker-Diagramm angezeigt werden. Gilt nur für BoxAndWhisker-Diagramme. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getShowMeanMarkers() {#getShowMeanMarkers--}
```
public abstract boolean getShowMeanMarkers()
```

Stellt Mittelwertsymbole dar. true, wenn Mittelwertsymbole im BoxAndWhisker-Diagramm angezeigt werden. Gilt nur für BoxAndWhisker-Diagramme. Lesen/Schreiben boolean.

**Rückgabe:**
boolean
### setShowMeanMarkers(boolean value) {#setShowMeanMarkers-boolean-}
```
public abstract void setShowMeanMarkers(boolean value)
```

Stellt Mittelwertsymbole dar. true, wenn Mittelwertsymbole im BoxAndWhisker-Diagramm angezeigt werden. Gilt nur für BoxAndWhisker-Diagramme. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getShowMeanLine() {#getShowMeanLine--}
```
public abstract boolean getShowMeanLine()
```

Stellt Mittelwertsymbole dar. true, wenn Mittelwertlinie im BoxAndWhisker-Diagramm angezeigt wird. Gilt nur für BoxAndWhisker-Diagramme. Lesen/Schreiben boolean.

**Rückgabe:**
boolean
### setShowMeanLine(boolean value) {#setShowMeanLine-boolean-}
```
public abstract void setShowMeanLine(boolean value)
```

Stellt Mittelwertsymbole dar. true, wenn Mittelwertlinie im BoxAndWhisker-Diagramm angezeigt wird. Gilt nur für BoxAndWhisker-Diagramme. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getQuartileMethod() {#getQuartileMethod--}
```
public abstract int getQuartileMethod()
```

Stellt Quartilsmethode dar. Gilt nur für BoxAndWhisker-Diagramme.

**Rückgabe:**
int
### setQuartileMethod(int value) {#setQuartileMethod-int-}
```
public abstract void setQuartileMethod(int value)
```

Stellt Quartilsmethode dar. Gilt nur für BoxAndWhisker-Diagramme.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### getShowConnectorLines() {#getShowConnectorLines--}
```
public abstract boolean getShowConnectorLines()
```

Stellt Verbindungslinien dar. Gilt nur für Waterfall-Diagramme.

**Rückgabe:**
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

Stellt das Layout der übergeordneten Kategorielabels dar. Gilt nur für Treemap-Diagramme.

**Rückgabe:**
int
### setParentLabelLayout(int value) {#setParentLabelLayout-int-}
```
public abstract void setParentLabelLayout(int value)
```

Stellt das Layout der übergeordneten Kategorielabels dar. Gilt nur für Treemap-Diagramme.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public abstract int getBubbleSizeScale()
```

Gibt den Skalierungsfaktor für das Blasendiagramm an (kann zwischen 0 % und 300 % der Standardgröße liegen). Diese Eigenschaft gilt nicht nur für diese Serie, sondern für alle Serien der übergeordneten Seriengruppe – sie ist eine Projektion der entsprechenden Gruppeneigenschaft. Daher ist sie nur lesbar. Verwenden Sie die Eigenschaft ParentSeriesGroup, um auf die übergeordnete Seriengruppe zuzugreifen. Verwenden Sie ParentSeriesGroup.BubbleSizeScale, um den Wert zu ändern.

--------------------

Dies ist die Projektion der Eigenschaft ParentSeriesGroup.BubbleSizeScale.

**Rückgabe:**
int
### hasUpDownBars() {#hasUpDownBars--}
```
public abstract boolean hasUpDownBars()
```

Bestimmt, ob ein Linien- oder Kursdiagramm Auf-/Ab-Balken hat. Diese Eigenschaft gilt nicht nur für diese Serie, sondern für alle Serien der übergeordneten Seriengruppe – sie ist eine Projektion der entsprechenden Gruppeneigenschaft. Daher ist sie nur lesbar. Verwenden Sie die Eigenschaft ParentSeriesGroup, um auf die übergeordnete Seriengruppe zuzugreifen. Verwenden Sie ParentSeriesGroup.UpDownBars.HasUpDownBars, um den Wert zu ändern. Verwenden Sie ParentSeriesGroup.UpDownBars, um die Auf-/Ab-Balken zu formatieren. Nur lesbar boolean.

--------------------

Dies ist die Projektion der Eigenschaft ParentSeriesGroup.UpDownBars.HasUpDownBars.

**Rückgabe:**
boolean
### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```

Gibt den Abstand zwischen Balken- oder Spaltenclustern als Prozentsatz der Balken- oder Spaltenbreite an. Diese Eigenschaft gilt nicht nur für diese Serie, sondern für alle Serien der übergeordneten Seriengruppe – sie ist eine Projektion der entsprechenden Gruppeneigenschaft. Daher ist sie nur lesbar. Verwenden Sie die Eigenschaft ParentSeriesGroup, um auf die übergeordnete Seriengruppe zuzugreifen. Verwenden Sie ParentSeriesGroup.GapWidth, um den Wert zu ändern. Nur lesbar int.

--------------------

Dies ist die Projektion der Eigenschaft ParentSeriesGroup.GapWidth.

**Rückgabe:**
int
### getGapDepth() {#getGapDepth--}
```
public abstract int getGapDepth()
```

Gibt den Abstand als Prozentsatz der Markerbreite zwischen den Datenserien in einem 3D-Diagramm zurück oder legt ihn fest. Diese Eigenschaft gilt nicht nur für diese Serie, sondern für alle Serien der übergeordneten Seriengruppe – sie ist eine Projektion der entsprechenden Gruppeneigenschaft. Daher ist sie nur lesbar. Verwenden Sie die Eigenschaft ParentSeriesGroup, um auf die übergeordnete Seriengruppe zuzugreifen. Verwenden Sie ParentSeriesGroup.GapDepth, um den Wert zu ändern. Nur lesbar int.

--------------------

Dies ist die Projektion der Eigenschaft ParentSeriesGroup.GapDepth.

**Rückgabe:**
int
### isColorVaried() {#isColorVaried--}
```
public abstract boolean isColorVaried()
```

Gibt an, dass jeder Datenmarker in der Serie eine andere Farbe hat. Diese Eigenschaft gilt nicht nur für diese Serie, sondern für alle Serien der übergeordneten Seriengruppe – sie ist eine Projektion der entsprechenden Gruppeneigenschaft. Daher ist sie nur lesbar. Verwenden Sie die Eigenschaft ParentSeriesGroup, um auf die übergeordnete Seriengruppe zuzugreifen. Verwenden Sie ParentSeriesGroup.IsColorVaried, um den Wert zu ändern. Nur lesbar boolean.

--------------------

Dies ist die Projektion der Eigenschaft ParentSeriesGroup.IsColorVaried.

**Rückgabe:**
boolean
### hasSeriesLines() {#hasSeriesLines--}
```
public abstract boolean hasSeriesLines()
```

Bestimmt, ob für diese Serie und verwandte Serien Serienlinien vorhanden sind. Diese Eigenschaft gilt nicht nur für diese Serie, sondern für alle Serien der übergeordneten Seriengruppe – sie ist eine Projektion der entsprechenden Gruppeneigenschaft. Daher ist sie nur lesbar. Verwenden Sie die Eigenschaft ParentSeriesGroup, um auf die übergeordnete Seriengruppe zuzugreifen. Verwenden Sie ParentSeriesGroup.HasSeriesLines, um den Wert zu ändern. Verwenden Sie ParentSeriesGroup.SeriesLinesFormat, um Serienlinien zu formatieren. Nur lesbar boolean.

--------------------

Dies ist die Projektion der Eigenschaft ParentSeriesGroup.HasSeriesLines.

**Rückgabe:**
boolean
### getOverlap() {#getOverlap--}
```
public abstract byte getOverlap()
```

Gibt an, wie stark Balken und Spalten in 2-D-Diagrammen überlappen, als Prozentsatz (von –100 % bis 100 %). Diese Eigenschaft gilt nicht nur für diese Serie, sondern für alle Serien der übergeordneten Seriengruppe. Sie ist eine Projektion der entsprechenden Eigenschaft in der übergeordneten Seriengruppe und daher nur lesbar. Zum Ändern des Werts verwenden Sie die Eigenschaft ParentSeriesGroup.Overlap. Nur lesbar byte.

--------------------

Overlap gibt den Grad der Überlappung bzw. des Abstands zwischen Balken und Spalten als Prozentsatz ihrer Breite an:
- –100 %: maximaler Abstand (Balken sind völlig getrennt).
- 0 %: Balken liegen nebeneinander ohne Überlappung oder Abstand.
- 100 %: maximale Überlappung (Balken überlagern sich vollständig). Dies ist eine Projektion der Eigenschaft ParentSeriesGroup.Overlap.

**Rückgabe:**
byte
### getSecondPieSize() {#getSecondPieSize--}
```
public abstract int getSecondPieSize()
```

Gibt die Größe des zweiten Kreises oder Balkens eines Kreis-in-Kreis- oder Balken-in-Kreis-Diagramms als Prozentsatz der Größe des ersten Kreises an (kann zwischen 5 % und 200 % liegen). Diese Eigenschaft gilt nicht nur für diese Serie, sondern für alle Serien der übergeordneten Seriengruppe – sie ist eine Projektion der entsprechenden Gruppeneigenschaft. Daher ist sie nur lesbar. Verwenden Sie die Eigenschaft ParentSeriesGroup, um auf die übergeordnete Seriengruppe zuzugreifen. Verwenden Sie ParentSeriesGroup.SecondPieSize, um den Wert zu ändern. Nur lesbar int.

--------------------

Dies ist die Projektion der Eigenschaft ParentSeriesGroup.SecondPieSize.

**Rückgabe:**
int
### getPieSplitPosition() {#getPieSplitPosition--}
```
public abstract double getPieSplitPosition()
```

Gibt einen Wert an, der zur Bestimmung verwendet wird, welche Datenpunkte im zweiten Kreis oder Balken eines Kreis-in-Kreis- oder Balken-in-Kreis-Diagramms liegen. Wird zusammen mit der Eigenschaft PieSplitBy verwendet. Diese Eigenschaft gilt nicht nur für diese Serie, sondern für alle Serien der übergeordneten Seriengruppe – sie ist eine Projektion der entsprechenden Gruppeneigenschaft. Daher ist sie nur lesbar. Verwenden Sie die Eigenschaft ParentSeriesGroup, um auf die übergeordnete Seriengruppe zuzugreifen. Verwenden Sie ParentSeriesGroup.PieSplitPosition, um den Wert zu ändern. Nur lesbar double.

--------------------

Dies ist die Projektion der Eigenschaft ParentSeriesGroup.PieSplitPosition.

**Rückgabe:**
double
### getPieSplitBy() {#getPieSplitBy--}
```
public abstract int getPieSplitBy()
```

Gibt an, wie bestimmt wird, welche Datenpunkte im zweiten Kreis oder Balken eines Kreis-in-Kreis- oder Balken-in-Kreis-Diagramms liegen. Diese Eigenschaft gilt nicht nur für diese Serie, sondern für alle Serien der übergeordneten Seriengruppe – sie ist eine Projektion der entsprechenden Gruppeneigenschaft. Daher ist sie nur lesbar. Verwenden Sie die Eigenschaft ParentSeriesGroup, um auf die übergeordnete Seriengruppe zuzugreifen. Verwenden Sie ParentSeriesGroup.PieSplitBy, um den Wert zu ändern. Nur lesbar [PieSplitType](../../com.aspose.slides/piesplittype).

--------------------

1) Dies ist die Projektion der Eigenschaft ParentSeriesGroup.PieSplitBy. 2) Wenn der Eigenschaftswert PieSplitType.Custom ist, können Sie benutzerdefinierte Trenninformationen mit der Eigenschaft ParentSeriesGroup.PieSplitCustomPoints definieren.

**Rückgabe:**
int
### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public abstract byte getDoughnutHoleSize()
```

Gibt die Größe des Lochs in einem Donut-Diagramm an (kann zwischen 10 % und 90 % der Plotbereichsgröße liegen). Diese Eigenschaft gilt nicht nur für diese Serie, sondern für alle Serien der übergeordneten Seriengruppe – sie ist eine Projektion der entsprechenden Gruppeneigenschaft. Daher ist sie nur lesbar. Verwenden Sie die Eigenschaft ParentSeriesGroup, um auf die übergeordnete Seriengruppe zuzugreifen. Verwenden Sie ParentSeriesGroup.DoughnutHoleSize, um den Wert zu ändern. Nur lesbar byte.

--------------------

Dies ist die Projektion der Eigenschaft ParentSeriesGroup.DoughnutHoleSize.

**Rückgabe:**
byte
### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public abstract int getFirstSliceAngle()
```

Gibt den Winkel des ersten Kreis- oder Donut-Diagrammscheibchens in Grad an (im Uhrzeigersinn von oben, von 0 bis 360 Grad). Diese Eigenschaft gilt nicht nur für diese Serie, sondern für alle Serien der übergeordneten Seriengruppe – sie ist eine Projektion der entsprechenden Gruppeneigenschaft. Daher ist sie nur lesbar. Verwenden Sie die Eigenschaft ParentSeriesGroup, um auf die übergeordnete Seriengruppe zuzugreifen. Verwenden Sie ParentSeriesGroup.FirstSliceAngle, um den Wert zu ändern. Nur lesbar int.

--------------------

Dies ist die Projektion der Eigenschaft ParentSeriesGroup.FirstSliceAngle.

**Rückgabe:**
int
### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public abstract IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

Die benutzerdefinierten Trenninformationen für ein Kreis-in-Kreis- oder Balken-in-Kreis-Diagramm mit benutzerdefinierter Trennung. Enthält Datenpunkte, die im zweiten Kreis oder Balken eines Kreis-in-Kreis- oder Balken-in-Kreis-Diagramms gezeichnet werden sollen. Diese Eigenschaft gilt nicht nur für diese Serie, sondern für alle Serien der übergeordneten Seriengruppe – sie ist eine Projektion der entsprechenden Gruppeneigenschaft Nur lesbar [IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection).

--------------------

Dies ist die Projektion der Eigenschaft ParentSeriesGroup.PieSplitCustomPoints.

**Rückgabe:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)
### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public abstract int getBubbleSizeRepresentation()
```

Gibt an, wie die Blasengrößenwerte im Blasendiagramm dargestellt werden. Diese Eigenschaft gilt nicht nur für diese Serie, sondern für alle Serien der übergeordneten Seriengruppe – sie ist eine Projektion der entsprechenden Gruppeneigenschaft. Daher ist sie nur lesbar. Verwenden Sie die Eigenschaft ParentSeriesGroup, um auf die übergeordnete Seriengruppe zuzugreifen. Verwenden Sie ParentSeriesGroup.BubbleSizeRepresentation, um den Wert zu ändern.

--------------------

Dies ist die Projektion der Eigenschaft ParentSeriesGroup.BubbleSizeRepresentation.

**Rückgabe:**
int