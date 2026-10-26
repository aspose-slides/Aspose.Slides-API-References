---
title: IPortionCollection
second_title: Riferimento API Java per Aspose.Slides per Android
description: Rappresenta una raccolta di porzioni.
type: docs
url: /it/com.aspose.slides/iportioncollection/
---
**Tutte le interfacce implementate:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IPortionCollection extends System.Collections.Generic.IGenericEnumerable<IPortion>
```

Rappresenta una raccolta di porzioni.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Restituisce l'elemento all'indice specificato. |
| [getCount()](#getCount--) | Restituisce il numero di elementi effettivamente contenuti nella raccolta. |
| [add(IPortion value)](#add-com.aspose.slides.IPortion-) | Aggiunge un Portion alla fine della raccolta. |
| [indexOf(IPortion item)](#indexOf-com.aspose.slides.IPortion-) | Determina l'indice di una specifica porzione nella raccolta. |
| [insert(int index, IPortion value)](#insert-int-com.aspose.slides.IPortion-) | Inserisce un Portion nella raccolta all'indice specificato. |
| [clear()](#clear--) | Rimuove tutti gli elementi dalla raccolta. |
| [contains(IPortion item)](#contains-com.aspose.slides.IPortion-) | Determina se il [IGenericCollection](../../com.aspose.slides/igenericcollection) contiene un valore specifico. |
| [remove(IPortion item)](#remove-com.aspose.slides.IPortion-) | Rimuove la prima occorrenza di un oggetto specifico dal [IGenericCollection](../../com.aspose.slides/igenericcollection). |
| [removeAt(int index)](#removeAt-int-) | Rimuove l'elemento all'indice specificato della raccolta. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IPortion get_Item(int index)
```

Restituisce l'elemento all'indice specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int |  |

**Restituisce:**
[IPortion](../../com.aspose.slides/iportion)
### getCount() {#getCount--}
```
public abstract int getCount()
```

Restituisce il numero di elementi effettivamente contenuti nella raccolta. Solo lettura int.

**Restituisce:**
int
### add(IPortion value) {#add-com.aspose.slides.IPortion-}
```
public abstract void add(IPortion value)
```

Aggiunge un Portion alla fine della raccolta.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IPortion](../../com.aspose.slides/iportion) | Il Portion da aggiungere alla fine della raccolta. |
### indexOf(IPortion item) {#indexOf-com.aspose.slides.IPortion-}
```
public abstract int indexOf(IPortion item)
```

Determina l'indice di una specifica porzione nella raccolta.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | La porzione da individuare nella raccolta. |

**Restituisce:**
int - L'indice dell'elemento se trovato nella raccolta; altrimenti, -1.
### insert(int index, IPortion value) {#insert-int-com.aspose.slides.IPortion-}
```
public abstract void insert(int index, IPortion value)
```

Inserisce un Portion nella raccolta all'indice specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | L'indice basato su zero al quale il Portion dovrebbe essere inserito. |
| value | [IPortion](../../com.aspose.slides/iportion) | Il Portion da inserire. |
### clear() {#clear--}
```
public abstract void clear()
```

Rimuove tutti gli elementi dalla raccolta.

### contains(IPortion item) {#contains-com.aspose.slides.IPortion-}
```
public abstract boolean contains(IPortion item)
```

Determina se il [IGenericCollection](../../com.aspose.slides/igenericcollection) contiene un valore specifico.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | L'oggetto da individuare nel [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Restituisce:**
boolean - true se l'elemento è trovato nel [IGenericCollection](../../com.aspose.slides/igenericcollection); altrimenti, false.
### remove(IPortion item) {#remove-com.aspose.slides.IPortion-}
```
public abstract boolean remove(IPortion item)
```

Rimuove la prima occorrenza di un oggetto specifico dal [IGenericCollection](../../com.aspose.slides/igenericcollection).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | L'oggetto da rimuovere dal [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Restituisce:**
boolean - true se l'elemento è stato rimosso con successo dal [IGenericCollection](../../com.aspose.slides/igenericcollection); altrimenti, false. Questo metodo restituisce anche false se l'elemento non è trovato nella [IGenericCollection](../../com.aspose.slides/igenericcollection) originale.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Rimuove l'elemento all'indice specificato della raccolta.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | L'indice basato su zero dell'elemento da rimuovere. |