---
title: IChartCategory
second_title: Aspose.Slides för Java API-referens
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
| [getUseCell()](#getUseCell--) | Om true är AsCell-egenskapen aktuell. |
| [getAsCell()](#getAsCell--) | Returnerar eller anger IChartDataCell-objekt. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | Returnerar eller anger IChartDataCell-objekt. |
| [getAsLiteral()](#getAsLiteral--) | Returnerar eller anger AsLiteral om UseCell är false. |
| [setAsLiteral(Object value)](#setAsLiteral-java.lang.Object-) | Returnerar eller anger AsLiteral om UseCell är false. |
| [getValue()](#getValue--) | Om UseCell är true representerar denna egenskap AsCell.Value-egenskapen. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Om UseCell är true representerar denna egenskap AsCell.Value-egenskapen. |
| [getGroupingLevels()](#getGroupingLevels--) | Hanterad behållare av värdena för diagramkategorins grupperingsnivåer. |
| [remove()](#remove--) | Tar bort kategori från diagrammet. |
### getUseCell() {#getUseCell--}
```
public abstract boolean getUseCell()
```

Om true är AsCell-egenskapen aktuell. Med andra ord används arbetsbladet för att lagra kategori (detta fall stöder en flernivåkategori). Om false är AsLiteral-egenskapen aktuell. Med andra ord används arbetsbladet INTE för att lagra kategori (och detta fall stöder inte flernivåkategorier). Skrivskyddad boolesk.

För att ändra värdet på denna egenskap (för alla kategorier i samlingen) sätt ett nytt värde till [ChartCategoryCollection.getUseCells()](../../com.aspose.slides/chartcategorycollection\#getUseCells--)-egenskapen.

**Returnerar:**
boolean
### getAsCell() {#getAsCell--}
```
public abstract IChartDataCell getAsCell()
```

Returnerar eller anger IChartDataCell-objekt. Om kategorin är flernivåal används IChartDataCell-objekt för nivå "0". Läs/skriv [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Returnerar:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setAsCell(IChartDataCell value)
```

Returnerar eller anger IChartDataCell-objekt. Om kategorin är flernivåal används IChartDataCell-objekt för nivå "0". Läs/skriv [IChartDataCell](../../com.aspose.slides/ichartdatacell).

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

Om UseCell är true representerar denna egenskap AsCell.Value-egenskapen. Om UseCell är false representerar denna egenskap AsLiteral-egenskapen. Läs/skriv Object.

**Returnerar:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```

Om UseCell är true representerar denna egenskap AsCell.Value-egenskapen. Om UseCell är false representerar denna egenskap AsLiteral-egenskapen. Läs/skriv Object.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.Object |  |
### getGroupingLevels() {#getGroupingLevels--}
```
public abstract IChartCategoryLevelsManager getGroupingLevels()
```

Hanterad behållare av värdena för diagramkategorins grupperingsnivåer. Flernivåkategori innehåller mer än en grupperingsnivå. Indexering av grupperingsnivåer är nollbaserad. Skrivskyddad [IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager).

**Returnerar:**
[IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager)
### remove() {#remove--}
```
public abstract void remove()
```

Tar bort kategori från diagrammet.