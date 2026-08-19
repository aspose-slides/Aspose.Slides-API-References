---
title: ChartCategory
second_title: Aspose.Slides voor Java API Referentie
description: Stelt diagramcategorieën voor.
type: docs
url: /nl/com.aspose.slides/chartcategory/
---
**Erfenis:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IChartCategory](../../com.aspose.slides/ichartcategory), com.aspose.slides.IDOMObject
```
public class ChartCategory implements IChartCategory, IDOMObject
```

Stelt diagramcategorieën voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getUseCell()](#getUseCell--) | Indien true is, is de AsCell-eigenschap actueel. |
| [getAsCell()](#getAsCell--) | Retourneert of stelt IChartDataCell-object in. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | Retourneert of stelt IChartDataCell-object in. |
| [getAsLiteral()](#getAsLiteral--) | Retourneert of stelt AsLiteral-object in. |
| [setAsLiteral(Object value)](#setAsLiteral-java.lang.Object-) | Retourneert of stelt AsLiteral-object in. |
| [getValue()](#getValue--) | Als UseCell true is, vertegenwoordigt deze eigenschap de AsCell.Value-eigenschap. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Als UseCell true is, vertegenwoordigt deze eigenschap de AsCell.Value-eigenschap. |
| [getGroupingLevels()](#getGroupingLevels--) | Beheerde container van de waarden van de groeperingsniveaus van de diagramcategorie. |
| [remove()](#remove--) | Verwijdert categorie uit diagram. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getUseCell() {#getUseCell--}
```
public final boolean getUseCell()
```

Als true is, is de AsCell-eigenschap actueel. Met andere woorden, werkblad wordt gebruikt voor het opslaan van de categorie (dit geval ondersteunt een meerlagige categorie). Als false is, is de AsLiteral-eigenschap actueel. Met andere woorden, werkblad wordt NIET gebruikt voor het opslaan van de categorie (en dit geval ondersteunt geen meerlagige categorieën). Alleen-lezen boolean.

--------------------

Om de waarde van deze eigenschap te wijzigen (voor alle categorieën in de collectie), stel een nieuwe waarde in op de eigenschap ChartCategoryCollection.UseCells.

**Retourneert:**
boolean
### getAsCell() {#getAsCell--}
```
public final IChartDataCell getAsCell()
```

Retourneert of stelt IChartDataCell-object in. Als de categorie meerlagig is, wordt het IChartDataCell-object voor niveau "0" gebruikt. Lezen/schrijven [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Retourneert:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public final void setAsCell(IChartDataCell value)
```

Retourneert of stelt IChartDataCell-object in. Als de categorie meerlagig is, wordt het IChartDataCell-object voor niveau "0" gebruikt. Lezen/schrijven [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |
### getAsLiteral() {#getAsLiteral--}
```
public final Object getAsLiteral()
```

Retourneert of stelt AsLiteral-object in. Lezen/schrijven Object.

**Retourneert:**
java.lang.Object
### setAsLiteral(Object value) {#setAsLiteral-java.lang.Object-}
```
public final void setAsLiteral(Object value)
```

Retourneert of stelt AsLiteral-object in. Lezen/schrijven Object.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.Object |  |
### getValue() {#getValue--}
```
public final Object getValue()
```

Als UseCell true is, vertegenwoordigt deze eigenschap de AsCell.Value-eigenschap. Als UseCell false is, vertegenwoordigt deze eigenschap de AsLiteral-eigenschap. Lezen/schrijven Object.

**Retourneert:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```

Als UseCell true is, vertegenwoordigt deze eigenschap de AsCell.Value-eigenschap. Als UseCell false is, vertegenwoordigt deze eigenschap de AsLiteral-eigenschap. Lezen/schrijven Object.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.Object |  |
### getGroupingLevels() {#getGroupingLevels--}
```
public final IChartCategoryLevelsManager getGroupingLevels()
```

Beheerde container van de waarden van de groeperingsniveaus van de diagramcategorie. Een meerlagige categorie bevat meer dan één groeperingsniveau. De indexering van groeperingsniveaus is nulgebaseerd. Alleen-lezen [IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager).

**Retourneert:**
[IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager)
### remove() {#remove--}
```
public final void remove()
```

Verwijdert categorie uit diagram.

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Retourneert Parent_Immediate-object. Alleen-lezen IDOMObject.

**Retourneert:**
com.aspose.slides.IDOMObject