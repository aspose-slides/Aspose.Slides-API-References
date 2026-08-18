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
| [get_Item(int index)](#get-Item-int-) | Ruft die Datenbeschriftung für den Datenpunkt mit dem angegebenen Index ab. |
| [getDefaultDataLabelFormat()](#getDefaultDataLabelFormat--) | Gibt das Standardformat aller Datenbeschriftungen in der Sammlung zurück. |
| [getLeaderLinesFormat()](#getLeaderLinesFormat--) | Stellt das Format der Führungslinien von Datenbeschriftungen dar. |
| [isVisible()](#isVisible--) | False bedeutet, dass die Datenbeschriftung standardmäßig nicht sichtbar ist (und daher alle Show\*-Flags (ShowValue, ...) der Eigenschaft DefaultDataLabelFormat false sind). |
| [hide()](#hide--) | Macht die Datenbeschriftung standardmäßig verborgen, indem alle Show\*-Flags (ShowValue, ...) der Eigenschaft DefaultDataLabelFormat auf den falschen Zustand gesetzt werden. |
| [getCountOfVisibleDataLabels()](#getCountOfVisibleDataLabels--) | Ruft die Anzahl der sichtbaren Datenbeschriftungen in der Sammlung ab. |
| [getCount()](#getCount--) | Ruft die Gesamtzahl aller Datenbeschriftungen in der Sammlung ab. |
| [getParentSeries()](#getParentSeries--) | Gibt die übergeordnete Diagrammserie zurück. |
| [indexOf(IDataLabel value)](#indexOf-com.aspose.slides.IDataLabel-) | Gibt den Index der angegebenen DataLabel in der Sammlung zurück. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IDataLabel get_Item(int index)
```

Ruft die Datenbeschriftung für den Datenpunkt mit dem angegebenen Index ab.

--------------------

Alternative Möglichkeit, auf die Datenbeschriftung zuzugreifen, ist: - getSeries().getDataPoints().get\_Item(i).getLabel() - Beschriftungseigenschaften verwalten.

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

Gibt das Standardformat aller Datenbeschriftungen in der Sammlung zurück. Nur-Lesen [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Rückgabewert:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getLeaderLinesFormat() {#getLeaderLinesFormat--}
```
public abstract IChartLinesFormat getLeaderLinesFormat()
```

Stellt das Format der Führungslinien von Datenbeschriftungen dar. Nur-Lesen [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

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

False bedeutet, dass die Datenbeschriftung standardmäßig nicht sichtbar ist (und daher alle Show\*-Flags (ShowValue, ...) der Eigenschaft DefaultDataLabelFormat false sind). Nur-Lesen  boolean .

--------------------

Wenn die Datenbeschriftung standardmäßig sichtbar ist, können Sie sie mit der Hide()-Methode standardmäßig verbergen. Wenn die Datenbeschriftung jedoch standardmäßig nicht sichtbar ist (IsVisible ist false), können Sie die Datenbeschriftung "standardmäßig sichtbar" machen, indem Sie die Show\*-Flags (ShowValue, ...) der Eigenschaft DefaultDataLabelFormat auf den wahren Zustand setzen.

**Rückgabewert:**
boolean
### hide() {#hide--}
```
public abstract void hide()
```

Macht die Datenbeschriftung standardmäßig verborgen, indem alle Show\*-Flags (ShowValue, ...) der Eigenschaft DefaultDataLabelFormat auf den falschen Zustand gesetzt werden. IsVisible wird danach false sein.

--------------------

Wenn die Datenbeschriftung standardmäßig nicht sichtbar ist (IsVisible ist false), können Sie die Datenbeschriftung "standardmäßig sichtbar" machen, indem Sie die Show\*-Flags (ShowValue, ...) der Eigenschaft DefaultDataLabelFormat auf den wahren Zustand setzen.

### getCountOfVisibleDataLabels() {#getCountOfVisibleDataLabels--}
```
public abstract int getCountOfVisibleDataLabels()
```

Ruft die Anzahl der sichtbaren Datenbeschriftungen in der Sammlung ab. Nur-Lesen  int .

**Rückgabewert:**
int
### getCount() {#getCount--}
```
public abstract int getCount()
```

Ruft die Gesamtzahl aller Datenbeschriftungen in der Sammlung ab. Nur-Lesen  int .

**Rückgabewert:**
int
### getParentSeries() {#getParentSeries--}
```
public abstract IChartSeries getParentSeries()
```

Gibt die übergeordnete Diagrammserie zurück. Nur-Lesen [IChartSeries](../../com.aspose.slides/ichartseries).

**Rückgabewert:**
[IChartSeries](../../com.aspose.slides/ichartseries)
### indexOf(IDataLabel value) {#indexOf-com.aspose.slides.IDataLabel-}
```
public abstract int indexOf(IDataLabel value)
```

Gibt den Index des angegebenen DataLabel in der Sammlung zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IDataLabel](../../com.aspose.slides/idatalabel) | DataLabel, das gefunden werden soll. |

**Rückgabewert:**
int – Index eines DataLabel oder -1, falls das DataLabel nicht aus dieser Sammlung stammt.