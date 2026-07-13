---
title: IRow
second_title: Aspose.Slides per Android tramite Java API Reference
description: Rappresenta una riga in una tabella.
type: docs
url: /it/com.aspose.slides/irow/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.ICellCollection](../../com.aspose.slides/icellcollection), [com.aspose.slides.IBulkTextFormattable](../../com.aspose.slides/ibulktextformattable)
```
public interface IRow extends ICellCollection, IBulkTextFormattable
```

Rappresenta una riga in una tabella.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getHeight()](#getHeight--) | Restituisce l'altezza di una riga. |
| [getMinimalHeight()](#getMinimalHeight--) | Restituisce o imposta l'altezza minima possibile di una riga. |
| [setMinimalHeight(double value)](#setMinimalHeight-double-) | Restituisce o imposta l'altezza minima possibile di una riga. |
| [getRowFormat()](#getRowFormat--) | Restituisce l'oggetto RowFormat che contiene le proprietà di formattazione per questa riga. |
### getHeight() {#getHeight--}
```
public abstract double getHeight()
```

Restituisce l'altezza di una riga. Solo lettura double.

**Restituisce:**
double
### getMinimalHeight() {#getMinimalHeight--}
```
public abstract double getMinimalHeight()
```

Restituisce o imposta l'altezza minima possibile di una riga. Lettura/scrittura double.

**Restituisce:**
double
### setMinimalHeight(double value) {#setMinimalHeight-double-}
```
public abstract void setMinimalHeight(double value)
```

Restituisce o imposta l'altezza minima possibile di una riga. Lettura/scrittura double.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | double |  |
### getRowFormat() {#getRowFormat--}
```
public abstract IRowFormat getRowFormat()
```

Restituisce l'oggetto RowFormat che contiene le proprietà di formattazione per questa riga. Solo lettura [IRowFormat](../../com.aspose.slides/irowformat).

**Restituisce:**
[IRowFormat](../../com.aspose.slides/irowformat)