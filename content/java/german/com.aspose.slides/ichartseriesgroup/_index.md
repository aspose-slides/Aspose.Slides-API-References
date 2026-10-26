---
title: IChartSeriesGroup
second_title: Aspose.Slides für Java API-Referenz
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

1) Siehe Zusammenfassung und Anmerkungen für die Klasse ChartSeriesGroupCollection und das Enum CombinableSeriesTypesGroup. 2) Eine Gruppe von Serien enthält einige serienspezifische Eigenschaften, die für jede Serie in der Gruppe gemeinsam sind („Series group properties“). „Series group properties“ in der Klasse ChartSeriesGroup sind Lese/Schreib. Jede der „Series group properties“ kann in der Klasse ChartSeries als Nur-lesend projiziert werden.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getType()](#getType--) | Gibt den Typ dieser Seriengruppe zurück. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Gibt an, ob die Serien dieser Gruppe auf einer sekundären Achse dargestellt werden. |
| [getSeries()](#getSeries--) | Gibt eine schreibgeschützte Sammlung von Diagrammserien zurück. |
| [get_Item(int index)](#get-Item-int-) | Liefert das Element am angegebenen Index. |
| [getUpDownBars()](#getUpDownBars--) | Stellt Zugriff auf Auf-/Ab-Balken von Linien- oder Kurs-Diagrammen bereit. |
| [getGapWidth()](#getGapWidth--) | Gibt den Abstand zwischen Balken- oder Säulen-Clusters als Prozentsatz der Balken- oder Säulenbreite an. |
| [setGapWidth(int value)](#setGapWidth-int-) | Gibt den Abstand zwischen Balken- oder Säulen-Clusters als Prozentsatz der Balken- oder Säulenbreite an. |
| [getGapDepth()](#getGapDepth--) | Gibt den Abstand zwischen Datenserien in einem 3D-Diagramm als Prozentsatz der Markierungsbreite zurück. |
| [setGapDepth(int value)](#setGapDepth-int-) | Legt den Abstand zwischen Datenserien in einem 3D-Diagramm als Prozentsatz der Markierungsbreite fest. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | Gibt den Winkel des ersten Kuchen- oder Donut-Diagrammsegments in Grad zurück. |
| [setFirstSliceAngle(int value)](#setFirstSliceAngle-int-) | Legt den Winkel des ersten Kuchen- oder Donut-Diagrammsegments in Grad fest. |
| [isColorVaried()](#isColorVaried--) | Gibt an, ob jeder Datenmarker in der Serie eine andere Farbe hat. |
| [setColorVaried(boolean value)](#setColorVaried-boolean-) | Legt fest, ob jeder Datenmarker in der Serie eine andere Farbe hat. |
| [hasSeriesLines()](#hasSeriesLines--) | Gibt an, ob das Diagramm Seriensenlinien hat. |
| [setSeriesLines(boolean value)](#setSeriesLines-boolean-) | Gibt an, ob das Diagramm Seriensenlinien hat. |
| [getOverlap()](#getOverlap--) | Gibt an, um wie viel Prozent Balken und Säulen in 2-D-Diagrammen überlappen sollen. |
| [setOverlap(byte value)](#setOverlap-byte-) | Gibt an, um wie viel Prozent Balken und Säulen in 2-D-Diagrammen überlappen sollen. |
| [getSecondPieSize()](#getSecondPieSize--) | Gibt die Größe des zweiten Kuchens oder Balkens eines Kuchen-aus-Kuchen-Diagramms bzw. Balken-aus-Kuchen-Diagramms als Prozentsatz der Größe des ersten Kuchens an. |
| [setSecondPieSize(int value)](#setSecondPieSize-int-) | Gibt die Größe des zweiten Kuchens oder Balkens eines Kuchen-aus-Kuchen-Diagramms bzw. Balken-aus-Kuchen-Diagramms als Prozentsatz der Größe des ersten Kuchens an. |
| [getPieSplitPosition()](#getPieSplitPosition--) | Gibt einen Wert an, der zur Bestimmung verwendet wird, welche Datenpunkte im zweiten Kuchen oder Balken eines Kuchen-aus-Kuchen-Diagramms liegen. |
| [setPieSplitPosition(double value)](#setPieSplitPosition-double-) | Gibt einen Wert an, der zur Bestimmung verwendet wird, welche Datenpunkte im zweiten Kuchen oder Balken eines Kuchen-aus-Kuchen-Diagramms liegen. |
| [getPieSplitBy()](#getPieSplitBy--) | Gibt an, wie zu bestimmen ist, welche Datenpunkte im zweiten Kuchen oder Balken eines Kuchen-aus-Kuchen-Diagramms liegen. |
| [setPieSplitBy(int value)](#setPieSplitBy-int-) | Gibt an, wie zu bestimmen ist, welche Datenpunkte im zweiten Kuchen oder Balken eines Kuchen-aus-Kuchen-Diagramms liegen. |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | Die benutzerdefinierten Split-Informationen für ein Kuchen-aus-Kuchen- oder Balken-aus-Kuchen-Diagramm mit benutzerdefiniertem Split. |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Gibt die Größe des Lochs in einem Donut-Diagramm an (kann zwischen 10 % und 90 % der Plot-Fläche liegen). |
| [setDoughnutHoleSize(byte value)](#setDoughnutHoleSize-byte-) | Gibt die Größe des Lochs in einem Donut-Diagramm an (kann zwischen 10 % und 90 % der Plot-Fläche liegen). |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Gibt den Skalierungsfaktor für das Blasendiagramm an (kann zwischen 0 % und 300 % der Standardgröße liegen). |
| [setBubbleSizeScale(int value)](#setBubbleSizeScale-int-) | Gibt den Skalierungsfaktor für das Blasendiagramm an (kann zwischen 0 % und 300 % der Standardgröße liegen). |
| [getHiLowLinesFormat()](#getHiLowLinesFormat--) | Gibt HiLowLines-Format an. |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Gibt an, wie die Blasengrößenwerte im Blasendiagramm dargestellt werden. |
| [setBubbleSizeRepresentation(int value)](#setBubbleSizeRepresentation-int-) | Gibt an, wie die Blasengrößenwerte im Blasendiagramm dargestellt werden. |

### getType() {#getType--}
```
public abstract int getType()
```

Gibt den Typ dieser Seriengruppe zurück. Nur lesend [CombinableSeriesTypesGroup](../../com.aspose.slides/combinableseriestypesgroup).

**Rückgabewert:**
int

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public abstract boolean getPlotOnSecondAxis()
```

Gibt an, ob die Serien dieser Gruppe auf einer sekundären Achse dargestellt werden. Nur lesend boolean.

**Rückgabewert:**
boolean

### getSeries() {#getSeries--}
```
public abstract IChartSeriesReadonlyCollection getSeries()
```

Gibt eine schreibgeschützte Sammlung von Diagrammserien zurück. Nur lesend [IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection).

**Rückgabewert:**
[IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection)

### get_Item(int index) {#get-Item-int-}
```
public abstract IChartSeries get_Item(int index)
```

Liefert das Element am angegebenen Index.

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

Stellt Zugriff auf Auf-/Ab-Balken von Linien- oder Kurs-Diagrammen bereit. Nur lesend [IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager).

**Rückgabewert:**
[IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)

### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```

Gibt den Abstand zwischen Balken- oder Säulen-Clusters als Prozentsatz der Balken- oder Säulenbreite an. Lese/Schreib int.

**Rückgabewert:**
int

### setGapWidth(int value) {#setGapWidth-int-}
```
public abstract void setGapWidth(int value)
```

Gibt den Abstand zwischen Balken- oder Säulen-Clusters als Prozentsatz der Balken- oder Säulenbreite an. Lese/Schreib int.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getGapDepth() {#getGapDepth--}
```
public abstract int getGapDepth()
```

Gibt den Abstand zwischen Datenserien in einem 3D-Diagramm als Prozentsatz der Markierungsbreite zurück. Lese/Schreib int.

**Rückgabewert:**
int

### setGapDepth(int value) {#setGapDepth-int-}
```
public abstract void setGapDepth(int value)
```

Legt den Abstand zwischen Datenserien in einem 3D-Diagramm als Prozentsatz der Markierungsbreite fest. Lese/Schreib int.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public abstract int getFirstSliceAngle()
```

Gibt den Winkel des ersten Kuchen- oder Donut-Diagrammsegments in Grad zurück. Lese/Schreib int.

**Rückgabewert:**
int

### setFirstSliceAngle(int value) {#setFirstSliceAngle-int-}
```
public abstract void setFirstSliceAngle(int value)
```

Legt den Winkel des ersten Kuchen- oder Donut-Diagrammsegments in Grad fest. Lese/Schreib int.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### isColorVaried() {#isColorVaried--}
```
public abstract boolean isColorVaried()
```

Gibt an, ob jeder Datenmarker in der Serie eine andere Farbe hat. Lese/Schreib boolean.

**Rückgabewert:**
boolean

### setColorVaried(boolean value) {#setColorVaried-boolean-}
```
public abstract void setColorVaried(boolean value)
```

Legt fest, ob jeder Datenmarker in der Serie eine andere Farbe hat. Lese/Schreib boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### hasSeriesLines() {#hasSeriesLines--}
```
public abstract boolean hasSeriesLines()
```

Gibt an, ob das Diagramm Seriensenlinien hat. Auf gestapelten Balken- und OfPie-Diagrammen anwendbar. Lese/Schreib boolean.

**Rückgabewert:**
boolean

### setSeriesLines(boolean value) {#setSeriesLines-boolean-}
```
public abstract void setSeriesLines(boolean value)
```

Legt fest, ob das Diagramm Seriensenlinien hat. Auf gestapelten Balken- und OfPie-Diagrammen anwendbar. Lese/Schreib boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getOverlap() {#getOverlap--}
```
public abstract byte getOverlap()
```

Gibt an, um wie viel Prozent Balken und Säulen in 2-D-Diagrammen überlappen sollen. - -100 %: maximale Trennung (Balken sind vollständig getrennt). - 0 %: Balken liegen nebeneinander ohne Überlappung oder Abstand. - 100 %: maximale Überlappung (Balken überlappen vollständig). Diese Eigenschaft ist Lese/Schreib byte.

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

Legt fest, um wie viel Prozent Balken und Säulen in 2-D-Diagrammen überlappen sollen. - -100 %: maximale Trennung (Balken sind vollständig getrennt). - 0 %: Balken liegen nebeneinander ohne Überlappung oder Abstand. - 100 %: maximale Überlappung (Balken überlappen vollständig). Diese Eigenschaft ist Lese/Schreib byte.

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

Gibt die Größe des zweiten Kuchens oder Balkens eines Kuchen-aus-Kuchen-Diagramms bzw. Balken-aus-Kuchen-Diagramms als Prozentsatz der Größe des ersten Kuchens an. Lese/Schreib int.

**Rückgabewert:**
int

### setSecondPieSize(int value) {#setSecondPieSize-int-}
```
public abstract void setSecondPieSize(int value)
```

Legt die Größe des zweiten Kuchens oder Balkens eines Kuchen-aus-Kuchen-Diagramms bzw. Balken-aus-Kuchen-Diagramms als Prozentsatz der Größe des ersten Kuchens fest. Lese/Schreib int.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getPieSplitPosition() {#getPieSplitPosition--}
```
public abstract double getPieSplitPosition()
```

Gibt einen Wert an, der zur Bestimmung verwendet wird, welche Datenpunkte im zweiten Kuchen oder Balken eines Kuchen-aus-Kuchen-Diagramms liegen. Wird zusammen mit der Eigenschaft PieSplitBy verwendet. Lese/Schreib double.

**Rückgabewert:**
double

### setPieSplitPosition(double value) {#setPieSplitPosition-double-}
```
public abstract void setPieSplitPosition(double value)
```

Legt einen Wert fest, der zur Bestimmung verwendet wird, welche Datenpunkte im zweiten Kuchen oder Balken eines Kuchen-aus-Kuchen-Diagramms liegen. Wird zusammen mit der Eigenschaft PieSplitBy verwendet. Lese/Schreib double.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | double |  |

### getPieSplitBy() {#getPieSplitBy--}
```
public abstract int getPieSplitBy()
```

Gibt an, wie zu bestimmen ist, welche Datenpunkte im zweiten Kuchen oder Balken eines Kuchen-aus-Kuchen-Diagramms liegen. Lese/Schreib [PieSplitType](../../com.aspose.slides/piesplittype).

**Rückgabewert:**
int

### setPieSplitBy(int value) {#setPieSplitBy-int-}
```
public abstract void setPieSplitBy(int value)
```

Legt fest, wie zu bestimmen ist, welche Datenpunkte im zweiten Kuchen oder Balken eines Kuchen-aus-Kuchen-Diagramms liegen. Lese/Schreib [PieSplitType](../../com.aspose.slides/piesplittype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public abstract IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

Die benutzerdefinierten Split-Informationen für ein Kuchen-aus-Kuchen- oder Balken-aus-Kuchen-Diagramm mit benutzerdefiniertem Split. Enthält Datenpunkte, die im zweiten Kuchen oder Balken gezeichnet werden sollen. Nur lesend [IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection).

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

Legt die Größe des Lochs in einem Donut-Diagramm fest (kann zwischen 10 % und 90 % der Plot-Fläche liegen). Lese/Schreib byte.

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

Legt den Skalierungsfaktor für das Blasendiagramm fest (kann zwischen 0 % und 300 % der Standardgröße liegen). Lese/Schreib int.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getHiLowLinesFormat() {#getHiLowLinesFormat--}
```
public abstract IChartLinesFormat getHiLowLinesFormat()
```

Gibt das HiLowLines-Format an. HiLowLines wird bei den Diagrammtypen HiLowClose, OpenHiLowClose, VolumeHiLowClose und VolumeOpenHiLowClose angewendet.

**Rückgabewert:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public abstract int getBubbleSizeRepresentation()
```

Gibt an, wie die Blasengrößenwerte im Blasendiagramm dargestellt werden. Lese/Schreib [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Rückgabewert:**
int

### setBubbleSizeRepresentation(int value) {#setBubbleSizeRepresentation-int-}
```
public abstract void setBubbleSizeRepresentation(int value)
```

Legt fest, wie die Blasengrößenwerte im Blasendiagramm dargestellt werden. Lese/Schreib [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |