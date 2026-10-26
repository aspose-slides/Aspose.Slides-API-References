---
title: TabCollection
second_title: Aspose.Slides pro Java – reference API
description: Reprezentuje kolekci tabulátorů.
type: docs
url: /cs/com.aspose.slides/tabcollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.ITabCollection](../../com.aspose.slides/itabcollection), com.aspose.slides.IDOMObject
```
public final class TabCollection implements ITabCollection, IDOMObject
```

Represents a collection of tabs.
## Methods

| Metoda | Popis |
| --- | --- |
| [size()](#size--) | Vrací počet prvků skutečně obsažených v kolekci. |
| [get_Item(int index)](#get-Item-int-) | Vrací prvek na zadaném indexu. |
| [add(double position, int align)](#add-double-int-) | Přidá Tab do kolekce. |
| [add(ITab value)](#add-com.aspose.slides.ITab-) | Přidá Tab do kolekce. |
| [clear()](#clear--) | Odstraní všechny prvky z kolekce. |
| [removeAt(int index)](#removeAt-int-) | Odstraní prvek na zadaném indexu v kolekci. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Určuje, zda jsou dva objekty TabsEx rovny. |
| [iterator()](#iterator--) | Vrací enumerátor, který prochází kolekcí. |
| [iteratorJava()](#iteratorJava--) | Vrací java iterator pro celou kolekci. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Zkopíruje všechny prvky z kolekce do zadaného pole. |
| [isSynchronized()](#isSynchronized--) | Vrací hodnotu udávající, zda je přístup ke kolekci synchronizován (vláknově bezpečný). |
| [getSyncRoot()](#getSyncRoot--) | Vrací kořen synchronizace. |
### size() {#size--}
```
public final int size()
```


Vrací počet prvků skutečně obsažených v kolekci. Pouze ke čtení int.

**Vrací:**
int
### get_Item(int index) {#get-Item-int-}
```
public final ITab get_Item(int index)
```


Vrací prvek na zadaném indexu. Pouze ke čtení [Tab](../../com.aspose.slides/tab).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int |  |

**Vrací:**
[ITab](../../com.aspose.slides/itab)
### add(double position, int align) {#add-double-int-}
```
public final ITab add(double position, int align)
```


Přidá Tab do kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| position | double |  |
| align | int |  |

**Vrací:**
[ITab](../../com.aspose.slides/itab) - Přidaná záložka.
### add(ITab value) {#add-com.aspose.slides.ITab-}
```
public final int add(ITab value)
```


Přidá Tab do kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [ITab](../../com.aspose.slides/itab) | Objekt Tab, který bude přidán na konec kolekce. |

**Vrací:**
int - Index, na kterém byla záložka přidána.
### clear() {#clear--}
```
public final void clear()
```


Odstraní všechny prvky z kolekce.

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Odstraní prvek na zadaném indexu v kolekci.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Nulový index prvku, který má být odstraněn. |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Vrací objekt Parent_Immediate. Pouze ke čtení IDOMObject.

**Vrací:**
com.aspose.slides.IDOMObject
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Určuje, zda jsou dva objekty TabsEx rovny.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | java.lang.Object | Objekt TabsEx, se kterým se porovnává aktuální TabsEx. |

**Vrací:**
boolean - **true** pokud je zadaný TabsEx roven aktuálnímu TabsEx; jinak **false**.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ITab> iterator()
```


Vrací enumerátor, který prochází kolekcí.

**Vrací:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITab> - IGenericEnumerator, který lze použít k iteraci přes kolekci.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ITab> iteratorJava()
```


Vrací java iterator pro celou kolekci.

**Vrací:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ITab> - java.util.Iterator pro celou kolekci.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Zkopíruje všechny prvky z kolekce do zadaného pole.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Cílové pole. |
| index | int | Počáteční index v cílovém poli. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Vrací hodnotu udávající, zda je přístup ke kolekci synchronizován (vláknově bezpečný). Pouze ke čtení boolean.

**Vrací:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Vrací kořen synchronizace. Pouze ke čtení Object.

**Vrací:**
java.lang.Object