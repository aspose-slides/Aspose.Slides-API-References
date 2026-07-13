---
title: ChartCategory
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt grafiekcategorieën voor.
type: docs
url: /nl/com.aspose.slides/chartcategory/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IChartCategory](../../com.aspose.slides/ichartcategory), com.aspose.slides.IDOMObject
```
public class ChartCategory implements IChartCategory, IDOMObject
```

Stelt grafiekcategorieën voor.
## Methoden

| Method | Description |
| --- | --- |
| [getUseCell()](#getUseCell--) | Als true is, dan is de AsCell-eigenschap actueel. |
| [getAsCell()](#getAsCell--) | Retourneert of stelt een IChartDataCell-object in. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | Retourneert of stelt een IChartDataCell-object in. |
| [getAsLiteral()](#getAsLiteral--) | Retourneert of stelt een AsLiteral-object in. |
| [setAsLiteral(Object value)](#setAsLiteral-java.lang.Object-) | Retourneert of stelt een AsLiteral-object in. |
| [getValue()](#getValue--) | Als UseCell true is, vertegenwoordigt deze eigenschap de AsCell.Value-eigenschap. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Als UseCell true is, vertegenwoordigt deze eigenschap de AsCell.Value-eigenschap. |
| [getGroupingLevels()](#getGroupingLevels--) | Beheerde container van de waarden van de groeperingsniveaus van grafiekcategorieën. |
| [remove()](#remove--) | Verwijdert de categorie uit de grafiek. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getUseCell() {#getUseCell--}
```
public final boolean getUseCell()
```


Als true is, dan is de AsCell-eigenschap actueel. Met andere woorden, werkblad wordt gebruikt voor het opslaan van de categorie (dit geval ondersteunt een meer-nivo-categorie). Als false is, dan is de AsLiteral-eigenschap actueel. Met andere woorden, werkblad wordt NIET gebruikt voor het opslaan van de categorie (en dit geval ondersteunt geen meer-nivo-categorieën). Alleen-lezen boolean.

--------------------

Om de waarde van deze eigenschap te wijzigen (voor alle categorieën in de collectie), stel een nieuwe waarde in op de eigenschap ChartCategoryCollection.UseCells.

**Returns:**
boolean
### getAsCell() {#getAsCell--}
```
public final IChartDataCell getAsCell()
```


Retourneert of stelt een IChartDataCell-object in. Als de categorie meer-nivo is, wordt het IChartDataCell-object voor niveau “0” gebruikt. Lezen/Schrijven [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Returns:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public final void setAsCell(IChartDataCell value)
```


Retourneert of stelt een IChartDataCell-object in. Als de categorie meer-nivo is, wordt het IChartDataCell-object voor niveau “0” gebruikt. Lezen/Schrijven [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getAsLiteral() {#getAsLiteral--}
```
public final Object getAsLiteral()
```


Retourneert of stelt een AsLiteral-object in. Lezen/Schrijven Object.

**Returns:**
java.lang.Object
### setAsLiteral(Object value) {#setAsLiteral-java.lang.Object-}
```
public final void setAsLiteral(Object value)
```


Retourneert of stelt een AsLiteral-object in. Lezen/Schrijven Object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Object |  |

### getValue() {#getValue--}
```
public final Object getValue()
```


Als UseCell true is, vertegenwoordigt deze eigenschap de AsCell.Value-eigenschap. Als UseCell false is, vertegenwoordigt deze eigenschap de AsLiteral-eigenschap. Lezen/Schrijven Object.

**Returns:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```


Als UseCell true is, vertegenwoordigt deze eigenschap de AsCell.Value-eigenschap. Als UseCell false is, vertegenwoordigt deze eigenschap de AsLiteral-eigenschap. Lezen/Schrijven Object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Object |  |

### getGroupingLevels() {#getGroupingLevels--}
```
public final IChartCategoryLevelsManager getGroupingLevels()
```


Beheerde container van de waarden van de groeperingsniveaus van grafiekcategorieën. Een meer-nivo-categorie bevat meer dan één groeperingsniveau. Indexering van groeperingsniveaus begint bij nul. Alleen-lezen [IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager).

**Returns:**
[IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager)
### remove() {#remove--}
```
public final void remove()
```


Verwijdert de categorie uit de grafiek.

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Retourneert Parent_Immediate-object. Alleen-lezen IDOMObject.

**Returns:**
com.aspose.slides.IDOMObject