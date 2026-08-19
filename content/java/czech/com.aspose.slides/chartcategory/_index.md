---
title: ChartCategory
second_title: Aspose.Slides pro Java – referenční příručka API
description: Reprezentuje kategorie grafu.
type: docs
url: /cs/com.aspose.slides/chartcategory/
---
**Dědičnost:**
java.lang.Object

**Všechna implementovaná rozhraní:**
[com.aspose.slides.IChartCategory](../../com.aspose.slides/ichartcategory), com.aspose.slides.IDOMObject
```
public class ChartCategory implements IChartCategory, IDOMObject
```

Reprezentuje kategorie grafu.
## Metody

| Metoda | Popis |
| --- | --- |
| [getUseCell()](#getUseCell--) | Pokud je true, pak je vlastnost AsCell aktuální. |
| [getAsCell()](#getAsCell--) | Vrací nebo nastavuje objekt IChartDataCell. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | Vrací nebo nastavuje objekt IChartDataCell. |
| [getAsLiteral()](#getAsLiteral--) | Vrací nebo nastavuje objekt AsLiteral. |
| [setAsLiteral(Object value)](#setAsLiteral-java.lang.Object-) | Vrací nebo nastavuje objekt AsLiteral. |
| [getValue()](#getValue--) | Pokud je UseCell true, pak tato vlastnost představuje vlastnost AsCell.Value. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Pokud je UseCell true, pak tato vlastnost představuje vlastnost AsCell.Value. |
| [getGroupingLevels()](#getGroupingLevels--) | Spravovaný kontejner hodnot úrovní seskupování kategorií grafu. |
| [remove()](#remove--) | Odstraňuje kategorii z grafu. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getUseCell() {#getUseCell--}
```
public final boolean getUseCell()
```

Pokud je true, pak je vlastnost AsCell aktuální. Jinými slovy, list je používán k ukládání kategorie (tento případ podporuje vícestupňovou kategorii). Pokud je false, pak je vlastnost AsLiteral aktuální. Jinými slovy, list NENÍ používán k ukládání kategorie (a tento případ nepodporuje vícestupňové kategorie). Pouze pro čtení boolean.

Pro změnu hodnoty této vlastnosti (pro všechny kategorie ve sbírce) nastavte novou hodnotu na vlastnost ChartCategoryCollection.UseCells property.

**Vrací:**
boolean
### getAsCell() {#getAsCell--}
```
public final IChartDataCell getAsCell()
```

Vrací nebo nastavuje objekt IChartDataCell. Pokud je kategorie vícestupňová, pak je použito IChartDataCell pro úroveň "0". Čtení/Zápis [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Vrací:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public final void setAsCell(IChartDataCell value)
```

Vrací nebo nastavuje objekt IChartDataCell. Pokud je kategorie vícestupňová, pak je použito IChartDataCell pro úroveň "0". Čtení/Zápis [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |
### getAsLiteral() {#getAsLiteral--}
```
public final Object getAsLiteral()
```

Vrací nebo nastavuje objekt AsLiteral. Čtení/Zápis Object.

**Vrací:**
java.lang.Object
### setAsLiteral(Object value) {#setAsLiteral-java.lang.Object-}
```
public final void setAsLiteral(Object value)
```

Vrací nebo nastavuje objekt AsLiteral. Čtení/Zápis Object.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.Object |  |
### getValue() {#getValue--}
```
public final Object getValue()
```

Pokud je UseCell true, pak tato vlastnost představuje vlastnost AsCell.Value. Pokud je UseCell false, pak tato vlastnost představuje vlastnost AsLiteral. Čtení/Zápis Object.

**Vrací:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```

Pokud je UseCell true, pak tato vlastnost představuje vlastnost AsCell.Value. Pokud je UseCell false, pak tato vlastnost představuje vlastnost AsLiteral. Čtení/Zápis Object.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.Object |  |
### getGroupingLevels() {#getGroupingLevels--}
```
public final IChartCategoryLevelsManager getGroupingLevels()
```

Spravovaný kontejner hodnot úrovní seskupování kategorií grafu. Vícestupňová kategorie obsahuje více než jednu úroveň seskupování. Indexování úrovní seskupování je nulové. Pouze pro čtení [IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager).

**Vrací:**
[IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager)
### remove() {#remove--}
```
public final void remove()
```

Odstraňuje kategorii z grafu.

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Vrací objekt Parent_Immediate. Pouze pro čtení IDOMObject.

**Vrací:**
com.aspose.slides.IDOMObject