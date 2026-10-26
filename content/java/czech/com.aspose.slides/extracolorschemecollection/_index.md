---
title: ExtraColorSchemeCollection
second_title: Aspose.Slides pro Java – reference API
description: Reprezentuje kolekci dalších barevných schémat.
type: docs
url: /cs/com.aspose.slides/extracolorschemecollection/
---
**Dědičnost:**
java.lang.Object

**Všechna implementovaná rozhraní:**
[com.aspose.slides.IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection), com.aspose.slides.IDOMObject
```
public class ExtraColorSchemeCollection implements IExtraColorSchemeCollection, IDOMObject
```

Reprezentuje kolekci dalších barevných schémat.
## Metody

| Metoda | Popis |
| --- | --- |
| [size()](#size--) | Vrací počet prvků v kolekci. |
| [get_Item(int index)](#get-Item-int-) | Vrací barevné schéma podle indexu. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [iterator()](#iterator--) | Vrací enumerátor, který prochází kolekcí. |
| [iteratorJava()](#iteratorJava--) | Vrací java iterator pro celou kolekci. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Zkopíruje všechny prvky kolekce do zadaného pole. |
| [isSynchronized()](#isSynchronized--) | Vrací hodnotu indikující, zda je přístup k ArrayList synchronizován (vláknově bezpečný). |
| [getSyncRoot()](#getSyncRoot--) | Vrací objekt, který lze použít k synchronizaci přístupu ke kolekci. |
### size() {#size--}
```
public final int size()
```

Vrací počet prvků v kolekci. Pouze pro čtení int.

**Vrací:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IExtraColorScheme get_Item(int index)
```

Vrací barevné schéma podle indexu. Pouze pro čtení [ExtraColorScheme](../../com.aspose.slides/extracolorscheme).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int |  |

**Vrací:**
[IExtraColorScheme](../../com.aspose.slides/iextracolorscheme)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Vrací objekt Parent_Immediate. Pouze pro čtení IDOMObject.

**Vrací:**
com.aspose.slides.IDOMObject
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IExtraColorScheme> iterator()
```

Vrací enumerátor, který prochází kolekcí.

**Vrací:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IExtraColorScheme> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IExtraColorScheme> iteratorJava()
```

Vrací java iterator pro celou kolekci.

**Vrací:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IExtraColorScheme> - An java.util.Iterator for the entire collection.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Zkopíruje všechny prvky kolekce do zadaného pole.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Cílové pole. |
| index | int | Počáteční index v poli. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Vrací hodnotu indikující, zda je přístup k ArrayList synchronizován (vláknově bezpečný). Pouze pro čtení boolean.

**Vrací:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Vrací objekt, který lze použít k synchronizaci přístupu ke kolekci. Pouze pro čtení Object.

Vrací kořen synchronizace. Pouze pro čtení Object.

**Vrací:**
java.lang.Object