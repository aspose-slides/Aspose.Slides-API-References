---
title: IChartCategory
second_title: Aspose.Slides for Java API Reference
description: Representerar diagramkategorier.
type: docs
url: /sv/com.aspose.slides/ichartcategory/
---```
public interface IChartCategory
```

Representerar diagramkategorier.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getUseCell()](#getUseCell--) | Om true är då AsCell-egenskapen aktuell. |
| [getAsCell()](#getAsCell--) | Returnerar eller anger IChartDataCell-objekt. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | Returnerar eller anger IChartDataCell-objekt. |
| [getAsLiteral()](#getAsLiteral--) | Returnerar eller anger AsLiteral om UseCell är false. |
| [setAsLiteral(Object value)](#setAsLiteral-java.lang.Object-) | Returnerar eller anger AsLiteral om UseCell är false. |
| [getValue()](#getValue--) | Om UseCell är true så representerar denna egendom AsCell.Value-egenskapen. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Om UseCell är true så representerar denna egendom AsCell.Value-egenskapen. |
| [getCachedValue()](#getCachedValue--) | Hämtar det cachade värdet för en diagramkategori. |
| [getGroupingLevels()](#getGroupingLevels--) | Hanterad behållare för värdena i diagramkategorins gruppnivåer. |
| [remove()](#remove--) | Tar bort kategori från diagrammet. |
### getUseCell() {#getUseCell--}
```
public abstract boolean getUseCell()
```

Om true är då AsCell-egenskapen aktuell. Med andra ord används arbetsbladet för att lagra kategori (detta fall stödjer en flernivåkategori). Om false är då AsLiteral-egenskapen aktuell. Med andra ord används arbetsbladet INTE för att lagra kategori (och detta fall stödjer inte flernivåkategorier). Skrivskyddad boolean.

--------------------

För att ändra värdet på denna egenskap (för alla kategorier i samlingen) sätt det nya värdet till [ChartCategoryCollection.getUseCells()](../../com.aspose.slides/chartcategorycollection\#getUseCells--)-egenskapen.

**Returnerar:**
boolean
### getAsCell() {#getAsCell--}
```
public abstract IChartDataCell getAsCell()
```

Returnerar eller anger IChartDataCell-objekt. Om kategori är flernivå används IChartDataCell-objekt för nivå "0". Läs/skriv [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Returnerar:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setAsCell(IChartDataCell value)
```

Returnerar eller anger IChartDataCell-objekt. Om kategori är flernivå används IChartDataCell-objekt för nivå "0". Läs/skriv [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |
### getAsLiteral() {#getAsLiteral--}
```
public abstract Object getAsLiteral()
```

Returnerar eller anger AsLiteral om UseCell är false. Läs/skriv Object.

**Returnerar:**
java.lang.Object
### setAsLiteral(Object value) {#setAsLiteral-java.lang.Object-}
```
public abstract void setAsLiteral(Object value)
```

Returnerar eller anger AsLiteral om UseCell är false. Läs/skriv Object.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.Object |  |
### getValue() {#getValue--}
```
public abstract Object getValue()
```

Om UseCell är true så representerar denna egenskap AsCell.Value-egenskapen. Om UseCell är false så representerar denna egenskap AsLiteral-egenskapen. Läs/skriv Object.

**Returnerar:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```

Om UseCell är true så representerar denna egenskap AsCell.Value-egenskapen. Om UseCell är false så representerar denna egenskap AsLiteral-egenskapen. Läs/skriv Object.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.Object |  |
### getCachedValue() {#getCachedValue--}
```
public abstract ICachedChartValue getCachedValue()
```

Hämtar det cachade värdet för en diagramkategori. Skrivskyddad [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
> 
>      // Skriv ut alla cachade diagramkategorivärden.
>      for (IChartCategory category : chart.getChartData().getCategories())
>          System.out.println(category.getCachedValue().toString());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returnerar:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
### getGroupingLevels() {#getGroupingLevels--}
```
public abstract IChartCategoryLevelsManager getGroupingLevels()
```

Hantera behållare för värdena i diagramkategorins gruppnivåer. Flernivåkategori innehåller mer än en gruppnivå. Indexering av gruppnivåer är nollbaserad. Skrivskyddad [IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager).

**Returnerar:**
[IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager)
### remove() {#remove--}
```
public abstract void remove()
```

Tar bort kategori från diagrammet.