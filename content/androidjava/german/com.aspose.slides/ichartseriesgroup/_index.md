---
title: IChartSeriesGroup
second_title: Aspose.Slides für Android über Java API Referenz
description: Stellt eine Gruppe von Reihen dar.
type: docs
url: /de/com.aspose.slides/ichartseriesgroup/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IChartSeriesGroup extends IChartComponent
```

Stellt eine Gruppe von Reihen dar.

--------------------

1) Siehe Zusammenfassung und Anmerkungen für die Klasse ChartSeriesGroupCollection und das Enum CombinableSeriesTypesGroup. 2) Gruppe von Reihen enthält einige Reiheneigenschaften, die für jede Reihe in der Gruppe gemeinsam sind („Series group properties“). „Series group properties“ in der Klasse ChartSeriesGroup ist Lesen/Schreiben. Jede der „Series group properties“ kann eine Nur-lesbare Projektion in der Klasse ChartSeries haben.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getType()](#getType--) | Gibt einen Typ dieser Seriengruppe zurück. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Zeigt an, ob die Reihen dieser Gruppe auf einer sekundären Achse dargestellt werden. |
| [getSeries()](#getSeries--) | Gibt eine schreibgeschützte Sammlung von Diagrammreihen zurück. |
| [get_Item(int index)](#get-Item-int-) | Gibt das Element am angegebenen Index zurück. |
| [getUpDownBars()](#getUpDownBars--) | Stellt Zugriff auf Auf/Ab-Balken eines Linien- oder Aktien-Diagramms bereit. |
| [getGapWidth()](#getGapWidth--) | Gibt den Abstand zwischen Balken- oder Säulen-Clustern als Prozentsatz der Balken- oder Säulenbreite an. |
| [setGapWidth(int value)](#setGapWidth-int-) | Gibt den Abstand zwischen Balken- oder Säulen-Clustern als Prozentsatz der Balken- oder Säulenbreite an. |
| [getGapDepth()](#getGapDepth--) | Gibt die Distanz zwischen den Datenreihen in einem 3D-Diagramm als Prozentsatz der Markierungsbreite zurück oder legt sie fest. |
| [setGapDepth(int value)](#setGapDepth-int-) | Gibt die Distanz zwischen den Datenreihen in einem 3D-Diagramm als Prozentsatz der Markierungsbreite zurück oder legt sie fest. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | Gibt den Winkel des ersten Kuchen- oder Donut-Diagrammsegments in Grad zurück oder legt ihn fest (im Uhrzeigersinn von oben, von 0 bis 360 Grad). |
| [setFirstSliceAngle(int value)](#setFirstSliceAngle-int-) | Gibt den Winkel des ersten Kuchen- oder Donut-Diagrammsegments in Grad zurück oder legt ihn fest (im Uhrzeigersinn von oben, von 0 bis 360 Grad). |
| [isColorVaried()](#isColorVaried--) | Gibt an, dass jeder Datenmarker in der Reihe eine andere Farbe hat. |
| [setColorVaried(boolean value)](#setColorVaried-boolean-) | Gibt an, dass jeder Datenmarker in der Reihe eine andere Farbe hat. |
| [hasSeriesLines()](#hasSeriesLines--) | Wahr, wenn das Diagramm Reihenlinien hat. |
| [setSeriesLines(boolean value)](#setSeriesLines-boolean-) | Wahr, wenn das Diagramm Reihenlinien hat. |
| [getOverlap()](#getOverlap--) | Gibt an, wie stark Balken und Säulen in 2-D-Diagrammen überlappen sollen, als Prozentsatz (von -100 % bis 100 %). |
| [setOverlap(byte value)](#setOverlap-byte-) | Gibt an, wie stark Balken und Säulen in 2-D-Diagrammen überlappen sollen, als Prozentsatz (von -100 % bis 100 %). |
| [getSecondPieSize()](#getSecondPieSize--) | Gibt die Größe des zweiten Kuchens oder Balkens eines Kuchen-aus-Kuchen-Diagramms bzw. Balken-aus-Kuchen-Diagramms als Prozentsatz der Größe des ersten Kuchens an (zwischen 5 % und 200 %). |
| [setSecondPieSize(int value)](#setSecondPieSize-int-) | Gibt die Größe des zweiten Kuchens oder Balkens eines Kuchen-aus-Kuchen-Diagramms bzw. Balken-aus-Kuchen-Diagramms als Prozentsatz der Größe des ersten Kuchens an (zwischen 5 % und 200 %). |
| [getPieSplitPosition()](#getPieSplitPosition--) | Gibt einen Wert an, der verwendet wird, um zu bestimmen, welche Datenpunkte im zweiten Kuchen bzw. Balken eines Kuchen-aus-Kuchen-Diagramms oder Balken-aus-Kuchen-Diagramms liegen. |
| [setPieSplitPosition(double value)](#setPieSplitPosition-double-) | Gibt einen Wert an, der verwendet wird, um zu bestimmen, welche Datenpunkte im zweiten Kuchen bzw. Balken eines Kuchen-aus-Kuchen-Diagramms oder Balken-aus-Kuchen-Diagramms liegen. |
| [getPieSplitBy()](#getPieSplitBy--) | Gibt an, wie bestimmt wird, welche Datenpunkte im zweiten Kuchen bzw. Balken eines Kuchen-aus-Kuchen-Diagramms oder Balken-aus-Kuchen-Diagramms liegen. |
| [setPieSplitBy(int value)](#setPieSplitBy-int-) | Gibt an, wie bestimmt wird, welche Datenpunkte im zweiten Kuchen bzw. Balken eines Kuchen-aus-Kuchen-Diagramms oder Balken-aus-Kuchen-Diagramms liegen. |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | Die benutzerdefinierte Aufteilungsinformation für ein Kuchen-aus-Kuchen-Diagramm oder Balken-aus-Kuchen-Diagramm mit benutzerdefinierter Aufteilung. |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Gibt die Größe des Lochs in einem Donut-Diagramm an (zwischen 10 % und 90 % der Plot-Flächengröße). |
| [setDoughnutHoleSize(byte value)](#setDoughnutHoleSize-byte-) | Gibt die Größe des Lochs in einem Donut-Diagramm an (zwischen 10 % und 90 % der Plot-Flächengröße). |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Gibt den Skalierungsfaktor für das Blasendiagramm an (zwischen 0 % und 300 % der Standardgröße). |
| [setBubbleSizeScale(int value)](#setBubbleSizeScale-int-) | Gibt den Skalierungsfaktor für das Blasendiagramm an (zwischen 0 % und 300 % der Standardgröße). |
| [getHiLowLinesFormat()](#getHiLowLinesFormat--) | Gibt das HiLowLines-Format an. |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Gibt an, wie die Blasengrößenwerte im Blasendiagramm dargestellt werden. |
| [setBubbleSizeRepresentation(int value)](#setBubbleSizeRepresentation-int-) | Gibt an, wie die Blasengrößenwerte im Blasendiagramm dargestellt werden. |

### getType() {#getType--}
```
public abstract int getType()
```

Gibt einen Typ dieser Seriengruppe zurück. Nur lesbar [CombinableSeriesTypesGroup](../../com.aspose.slides/combinableseriestypesgroup).

**Rückgabe:**
int

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public abstract boolean getPlotOnSecondAxis()
```

Zeigt an, ob die Reihen dieser Gruppe auf einer sekundären Achse dargestellt werden. Nur lesbar boolean.

**Rückgabe:**
boolean

### getSeries() {#getSeries--}
```
public abstract IChartSeriesReadonlyCollection getSeries()
```

Gibt eine schreibgeschützte Sammlung von Diagrammreihen zurück. Nur lesbar [IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection).

**Rückgabe:**
[IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection)

### get_Item(int index) {#get-Item-int-}
```
public abstract IChartSeries get_Item(int index)
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
public abstract IUpDownBarsManager getUpDownBars()
```

Stellt Zugriff auf Auf/Ab-Balken eines Linien- oder Aktien-Diagramms bereit. Nur lesbar [IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager).

**Rückgabe:**
[IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)

### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```

Gibt den Abstand zwischen Balken- oder Säulen-Clustern als Prozentsatz der Balken- oder Säulenbreite an. Lesen/Schreiben int.

**Rückgabe:**
int

### setGapWidth(int value) {#setGapWidth-int-}
```
public abstract void setGapWidth(int value)
```

Gibt den Abstand zwischen Balken- oder Säulen-Clustern als Prozentsatz der Balken- oder Säulenbreite an. Lesen/Schreiben int.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getGapDepth() {#getGapDepth--}
```
public abstract int getGapDepth()
```

Gibt die Distanz zwischen den Datenreihen in einem 3D-Diagramm als Prozentsatz der Markierungsbreite zurück oder legt sie fest. Lesen/Schreiben int.

**Rückgabe:**
int

### setGapDepth(int value) {#setGapDepth-int-}
```
public abstract void setGapDepth(int value)
```

Gibt die Distanz zwischen den Datenreihen in einem 3D-Diagramm als Prozentsatz der Markierungsbreite zurück oder legt sie fest. Lesen/Schreiben int.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public abstract int getFirstSliceAngle()
```

Gibt den Winkel des ersten Kuchen- oder Donut-Diagrammsegments in Grad zurück oder legt ihn fest (im Uhrzeigersinn von oben, von 0 bis 360 Grad). Lesen/Schreiben int.

**Rückgabe:**
int

### setFirstSliceAngle(int value) {#setFirstSliceAngle-int-}
```
public abstract void setFirstSliceAngle(int value)
```

Gibt den Winkel des ersten Kuchen- oder Donut-Diagrammsegments in Grad zurück oder legt ihn fest (im Uhrzeigersinn von oben, von 0 bis 360 Grad). Lesen/Schreiben int.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### isColorVaried() {#isColorVaried--}
```
public abstract boolean isColorVaried()
```

Gibt an, dass jeder Datenmarker in der Reihe eine andere Farbe hat. Lesen/Schreiben boolean.

**Rückgabe:**
boolean

### setColorVaried(boolean value) {#setColorVaried-boolean-}
```
public abstract void setColorVaried(boolean value)
```

Gibt an, dass jeder Datenmarker in der Reihe eine andere Farbe hat. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### hasSeriesLines() {#hasSeriesLines--}
```
public abstract boolean hasSeriesLines()
```

Wahr, wenn das Diagramm Reihenlinien hat. Auf gestapelten Balken- und OfPie-Diagrammen anwendbar. Lesen/Schreiben boolean.

**Rückgabe:**
boolean

### setSeriesLines(boolean value) {#setSeriesLines-boolean-}
```
public abstract void setSeriesLines(boolean value)
```

Wahr, wenn das Diagramm Reihenlinien hat. Auf gestapelten Balken- und OfPie-Diagrammen anwendbar. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getOverlap() {#getOverlap--}
```
public abstract byte getOverlap()
```

Gibt an, wie stark Balken und Säulen in 2-D-Diagrammen überlappen sollen, als Prozentsatz (von -100 % bis 100 %). - -100 %: Maximale Abstände (Balken sind vollständig getrennt). - 0 %: Balken liegen nebeneinander ohne Überlappung oder Abstand. - 100 %: Maximale Überlappung (Balken überlappen sich vollständig). Diese Eigenschaft ist Lesen/Schreiben byte.

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


**Rückgabe:**
byte

### setOverlap(byte value) {#setOverlap-byte-}
```
public abstract void setOverlap(byte value)
```

Gibt an, wie stark Balken und Säulen in 2-D-Diagrammen überlappen sollen, als Prozentsatz (von -100 % bis 100 %). - -100 %: Maximale Abstände (Balken sind vollständig getrennt). - 0 %: Balken liegen nebeneinander ohne Überlappung oder Abstand. - 100 %: Maximale Überlappung (Balken überlappen sich vollständig). Diese Eigenschaft ist Lesen/Schreiben byte.

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

Gibt die Größe des zweiten Kuchens oder Balkens eines Kuchen-aus-Kuchen-Diagramms bzw. Balken-aus-Kuchen-Diagramms als Prozentsatz der Größe des ersten Kuchens an (zwischen 5 % und 200 %). Lesen/Schreiben int.

**Rückgabe:**
int

### setSecondPieSize(int value) {#setSecondPieSize-int-}
```
public abstract void setSecondPieSize(int value)
```

Gibt die Größe des zweiten Kuchens oder Balkens eines Kuchen-aus-Kuchen-Diagramms bzw. Balken-aus-Kuchen-Diagramms als Prozentsatz der Größe des ersten Kuchens an (zwischen 5 % und 200 %). Lesen/Schreiben int.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getPieSplitPosition() {#getPieSplitPosition--}
```
public abstract double getPieSplitPosition()
```

Gibt einen Wert an, der verwendet wird, um zu bestimmen, welche Datenpunkte im zweiten Kuchen bzw. Balken eines Kuchen-aus-Kuchen-Diagramms oder Balken-aus-Kuchen-Diagramms liegen. Wird zusammen mit der Eigenschaft PieSplitBy verwendet. Lesen/Schreiben double.

**Rückgabe:**
double

### setPieSplitPosition(double value) {#setPieSplitPosition-double-}
```
public abstract void setPieSplitPosition(double value)
```

Gibt einen Wert an, der verwendet wird, um zu bestimmen, welche Datenpunkte im zweiten Kuchen bzw. Balken eines Kuchen-aus-Kuchen-Diagramms oder Balken-aus-Kuchen-Diagramms liegen. Wird zusammen mit der Eigenschaft PieSplitBy verwendet. Lesen/Schreiben double.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |

### getPieSplitBy() {#getPieSplitBy--}
```
public abstract int getPieSplitBy()
```

Gibt an, wie bestimmt wird, welche Datenpunkte im zweiten Kuchen bzw. Balken eines Kuchen-aus-Kuchen-Diagramms oder Balken-aus-Kuchen-Diagramms liegen. Lesen/Schreiben [PieSplitType](../../com.aspose.slides/piesplittype).

**Rückgabe:**
int

### setPieSplitBy(int value) {#setPieSplitBy-int-}
```
public abstract void setPieSplitBy(int value)
```

Gibt an, wie bestimmt wird, welche Datenpunkte im zweiten Kuchen bzw. Balken eines Kuchen-aus-Kuchen-Diagramms oder Balken-aus-Kuchen-Diagramms liegen. Lesen/Schreiben [PieSplitType](../../com.aspose.slides/piesplittype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public abstract IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

Die benutzerdefinierte Aufteilungsinformation für ein Kuchen-aus-Kuchen-Diagramm oder Balken-aus-Kuchen-Diagramm mit benutzerdefinierter Aufteilung. Enthält Datenpunkte, die im zweiten Kuchen bzw. Balken gezeichnet werden sollen. Nur lesbar [IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection).

**Rückgabe:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public abstract byte getDoughnutHoleSize()
```

Gibt die Größe des Lochs in einem Donut-Diagramm an (zwischen 10 % und 90 % der Plot-Flächengröße). Lesen/Schreiben byte.

**Rückgabe:**
byte

### setDoughnutHoleSize(byte value) {#setDoughnutHoleSize-byte-}
```
public abstract void setDoughnutHoleSize(byte value)
```

Gibt die Größe des Lochs in einem Donut-Diagramm an (zwischen 10 % und 90 % der Plot-Flächengröße). Lesen/Schreiben byte.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public abstract int getBubbleSizeScale()
```

Gibt den Skalierungsfaktor für das Blasendiagramm an (zwischen 0 % und 300 % der Standardgröße). Lesen/Schreiben int.

**Rückgabe:**
int

### setBubbleSizeScale(int value) {#setBubbleSizeScale-int-}
```
public abstract void setBubbleSizeScale(int value)
```

Gibt den Skalierungsfaktor für das Blasendiagramm an (zwischen 0 % und 300 % der Standardgröße). Lesen/Schreiben int.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getHiLowLinesFormat() {#getHiLowLinesFormat--}
```
public abstract IChartLinesFormat getHiLowLinesFormat()
```

Gibt das HiLowLines-Format an. HiLowLines wird bei den Diagrammtypen HiLowClose, OpenHiLowClose, VolumeHiLowClose und VolumeOpenHiLowClose verwendet.

**Rückgabe:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public abstract int getBubbleSizeRepresentation()
```

Gibt an, wie die Blasengrößenwerte im Blasendiagramm dargestellt werden. Lesen/Schreiben [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Rückgabe:**
int

### setBubbleSizeRepresentation(int value) {#setBubbleSizeRepresentation-int-}
```
public abstract void setBubbleSizeRepresentation(int value)
```

Gibt an, wie die Blasengrößenwerte im Blasendiagramm dargestellt werden. Lesen/Schreiben [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |