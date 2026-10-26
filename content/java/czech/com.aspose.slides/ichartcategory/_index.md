---
title: IChartCategory
second_title: Aspose.Slides pro Java API Reference
description: Zastupuje kategorie grafu.
type: docs
url: /cs/com.aspose.slides/ichartcategory/
---```
public interface IChartCategory
```

Zastupuje kategorie grafu.
## Metody

| Metoda | Popis |
| --- | --- |
| [getUseCell()](#getUseCell--) | If true then AsCell property is actual. |
| [getAsCell()](#getAsCell--) | Returns or sets IChartDataCell object. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | Returns or sets IChartDataCell object. |
| [getAsLiteral()](#getAsLiteral--) | Returns or sets AsLiteral if UseCell is false. |
| [setAsLiteral(Object value)](#setAsLiteral-java.lang.Object-) | Returns or sets AsLiteral if UseCell is false. |
| [getValue()](#getValue--) | If UseCell is true then this property represents AsCell.Value property. |
| [setValue(Object value)](#setValue-java.lang.Object-) | If UseCell is true then this property represents AsCell.Value property. |
| [getGroupingLevels()](#getGroupingLevels--) | Managed container of the values of the chart category grouping levels. |
| [remove()](#remove--) | Removes category from chart. |
### getUseCell() {#getUseCell--}
```
public abstract boolean getUseCell()
```

Pokud je true, pak je vlastnost AsCell aktuální. Jinak řečeno, list je použit k ukládání kategorie (tento případ podporuje víceúrovňovou kategorii). Pokud je false, pak je vlastnost AsLiteral aktuální. Jinak řečeno, list NENÍ použit k ukládání kategorie (a tento případ nepodporuje víceúrovňové kategorie). Pouze pro čtení, typ boolean.

--------------------

Pro změnu hodnoty této vlastnosti (pro všechny kategorie ve sbírce) nastavte novou hodnotu na vlastnost [ChartCategoryCollection.getUseCells()](../../com.aspose.slides/chartcategorycollection\#getUseCells--).

**Vrací:**
boolean
### getAsCell() {#getAsCell--}
```
public abstract IChartDataCell getAsCell()
```

Vrací nebo nastavuje objekt IChartDataCell. Pokud je kategorie víceúrovňová, použije se objekt IChartDataCell pro úroveň "0". Read/write [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Vrací:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setAsCell(IChartDataCell value)
```

Vrací nebo nastavuje objekt IChartDataCell. Pokud je kategorie víceúrovňová, použije se objekt IChartDataCell pro úroveň "0". Read/write [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getAsLiteral() {#getAsLiteral--}
```
public abstract Object getAsLiteral()
```

Vrací nebo nastavuje AsLiteral, pokud je UseCell false. Read/write Object.

**Vrací:**
java.lang.Object
### setAsLiteral(Object value) {#setAsLiteral-java.lang.Object-}
```
public abstract void setAsLiteral(Object value)
```

Vrací nebo nastavuje AsLiteral, pokud je UseCell false. Read/write Object.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.Object |  |

### getValue() {#getValue--}
```
public abstract Object getValue()
```

Pokud je UseCell true, pak tato vlastnost představuje vlastnost AsCell.Value. Pokud je UseCell false, pak tato vlastnost představuje vlastnost AsLiteral. Read/write Object.

**Vrací:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```

Pokud je UseCell true, pak tato vlastnost představuje vlastnost AsCell.Value. Pokud je UseCell false, pak tato vlastnost představuje vlastnost AsLiteral. Read/write Object.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.Object |  |

### getGroupingLevels() {#getGroupingLevels--}
```
public abstract IChartCategoryLevelsManager getGroupingLevels()
```

Spravovaný kontejner hodnot úrovní seskupování kategorií grafu. Víceúrovňová kategorie obsahuje více než jednu úroveň seskupování. Indexování úrovní seskupování začíná od nuly. Read-only [IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager).

**Vrací:**
[IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager)
### remove() {#remove--}
```
public abstract void remove()
```

Odstraní kategorii z grafu.