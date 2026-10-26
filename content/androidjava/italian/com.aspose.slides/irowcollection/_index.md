---
title: IRowCollection
second_title: Riferimento API Java per Aspose.Slides per Android
description: Rappresenta la raccolta di righe della tabella.
type: docs
url: /it/com.aspose.slides/irowcollection/
---
**Tutte le interfacce implementate:**
com.aspose.slides.IGenericCollection
```
public interface IRowCollection extends IGenericCollection<IRow>
```

Rappresenta la raccolta di righe della tabella.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Ottiene l'elemento all'indice specificato. |
| [addClone(IRow templ, boolean withAttachedRows)](#addClone-com.aspose.slides.IRow-boolean-) | Crea una copia della riga modello specificata e la inserisce in fondo a una tabella. |
| [insertClone(int index, IRow templ, boolean withAttachedRows)](#insertClone-int-com.aspose.slides.IRow-boolean-) | Crea una copia della riga modello specificata e la inserisce nella posizione specificata in una tabella. |
| [removeAt(int firstRowIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | Rimuove una riga nella posizione specificata da una tabella. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IRow get_Item(int index)
```

Ottiene l'elemento all'indice specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int |  |

**Restituisce:**
[IRow](../../com.aspose.slides/irow)
### addClone(IRow templ, boolean withAttachedRows) {#addClone-com.aspose.slides.IRow-boolean-}
```
public abstract IRow[] addClone(IRow templ, boolean withAttachedRows)
```

Crea una copia della riga modello specificata e la inserisce in fondo a una tabella.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| templ | [IRow](../../com.aspose.slides/irow) | Riga usata come modello. |
| withAttachedRows | boolean | True per copiare anche tutte le righe collegate alla riga modello. |

**Restituisce:**
com.aspose.slides.IRow[] - Righe aggiunte.
### insertClone(int index, IRow templ, boolean withAttachedRows) {#insertClone-int-com.aspose.slides.IRow-boolean-}
```
public abstract IRow[] insertClone(int index, IRow templ, boolean withAttachedRows)
```

Crea una copia della riga modello specificata e la inserisce nella posizione specificata in una tabella.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice di una nuova riga. |
| templ | [IRow](../../com.aspose.slides/irow) | Riga usata come modello. |
| withAttachedRows | boolean | True per copiare anche tutte le righe collegate alla riga modello. |

**Restituisce:**
com.aspose.slides.IRow[] - Righe inserite.
### removeAt(int firstRowIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public abstract void removeAt(int firstRowIndex, boolean withAttachedRows)
```

Rimuove una riga nella posizione specificata da una tabella.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| firstRowIndex | int | Indice di una riga da eliminare. |
| withAttachedRows | boolean | True per eliminare anche tutte le righe collegate. |