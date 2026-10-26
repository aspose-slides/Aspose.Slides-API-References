---
title: IBehaviorCollection
second_title: Riferimento API Java per Aspose.Slides per Android
description: Rappresenta una raccolta di effetti di comportamento.
type: docs
url: /it/com.aspose.slides/ibehaviorcollection/
---
**Tutte le interfacce implementate:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IBehaviorCollection extends System.Collections.Generic.IGenericEnumerable<IBehavior>
```

Rappresenta una raccolta di effetti di comportamento.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Restituisce un comportamento all'indice specificato. |
| [set_Item(int index, IBehavior value)](#set-Item-int-com.aspose.slides.IBehavior-) | Restituisce un comportamento all'indice specificato. |
| [getCount()](#getCount--) | Restituisce il numero di comportamenti in una raccolta. |
| [add(IBehavior item)](#add-com.aspose.slides.IBehavior-) | Aggiunge un nuovo comportamento a una raccolta. |
| [indexOf(IBehavior item)](#indexOf-com.aspose.slides.IBehavior-) | Determina l'indice di un elemento specifico nella Lista. |
| [insert(int index, IBehavior item)](#insert-int-com.aspose.slides.IBehavior-) | Inserisce un nuovo comportamento in una raccolta all'indice specificato. |
| [remove(IBehavior item)](#remove-com.aspose.slides.IBehavior-) | Rimuove il comportamento specificato da una raccolta. |
| [removeAt(int index)](#removeAt-int-) | Rimuove un comportamento da una raccolta all'indice specificato. |
| [clear()](#clear--) | Rimuove tutti i comportamenti da una raccolta. |
| [contains(IBehavior item)](#contains-com.aspose.slides.IBehavior-) | Determina se il [IGenericCollection](../../com.aspose.slides/igenericcollection) contiene un valore specifico. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IBehavior get_Item(int index)
```

Restituisce un comportamento all'indice specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice del comportamento da restituire. |

**Restituisce:**
[IBehavior](../../com.aspose.slides/ibehavior) - Comportamento di animazione.
### set_Item(int index, IBehavior value) {#set-Item-int-com.aspose.slides.IBehavior-}
```
public abstract void set_Item(int index, IBehavior value)
```

Restituisce un comportamento all'indice specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice del comportamento da restituire. |
| value | [IBehavior](../../com.aspose.slides/ibehavior) |  |

### getCount() {#getCount--}
```
public abstract int getCount()
```

Restituisce il numero di comportamenti in una raccolta. int di sola lettura.

**Restituisce:**
int
### add(IBehavior item) {#add-com.aspose.slides.IBehavior-}
```
public abstract void add(IBehavior item)
```

Aggiunge un nuovo comportamento a una raccolta.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Comportamento da aggiungere. |

### indexOf(IBehavior item) {#indexOf-com.aspose.slides.IBehavior-}
```
public abstract int indexOf(IBehavior item)
```

Determina l'indice di un elemento specifico nella Lista.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | L'oggetto da trovare nella Lista. |

**Restituisce:**
int - L'indice dell'elemento se trovato nella lista; altrimenti, -1.
### insert(int index, IBehavior item) {#insert-int-com.aspose.slides.IBehavior-}
```
public abstract void insert(int index, IBehavior item)
```

Inserisce un nuovo comportamento in una raccolta all'indice specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice dove il nuovo comportamento dovrebbe essere inserito. |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Comportamento da inserire. |

### remove(IBehavior item) {#remove-com.aspose.slides.IBehavior-}
```
public abstract boolean remove(IBehavior item)
```

Rimuove il comportamento specificato da una raccolta.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Comportamento da rimuovere. |

**Restituisce:**
boolean - True se un comportamento è stato rimosso con successo boolean
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Rimuove un comportamento da una raccolta all'indice specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice di un comportamento da rimuovere. |

### clear() {#clear--}
```
public abstract void clear()
```

Rimuove tutti i comportamenti da una raccolta.

### contains(IBehavior item) {#contains-com.aspose.slides.IBehavior-}
```
public abstract boolean contains(IBehavior item)
```

Determina se il [IGenericCollection](../../com.aspose.slides/igenericcollection) contiene un valore specifico.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | L'oggetto da individuare nel [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Restituisce:**
boolean - true se l'elemento è trovato nel [IGenericCollection](../../com.aspose.slides/igenericcollection); altrimenti, false.