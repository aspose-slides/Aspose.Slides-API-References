---
title: LayoutSlideCollection
second_title: Riferimento API Aspose.Slides per Java
description: Rappresenta una classe base per la collezione di diapositive di layout.
type: docs
url: /it/com.aspose.slides/layoutslidecollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.ILayoutSlideCollection](../../com.aspose.slides/ilayoutslidecollection), com.aspose.slides.IDOMObject
```
public class LayoutSlideCollection implements ILayoutSlideCollection, IDOMObject
```

Rappresenta una classe base per la collezione di diapositive di layout.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [size()](#size--) | Restituisce il numero di diapositive di layout in una collezione. |
| [get_Item(int index)](#get-Item-int-) | Restituisce la diapositiva di layout per indice. |
| [getByType(byte type)](#getByType-byte-) | Restituisce la prima diapositiva di layout del tipo specificato. |
| [remove(ILayoutSlide value)](#remove-com.aspose.slides.ILayoutSlide-) | Rimuove un layout dalla collezione. |
| [removeUnused()](#removeUnused--) | Rimuove le diapositive di layout inutilizzate (diapositive di layout il cui HasDependingSlides è false). |
| [iterator()](#iterator--) | Restituisce un enumeratore che itera attraverso la collezione. |
| [iteratorJava()](#iteratorJava--) | Restituisce un iteratore java per l'intera collezione. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copia tutti gli elementi dalla collezione nell'array specificato. |
| [isSynchronized()](#isSynchronized--) | Restituisce un valore che indica se l'accesso alla collezione è sincronizzato (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Restituisce la radice di sincronizzazione. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### size() {#size--}
```
public final int size()
```

Restituisce il numero di diapositive di layout in una collezione. Solo lettura int.

**Returns:**
int

### get_Item(int index) {#get-Item-int-}
```
public final ILayoutSlide get_Item(int index)
```

Restituisce la diapositiva di layout per indice. Solo lettura [LayoutSlide](../../com.aspose.slides/layoutslide).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int |  |

**Returns:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)

### getByType(byte type) {#getByType-byte-}
```
public final ILayoutSlide getByType(byte type)
```

Restituisce la prima diapositiva di layout del tipo specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| type | byte | Un tipo di diapositiva di layout da trovare. |

**Returns:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - [LayoutSlide](../../com.aspose.slides/layoutslide) con tipo specificato o null se non vengono trovati layout.

### remove(ILayoutSlide value) {#remove-com.aspose.slides.ILayoutSlide-}
```
public final void remove(ILayoutSlide value)
```

Rimuove un layout dalla collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Il layout slide da rimuovere dalla collezione.

1) Per evitare il lancio di PptxEditException controllare la proprietà HasDependingSlides del layout prima. 2) È possibile utilizzare anche il metodo [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) per semplificare il codice. |

### removeUnused() {#removeUnused--}
```
public final void removeUnused()
```

Rimuove le diapositive di layout inutilizzate (diapositive di layout il cui HasDependingSlides è false).

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ILayoutSlide> iterator()
```

Restituisce un enumeratore che itera attraverso la collezione.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ILayoutSlide> - Un IGenericEnumerator che può essere usato per iterare attraverso la collezione.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ILayoutSlide> iteratorJava()
```

Restituisce un iteratore java per l'intera collezione.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ILayoutSlide> - Un java.util.Iterator per l'intera collezione.

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

**Returns:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Restituisce la radice di sincronizzazione. Solo lettura Object.

**Returns:**
java.lang.Object

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Restituisce l'oggetto Parent_Immediate. Solo lettura IDOMObject.

**Returns:**
com.aspose.slides.IDOMObject