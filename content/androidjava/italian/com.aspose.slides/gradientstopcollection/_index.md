---
title: GradientStopCollection
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Rappresenta una collezione di gradient stop.
type: docs
url: /it/com.aspose.slides/gradientstopcollection/
---
**Eredità:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Tutte le interfacce implementate:**
[com.aspose.slides.IGradientStopCollection](../../com.aspose.slides/igradientstopcollection)
```
public final class GradientStopCollection extends PVIObject implements IGradientStopCollection
```

Rappresenta una collezione di gradient stop.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [size()](#size--) | Restituisce il numero di gradient stop in una collezione. |
| [get_Item(int index)](#get-Item-int-) | Restituisce il gradient stop per indice. |
| [add(float position, Integer color)](#add-float-java.lang.Integer-) | Crea un nuovo gradient stop e lo aggiunge alla fine della collezione. |
| [addPresetColor(float position, int presetColor)](#addPresetColor-float-int-) | Crea un nuovo gradient stop e lo aggiunge alla fine della collezione. |
| [addSchemeColor(float position, int schemeColor)](#addSchemeColor-float-int-) | Crea un nuovo gradient stop e lo aggiunge alla fine della collezione. |
| [insert(int index, float position, Integer color)](#insert-int-float-java.lang.Integer-) | Crea un nuovo gradient stop e lo inserisce all'indice specificato nella collezione. |
| [insertPresetColor(int index, float position, int presetColor)](#insertPresetColor-int-float-int-) | Crea un nuovo gradient stop e lo inserisce all'indice specificato nella collezione. |
| [insertSchemeColor(int index, float position, int schemeColor)](#insertSchemeColor-int-float-int-) | Crea un nuovo gradient stop e lo inserisce all'indice specificato nella collezione. |
| [removeAt(int index)](#removeAt-int-) | Rimuove un gradient stop all'indice specificato. |
| [clear()](#clear--) | Rimuove tutti i gradient stop da una collezione. |
| [iterator()](#iterator--) | Restituisce un enumeratore che itera attraverso la collezione. |
| [iteratorJava()](#iteratorJava--) | Restituisce un iterator java per l'intera collezione. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copia tutti gli elementi della collezione nell'array specificato. |
| [isSynchronized()](#isSynchronized--) | Restituisce un valore che indica se l'accesso alla collezione è sincronizzato (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Restituisce una radice di sincronizzazione. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

Versione. Solo lettura long.

**Restituisce:**
long
### size() {#size--}
```
public final int size()
```

Restituisce il numero di gradient stop in una collezione. Solo lettura int.

**Restituisce:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IGradientStop get_Item(int index)
```

Restituisce il gradient stop per indice.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int |  |

**Restituisce:**
[IGradientStop](../../com.aspose.slides/igradientstop)
### add(float position, Integer color) {#add-float-java.lang.Integer-}
```
public final IGradientStop add(float position, Integer color)
```

Crea un nuovo gradient stop e lo aggiunge alla fine della collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| position | float | Posizione del nuovo gradient stop. |
| color | java.lang.Integer | Colore del nuovo gradient stop. |

**Restituisce:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Indice del nuovo gradient stop nella collezione.
### addPresetColor(float position, int presetColor) {#addPresetColor-float-int-}
```
public final IGradientStop addPresetColor(float position, int presetColor)
```

Crea un nuovo gradient stop e lo aggiunge alla fine della collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| position | float | Posizione del nuovo gradient stop. |
| presetColor | int | Colore del nuovo gradient stop. |

**Restituisce:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Indice del nuovo gradient stop nella collezione.
### addSchemeColor(float position, int schemeColor) {#addSchemeColor-float-int-}
```
public final IGradientStop addSchemeColor(float position, int schemeColor)
```

Crea un nuovo gradient stop e lo aggiunge alla fine della collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| position | float | Posizione del nuovo gradient stop. |
| schemeColor | int | Colore del nuovo gradient stop. |

**Restituisce:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Indice del nuovo gradient stop nella collezione.
### insert(int index, float position, Integer color) {#insert-int-float-java.lang.Integer-}
```
public final void insert(int index, float position, Integer color)
```

Crea un nuovo gradient stop e lo inserisce all'indice specificato nella collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice nella collezione dove il nuovo gradient stop verrà inserito. |
| position | float | Posizione del nuovo gradient stop. |
| color | java.lang.Integer | Colore del nuovo gradient stop. |
### insertPresetColor(int index, float position, int presetColor) {#insertPresetColor-int-float-int-}
```
public final void insertPresetColor(int index, float position, int presetColor)
```

Crea un nuovo gradient stop e lo inserisce all'indice specificato nella collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice nella collezione dove il nuovo gradient stop verrà inserito. |
| position | float | Posizione del nuovo gradient stop. |
| presetColor | int | Colore del nuovo gradient stop. |
### insertSchemeColor(int index, float position, int schemeColor) {#insertSchemeColor-int-float-int-}
```
public final void insertSchemeColor(int index, float position, int schemeColor)
```

Crea un nuovo gradient stop e lo inserisce all'indice specificato nella collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice nella collezione dove il nuovo gradient stop verrà inserito. |
| position | float | Posizione del nuovo gradient stop. |
| schemeColor | int | Colore del nuovo gradient stop. |
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Rimuove un gradient stop all'indice specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice del gradient stop da eliminare. |
### clear() {#clear--}
```
public final void clear()
```

Rimuove tutti i gradient stop da una collezione.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IGradientStop> iterator()
```

Restituisce un enumeratore che itera attraverso la collezione.

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IGradientStop> - Un IGenericEnumerator che può essere usato per iterare attraverso la collezione.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IGradientStop> iteratorJava()
```

Restituisce un iterator java per l'intera collezione.

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IGradientStop> - Un java.util.Iterator per l'intera collezione.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Copia tutti gli elementi della collezione nell'array specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array di destinazione. |
| index | int | Indice iniziale nell'array di destinazione. |
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