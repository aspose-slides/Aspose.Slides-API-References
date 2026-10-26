---
title: IDataLabelCollection
second_title: Aspose.Slides pro Android pomocí Java API Reference
description: Reprezentuje popisky řady.
type: docs
url: /cs/com.aspose.slides/idatalabelcollection/
---
**Všechny implementované rozhraní:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable, [com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IDataLabelCollection extends System.Collections.Generic.IGenericEnumerable<IDataLabel>, IChartComponent
```

Reprezentuje popisky řady.
## Metody

| Metoda | Popis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Získá popisek dat pro datový bod se zadaným indexem. |
| [getDefaultDataLabelFormat()](#getDefaultDataLabelFormat--) | Vrací výchozí formát všech popisků dat ve sbírce. |
| [getLeaderLinesFormat()](#getLeaderLinesFormat--) | Reprezentuje formát čar ukazujících na popisky dat. |
| [isVisible()](#isVisible--) | False znamená, že popisek dat není ve výchozím nastavení viditelný (a tudíž všechna příznaky Show\*-flags (ShowValue, ...) vlastnosti DefaultDataLabelFormat jsou false). |
| [hide()](#hide--) | Skryje popisek dat ve výchozím nastavení nastavením všech příznaků Show\*-flags (ShowValue, ...) vlastnosti DefaultDataLabelFormat na false. |
| [getCountOfVisibleDataLabels()](#getCountOfVisibleDataLabels--) | Získá počet viditelných popisků dat ve sbírce. |
| [getCount()](#getCount--) | Získá počet všech popisků dat ve sbírce. |
| [getParentSeries()](#getParentSeries--) | Vrací rodičovskou řadu grafu. |
| [indexOf(IDataLabel value)](#indexOf-com.aspose.slides.IDataLabel-) | Vrací index zadaného DataLabel ve sbírce. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IDataLabel get_Item(int index)
```

Získá popisek dat pro datový bod se zadaným indexem.

--------------------

Alternativní způsob přístupu k popisku dat je: - getSeries().getDataPoints().get_Item(i).getLabel() - spravovat vlastnosti popisku.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Vrací:**
[IDataLabel](../../com.aspose.slides/idatalabel)
### getDefaultDataLabelFormat() {#getDefaultDataLabelFormat--}
```
public abstract IDataLabelFormat getDefaultDataLabelFormat()
```

Vrací výchozí formát všech popisků dat ve sbírce. Pouze pro čtení [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**Vrací:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getLeaderLinesFormat() {#getLeaderLinesFormat--}
```
public abstract IChartLinesFormat getLeaderLinesFormat()
```

Reprezentuje formát čar ukazujících na popisky dat. Pouze pro čtení [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

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

**Vrací:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

False znamená, že popisek dat není ve výchozím nastavení viditelný (a tudíž všechna příznaky Show\*-flags (ShowValue, ...) vlastnosti DefaultDataLabelFormat jsou false). Pouze pro čtení  boolean .

--------------------

Pokud je popisek dat ve výchozím nastavení viditelný, můžete jej ve výchozím nastavení skrýt pomocí metody Hide(). Pokud popisek dat není ve výchozím nastavení viditelný (IsVisible je false), můžete jej „viditelný ve výchozím nastavení“ učinit nastavením příznaků Show\*-flags (ShowValue, ...) vlastnosti DefaultDataLabelFormat na stav true.

**Vrací:**
boolean
### hide() {#hide--}
```
public abstract void hide()
```

Skryje popisek dat ve výchozím nastavení nastavením všech příznaků Show\*-flags (ShowValue, ...) vlastnosti DefaultDataLabelFormat do stavu false. IsVisible bude po tomto nastavení false.

--------------------

Pokud popisek dat není ve výchozím nastavení viditelný (IsVisible je false), můžete jej „viditelný ve výchozím nastavení“ učinit nastavením příznaků Show\*-flags (ShowValue, ...) vlastnosti DefaultDataLabelFormat na stav true.

### getCountOfVisibleDataLabels() {#getCountOfVisibleDataLabels--}
```
public abstract int getCountOfVisibleDataLabels()
```

Získá počet viditelných popisků dat ve sbírce. Pouze pro čtení  int .

**Vrací:**
int
### getCount() {#getCount--}
```
public abstract int getCount()
```

Získá počet všech popisků dat ve sbírce. Pouze pro čtení  int .

**Vrací:**
int
### getParentSeries() {#getParentSeries--}
```
public abstract IChartSeries getParentSeries()
```

Vrací rodičovskou řadu grafu. Pouze pro čtení [IChartSeries](../../com.aspose.slides/ichartseries).

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
int - Index DataLabel nebo -1 pokud DataLabel není součástí této sbírky.