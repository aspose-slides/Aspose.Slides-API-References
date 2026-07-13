---
title: VbaModuleCollection
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Rappresenta una collezione di moduli di un progetto VBA.
type: docs
url: /it/com.aspose.slides/vbamodulecollection/
---
**Eredita da:**
java.lang.Object

**Tutte le Interfacce Implementate:**
[com.aspose.slides.IVbaModuleCollection](../../com.aspose.slides/ivbamodulecollection)
```
public final class VbaModuleCollection implements IVbaModuleCollection
```

Rappresenta una collezione di moduli di un progetto VBA.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [size()](#size--) | Restituisce il numero di elementi effettivamente contenuti nella collezione. |
| [remove(IVbaModule value)](#remove-com.aspose.slides.IVbaModule-) | Rimuove la prima occorrenza di un oggetto specifico dalla collezione. |
| [addEmptyModule(String name)](#addEmptyModule-java.lang.String-) | Aggiunge un nuovo modulo vuoto al progetto VBA. |
| [get_Item(int index)](#get-Item-int-) | Restituisce l'elemento all'indice specificato. |
| [iterator()](#iterator--) | Restituisce un enumeratore che itera attraverso la collezione. |
| [iteratorJava()](#iteratorJava--) | Restituisce un iteratore java per l'intera collezione. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copia tutti gli elementi dalla collezione nell'array specificato. |
| [isSynchronized()](#isSynchronized--) | Restituisce un valore che indica se l'accesso alla collezione è sincronizzato (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Restituisce la radice di sincronizzazione. |
### size() {#size--}
```
public final int size()
```


Restituisce il numero di elementi effettivamente contenuti nella collezione. Solo lettura int.

**Restituisce:**
int
### remove(IVbaModule value) {#remove-com.aspose.slides.IVbaModule-}
```
public final void remove(IVbaModule value)
```


Rimuove la prima occorrenza di un oggetto specifico dalla collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IVbaModule](../../com.aspose.slides/ivbamodule) | Il modulo da rimuovere dalla collezione. |

### addEmptyModule(String name) {#addEmptyModule-java.lang.String-}
```
public final IVbaModule addEmptyModule(String name)
```


Aggiunge un nuovo modulo vuoto al progetto VBA.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| name | java.lang.String | Nome del modulo |

**Restituisce:**
[IVbaModule](../../com.aspose.slides/ivbamodule) - Modulo aggiunto.
### get_Item(int index) {#get-Item-int-}
```
public final IVbaModule get_Item(int index)
```


Restituisce l'elemento all'indice specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int |  |

**Restituisce:**
[IVbaModule](../../com.aspose.slides/ivbamodule)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IVbaModule> iterator()
```


Restituisce un enumeratore che itera attraverso la collezione.

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVbaModule> - Un IGenericEnumerator che può essere usato per iterare attraverso la collezione.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IVbaModule> iteratorJava()
```


Restituisce un iteratore java per l'intera collezione.

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVbaModule> - Un java.util.Iterator per l'intera collezione.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Copia tutti gli elementi dalla collezione nell'array specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array di destinazione. |
| index | int | Indice di partenza nell'array di destinazione. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Restituisce un valore che indica se l'accesso alla collezione è sincronizzato (thread-safe). Solo lettura boolean.

**Restituisce:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Restituisce una radice di sincronizzazione. Solo lettura Object.

**Restituisce:**
java.lang.Object