---
title: IChartCategory
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt diagramcategorieën voor.
type: docs
url: /nl/com.aspose.slides/ichartcategory/
---```
public interface IChartCategory
```

Stelt diagramcategorieën voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getUseCell()](#getUseCell--) | Als true dan is de AsCell-eigenschap actueel. |
| [getAsCell()](#getAsCell--) | Retourneert of stelt IChartDataCell-object in. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | Retourneert of stelt IChartDataCell-object in. |
| [getAsLiteral()](#getAsLiteral--) | Retourneert of stelt AsLiteral in als UseCell false is. |
| [setAsLiteral(Object value)](#setAsLiteral-java.lang.Object-) | Retourneert of stelt AsLiteral in als UseCell false is. |
| [getValue()](#getValue--) | Als UseCell true is, vertegenwoordigt deze eigenschap de AsCell.Value-eigenschap. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Als UseCell true is, vertegenwoordigt deze eigenschap de AsCell.Value-eigenschap. |
| [getGroupingLevels()](#getGroupingLevels--) | Beheerde container van de waarden van de groeperingsniveaus van de diagramcategorie. |
| [remove()](#remove--) | Verwijdert categorie uit diagram. |
### getUseCell() {#getUseCell--}
```
public abstract boolean getUseCell()
```

Als true dan is de AsCell-eigenschap actueel. Met andere woorden, wordt werkblad gebruikt voor het opslaan van de categorie (dit geval ondersteunt een meerlagige categorie). Als false dan is de AsLiteral-eigenschap actueel. Met andere woorden, wordt werkblad NIET gebruikt voor het opslaan van de categorie (en dit geval ondersteunt geen meerlagige categorieën). Alleen-lezen boolean.

--------------------

Om de waarde van deze eigenschap te wijzigen (voor alle categorieën in de collectie) stel een nieuwe waarde in op de eigenschap [ChartCategoryCollection.getUseCells()](../../com.aspose.slides/chartcategorycollection\#getUseCells--).

**Retourneert:**
boolean
### getAsCell() {#getAsCell--}
```
public abstract IChartDataCell getAsCell()
```

Retourneert of stelt IChartDataCell-object in. Als de categorie meerlagig is, wordt IChartDataCell-object gebruikt voor niveau "0". Lezen/Schrijven [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Retourneert:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setAsCell(IChartDataCell value)
```

Retourneert of stelt IChartDataCell-object in. Als de categorie meerlagig is, wordt IChartDataCell-object gebruikt voor niveau "0". Lezen/Schrijven [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |
### getAsLiteral() {#getAsLiteral--}
```
public abstract Object getAsLiteral()
```

Retourneert of stelt AsLiteral in als UseCell false is. Lezen/Schrijven Object.

**Retourneert:**
java.lang.Object
### setAsLiteral(Object value) {#setAsLiteral-java.lang.Object-}
```
public abstract void setAsLiteral(Object value)
```

Retourneert of stelt AsLiteral in als UseCell false is. Lezen/Schrijven Object.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.Object |  |
### getValue() {#getValue--}
```
public abstract Object getValue()
```

Als UseCell true is, vertegenwoordigt deze eigenschap de AsCell.Value-eigenschap. Als UseCell false is, vertegenwoordigt deze eigenschap de AsLiteral-eigenschap. Lezen/Schrijven Object.

**Retourneert:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```

Als UseCell true is, vertegenwoordigt deze eigenschap de AsCell.Value-eigenschap. Als UseCell false is, vertegenwoordigt deze eigenschap de AsLiteral-eigenschap. Lezen/Schrijven Object.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.Object |  |
### getGroupingLevels() {#getGroupingLevels--}
```
public abstract IChartCategoryLevelsManager getGroupingLevels()
```

Beheerde container van de waarden van de groeperingsniveaus van de diagramcategorie. Een meerlagige categorie bevat meer dan één groeperingsniveau. Indexering van groeperingsniveaus is nulgebaseerd. Alleen-lezen [IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager).

**Retourneert:**
[IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager)
### remove() {#remove--}
```
public abstract void remove()
```

Verwijdert categorie uit diagram.