---
title: ChartSeries
second_title: Aspose.Slides für Android über Java API Referenz
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
| [getExplosion()](#getExplosion--) | Der Abstand eines geöffneten Kuchenstücks vom Zentrum des Kuchendiagramms wird als Prozentsatz des Kuchendurchmessers angegeben. |
| [setExplosion(int value)](#setExplosion-int-) | Der Abstand eines geöffneten Kuchenstücks vom Zentrum des Kuchendiagramms wird als Prozentsatz des Kuchendurchmessers angegeben. |
| [getSmooth()](#getSmooth--) | Stellt die Kurvenglättung dar. |
| [setSmooth(boolean value)](#setSmooth-boolean-) | Stellt die Kurvenglättung dar. |
| [getName()](#getName--) | Gibt den Seriennamen zurück. |
| [getDataPoints()](#getDataPoints--) | Gibt die Sammlung von Datenpunkten dieser Serie zurück. |
| [getType()](#getType--) | Gibt einen Typ dieser Serie zurück. |
| [setType(int value)](#setType-int-) | Gibt einen Typ dieser Serie zurück. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Zeigt an, ob diese Serie auf der sekundären Achse geplottet wird. |
| [setPlotOnSecondAxis(boolean value)](#setPlotOnSecondAxis-boolean-) | Zeigt an, ob diese Serie auf der sekundären Achse geplottet wird. |
| [getParentSeriesGroup()](#getParentSeriesGroup--) | ParentSeriesGroup. |
| [getFormat()](#getFormat--) | Gibt das Format einer Serie zurück. |
| [getOrder()](#getOrder--) | Gibt die Reihenfolge einer Serie zurück. |
| [setOrder(int value)](#setOrder-int-) | Gibt die Reihenfolge einer Serie zurück. |
| [getLabels()](#getLabels--) | Gibt die Labels einer Serie zurück. |
| [getTrendLines()](#getTrendLines--) | Sammlung von Trendlinien der Serie. |
| [getErrorBarsXFormat()](#getErrorBarsXFormat--) | Stellt ErrorBars der Serie mit Richtung X dar. |
| [getErrorBarsYFormat()](#getErrorBarsYFormat--) | Stellt ErrorBars der Serie mit Richtung Y dar. |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Stellt den Legendeneintrag dar, der mit dieser Serie verknüpft ist. Nur-Lesen [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |
| [getNumberFormatOfValues()](#getNumberFormatOfValues--) | NumberFormatOfValues. |
| [setNumberFormatOfValues(String value)](#setNumberFormatOfValues-java.lang.String-) | NumberFormatOfValues. |
| [getNumberFormatOfXValues()](#getNumberFormatOfXValues--) | NumberFormatOfXValues. |
| [setNumberFormatOfXValues(String value)](#setNumberFormatOfXValues-java.lang.String-) | NumberFormatOfXValues. |
| [getNumberFormatOfYValues()](#getNumberFormatOfYValues--) | NumberFormatOfYValues. |
| [setNumberFormatOfYValues(String value)](#setNumberFormatOfYValues-java.lang.String-) | NumberFormatOfYValues. |
| [getNumberFormatOfBubbleSizes()](#getNumberFormatOfBubbleSizes--) | NumberFormatOfBubbleSizes. |
| [setNumberFormatOfBubbleSizes(String value)](#setNumberFormatOfBubbleSizes-java.lang.String-) | NumberFormatOfBubbleSizes. |
| [getMarker()](#getMarker--) | Marker. |
| [getBar3DShape()](#getBar3DShape--) | Gibt die Form einer Serie eines 3-D-Balkendiagramms an. |
| [setBar3DShape(int value)](#setBar3DShape-int-) | Gibt die Form einer Serie eines 3-D-Balkendiagramms an. |
| [getInvertIfNegative()](#getInvertIfNegative--) | Gibt an, dass die Balken-, Spalten- oder Blasenserie ihre Farben invertiert, wenn der Wert negativ ist. |
| [setInvertIfNegative(boolean value)](#setInvertIfNegative-boolean-) | Gibt an, dass die Balken-, Spalten- oder Blasenserie ihre Farben invertiert, wenn der Wert negativ ist. |
| [getInvertedSolidFillColor()](#getInvertedSolidFillColor--) | Gibt die invertierte Vollfarbe für die Serie an. |
| [getAutomaticSeriesColor()](#getAutomaticSeriesColor--) | Gibt eine automatische Farbe der Serie zurück, basierend auf dem Serienindex und dem Diagrammstil. |
| [getShowInnerPoints()](#getShowInnerPoints--) | Stellt innere Punkte dar. |
| [setShowInnerPoints(boolean value)](#setShowInnerPoints-boolean-) | Stellt innere Punkte dar. |
| [getShowOutlierPoints()](#getShowOutlierPoints--) | Stellt Ausreißerpunkte dar. |
| [setShowOutlierPoints(boolean value)](#setShowOutlierPoints-boolean-) | Stellt Ausreißerpunkte dar. |
| [getShowMeanMarkers()](#getShowMeanMarkers--) | Stellt Mittelwertmarker dar. |
| [setShowMeanMarkers(boolean value)](#setShowMeanMarkers-boolean-) | Stellt Mittelwertmarker dar. |
| [getShowMeanLine()](#getShowMeanLine--) | Stellt Mittelwertlinie dar. |
| [setShowMeanLine(boolean value)](#setShowMeanLine-boolean-) | Stellt Mittelwertlinie dar. |
| [getQuartileMethod()](#getQuartileMethod--) | Stellt die Quartilmethode dar. |
| [setQuartileMethod(int value)](#setQuartileMethod-int-) | Stellt die Quartilmethode dar. |
| [getShowConnectorLines()](#getShowConnectorLines--) | Stellt Verbindungslinien dar. |
| [setShowConnectorLines(boolean value)](#setShowConnectorLines-boolean-) | Stellt Verbindungslinien dar. |
| [getParentLabelLayout()](#getParentLabelLayout--) | Stellt das Layout der übergeordneten Kategoriebeschriftungen dar. |
| [setParentLabelLayout(int value)](#setParentLabelLayout-int-) | Stellt das Layout der übergeordneten Kategoriebeschriftungen dar. |
| [hasUpDownBars()](#hasUpDownBars--) | Bestimmt, ob ein Linien- oder Kursdiagramm Auf/Ab-Balken hat. |
| [getGapWidth()](#getGapWidth--) | Gibt den Abstand zwischen Balken- oder Spaltenclustern als Prozentsatz der Balken- oder Spaltenbreite an. |
| [getGapDepth()](#getGapDepth--) | Gibt den Abstand zurück oder legt ihn fest, als Prozentsatz der Markierungsbreite, zwischen den Datenserien in einem 3D-Diagramm. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | Gibt den Winkel des ersten Kuchen- oder Donut-Diagrammsegments in Grad an (im Uhrzeigersinn von oben, von 0 bis 360 Grad). |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Gibt die Größe des Lochs in einem Donut-Diagramm an (kann zwischen 10 % und 90 % der Größe des Zeichenbereichs liegen). |
| [getOverlap()](#getOverlap--) | Gibt an, wie stark Balken und Spalten in 2-D-Diagrammen überlappen, als Prozentsatz (von -100 % bis 100 %). |
| [getSecondPieSize()](#getSecondPieSize--) | Gibt die Größe des zweiten Kuchens oder Balkens eines Kuchen-aus-Kuchen-Diagramms oder eines Balken-aus-Kuchen-Diagramms als Prozentsatz der Größe des ersten Kuchens an (kann zwischen 5 % und 200 % liegen). |
| [hasSeriesLines()](#hasSeriesLines--) | Bestimmt, ob es Serienlinien für diese Serie und verwandte Serien gibt. |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Gibt an, wie die Größenwerte der Blasen im Blasendiagramm dargestellt werden. |
| [getPieSplitPosition()](#getPieSplitPosition--) | Gibt einen Wert an, der zur Bestimmung verwendet wird, welche Datenpunkte im zweiten Kuchen oder Balken eines Kuchen-aus-Kuchen- oder Balken-aus-Kuchen-Diagramms liegen. |
| [getPieSplitBy()](#getPieSplitBy--) | Gibt an, wie zu bestimmen ist, welche Datenpunkte im zweiten Kuchen oder Balken eines Kuchen-aus-Kuchen- oder Balken-aus-Kuchen-Diagramms liegen. |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | Die benutzerdefinierten Split-Informationen für ein Kuchen-aus-Kuchen- oder Balken-aus-Kuchen-Diagramm mit benutzerdefiniertem Split. |
| [isColorVaried()](#isColorVaried--) | Gibt an, dass jeder Datenmarker in der Serie eine andere Farbe hat. |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Gibt den Skalierungsfaktor für das Blasendiagramm an (kann zwischen 0 % und 300 % der Standardgröße liegen). |
| [getSlide()](#getSlide--) | Gibt die übergeordnete Folie eines FillFormat zurück. |
| [getPresentation()](#getPresentation--) | Gibt die übergeordnete Präsentation eines FillFormat zurück. |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Gibt das Parent_Immediate-Objekt zurück. Nur-Lesen IDOMObject.

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

Der Abstand eines geöffneten Kuchenstücks vom Zentrum des Kuchendiagramms wird als Prozentsatz des Kuchendurchmessers angegeben. Lesen/Schreiben int.

**Rückgabe:**
int

### setExplosion(int value) {#setExplosion-int-}
```
public final void setExplosion(int value)
```

Der Abstand eines geöffneten Kuchenstücks vom Zentrum des Kuchendiagramms wird als Prozentsatz des Kuchendurchmessers angegeben. Lesen/Schreiben int.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getSmooth() {#getSmooth--}
```
public final boolean getSmooth()
```

Stellt die Kurvenglättung dar. True, wenn die Kurvenglättung für das Liniendiagramm oder Streudiagramm aktiviert ist. Gilt nur für Linien- und Streudiagramme, die durch Linien verbunden sind. Lesen/Schreiben boolean.

**Rückgabe:**
boolean

### setSmooth(boolean value) {#setSmooth-boolean-}
```
public final void setSmooth(boolean value)
```

Stellt die Kurvenglättung dar. True, wenn die Kurvenglättung für das Liniendiagramm oder Streudiagramm aktiviert ist. Gilt nur für Linien- und Streudiagramme, die durch Linien verbunden sind. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getName() {#getName--}
```
public final IStringChartValue getName()
```

Gibt den Seriennamen zurück. Nur-Lesen [IStringChartValue](../../com.aspose.slides/istringchartvalue).

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

Zeigt an, ob diese Serie auf der sekundären Achse geplottet wird. Lesen/Schreiben boolean.

**Rückgabe:**
boolean

### setPlotOnSecondAxis(boolean value) {#setPlotOnSecondAxis-boolean-}
```
public final void setPlotOnSecondAxis(boolean value)
```

Zeigt an, ob diese Serie auf der sekundären Achse geplottet wird. Lesen/Schreiben boolean.

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

TrendLines sind für Datenserien in nicht gestapelten 2-D-Fläche-, Balken-, Säulen-, Linien-, Kurs-, XY- (Streudiagramm)- und Blasendiagrammen verfügbar. Für Datenserien in gestapelten oder 3-D-Diagrammen ist keine Trendlinie verfügbar. Trendlines sind außerdem für Radar-, Kuchen-, Oberflächen- oder Donut-Diagramme nicht verfügbar.

**Rückgabe:**
[ITrendlineCollection](../../com.aspose.slides/itrendlinecollection)

### getErrorBarsXFormat() {#getErrorBarsXFormat--}
```
public final IErrorBarsFormat getErrorBarsXFormat()
```

Stellt ErrorBars der Serie mit Richtung X dar. Nur-Lesen [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

ErrorBars mit X-Richtung sind für Serien vom Typ Fläche, Balken, Streuung und Blase verfügbar. Für alle anderen Diagrammtypen gibt diese Eigenschaft null zurück (einschließlich 3D-Diagramme). Bei benutzerdefinierten Werten verwenden Sie die DataPoints-Sammlung, um den Wert anzugeben (mit ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues))-Eigenschaft).

**Rückgabe:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)

### getErrorBarsYFormat() {#getErrorBarsYFormat--}
```
public final IErrorBarsFormat getErrorBarsYFormat()
```

Stellt ErrorBars der Serie mit Richtung Y dar. Nur-Lesen [IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat).

--------------------

ErrorBars mit Y-Richtung sind für Serien vom Typ Fläche, Balken, Linie, Streuung und Blase verfügbar. Für alle anderen Diagrammtypen gibt diese Eigenschaft null zurück (einschließlich 3D-Diagramme). Bei benutzerdefinierten Werten verwenden Sie die DataPoints-Sammlung, um den Wert anzugeben (mit ([IChartDataPoint.getErrorBarsCustomValues](../../com.aspose.slides/ichartdatapoint\#getErrorBarsCustomValues))-Eigenschaft).

**Rückgabe:**
[IErrorBarsFormat](../../com.aspose.slides/ierrorbarsformat)

### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public final ILegendEntryProperties getRelatedLegendEntry()
```

Stellt den Legendeneintrag dar, der mit dieser Serie verknüpft ist. Nur-Lesen [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

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
public final void setNumberFormatOfYValues(String value)
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

Gibt die Form einer Serie eines 3-D-Balkendiagramms an. Eine Änderung dieses Wertes kann zu einer automatischen Änderung des Serientyps führen. Lesen/Schreiben [ChartShapeType](../../com.aspose.slides/chartshapetype).

**Rückgabe:**
int

### setBar3DShape(int value) {#setBar3DShape-int-}
```
public final void setBar3DShape(int value)
```

Gibt die Form einer Serie eines 3-D-Balkendiagramms an. Eine Änderung dieses Wertes kann zu einer automatischen Änderung des Serientyps führen. Lesen/Schreiben [ChartShapeType](../../com.aspose.slides/chartshapetype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getInvertIfNegative() {#getInvertIfNegative--}
```
public final boolean getInvertIfNegative()
```

Gibt an, dass die Balken-, Spalten- oder Blasenserie ihre Farben invertiert, wenn der Wert negativ ist. Lesen/Schreiben boolean.

**Rückgabe:**
boolean

### setInvertIfNegative(boolean value) {#setInvertIfNegative-boolean-}
```
public final void setInvertIfNegative(boolean value)
```

Gibt an, dass die Balken-, Spalten- oder Blasenserie ihre Farben invertiert, wenn der Wert negativ ist. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getInvertedSolidFillColor() {#getInvertedSolidFillColor--}
```
public final IColorFormat getInvertedSolidFillColor()
```

Gibt die invertierte Vollfarbe für die Serie an. Um die Farbe anzuwenden, setzen Sie den FillType des Serienformats auf FillType.Solid. Lesen/Schreiben [ColorFormat](../../com.aspose.slides/colorformat).

**Rückgabe:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getAutomaticSeriesColor() {#getAutomaticSeriesColor--}
```
public final Integer getAutomaticSeriesColor()
```

Gibt eine automatische Farbe der Serie zurück, basierend auf dem Serienindex und dem Diagrammstil. Diese Farbe wird standardmäßig verwendet, wenn FillType gleich NotDefined ist.

**Rückgabe:**
java.lang.Integer - Das java.lang.Integer-Objekt.

### getShowInnerPoints() {#getShowInnerPoints--}
```
public final boolean getShowInnerPoints()
```

Stellt innere Punkte dar. True, wenn innere Punkte im BoxAndWhisker-Diagramm angezeigt werden. Gilt nur für BoxAndWhisker-Diagramme. Lesen/Schreiben boolean.

**Rückgabe:**
boolean

### setShowInnerPoints(boolean value) {#setShowInnerPoints-boolean-}
```
public final void setShowInnerPoints(boolean value)
```

Stellt innere Punkte dar. True, wenn innere Punkte im BoxAndWhisker-Diagramm angezeigt werden. Gilt nur für BoxAndWhisker-Diagramme. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getShowOutlierPoints() {#getShowOutlierPoints--}
```
public final boolean getShowOutlierPoints()
```

Stellt Ausreißerpunkte dar. True, wenn Ausreißerpunkte im BoxAndWhisker-Diagramm angezeigt werden. Gilt nur für BoxAndWhisker-Diagramme. Lesen/Schreiben boolean.

**Rückgabe:**
boolean

### setShowOutlierPoints(boolean value) {#setShowOutlierPoints-boolean-}
```
public final void setShowOutlierPoints(boolean value)
```

Stellt Ausreißerpunkte dar. True, wenn Ausreißerpunkte im BoxAndWhisker-Diagramm angezeigt werden. Gilt nur für BoxAndWhisker-Diagramme. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getShowMeanMarkers() {#getShowMeanMarkers--}
```
public final boolean getShowMeanMarkers()
```

Stellt Mittelwertmarker dar. True, wenn Mittelwertmarker im BoxAndWhisker-Diagramm angezeigt werden. Gilt nur für BoxAndWhisker-Diagramme. Lesen/Schreiben boolean.

**Rückgabe:**
boolean

### setShowMeanMarkers(boolean value) {#setShowMeanMarkers-boolean-}
```
public final void setShowMeanMarkers(boolean value)
```

Stellt Mittelwertmarker dar. True, wenn Mittelwertmarker im BoxAndWhisker-Diagramm angezeigt werden. Gilt nur für BoxAndWhisker-Diagramme. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getShowMeanLine() {#getShowMeanLine--}
```
public final boolean getShowMeanLine()
```

Stellt Mittelwertlinie dar. True, wenn Mittelwertlinie im BoxAndWhisker-Diagramm angezeigt wird. Gilt nur für BoxAndWhisker-Diagramme. Lesen/Schreiben boolean.

**Rückgabe:**
boolean

### setShowMeanLine(boolean value) {#setShowMeanLine-boolean-}
```
public final void setShowMeanLine(boolean value)
```

Stellt Mittelwertlinie dar. True, wenn Mittelwertlinie im BoxAndWhisker-Diagramm angezeigt wird. Gilt nur für BoxAndWhisker-Diagramme. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getQuartileMethod() {#getQuartileMethod--}
```
public final int getQuartileMethod()
```

Stellt die Quartilmethode dar. Gilt nur für BoxAndWhisker-Diagramme.

**Rückgabe:**
int

### setQuartileMethod(int value) {#setQuartileMethod-int-}
```
public final void setQuartileMethod(int value)
```

Stellt die Quartilmethode dar. Gilt nur für BoxAndWhisker-Diagramme.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getShowConnectorLines() {#getShowConnectorLines--}
```
public final boolean getShowConnectorLines()
```

Stellt Verbindungslinien dar. Gilt nur für Waterfall-Diagramme.

**Rückgabe:**
boolean

### setShowConnectorLines(boolean value) {#setShowConnectorLines-boolean-}
```
public final void setShowConnectorLines(boolean value)
```

Stellt Verbindungslinien dar. Gilt nur für Waterfall-Diagramme.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getParentLabelLayout() {#getParentLabelLayout--}
```
public final int getParentLabelLayout()
```

Stellt das Layout der übergeordneten Kategoriebeschriftungen dar. Gilt nur für Treemap-Diagramme.

**Rückgabe:**
int

### setParentLabelLayout(int value) {#setParentLabelLayout-int-}
```
public final void setParentLabelLayout(int value)
```

Stellt das Layout der übergeordneten Kategoriebeschriftungen dar. Gilt nur für Treemap-Diagramme.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### hasUpDownBars() {#hasUpDownBars--}
```
public final boolean hasUpDownBars()
```

Bestimmt, ob ein Linien- oder Kursdiagramm Auf/Ab-Balken hat. Diese Eigenschaft gilt nicht nur für diese Serie, sondern für alle Serien der übergeordneten Seriengruppe – sie ist eine Projektion der entsprechenden Gruppeneigenschaft. Deshalb ist diese Eigenschaft nur-Lesen. Verwenden Sie die Eigenschaft ParentSeriesGroup, um auf die übergeordnete Seriengruppe zuzugreifen. Verwenden Sie die les-/schreibbare Eigenschaft ParentSeriesGroup.UpDownBars.HasUpDownBars, um den Wert zu ändern. Verwenden Sie die Eigenschaft ParentSeriesGroup.UpDownBars, um das Format der Auf/Ab-Balken zu ändern. Nur-Lesen boolean.

--------------------

Dies ist die Projektion der Eigenschaft ParentSeriesGroup.UpDownBars.HasUpDownBars.

**Rückgabe:**
boolean

### getGapWidth() {#getGapWidth--}
```
public final int getGapWidth()
```

Gibt den Abstand zwischen Balken- oder Spaltenclustern als Prozentsatz der Balken- oder Spaltenbreite an. Diese Eigenschaft gilt nicht nur für diese Serie, sondern für alle Serien der übergeordneten Seriengruppe – sie ist eine Projektion der entsprechenden Gruppeneigenschaft. Deshalb ist diese Eigenschaft nur-Lesen. Verwenden Sie die Eigenschaft ParentSeriesGroup, um auf die übergeordnete Seriengruppe zuzugreifen. Verwenden Sie die les-/schreibbare Eigenschaft ParentSeriesGroup.GapWidth, um den Wert zu ändern. Nur-Lesen int.

--------------------

Dies ist die Projektion der Eigenschaft ParentSeriesGroup.GapWidth.

**Rückgabe:**
int

### getGapDepth() {#getGapDepth--}
```
public final int getGapDepth()
```

Gibt den Abstand zurück oder legt ihn fest, als Prozentsatz der Markierungsbreite, zwischen den Datenserien in einem 3D-Diagramm. Diese Eigenschaft gilt nicht nur für diese Serie, sondern für alle Serien der übergeordneten Seriengruppe – sie ist eine Projektion der entsprechenden Gruppeneigenschaft. Deshalb ist diese Eigenschaft nur-Lesen. Verwenden Sie die Eigenschaft ParentSeriesGroup, um auf die übergeordnete Seriengruppe zuzugreifen. Verwenden Sie die les-/schreibbare Eigenschaft ParentSeriesGroup.GapDepth, um den Wert zu ändern. Nur-Lesen int.

--------------------

Dies ist die Projektion der Eigenschaft ParentSeriesGroup.GapDepth.

**Rückgabe:**
int

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public final int getFirstSliceAngle()
```

Gibt den Winkel des ersten Kuchen- oder Donut-Diagrammsegments in Grad an (im Uhrzeigersinn von oben, von 0 bis 360 Grad). Diese Eigenschaft gilt nicht nur für diese Serie, sondern für alle Serien der übergeordneten Seriengruppe – sie ist eine Projektion der entsprechenden Gruppeneigenschaft. Deshalb ist diese Eigenschaft nur-Lesen. Verwenden Sie die Eigenschaft ParentSeriesGroup, um auf die übergeordnete Seriengruppe zuzugreifen. Verwenden Sie die les-/schreibbare Eigenschaft ParentSeriesGroup.FirstSliceAngle, um den Wert zu ändern. Nur-Lesen int.

--------------------

Dies ist die Projektion der Eigenschaft ParentSeriesGroup.FirstSliceAngle.

**Rückgabe:**
int

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public final byte getDoughnutHoleSize()
```

Gibt die Größe des Lochs in einem Donut-Diagramm an (kann zwischen 10 % und 90 % der Größe des Zeichenbereichs liegen). Diese Eigenschaft gilt nicht nur für diese Serie, sondern für alle Serien der übergeordneten Seriengruppe – sie ist eine Projektion der entsprechenden Gruppeneigenschaft. Deshalb ist diese Eigenschaft nur-Lesen. Verwenden Sie die Eigenschaft ParentSeriesGroup, um auf die übergeordnete Seriengruppe zuzugreifen. Verwenden Sie die les-/schreibbare Eigenschaft ParentSeriesGroup.DoughnutHoleSize, um den Wert zu ändern. Nur-Lesen byte.

--------------------

Dies ist die Projektion der Eigenschaft ParentSeriesGroup.DoughnutHoleSize.

**Rückgabe:**
byte

### getOverlap() {#getOverlap--}
```
public



```

Gibt an, wie stark Balken und Spalten in 2-D-Diagrammen überlappen, als Prozentsatz (von -100 % bis 100 %). Diese Eigenschaft gilt nicht nur für diese Serie, sondern für alle Serien der übergeordneten Seriengruppe. Sie ist eine Projektion der entsprechenden Eigenschaft in der übergeordneten Seriengruppe und daher nur-Lesen. Um den Wert zu ändern, verwenden Sie die les-/schreibbare Eigenschaft ParentSeriesGroup.Overlap. Nur-Lesen byte.

--------------------

Overlap gibt den Grad der Überlappung oder des Abstands zwischen Balken und Spalten als Prozentsatz ihrer Breite an:
- -100 %: Maximaler Abstand (Balken sind vollständig getrennt).
- 0 %: Balken stehen nebeneinander ohne Überlappung oder Abstand.
- 100 %: Maximale Überlappung (Balken überlappen vollständig). Dies ist eine Projektion der Eigenschaft ParentSeriesGroup.Overlap.

**Rückgabe:**
byte

### getSecondPieSize() {#getSecondPieSize--}
```
public final int getSecondPieSize()
```

Gibt die Größe des zweiten Kuchens oder Balkens eines Kuchen-aus-Kuchen-Diagramms oder eines Balken-aus-Kuchen-Diagramms als Prozentsatz der Größe des ersten Kuchens an (kann zwischen 5 % und 200 % liegen). Diese Eigenschaft gilt nicht nur für diese Serie, sondern für alle Serien der übergeordneten Seriengruppe – sie ist eine Projektion der entsprechenden Gruppeneigenschaft. Deshalb ist diese Eigenschaft nur-Lesen. Verwenden Sie die Eigenschaft ParentSeriesGroup, um auf die übergeordnete Seriengruppe zuzugreifen. Verwenden Sie die les-/schreibbare Eigenschaft ParentSeriesGroup.SecondPieSize, um den Wert zu ändern. Nur-Lesen int.

--------------------

Dies ist die Projektion der Eigenschaft ParentSeriesGroup.SecondPieSize.

**Rückgabe:**
int

### hasSeriesLines() {#hasSeriesLines--}
```
public final boolean hasSeriesLines()
```

Bestimmt, ob es Serienlinien für diese Serie und verwandte Serien gibt. Diese Eigenschaft gilt nicht nur für diese Serie, sondern für alle Serien der übergeordneten Seriengruppe – sie ist eine Projektion der entsprechenden Gruppeneigenschaft. Deshalb ist diese Eigenschaft nur-Lesen. Verwenden Sie die Eigenschaft ParentSeriesGroup, um auf die übergeordnete Seriengruppe zuzugreifen. Verwenden Sie die les-/schreibbare Eigenschaft ParentSeriesGroup.HasSeriesLines, um den Wert zu ändern. Verwenden Sie die Eigenschaft ParentSeriesGroup.SeriesLinesFormat, um Serienlinien zu formatieren. Nur-Lesen boolean.

--------------------

Dies ist die Projektion der Eigenschaft ParentSeriesGroup.HasSeriesLines.

**Rückgabe:**
boolean

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public final int getBubbleSizeRepresentation()
```

Gibt an, wie die Größenwerte der Blasen im Blasendiagramm dargestellt werden. Diese Eigenschaft gilt nicht nur für diese Serie, sondern für alle Serien der übergeordneten Seriengruppe – sie ist eine Projektion der entsprechenden Gruppeneigenschaft. Deshalb ist diese Eigenschaft nur-Lesen. Verwenden Sie die Eigenschaft ParentSeriesGroup, um auf die übergeordnete Seriengruppe zuzugreifen. Verwenden Sie die les-/schreibbare Eigenschaft ParentSeriesGroup.BubbleSizeRepresentation, um den Wert zu ändern.

--------------------

Dies ist die Projektion der Eigenschaft ParentSeriesGroup.BubbleSizeRepresentation.

**Rückgabe:**
int

### getPieSplitPosition() {#getPieSplitPosition--}
```
public final double getPieSplitPosition()
```

Gibt einen Wert an, der zur Bestimmung verwendet wird, welche Datenpunkte im zweiten Kuchen oder Balken eines Kuchen-aus-Kuchen- oder Balken-aus-Kuchen-Diagramms liegen. Wird zusammen mit der Eigenschaft PieSplitBy verwendet. Diese Eigenschaft gilt nicht nur für diese Serie, sondern für alle Serien der übergeordneten Seriengruppe – sie ist eine Projektion der entsprechenden Gruppeneigenschaft. Deshalb ist diese Eigenschaft nur-Lesen. Verwenden Sie die Eigenschaft ParentSeriesGroup, um auf die übergeordnete Seriengruppe zuzugreifen. Verwenden Sie die les-/schreibbare Eigenschaft ParentSeriesGroup.PieSplitPosition, um den Wert zu ändern. Nur-Lesen double.

--------------------

Dies ist die Projektion der Eigenschaft ParentSeriesGroup.PieSplitPosition.

**Rückgabe:**
double

### getPieSplitBy() {#getPieSplitBy--}
```
public final int getPieSplitBy()
```

Gibt an, wie zu bestimmen ist, welche Datenpunkte im zweiten Kuchen oder Balken eines Kuchen-aus-Kuchen- oder Balken-aus-Kuchen-Diagramms liegen. Diese Eigenschaft gilt nicht nur für diese Serie, sondern für alle Serien der übergeordneten Seriengruppe – sie ist eine Projektion der entsprechenden Gruppeneigenschaft. Deshalb ist diese Eigenschaft nur-Lesen. Verwenden Sie die Eigenschaft ParentSeriesGroup, um auf die übergeordnete Seriengruppe zuzugreifen. Verwenden Sie die les-/schreibbare Eigenschaft ParentSeriesGroup.PieSplitBy, um den Wert zu ändern. Nur-Lesen [PieSplitType](../../com.aspose.slides/piesplittype).

--------------------

1) Dies ist die Projektion der Eigenschaft ParentSeriesGroup.PieSplitBy. 2) Wenn der Eigenschaftswert PieSplitType.Custom ist, können Sie benutzerdefinierte Split-Informationen mit der Eigenschaft ParentSeriesGroup.PieSplitCustomPoints definieren.

**Rückgabe:**
int

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public final IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

Die benutzerdefinierten Split-Informationen für ein Kuchen-aus-Kuchen- oder Balken-aus-Kuchen-Diagramm mit benutzerdefiniertem Split. Enthält Datenpunkte, die im zweiten Kuchen oder Balken eines Kuchen-aus-Kuchen- oder Balken-aus-Kuchen-Diagramms gezeichnet werden sollen. Diese Eigenschaft gilt nicht nur für diese Serie, sondern für alle Serien der übergeordneten Seriengruppe – sie ist eine Projektion der entsprechenden Gruppeneigenschaft Nur-Lesen [PieSplitCustomPointCollection](../../com.aspose.slides/piesplitcustompointcollection).

--------------------

Dies ist die Projektion der Eigenschaft ParentSeriesGroup.PieSplitCustomPoints.

**Rückgabe:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)

### isColorVaried() {#isColorVaried--}
```
public final boolean isColorVaried()
```

Gibt an, dass jeder Datenmarker in der Serie eine andere Farbe hat. Diese Eigenschaft gilt nicht nur für diese Serie, sondern für alle Serien der übergeordneten Seriengruppe – sie ist eine Projektion der entsprechenden Gruppeneigenschaft. Deshalb ist diese Eigenschaft nur-Lesen. Verwenden Sie die Eigenschaft ParentSeriesGroup, um auf die übergeordnete Seriengruppe zuzugreifen. Verwenden Sie die les-/schreibbare Eigenschaft ParentSeriesGroup.IsColorVaried, um den Wert zu ändern. Nur-Lesen boolean.

--------------------

Dies ist die Projektion der Eigenschaft ParentSeriesGroup.IsColorVaried.

**Rückgabe:**
boolean

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public final int getBubbleSizeScale()
```

Gibt den Skalierungsfaktor für das Blasendiagramm an (kann zwischen 0 % und 300 % der Standardgröße liegen). Diese Eigenschaft gilt nicht nur für diese Serie, sondern für alle Serien der übergeordneten Seriengruppe – sie ist eine Projektion der entsprechenden Gruppeneigenschaft. Deshalb ist diese Eigenschaft nur-Lesen. Verwenden Sie die Eigenschaft ParentSeriesGroup, um auf die übergeordnete Seriengruppe zuzugreifen. Verwenden Sie die les-/schreibbare Eigenschaft ParentSeriesGroup.BubbleSizeScale, um den Wert zu ändern.

--------------------

Dies ist die Projektion der Eigenschaft ParentSeriesGroup.BubbleSizeScale.

**Rückgabe:**
int

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Gibt die übergeordnete Folie eines FillFormat zurück. Nur-Lesen [BaseSlide](../../com.aspose.slides/baseslide).

**Rückgabe:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Gibt die übergeordnete Präsentation eines FillFormat zurück. Nur-Lesen [IPresentation](../../com.aspose.slides/ipresentation).

**Rückgabe:**
[IPresentation](../../com.aspose.slides/ipresentation)