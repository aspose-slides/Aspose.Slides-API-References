---
title: ControlCollection
second_title: Riferimento API Aspose.Slides per Java
description: Una raccolta di controlli ActiveX.
type: docs
url: /it/com.aspose.slides/controlcollection/
---
**Ereditarietà:**
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
| [size()](#size--) | Restituisce il numero di oggetti nella raccolta. |
| [addControl(int controlType, float x, float y, float width, float height)](#addControl-int-float-float-float-float-) | Crea e aggiunge un nuovo controllo alla raccolta. |
| [remove(IControl item)](#remove-com.aspose.slides.IControl-) | Rimuove un controllo ActiveX dalla raccolta. |
| [removeAt(int index)](#removeAt-int-) | Rimuove un controllo ActiveX memorizzato nella posizione specificata dalla raccolta. |
| [clear()](#clear--) | Rimuove tutti i controlli dalla raccolta. |
| [get_Item(int index)](#get-Item-int-) | Restituisce un controllo nella posizione specificata. |
| [iterator()](#iterator--) | Restituisce un enumeratore che itera sulla raccolta. |
| [iteratorJava()](#iteratorJava--) | Restituisce un iteratore java per l'intera raccolta. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copia l'intera raccolta nell'array specificato. |
| [isSynchronized()](#isSynchronized--) | Restituisce un valore che indica se l'accesso alla raccolta è sincronizzato (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Restituisce la radice di sincronizzazione. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### size() {#size--}
```
public final int size()
```

Restituisce il numero di oggetti nella raccolta. Solo lettura int.

**Restituisce:**
int

### addControl(int controlType, float x, float y, float width, float height) {#addControl-int-float-float-float-float-}
```
public final IControl addControl(int controlType, float x, float y, float width, float height)
```

Crea e aggiunge un nuovo controllo alla raccolta.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| controlType | int | Tipo di controllo da aggiungere. |
| x | float | Coordinata X per il lato sinistro del frame della forma. |
| y | float | Coordinata Y per il lato superiore del frame della forma. |
| width | float | Larghezza del frame della forma. |
| height | float | Altezza del frame della forma. |

**Restituisce:**
[IControl](../../com.aspose.slides/icontrol) - Controllo creato.

### remove(IControl item) {#remove-com.aspose.slides.IControl-}
```
public final void remove(IControl item)
```

Rimuove un controllo ActiveX dalla raccolta.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| item | [IControl](../../com.aspose.slides/icontrol) | Un controllo da rimuovere. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Rimuove un controllo ActiveX memorizzato nella posizione specificata dalla raccolta.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice del controllo da rimuovere. |

### clear() {#clear--}
```
public final void clear()
```

Rimuove tutti i controlli dalla raccolta.

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

Restituisce un enumeratore che itera sulla raccolta.

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IControl> - Un IGenericEnumerator che può essere usato per iterare sulla raccolta.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IControl> iteratorJava()
```

Restituisce un iteratore java per l'intera raccolta.

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IControl> - Un java.util.Iterator per l'intera raccolta.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Copia l'intera raccolta nell'array specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array di destinazione |
| index | int | Indice nell'array di destinazione. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Restituisce un valore che indica se l'accesso alla raccolta è sincronizzato (thread-safe). Solo lettura boolean.

**Restituisce:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Restituisce la radice di sincronizzazione. Solo lettura Object.

**Restituisce:**
java.lang.Object

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Restituisce l'oggetto Parent_Immediate. Solo lettura IDOMObject.

**Restituisce:**
com.aspose.slides.IDOMObject