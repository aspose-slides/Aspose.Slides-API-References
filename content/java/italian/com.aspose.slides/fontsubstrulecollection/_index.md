---
title: FontSubstRuleCollection
second_title: Riferimento API di Aspose.Slides per Java
description: Rappresenta una collezione di sostituzioni di caratteri.
type: docs
url: /it/com.aspose.slides/fontsubstrulecollection/
---
**Eredità:**
java.lang.Object

**Tutte le interfacce implementate:**
[com.aspose.slides.IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)
```
public class FontSubstRuleCollection implements IFontSubstRuleCollection
```

Rappresenta una collezione di sostituzioni di caratteri.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [FontSubstRuleCollection()](#FontSubstRuleCollection--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [size()](#size--) | Restituisce il numero di elementi effettivamente contenuti nella collezione. |
| [add(IFontSubstRule value)](#add-com.aspose.slides.IFontSubstRule-) | Aggiunge la nuova regola di sostituzione di caratteri alla collezione |
| [remove(IFontSubstRule value)](#remove-com.aspose.slides.IFontSubstRule-) | Rimuove la prima occorrenza di un oggetto specifico dalla collezione. |
| [get_Item(int index)](#get-Item-int-) | Restituisce l'elemento all'indice specificato. |
| [iterator()](#iterator--) | Restituisce un enumeratore che itera attraverso la collezione. |
| [iteratorJava()](#iteratorJava--) | Restituisce un iteratore java per l'intera collezione. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copia tutti gli elementi dalla collezione all'array specificato. |
| [isSynchronized()](#isSynchronized--) | Restituisce un valore che indica se l'accesso alla collezione è sincronizzato (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Restituisce una radice di sincronizzazione. |
### FontSubstRuleCollection() {#FontSubstRuleCollection--}
```
public FontSubstRuleCollection()
```


### size() {#size--}
```
public final int size()
```


Restituisce il numero di elementi effettivamente contenuti nella collezione. int a sola lettura.

**Restituisce:**
int
### add(IFontSubstRule value) {#add-com.aspose.slides.IFontSubstRule-}
```
public final void add(IFontSubstRule value)
```


Aggiunge la nuova regola di sostituzione di caratteri alla collezione

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) |  |

### remove(IFontSubstRule value) {#remove-com.aspose.slides.IFontSubstRule-}
```
public final void remove(IFontSubstRule value)
```


Rimuove la prima occorrenza di un oggetto specifico dalla collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) | La regola di sostituzione di caratteri da rimuovere dalla collezione. |

### get_Item(int index) {#get-Item-int-}
```
public final IFontSubstRule get_Item(int index)
```


Restituisce l'elemento all'indice specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int |  |

**Restituisce:**
[IFontSubstRule](../../com.aspose.slides/ifontsubstrule)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IFontSubstRule> iterator()
```


Restituisce un enumeratore che itera attraverso la collezione.

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IFontSubstRule> - Un IGenericEnumerator che può essere usato per iterare attraverso la collezione.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IFontSubstRule> iteratorJava()
```


Restituisce un iteratore java per l'intera collezione.

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IFontSubstRule> - Un java.util.Iterator per l'intera collezione.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Copia tutti gli elementi dalla collezione all'array specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array di destinazione. |
| index | int | Indice di partenza nell'array di destinazione. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Restituisce un valore che indica se l'accesso alla collezione è sincronizzato (thread-safe). boolean a sola lettura.

**Restituisce:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Restituisce una radice di sincronizzazione. Object a sola lettura.

**Restituisce:**
java.lang.Object