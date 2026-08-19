---
title: SectionSlideCollection
second_title: Aspose.Slides pro Java – referenční příručka API
description: Představuje kolekci snímků v sekci.
type: docs
url: /cs/com.aspose.slides/sectionslidecollection/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.ISectionSlideCollection](../../com.aspose.slides/isectionslidecollection)
```
public final class SectionSlideCollection extends DomObject<Section> implements ISectionSlideCollection
```

Represents a collection of slides in the section.
## Metody

| Metoda | Popis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Získá prvek na zadaném indexu. |
| [size()](#size--) | Získá počet prvků ve skutečnosti obsažených ve sbírce. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Zkopíruje celou sbírku do zadaného pole. |
| [isSynchronized()](#isSynchronized--) | Vrací hodnotu udávající, zda je přístup ke sbírce synchronizován (vláknově bezpečný). |
| [getSyncRoot()](#getSyncRoot--) | Vrací kořen synchronizace. |
| [iterator()](#iterator--) | Vrací enumerátor, který prochází sbírku. |
| [iteratorJava()](#iteratorJava--) | Vrací java iterátor pro celou sbírku. |
### get_Item(int index) {#get-Item-int-}
```
public final ISlide get_Item(int index)
```


Získá prvek na zadaném indexu. Pouze ke čtení [ISlide](../../com.aspose.slides/islide).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int |  |

**Vrací:**
[ISlide](../../com.aspose.slides/islide)
### size() {#size--}
```
public final int size()
```


Získá počet prvků ve skutečnosti obsažených ve sbírce. Pouze ke čtení int.

**Vrací:**
int
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Zkopíruje celou sbírku do zadaného pole.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Cílové pole |
| index | int | Index v cílovém poli. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Vrací hodnotu udávající, zda je přístup ke sbírce synchronizován (vláknově bezpečný). Pouze ke čtení boolean.

**Vrací:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Vrací kořen synchronizace. Pouze ke čtení Object.

**Vrací:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISlide> iterator()
```


Vrací enumerátor, který prochází sbírku.

**Vrací:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISlide> - IGenericEnumerator, který lze použít k iteraci přes sbírku.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISlide> iteratorJava()
```


Vrací java iterátor pro celou sbírku.

**Vrací:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISlide> - java.util.Iterator pro celou sbírku.