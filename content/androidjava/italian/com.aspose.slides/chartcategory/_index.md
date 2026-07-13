---
title: ChartCategory
second_title: Aspose.Slides per Android tramite riferimento API Java
description: Rappresenta le categorie del grafico.
type: docs
url: /it/com.aspose.slides/chartcategory/
---
**Ereditarietà:**
java.lang.Object

**Tutte le interfacce implementate:**
[com.aspose.slides.IChartCategory](../../com.aspose.slides/ichartcategory), com.aspose.slides.IDOMObject
```
public class ChartCategory implements IChartCategory, IDOMObject
```

Rappresenta le categorie del grafico.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getUseCell()](#getUseCell--) | Se true allora la proprietà AsCell è effettiva. |
| [getAsCell()](#getAsCell--) | Restituisce o imposta l'oggetto IChartDataCell. |
| [setAsCell(IChartDataCell value)](#setAsCell-com.aspose.slides.IChartDataCell-) | Restituisce o imposta l'oggetto IChartDataCell. |
| [getAsLiteral()](#getAsLiteral--) | Restituisce o imposta l'oggetto AsLiteral. |
| [setAsLiteral(Object value)](#setAsLiteral-java.lang.Object-) | Restituisce o imposta l'oggetto AsLiteral. |
| [getValue()](#getValue--) | Se UseCell è true allora questa proprietà rappresenta la proprietà AsCell.Value. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Se UseCell è true allora questa proprietà rappresenta la proprietà AsCell.Value. |
| [getGroupingLevels()](#getGroupingLevels--) | Contenitore gestito dei valori dei livelli di raggruppamento delle categorie del grafico. |
| [remove()](#remove--) | Rimuove la categoria dal grafico. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getUseCell() {#getUseCell--}
```
public final boolean getUseCell()
```


Se true allora la proprietà AsCell è effettiva. In altre parole, il foglio di lavoro è usato per memorizzare la categoria (questo caso supporta una categoria multi-livello). Se false allora la proprietà AsLiteral è effettiva. In altre parole, il foglio di lavoro NON è usato per memorizzare la categoria (e questo caso non supporta categorie multi-livello). Solo lettura boolean.

--------------------

Per modificare il valore di questa proprietà (per tutte le categorie nella collezione) impostare il nuovo valore sulla proprietà ChartCategoryCollection.UseCells.

**Restituisce:**
boolean
### getAsCell() {#getAsCell--}
```
public final IChartDataCell getAsCell()
```


Restituisce o imposta l'oggetto IChartDataCell. Se la categoria è multi-livello allora viene usato l'oggetto IChartDataCell per il livello "0". Lettura/scrittura [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Restituisce:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setAsCell(IChartDataCell value) {#setAsCell-com.aspose.slides.IChartDataCell-}
```
public final void setAsCell(IChartDataCell value)
```


Restituisce o imposta l'oggetto IChartDataCell. Se la categoria è multi-livello allora viene usato l'oggetto IChartDataCell per il livello "0". Lettura/scrittura [IChartDataCell](../../com.aspose.slides/ichartdatacell).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |
### getAsLiteral() {#getAsLiteral--}
```
public final Object getAsLiteral()
```


Restituisce o imposta l'oggetto AsLiteral. Lettura/scrittura Object.

**Restituisce:**
java.lang.Object
### setAsLiteral(Object value) {#setAsLiteral-java.lang.Object-}
```
public final void setAsLiteral(Object value)
```


Restituisce o imposta l'oggetto AsLiteral. Lettura/scrittura Object.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.Object |  |
### getValue() {#getValue--}
```
public final Object getValue()
```


Se UseCell è true allora questa proprietà rappresenta la proprietà AsCell.Value. Se UseCell è false allora questa proprietà rappresenta la proprietà AsLiteral. Lettura/scrittura Object.

**Restituisce:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```


Se UseCell è true allora questa proprietà rappresenta la proprietà AsCell.Value. Se UseCell è false allora questa proprietà rappresenta la proprietà AsLiteral. Lettura/scrittura Object.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.Object |  |
### getGroupingLevels() {#getGroupingLevels--}
```
public final IChartCategoryLevelsManager getGroupingLevels()
```


Contenitore gestito dei valori dei livelli di raggruppamento delle categorie del grafico. Una categoria multi-livello contiene più di un livello di raggruppamento. L'indicizzazione dei livelli di raggruppamento parte da zero. Solo lettura [IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager).

**Restituisce:**
[IChartCategoryLevelsManager](../../com.aspose.slides/ichartcategorylevelsmanager)
### remove() {#remove--}
```
public final void remove()
```


Rimuove la categoria dal grafico.

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Restituisce l'oggetto Parent_Immediate. Solo lettura IDOMObject.

**Restituisce:**
com.aspose.slides.IDOMObject