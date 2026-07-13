---
title: LayoutSlideCollection
second_title: Aspose.Slides pro Android prostřednictvím Java API Reference
description: Representuje základní třídu pro kolekci rozvržení snímků.
type: docs
url: /cs/com.aspose.slides/layoutslidecollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.ILayoutSlideCollection](../../com.aspose.slides/ilayoutslidecollection), com.aspose.slides.IDOMObject
```
public class LayoutSlideCollection implements ILayoutSlideCollection, IDOMObject
```

Representuje základní třídu pro kolekci rozvržení snímků.

## Metody

| Metoda | Popis |
| --- | --- |
| [size()](#size--) | Vrací počet rozvržení snímků v kolekci. |
| [get_Item(int index)](#get-Item-int-) | Vrací rozvržení snímku podle indexu. |
| [getByType(byte type)](#getByType-byte-) | Vrací první rozvržení snímku zadaného typu. |
| [remove(ILayoutSlide value)](#remove-com.aspose.slides.ILayoutSlide-) | Odstraňuje rozvržení z kolekce. |
| [removeUnused()](#removeUnused--) | Odstraňuje nepoužitá rozvržení snímků (rozvržení snímků, jejichž HasDependingSlides je false). |
| [iterator()](#iterator--) | Vrací enumerátor, který prochází kolekcí. |
| [iteratorJava()](#iteratorJava--) | Vrací java iterátor pro celou kolekci. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopíruje všechny prvky z kolekce do zadaného pole. |
| [isSynchronized()](#isSynchronized--) | Vrací hodnotu udávající, zda je přístup ke kolekci synchronizován (bezpečný pro vlákna). |
| [getSyncRoot()](#getSyncRoot--) | Vrací kořen synchronizace. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### size() {#size--}
```
public final int size()
```

Vrací počet rozvržení snímků v kolekci. Pouze ke čtení int.

**Vrací:**
int

### get_Item(int index) {#get-Item-int-}
```
public final ILayoutSlide get_Item(int index)
```

Vrací rozvržení snímku podle indexu. Pouze ke čtení [LayoutSlide](../../com.aspose.slides/layoutslide).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int |  |

**Vrací:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)

### getByType(byte type) {#getByType-byte-}
```
public final ILayoutSlide getByType(byte type)
```

Vrací první rozvržení snímku zadaného typu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| type | byte | Typ rozvržení snímku, který se má najít. |

**Vrací:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) – [LayoutSlide](../../com.aspose.slides/layoutslide) se zadaným typem nebo null, pokud nebyly nalezeny žádné rozvržení.

### remove(ILayoutSlide value) {#remove-com.aspose.slides.ILayoutSlide-}
```
public final void remove(ILayoutSlide value)
```

Odstraňuje rozvržení z kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Rozvržení snímku, které se má odstranit z kolekce.

--------------------

1) Aby nedošlo k vyhození výjimky PptxEditException, předtím zkontrolujte vlastnost HasDependingSlides rozvržení. 2) Můžete také použít metodu [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) pro zjednodušení kódu. |

### removeUnused() {#removeUnused--}
```
public final void removeUnused()
```

Odstraňuje nepoužitá rozvržení snímků (rozvržení snímků, jejichž HasDependingSlides je false).

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ILayoutSlide> iterator()
```

Vrací enumerátor, který prochází kolekcí.

**Vrací:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ILayoutSlide> – IGenericEnumerator, který lze použít k iteraci přes kolekci.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ILayoutSlide> iteratorJava()
```

Vrací java iterátor pro celou kolekci.

**Vrací:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ILayoutSlide> – java.util.Iterator pro celou kolekci.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Kopíruje všechny prvky z kolekce do zadaného pole.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Cílové pole. |
| index | int | Počáteční index v cílovém poli. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Vrací hodnotu udávající, zda je přístup ke kolekci synchronizován (bezpečný pro vlákna). Pouze ke čtení boolean.

**Vrací:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Vrací kořen synchronizace. Pouze ke čtení Object.

**Vrací:**
java.lang.Object

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Vrací objekt Parent_Immediate. Pouze ke čtení IDOMObject.

**Vrací:**
com.aspose.slides.IDOMObject