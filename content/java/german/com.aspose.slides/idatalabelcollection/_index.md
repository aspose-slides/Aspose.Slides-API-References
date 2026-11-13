---
title: IDataLabelCollection
second_title: Aspose.Slides für Java API Referenz
description: Stellt Serienbeschriftungen dar.
type: docs
url: /de/com.aspose.slides/idatalabelcollection/
---
**Alle implementierten Schnittstellen:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable, [com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IDataLabelCollection extends System.Collections.Generic.IGenericEnumerable<IDataLabel>, IChartComponent
```

Stellt Serienbeschriftungen dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Ermittelt die Datenbeschriftung für den Datenpunkt mit dem angegebenen Index. |
| [getDefaultDataLabelFormat()](#getDefaultDataLabelFormat--) | Gibt das Standardformat aller Datenbeschriftungen in der Sammlung zurück. |
| [getLeaderLinesFormat()](#getLeaderLinesFormat--) | Stellt das Format der Führungs-Linien von Datenbeschriftungen dar. |
| [isVisible()](#isVisible--) | False bedeutet, dass die Datenbeschriftung standardmäßig nicht sichtbar ist (und somit alle Show\*-Flags (ShowValue, ...) der Eigenschaft DefaultDataLabelFormat false sind). |
| [hide()](#hide--) | Macht die Datenbeschriftung standardmäßig ausgeblendet, indem alle Show\*-Flags (ShowValue, ...) der Eigenschaft DefaultDataLabelFormat auf den falschen Zustand gesetzt werden. |
| [getCountOfVisibleDataLabels()](#getCountOfVisibleDataLabels--) | Ermittelt die Anzahl sichtbarer Datenbeschriftungen in der Sammlung. |
| [getCount()](#getCount--) | Ermittelt die Gesamtzahl aller Datenbeschriftungen in der Sammlung. |
| [getParentSeries()](#getParentSeries--) | Gibt die übergeordnete Diagrammserie zurück. |
| [indexOf(IDataLabel value)](#indexOf-com.aspose.slides.IDataLabel-) | Gibt den Index der angegebenen DataLabel in der Sammlung zurück. |
| [getDefaultLabelShapeType()](#getDefaultLabelShapeType--) | Liest oder schreibt den Standard-Formtyp für Datenbeschriftungen. |
| [setDefaultLabelShapeType(int value)](#setDefaultLabelShapeType-int-) | Liest oder schreibt den Standard-Formtyp für Datenbeschriftungen. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IDataLabel get_Item(int index)
```


Ermittelt die Datenbeschriftung für den Datenpunkt mit dem angegebenen Index.

--------------------

Alternative Möglichkeit, auf die Datenbeschriftung zuzugreifen, ist: - getSeries().getDataPoints().get_Item(i).getLabel() - Beschriftungseigenschaften verwalten.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int |  |

**Rückgabewert:**
[IDataLabel](../../com.aspose.slides/idatalabel)
### getDefaultDataLabelFormat() {#getDefaultDataLabelFormat--}
```
public abstract IDataLabelFormat getDefaultDataLabelFormat()
```


Gibt das Standardformat aller Datenbeschriftungen in der Sammlung zurück. Nur lesbar [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Rückgabewert:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getLeaderLinesFormat() {#getLeaderLinesFormat--}
```
public abstract IChartLinesFormat getLeaderLinesFormat()
```


Stellt das Format der Führungs-Linien von Datenbeschriftungen dar. Nur lesbar [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

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


**Rückgabewert:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```


False bedeutet, dass die Datenbeschriftung standardmäßig nicht sichtbar ist (und somit alle Show\*-Flags (ShowValue, ...) der Eigenschaft DefaultDataLabelFormat false sind). Nur lesbar  boolean .

--------------------

Wenn die Datenbeschriftung standardmäßig sichtbar ist, können Sie sie mit der Methode Hide() standardmäßig ausblenden. Ist die Datenbeschriftung jedoch standardmäßig nicht sichtbar (IsVisible ist false), können Sie sie "standardmäßig sichtbar" machen, indem Sie die Show\*-Flags (ShowValue, ...) der Eigenschaft DefaultDataLabelFormat auf den wahren Zustand setzen.

**Rückgabewert:**
boolean
### hide() {#hide--}
```
public abstract void hide()
```


Macht die Datenbeschriftung standardmäßig ausgeblendet, indem alle Show\*-Flags (ShowValue, ...) der Eigenschaft DefaultDataLabelFormat auf den falschen Zustand gesetzt werden. IsVisible wird danach false sein.

--------------------

Wenn die Datenbeschriftung nicht standardmäßig sichtbar ist (IsVisible ist false), können Sie sie "standardmäßig sichtbar" machen, indem Sie die Show\*-Flags (ShowValue, ...) der Eigenschaft DefaultDataLabelFormat auf den wahren Zustand setzen.

### getCountOfVisibleDataLabels() {#getCountOfVisibleDataLabels--}
```
public abstract int getCountOfVisibleDataLabels()
```


Ermittelt die Anzahl sichtbarer Datenbeschriftungen in der Sammlung. Nur lesbar  int .

**Rückgabewert:**
int
### getCount() {#getCount--}
```
public abstract int getCount()
```


Ermittelt die Gesamtzahl aller Datenbeschriftungen in der Sammlung. Nur lesbar  int .

**Rückgabewert:**
int
### getParentSeries() {#getParentSeries--}
```
public abstract IChartSeries getParentSeries()
```


Gibt die übergeordnete Diagrammserie zurück. Nur lesbar [IChartSeries](../../com.aspose.slides/ichartseries).

**Rückgabewert:**
[IChartSeries](../../com.aspose.slides/ichartseries)
### indexOf(IDataLabel value) {#indexOf-com.aspose.slides.IDataLabel-}
```
public abstract int indexOf(IDataLabel value)
```


Gibt den Index der angegebenen DataLabel in der Sammlung zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IDataLabel](../../com.aspose.slides/idatalabel) | DataLabel zum Suchen. |

**Rückgabewert:**
int - Index einer DataLabel oder -1, falls die DataLabel nicht aus dieser Sammlung stammt.
### getDefaultLabelShapeType() {#getDefaultLabelShapeType--}
```
public abstract int getDefaultLabelShapeType()
```


Liest oder schreibt den Standard-Formtyp für Datenbeschriftungen. Gibt [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) zurück, falls keine Form definiert ist.

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // Setze den Formtyp aller Datenbeschriftungen in der ersten Serie auf Ellipse.
>      firstSeries.getLabels().setDefaultLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabels.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

Das Setzen dieser Eigenschaft setzt ebenfalls die Eigenschaft IDataLabel.LabelShapeType ([IDataLabel.getLabelShapeType](../../com.aspose.slides/idatalabel\#getLabelShapeType)/[IDataLabel.setLabelShapeType(int)](../../com.aspose.slides/idatalabel\#setLabelShapeType-int-)) für alle Datenbeschriftungen in der Sammlung auf denselben Wert.

**Rückgabewert:**
int
### setDefaultLabelShapeType(int value) {#setDefaultLabelShapeType-int-}
```
public abstract void setDefaultLabelShapeType(int value)
```


Liest oder schreibt den Standard-Formtyp für Datenbeschriftungen. Gibt [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) zurück, falls keine Form definiert ist.

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // Setze den Formtyp aller Datenbeschriftungen in der ersten Serie auf Ellipse.
>      firstSeries.getLabels().setDefaultLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabels.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

Das Setzen dieser Eigenschaft setzt ebenfalls die Eigenschaft IDataLabel.LabelShapeType ([IDataLabel.getLabelShapeType](../../com.aspose.slides/idatalabel\#getLabelShapeType)/[IDataLabel.setLabelShapeType(int)](../../com.aspose.slides/idatalabel\#setLabelShapeType-int-)) für alle Datenbeschriftungen in der Sammlung auf denselben Wert.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |