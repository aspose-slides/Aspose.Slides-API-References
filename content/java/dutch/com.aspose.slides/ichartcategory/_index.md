---
title: IChartCategory
second_title: Aspose.Slides for Java API Reference
description: Stelt diagramcategorieën voor.
type: docs
url: /nl/com.aspose.slides/ichartcategory/
---```
public interface IChartCategory
```

Stelt diagramcategorieën voor.
## Methoden

| Method | Description |
| --- | --- |
| [getUseCell()](#getUseCell--) | Als true dan is de AsCell-eigenschap actueel. |
| [getAsCell()](#getAsCell--) | Retourneert of stelt IChartDataCell-object in. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | Retourneert of stelt IChartDataCell-object in. |
| [getAsLiteral()](#getAsLiteral--) | Retourneert of stelt AsLiteral in als UseCell false is. |
| [setAsLiteral(Object value)](#setAsLiteral-java.lang.Object-) | Retourneert of stelt AsLiteral in als UseCell false is. |
| [getValue()](#getValue--) | Als UseCell true is, vertegenwoordigt deze eigenschap de AsCell.Value-eigenschap. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Als UseCell true is, vertegenwoordigt deze eigenschap de AsCell.Value-eigenschap. |
| [getCachedValue()](#getCachedValue--) | Haalt de gecachte waarde van een diagramcategorie op. |
| [getGroupingLevels()](#getGroupingLevels--) | Beheerde container van de waarden van de gegroepeerde niveaus van de diagramcategorie. |
| [remove()](#remove--) | Verwijdert de categorie uit het diagram. |
### getUseCell() {#getUseCell--}
```
public abstract boolean getUseCell()
```


Als true dan is de AsCell-eigenschap actueel. Met andere woorden, werkblad wordt gebruikt voor het opslaan van de categorie (dit geval ondersteunt een meerlagige categorie). Als false dan is de AsLiteral-eigenschap actueel. Met andere woorden, werkblad wordt NIET gebruikt voor het opslaan van de categorie (en dit geval ondersteunt geen meerlagige categorieën). Alleen-lezen boolean.

--------------------

Voor het wijzigen van de waarde van deze eigenschap (voor alle categorieën in de collectie) stel een nieuwe waarde in voor [ChartCategoryCollection.getUseCells()](../../com.aspose.slides/chartcategorycollection\#getUseCells--)-eigenschap.

**Retour:**
boolean
### getAsCell() {#getAsCell--}
```
public abstract IChartDataCell getAsCell()
```


Retourneert of stelt IChartDataCell-object in. Als de categorie meerlagig is, wordt IChartDataCell-object voor niveau “0” gebruikt. Lezen/schrijven [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Retour:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setAsCell(IChartDataCell value)
```


Retourneert of stelt IChartDataCell-object in. Als de categorie meerlagig is, wordt IChartDataCell-object voor niveau “0” gebruikt. Lezen/schrijven [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getAsLiteral() {#getAsLiteral--}
```
public abstract Object getAsLiteral()
```


Retourneert of stelt AsLiteral in als UseCell false is. Lezen/schrijven Object.

**Retour:**
java.lang.Object
### setAsLiteral(Object value) {#setAsLiteral-java.lang.Object-}
```
public abstract void setAsLiteral(Object value)
```


Retourneert of stelt AsLiteral in als UseCell false is. Lezen/schrijven Object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Object |  |

### getValue() {#getValue--}
```
public abstract Object getValue()
```


Als UseCell true is, vertegenwoordigt deze eigenschap de AsCell.Value-eigenschap. Als UseCell false is, vertegenwoordigt deze eigenschap de AsLiteral-eigenschap. Lezen/schrijven Object.

**Retour:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```


Als UseCell true is, vertegenwoordigt deze eigenschap de AsCell.Value-eigenschap. Als UseCell false is, vertegenwoordigt deze eigenschap de AsLiteral-eigenschap. Lezen/schrijven Object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Object |  |

### getCachedValue() {#getCachedValue--}
```
public abstract ICachedChartValue getCachedValue()
```


Haalt de gecachte waarde van een diagramcategorie op. Alleen-lezen [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
> 
>      // Print alle gecachte diagramcategorie waarden.
>      for (IChartCategory category : chart.getChartData().getCategories())
>          System.out.println(category.getCachedValue().toString());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Retour:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
### getGroupingLevels() {#getGroupingLevels--}
```
public abstract IChartCategoryLevelsManager getGroupingLevels()
```


Beheerde container van de waarden van de gegroepeerde niveaus van de diagramcategorie. Een meerlagige categorie bevat meer dan één groeperingsniveau. Indexering van groeperingsniveaus begint bij nul. Alleen-lezen [IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager).

**Retour:**
[IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager)
### remove() {#remove--}
```
public abstract void remove()
```


Verwijdert de categorie uit het diagram.