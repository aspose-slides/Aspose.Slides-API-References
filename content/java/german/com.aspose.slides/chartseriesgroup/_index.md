---
title: ChartSeriesGroup
second_title: Aspose.Slides für Java API-Referenz
description: Stellt eine Gruppe von Serien dar.
type: docs
url: /de/com.aspose.slides/chartseriesgroup/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup), com.aspose.slides.IDOMObject
```
public class ChartSeriesGroup implements IChartSeriesGroup, IDOMObject
```

Stellt eine Gruppe von Serien dar.

--------------------

1) Siehe Zusammenfassung und Anmerkungen für ChartSeriesGroupCollection Klasse und CombinableSeriesTypesGroup Aufzählung. 2) Gruppe von Serien enthält einige Serien-Eigenschaften, die für jede Serie in der Gruppe gemeinsam sind („series group properties“). „Series group properties“ in ChartSeriesGroup Klasse ist Lesen/Schreiben. Jede der „series group properties“ kann eine Nur-lesbar-Projektion in ChartSeries Klasse haben.

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getType()](#getType--) | Gibt den Typ dieser Seriengruppe zurück. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Gibt an, ob Serien dieser Gruppe auf einer sekundären Achse dargestellt werden. |
| [getSeries()](#getSeries--) | Gibt eine Sammlung von Serien zurück. |
| [get_Item(int index)](#get-Item-int-) | Gibt das Element am angegebenen Index zurück. |
| [getUpDownBars()](#getUpDownBars--) | Stellt Zugriff auf Auf/Ab-Balken eines Linien- oder Kurs-Diagramms bereit. |
| [getGapWidth()](#getGapWidth--) | Gibt den Abstand zwischen Balken- oder Säulen-Clustern als Prozentsatz der Balken- oder Säulenbreite an. |
| [setGapWidth(int value)](#setGapWidth-int-) | Gibt den Abstand zwischen Balken- oder Säulen-Clustern als Prozentsatz der Balken- oder Säulenbreite an. |
| [getGapDepth()](#getGapDepth--) | Gibt die Entfernung als Prozentsatz der Markierungsbreite zwischen den Datenserien in einem 3D-Diagramm zurück oder legt sie fest. |
| [setGapDepth(int value)](#setGapDepth-int-) | Gibt die Entfernung als Prozentsatz der Markierungsbreite zwischen den Datenserien in einem 3D-Diagramm zurück oder legt sie fest. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | Gibt den Winkel des ersten Kuchens oder Donut-Diagrammsegments in Grad zurück oder legt ihn fest (im Uhrzeigersinn von oben, von 0 bis 360 Grad). |
| [setFirstSliceAngle(int value)](#setFirstSliceAngle-int-) | Gibt den Winkel des ersten Kuchens oder Donut-Diagrammsegments in Grad zurück oder legt ihn fest (im Uhrzeigersinn von oben, von 0 bis 360 Grad). |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Gibt die Größe des Lochs in einem Donut-Diagramm an (kann zwischen 0 und 90 % der Plot-Bereich-Größe liegen). |
| [setDoughnutHoleSize(byte value)](#setDoughnutHoleSize-byte-) | Gibt die Größe des Lochs in einem Donut-Diagramm an (kann zwischen 0 und 90 % der Plot-Bereich-Größe liegen). |
| [getOverlap()](#getOverlap--) | Gibt an, wie stark Balken und Säulen in 2-D-Diagrammen überlappen sollen, als Prozentsatz (von –100 % bis 100 %). |
| [setOverlap(byte value)](#setOverlap-byte-) | Gibt an, wie stark Balken und Säulen in 2-D-Diagrammen überlappen sollen, als Prozentsatz (von –100 % bis 100 %). |
| [getSecondPieSize()](#getSecondPieSize--) | Gibt die Größe des zweiten Kuchens oder Balkens eines Pie-of-Pie-Diagramms oder Bar-of-Pie-Diagramms als Prozentsatz der Größe des ersten Kuchens an (kann zwischen 5 % und 200 % liegen). |
| [setSecondPieSize(int value)](#setSecondPieSize-int-) | Gibt die Größe des zweiten Kuchens oder Balkens eines Pie-of-Pie-Diagramms oder Bar-of-Pie-Diagramms als Prozentsatz der Größe des ersten Kuchens an (kann zwischen 5 % und 200 % liegen). |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Gibt an, wie die Werte der Blasengröße im Blasendiagramm dargestellt werden. |
| [setBubbleSizeRepresentation(int value)](#setBubbleSizeRepresentation-int-) | Gibt an, wie die Werte der Blasengröße im Blasendiagramm dargestellt werden. |
| [getPieSplitPosition()](#getPieSplitPosition--) | Gibt einen Wert an, der verwendet wird, um zu bestimmen, welche Datenpunkte im zweiten Kuchen oder Balken eines Pie-of-Pie- oder Bar-of-Pie-Diagramms liegen. |
| [setPieSplitPosition(double value)](#setPieSplitPosition-double-) | Gibt einen Wert an, der verwendet wird, um zu bestimmen, welche Datenpunkte im zweiten Kuchen oder Balken eines Pie-of-Pie- oder Bar-of-Pie-Diagramms liegen. |
| [getPieSplitBy()](#getPieSplitBy--) | Gibt an, wie zu bestimmen ist, welche Datenpunkte im zweiten Kuchen oder Balken eines Pie-of-Pie- oder Bar-of-Pie-Diagramms liegen. |
| [setPieSplitBy(int value)](#setPieSplitBy-int-) | Gibt an, wie zu bestimmen ist, welche Datenpunkte im zweiten Kuchen oder Balken eines Pie-of-Pie- oder Bar-of-Pie-Diagramms liegen. |
| [isColorVaried()](#isColorVaried--) | Gibt an, dass jeder Datenmarker in der Serie eine andere Farbe hat. |
| [setColorVaried(boolean value)](#setColorVaried-boolean-) | Gibt an, dass jeder Datenmarker in der Serie eine andere Farbe hat. |
| [hasSeriesLines()](#hasSeriesLines--) | Wahr, wenn das Diagramm Serienlinien hat. |
| [setSeriesLines(boolean value)](#setSeriesLines-boolean-) | Wahr, wenn das Diagramm Serienlinien hat. |
| [getHiLowLinesFormat()](#getHiLowLinesFormat--) | Gibt das HiLowLines-Format an. |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Gibt den Skalierungsfaktor für das Blasendiagramm an (kann zwischen 0 und 300 % der Standardgröße liegen). |
| [setBubbleSizeScale(int value)](#setBubbleSizeScale-int-) | Gibt den Skalierungsfaktor für das Blasendiagramm an (kann zwischen 0 und 300 % der Standardgröße liegen). |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | Die benutzerdefinierten Split-Informationen für ein Pie-of-Pie- oder Bar-of-Pie-Diagramm mit einem benutzerdefinierten Split. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | Gibt das übergeordnete Diagramm zurück. |
| [getSlide()](#getSlide--) | Gibt die übergeordnete Folie eines FillFormat zurück. |
| [getPresentation()](#getPresentation--) | Gibt die übergeordnete Präsentation eines FillFormat zurück. |

### getType() {#getType--}
```
public final int getType()
```

Gibt einen Typ dieser Seriengruppe zurück. Nur lesbar [CombinableSeriesTypesGroup](../../com.aspose.slides/combinableseriestypesgroup).

**Rückgabe:**
int

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public final boolean getPlotOnSecondAxis()
```

Gibt an, ob Serien dieser Gruppe auf einer sekundären Achse dargestellt werden. Nur lesbar boolean.

**Rückgabe:**
boolean

### getSeries() {#getSeries--}
```
public final IChartSeriesReadonlyCollection getSeries()
```

Gibt eine Sammlung von Serien zurück. Nur lesbar [IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection).

**Rückgabe:**
[IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection)

### get_Item(int index) {#get-Item-int-}
```
public final IChartSeries get_Item(int index)
```

Gibt das Element am angegebenen Index zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int |  |

**Rückgabe:**
[IChartSeries](../../com.aspose.slides/ichartseries)

### getUpDownBars() {#getUpDownBars--}
```
public final IUpDownBarsManager getUpDownBars()
```

Stellt Zugriff auf Auf/Ab-Balken eines Linien- oder Kurs-Diagramms bereit. Nur lesbar [IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager).

**Rückgabe:**
[IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)

### getGapWidth() {#getGapWidth--}
```
public final int getGapWidth()
```

Gibt den Abstand zwischen Balken- oder Säulen-Clustern als Prozentsatz der Balken- oder Säulenbreite an. Lesen/Schreiben int.

**Rückgabe:**
int

### setGapWidth(int value) {#setGapWidth-int-}
```
public final void setGapWidth(int value)
```

Gibt den Abstand zwischen Balken- oder Säulen-Clustern als Prozentsatz der Balken- oder Säulenbreite an. Lesen/Schreiben int.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getGapDepth() {#getGapDepth--}
```
public final int getGapDepth()
```

Gibt die Entfernung als Prozentsatz der Markierungsbreite zwischen den Datenserien in einem 3D-Diagramm zurück oder legt sie fest. Lesen/Schreiben int.

**Rückgabe:**
int

### setGapDepth(int value) {#setGapDepth-int-}
```
public final void setGapDepth(int value)
```

Gibt die Entfernung als Prozentsatz der Markierungsbreite zwischen den Datenserien in einem 3D-Diagramm zurück oder legt sie fest. Lesen/Schreiben int.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public final int getFirstSliceAngle()
```

Gibt den Winkel des ersten Kuchens oder Donut-Diagrammsegments in Grad zurück oder legt ihn fest (im Uhrzeigersinn von oben, von 0 bis 360 Grad). Lesen/Schreiben int.

**Rückgabe:**
int

### setFirstSliceAngle(int value) {#setFirstSliceAngle-int-}
```
public final void setFirstSliceAngle(int value)
```

Gibt den Winkel des ersten Kuchens oder Donut-Diagrammsegments in Grad zurück oder legt ihn fest (im Uhrzeigersinn von oben, von 0 bis 360 Grad). Lesen/Schreiben int.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public final byte getDoughnutHoleSize()
```

Gibt die Größe des Lochs in einem Donut-Diagramm an (kann zwischen 0 und 90 % der Plot-Bereich-Größe liegen). Lesen/Schreiben byte.

**Rückgabe:**
byte

### setDoughnutHoleSize(byte value) {#setDoughnutHoleSize-byte-}
```
public final void setDoughnutHoleSize(byte value)
```

Gibt die Größe des Lochs in einem Donut-Diagramm an (kann zwischen 0 und 90 % der Plot-Bereich-Größe liegen). Lesen/Schreiben byte.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |

### getOverlap() {#getOverlap--}
```
public final byte getOverlap()
```

Gibt an, wie stark Balken und Säulen in 2-D-Diagrammen überlappen sollen, als Prozentsatz (von –100 % bis 100 %). –100 %: Maximale Trennung (Balken sind vollständig getrennt). –0 %: Balken liegen nebeneinander ohne Überlappung oder Abstand. 100 %: Maximale Überlappung (Balken überlappen vollständig). Diese Eigenschaft ist Lesen/Schreiben byte.

--------------------

> ```
> The following example demonstrates how to set the overlap for a chart series group 
>   and render the resulting chart on a form:
>   
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.ClusteredColumn, 10, 10, 600, 300);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      series.get_Item(0).getParentSeriesGroup().setOverlap((byte)55); // Set overlap to 55%
>      pres.getSlides().get_Item(0).getImage(1, 1).save("chart.png", ImageFormat.Png);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Rückgabe:**
byte

### setOverlap(byte value) {#setOverlap-byte-}
```
public final void setOverlap(byte value)
```

Gibt an, wie stark Balken und Säulen in 2-D-Diagrammen überlappen sollen, als Prozentsatz (von –100 % bis 100 %). –100 %: Maximale Trennung (Balken sind vollständig getrennt). –0 %: Balken liegen nebeneinander ohne Überlappung oder Abstand. 100 %: Maximale Überlappung (Balken überlappen vollständig). Diese Eigenschaft ist Lesen/Schreiben byte.

--------------------

> ```
> The following example demonstrates how to set the overlap for a chart series group 
>   and render the resulting chart on a form:
>   
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.ClusteredColumn, 10, 10, 600, 300);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      series.get_Item(0).getParentSeriesGroup().setOverlap((byte)55); // Set overlap to 55%
>      pres.getSlides().get_Item(0).getImage(1, 1).save("chart.png", ImageFormat.Png);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |

### getSecondPieSize() {#getSecondPieSize--}
```
public final int getSecondPieSize()
```

Gibt die Größe des zweiten Kuchens oder Balkens eines Pie-of-Pie-Diagramms oder Bar-of-Pie-Diagramms als Prozentsatz der Größe des ersten Kuchens an (kann zwischen 5 % und 200 % liegen). Lesen/Schreiben int.

**Rückgabe:**
int

### setSecondPieSize(int value) {#setSecondPieSize-int-}
```
public final void setSecondPieSize(int value)
```

Gibt die Größe des zweiten Kuchens oder Balkens eines Pie-of-Pie-Diagramms oder Bar-of-Pie-Diagramms als Prozentsatz der Größe des ersten Kuchens an (kann zwischen 5 % und 200 % liegen). Lesen/Schreiben int.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public final int getBubbleSizeRepresentation()
```

Gibt an, wie die Werte der Blasengröße im Blasendiagramm dargestellt werden. Lesen/Schreiben [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Rückgabe:**
int

### setBubbleSizeRepresentation(int value) {#setBubbleSizeRepresentation-int-}
```
public final void setBubbleSizeRepresentation(int value)
```

Gibt an, wie die Werte der Blasengröße im Blasendiagramm dargestellt werden. Lesen/Schreiben [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getPieSplitPosition() {#getPieSplitPosition--}
```
public final double getPieSplitPosition()
```

Gibt einen Wert an, der verwendet wird, um zu bestimmen, welche Datenpunkte im zweiten Kuchen oder Balken eines Pie-of-Pie- oder Bar-of-Pie-Diagramms liegen. Wird zusammen mit der Eigenschaft PieSplitBy verwendet. Lesen/Schreiben double.

**Rückgabe:**
double

### setPieSplitPosition(double value) {#setPieSplitPosition-double-}
```
public final void setPieSplitPosition(double value)
```

Gibt einen Wert an, der verwendet wird, um zu bestimmen, welche Datenpunkte im zweiten Kuchen oder Balken eines Pie-of-Pie- oder Bar-of-Pie-Diagramms liegen. Wird zusammen mit der Eigenschaft PieSplitBy verwendet. Lesen/Schreiben double.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |

### getPieSplitBy() {#getPieSplitBy--}
```
public final int getPieSplitBy()
```

Gibt an, wie zu bestimmen ist, welche Datenpunkte im zweiten Kuchen oder Balken eines Pie-of-Pie- oder Bar-of-Pie-Diagramms liegen. Lesen/Schreiben [PieSplitType](../../com.aspose.slides/piesplittype).

**Rückgabe:**
int

### setPieSplitBy(int value) {#setPieSplitBy-int-}
```
public final void setPieSplitBy(int value)
```

Gibt an, wie zu bestimmen ist, welche Datenpunkte im zweiten Kuchen oder Balken eines Pie-of-Pie- oder Bar-of-Pie-Diagramms liegen. Lesen/Schreiben [PieSplitType](../../com.aspose.slides/piesplittype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### isColorVaried() {#isColorVaried--}
```
public final boolean isColorVaried()
```

Gibt an, dass jeder Datenmarker in der Serie eine andere Farbe hat. Lesen/Schreiben boolean.

**Rückgabe:**
boolean

### setColorVaried(boolean value) {#setColorVaried-boolean-}
```
public final void setColorVaried(boolean value)
```

Gibt an, dass jeder Datenmarker in der Serie eine andere Farbe hat. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### hasSeriesLines() {#hasSeriesLines--}
```
public final boolean hasSeriesLines()
```

Wahr, wenn das Diagramm Serienlinien hat. Auf gestapelte Balken- und OfPie-Diagramme angewendet. Lesen/Schreiben boolean.

**Rückgabe:**
boolean

### setSeriesLines(boolean value) {#setSeriesLines-boolean-}
```
public final void setSeriesLines(boolean value)
```

Wahr, wenn das Diagramm Serienlinien hat. Auf gestapelte Balken- und OfPie-Diagramme angewendet. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getHiLowLinesFormat() {#getHiLowLinesFormat--}
```
public final IChartLinesFormat getHiLowLinesFormat()
```

Gibt das HiLowLines-Format an. HiLowLines wird mit den Diagrammtypen HiLowClose, OpenHiLowClose, VolumeHiLowClose und VolumeOpenHiLowClose verwendet.

**Rückgabe:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public final int getBubbleSizeScale()
```

Gibt den Skalierungsfaktor für das Blasendiagramm an (kann zwischen 0 und 300 % der Standardgröße liegen). Lesen/Schreiben int.

**Rückgabe:**
int

### setBubbleSizeScale(int value) {#setBubbleSizeScale-int-}
```
public final void setBubbleSizeScale(int value)
```

Gibt den Skalierungsfaktor für das Blasendiagramm an (kann zwischen 0 und 300 % der Standardgröße liegen). Lesen/Schreiben int.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public final IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

Die benutzerdefinierten Split-Informationen für ein Pie-of-Pie- oder Bar-of-Pie-Diagramm mit einem benutzerdefinierten Split. Enthält Datenpunkte, die im zweiten Kuchen oder Balken eines Pie-of-Pie- oder Bar-of-Pie-Diagramms gezeichnet werden sollen. Nur lesbar [PieSplitCustomPointCollection](../../com.aspose.slides/piesplitcustompointcollection).

**Rückgabe:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Gibt das Parent_Immediate-Objekt zurück. Nur lesbar IDOMObject.

**Rückgabe:**
com.aspose.slides.IDOMObject

### getChart() {#getChart--}
```
public final IChart getChart()
```

Gibt das übergeordnete Diagramm zurück. Nur lesbar [IChart](../../com.aspose.slides/ichart).

**Rückgabe:**
[IChart](../../com.aspose.slides/ichart)

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