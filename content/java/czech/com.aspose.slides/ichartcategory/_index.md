---
title: IChartCategory
second_title: Aspose.Slides pro Java API Reference
description: Reprezentuje kategorie grafu.
type: docs
url: /cs/com.aspose.slides/ichartcategory/
---```
public interface IChartCategory
```

Reprezentuje kategorie grafu.
## Metody

| Metoda | Popis |
| --- | --- |
| [getUseCell()](#getUseCell--) | Pokud je true, pak je vlastnost AsCell aktuální. |
| [getAsCell()](#getAsCell--) | Vrací nebo nastavuje objekt IChartDataCell. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | Vrací nebo nastavuje objekt IChartDataCell. |
| [getAsLiteral()](#getAsLiteral--) | Vrací nebo nastavuje AsLiteral, pokud je UseCell false. |
| [setAsLiteral(Object value)](#setAsLiteral-java.lang.Object-) | Vrací nebo nastavuje AsLiteral, pokud je UseCell false. |
| [getValue()](#getValue--) | Pokud je UseCell true, pak tato vlastnost představuje vlastnost AsCell.Value. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Pokud je UseCell true, pak tato vlastnost představuje vlastnost AsCell.Value. |
| [getCachedValue()](#getCachedValue--) | Získá uloženou hodnotu kategorie grafu. |
| [getGroupingLevels()](#getGroupingLevels--) | Spravovaný kontejner hodnot úrovní seskupení kategorií grafu. |
| [remove()](#remove--) | Odstraní kategorii z grafu. |
### getUseCell() {#getUseCell--}
```
public abstract boolean getUseCell()
```


Pokud je true, pak je vlastnost AsCell aktuální. Jinými slovy, sešit se používá k ukládání kategorie (tento případ podporuje víceúrovňovou kategorii). Pokud je false, pak je vlastnost AsLiteral aktuální. Jinými slovy, sešit se NEpoužívá k ukládání kategorie (a tento případ nepodporuje víceúrovňové kategorie). Pouze ke čtení, boolean.

--------------------

Pro změnu hodnoty této vlastnosti (pro všechny kategorie ve sbírce) nastavte novou hodnotu na vlastnost [ChartCategoryCollection.getUseCells()](../../com.aspose.slides/chartcategorycollection\#getUseCells--).

**Vrací:**
boolean
### getAsCell() {#getAsCell--}
```
public abstract IChartDataCell getAsCell()
```


Vrací nebo nastavuje objekt IChartDataCell. Pokud je kategorie víceúrovňová, použije se objekt IChartDataCell pro úroveň "0". Číst/zapisovat [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Vrací:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setAsCell(IChartDataCell value)
```


Vrací nebo nastavuje objekt IChartDataCell. Pokud je kategorie víceúrovňová, použije se objekt IChartDataCell pro úroveň "0". Číst/zapisovat [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getAsLiteral() {#getAsLiteral--}
```
public abstract Object getAsLiteral()
```


Vrací nebo nastavuje AsLiteral, pokud je UseCell false. Číst/zapisovat Object.

**Vrací:**
java.lang.Object
### setAsLiteral(Object value) {#setAsLiteral-java.lang.Object-}
```
public abstract void setAsLiteral(Object value)
```


Vrací nebo nastavuje AsLiteral, pokud je UseCell false. Číst/zapisovat Object.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.Object |  |

### getValue() {#getValue--}
```
public abstract Object getValue()
```


Pokud je UseCell true, pak tato vlastnost představuje vlastnost AsCell.Value. Pokud je UseCell false, pak tato vlastnost představuje vlastnost AsLiteral. Číst/zapisovat Object.

**Vrací:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```


Pokud je UseCell true, pak tato vlastnost představuje vlastnost AsCell.Value. Pokud je UseCell false, pak tato vlastnost představuje vlastnost AsLiteral. Číst/zapisovat Object.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.Object |  |

### getCachedValue() {#getCachedValue--}
```
public abstract ICachedChartValue getCachedValue()
```


Získá uloženou hodnotu kategorie grafu. Pouze ke čtení [ICachedChartValue](../../com.aspose.slides/icachedchartvalue).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
> 
>      // Vytiskne všechny kešované hodnoty kategorií grafu.
>      for (IChartCategory category : chart.getChartData().getCategories())
>          System.out.println(category.getCachedValue().toString());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Vrací:**
[ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
### getGroupingLevels() {#getGroupingLevels--}
```
public abstract IChartCategoryLevelsManager getGroupingLevels()
```


Spravovaný kontejner hodnot úrovní seskupení kategorií grafu. Víceúrovňová kategorie obsahuje více než jednu úroveň seskupení. Indexování úrovní seskupení začíná od nuly. Pouze ke čtení [IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager).

**Vrací:**
[IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager)
### remove() {#remove--}
```
public abstract void remove()
```


Odstraní kategorii z grafu.