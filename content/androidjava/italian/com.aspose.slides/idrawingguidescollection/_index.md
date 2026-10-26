---
title: IDrawingGuidesCollection
second_title: Riferimento API Java di Aspose.Slides per Android
description: Rappresenta una raccolta delle guide di disegno regolabili.
type: docs
url: /it/com.aspose.slides/idrawingguidescollection/
---
**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IDrawingGuidesCollection extends System.Collections.Generic.IGenericEnumerable<IDrawingGuide>
```

Rappresenta una raccolta delle guide di disegno regolabili.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Restituisce la guida di disegno per indice. |
| [add(byte orientation, float position)](#add-byte-float-) | Aggiunge la guida di disegno alla fine della raccolta. |
| [removeAt(int index)](#removeAt-int-) | Rimuove la guida di disegno all'indice specificato. |
| [clear()](#clear--) | Rimuove tutti gli elementi dalla raccolta. |
| [getCount()](#getCount--) | Ottiene il numero di tutti gli elementi nella raccolta. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IDrawingGuide get_Item(int index)
```


Restituisce la guida di disegno per indice. Solo lettura [IDrawingGuide](../../com.aspose.slides/idrawingguide).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int |  |

**Restituisce:**
[IDrawingGuide](../../com.aspose.slides/idrawingguide)
### add(byte orientation, float position) {#add-byte-float-}
```
public abstract IDrawingGuide add(byte orientation, float position)
```


Aggiunge la guida di disegno alla fine della raccolta.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| orientation | byte | Orientamento della guida di disegno. |
| position | float | Posizione della guida di disegno in punti. |

**Restituisce:**
[IDrawingGuide](../../com.aspose.slides/idrawingguide)
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Rimuove la guida di disegno all'indice specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice della guida di disegno da eliminare. |

### clear() {#clear--}
```
public abstract void clear()
```


Rimuove tutti gli elementi dalla raccolta.

### getCount() {#getCount--}
```
public abstract int getCount()
```


Ottiene il numero di tutti gli elementi nella raccolta. Solo lettura int.

**Restituisce:**
int