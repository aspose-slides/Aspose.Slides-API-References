---
title: IDataLabelCollection
second_title: Aspose.Slides pro Java API Reference
description: Reprezentuje štítky řady.
type: docs
url: /cs/com.aspose.slides/idatalabelcollection/
---
**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable, [com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IDataLabelCollection extends System.Collections.Generic.IGenericEnumerable<IDataLabel>, IChartComponent
```

Represents a series labels.
## Metody

| Metoda | Popis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Získá datový štítek pro datový bod s určeným indexem. |
| [getDefaultDataLabelFormat()](#getDefaultDataLabelFormat--) | Vrací výchozí formát všech datových štítků ve sbírce. |
| [getLeaderLinesFormat()](#getLeaderLinesFormat--) | Představuje formát vodicích čar datových štítků. |
| [isVisible()](#isVisible--) | False znamená, že datový štítek není ve výchozím nastavení viditelný (a tak jsou všechny Show*-flags (ShowValue, ...) vlastnosti DefaultDataLabelFormat nastaveny na false). |
| [hide()](#hide--) | Skryje datový štítek ve výchozím nastavení nastavením všech Show*-flags (ShowValue, ...) vlastnosti DefaultDataLabelFormat na false. |
| [getCountOfVisibleDataLabels()](#getCountOfVisibleDataLabels--) | Získá počet viditelných datových štítků ve sbírce. |
| [getCount()](#getCount--) | Získá počet všech datových štítků ve sbírce. |
| [getParentSeries()](#getParentSeries--) | Vrací nadřazenou sérii grafu. |
| [indexOf(IDataLabel value)](#indexOf-com.aspose.slides.IDataLabel-) | Vrací index zadaného DataLabel ve sbírce. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IDataLabel get_Item(int index)
```


Získá datový štítek pro datový bod s určeným indexem.

--------------------

Alternativní způsob přístupu k datovému štítku je: - getSeries().getDataPoints().get_Item(i).getLabel() - spravovat vlastnosti štítku.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int |  |

**Vrací:**
[IDataLabel](../../com.aspose.slides/idatalabel)
### getDefaultDataLabelFormat() {#getDefaultDataLabelFormat--}
```
public abstract IDataLabelFormat getDefaultDataLabelFormat()
```


Vrací výchozí formát všech datových štítků ve sbírce. Pouze pro čtení [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Vrací:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getLeaderLinesFormat() {#getLeaderLinesFormat--}
```
public abstract IChartLinesFormat getLeaderLinesFormat()
```


Představuje formát vodicích čar datových štítků. Pouze pro čtení [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

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

**Vrací:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```


False znamená, že datový štítek není ve výchozím nastavení viditelný (a tak jsou všechny Show*-flags (ShowValue, ...) vlastnosti DefaultDataLabelFormat nastaveny na false). Pouze pro čtení  boolean .

--------------------

Pokud je datový štítek ve výchozím nastavení viditelný, můžete jej skrýt ve výchozím nastavení metodou Hide(). Pokud však datový štítek není ve výchozím nastavení viditelný (IsVisible je false), můžete jej nastavit jako „viditelný ve výchozím nastavení“ nastavením Show*-flags (ShowValue, ...) vlastnosti DefaultDataLabelFormat na true.

**Vrací:**
boolean
### hide() {#hide--}
```
public abstract void hide()
```


Skryje datový štítek ve výchozím nastavení nastavením všech Show*-flags (ShowValue, ...) vlastnosti DefaultDataLabelFormat na false. IsVisible bude po tomto nastavení false.

--------------------

Pokud je datový štítek ve výchozím nastavení viditelný, můžete jej skrýt ve výchozím nastavení metodou Hide(). Pokud však datový štítek není ve výchozím nastavení viditelný (IsVisible je false), můžete jej nastavit jako „viditelný ve výchozím nastavení“ nastavením Show*-flags (ShowValue, ...) vlastnosti DefaultDataLabelFormat na true.
### getCountOfVisibleDataLabels() {#getCountOfVisibleDataLabels--}
```
public abstract int getCountOfVisibleDataLabels()
```


Získá počet viditelných datových štítků ve sbírce. Pouze pro čtení  int .

**Vrací:**
int
### getCount() {#getCount--}
```
public abstract int getCount()
```


Získá počet všech datových štítků ve sbírce. Pouze pro čtení  int .

**Vrací:**
int
### getParentSeries() {#getParentSeries--}
```
public abstract IChartSeries getParentSeries()
```


Vrací nadřazenou sérii grafu. Pouze pro čtení [IChartSeries](../../com.aspose.slides/ichartseries).

**Vrací:**
[IChartSeries](../../com.aspose.slides/ichartseries)
### indexOf(IDataLabel value) {#indexOf-com.aspose.slides.IDataLabel-}
```
public abstract int indexOf(IDataLabel value)
```


Vrací index zadaného DataLabel ve sbírce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IDataLabel](../../com.aspose.slides/idatalabel) | DataLabel k nalezení. |

**Vrací:**
int - Index DataLabel nebo -1, pokud DataLabel nepatří do této sbírky.