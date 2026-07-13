---
title: IColumnCollection
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Rappresenta una collezione di colonne in una tabella.
type: docs
url: /it/com.aspose.slides/icolumncollection/
---
**Tutte le Interfacce Implementate:**
com.aspose.slides.IGenericCollection
```
public interface IColumnCollection extends IGenericCollection<IColumn>
```

Rappresenta una collezione di colonne in una tabella.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Restituisce la colonna all'indice specificato. |
| [addClone(IColumn templ, boolean withAttachedColumns)](#addClone-com.aspose.slides.IColumn-boolean-) | Crea una copia della riga modello specificata e la inserisce nella parte inferiore di una tabella. |
| [insertClone(int index, IColumn templ, boolean withAttachedColumns)](#insertClone-int-com.aspose.slides.IColumn-boolean-) | Crea una copia della colonna modello specificata e la inserisce nella posizione specificata in una tabella. |
| [removeAt(int firstColumnIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | Rimuove una colonna nella posizione specificata da una tabella. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IColumn get_Item(int index)
```


Restituisce la colonna all'indice specificato. Solo lettura [IColumn](../../com.aspose.slides/icolumn).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int |  |

**Restituisce:**
[IColumn](../../com.aspose.slides/icolumn)
### addClone(IColumn templ, boolean withAttachedColumns) {#addClone-com.aspose.slides.IColumn-boolean-}
```
public abstract IColumn[] addClone(IColumn templ, boolean withAttachedColumns)
```


Crea una copia della riga modello specificata e la inserisce nella parte inferiore di una tabella.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| templ | [IColumn](../../com.aspose.slides/icolumn) | Colonna utilizzata come modello. |
| withAttachedColumns | boolean | True per copiare anche tutte le colonne collegate alla riga modello. |

**Restituisce:**
com.aspose.slides.IColumn[] - Colonne aggiunte.
### insertClone(int index, IColumn templ, boolean withAttachedColumns) {#insertClone-int-com.aspose.slides.IColumn-boolean-}
```
public abstract IColumn[] insertClone(int index, IColumn templ, boolean withAttachedColumns)
```


Crea una copia della colonna modello specificata e la inserisce nella posizione specificata in una tabella.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice di una nuova colonna. |
| templ | [IColumn](../../com.aspose.slides/icolumn) | Colonna utilizzata come modello. |
| withAttachedColumns | boolean | True per copiare anche tutte le colonne collegate alla colonna modello. |

**Restituisce:**
com.aspose.slides.IColumn[] - Colonne inserite.
### removeAt(int firstColumnIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public abstract void removeAt(int firstColumnIndex, boolean withAttachedRows)
```


Rimuove una colonna nella posizione specificata da una tabella.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| firstColumnIndex | int | Indice di una colonna da eliminare. |
| withAttachedRows | boolean | True per eliminare anche tutte le colonne collegate. |