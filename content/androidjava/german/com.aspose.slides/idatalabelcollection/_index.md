---
title: IDataLabelCollection
second_title: Aspose.Slides für Android über die Java-API-Referenz
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
| [get_Item(int index)](#get-Item-int-) | Ruft das Datenetikett für den Datenpunkt mit dem angegebenen Index ab. |
| [getDefaultDataLabelFormat()](#getDefaultDataLabelFormat--) | Gibt das Standardformat aller Datenetiketten in der Sammlung zurück. |
| [getLeaderLinesFormat()](#getLeaderLinesFormat--) | Stellt das Format der Führungslinien von Datenetiketten dar. |
| [isVisible()](#isVisible--) | False bedeutet, dass das Datenetikett standardmäßig nicht sichtbar ist (und daher alle Show*-Flags (ShowValue, ...) der Eigenschaft DefaultDataLabelFormat false sind). |
| [hide()](#hide--) | Macht das Datenetikett standardmäßig verborgen, indem alle Show*-Flags (ShowValue, ...) der Eigenschaft DefaultDataLabelFormat auf den falschen Zustand gesetzt werden. |
| [getCountOfVisibleDataLabels()](#getCountOfVisibleDataLabels--) | Ruft die Anzahl der sichtbaren Datenetiketten in der Sammlung ab. |
| [getCount()](#getCount--) | Ruft die Anzahl aller Datenetiketten in der Sammlung ab. |
| [getParentSeries()](#getParentSeries--) | Gibt die übergeordnete Diagrammserie zurück. |
| [indexOf(IDataLabel value)](#indexOf-com.aspose.slides.IDataLabel-) | Gibt den Index des angegebenen DataLabel in der Sammlung zurück. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IDataLabel get_Item(int index)
```


Ruft das Datenetikett für den Datenpunkt mit dem angegebenen Index ab.

--------------------

Alternative Möglichkeit, auf das Datenetikett zuzugreifen, ist: - getSeries().getDataPoints().get_Item(i).getLabel() - Beschriftungseigenschaften verwalten.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int |  |

**Rückgabe:**
[IDataLabel](../../com.aspose.slides/idatalabel)
### getDefaultDataLabelFormat() {#getDefaultDataLabelFormat--}
```
public abstract IDataLabelFormat getDefaultDataLabelFormat()
```


Gibt das Standardformat aller Datenetiketten in der Sammlung zurück. Nur lesbar [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Rückgabe:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getLeaderLinesFormat() {#getLeaderLinesFormat--}
```
public abstract IChartLinesFormat getLeaderLinesFormat()
```


Stellt das Format der Führungslinien von Datenetiketten dar. Nur lesbar [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

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
>      labels.getLeaderLinesFormat().getLine().getFillFormat().getSolidFillColor().setColor(Color.RED);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Rückgabe:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```


False bedeutet, dass das Datenetikett standardmäßig nicht sichtbar ist (und daher alle Show*-Flags (ShowValue, ...) der Eigenschaft DefaultDataLabelFormat false sind). Nur lesbar  boolean .

--------------------

Wenn das Datenetikett standardmäßig sichtbar ist, können Sie es mit der Hide()-Methode standardmäßig verbergen. Wenn das Datenetikett jedoch standardmäßig nicht sichtbar ist (IsVisible ist false), können Sie das Datenetikett „standardmäßig sichtbar“ machen, indem Sie die Show*-Flags (ShowValue, ...) der Eigenschaft DefaultDataLabelFormat auf den wahren Zustand setzen.

**Rückgabe:**
boolean
### hide() {#hide--}
```
public abstract void hide()
```


Macht das Datenetikett standardmäßig verborgen, indem alle Show*-Flags (ShowValue, ...) der Eigenschaft DefaultDataLabelFormat auf den falschen Zustand gesetzt werden. IsVisible wird danach false sein.

--------------------

Wenn das Datenetikett nicht standardmäßig sichtbar ist (IsVisible ist false), können Sie das Datenetikett „standardmäßig sichtbar“ machen, indem Sie die Show*-Flags (ShowValue, ...) der Eigenschaft DefaultDataLabelFormat auf den wahren Zustand setzen.

### getCountOfVisibleDataLabels() {#getCountOfVisibleDataLabels--}
```
public abstract int getCountOfVisibleDataLabels()
```


Ruft die Anzahl der sichtbaren Datenetiketten in der Sammlung ab. Nur lesbar  int .

**Rückgabe:**
int
### getCount() {#getCount--}
```
public abstract int getCount()
```


Ruft die Anzahl aller Datenetiketten in der Sammlung ab. Nur lesbar  int .

**Rückgabe:**
int
### getParentSeries() {#getParentSeries--}
```
public abstract IChartSeries getParentSeries()
```


Gibt die übergeordnete Diagrammserie zurück. Nur lesbar [IChartSeries](../../com.aspose.slides/ichartseries).

**Rückgabe:**
[IChartSeries](../../com.aspose.slides/ichartseries)
### indexOf(IDataLabel value) {#indexOf-com.aspose.slides.IDataLabel-}
```
public abstract int indexOf(IDataLabel value)
```


Gibt den Index des angegebenen DataLabel in der Sammlung zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IDataLabel](../../com.aspose.slides/idatalabel) | DataLabel zum Suchen. |

**Rückgabe:**
int - Index eines DataLabel oder -1, falls DataLabel nicht aus dieser Sammlung stammt.