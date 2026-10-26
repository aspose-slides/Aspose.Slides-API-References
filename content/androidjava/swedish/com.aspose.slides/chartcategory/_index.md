---
title: ChartCategory
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar diagramkategorier.
type: docs
url: /sv/com.aspose.slides/chartcategory/
---
**Arv:**
java.lang.Object

**Alla implementerade gränssnitt:**
[com.aspose.slides.IChartCategory](../../com.aspose.slides/ichartcategory), com.aspose.slides.IDOMObject
```
public class ChartCategory implements IChartCategory, IDOMObject
```

Representerar diagramkategorier.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getUseCell()](#getUseCell--) | Om true är AsCell-egenskapen aktuell. |
| [getAsCell()](#getAsCell--) | Returnerar eller sätter IChartDataCell-objekt. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | Returnerar eller sätter IChartDataCell-objekt. |
| [getAsLiteral()](#getAsLiteral--) | Returnerar eller sätter AsLiteral-objekt. |
| [setAsLiteral(Object value)](#setAsLiteral-java.lang.Object-) | Returnerar eller sätter AsLiteral-objekt. |
| [getValue()](#getValue--) | Om UseCell är true så representerar denna egenskap AsCell.Value-egenskapen. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Om UseCell är true så representerar denna egenskap AsCell.Value-egenskapen. |
| [getGroupingLevels()](#getGroupingLevels--) | Hanterad behållare för värdena i diagramkategori-grupperingsnivåerna. |
| [remove()](#remove--) | Tar bort kategori från diagrammet. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getUseCell() {#getUseCell--}
```
public final boolean getUseCell()
```


Om true är AsCell-egenskapen aktuell. Med andra ord används arbetsbladet för att lagra kategori (detta fall stödjer en flernivåkategori). Om false är AsLiteral-egenskapen aktuell. Med andra ord används arbetsbladet INTE för att lagra kategori (och detta fall stödjer inte flernivåkategorier). Skrivskyddad boolesk.

--------------------

För att ändra värdet på denna egenskap (för alla kategorier i samlingen) sätt det nya värdet till ChartCategoryCollection.UseCells-egenskapen.

**Returnerar:**
boolean
### getAsCell() {#getAsCell--}
```
public final IChartDataCell getAsCell()
```


Returnerar eller sätter IChartDataCell-objekt. Om kategorin är flernivå används IChartDataCell-objekt för nivå "0". Läs/skriv [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Returnerar:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public final void setAsCell(IChartDataCell value)
```


Returnerar eller sätter IChartDataCell-objekt. Om kategorin är flernivå används IChartDataCell-objekt för nivå "0". Läs/skriv [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getAsLiteral() {#getAsLiteral--}
```
public final Object getAsLiteral()
```


Returnerar eller sätter AsLiteral-objekt. Läs/skriv Object.

**Returnerar:**
java.lang.Object
### setAsLiteral(Object value) {#setAsLiteral-java.lang.Object-}
```
public final void setAsLiteral(Object value)
```


Returnerar eller sätter AsLiteral-objekt. Läs/skriv Object.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.Object |  |

### getValue() {#getValue--}
```
public final Object getValue()
```


Om UseCell är true så representerar denna egenskap AsCell.Value-egenskapen. Om UseCell är false så representerar denna egenskap AsLiteral-egenskapen. Läs/skriv Object.

**Returnerar:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```


Om UseCell är true så representerar denna egenskap AsCell.Value-egenskapen. Om UseCell är false så representerar denna egenskap AsLiteral-egenskapen. Läs/skriv Object.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.Object |  |

### getGroupingLevels() {#getGroupingLevels--}
```
public final IChartCategoryLevelsManager getGroupingLevels()
```


Hanterad behållare för värdena i diagramkategori-grupperingsnivåerna. Flernivåkategori innehåller mer än en grupperingsnivå. Indexering av grupperingsnivåer är nollbaserad. Skrivskyddad [IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager).

**Returnerar:**
[IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager)
### remove() {#remove--}
```
public final void remove()
```


Tar bort kategori från diagrammet.

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Returnerar Parent_Immediate-objekt. Skrivskyddad IDOMObject.

**Returnerar:**
com.aspose.slides.IDOMObject