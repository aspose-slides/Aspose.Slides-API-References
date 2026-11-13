---
title: DataLabelCollection
second_title: Aspose.Slides für Java API-Referenz
description: Stellt Serienbeschriftungen dar.
type: docs
url: /de/com.aspose.slides/datalabelcollection/
---
**Vererbung:**
java.lang.Object, com.aspose.slides.DomObject

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)
```
public class DataLabelCollection extends DomObject<ChartSeries> implements IDataLabelCollection
```

Stellt Serienbeschriftungen dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getChart()](#getChart--) | Gibt das übergeordnete Diagramm zurück. |
| [iterator()](#iterator--) | Gibt einen Enumerator zurück, der die Sammlung durchläuft. |
| [iteratorJava()](#iteratorJava--) | Gibt einen java-Iterator für die gesamte Sammlung zurück. |
| [isVisible()](#isVisible--) | False bedeutet, dass die Datenbeschriftung standardmäßig nicht sichtbar ist (und daher alle Show*-Flags (ShowValue, ...) der Eigenschaft DefaultDataLabelFormat false sind). |
| [hide()](#hide--) | Macht die Datenbeschriftung standardmäßig versteckt, indem alle Show*-Flags (ShowValue, ...) der Eigenschaft DefaultDataLabelFormat auf den falschen Zustand gesetzt werden. |
| [getCountOfVisibleDataLabels()](#getCountOfVisibleDataLabels--) | Ermittelt die Anzahl der sichtbaren Datenbeschriftungen in der Sammlung. |
| [getCount()](#getCount--) | Ermittelt die Anzahl aller Datenbeschriftungen in der Sammlung. |
| [getDefaultDataLabelFormat()](#getDefaultDataLabelFormat--) | Ermittelt das Standardformat der Datenbeschriftung. |
| [getLeaderLinesFormat()](#getLeaderLinesFormat--) | Stellt das Format der Führungslinien von Datenbeschriftungen dar. |
| [getParentSeries()](#getParentSeries--) | Ermittelt die übergeordnete Serie. |
| [indexOf(IDataLabel value)](#indexOf-com.aspose.slides.IDataLabel-) | Gibt den Index des angegebenen DataLabel in der Sammlung zurück. |
| [get_Item(int index)](#get-Item-int-) | Ermittelt die Datenbeschriftung für den Datenpunkt mit dem angegebenen Index. |
| [getDefaultLabelShapeType()](#getDefaultLabelShapeType--) | Ermittelt oder legt den Standard-Shape-Typ für Datenbeschriftungen fest. |
| [setDefaultLabelShapeType(int value)](#setDefaultLabelShapeType-int-) | Ermittelt oder legt den Standard-Shape-Typ für Datenbeschriftungen fest. |
| [getSlide()](#getSlide--) | Gibt die übergeordnete Folie eines FillFormat zurück. |
| [getPresentation()](#getPresentation--) | Gibt die übergeordnete Präsentation eines FillFormat zurück. |

### getChart() {#getChart--}
```
public final IChart getChart()
```

Gibt das übergeordnete Diagramm zurück. Nur lesbar [IChart](../../com.aspose.slides/ichart).

**Rückgabe:**
[IChart](../../com.aspose.slides/ichart)

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IDataLabel> iterator()
```

Gibt einen Enumerator zurück, der die Sammlung durchläuft.

**Rückgabe:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDataLabel> - A IGenericEnumerator that can be used to iterate through the collection.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IDataLabel> iteratorJava()
```

Gibt einen java-Iterator für die gesamte Sammlung zurück.

**Rückgabe:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDataLabel> - An java.util.Iterator for the entire collection.

### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

False bedeutet, dass die Datenbeschriftung standardmäßig nicht sichtbar ist (und daher alle Show*-Flags (ShowValue, ...) der Eigenschaft DefaultDataLabelFormat false sind). Nur lesbar boolean.

--------------------

Wenn das Datenbeschriftung standardmäßig sichtbar ist, können Sie es mit der Hide()-Methode standardmäßig ausblenden. Wenn das Datenbeschriftung standardmäßig nicht sichtbar ist (IsVisible ist false), können Sie die Datenbeschriftung „standardmäßig sichtbar“ machen, indem Sie die Show*-Flags (ShowValue, ...) der Eigenschaft DefaultDataLabelFormat auf den wahren Zustand setzen.

**Rückgabe:**
boolean

### hide() {#hide--}
```
public final void hide()
```

Macht die Datenbeschriftung standardmäßig versteckt, indem alle Show*-Flags (ShowValue, ...) der Eigenschaft DefaultDataLabelFormat auf den falschen Zustand gesetzt werden. IsVisible wird danach false sein.

--------------------

Wenn das Datenbeschriftung standardmäßig nicht sichtbar ist (IsVisible ist false), können Sie die Datenbeschriftung „standardmäßig sichtbar“ machen, indem Sie die Show*-Flags (ShowValue, ...) der Eigenschaft DefaultDataLabelFormat auf den wahren Zustand setzen.

### getCountOfVisibleDataLabels() {#getCountOfVisibleDataLabels--}
```
public final int getCountOfVisibleDataLabels()
```

Ermittelt die Anzahl der sichtbaren Datenbeschriftungen in der Sammlung. Nur lesbar int.

**Rückgabe:**
int

### getCount() {#getCount--}
```
public final int getCount()
```

Ermittelt die Anzahl aller Datenbeschriftungen in der Sammlung. Nur lesbar int.

**Rückgabe:**
int

### getDefaultDataLabelFormat() {#getDefaultDataLabelFormat--}
```
public final IDataLabelFormat getDefaultDataLabelFormat()
```

Ermittelt das Standardformat der Datenbeschriftung. Nur lesbar [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Rückgabe:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)

### getLeaderLinesFormat() {#getLeaderLinesFormat--}
```
public final IChartLinesFormat getLeaderLinesFormat()
```

Stellt das Format der Führungslinien von Datenbeschriftungen dar. Nur lesbar [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IChart chart = (IChart) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      IDataLabelCollection labels = series.get_Item(0).getLabels();
>      labels.getLeaderLinesFormat().getLine().getFillFormat().setFillType(FillType.Solid);
>      labels.getLeaderLinesFormat().getLine().getFillFormat().getSolidFillColor().setColor(new java.awt.Color(255, 0, 0, 255));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Rückgabe:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getParentSeries() {#getParentSeries--}
```
public final IChartSeries getParentSeries()
```

Ermittelt die übergeordnete Serie. Nur lesbar [IChartSeries](../../com.aspose.slides/ichartseries).

**Rückgabe:**
[IChartSeries](../../com.aspose.slides/ichartseries)

### indexOf(IDataLabel value) {#indexOf-com.aspose.slides.IDataLabel-}
```
public final int indexOf(IDataLabel value)
```

Gibt den Index des angegebenen DataLabel in der Sammlung zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IDataLabel](../../com.aspose.slides/idatalabel) | DataLabel zum Finden. |

**Rückgabe:**
int - Index eines DataLabel oder -1, wenn das DataLabel nicht aus dieser Sammlung stammt.

### get_Item(int index) {#get-Item-int-}
```
public final IDataLabel get_Item(int index)
```

Ermittelt die Datenbeschriftung für den Datenpunkt mit dem angegebenen Index.

--------------------

Alternativer Weg, auf die Datenbeschriftung zuzugreifen, ist: - series.getDataPoints().get_Item(i).getLabel() - Beschriftungseigenschaften verwalten.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int |  |

**Rückgabe:**
[IDataLabel](../../com.aspose.slides/idatalabel)

### getDefaultLabelShapeType() {#getDefaultLabelShapeType--}
```
public final int getDefaultLabelShapeType()
```

Ermittelt oder legt den Standard-Shape-Typ für Datenbeschriftungen fest. Gibt [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) zurück, wenn kein Shape definiert ist.

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // Setze den Shape-Typ aller Datenbeschriftungen in der ersten Serie auf Ellipse.
>      firstSeries.getLabels().setDefaultLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabels.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Das Setzen dieser Eigenschaft setzt außerdem die  IDataLabel.LabelShapeType ([IDataLabel.getLabelShapeType](../../com.aspose.slides/idatalabel\#getLabelShapeType)/[IDataLabel.setLabelShapeType(int)](../../com.aspose.slides/idatalabel\#setLabelShapeType-int-)) Eigenschaft für alle Datenbeschriftungen in der Sammlung auf denselben Wert.

**Rückgabe:**
int

### setDefaultLabelShapeType(int value) {#setDefaultLabelShapeType-int-}
```
public final void setDefaultLabelShapeType(int value)
```

Ermittelt oder legt den Standard-Shape-Typ für Datenbeschriftungen fest. Gibt [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) zurück, wenn kein Shape definiert ist.

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // Setze den Shape-Typ aller Datenbeschriftungen in der ersten Serie auf Ellipse.
>      firstSeries.getLabels().setDefaultLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabels.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Das Setzen dieser Eigenschaft setzt außerdem die  IDataLabel.LabelShapeType ([IDataLabel.getLabelShapeType](../../com.aspose.slides/idatalabel\#getLabelShapeType)/[IDataLabel.setLabelShapeType(int)](../../com.aspose.slides/idatalabel\#setLabelShapeType-int-)) Eigenschaft für alle Datenbeschriftungen in der Sammlung auf denselben Wert.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

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