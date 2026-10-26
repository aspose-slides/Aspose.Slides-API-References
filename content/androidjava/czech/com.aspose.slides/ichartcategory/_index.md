---
title: IChartCategory
second_title: Aspose.Slides for Android via Java API Reference
description: Represents chart categories.
type: docs
url: /cs/com.aspose.slides/ichartcategory/
---```
public interface IChartCategory
```

Represents chart categories.
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
| [getGroupingLevels()](#getGroupingLevels--) | Spravovaný kontejner hodnot úrovní seskupování kategorií grafu. |
| [remove()](#remove--) | Odstraňuje kategorii z grafu. |
### getUseCell() {#getUseCell--}
```
public abstract boolean getUseCell()
```


Pokud je true, pak je vlastnost AsCell aktuální. Jinak řečeno, list je používán pro ukládání kategorie (tento případ podporuje víceúrovňovou kategorii). Pokud je false, pak je vlastnost AsLiteral aktuální. Jinak řečeno, list NENÍ používán pro ukládání kategorie (a tento případ nepodporuje víceúrovňové kategorie). **Pouze pro čtení** boolean.

--------------------

Pro změnu hodnoty této vlastnosti (pro všechny kategorie ve sbírce) nastavte novou hodnotu vlastnosti [ChartCategoryCollection.getUseCells()](../../com.aspose.slides/chartcategorycollection\#getUseCells--).

**Vrací:**
boolean
### getAsCell() {#getAsCell--}
```
public abstract IChartDataCell getAsCell()
```


Vrací nebo nastavuje objekt IChartDataCell. Pokud je kategorie víceúrovňová, pak se používá objekt IChartDataCell pro úroveň „0“. **Čtení a zápis** [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Vrací:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setAsCell(IChartDataCell value)
```


Vrací nebo nastavuje objekt IChartDataCell. Pokud je kategorie víceúrovňová, pak se používá objekt IChartDataCell pro úroveň „0“. **Čtení a zápis** [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |
### getAsLiteral() {#getAsLiteral--}
```
public abstract Object getAsLiteral()
```


Vrací nebo nastavuje AsLiteral, pokud je UseCell false. **Čtení a zápis** Object.

**Vrací:**
java.lang.Object
### setAsLiteral(Object value) {#setAsLiteral-java.lang.Object-}
```
public abstract void setAsLiteral(Object value)
```


Vrací nebo nastavuje AsLiteral, pokud je UseCell false. **Čtení a zápis** Object.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.Object |  |
### getValue() {#getValue--}
```
public abstract Object getValue()
```


Pokud je UseCell true, pak tato vlastnost představuje vlastnost AsCell.Value. Pokud je UseCell false, pak tato vlastnost představuje vlastnost AsLiteral. **Čtení a zápis** Object.

**Vrací:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```


Pokud je UseCell true, pak tato vlastnost představuje vlastnost AsCell.Value. Pokud je UseCell false, pak tato vlastnost představuje vlastnost AsLiteral. **Čtení a zápis** Object.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.Object |  |
### getGroupingLevels() {#getGroupingLevels--}
```
public abstract IChartCategoryLevelsManager getGroupingLevels()
```


Spravovaný kontejner hodnot úrovní seskupování kategorií grafu. Víceúrovňová kategorie obsahuje více než jednu úroveň seskupování. Indexování úrovní seskupování je nulové. **Pouze pro čtení** [IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager).

**Vrací:**
[IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager)
### remove() {#remove--}
```
public abstract void remove()
```


Odstraňuje kategorii z grafu.