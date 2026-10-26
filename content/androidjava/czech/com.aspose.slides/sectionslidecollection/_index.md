---
title: SectionSlideCollection
second_title: Aspose.Slides pro Android pomocí Java API Reference
description: Reprezentuje kolekci snímků v sekci.
type: docs
url: /cs/com.aspose.slides/sectionslidecollection/
---
**Dědičnost:**
java.lang.Object, com.aspose.slides.DomObject

**Všechny implementované rozhraní:**
[com.aspose.slides.ISectionSlideCollection](../../com.aspose.slides/isectionslidecollection)
```
public final class SectionSlideCollection extends DomObject<Section> implements ISectionSlideCollection
```

Representuje kolekci snímků v sekci.
## Metody

| Metoda | Popis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Vrací prvek na zadaném indexu. |
| [size()](#size--) | Vrací počet prvků skutečně obsažených ve kolekci. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Zkopíruje celou kolekci do zadaného pole. |
| [isSynchronized()](#isSynchronized--) | Vrací hodnotu indikující, zda je přístup ke kolekci synchronizován (vláknově bezpečný). |
| [getSyncRoot()](#getSyncRoot--) | Vrací kořen synchronizace. |
| [iterator()](#iterator--) | Vrací enumerátor, který prochází kolekcí. |
| [iteratorJava()](#iteratorJava--) | Vrací java iterator pro celou kolekci. |
### get_Item(int index) {#get-Item-int-}
```
public final ISlide get_Item(int index)
```

Vrací prvek na zadaném indexu. Pouze ke čtení [ISlide](../../com.aspose.slides/islide).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int |  |

**Návratová hodnota:**
[ISlide](../../com.aspose.slides/islide)
### size() {#size--}
```
public final int size()
```

Vrací počet prvků skutečně obsažených ve kolekci. Pouze ke čtení int.

**Návratová hodnota:**
int
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Zkopíruje celou kolekci do zadaného pole.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Cílové pole |
| index | int | Index v cílovém poli. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Vrací hodnotu indikující, zda je přístup ke kolekci synchronizován (vláknově bezpečný). Pouze ke čtení boolean.

**Návratová hodnota:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Vrací kořen synchronizace. Pouze ke čtení Object.

**Návratová hodnota:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISlide> iterator()
```

Vrací enumerátor, který prochází kolekcí.

**Návratová hodnota:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISlide> - IGenericEnumerator, který lze použít k iteraci přes kolekci.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISlide> iteratorJava()
```

Vrací java iterator pro celou kolekci.

**Návratová hodnota:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISlide> - java.util.Iterator pro celou kolekci.