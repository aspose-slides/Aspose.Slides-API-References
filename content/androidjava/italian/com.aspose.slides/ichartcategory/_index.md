---
title: IChartCategory
second_title: Aspose.Slides for Android via Java API Reference
description: Represents chart categories.
type: docs
url: /it/com.aspose.slides/ichartcategory/
---```
public interface IChartCategory
```

Rappresenta le categorie del grafico.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getUseCell()](#getUseCell--) | Se true, la proprietà AsCell è effettiva. |
| [getAsCell()](#getAsCell--) | Restituisce o imposta l'oggetto IChartDataCell. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | Restituisce o imposta l'oggetto IChartDataCell. |
| [getAsLiteral()](#getAsLiteral--) | Restituisce o imposta AsLiteral se UseCell è false. |
| [setAsLiteral(Object value)](#setAsLiteral-java.lang.Object-) | Restituisce o imposta AsLiteral se UseCell è false. |
| [getValue()](#getValue--) | Se UseCell è true, questa proprietà rappresenta la proprietà AsCell.Value. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Se UseCell è true, questa proprietà rappresenta la proprietà AsCell.Value. |
| [getGroupingLevels()](#getGroupingLevels--) | Contenitore gestito dei valori dei livelli di raggruppamento delle categorie del grafico. |
| [remove()](#remove--) | Rimuove la categoria dal grafico. |
### getUseCell() {#getUseCell--}
```
public abstract boolean getUseCell()
```

Se true, la proprietà AsCell è effettiva. In altre parole, il foglio di lavoro è usato per memorizzare la categoria (questo caso supporta una categoria a più livelli). Se false, la proprietà AsLiteral è effettiva. In altre parole, il foglio di lavoro NON è usato per memorizzare la categoria (e questo caso non supporta categorie a più livelli). Booleano sola lettura.

--------------------

Per modificare il valore di questa proprietà (per tutte le categorie nella collezione) impostare il nuovo valore sulla proprietà [ChartCategoryCollection.getUseCells()](../../com.aspose.slides/chartcategorycollection\#getUseCells--).

### getAsCell() {#getAsCell--}
```
public abstract IChartDataCell getAsCell()
```

Restituisce o imposta l'oggetto IChartDataCell. Se la categoria è a più livelli, allora viene usato l'oggetto IChartDataCell per il livello "0". Lettura/scrittura [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Restituisce:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setAsCell(IChartDataCell value)
```

Restituisce o imposta l'oggetto IChartDataCell. Se la categoria è a più livelli, allora viene usato l'oggetto IChartDataCell per il livello "0". Lettura/scrittura [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getAsLiteral() {#getAsLiteral--}
```
public abstract Object getAsLiteral()
```

Restituisce o imposta AsLiteral se UseCell è false. Lettura/scrittura Object.

**Restituisce:**
java.lang.Object
### setAsLiteral(Object value) {#setAsLiteral-java.lang.Object-}
```
public abstract void setAsLiteral(Object value)
```

Restituisce o imposta AsLiteral se UseCell è false. Lettura/scrittura Object.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.Object |  |

### getValue() {#getValue--}
```
public abstract Object getValue()
```

Se UseCell è true, questa proprietà rappresenta la proprietà AsCell.Value. Se UseCell è false, questa proprietà rappresenta la proprietà AsLiteral. Lettura/scrittura Object.

**Restituisce:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```

Se UseCell è true, questa proprietà rappresenta la proprietà AsCell.Value. Se UseCell è false, questa proprietà rappresenta la proprietà AsLiteral. Lettura/scrittura Object.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.Object |  |

### getGroupingLevels() {#getGroupingLevels--}
```
public abstract IChartCategoryLevelsManager getGroupingLevels()
```

Contenitore gestito dei valori dei livelli di raggruppamento delle categorie del grafico. Una categoria a più livelli contiene più di un livello di raggruppamento. L'indicizzazione dei livelli di raggruppamento è a base zero. Sola lettura [IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager).

**Restituisce:**
[IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager)
### remove() {#remove--}
```
public abstract void remove()
```

Rimuove la categoria dal grafico.