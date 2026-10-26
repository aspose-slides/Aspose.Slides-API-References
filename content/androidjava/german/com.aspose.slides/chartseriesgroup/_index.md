---
title: ChartSeriesGroup
second_title: Aspose.Slides für Android über die Java-API-Referenz
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

1) Siehe Zusammenfassung und Anmerkungen zur Klasse ChartSeriesGroupCollection und zum Enum CombinableSeriesTypesGroup. 2) Die Gruppe von Serien enthält einige Serieneigenschaften, die für jede Serie in der Gruppe gemeinsam sind („series group properties“). „Series group properties“ in der Klasse ChartSeriesGroup ist lesbar/schreibbar. Jede „series group properties“ kann in der Klasse ChartSeries eine schreibgeschützte Projektion haben.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getType()](#getType--) | Gibt einen Typ dieser Seriengruppe zurück. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Gibt an, ob die Serien dieser Gruppe auf einer sekundären Achse dargestellt werden. |
| [getSeries()](#getSeries--) | Gibt eine Sammlung von Serien zurück. |
| [get_Item(int index)](#get-Item-int-) | Liefert das Element am angegebenen Index. |
| [getUpDownBars()](#getUpDownBars--) | Stellt Zugriff auf Auf/Ab-Balken von Linien- oder Kursdiagrammen bereit. |
| [getGapWidth()](#getGapWidth--) | Gibt den Abstand zwischen Balken- oder Spaltenclustern als Prozentsatz der Balken- bzw. Spaltenbreite an. |
| [setGapWidth(int value)](#setGapWidth-int-) | Gibt den Abstand zwischen Balken- oder Spaltenclustern als Prozentsatz der Balken- bzw. Spaltenbreite an. |
| [getGapDepth()](#getGapDepth--) | Gibt die Entfernung als Prozentsatz der Markierungsbreite zwischen den Datenserien in einem 3D-Diagramm zurück oder legt sie fest. |
| [setGapDepth(int value)](#setGapDepth-int-) | Gibt die Entfernung als Prozentsatz der Markierungsbreite zwischen den Datenserien in einem 3D-Diagramm zurück oder legt sie fest. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | Liefert oder legt den Winkel des ersten Kuchen- oder Donut-Diagrammsegments in Grad fest (im Uhrzeigersinn von oben, von 0 bis 360 Grad). |
| [setFirstSliceAngle(int value)](#setFirstSliceAngle-int-) | Liefert oder legt den Winkel des ersten Kuchen- oder Donut-Diagrammsegments in Grad fest (im Uhrzeigersinn von oben, von 0 bis 360 Grad). |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Gibt die Größe des Lochs in einem Donut-Diagramm an (kann zwischen 0 und 90 % der Plotbereichsgröße liegen). |
| [setDoughnutHoleSize(byte value)](#setDoughnutHoleSize-byte-) | Gibt die Größe des Lochs in einem Donut-Diagramm an (kann zwischen 0 und 90 % der Plotbereichsgröße liegen). |
| [getOverlap()](#getOverlap--) | Gibt an, wie stark Balken und Spalten in 2-D-Diagrammen überlappen sollen, als Prozentsatz (von -100 % bis 100 %). |
| [setOverlap(byte value)](#setOverlap-byte-) | Gibt an, wie stark Balken und Spalten in 2-D-Diagrammen überlappen sollen, als Prozentsatz (von -100 % bis 100 %). |
| [getSecondPieSize()](#getSecondPieSize--) | Gibt die Größe des zweiten Kuchens oder Balkens eines Pie-of-Pie- bzw. Bar-of-Pie-Diagramms als Prozentsatz der Größe des ersten Kuchens an (kann zwischen 5 und 200 % liegen). |
| [setSecondPieSize(int value)](#setSecondPieSize-int-) | Gibt die Größe des zweiten Kuchens oder Balkens eines Pie-of-Pie- bzw. Bar-of-Pie-Diagramms als Prozentsatz der Größe des ersten Kuchens an (kann zwischen 5 und 200 % liegen). |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Gibt an, wie die Bubble-Größenwerte im Blasendiagramm dargestellt werden. |
| [setBubbleSizeRepresentation(int value)](#setBubbleSizeRepresentation-int-) | Gibt an, wie die Bubble-Größenwerte im Blasendiagramm dargestellt werden. |
| [getPieSplitPosition()](#getPieSplitPosition--) | Gibt einen Wert an, der verwendet wird, um zu bestimmen, welche Datenpunkte im zweiten Kuchen oder Balken eines Pie-of-Pie- bzw. Bar-of-Pie-Diagramms liegen. |
| [setPieSplitPosition(double value)](#setPieSplitPosition-double-) | Gibt einen Wert an, der verwendet wird, um zu bestimmen, welche Datenpunkte im zweiten Kuchen oder Balken eines Pie-of-Pie- bzw. Bar-of-Pie-Diagramms liegen. |
| [getPieSplitBy()](#getPieSplitBy--) | Gibt an, wie zu bestimmen ist, welche Datenpunkte im zweiten Kuchen oder Balken eines Pie-of-Pie- bzw. Bar-of-Pie-Diagramms liegen. |
| [setPieSplitBy(int value)](#setPieSplitBy-int-) | Gibt an, wie zu bestimmen ist, welche Datenpunkte im zweiten Kuchen oder Balken eines Pie-of-Pie- bzw. Bar-of-Pie-Diagramms liegen. |
| [isColorVaried()](#isColorVaried--) | Gibt an, dass jeder Datenmarker in der Serie eine andere Farbe hat. |
| [setColorVaried(boolean value)](#setColorVaried-boolean-) | Gibt an, dass jeder Datenmarker in der Serie eine andere Farbe hat. |
| [hasSeriesLines()](#hasSeriesLines--) | True, wenn das Diagramm Serienlinien hat. |
| [setSeriesLines(boolean value)](#setSeriesLines-boolean-) | True, wenn das Diagramm Serienlinien hat. |
| [getHiLowLinesFormat()](#getHiLowLinesFormat--) | Gibt das HiLowLines-Format an. |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Gibt den Skalierungsfaktor für das Blasendiagramm an (kann zwischen 0 und 300 % der Standardgröße liegen). |
| [setBubbleSizeScale(int value)](#setBubbleSizeScale-int-) | Gibt den Skalierungsfaktor für das Blasendiagramm an (kann zwischen 0 und 300 % der Standardgröße liegen). |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | Die benutzerdefinierten Split-Informationen für ein Pie-of-Pie- oder Bar-of-Pie-Diagramm mit benutzerdefiniertem Split. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | Gibt das übergeordnete Diagramm zurück. |
| [getSlide()](#getSlide--) | Gibt die übergeordnete Folie eines FillFormat zurück. |
| [getPresentation()](#getPresentation--) | Gibt die übergeordnete Präsentation eines FillFormat zurück. |

### getType() {#getType--}
```
public final int getType()
```

Gibt einen Typ dieser Seriengruppe zurück. Schreibgeschützt [CombinableSeriesTypesGroup](../../com.aspose.slides/combinableseriestypesgroup).

**Rückgabe:**
int

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public final boolean getPlotOnSecondAxis()
```

Gibt an, ob die Serien dieser Gruppe auf einer sekundären Achse dargestellt werden. Schreibgeschützt boolean.

**Rückgabe:**
boolean

### getSeries() {#getSeries--}
```
public final IChartSeriesReadonlyCollection getSeries()
```

Gibt eine Sammlung von Serien zurück. Schreibgeschützt [IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection).

**Rückgabe:**
[IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection)

### get_Item(int index) {#get-Item-int-}
```
public final IChartSeries get_Item(int index)
```

Liefert das Element am angegebenen Index.

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

Stellt Zugriff auf Auf/Ab-Balken von Linien- oder Kursdiagrammen bereit. Schrijfgeschützt [IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager).

**Rückgabe:**
[IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)

### getGapWidth() {#getGapWidth--}
```
public final int getGapWidth()
```

Gibt den Abstand zwischen Balken- oder Spaltenclustern als Prozentsatz der Balken- bzw. Spaltenbreite an. Lesbar/schreibbar int.

**Rückgabe:**
int

### setGapWidth(int value) {#setGapWidth-int-}
```
public final void setGapWidth(int value)
```

Gibt den Abstand zwischen Balken- oder Spaltenclustern als Prozentsatz der Balken- bzw. Spaltenbreite an. Lesbar/schreibbar int.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getGapDepth() {#getGapDepth--}
```
public final int getGapDepth()
```

Gibt die Entfernung als Prozentsatz der Markierungsbreite zwischen den Datenserien in einem 3D-Diagramm zurück oder legt sie fest. Lesbar/schreibbar int.

**Rückgabe:**
int

### setGapDepth(int value) {#setGapDepth-int-}
```
public final void setGapDepth(int value)
```

Gibt die Entfernung als Prozentsatz der Markierungsbreite zwischen den Datenserien in einem 3D-Diagramm zurück oder legt sie fest. Lesbar/schreibbar int.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public final int getFirstSliceAngle()
```

Liefert oder legt den Winkel des ersten Kuchen- oder Donut-Diagrammsegments in Grad fest (im Uhrzeigersinn von oben, von 0 bis 360 Grad). Lesbar/schreibbar int.

**Rückgabe:**
int

### setFirstSliceAngle(int value) {#setFirstSliceAngle-int-}
```
public final void setFirstSliceAngle(int value)
```

Liefert oder legt den Winkel des ersten Kuchen- oder Donut-Diagrammsegments in Grad fest (im Uhrzeigersinn von oben, von 0 bis 360 Grad). Lesbar/schreibbar int.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public final byte getDoughnutHoleSize()
```

Gibt die Größe des Lochs in einem Donut-Diagramm an (kann zwischen 0 und 90 % der Plotbereichsgröße liegen). Lesbar/schreibbar byte.

**Rückgabe:**
byte

### setDoughnutHoleSize(byte value) {#setDoughnutHoleSize-byte-}
```
public final void setDoughnutHoleSize(byte value)
```

Gibt die Größe des Lochs in einem Donut-Diagramm an (kann zwischen 0 und 90 % der Plotbereichsgröße liegen). Lesbar/schreibbar byte.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |

### getOverlap() {#getOverlap--}
```
public final byte getOverlap()
```

Gibt an, wie stark Balken und Spalten in 2-D-Diagrammen überlappen sollen, als Prozentsatz (von -100 % bis 100 %). -100 %: Maximale Trennung (Balken sind vollständig getrennt). -0 %: Balken stehen nebeneinander ohne Überlappung oder Abstand. 100 %: Maximale Überlappung (Balken überlappen komplett). Diese Eigenschaft ist lesbar/schreibbar byte.

--------------------

> ```
> The following example demonstrates how to set the overlap for a chart series group 
>   and render the resulting chart on a form:
>   
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.ClusteredColumn, 10, 10, 600, 300);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      series.get_Item(0).getParentSeriesGroup().setOverlap((byte)55); // Setze die Überlappung auf 55%
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

Gibt an, wie stark Balken und Spalten in 2-D-Diagrammen überlappen sollen, als Prozentsatz (von -100 % bis 100 %). -100 %: Maximale Trennung (Balken sind vollständig getrennt). -0 %: Balken stehen nebeneinander ohne Überlappung oder Abstand. 100 %: Maximale Überlappung (Balken überlappen komplett). Diese Eigenschaft ist lesbar/schreibbar byte.

--------------------

> ```
> The following example demonstrates how to set the overlap for a chart series group 
>   and render the resulting chart on a form:
>   
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.ClusteredColumn, 10, 10, 600, 300);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      series.get_Item(0).getParentSeriesGroup().setOverlap((byte)55); // Setze die Überlappung auf 55%
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

Gibt die Größe des zweiten Kuchens oder Balkens eines Pie-of-Pie- bzw. Bar-of-Pie-Diagramms als Prozentsatz der Größe des ersten Kuchens an (kann zwischen 5 und 200 % liegen). Lesbar/schreibbar int.

**Rückgabe:**
int

### setSecondPieSize(int value) {#setSecondPieSize-int-}
```
public final void setSecondPieSize(int value)
```

Gibt die Größe des zweiten Kuchens oder Balkens eines Pie-of-Pie- bzw. Bar-of-Pie-Diagramms als Prozentsatz der Größe des ersten Kuchens an (kann zwischen 5 und 200 % liegen). Lesbar/schreibbar int.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public final int getBubbleSizeRepresentation()
```

Gibt an, wie die Bubble-Größenwerte im Blasendiagramm dargestellt werden. Lesbar/schreibbar [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Rückgabe:**
int

### setBubbleSizeRepresentation(int value) {#setBubbleSizeRepresentation-int-}
```
public final void setBubbleSizeRepresentation(int value)
```

Gibt an, wie die Bubble-Größenwerte im Blasendiagramm dargestellt werden. Lesbar/schreibbar [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getPieSplitPosition() {#getPieSplitPosition--}
```
public final double getPieSplitPosition()
```

Gibt einen Wert an, der verwendet wird, um zu bestimmen, welche Datenpunkte im zweiten Kuchen oder Balken eines Pie-of-Pie- bzw. Bar-of-Pie-Diagramms liegen. Wird zusammen mit der Eigenschaft PieSplitBy verwendet. Lesbar/schreibbar double.

**Rückgabe:**
double

### setPieSplitPosition(double value) {#setPieSplitPosition-double-}
```
public final void setPieSplitPosition(double value)
```

Gibt einen Wert an, der verwendet wird, um zu bestimmen, welche Datenpunkte im zweiten Kuchen oder Balken eines Pie-of-Pie- bzw. Bar-of-Pie-Diagramms liegen. Wird zusammen mit der Eigenschaft PieSplitBy verwendet. Lesbar/schreibbar double.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |

### getPieSplitBy() {#getPieSplitBy--}
```
public final int getPieSplitBy()
```

Gibt an, wie zu bestimmen ist, welche Datenpunkte im zweiten Kuchen oder Balken eines Pie-of-Pie- bzw. Bar-of-Pie-Diagramms liegen. Lesbar/schreibbar [PieSplitType](../../com.aspose.slides/piesplittype).

**Rückgabe:**
int

### setPieSplitBy(int value) {#setPieSplitBy-int-}
```
public final void setPieSplitBy(int value)
```

Gibt an, wie zu bestimmen ist, welche Datenpunkte im zweiten Kuchen oder Balken eines Pie-of-Pie- bzw. Bar-of-Pie-Diagramms liegen. Lesbar/schreibbar [PieSplitType](../../com.aspose.slides/piesplittype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### isColorVaried() {#isColorVaried--}
```
public final boolean isColorVaried()
```

Gibt an, dass jeder Datenmarker in der Serie eine andere Farbe hat. Lesbar/schreibbar boolean.

**Rückgabe:**
boolean

### setColorVaried(boolean value) {#setColorVaried-boolean-}
```
public final void setColorVaried(boolean value)
```

Gibt an, dass jeder Datenmarker in der Serie eine andere Farbe hat. Lesbar/schreibbar boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### hasSeriesLines() {#hasSeriesLines--}
```
public final boolean hasSeriesLines()
```

True, wenn das Diagramm Serienlinien hat. Gilt für gestapelte Balken- und OfPie-Diagramme. Lesbar/schreibbar boolean.

**Rückgabe:**
boolean

### setSeriesLines(boolean value) {#setSeriesLines-boolean-}
```
public final void setSeriesLines(boolean value)
```

True, wenn das Diagramm Serienlinien hat. Gilt für gestapelte Balken- und OfPie-Diagramme. Lesbar/schreibbar boolean.

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

Gibt den Skalierungsfaktor für das Blasendiagramm an (kann zwischen 0 und 300 % der Standardgröße liegen). Lesbar/schreibbar int.

**Rückgabe:**
int

### setBubbleSizeScale(int value) {#setBubbleSizeScale-int-}
```
public final void setBubbleSizeScale(int value)
```

Gibt den Skalierungsfaktor für das Blasendiagramm an (kann zwischen 0 und 300 % der Standardgröße liegen). Lesbar/schreibbar int.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public final IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

Die benutzerdefinierten Split-Informationen für ein Pie-of-Pie- oder Bar-of-Pie-Diagramm mit benutzerdefiniertem Split. Enthält Datenpunkte, die im zweiten Kuchen oder Balken eines Pie-of-Pie- bzw. Bar-of-Pie-Diagramms gezeichnet werden sollen. Schrijfgeschützt [PieSplitCustomPointCollection](../../com.aspose.slides/piesplitcustompointcollection).

**Rückgabe:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Gibt das Parent_Immediate-Objekt zurück. Schrijfgeschützt IDOMObject.

**Rückgabe:**
com.aspose.slides.IDOMObject

### getChart() {#getChart--}
```
public final IChart getChart()
```

Gibt das übergeordnete Diagramm zurück. Schrijfgeschützt [IChart](../../com.aspose.slides/ichart).

**Rückgabe:**
[IChart](../../com.aspose.slides/ichart)

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Gibt die übergeordnete Folie eines FillFormat zurück. Schrijfgeschützt [BaseSlide](../../com.aspose.slides/baseslide).

**Rückgabe:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Gibt die übergeordnete Präsentation eines FillFormat zurück. Schrijfgeschützt [IPresentation](../../com.aspose.slides/ipresentation).

**Rückgabe:**
[IPresentation](../../com.aspose.slides/ipresentation)