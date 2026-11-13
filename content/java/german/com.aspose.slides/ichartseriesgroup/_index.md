---
title: IChartSeriesGroup
second_title: Aspose.Slides für Java API Referenz
description: Stellt eine Gruppe von Serien dar.
type: docs
url: /de/com.aspose.slides/ichartseriesgroup/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IChartSeriesGroup extends IChartComponent
```

Stellt eine Gruppe von Serien dar.

--------------------

1) Siehe Zusammenfassung und Anmerkungen für die Klasse ChartSeriesGroupCollection und das Aufzählungsfeld CombinableSeriesTypesGroup. 2) Eine Gruppe von Serien enthält einige Serien-Eigenschaften, die für jede Serie in der Gruppe gemeinsam sind („Serien-Gruppeneigenschaften“). „Serien-Gruppeneigenschaften“ in der Klasse ChartSeriesGroup sind Lese/Schreib. Jede der „Serien-Gruppeneigenschaften“ kann in der Klasse ChartSeries eine nur-lesbare Projektion haben.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getType()](#getType--) | Gibt einen Typ dieser Seriengruppe zurück. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Gibt an, ob die Serien dieser Gruppe auf einer sekundären Achse geplottet werden. |
| [getSeries()](#getSeries--) | Gibt eine nur-lesbare Auflistung von Diagrammserien zurück. |
| [get_Item(int index)](#get-Item-int-) | Ruft das Element am angegebenen Index ab. |
| [getUpDownBars()](#getUpDownBars--) | Stellt Zugriff auf Auf-/Ab-Bars von Linien- oder Kurs-Diagramm bereit. |
| [getGapWidth()](#getGapWidth--) | Ruft den Abstand zwischen Balken- oder Säulen-Clustern ab oder legt ihn fest, als Prozentsatz der Balken- oder Säulenbreite. |
| [setGapWidth(int value)](#setGapWidth-int-) | Ruft den Abstand zwischen Balken- oder Säulen-Clustern ab oder legt ihn fest, als Prozentsatz der Balken- oder Säulenbreite. |
| [getGapDepth()](#getGapDepth--) | Ruft den Abstand zwischen Datenserien in einem 3D-Diagramm ab oder legt ihn fest, als Prozentsatz der Markierungsbreite. |
| [setGapDepth(int value)](#setGapDepth-int-) | Ruft den Abstand zwischen Datenserien in einem 3D-Diagramm ab oder legt ihn fest, als Prozentsatz der Markierungsbreite. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | Ruft den Winkel des ersten Kuchen- oder Donut-Diagrammsegments ab oder legt ihn fest, in Grad (im Uhrzeigersinn von oben, von 0 bis 360 Grad). |
| [setFirstSliceAngle(int value)](#setFirstSliceAngle-int-) | Ruft den Winkel des ersten Kuchen- oder Donut-Diagrammsegments ab oder legt ihn fest, in Grad (im Uhrzeigersinn von oben, von 0 bis 360 Grad). |
| [isColorVaried()](#isColorVaried--) | Gibt an, dass jeder Datenmarker in der Serie eine andere Farbe hat. |
| [setColorVaried(boolean value)](#setColorVaried-boolean-) | Gibt an, dass jeder Datenmarker in der Serie eine andere Farbe hat. |
| [hasSeriesLines()](#hasSeriesLines--) | Wahr, wenn das Diagramm Serienlinien hat. |
| [setSeriesLines(boolean value)](#setSeriesLines-boolean-) | Wahr, wenn das Diagramm Serienlinien hat. |
| [getOverlap()](#getOverlap--) | Gibt an, wie stark Balken und Säulen in 2-D-Diagrammen überlappen sollen, als Prozentsatz (von -100 % bis 100 %). |
| [setOverlap(byte value)](#setOverlap-byte-) | Gibt an, wie stark Balken und Säulen in 2-D-Diagrammen überlappen sollen, als Prozentsatz (von -100 % bis 100 %). |
| [getSecondPieSize()](#getSecondPieSize--) | Gibt die Größe des zweiten Kuchens oder Balkens eines Pie-of-Pie-Diagramms oder Bar-of-Pie-Diagramms an, als Prozentsatz der Größe des ersten Kuchens (kann zwischen 5 % und 200 % liegen). |
| [setSecondPieSize(int value)](#setSecondPieSize-int-) | Gibt die Größe des zweiten Kuchens oder Balkens eines Pie-of-Pie-Diagramms oder Bar-of-Pie-Diagramms an, als Prozentsatz der Größe des ersten Kuchens (kann zwischen 5 % und 200 % liegen). |
| [getPieSplitPosition()](#getPieSplitPosition--) | Gibt einen Wert an, der verwendet wird, um zu bestimmen, welche Datenpunkte im zweiten Kuchen oder Balken eines Pie-of-Pie- bzw. Bar-of-Pie-Diagramms liegen. |
| [setPieSplitPosition(double value)](#setPieSplitPosition-double-) | Gibt einen Wert an, der verwendet wird, um zu bestimmen, welche Datenpunkte im zweiten Kuchen oder Balken eines Pie-of-Pie- bzw. Bar-of-Pie-Diagramms liegen. |
| [getPieSplitBy()](#getPieSplitBy--) | Gibt an, wie zu bestimmen ist, welche Datenpunkte im zweiten Kuchen oder Balken eines Pie-of-Pie- bzw. Bar-of-Pie-Diagramms liegen. |
| [setPieSplitBy(int value)](#setPieSplitBy-int-) | Gibt an, wie zu bestimmen ist, welche Datenpunkte im zweiten Kuchen oder Balken eines Pie-of-Pie- bzw. Bar-of-Pie-Diagramms liegen. |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | Die benutzerdefinierten Split-Informationen für ein Pie-of-Pie- oder Bar-of-Pie-Diagramm mit benutzerdefiniertem Split. |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Gibt die Größe des Lochs in einem Donut-Diagramm an (kann zwischen 10 % und 90 % der Plot-Fläche liegen). |
| [setDoughnutHoleSize(byte value)](#setDoughnutHoleSize-byte-) | Gibt die Größe des Lochs in einem Donut-Diagramm an (kann zwischen 10 % und 90 % der Plot-Fläche liegen). |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Gibt den Skalierungsfaktor für das Blasendiagramm an (kann zwischen 0 % und 300 % der Standardgröße liegen). |
| [setBubbleSizeScale(int value)](#setBubbleSizeScale-int-) | Gibt den Skalierungsfaktor für das Blasendiagramm an (kann zwischen 0 % und 300 % der Standardgröße liegen). |
| [getHiLowLinesFormat()](#getHiLowLinesFormat--) | Gibt das HiLowLines-Format an. |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Gibt an, wie die Werte der Blasengröße im Blasendiagramm dargestellt werden. |
| [setBubbleSizeRepresentation(int value)](#setBubbleSizeRepresentation-int-) | Gibt an, wie die Werte der Blasengröße im Blasendiagramm dargestellt werden. |

### getType() {#getType--}
```
public abstract int getType()
```

Gibt einen Typ dieser Seriengruppe zurück. Nur-Lese [CombinableSeriesTypesGroup](../../com.aspose.slides/combinableseriestypesgroup).

**Rückgabewert:**
int

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public abstract boolean getPlotOnSecondAxis()
```

Gibt an, ob die Serien dieser Gruppe auf einer sekundären Achse geplottet werden. Nur-Lese boolean.

**Rückgabewert:**
boolean

### getSeries() {#getSeries--}
```
public abstract IChartSeriesReadonlyCollection getSeries()
```

Gibt eine nur-lesbare Auflistung von Diagrammserien zurück. Nur-Lese [IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection).

**Rückgabewert:**
[IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection)

### get_Item(int index) {#get-Item-int-}
```
public abstract IChartSeries get_Item(int index)
```

Ruft das Element am angegebenen Index ab.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int |  |

**Rückgabewert:**
[IChartSeries](../../com.aspose.slides/ichartseries)

### getUpDownBars() {#getUpDownBars--}
```
public abstract IUpDownBarsManager getUpDownBars()
```

Stellt Zugriff auf Auf-/Ab-Bars von Linien- oder Kurs-Diagramm bereit. Nur-Lese [IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager).

**Rückgabewert:**
[IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)

### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```

Ruft den Abstand zwischen Balken- oder Säulen-Clustern ab oder legt ihn fest, als Prozentsatz der Balken- oder Säulenbreite. Der Wert muss zwischen 0 und 500 liegen. Lese/Schreib int.

--------------------

Diese Eigenschaft gilt für Serien der folgenden Typen: Alle Balken- und Säulenuntertypen, [ChartType.BarOfPie](../../com.aspose.slides/charttype\#BarOfPie), [ChartType.PieOfPie](../../com.aspose.slides/charttype\#PieOfPie), [ChartType.BoxAndWhisker](../../com.aspose.slides/charttype\#BoxAndWhisker), [ChartType.Funnel](../../com.aspose.slides/charttype\#Funnel), [ChartType.Histogram](../../com.aspose.slides/charttype\#Histogram), [ChartType.Waterfall](../../com.aspose.slides/charttype\#Waterfall).

**Rückgabewert:**
int

### setGapWidth(int value) {#setGapWidth-int-}
```
public abstract void setGapWidth(int value)
```

Ruft den Abstand zwischen Balken- oder Säulen-Clustern ab oder legt ihn fest, als Prozentsatz der Balken- oder Säulenbreite. Der Wert muss zwischen 0 und 500 liegen. Lese/Schreib int.

--------------------

Diese Eigenschaft gilt für Serien der folgenden Typen: Alle Balken- und Säulenuntertypen, [ChartType.BarOfPie](../../com.aspose.slides/charttype\#BarOfPie), [ChartType.PieOfPie](../../com.aspose.slides/charttype\#PieOfPie), [ChartType.BoxAndWhisker](../../com.aspose.slides/charttype\#BoxAndWhisker), [ChartType.Funnel](../../com.aspose.slides/charttype\#Funnel), [ChartType.Histogram](../../com.aspose.slides/charttype\#Histogram), [ChartType.Waterfall](../../com.aspose.slides/charttype\#Waterfall).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getGapDepth() {#getGapDepth--}
```
public abstract int getGapDepth()
```

Ruft den Abstand zwischen Datenserien in einem 3D-Diagramm ab oder legt ihn fest, als Prozentsatz der Markierungsbreite. Der Wert muss zwischen 0 und 500 liegen. Lese/Schreib int.

--------------------

Diese Eigenschaft gilt für Serien der folgenden Typen: 3D-Balken- und Säulen-Untertypen, [ChartType.Line3D](../../com.aspose.slides/charttype\#Line3D), [ChartType.Area3D](../../com.aspose.slides/charttype\#Area3D), [ChartType.StackedArea3D](../../com.aspose.slides/charttype\#StackedArea3D), [ChartType.PercentsStackedArea3D](../../com.aspose.slides/charttype\#PercentsStackedArea3D).

**Rückgabewert:**
int

### setGapDepth(int value) {#setGapDepth-int-}
```
public abstract void setGapDepth(int value)
```

Ruft den Abstand zwischen Datenserien in einem 3D-Diagramm ab oder legt ihn fest, als Prozentsatz der Markierungsbreite. Der Wert muss zwischen 0 und 500 liegen. Lese/Schreib int.

--------------------

Diese Eigenschaft gilt für Serien der folgenden Typen: 3D-Balken- und Säulen-Untertypen, [ChartType.Line3D](../../com.aspose.slides/charttype\#Line3D), [ChartType.Area3D](../../com.aspose.slides/charttype\#Area3D), [ChartType.StackedArea3D](../../com.aspose.slides/charttype\#StackedArea3D), [ChartType.PercentsStackedArea3D](../../com.aspose.slides/charttype\#PercentsStackedArea3D).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public abstract int getFirstSliceAngle()
```

Ruft den Winkel des ersten Kuchen- oder Donut-Diagrammsegments ab oder legt ihn fest, in Grad (im Uhrzeigersinn von oben, von 0 bis 360 Grad). Lese/Schreib int.

**Rückgabewert:**
int

### setFirstSliceAngle(int value) {#setFirstSliceAngle-int-}
```
public abstract void setFirstSliceAngle(int value)
```

Ruft den Winkel des ersten Kuchen- oder Donut-Diagrammsegments ab oder legt ihn fest, in Grad (im Uhrzeigersinn von oben, von 0 bis 360 Grad). Lese/Schreib int.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### isColorVaried() {#isColorVaried--}
```
public abstract boolean isColorVaried()
```

Gibt an, dass jeder Datenmarker in der Serie eine andere Farbe hat. Lese/Schreib boolean.

**Rückgabewert:**
boolean

### setColorVaried(boolean value) {#setColorVaried-boolean-}
```
public abstract void setColorVaried(boolean value)
```

Gibt an, dass jeder Datenmarker in der Serie eine andere Farbe hat. Lese/Schreib boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### hasSeriesLines() {#hasSeriesLines--}
```
public abstract boolean hasSeriesLines()
```

Wahr, wenn das Diagramm Serienlinien hat. Gilt für gestapelte Balken- und OfPie-Diagramme. Lese/Schreib boolean.

**Rückgabewert:**
boolean

### setSeriesLines(boolean value) {#setSeriesLines-boolean-}
```
public abstract void setSeriesLines(boolean value)
```

Wahr, wenn das Diagramm Serienlinien hat. Gilt für gestapelte Balken- und OfPie-Diagramme. Lese/Schreib boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getOverlap() {#getOverlap--}
```
public abstract byte getOverlap()
```

Gibt an, wie stark Balken und Säulen in 2-D-Diagrammen überlappen sollen, als Prozentsatz (von -100 % bis 100 %). - -100 %: maximaler Abstand (Balken sind komplett getrennt). - 0 %: Balken werden nebeneinander ohne Überlappung oder Abstand platziert. - 100 %: maximale Überlappung (Balken überlappen sich vollständig). Diese Eigenschaft ist Lese/Schreib byte.

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
>      pres.getSlides().get_Item(0).getImage(1, 1).save("chart.png");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Rückgabewert:**
byte

### setOverlap(byte value) {#setOverlap-byte-}
```
public abstract void setOverlap(byte value)
```

Gibt an, wie stark Balken und Säulen in 2-D-Diagrammen überlappen sollen, als Prozentsatz (von -100 % bis 100 %). - -100 %: maximaler Abstand (Balken sind komplett getrennt). - 0 %: Balken werden nebeneinander ohne Überlappung oder Abstand platziert. - 100 %: maximale Überlappung (Balken überlappen sich vollständig). Diese Eigenschaft ist Lese/Schreib byte.

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
public abstract int getSecondPieSize()
```

Gibt die Größe des zweiten Kuchens oder Balkens eines Pie-of-Pie-Diagramms oder Bar-of-Pie-Diagramms an, als Prozentsatz der Größe des ersten Kuchens (kann zwischen 5 % und 200 % liegen). Lese/Schreib int.

**Rückgabewert:**
int

### setSecondPieSize(int value) {#setSecondPieSize-int-}
```
public abstract void setSecondPieSize(int value)
```

Gibt die Größe des zweiten Kuchens oder Balkens eines Pie-of-Pie-Diagramms oder Bar-of-Pie-Diagramms an, als Prozentsatz der Größe des ersten Kuchens (kann zwischen 5 % und 200 % liegen). Lese/Schreib int.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getPieSplitPosition() {#getPieSplitPosition--}
```
public abstract double getPieSplitPosition()
```

Gibt einen Wert an, der verwendet wird, um zu bestimmen, welche Datenpunkte im zweiten Kuchen oder Balken eines Pie-of-Pie- bzw. Bar-of-Pie-Diagramms liegen. Wird zusammen mit der Eigenschaft PieSplitBy verwendet. Lese/Schreib double.

**Rückgabewert:**
double

### setPieSplitPosition(double value) {#setPieSplitPosition-double-}
```
public abstract void setPieSplitPosition(double value)
```

Gibt einen Wert an, der verwendet wird, um zu bestimmen, welche Datenpunkte im zweiten Kuchen oder Balken eines Pie-of-Pie- bzw. Bar-of-Pie-Diagramms liegen. Wird zusammen mit der Eigenschaft PieSplitBy verwendet. Lese/Schreib double.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |

### getPieSplitBy() {#getPieSplitBy--}
```
public abstract int getPieSplitBy()
```

Gibt an, wie zu bestimmen ist, welche Datenpunkte im zweiten Kuchen oder Balken eines Pie-of-Pie- bzw. Bar-of-Pie-Diagramms liegen. Lese/Schreib [PieSplitType](../../com.aspose.slides/piesplittype).

**Rückgabewert:**
int

### setPieSplitBy(int value) {#setPieSplitBy-int-}
```
public abstract void setPieSplitBy(int value)
```

Gibt an, wie zu bestimmen ist, welche Datenpunkte im zweiten Kuchen oder Balken eines Pie-of-Pie- bzw. Bar-of-Pie-Diagramms liegen. Lese/Schreib [PieSplitType](../../com.aspose.slides/piesplittype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public abstract IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

Die benutzerdefinierten Split-Informationen für ein Pie-of-Pie- bzw. Bar-of-Pie-Diagramm mit benutzerdefiniertem Split. Enthält Datenpunkte, die im zweiten Kuchen oder Balken eines Pie-of-Pie- bzw. Bar-of-Pie-Diagramms gezeichnet werden sollen. Nur-Lese [IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection).

**Rückgabewert:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public abstract byte getDoughnutHoleSize()
```

Gibt die Größe des Lochs in einem Donut-Diagramm an (kann zwischen 10 % und 90 % der Plot-Fläche liegen). Lese/Schreib byte.

**Rückgabewert:**
byte

### setDoughnutHoleSize(byte value) {#setDoughnutHoleSize-byte-}
```
public abstract void setDoughnutHoleSize(byte value)
```

Gibt die Größe des Lochs in einem Donut-Diagramm an (kann zwischen 10 % und 90 % der Plot-Fläche liegen). Lese/Schreib byte.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public abstract int getBubbleSizeScale()
```

Gibt den Skalierungsfaktor für das Blasendiagramm an (kann zwischen 0 % und 300 % der Standardgröße liegen). Lese/Schreib int.

**Rückgabewert:**
int

### setBubbleSizeScale(int value) {#setBubbleSizeScale-int-}
```
public abstract void setBubbleSizeScale(int value)
```

Gibt den Skalierungsfaktor für das Blasendiagramm an (kann zwischen 0 % und 300 % der Standardgröße liegen). Lese/Schreib int.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getHiLowLinesFormat() {#getHiLowLinesFormat--}
```
public abstract IChartLinesFormat getHiLowLinesFormat()
```

Gibt das HiLowLines-Format an. HiLowLines werden bei den Diagrammtypen HiLowClose, OpenHiLowClose, VolumeHiLowClose und VolumeOpenHiLowClose verwendet.

**Rückgabewert:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public abstract int getBubbleSizeRepresentation()
```

Gibt an, wie die Werte der Blasengröße im Blasendiagramm dargestellt werden. Lese/Schreib [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Rückgabewert:**
int

### setBubbleSizeRepresentation(int value) {#setBubbleSizeRepresentation-int-}
```
public abstract void setBubbleSizeRepresentation(int value)
```

Gibt an, wie die Werte der Blasengröße im Blasendiagramm dargestellt werden. Lese/Schreib [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |