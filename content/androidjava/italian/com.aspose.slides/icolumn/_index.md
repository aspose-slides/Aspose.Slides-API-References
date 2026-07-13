---
title: IColumn
second_title: Aspose.Slides per Android tramite Java API Reference
description: Rappresenta una colonna in una tabella.
type: docs
url: /it/com.aspose.slides/icolumn/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.ICellCollection](../../com.aspose.slides/icellcollection), [com.aspose.slides.IBulkTextFormattable](../../com.aspose.slides/ibulktextformattable)
```
public interface IColumn extends ICellCollection, IBulkTextFormattable
```

Rappresenta una colonna in una tabella.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getWidth()](#getWidth--) | Restituisce o imposta la larghezza di una colonna. |
| [setWidth(double value)](#setWidth-double-) | Restituisce o imposta la larghezza di una colonna. |
| [getColumnFormat()](#getColumnFormat--) | Restituisce l'oggetto ColumnFormat che contiene le proprietà di formattazione per questa colonna. |
### getWidth() {#getWidth--}
```
public abstract double getWidth()
```


Restituisce o imposta la larghezza di una colonna. Lettura/scrittura double.

**Restituisce:**
double
### setWidth(double value) {#setWidth-double-}
```
public abstract void setWidth(double value)
```


Restituisce o imposta la larghezza di una colonna. Lettura/scrittura double.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | double |  |

### getColumnFormat() {#getColumnFormat--}
```
public abstract IColumnFormat getColumnFormat()
```


Restituisce l'oggetto ColumnFormat che contiene le proprietà di formattazione per questa colonna. Solo lettura [IColumnFormat](../../com.aspose.slides/icolumnformat).

**Restituisce:**
[IColumnFormat](../../com.aspose.slides/icolumnformat)