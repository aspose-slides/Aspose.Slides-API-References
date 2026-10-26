---
title: IChartCategory
second_title: Aspose.Slides för Android via Java API-referens
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
| [getUseCell()](#getUseCell--) | Om true är AsCell property aktuell. |
| [getAsCell()](#getAsCell--) | Returnerar eller anger IChartDataCell-objekt. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | Returnerar eller anger IChartDataCell-objekt. |
| [getAsLiteral()](#getAsLiteral--) | Returnerar eller anger AsLiteral om UseCell är false. |
| [setAsLiteral(Object value)](#setAsLiteral-java.lang.Object-) | Returnerar eller anger AsLiteral om UseCell är false. |
| [getValue()](#getValue--) | Om UseCell är true representerar denna egenskap AsCell.Value property. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Om UseCell är true representerar denna egenskap AsCell.Value property. |
| [getGroupingLevels()](#getGroupingLevels--) | Hanterad behållare för värdena i diagramkategoriens grupperingsnivåer. |
| [remove()](#remove--) | Tar bort kategori från diagrammet. |
### getUseCell() {#getUseCell--}
```
public abstract boolean getUseCell()
```

Om true är AsCell property aktuell. Med andra ord används arbetsbladet för att lagra kategori (detta fall stöder en flernivåkategori). Om false är AsLiteral property aktuell. Med andra ord används arbetsbladet INTE för att lagra kategori (och detta fall stöder inte flernivåkategorier). Skrivskyddad boolean.

--------------------

För att ändra värdet på denna egenskap (för alla kategorier i samlingen) sätt det nya värdet till [ChartCategoryCollection.getUseCells()](../../com.aspose.slides/chartcategorycollection\#getUseCells--) property.

**Returnerar:**
boolean
### getAsCell() {#getAsCell--}
```
public abstract IChartDataCell getAsCell()
```

Returnerar eller anger IChartDataCell-objekt. Om kategorin är flernivå används IChartDataCell-objekt för nivå "0". Läs/skriv [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Returnerar:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setAsCell(IChartDataCell value)
```

Returnerar eller anger IChartDataCell-objekt. Om kategorin är flernivå används IChartDataCell-objekt för nivå "0". Läs/skriv [IChartDataCell](../../com.aspose.slides/ichartdatacell).

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

Om UseCell är true representerar denna egenskap AsCell.Value property. Om UseCell är false representerar denna egenskap AsLiteral property. Läs/skriv Object.

**Returnerar:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```

Om UseCell är true representerar denna egenskap AsCell.Value property. Om UseCell är false representerar denna egenskap AsLiteral property. Läs/skriv Object.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.Object |  |
### getGroupingLevels() {#getGroupingLevels--}
```
public abstract IChartCategoryLevelsManager getGroupingLevels()
```

Hanterad behållare för värdena i diagramkategoriens grupperingsnivåer. Flernivåkategori innehåller mer än en grupperingsnivå. Indexering av gruppnivåer är nollbaserad. Skrivskyddad [IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager).

**Returnerar:**
[IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager)
### remove() {#remove--}
```
public abstract void remove()
```

Tar bort kategori från diagrammet.