---
title: ControlCollection
second_title: Riferimento API Java di Aspose.Slides per Android
description: Una raccolta di controlli ActiveX.
type: docs
url: /it/com.aspose.slides/controlcollection/
---
**Eredità:**
java.lang.Object

**Tutte le interfacce implementate:**
[com.aspose.slides.IControlCollection](../../com.aspose.slides/icontrolcollection), com.aspose.slides.IDOMObject
```
public class ControlCollection implements IControlCollection, IDOMObject
```

Una raccolta di controlli ActiveX.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [size()](#size--) | Restituisce il numero di oggetti nella collezione. |
| [addControl(int controlType, float x, float y, float width, float height)](#addControl-int-float-float-float-float-) | Crea e aggiunge un nuovo controllo alla collezione. |
| [remove(IControl item)](#remove-com.aspose.slides.IControl-) | Rimuove un controllo ActiveX dalla collezione. |
| [removeAt(int index)](#removeAt-int-) | Rimuove un controllo ActiveX memorizzato nella posizione specificata dalla collezione. |
| [clear()](#clear--) | Rimuove tutti i controlli dalla collezione. |
| [get_Item(int index)](#get-Item-int-) | Restituisce un controllo nella posizione specificata. |
| [iterator()](#iterator--) | Restituisce un enumeratore che itera attraverso la collezione. |
| [iteratorJava()](#iteratorJava--) | Restituisce un iteratore java per l'intera collezione. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copia l'intera collezione nell'array specificato. |
| [isSynchronized()](#isSynchronized--) | Restituisce un valore che indica se l'accesso alla collezione è sincronizzato (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Restituisce una radice di sincronizzazione. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### size() {#size--}
```
public final int size()
```

Restituisce il numero di oggetti nella collezione. Solo lettura int.

**Restituisce:**
int

### addControl(int controlType, float x, float y, float width, float height) {#addControl-int-float-float-float-float-}
```
public final IControl addControl(int controlType, float x, float y, float width, float height)
```

Crea e aggiunge un nuovo controllo alla collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| controlType | int | Tipo di controllo da aggiungere. |
| x | float | La coordinata X per il lato sinistro della cornice della forma. |
| y | float | La coordinata Y per il lato superiore della cornice della forma. |
| width | float | La larghezza della cornice della forma. |
| height | float | L'altezza della cornice della forma. |

**Restituisce:**
[IControl](../../com.aspose.slides/icontrol) - Controllo creato.

### remove(IControl item) {#remove-com.aspose.slides.IControl-}
```
public final void remove(IControl item)
```

Rimuove un controllo ActiveX dalla collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| item | [IControl](../../com.aspose.slides/icontrol) | Un controllo da rimuovere. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Rimuove un controllo ActiveX memorizzato nella posizione specificata dalla collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice del controllo da rimuovere. |

### clear() {#clear--}
```
public final void clear()
```

Rimuove tutti i controlli dalla collezione.

### get_Item(int index) {#get-Item-int-}
```
public final IControl get_Item(int index)
```

Restituisce un controllo nella posizione specificata.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice del controllo. |

**Restituisce:**
[IControl](../../com.aspose.slides/icontrol)

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IControl> iterator()
```

Restituisce un enumeratore che itera attraverso la collezione.

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IControl> - Un IGenericEnumerator che può essere usato per iterare attraverso la collezione.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IControl> iteratorJava()
```

Restituisce un iteratore java per l'intera collezione.

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IControl> - Un java.util.Iterator per l'intera collezione.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Copia l'intera collezione nell'array specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array di destinazione |
| index | int | Indice nell'array di destinazione. |

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

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Restituisce l'oggetto Parent_Immediate. Solo lettura IDOMObject.

**Restituisce:**
com.aspose.slides.IDOMObject