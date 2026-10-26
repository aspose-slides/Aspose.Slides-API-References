---
title: LayoutSlideCollection
second_title: Aspose.Slides pro Java API Reference
description: Reprezentuje základní třídu pro sbírku rozložení snímků.
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

Reprezentuje základní třídu pro sbírku rozložení snímků.
## Methods

| Metoda | Popis |
| --- | --- |
| [size()](#size--) | Vrací počet rozložení snímků ve sbírce. |
| [get_Item(int index)](#get-Item-int-) | Vrací rozložení snímku podle indexu. |
| [getByType(byte type)](#getByType-byte-) | Vrací první rozložení snímku zadaného typu. |
| [remove(ILayoutSlide value)](#remove-com.aspose.slides.ILayoutSlide-) | Odstraňuje rozložení ze sbírky. |
| [removeUnused()](#removeUnused--) | Odstraňuje nepoužitá rozložení snímků (rozložení snímků, jejichž HasDependingSlides je false). |
| [iterator()](#iterator--) | Vrací enumerátor, který prochází sbírku. |
| [iteratorJava()](#iteratorJava--) | Vrací java iterátor pro celou sbírku. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopíruje všechny prvky ze sbírky do zadaného pole. |
| [isSynchronized()](#isSynchronized--) | Vrací hodnotu naznačující, zda je přístup ke sbírce synchronizován (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Vrací kořen synchronizace. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### size() {#size--}
```
public final int size()
```

Vrací počet rozložení snímků ve sbírce. Read-only int.

**Vrací:**
int
### get_Item(int index) {#get-Item-int-}
```
public final ILayoutSlide get_Item(int index)
```

Vrací rozložení snímku podle indexu. Read-only [LayoutSlide](../../com.aspose.slides/layoutslide).

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

Vrací první rozložení snímku zadaného typu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| type | byte | Typ rozložení snímku, který se má najít. |

**Vrací:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - [LayoutSlide](../../com.aspose.slides/layoutslide) se zadaným typem nebo null, pokud nebyly nalezeny žádné rozložení.
### remove(ILayoutSlide value) {#remove-com.aspose.slides.ILayoutSlide-}
```
public final void remove(ILayoutSlide value)
```

Odstraňuje rozložení ze sbírky.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Rozložení snímku, které má být odebráno ze sbírky.

--------------------

1) Aby se zabránilo vyhození výjimky PptxEditException, zkontrolujte předtím vlastnost HasDependingSlides rozložení. 2) Můžete také použít metodu [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) pro zjednodušení kódu. |
### removeUnused() {#removeUnused--}
```
public final void removeUnused()
```

Odstraňuje nepoužitá rozložení snímků (rozložení snímků, jejichž HasDependingSlides je false).

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ILayoutSlide> iterator()
```

Vrací enumerátor, který prochází sbírku.

**Vrací:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ILayoutSlide> - IGenericEnumerator, který lze použít k iteraci přes sbírku.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ILayoutSlide> iteratorJava()
```

Vrací java iterátor pro celou sbírku.

**Vrací:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ILayoutSlide> - java.util.Iterator pro celou sbírku.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Kopíruje všechny prvky ze sbírky do zadaného pole.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Cílové pole. |
| index | int | Počáteční index v cílovém poli. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Vrací hodnotu naznačující, zda je přístup ke sbírce synchronizován (thread-safe). Read-only boolean.

**Vrací:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Vrací kořen synchronizace. Read-only Object.

**Vrací:**
java.lang.Object
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Vrací objekt Parent_Immediate. Read-only IDOMObject.

**Vrací:**
com.aspose.slides.IDOMObject