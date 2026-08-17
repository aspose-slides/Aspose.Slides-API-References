---
title: ChartSeries
second_title: Aspose.Slides für Java API Referenz
description: Stellt eine Diagrammserie dar.
type: docs
url: /de/com.aspose.slides/chartseries/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IChartSeries](../../com.aspose.slides/ichartseries), com.aspose.slides.IDOMObject
```
public class ChartSeries implements IChartSeries, IDOMObject
```

Stellt eine Diagrammserie dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | Gibt das übergeordnete Diagramm zurück. |
| [getExplosion()](#getExplosion--) | Der Abstand eines offenen Kuchenscheibens vom Zentrum des Kreisdiagramms wird als Prozentsatz des Durchmessers angegeben. |
| [setExplosion(int value)](#setExplosion-int-) | Der Abstand eines offenen Kuchenscheibens vom Zentrum des Kreisdiagramms wird als Prozentsatz des Durchmessers angegeben. |
| [getSmooth()](#getSmooth--) | Stellt Kurvensglättung dar. |
| [setSmooth(boolean value)](#setSmooth-boolean-) | Stellt Kurvensglättung dar. |
| [getName()](#getName--) | Gibt den Namen der Serie zurück. |
| [getDataPoints()](#getDataPoints--) | Gibt die Sammlung von Datenpunkten dieser Serie zurück. |
| [getType()](#getType--) | Gibt einen Typ dieser Serie zurück. |
| [setType(int value)](#setType-int-) | Gibt einen Typ dieser Serie zurück. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Gibt an, ob diese Serie auf der Sekundärachse geplottet wird. |
| [setPlotOnSecondAxis(boolean value)](#setPlotOnSecondAxis-boolean-) | Gibt an, ob diese Serie auf der Sekundärachse geplottet wird. |
| [getParentSeriesGroup()](#getParentSeriesGroup--) | ParentSeriesGroup. |
| [getFormat()](#getFormat--) | Gibt das Format einer Serie zurück. |
| [getOrder()](#getOrder--) | Gibt die Reihenfolge einer Serie zurück. |
| [setOrder(int value)](#setOrder-int-) | Gibt die Reihenfolge einer Serie zurück. |
| [getLabels()](#getLabels--) | Gibt die Labels einer Serie zurück. |
| [getTrendLines()](#getTrendLines--) | Sammlung von Trendlinien der Serie. |
| [getErrorBarsXFormat()](#getErrorBarsXFormat--) | Stellt ErrorBars der Serie mit Richtung X dar. |
| [getErrorBarsYFormat()](#getErrorBarsYFormat--) | Stellt ErrorBars der Serie mit Richtung Y dar. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Stellt Legendeneintrag, der mit dieser Serie verbunden ist, dar Nur-Lesen [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |
| [getNumberFormatOfValues()](#getNumberFormatOfValues--) | NumberFormatOfValues. |
| [setNumberFormatOfValues(String value)](#setNumberFormatOfValues-java.lang.String-) | NumberFormatOfValues. |
| [getNumberFormatOfXValues()](#getNumberFormatOfXValues--) | NumberFormatOfXValues. |
| [setNumberFormatOfXValues(String value)](#setNumberFormatOfXValues-java.lang.String-) | NumberFormatOfXValues. |
| [getNumberFormatOfYValues()](#getNumberFormatOfYValues--) | NumberFormatOfYValues. |
| [setNumberFormatOfYValues(String value)](#setNumberFormatOfYValues-java.lang.String-) | NumberFormatOfYValues. |
| [getNumberFormatOfBubbleSizes()](#getNumberFormatOfBubbleSizes--) | NumberFormatOfBubbleSizes. |
| [setNumberFormatOfBubbleSizes(String value)](#setNumberFormatOfBubbleSizes-java.lang.String-) | NumberFormatOfBubbleSizes. |
| [getMarker()](#getMarker--) | Marker. |
| [getBar3DShape()](#getBar3DShape--) | Gibt die Form einer Serie eines 3-D-Säulendiagramms an. |
| [setBar3DShape(int value)](#setBar3DShape-int-) | Gibt die Form einer Serie eines 3-D-Säulendiagramms an. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Gibt an, dass die Balken-, Säulen- oder Blasensereien ihre Farben invertieren sollen, wenn der Wert negativ ist. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Gibt an, dass die Balken-, Säulen- oder Blasensereien ihre Farben invertieren sollen, wenn der Wert negativ ist. |
| [getInvertedSolidFillColor()](#getInvertedSolidFillColor--) | Gibt die invertierte Vollfarbe für eine Serie an. |
| [getAutomaticSeriesColor()](#getAutomaticSeriesColor--) | Gibt eine automatische Farbe einer Serie zurück, basierend auf dem Serienindex und dem Diagrammstil. |
| [getShowInnerPoints()](#getShowInnerPoints--) | Stellt innere Punkte dar. |
| [setShowInnerPoints(boolean value)](#setShowInnerPoints-boolean-) | Stellt innere Punkte dar. |
| [getShowOutlierPoints()](#getShowOutlierPoints--) | Stellt Ausreißerpunkte dar. |
| [setShowOutlierPoints(boolean value)](#setShowOutlierPoints-boolean-) | Stellt Ausreißerpunkte dar. |
| [getShowMeanMarkers()](#getShowMeanMarkers--) | Stellt Mittelwertmarker dar. |
| [setShowMeanMarkers(boolean value)](#setShowMeanMarkers-boolean-) | Stellt Mittelwertmarker dar. |
| [getShowMeanLine()](#getShowMeanLine--) | Stellt Mittelwertlinie dar. |
| [setShowMeanLine(boolean value)](#setShowMeanLine-boolean-) | Stellt Mittelwertlinie dar. |
| [getQuartileMethod()](#getQuartileMethod--) | Stellt Quartilmethode dar. |
| [setQuartileMethod(int value)](#setQuartileMethod-int-) | Stellt Quartilmethode dar. |
| [getShowConnectorLines()](#getShowConnectorLines--) | Stellt Verbindungslinien dar. |
| [setShowConnectorLines(boolean value)](#setShowConnectorLines-boolean-) | Stellt Verbindungslinien dar. |
| [getParentLabelLayout()](#getParentLabelLayout--) | Stellt Layout der übergeordneten Kategorielabels dar. |
| [setParentLabelLayout(int value)](#setParentLabelLayout-int-) | Stellt Layout der übergeordneten Kategorielabels dar. |
| [hasUpDownBars()](#hasUpDownBars--) | Bestimmt, ob ein Linien- oder Aktien-Diagramm Auf-/Abwärts-Balken hat. |
| [getGapWidth()](#getGapWidth--) | Gibt den Abstand zwischen Balken- oder Säulenclustern als Prozentsatz der Balken- oder Säulenbreite an. |
| [getGapDepth()](#getGapDepth--) | Gibt den Abstand zurück oder legt ihn fest, als Prozentsatz der Markierungsbreite, zwischen den Datenserien in einem 3D-Diagramm. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | Gibt den Winkel des ersten Kuchen- oder Donut-Abschnitts in Grad an (im Uhrzeigersinn von oben, von 0 bis 360 Grad). |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Gibt die Größe des Lochs in einem Donut-Diagramm an (kann zwischen 10 und 90 Prozent der Größe des Plotbereichs liegen). |
| [getOverlap()](#getOverlap--) | Gibt an, wie stark Balken und Säulen in 2-D-Diagrammen überlappen, als Prozentsatz (von -100% bis 100%). |
| [getSecondPieSize()](#getSecondPieSize--) | Gibt die Größe des zweiten Kuchens oder Balkens eines Pie-of-Pie- oder Bar-of-Pie-Diagramms als Prozentsatz der Größe des ersten Kuchens an (kann zwischen 5 und 200 Prozent liegen). |
| [hasSeriesLines()](#hasSeriesLines--) | Bestimmt, ob es Serienlinien für diese Serie und verwandte Serien gibt. |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Gibt an, wie die Werte der Blasengrößen im Blasendiagramm dargestellt werden. |
| [getPieSplitPosition()](#getPieSplitPosition--) | Gibt einen Wert an, der verwendet wird, um zu bestimmen, welche Datenpunkte im zweiten Kuchen oder Balken eines Pie-of-Pie- oder Bar-of-Pie-Diagramms liegen. |
| [getPieSplitBy()](#getPieSplitBy--) | Gibt an, wie zu bestimmen ist, welche Datenpunkte im zweiten Kuchen oder Balken eines Pie-of-Pie- oder Bar-of-Pie-Diagramms liegen. |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | Die benutzerdefinierten Split-Informationen für ein Pie-of-Pie- oder Bar-of-Pie-Diagramm mit benutzerdefiniertem Split. |
| [isColorVaried()](#isColorVaried--) | Gibt an, dass jeder Datenmarker in der Serie eine andere Farbe hat. |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Gibt den Skalierungsfaktor für das Blasendiagramm an (kann zwischen 0 und 300 Prozent der Standardgröße liegen). |
| [getSlide()](#getSlide--) | Gibt die übergeordnete Folie eines FillFormat zurück. |
| [getPresentation()](#getPresentation--) | Gibt die übergeordnete Präsentation eines FillFormat zurück. |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Gibt ein Parent_Immediate-Objekt zurück. Nur-Lesen IDOMObject.

**Rückgabe:**
com.aspose.slides.IDOMObject
### getChart() {#getChart--}
```
public final IChart getChart()
```

Gibt das übergeordnete Diagramm zurück. Nur-Lesen [IChart](../../com.aspose.slides/ichart).

**Rückgabe:**
[IChart](../../com.aspose.slides/ichart)
### getExplosion() {#getExplosion--}
```
public final int getExplosion()
```

Der Abstand eines offenen Kuchenscheibens vom Zentrum des Kreisdiagramms wird als Prozentsatz des Durchmessers angegeben. Lesen/Schreiben int.

**Rückgabe:**
int
### setExplosion(int value) {#setExplosion-int-}
```
public final void setExplosion(int value)
```

Der Abstand eines offenen Kuchenscheibens vom Zentrum des Kreisdiagramms wird als Prozentsatz des Durchmessers angegeben. Lesen/Schreiben int.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### getSmooth() {#getSmooth--}
```
public final boolean getSmooth()
```

Stellt Kurvensglättung dar. True, wenn die Kurvensglättung für das Liniendiagramm oder Streudiagramm aktiviert ist. Gilt nur für Linien- und Streudiagramme, die durch Linien verbunden sind. Lesen/Schreiben boolean.

**Rückgabe:**
boolean
### setSmooth(boolean value) {#setSmooth-boolean-}
```
public final void setSmooth(boolean value)
```

Stellt Kurvensglättung dar. True, wenn die Kurvensglättung für das Liniendiagramm oder Streudiagramm aktiviert ist. Gilt nur für Linien- und Streudiagramme, die durch Linien verbunden sind. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getName() {#getName--}
```
public final IStringChartValue getName()
```

Gibt den Namen der Serie zurück. Nur-Lesen [IStringChartValue](../../com.aspose.slides/istringchartvalue).

**Rückgabe:**
[IStringChartValue](../../com.aspose.slides/istringchartvalue)
### getDataPoints() {#getDataPoints--}
```
public final IChartDataPointCollection getDataPoints()
```

Gibt die Sammlung von Datenpunkten dieser Serie zurück. Nur-Lesen [IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection).

**Rückgabe:**
[IChartDataPointCollection](../../com.aspose.slides/ichartdatapointcollection)
### getType() {#getType--}
```
public final int getType()
```

Gibt einen Typ dieser Serie zurück. Lesen/Schreiben [ChartType](../../com.aspose.slides/charttype).

**Rückgabe:**
int
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

Gibt einen Typ dieser Serie zurück. Lesen/Schreiben [ChartType](../../com.aspose.slides/charttype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public final boolean getPlotOnSecondAxis()
```

Gibt an, ob diese Serie auf der Sekundärachse geplottet wird. Lesen/Schreiben boolean.

**Rückgabe:**
boolean
### setPlotOnSecondAxis(boolean value) {#setPlotOnSecondAxis-boolean-}
```
public final void setPlotOnSecondAxis(boolean value)
```

Gibt an, ob diese Serie auf der Sekundärachse geplottet wird. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getParentSeriesGroup() {#getParentSeriesGroup--}
```
public final IChartSeriesGroup getParentSeriesGroup()
```

ParentSeriesGroup. Nur-Lesen [IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup).

**Rückgabe:**
[IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup)
### getFormat() {#getFormat--}
```
public final IFormat getFormat()
```

Gibt das Format einer Serie zurück. Nur-Lesen [IFormat](../../com.aspose.slides/iformat).

**Rückgabe:**
[IFormat](../../com.aspose.slides/iformat)
### getOrder() {#getOrder--}
```
public final int getOrder()
```

Gibt die Reihenfolge einer Serie zurück. Lesen/Schreiben int.

**Rückgabe:**
int
### setOrder(int value) {#setOrder-int-}
```
public final void setOrder(int value)
```

Gibt die Reihenfolge einer Serie zurück. Lesen/Schreiben int.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### getLabels() {#getLabels--}
```
public final IDataLabelCollection getLabels()
```

Gibt die Labels einer Serie zurück. Nur-Lesen [IDataLabelCollection](../../com.aspose.slides/idatalabelcollection).

**Rückgabe:**
[IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)
### getTrendLines() {#getTrendLines--}
```
public final ITrendlineCollection getTrendLines()
```

Sammlung von Trendlinien der Serie. Nur-Lesen [ITrendlineCollection](../../com.aspose.slides/itrendlinecollection).

--------------------

TrendLines sind für Datenserien in nicht gestapelten 2-D-Flächen-, Balken-, Säulen-, Linien-, Aktien-, XY- (Streudiagramm) und Blasendiagrammen verfügbar (nicht null). Trendlinien sind für Datenserien in gestapelten oder 3-D-Diagrammen nicht verfügbar. Trendlinien sind zudem für Radar-, Kuchen-, Oberflächen- oder Donut-Diagramme nicht verfügbar.

**Rückgabe:**
[ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)
### getErrorBarsXFormat() {#getErrorBarsXFormat--}
```
public final IErrorBarsFormat getErrorBarsXFormat()
```

Stellt ErrorBars der Serie mit Richtung X dar. Nur-Lesen [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

ErrorBars mit X-Richtung sind für Serien vom Typ Fläche, Balken, Streuung und Blase verfügbar. Für alle anderen Diagrammtypen gibt diese Eigenschaft null zurück (einschließlich 3-D-Diagrammen). Bei benutzerdefinierten Werten verwenden Sie die DataPoints-Sammlung, um den Wert (mit ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) Eigenschaft) anzugeben.

**Rückgabe:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)
### getErrorBarsYFormat() {#getErrorBarsYFormat--}
```
public final IErrorBarsFormat getErrorBarsYFormat()
```

Stellt ErrorBars der Serie mit Richtung Y dar. Nur-Lesen [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

ErrorBars mit Y-Richtung sind für Serien vom Typ Fläche, Balken, Linie, Streuung und Blase verfügbar. Für alle anderen Diagrammtypen gibt diese Eigenschaft null zurück (einschließlich 3-D-Diagrammen). Bei benutzerdefinierten Werten verwenden Sie die DataPoints-Sammlung, um den Wert (mit ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues)) Eigenschaft) anzugeben.

**Rückgabe:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)
### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```

Stellt Legendeneintrag, der mit dieser Serie verbunden ist, dar Nur-Lesen [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Rückgabe:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### getNumberFormatOfValues() {#getNumberFormatOfValues--}
```
public final String getNumberFormatOfValues()
```

NumberFormatOfValues. Lesen/Schreiben String.

**Rückgabe:**
java.lang.String
### setNumberFormatOfValues(String value) {#setNumberFormatOfValues-java.lang.String-}
```
public final void setNumberFormatOfValues(String value)
```

NumberFormatOfValues. Lesen/Schreiben String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |
### getNumberFormatOfXValues() {#getNumberFormatOfXValues--}
```
public final String getNumberFormatOfXValues()
```

NumberFormatOfXValues. Lesen/Schreiben String.

**Rückgabe:**
java.lang.String
### setNumberFormatOfXValues(String value) {#setNumberFormatOfXValues-java.lang.String-}
```
public final void setNumberFormatOfXValues(String value)
```

NumberFormatOfXValues. Lesen/Schreiben String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |
### getNumberFormatOfYValues() {#getNumberFormatOfYValues--}
```
public final String getNumberFormatOfYValues()
```

NumberFormatOfYValues. Lesen/Schreiben String.

**Rückgabe:**
java.lang.String
### setNumberFormatOfYValues(String value) {#setNumberFormatOfYValues-java.lang.String-}
```
public final void setNumberOfValues(String value)
```

NumberFormatOfYValues. Lesen/Schreiben String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |
### getNumberFormatOfBubbleSizes() {#getNumberFormatOfBubbleSizes--}
```
public final String getNumberFormatOfBubbleSizes()
```

NumberFormatOfBubbleSizes. Lesen/Schreiben String.

**Rückgabe:**
java.lang.String
### setNumberFormatOfBubbleSizes(String value) {#setNumberFormatOfBubbleSizes-java.lang.String-}
```
public final void setNumberFormatOfBubbleSizes(String value)
```

NumberFormatOfBubbleSizes. Lesen/Schreiben String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |
### getMarker() {#getMarker--}
```
public final IMarker getMarker()
```

Marker. Nur-Lesen [IMarker](../../com.aspose.slides/imarker).

**Rückgabe:**
[IMarker](../../com.aspose.slides/imarker)
### getBar3DShape() {#getBar3DShape--}
```
public final int getBar3DShape()
```

Gibt die Form einer Serie eines 3-D-Säulendiagramms an. Das Ändern dieses Wertes kann zu einer automatischen Änderung des Serientyps führen. Lesen/Schreiben [ChartShapeType](../../com.aspose.slides/chartshapetype).

**Rückgabe:**
int
### setBar3DShape(int value) {#setBar3DShape-int-}
```
public final void setBar3DShape(int value)
```

Gibt die Form einer Serie eines 3-D-Säulendiagramms an. Das Ändern dieses Wertes kann zu einer automatischen Änderung des Serientyps führen. Lesen/Schreiben [ChartShapeType](../../com.aspose.slides/chartshapetype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### getInvertIfNegative() {#getInvertIfNegative--}
```
public final boolean getInvertIfNegative()
```

Gibt an, dass die Balken-, Säulen- oder Blasensereien ihre Farben invertieren sollen, wenn der Wert negativ ist. Lesen/Schreiben boolean.

**Rückgabe:**
boolean
### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public final void setInvertIfNegative(boolean value)
```

Gibt an, dass die Balken-, Säulen- oder Blasensereien ihre Farben invertieren sollen, wenn der Wert negativ ist. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getInvertedSolidFillColor() {#getInvertedSolidFillColor--}
```
public final IColorFormat getInvertedSolidFillColor()
```
Legt invertierte Vollfarbe für die Serie fest. Um die Farbeinstellung anzuwenden, setzen Sie das Serienformat FillType auf FillType.Solid. Lesen/Schreiben [ColorFormat](../../com.aspose.slides/colorformat).

**Rückgabe:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getAutomaticSeriesColor() {#getAutomaticSeriesColor--}
```
public final Color getAutomaticSeriesColor()
```

Gibt eine automatische Farbe der Serie zurück, die auf dem Serienindex und dem Diagrammstil basiert. Diese Farbe wird standardmäßig verwendet, wenn FillType gleich NotDefined ist.

**Rückgabe:**
java.awt.Color - Das java.awt.Color-Objekt.
### getShowInnerPoints() {#getShowInnerPoints--}
```
public final boolean getShowInnerPoints()
```

Stellt innere Punkte dar. True, wenn innere Punkte im BoxAndWhisker-Chart angezeigt werden. Gilt nur für BoxAndWhisker-Charts. Lesen/Schreiben boolean.

**Rückgabe:**
boolean
### setShowInnerPoints(boolean value) {#setShowInnerPoints-boolean-}
```
public final void setShowInnerPoints(boolean value)
```

Stellt innere Punkte dar. True, wenn innere Punkte im BoxAndWhisker-Chart angezeigt werden. Gilt nur für BoxAndWhisker-Charts. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getShowOutlierPoints() {#getShowOutlierPoints--}
```
public final boolean getShowOutlierPoints()
```

Stellt Ausreißerpunkte dar. True, wenn Ausreißerpunkte im BoxAndWhisker-Chart angezeigt werden. Gilt nur für BoxAndWhisker-Charts. Lesen/Schreiben boolean.

**Rückgabe:**
boolean
### setShowOutlierPoints(boolean value) {#setShowOutlierPoints-boolean-}
```
public final void setShowOutlierPoints(boolean value)
```

Stellt Ausreißerpunkte dar. True, wenn Ausreißerpunkte im BoxAndWhisker-Chart angezeigt werden. Gilt nur für BoxAndWhisker-Charts. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getShowMeanMarkers() {#getShowMeanMarkers--}
```
public final boolean getShowMeanMarkers()
```

Stellt Mittelwert-Marker dar. True, wenn Mittelwert-Marker im BoxAndWhisker-Chart angezeigt werden. Gilt nur für BoxAndWhisker-Charts. Lesen/Schreiben boolean.

**Rückgabe:**
boolean
### setShowMeanMarkers(boolean value) {#setShowMeanMarkers-boolean-}
```
public final void setShowMeanMarkers(boolean value)
```

Stellt Mittelwert-Marker dar. True, wenn Mittelwert-Marker im BoxAndWhisker-Chart angezeigt werden. Gilt nur für BoxAndWhisker-Charts. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getShowMeanLine() {#getShowMeanLine--}
```
public final boolean getShowMeanLine()
```

Stellt Mittelwert-Linie dar. True, wenn die Mittelwert-Linie im BoxAndWhisker-Chart angezeigt wird. Gilt nur für BoxAndWhisker-Charts. Lesen/Schreiben boolean.

**Rückgabe:**
boolean
### setShowMeanLine(boolean value) {#setShowMeanLine-boolean-}
```
public final void setShowMeanLine(boolean value)
```

Stellt Mittelwert-Linie dar. True, wenn die Mittelwert-Linie im BoxAndWhisker-Chart angezeigt wird. Gilt nur für BoxAndWhisker-Charts. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getQuartileMethod() {#getQuartileMethod--}
```
public final int getQuartileMethod()
```

Stellt Quartil-Methode dar. Gilt nur für BoxAndWhisker-Charts.

**Rückgabe:**
int
### setQuartileMethod(int value) {#setQuartileMethod-int-}
```
public final void setQuartileMethod(int value)
```

Stellt Quartil-Methode dar. Gilt nur für BoxAndWhisker-Charts.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### getShowConnectorLines() {#getShowConnectorLines--}
```
public final boolean getShowConnectorLines()
```

Stellt Verbindungslinien dar. Gilt nur für Waterfall-Charts.

**Rückgabe:**
boolean
### setShowConnectorLines(boolean value) {#setShowConnectorLines-boolean-}
```
public final void setShowConnectorLines(boolean value)
```

Stellt Verbindungslinien dar. Gilt nur für Waterfall-Charts.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getParentLabelLayout() {#getParentLabelLayout--}
```
public final int getParentLabelLayout()
```

Stellt das Layout der übergeordneten Kategorienlabels dar. Gilt nur für Treemap-Charts.

**Rückgabe:**
int
### setParentLabelLayout(int value) {#setParentLabelLayout-int-}
```
public final void setParentLabelLayout(int value)
```

Stellt das Layout der übergeordneten Kategorienlabels dar. Gilt nur für Treemap-Charts.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### hasUpDownBars() {#hasUpDownBars--}
```
public final boolean hasUpDownBars()
```

Bestimmt, ob das Line- oder Stock-chart Auf/Ab-Balken hat. Dies ist die Eigenschaft nicht nur dieser Serie, sondern aller Serien der übergeordneten Seriengruppe – dies ist die Projektion der entsprechenden Gruppeneigenschaft. Daher ist diese Eigenschaft Nur lesen. Verwenden Sie die ParentSeriesGroup-Eigenschaft, um auf die übergeordnete Seriengruppe zuzugreifen. Verwenden Sie die ParentSeriesGroup.UpDownBars.HasUpDownBars Lese/Schreiben-Eigenschaft, um den Wert zu ändern. Verwenden Sie die ParentSeriesGroup.UpDownBars-Eigenschaft, um Auf/Ab-Balken zu formatieren. Nur lesen boolean.

--------------------

Dies ist die Projektion der Eigenschaft ParentSeriesGroup.UpDownBars.HasUpDownBars.

**Rückgabe:**
boolean
### getGapWidth() {#getGapWidth--}
```
public final int getGapWidth()
```

Legt den Abstand zwischen Balken- oder Säulen-Cluster als Prozentsatz der Balken- oder Säulenbreite fest. Dies ist die Eigenschaft nicht nur dieser Serie, sondern aller Serien der übergeordneten Seriengruppe – dies ist die Projektion der entsprechenden Gruppeneigenschaft. Daher ist diese Eigenschaft Nur lesen. Verwenden Sie die ParentSeriesGroup-Eigenschaft, um auf die übergeordnete Seriengruppe zuzugreifen. Verwenden Sie die ParentSeriesGroup.GapWidth Lese/Schreiben-Eigenschaft, um den Wert zu ändern. Nur lesen int.

--------------------

Dies ist die Projektion der Eigenschaft ParentSeriesGroup.GapWidth.

**Rückgabe:**
int
### getGapDepth() {#getGapDepth--}
```
public final int getGapDepth()
```

Gibt den Abstand als Prozentsatz der Markierungsbreite zwischen den Datenserien in einem 3D-Diagramm zurück oder setzt ihn. Dies ist die Eigenschaft nicht nur dieser Serie, sondern aller Serien der übergeordneten Seriengruppe – dies ist die Projektion der entsprechenden Gruppeneigenschaft. Daher ist diese Eigenschaft Nur lesen. Verwenden Sie die ParentSeriesGroup-Eigenschaft, um auf die übergeordnete Seriengruppe zuzugreifen. Verwenden Sie die ParentSeriesGroup.GapDepth Lese/Schreiben-Eigenschaft, um den Wert zu ändern. Nur lesen int.

--------------------

Dies ist die Projektion der Eigenschaft ParentSeriesGroup.GapDepth.

**Rückgabe:**
int
### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public final int getFirstSliceAngle()
```

Legt den Winkel des ersten Kuchens- oder Donut-Diagrammsegments in Grad fest (im Uhrzeigersinn von oben, von 0 bis 360 Grad). Dies ist die Eigenschaft nicht nur dieser Serie, sondern aller Serien der übergeordneten Seriengruppe – dies ist die Projektion der entsprechenden Gruppeneigenschaft. Daher ist diese Eigenschaft Nur lesen. Verwenden Sie die ParentSeriesGroup-Eigenschaft, um auf die übergeordnete Seriengruppe zuzugreifen. Verwenden Sie die ParentSeriesGroup.FirstSliceAngle Lese/Schreiben-Eigenschaft, um den Wert zu ändern. Nur lesen int.

--------------------

Dies ist die Projektion der Eigenschaft ParentSeriesGroup.FirstSliceAngle.

**Rückgabe:**
int
### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public final byte getDoughnutHoleSize()
```

Legt die Größe des Lochs in einem Donut-Diagramm fest (kann zwischen 10 % und 90 % der Plot-Flächengröße liegen). Dies ist die Eigenschaft nicht nur dieser Serie, sondern aller Serien der übergeordneten Seriengruppe – dies ist die Projektion der entsprechenden Gruppeneigenschaft. Daher ist diese Eigenschaft Nur lesen. Verwenden Sie die ParentSeriesGroup-Eigenschaft, um auf die übergeordnete Seriengruppe zuzugreifen. Verwenden Sie die ParentSeriesGroup.DoughnutHoleSize Lese/Schreiben-Eigenschaft, um den Wert zu ändern. Nur lesen byte.

--------------------

Dies ist die Projektion der Eigenschaft ParentSeriesGroup.DoughnutHoleSize.

**Rückgabe:**
byte
### getOverlap() {#getOverlap--}
```
public final byte getOverlap()
```

Legt fest, wie stark Balken und Säulen in 2-D-Diagrammen überlappen, als Prozentsatz (von –100 % bis 100 %). Dies ist die Eigenschaft nicht nur dieser Serie, sondern aller Serien der übergeordneten Seriengruppe. Es ist eine Projektion der entsprechenden Eigenschaft in der übergeordneten Seriengruppe, daher ist diese Eigenschaft Nur lesen. Um den Wert zu ändern, verwenden Sie die ParentSeriesGroup.Overlap Lese/Schreiben-Eigenschaft. Nur lesen byte.

Overlap gibt den Grad der Überlappung oder des Abstands zwischen Balken und Säulen als Prozentsatz ihrer Breite an:
- –100 %: maximaler Abstand (Balken sind vollständig getrennt).
- 0 %: Balken stehen nebeneinander ohne Überlappung oder Abstand.
- 100 %: maximale Überlappung (Balken überlappen vollständig).

Dies ist die Projektion der Eigenschaft ParentSeriesGroup.Overlap.

**Rückgabe:**
byte
### getSecondPieSize() {#getSecondPieSize--}
```
public final int getSecondPieSize()
```

Legt die Größe des zweiten Kuchens oder Balkens eines pie-of-pie-Diagramms bzw. eines bar-of-pie-Diagramms als Prozentsatz der Größe des ersten Kuchens fest (kann zwischen 5 % und 200 % liegen). Dies ist die Eigenschaft nicht nur dieser Serie, sondern aller Serien der übergeordneten Seriengruppe – dies ist die Projektion der entsprechenden Gruppeneigenschaft. Daher ist diese Eigenschaft Nur lesen. Verwenden Sie die ParentSeriesGroup-Eigenschaft, um auf die übergeordnete Seriengruppe zuzugreifen. Verwenden Sie die ParentSeriesGroup.SecondPieSize Lese/Schreiben-Eigenschaft, um den Wert zu ändern. Nur lesen int.

--------------------

Dies ist die Projektion der Eigenschaft ParentSeriesGroup.SecondPieSize.

**Rückgabe:**
int
### hasSeriesLines() {#hasSeriesLines--}
```
public final boolean hasSeriesLines()
```

Bestimmt, ob für diese Serie und verwandte Serien Serienlinien vorhanden sind. Dies ist die Eigenschaft nicht nur dieser Serie, sondern aller Serien der übergeordneten Seriengruppe – dies ist die Projektion der entsprechenden Gruppeneigenschaft. Daher ist diese Eigenschaft Nur lesen. Verwenden Sie die ParentSeriesGroup-Eigenschaft, um auf die übergeordnete Seriengruppe zuzugreifen. Verwenden Sie die ParentSeriesGroup.HasSeriesLines Lese/Schreiben-Eigenschaft, um den Wert zu ändern. Verwenden Sie die ParentSeriesGroup.SeriesLinesFormat-Eigenschaft, um Serienlinien zu formatieren. Nur lesen boolean.

--------------------

Dies ist die Projektion der Eigenschaft ParentSeriesGroup.HasSeriesLines.

**Rückgabe:**
boolean
### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public final int getBubbleSizeRepresentation()
```

Legt fest, wie die Bubble-Größenwerte im Bubble-Chart dargestellt werden. Dies ist die Eigenschaft nicht nur dieser Serie, sondern aller Serien der übergeordneten Seriengruppe – dies ist die Projektion der entsprechenden Gruppeneigenschaft. Daher ist diese Eigenschaft Nur lesen. Verwenden Sie die ParentSeriesGroup-Eigenschaft, um auf die übergeordnete Seriengruppe zuzugreifen. Verwenden Sie die ParentSeriesGroup.BubbleSizeRepresentation Lese/Schreiben-Eigenschaft, um den Wert zu ändern.

--------------------

Dies ist die Projektion der Eigenschaft ParentSeriesGroup.BubbleSizeRepresentation.

**Rückgabe:**
int
### getPieSplitPosition() {#getPieSplitPosition--}
```
public final double getPieSplitPosition()
```

Legt einen Wert fest, der zur Bestimmung verwendet wird, welche Datenpunkte im zweiten Kuchen oder Balken eines pie-of-pie- oder bar-of-pie-Diagramms liegen. Wird zusammen mit der PieSplitBy-Eigenschaft verwendet. Dies ist die Eigenschaft nicht nur dieser Serie, sondern aller Serien der übergeordneten Seriengruppe – dies ist die Projektion der entsprechenden Gruppeneigenschaft. Daher ist diese Eigenschaft Nur lesen. Verwenden Sie die ParentSeriesGroup-Eigenschaft, um auf die übergeordnete Seriengruppe zuzugreifen. Verwenden Sie die ParentSeriesGroup.PieSplitPosition Lese/Schreiben-Eigenschaft, um den Wert zu ändern. Nur lesen double.

--------------------

Dies ist die Projektion der Eigenschaft ParentSeriesGroup.PieSplitPosition.

**Rückgabe:**
double
### getPieSplitBy() {#getPieSplitBy--}
```
public final int getPieSplitBy()
```

Legt fest, wie bestimmt wird, welche Datenpunkte im zweiten Kuchen oder Balken eines pie-of-pie- oder bar-of-pie-Diagramms liegen. Dies ist die Eigenschaft nicht nur dieser Serie, sondern aller Serien der übergeordneten Seriengruppe – dies ist die Projektion der entsprechenden Gruppeneigenschaft. Daher ist diese Eigenschaft Nur lesen. Verwenden Sie die ParentSeriesGroup-Eigenschaft, um auf die übergeordnete Seriengruppe zuzugreifen. Verwenden Sie die ParentSeriesGroup.PieSplitBy Lese/Schreiben-Eigenschaft, um den Wert zu ändern. Nur lesen [PieSplitType](../../com.aspose.slides/piesplittype).

--------------------

1) Dies ist die Projektion der Eigenschaft ParentSeriesGroup.PieSplitBy. 2) Wenn der Eigenschaftswert PieSplitType.Custom ist, können Sie benutzerdefinierte Split-Informationen mit der ParentSeriesGroup.PieSplitCustomPoints-Eigenschaft definieren.

**Rückgabe:**
int
### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public final IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

Die benutzerdefinierten Split-Informationen für ein pie-of-pie- oder bar-of-pie-Diagramm mit einem benutzerdefinierten Split. Enthält Datenpunkte, die im zweiten Kuchen oder Balken eines pie-of-pie- bzw. bar-of-pie-Diagramms gezeichnet werden sollen. Dies ist die Eigenschaft nicht nur dieser Serie, sondern aller Serien der übergeordneten Seriengruppe – dies ist die Projektion der entsprechenden Gruppeneigenschaft Nur lesen [PieSplitCustomPointCollection](../../com.aspose.slides/piesplitcustompointcollection).

--------------------

Dies ist die Projektion der Eigenschaft ParentSeriesGroup.PieSplitCustomPoints.

**Rückgabe:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)
### isColorVaried() {#isColorVaried--}
```
public final boolean isColorVaried()
```
Gibt an, dass jeder Datenmarker in der Serie eine andere Farbe hat. Dies ist die Eigenschaft nicht nur dieser Serie, sondern aller Serien der übergeordneten Seriengruppe – dies ist die Projektion der entsprechenden Gruppeneigenschaft. Daher ist diese Eigenschaft nur lesbar. Verwenden Sie die Eigenschaft ParentSeriesGroup, um auf die übergeordnete Seriengruppe zuzugreifen. Verwenden Sie die Lese-/Schreib-Eigenschaft ParentSeriesGroup.IsColorVaried, um den Wert zu ändern. Nur lesbarer boolean.

--------------------

Dies ist die Projektion der Eigenschaft ParentSeriesGroup.IsColorVaried.

**Rückgabe:**
boolean
### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public final int getBubbleSizeScale()
```

Gibt den Skalierungsfaktor für das Blasendiagramm an (kann zwischen 0 und 300 Prozent der Standardgröße liegen). Dies ist die Eigenschaft nicht nur dieser Serie, sondern aller Serien der übergeordneten Seriengruppe – dies ist die Projektion der entsprechenden Gruppeneigenschaft. Daher ist diese Eigenschaft nur lesbar. Verwenden Sie die Eigenschaft ParentSeriesGroup, um auf die übergeordnete Seriengruppe zuzugreifen. Verwenden Sie die Lese-/Schreib-Eigenschaft ParentSeriesGroup.BubbleSizeScale, um den Wert zu ändern.

--------------------

Dies ist die Projektion der Eigenschaft ParentSeriesGroup.BubbleSizeScale.

**Rückgabe:**
int
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